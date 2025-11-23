<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LaunchPad - Your Free Website</title>
    <!-- Load Tailwind CSS from CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Use Inter font family -->
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- 1. Navigation Bar (Always visible and sticky) -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo -->
                <a href="#hero" class="text-2xl font-bold text-indigo-600 hover:text-indigo-800 transition duration-300">
                    LaunchPad
                </a>

                <!-- Desktop Navigation Links -->
                <nav class="hidden md:flex space-x-8">
                    <a href="#features" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300">Features</a>
                    <a href="#about" class="text-gray-600 hover:text-indigo-600 font-medium transition duration-300">About Us</a>
                    <a href="#contact" class="text-white bg-indigo-600 hover:bg-indigo-700 px-4 py-2 rounded-lg text-sm font-semibold shadow-md transition duration-300">Get Started</a>
                </nav>

                <!-- Mobile Menu Button -->
                <button id="menu-button" class="md:hidden text-gray-600 hover:text-indigo-600 focus:outline-none">
                    <!-- Icon SVG for Menu (Hamburger) -->
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
                </button>
            </div>
        </div>

        <!-- Mobile Menu (Hidden by default) -->
        <div id="mobile-menu" class="hidden md:hidden bg-white shadow-lg border-t border-gray-100">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#features" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-50">Features</a>
                <a href="#about" class="block px-3 py-2 rounded-md text-base font-medium text-gray-700 hover:bg-gray-50">About Us</a>
                <a href="#contact" class="block w-full text-center px-3 py-2 rounded-md text-base font-medium text-white bg-indigo-600 hover:bg-indigo-700 mt-2">Get Started</a>
            </div>
        </div>
    </header>

    <main>
        <!-- 2. Hero Section -->
        <section id="hero" class="pt-16 pb-20 md:pt-24 md:pb-32 bg-white text-center">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-gray-900 leading-tight mb-4">
                    Launch Your <span class="text-indigo-600">Free Website</span> Today.
                </h1>
                <p class="mt-4 text-xl text-gray-500 max-w-3xl mx-auto">
                    A professional platform built with simplicity and speed in mind. Focus on your content, we handle the design.
                </p>
                <div class="mt-10 flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-6">
                    <a href="#contact" class="inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-xl shadow-lg text-white bg-indigo-600 hover:bg-indigo-700 transform hover:scale-105 transition duration-300 ease-in-out">
                        Start Building Now
                    </a>
                    <a href="#features" class="inline-flex items-center justify-center px-8 py-3 border border-indigo-200 text-base font-medium rounded-xl text-indigo-700 bg-indigo-100 hover:bg-indigo-200 transition duration-300">
                        Explore Features
                    </a>
                </div>

                <!-- Mockup Image Placeholder -->
                <div class="mt-16 w-full max-w-4xl mx-auto">
                    <img src="https://placehold.co/1000x500/e0e7ff/4338ca?text=Modern+Website+Design+Mockup" 
                         alt="Website mockup showing responsive design"
                         class="rounded-2xl shadow-2xl ring-4 ring-indigo-500/50"
                         onerror="this.onerror=null; this.src='https://placehold.co/1000x500/e0e7ff/4338ca?text=Responsive+Design+View';">
                </div>
            </div>
        </section>

        <!-- 3. Features/Services Section -->
        <section id="features" class="py-16 bg-gray-100">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="text-center">
                    <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                        Everything You Need, Built-In.
                    </h2>
                    <p class="mt-4 text-xl text-gray-500">
                        From mobile responsiveness to lightning-fast performance.
                    </p>
                </div>

                <div class="mt-12 grid grid-cols-1 gap-8 sm:grid-cols-2 lg:grid-cols-3">
                    <!-- Feature 1 -->
                    <div class="pt-6">
                        <div class="flow-root bg-white rounded-xl px-6 pb-8 shadow-lg h-full transition duration-300 hover:shadow-xl hover:scale-[1.02]">
                            <div class="mt-6">
                                <div class="p-3 inline-flex items-center justify-center rounded-full bg-indigo-500 text-white shadow-lg">
                                    <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 18h.01M8 21h8a2 2 0 002-2V5a2 2 0 00-2-2H8a2 2 0 00-2 2v14a2 2 0 002 2z"></path></svg>
                                </div>
                                <h3 class="mt-4 text-lg font-semibold text-gray-900">Fully Responsive</h3>
                                <p class="mt-2 text-base text-gray-500">
                                    Looks perfect on any device, from small phones to large desktops. Optimized for touch interactions.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Feature 2 -->
                    <div class="pt-6">
                        <div class="flow-root bg-white rounded-xl px-6 pb-8 shadow-lg h-full transition duration-300 hover:shadow-xl hover:scale-[1.02]">
                            <div class="mt-6">
                                <div class="p-3 inline-flex items-center justify-center rounded-full bg-indigo-500 text-white shadow-lg">
                                    <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                                </div>
                                <h3 class="mt-4 text-lg font-semibold text-gray-900">Blazing Fast Load Times</h3>
                                <p class="mt-2 text-base text-gray-500">
                                    Built with lean, efficient code to ensure your site loads instantly, keeping visitors engaged.
                                </p>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Feature 3 -->
                    <div class="pt-6">
                        <div class="flow-root bg-white rounded-xl px-6 pb-8 shadow-lg h-full transition duration-300 hover:shadow-xl hover:scale-[1.02]">
                            <div class="mt-6">
                                <div class="p-3 inline-flex items-center justify-center rounded-full bg-indigo-500 text-white shadow-lg">
                                    <svg class="h-6 w-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 7v10M10 5l4 4m0 0l4 4m-4-4v10m-4-4l4 4m0 0l4-4"></path></svg>
                                </div>
                                <h3 class="mt-4 text-lg font-semibold text-gray-900">Easy to Customize</h3>
                                <p class="mt-2 text-base text-gray-500">
                                    Uses Tailwind CSS, making it simple to change colors, fonts, and layouts with minimal effort.
                                </p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. About Section -->
        <section id="about" class="py-16">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <div class="lg:flex lg:items-center lg:justify-between">
                    <div class="lg:w-1/2">
                        <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                            Our Mission: Empowering Creators
                        </h2>
                        <p class="mt-4 text-lg text-gray-500">
                            We believe that everyone deserves a high-quality online presence without the high cost. This template is designed to cut through the complexity, providing a robust starting point for developers, small businesses, and personal portfolios.
                        </p>
                        <ul class="mt-8 space-y-4 text-lg text-gray-600">
                            <li class="flex items-start">
                                <svg class="flex-shrink-0 h-6 w-6 text-indigo-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span>100% Free and Open Source code.</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="flex-shrink-0 h-6 w-6 text-indigo-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span>No hidden fees, no required sign-ups.</span>
                            </li>
                            <li class="flex items-start">
                                <svg class="flex-shrink-0 h-6 w-6 text-indigo-500 mr-2" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 13l4 4L19 7"></path></svg>
                                <span>Built on modern, accessible web standards.</span>
                            </li>
                        </ul>
                    </div>
                    <div class="mt-10 lg:mt-0 lg:w-5/12">
                        <img class="rounded-2xl shadow-xl transform hover:scale-[1.01] transition duration-500" 
                             src="https://placehold.co/500x350/a5b4fc/4338ca?text=Growth+%26+Innovation" 
                             alt="Abstract image representing growth"
                             onerror="this.onerror=null; this.src='https://placehold.co/500x350/a5b4fc/4338ca?text=Abstract+Concept';">
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. Contact Section -->
        <section id="contact" class="py-16 bg-indigo-50">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <h2 class="text-3xl font-extrabold text-gray-900 sm:text-4xl">
                    Ready to Launch?
                </h2>
                <p class="mt-4 text-lg text-gray-600">
                    Get in touch with the team or download the source code immediately below.
                </p>

                <div class="mt-8 bg-white p-8 rounded-xl shadow-2xl">
                    <form action="#" method="POST" class="space-y-6">
                        <div>
                            <label for="name" class="block text-left text-sm font-medium text-gray-700">Name</label>
                            <input type="text" id="name" name="name" required
                                   class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 transition duration-150"
                                   placeholder="Your Name">
                        </div>
                        <div>
                            <label for="email" class="block text-left text-sm font-medium text-gray-700">Email</label>
                            <input type="email" id="email" name="email" required
                                   class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 transition duration-150"
                                   placeholder="you@example.com">
                        </div>
                        <div>
                            <label for="message" class="block text-left text-sm font-medium text-gray-700">Message</label>
                            <textarea id="message" name="message" rows="4" required
                                      class="mt-1 block w-full px-4 py-2 border border-gray-300 rounded-lg shadow-sm focus:ring-indigo-500 focus:border-indigo-500 transition duration-150"
                                      placeholder="Tell us about your project..."></textarea>
                        </div>
                        <button type="submit" 
                                class="w-full inline-flex justify-center items-center px-6 py-3 border border-transparent text-base font-medium rounded-xl shadow-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500 transition duration-300">
                            Send Message
                        </button>
                    </form>
                    <p class="mt-4 text-xs text-gray-400">
                        *Note: This is a static HTML form. You will need a backend service (like Formspree or Netlify Forms) to actually receive the messages.
                    </p>
                </div>
            </div>
        </section>
    </main>

    <!-- 6. Footer -->
    <footer class="bg-gray-800 text-white">
        <div class="max-w-7xl mx-auto py-8 px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 gap-8 md:grid-cols-4 lg:grid-cols-6">
                <!-- Column 1 -->
                <div class="col-span-2 md:col-span-1">
                    <h4 class="text-xl font-bold text-indigo-400">LaunchPad</h4>
                    <p class="mt-4 text-sm text-gray-400">&copy; 2025 All rights reserved.</p>
                </div>

                <!-- Column 2 (Links) -->
                <div>
                    <h5 class="text-md font-semibold text-white mb-2">Sections</h5>
                    <ul class="space-y-2">
                        <li><a href="#hero" class="text-sm text-gray-400 hover:text-indigo-400 transition duration-300">Home</a></li>
                        <li><a href="#features" class="text-sm text-gray-400 hover:text-indigo-400 transition duration-300">Features</a></li>
                        <li><a href="#about" class="text-sm text-gray-400 hover:text-indigo-400 transition duration-300">About</a></li>
                        <li><a href="#contact" class="text-sm text-gray-400 hover:text-indigo-400 transition duration-300">Contact</a></li>
                    </ul>
                </div>
            </div>

            <div class="mt-8 border-t border-gray-700 pt-8 text-center">
                <p class="text-sm text-gray-500">
                    Built for free with HTML, Tailwind CSS, and pure JavaScript.
                </p>
            </div>
        </div>
    </footer>


    <!-- JavaScript for Mobile Menu Toggle -->
    <script>
        document.addEventListener('DOMContentLoaded', () => {
            const menuButton = document.getElementById('menu-button');
            const mobileMenu = document.getElementById('mobile-menu');

            // Function to toggle the mobile menu visibility
            function toggleMenu() {
                mobileMenu.classList.toggle('hidden');
                // You could also change the icon here if desired
            }

            // Listen for click on the hamburger button
            menuButton.addEventListener('click', toggleMenu);

            // Hide the menu if any link inside it is clicked (for better UX)
            const mobileLinks = mobileMenu.querySelectorAll('a');
            mobileLinks.forEach(link => {
                link.addEventListener('click', () => {
                    mobileMenu.classList.add('hidden');
                });
            });

            // Handle smooth scrolling for all internal links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    // Prevent default anchor click behavior
                    e.preventDefault();

                    // Get the target element
                    const targetId = this.getAttribute('href');
                    const targetElement = document.querySelector(targetId);

                    if (targetElement) {
                        // Scroll smoothly to the target element's position
                        targetElement.scrollIntoView({
                            behavior: 'smooth'
                        });
                    }
                });
            });
        });
    </script>

</body>
</html>

