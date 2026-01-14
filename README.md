# Petersons-spec.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Artistry - Contemporary Art Gallery</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Inter:wght@400;500;600&display=swap" rel="stylesheet">
    <style>
        * {
            --font-display: 'Playfair Display', serif;
            --font-body: 'Inter', sans-serif;
        }
        
        h1, h2, h3 { font-family: var(--font-display); }
        body { font-family: var(--font-body); }
    </style>
</head>
<body class="bg-white text-gray-900">
    <!-- Header -->
    <header class="border-b border-gray-200">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-6 flex items-center justify-between">
            <h1 class="text-2xl font-bold tracking-tight">ARTISTRY</h1>
            <ul class="hidden md:flex gap-8">
                <li><a href="#gallery" class="text-sm hover:text-amber-700 transition">Gallery</a></li>
                <li><a href="#about" class="text-sm hover:text-amber-700 transition">About</a></li>
                <li><a href="#contact" class="text-sm hover:text-amber-700 transition">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20 md:py-32 text-center">
        <h2 class="text-5xl md:text-7xl font-bold mb-6 leading-tight text-pretty">
            Where Vision Becomes Art
        </h2>
        <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-8 leading-relaxed">
            Discover curated contemporary artworks that challenge, inspire, and transform. Explore our collection of emerging and established artists.
        </p>
        <button class="bg-amber-700 text-white px-8 py-3 font-medium hover:bg-amber-800 transition">
            Explore Gallery
        </button>
    </section>

    <!-- Featured Works -->
    <section id="gallery" class="bg-gray-50 py-20">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <h2 class="text-4xl font-bold mb-12 text-center">Featured Works</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Work 1 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="bg-gradient-to-br from-blue-400 to-blue-600 h-64"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Ethereal Dreams</h3>
                        <p class="text-gray-600 text-sm mb-4">By Sarah Chen</p>
                        <p class="text-gray-700 text-sm leading-relaxed">Contemporary exploration of consciousness and emotion through abstract forms.</p>
                    </div>
                </div>

                <!-- Work 2 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="bg-gradient-to-br from-amber-300 to-orange-500 h-64"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Urban Poetry</h3>
                        <p class="text-gray-600 text-sm mb-4">By Marcus Rodriguez</p>
                        <p class="text-gray-700 text-sm leading-relaxed">Vibrant urban landscapes capturing the pulse of modern city life.</p>
                    </div>
                </div>

                <!-- Work 3 -->
                <div class="bg-white rounded-lg overflow-hidden shadow-lg hover:shadow-xl transition">
                    <div class="bg-gradient-to-br from-slate-400 to-slate-700 h-64"></div>
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Solitude</h3>
                        <p class="text-gray-600 text-sm mb-4">By Elena Moretti</p>
                        <p class="text-gray-700 text-sm leading-relaxed">Minimalist study of space, light, and the human condition.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
        <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
            <div>
                <h2 class="text-4xl font-bold mb-6">About Artistry</h2>
                <p class="text-gray-700 mb-4 leading-relaxed">
                    For over a decade, Artistry has been a premier destination for contemporary art collectors and enthusiasts. We showcase emerging voices and established masters, bridging the gap between artists and art lovers worldwide.
                </p>
                <p class="text-gray-700 leading-relaxed">
                    Our carefully curated collections celebrate diversity, innovation, and the transformative power of creative expression. Each piece tells a story worth sharing.
                </p>
            </div>
            <div class="bg-gradient-to-br from-purple-300 to-pink-300 rounded-lg h-80"></div>
        </div>
    </section>

    <!-- Newsletter -->
    <section class="bg-gray-900 text-white py-16">
        <div class="max-w-2xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-4">Stay Inspired</h2>
            <p class="text-gray-300 mb-8">Get updates on new exhibitions, artist features, and exclusive previews.</p>
            <form class="flex flex-col sm:flex-row gap-3">
                <input 
                    type="email" 
                    placeholder="Enter your email" 
                    required
                    class="flex-1 px-4 py-3 rounded text-gray-900 focus:outline-none focus:ring-2 focus:ring-amber-600"
                    aria-label="Email address"
                />
                <button 
                    type="submit" 
                    class="bg-amber-700 hover:bg-amber-800 text-white px-8 py-3 rounded font-medium transition"
                >
                    Subscribe
                </button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer id="contact" class="border-t border-gray-200 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div>
                    <h3 class="font-bold mb-4">About</h3>
                    <ul class="space-y-2 text-sm text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Our Story</a></li>
                        <li><a href="#" class="hover:text-gray-900">Artists</a></li>
                        <li><a href="#" class="hover:text-gray-900">Team</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold mb-4">Gallery</h3>
                    <ul class="space-y-2 text-sm text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Collections</a></li>
                        <li><a href="#" class="hover:text-gray-900">Exhibitions</a></li>
                        <li><a href="#" class="hover:text-gray-900">Events</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold mb-4">Support</h3>
                    <ul class="space-y-2 text-sm text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Contact</a></li>
                        <li><a href="#" class="hover:text-gray-900">FAQ</a></li>
                        <li><a href="#" class="hover:text-gray-900">Shipping</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold mb-4">Follow</h3>
                    <ul class="space-y-2 text-sm text-gray-600">
                        <li><a href="#" class="hover:text-gray-900">Instagram</a></li>
                        <li><a href="#" class="hover:text-gray-900">Twitter</a></li>
                        <li><a href="#" class="hover:text-gray-900">LinkedIn</a></li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-200 pt-8 text-center text-sm text-gray-600">
                <p>&copy; 2025 Artistry Gallery. All rights reserved.</p>
            </div>
        </div>
    </footer>
</body>
</html>
