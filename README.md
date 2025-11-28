<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivank Kanojiya | Graphic Designer Portfolio</title>
    
    <!-- Load Tailwind CSS for styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Load Lucide Icons for social media and skills -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Custom styles for professional polish and mobile readability */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap');

        body {
            font-family: 'Inter', sans-serif;
            background-color: #f4f7fa; /* Light background for a clean look */
        }
        /* Custom shadow for cards to give a lift effect */
        .card-shadow {
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.05), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
        /* Style the link icons */
        .social-link {
            transition: transform 0.2s, color 0.2s;
        }
        .social-link:hover {
            transform: scale(1.1);
            color: #10b981; /* Emerald green on hover */
        }
        /* Smooth scrolling for internal links */
        html {
            scroll-behavior: smooth;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Header & Navigation -->
    <header class="sticky top-0 z-50 bg-white shadow-md">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex justify-between items-center">
            <!-- Logo/Name -->
            <a href="#hero" class="text-2xl font-bold text-gray-900 tracking-tight transition duration-300 hover:text-emerald-600">
                Shivank Kanojiya
            </a>
            <!-- Desktop Navigation Links -->
            <div class="hidden md:flex space-x-6">
                <a href="#hero" class="text-gray-600 hover:text-emerald-600 font-medium transition duration-150">Home</a>
                <a href="#about" class="text-gray-600 hover:text-emerald-600 font-medium transition duration-150">About Me</a>
                <a href="#skills" class="text-gray-600 hover:text-emerald-600 font-medium transition duration-150">Photoshop & Designing</a>
                <a href="#projects" class="text-gray-600 hover:text-emerald-600 font-medium transition duration-150">My Poster Designs</a>
                <a href="#contact" class="text-gray-600 hover:text-emerald-600 font-medium transition duration-150">Contact</a>
            </div>
            <!-- Mobile Menu Button (if needed, simplified for this single file) -->
        </nav>
    </header>

    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 pt-10">

        <!-- 1. Hero Section (Home) -->
        <section id="hero" class="py-16 md:py-24 flex flex-col md:flex-row items-center justify-between gap-10">
            <div class="md:w-1/2 text-center md:text-left">
                <h1 class="text-4xl sm:text-5xl lg:text-6xl font-extrabold text-gray-900 leading-tight mb-4">
                    Hi, I'm <span class="text-emerald-600">Shivank Kanojiya</span>
                </h1>
                <p class="text-xl text-gray-600 mb-8">
                    Graphic Designer | Transforming Ideas into Stunning Visuals
                </p>
                <div class="space-x-4">
                    <a href="#projects" class="inline-block bg-emerald-600 text-white font-semibold py-3 px-6 rounded-lg transition duration-300 transform hover:scale-105 hover:bg-emerald-700 card-shadow">
                        My Poster Designs
                    </a>
                    <a href="#contact" class="inline-block bg-white text-emerald-600 border border-emerald-600 font-semibold py-3 px-6 rounded-lg transition duration-300 transform hover:scale-105 hover:bg-emerald-50">
                        Get In Touch
                    </a>
                </div>
            </div>
            <div class="md:w-1/3 w-2/3">
                <!-- Profile Image added from your provided URL -->
                <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/347-bf1b5592/shivank.png" alt="Shivank Kanojiya Profile Photo" class="rounded-full w-full h-auto object-cover card-shadow border-4 border-white transition duration-500 hover:rotate-2">
            </div>
        </section>

        <!-- 2. About Me Section -->
        <section id="about" class="py-16 border-t border-gray-200">
            <h2 class="text-3xl font-bold text-gray-900 mb-8 text-center">About Me</h2>
            <div class="max-w-4xl mx-auto bg-white p-8 rounded-xl card-shadow">
                <!-- Updated About Me Text -->
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    Welcome to my portfolio. I am Shivank, a dedicated Graphic Designer with a passion for transforming complex ideas into simple, powerful visual experiences. Creating dynamic and effective visual communication for the digital space.
                </p>
                <p class="text-lg text-gray-700 leading-relaxed mb-6">
                    Hiii Welcome To My Portfolio Here You Can See My Work And Also You Can See My Hardwork Behind My Design. Every Design Have My Unique Vision. Now Enjoy My Work......
                </p>
                <div class="mt-6 flex justify-center space-x-6">
                    <!-- Updated Email Link -->
                    <a href="mailto:shivankkanojiya05@gmail.com" class="text-gray-500 social-link flex items-center">
                        <i data-lucide="mail" class="w-6 h-6 mr-1"></i> shivankkanojiya05@gmail.com
                    </a>
                    <!-- Instagram Link - REMEMBER TO UPDATE THIS LINK -->
                    <a href="https://instagram.com/your_instagram_profile" target="_blank" class="text-gray-500 social-link flex items-center">
                        <i data-lucide="instagram" class="w-6 h-6 mr-1"></i> Instagram (Update Link!)
                    </a>
                </div>
            </div>
        </section>

        <!-- 3. Skills Section (Renamed to "Photoshop & Designing" and content updated) -->
        <section id="skills" class="py-16 border-t border-gray-200 bg-gray-50">
            <h2 class="text-3xl font-bold text-gray-900 mb-10 text-center">Photoshop & Designing</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6 max-w-6xl mx-auto">

                <!-- Skill Card 1: Adobe Photoshop -->
                <div class="bg-white p-6 rounded-xl card-shadow text-center transition duration-300 hover:ring-4 hover:ring-emerald-200">
                    <i data-lucide="image-plus" class="w-8 h-8 text-emerald-600 mx-auto mb-3"></i>
                    <h3 class="text-xl font-semibold mb-2">Adobe Photoshop</h3>
                    <p class="text-sm text-gray-600">Image manipulation, photo retouching, compositing, and visual effects.</p>
                </div>

                <!-- Skill Card 2: Graphic Design Principles -->
                <div class="bg-white p-6 rounded-xl card-shadow text-center transition duration-300 hover:ring-4 hover:ring-emerald-200">
                    <i data-lucide="palette" class="w-8 h-8 text-emerald-600 mx-auto mb-3"></i>
                    <h3 class="text-xl font-semibold mb-2">Graphic Design Principles</h3>
                    <p class="text-sm text-gray-600">Layout, typography, color theory, and visual hierarchy.</p>
                </div>

                <!-- Skill Card 3: Branding -->
                <div class="bg-white p-6 rounded-xl card-shadow text-center transition duration-300 hover:ring-4 hover:ring-emerald-200">
                    <i data-lucide="gem" class="w-8 h-8 text-emerald-600 mx-auto mb-3"></i>
                    <h3 class="text-xl font-semibold mb-2">Branding & Visual Identity</h3>
                    <p class="text-sm text-gray-600">Creating cohesive visual systems for brands across platforms.</p>
                </div>

                <!-- Skill Card 4: Digital Art -->
                <div class="bg-white p-6 rounded-xl card-shadow text-center transition duration-300 hover:ring-4 hover:ring-emerald-200">
                    <i data-lucide="pen-tool" class="w-8 h-8 text-emerald-600 mx-auto mb-3"></i>
                    <h3 class="text-xl font-semibold mb-2">Digital Art & Illustration</h3>
                    <p class="text-sm text-gray-600">Creating unique digital artworks and illustrations.</p>
                </div>

            </div>
        </section>

        <!-- 4. Projects Section (My Poster Designs) -->
        <section id="projects" class="py-16 border-t border-gray-200">
            <h2 class="text-3xl font-bold text-gray-900 mb-10 text-center">My Poster Designs</h2>

            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 max-w-6xl mx-auto">

                <!-- Project 1: Coffee (Image from uploaded file) -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow hover:shadow-xl transition duration-300 group">
                    <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/348-185d9302/WhatsApp_Image_2024-05-18_at_15.17.06.jpeg" alt="Special Coffee Poster" class="w-full h-60 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 group-hover:text-emerald-600 transition duration-300 mb-2">Special Coffee Promotion</h3>
                        <p class="text-gray-600 mb-4 text-sm">A vibrant poster design to promote a special coffee offer, focusing on visual appeal and clear call to action.</p>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-xs font-semibold text-gray-700 mr-2">Advertising</span>
                    </div>
                </div>

                <!-- Project 2: Ferrari (Image from uploaded file) -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow hover:shadow-xl transition duration-300 group">
                    <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/349-2f22b821/WhatsApp_Image_2024-05-18_at_15.17.07%20%281%29.jpeg" alt="Ferrari F12 Poster" class="w-full h-60 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 group-hover:text-emerald-600 transition duration-300 mb-2">Ferrari F12 Automotive Ad</h3>
                        <p class="text-gray-600 mb-4 text-sm">A sleek and powerful poster design for the iconic Ferrari F12, emphasizing luxury and performance.</p>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-xs font-semibold text-gray-700 mr-2">Automotive</span>
                    </div>
                </div>

                <!-- Project 3: Jeep (Image from uploaded file) -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow hover:shadow-xl transition duration-300 group">
                    <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/350-fdd7c3a4/WhatsApp_Image_2024-05-18_at_15.17.07%20%282%29.jpeg" alt="Jeep Poster" class="w-full h-60 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 group-hover:text-emerald-600 transition duration-300 mb-2">Jeep "Power" Ad Campaign</h3>
                        <p class="text-gray-600 mb-4 text-sm">Dynamic poster design capturing the essence of adventure and power for the Jeep brand.</p>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-xs font-semibold text-gray-700 mr-2">Automotive</span>
                    </div>
                </div>

                <!-- Project 4: Nike Shoes (Image from uploaded file) -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow hover:shadow-xl transition duration-300 group">
                    <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/351-4d1a5116/WhatsApp_Image_2024-05-18_at_15.17.07%20%283%29.jpeg" alt="Nike Dunk High LE Poster" class="w-full h-60 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 group-hover:text-emerald-600 transition duration-300 mb-2">Nike Dunk "Goldenrod" Promotion</h3>
                        <p class="text-gray-600 mb-4 text-sm">Striking visual for Nike's "Just Do It" campaign, highlighting the Goldenrod Obsidian sneaker.</p>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-xs font-semibold text-gray-700 mr-2">Fashion</span>
                    </div>
                </div>

                <!-- Project 5: Sony Headphones (Image from uploaded file) -->
                <div class="bg-white rounded-xl overflow-hidden card-shadow hover:shadow-xl transition duration-300 group">
                    <img src="https://assets-c4e954accc72782b1c431d102a0a2569.rimg.io/s/600x0/filters:format(webp):quality(85)/https://www.shivank-kanojiya-portfolio.odoo.com/web/image/352-031f77d3/WhatsApp_Image_2024-05-18_at_15.17.07.jpeg" alt="Sony MDR-1000X Headphones Poster" class="w-full h-60 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-semibold text-gray-900 group-hover:text-emerald-600 transition duration-300 mb-2">Sony MDR-1000X Headphones Ad</h3>
                        <p class="text-gray-600 mb-4 text-sm">Minimalist and impactful design promoting the key features of Sony's premium noise-cancelling headphones.</p>
                        <span class="inline-block bg-gray-200 rounded-full px-3 py-1 text-xs font-semibold text-gray-700 mr-2">Electronics</span>
                    </div>
                </div>

            </div>
        </section>

        <!-- 5. Contact Section -->
        <section id="contact" class="py-16 border-t border-gray-200 bg-emerald-50 rounded-xl mb-10 card-shadow">
            <h2 class="text-3xl font-bold text-gray-900 mb-4 text-center">Get in Touch</h2>
            <p class="text-lg text-gray-600 mb-10 text-center">
                I am currently open to new opportunities and projects. Send me an email!
            </p>

            <!-- Direct Email Link for "Send Message" button -->
            <div class="max-w-xl mx-auto space-y-6">
                <div>
                    <a href="mailto:shivankkanojiya05@gmail.com" class="w-full flex justify-center py-3 px-4 border border-transparent rounded-lg shadow-md text-base font-medium text-white bg-emerald-600 hover:bg-emerald-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-emerald-500 transition duration-300">
                        <i data-lucide="mail" class="w-5 h-5 mr-2"></i> Send Message to shivankkanojiya05@gmail.com
                    </a>
                </div>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 py-8 mt-10">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-400">
            <div class="mb-4 space-x-6">
                <!-- Email in Footer -->
                <a href="mailto:shivankkanojiya05@gmail.com" class="social-link text-gray-400 hover:text-white">
                    <i data-lucide="mail" class="w-6 h-6 inline"></i>
                </a>
                <!-- Instagram in Footer -->
                <a href="https://instagram.com/your_instagram_profile" target="_blank" class="social-link text-gray-400 hover:text-white">
                    <i data-lucide="instagram" class="w-6 h-6 inline"></i>
                </a>
            </div>
            <p>&copy; <span id="current-year"></span> Shivank Kanojiya. All rights reserved. | Built with HTML & Tailwind CSS.</p>
        </div>
    </footer>

    <script>
        // Initialize Lucide icons
        lucide.createIcons();

        // Set current year in the footer
        document.getElementById('current-year').textContent = new Date().getFullYear();
    </script>
</body>
</html>
