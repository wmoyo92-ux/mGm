<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mgrovemed.com - Mission Grove Medical Corporation</title>
    <script src="https://cdn.tailwindcss.com/"></script>
    <style>
        /* Setting Inter font as the primary font */
        html { font-family: 'Inter', sans-serif; }
        
        /* Custom colors based on the logo */
        .color-primary-red { color: #C62828; }
        .bg-primary-red { background-color: #C62828; }
        .border-secondary-green { border-color: #2E7D32; }
        .bg-secondary-green { background-color: #2E7D32; }
    </style>
</head>
<body class="bg-gray-50">
    
    <!-- Navigation Bar -->
    <header class="shadow-lg sticky top-0 z-50 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4 md:justify-start md:space-x-10">
                <!-- Logo Section -->
                <div class="flex justify-start lg:w-0 lg:flex-1">
                    <a href="#" class="flex items-center space-x-2">
                        <!-- Logo Graphic (Simplified SVG based on uploaded design) -->
                        <div class="w-10 h-10 relative">
                            <svg class="w-full h-full" viewBox="0 0 100 100" xmlns="http://www.w3.org/2000/svg">
                                <!-- Red Cross Background -->
                                <rect x="35" y="0" width="30" height="100" fill="#C62828"/>
                                <rect x="0" y="35" width="100" height="30" fill="#C62828"/>
                                <!-- Tree Silhouette (Dark Green, simplified) -->
                                <path d="M50 20 L40 40 L60 40 Z M45 40 Q40 50 40 60 C40 70 50 70 50 80 Q60 70 60 60 C60 50 55 40 55 40 Z" fill="#2E7D32"/>
                            </svg>
                        </div>
                        <div class="flex flex-col leading-none">
                            <span class="text-2xl font-bold color-primary-red">MISSION GROVE</span>
                            <span class="text-sm tracking-widest border-t border-secondary-green text-gray-700 pt-1">MEDICAL CORPORATION</span>
                        </div>
                    </a>
                </div>

                <!-- Navigation Links (Hidden on small, shown on medium+) -->
                <nav class="hidden md:flex space-x-10">
                    <a href="#home" class="text-base font-medium text-gray-500 hover:text-gray-900 transition duration-150">Home</a>
                    <a href="#services" class="text-base font-medium text-gray-500 hover:text-gray-900 transition duration-150">Services</a>
                    <a href="#location" class="text-base font-medium text-gray-500 hover:text-gray-900 transition duration-150">Location</a>
                </nav>

                <!-- CTA Button -->
                <div class="hidden md:flex items-center justify-end md:flex-1 lg:w-0">
                    <a href="#contact" class="whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-primary-red hover:bg-red-700 transition duration-300">
                        (951) 780-3300
                    </a>
                    <a href="#" class="ml-4 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-secondary-green hover:bg-green-800 transition duration-300">
                        Save Your Spot
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="pt-16 pb-20 sm:pt-24 sm:pb-32 lg:pt-40 lg:pb-48 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight text-gray-900">
                <span class="block color-primary-red">Urgent Care &</span>
                <span class="block text-gray-800 mt-2">Specialized Wound Treatment</span>
            </h1>
            <p class="mt-6 max-w-lg mx-auto text-xl text-gray-500">
                Quality, compassionate medical care for your immediate needs and chronic wound healing, right here in Mission Grove.
            </p>
            
            <!-- Rebranding Note -->
            <div class="mt-8 max-w-2xl mx-auto">
                <div class="rounded-lg bg-yellow-50 p-4 shadow-lg border border-yellow-200">
                    <p class="text-base font-medium text-yellow-800">
                        We were formerly AFC Riverside! We have rebranded to Mission Grove Medical, but still offer the same quality of service you know and trust.
                    </p>
                </div>
            </div>

            <div class="mt-10 flex flex-wrap justify-center gap-4">
                <a href="#" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-lg shadow-lg text-white bg-secondary-green hover:bg-green-800 transition duration-300 transform hover:scale-105">
                    Save Your Spot
                </a>
                <a href="#services" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-3 border border-gray-300 text-base font-medium rounded-lg shadow-lg text-gray-700 bg-white hover:bg-gray-100 transition duration-300 transform hover:scale-105">
                    See Our Services
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 sm:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <h2 class="text-base color-primary-red font-semibold tracking-wide uppercase">Our Specialties</h2>
                <p class="mt-2 text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
                    Comprehensive Care When You Need It Most
                </p>
            </div>

            <div class="mt-12 grid grid-cols-1 gap-8 md:grid-cols-2">
                <!-- Urgent Care Card -->
                <div class="p-8 bg-gray-50 rounded-xl shadow-xl transform hover:shadow-2xl transition duration-500 ease-in-out">
                    <div class="flex items-center justify-center h-12 w-12 rounded-lg bg-primary-red text-white">
                         <!-- Medical Icon -->
                         <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v3m0 0v3m0-3h3m-3 0H9m12 0a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="mt-6 text-xl font-bold text-gray-900">Urgent Care & Walk-ins</h3>
                    <p class="mt-4 text-base text-gray-600">
                        For non-life-threatening illnesses and injuries that need immediate attention. Skip the long waits of the ER for things like colds, flu, minor fractures, cuts, and infections.
                    </p>
                    <ul class="mt-4 space-y-2 text-sm text-gray-600 list-disc list-inside">
                        <li>Colds, Flu, and Viral Illnesses</li>
                        <li>Minor Injuries and Sprains</li>
                        <li>Allergies and Rashes</li>
                        <li>Physicals and Vaccinations</li>
                    </ul>
                </div>

                <!-- Wound Care Card -->
                <div class="p-8 bg-gray-50 rounded-xl shadow-xl transform hover:shadow-2xl transition duration-500 ease-in-out">
                    <div class="flex items-center justify-center h-12 w-12 rounded-lg bg-primary-red text-white">
                         <!-- Wound Care Icon -->
                         <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.001 12.001 0 002 15.46V18a2 2 0 002 2h16a2 2 0 002-2v-2.54a12.001 12.001 0 00-1.382-7.516z"></path></svg>
                    </div>
                    <h3 class="mt-6 text-xl font-bold text-gray-900">Expert Wound Management</h3>
                    <p class="mt-4 text-base text-gray-600">
                        Specialized care for chronic, non-healing wounds, post-surgical wounds, and diabetic ulcers. Our experts focus on advanced techniques to promote rapid and complete healing.
                    </p>
                    <ul class="mt-4 space-y-2 text-sm text-gray-600 list-disc list-inside">
                        <li>Diabetic Foot Ulcer Treatment</li>
                        <li>Pressure Sore Management</li>
                        <li>Infected Wound Care</li>
                        <li>Advanced Dressing Techniques</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Location and Contact Section -->
    <section id="location" class="py-16 sm:py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <!-- Contact Details -->
                <div class="lg:pr-16 text-center lg:text-left" id="contact">
                    <h2 class="text-base color-primary-red font-semibold tracking-wide uppercase">Find Us</h2>
                    <p class="mt-2 text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
                        Your Local Clinic in Mission Grove
                    </p>
                    <p class="mt-4 text-lg text-gray-600">
                        MG Medical is dedicated to serving the Riverside community with convenient and high-quality medical services.
                    </p>

                    <div class="mt-8 space-y-6">
                        <!-- Address -->
                        <div class="flex items-start space-x-4">
                            <svg class="flex-shrink-0 h-6 w-6 color-primary-red" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.828 0l-4.243-4.243m10.121-6.121a5 5 0 11-7.07 0 5 5 0 017.07 0z"></path></svg>
                            <div>
                                <h4 class="font-bold text-gray-900">Address</h4>
                                <p class="text-gray-600">191 Alessandro Blvd #9a, Riverside, CA 92508</p>
                                <a href="https://maps.app.goo.gl/YourClinicMapLink" target="_blank" class="text-sm font-medium text-blue-600 hover:text-blue-800 transition duration-150">(Get Directions)</a>
                            </div>
                        </div>

                        <!-- Phone -->
                        <div class="flex items-start space-x-4">
                            <svg class="flex-shrink-0 h-6 w-6 color-primary-red" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.128a11.033 11.033 0 007.584 7.584l1.128-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                            <div>
                                <h4 class="font-bold text-gray-900">Phone Number</h4>
                                <p class="text-gray-600 font-extrabold text-lg">(951) 780-3300</p>
                            </div>
                        </div>
                        
                        <!-- Hours -->
                        <div class="flex items-start space-x-4">
                            <svg class="flex-shrink-0 h-6 w-6 color-primary-red" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                            <div>
                                <h4 class="font-bold text-gray-900">Operating Hours</h4>
                                <p class="text-gray-600">Mon - Fri: 8:00 AM - 8:00 PM</p>
                                <p class="text-gray-600">Sat - Sun: 8:00 AM - 6:00 PM</p>
                                <p class="text-gray-600 font-medium mt-1">Walk-ins are welcome everyday.</p>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Map Placeholder -->
                <div class="relative h-64 lg:h-96 w-full rounded-xl overflow-hidden shadow-2xl border-4 border-secondary-green">
                    <div class="w-full h-full bg-gray-200 flex items-center justify-center text-center p-4">
                        <p class="text-gray-600 font-semibold">
                            Map Placeholder (Google Maps Embed)<br>
                            <span class="text-sm font-normal">Showing location of 191 Alessandro Blvd #9a, Riverside, CA 92508</span>
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-sm text-gray-400">&copy; 2025 mgrovemed.com. Mission Grove Medical Corporation. All rights reserved.</p>
            <p class="mt-2 text-xs text-gray-500">Address: 191 Alessandro Blvd #9a, Riverside, CA 92508 | Phone: (951) 780-3300</p>
        </div>
    </footer>

</body>
</html>
