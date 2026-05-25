<!DOCTYPE ahtml>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>mgrovemed.com - Mission Grove Medical Corporation</title>
    <script src="https://cdn.tailwindcss.com/"></script>
    <style>
        /* Setting Inter font as the primary font */
        html { font-family: 'Inter', sans-serif; }
        
        /* Custom colors based on the logo and flyers */
        /* Updated colors for a richer look: Deep Red and Forest Green */
        .color-primary-red { color: #8C0000; } 
        .bg-primary-red { background-color: #8C0000; }
        .border-secondary-green { border-color: #0B6B00; }
        .bg-secondary-green { background-color: #0B6B00; }
        
        /* Custom CSS to style the multiple specialty grid */
        @media (min-width: 1024px) {
            #specialties-grid {
                grid-template-columns: repeat(3, minmax(0, 1fr));
            }
        }
        
        /* Loading spinner animation */
        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }
        .animate-spin-slow {
            animation: spin 1.5s linear infinite;
        }
    </style>
</head>
<body class="bg-gray-50">
    
    <!-- Navigation Bar -->
    <header class="shadow-lg sticky top-0 z-50 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center py-4 md:justify-start md:space-x-10">
                <!-- Logo Section: Updated to match the provided 2.png logo -->
                <div class="flex justify-start lg:w-0 lg:flex-1">
                    <a href="#" class="flex items-center">
                        <img src="logo.png" alt="Mission Grove Medical Corporation" class="h-14">
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
                    <!-- Updated Primary CTA to Call -->
                    <a href="tel:9517803300" class="whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-primary-red hover:bg-red-700 transition duration-300">
                        Call to Save a Spot
                    </a>
                    <!-- Disabled Online Booking CTA -->
                    <span class="ml-4 whitespace-nowrap inline-flex items-center justify-center px-4 py-2 border border-transparent rounded-lg shadow-sm text-base font-medium text-white bg-gray-400 cursor-not-allowed">
                        Online Booking Coming Soon
                    </span>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="pt-16 pb-20 sm:pt-24 sm:pb-32 lg:pt-40 lg:pb-48 bg-gray-50">
        <!-- ... existing hero section code ... -->
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h1 class="text-4xl sm:text-6xl lg:text-7xl font-extrabold tracking-tight text-gray-900">
                <span class="block color-primary-red">MGMC Urgent Care &</span>
                <!-- Updated Line -->
                <span class="block text-gray-800 mt-2">Wound Clinic</span>
            </h1>
            <p class="mt-6 max-w-lg mx-auto text-xl text-gray-500">
                Quality, compassionate medical care for your immediate needs and chronic wound healing, right here in Mission Grove.
            </p>
            
            <!-- Rebranding Note -->
            <div class="mt-8 max-w-2xl mx-auto">
                <div class="rounded-lg bg-yellow-50 p-4 shadow-lg border border-yellow-200">
                    <p class="text-base font-medium text-yellow-800">
                        **Formerly AFC Urgent Care- Riverside, now operating as Mission Grove Medical Urgent Care & Clinic!** We still offer the same high quality service that you know and trust!
                    </p>
                </div>
            </div>

            <div class="mt-10 flex flex-wrap justify-center gap-4">
                <!-- Disabled Online Booking CTA -->
                <span class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-3 border border-transparent text-base font-medium rounded-lg shadow-lg text-white bg-gray-400 cursor-not-allowed">
                    Online Booking Coming Soon
                </span>
                <a href="#services" class="w-full sm:w-auto inline-flex items-center justify-center px-8 py-3 border border-gray-300 text-base font-medium rounded-lg shadow-lg text-gray-700 bg-white hover:bg-gray-100 transition duration-300 transform hover:scale-105">
                    See Our Services
                </a>
            </div>
            
            <!-- Clarifying Note -->
            <p class="mt-4 text-lg text-gray-500">
                **Note:** Our online **save a spot** feature is currently unavailable. Please call us at (951) 780-3300 to **save a spot**.
            </p>
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

            <!-- Specialty Grid: Now 3 columns on large screens -->
            <div id="specialties-grid" class="mt-12 grid grid-cols-1 gap-8 md:grid-cols-2 lg:grid-cols-3">
                
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
                        <li>Acute illness visits</li>
                        <li>Minor injury care</li>
                        <li>Physical exams & Wellness checks</li>
                        <li>Work, school, and clearance forms</li>
                    </ul>
                </div>

                <!-- Wound Care Card -->
                <div class="p-8 bg-gray-50 rounded-xl shadow-xl transform hover:shadow-2xl transition duration-500 ease-in-out">
                    <div class="flex items-center justify-center h-12 w-12 rounded-lg bg-primary-red text-white">
                         <!-- Wound Care Icon (Shield/Protection) -->
                         <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m5.618-4.016A11.955 11.955 0 0112 2.944a11.955 11.955 0 01-8.618 3.04A12.001 12.001 0 002 15.46V18a2 2 0 002 2h16a2 2 0 002-2v-2.54a12.001 12.001 0 00-1.382-7.516z"></path></svg>
                    </div>
                    <h3 class="mt-6 text-xl font-bold text-gray-900">Expert Wound Management</h3>
                    <p class="mt-4 text-base text-gray-600">
                        Specialized care for chronic, non-healing wounds, post-surgical wounds, and diabetic ulcers. Our experts promote rapid and complete healing.
                    </p>
                    <ul class="mt-4 space-y-2 text-sm text-gray-600 list-disc list-inside">
                        <li>Diabetic Foot Ulcer Treatment</li>
                        <li>Venous & Arterial Ulcer Treatment</li>
                        <li>Pressure Injury Management</li>
                        <li>Debridement Services & Infection Eval.</li>
                    </ul>
                </div>

                <!-- NUYU Aesthetics Card (New Specialty) -->
                <div class="p-8 bg-gray-50 rounded-xl shadow-xl transform hover:shadow-2xl transition duration-500 ease-in-out">
                    <div class="flex items-center justify-center h-12 w-12 rounded-lg bg-secondary-green text-white">
                         <!-- Aesthetics Icon (Leaf/Wellness) -->
                         <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M5 3v4M3 5h4M6 17v4m-2-2h4m5-16l2.286 6.857L21 12l-5.714 2.143L13 21l-2.286-6.857L5 12l5.714-2.143L13 3z"></path></svg>
                    </div>
                    <!-- Hyperlinked Title to nuyutoday.com -->
                    <h3 class="mt-6 text-xl font-bold text-gray-900">
                        <a href="https://nuyutoday.com" target="_blank" rel="noopener noreferrer" class="hover:text-secondary-green transition duration-150">
                            NUYU Graceful Wellness & Aesthetics
                        </a>
                    </h3>
                    <p class="mt-4 text-base text-gray-600">
                        Achieve your beauty and wellness goals with specialized treatments including body contouring, IV therapy, and personalized weight loss programs.
                    </p>
                    <ul class="mt-4 space-y-2 text-sm text-gray-600 list-disc list-inside">
                        <li>Neurotoxins, Fillers, & Facials</li>
                        <li>Microneedling & Aesthetics</li>
                        <li>Organic & GLP-1 Weight Loss Programs</li>
                        <li>Wellness: IV Vitamins & Hydration Therapy</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Gemini AI Assistant Section (New Component) -->
    <section id="ai-assistant" class="py-16 sm:py-24 bg-gray-100 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center">
                <h2 class="text-base color-primary-red font-semibold tracking-wide uppercase">AI Health Resource Generator ✨</h2>
                <p class="mt-2 text-3xl font-extrabold tracking-tight text-gray-900 sm:text-4xl">
                    Get Quick, Reliable Health Information
                </p>
                <p class="mt-4 text-lg text-gray-600 max-w-3xl mx-auto">
                    Use our AI tool (powered by Gemini, a Google AI) to get summaries on minor symptoms or basic wound care advice. **(Note: This tool is for informational purposes only and is NOT a substitute for professional medical advice.)**
                </p>
            </div>

            <div class="mt-12 max-w-4xl mx-auto p-6 bg-white rounded-xl shadow-2xl border border-gray-200">
                <input 
                    type="text" 
                    id="userQuery" 
                    placeholder="E.g., What should I put on a minor burn? or, What are the symptoms of a sinus infection?" 
                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-secondary-green focus:border-secondary-green mb-4 text-gray-700"
                >

                <div class="flex flex-col sm:flex-row gap-3">
                    <button 
                        onclick="generateHealthAdvice('symptoms')" 
                        id="symptomButton"
                        class="w-full sm:w-1/2 inline-flex items-center justify-center px-4 py-3 border border-transparent text-base font-medium rounded-lg shadow-sm text-white bg-primary-red hover:bg-red-700 transition duration-300 transform hover:scale-[1.01]"
                    >
                        Check Symptoms Summary ✨
                    </button>
                    <button 
                        onclick="generateHealthAdvice('wound')" 
                        id="woundButton"
                        class="w-full sm:w-1/2 inline-flex items-center justify-center px-4 py-3 border border-transparent text-base font-medium rounded-lg shadow-sm text-white bg-secondary-green hover:bg-green-800 transition duration-300 transform hover:scale-[1.01]"
                    >
                        Basic Wound Advice ✨
                    </button>
                </div>
                
                <!-- Output Area -->
                <div id="loadingIndicator" class="hidden mt-6 text-center">
                    <div class="inline-block w-8 h-8 border-4 border-t-4 border-gray-200 border-t-primary-red rounded-full animate-spin-slow"></div>
                    <p class="mt-2 text-sm text-gray-600">Generating advice, please wait...</p>
                </div>

                <div id="aiOutput" class="mt-6 p-4 border border-gray-300 rounded-lg bg-gray-50 min-h-[100px] text-gray-800 text-left overflow-auto whitespace-pre-wrap">
                    Results will appear here. Remember to contact us or call 911 for emergencies.
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
                                <!-- UPDATED "Get Directions" Link -->
                                <a href="https://maps.app.goo.gl/kJ9iiFocYQL1pe7S9" target="_blank" rel="noopener noreferrer" class="text-sm font-medium text-blue-600 hover:text-blue-800 transition duration-150">(Get Directions)</a>
                            </div>
                        </div>

                        <!-- Phone & Fax -->
                        <div class="flex items-start space-x-4">
                            <svg class="flex-shrink-0 h-6 w-6 color-primary-red" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.128a11.033 11.033 0 007.584 7.584l1.128-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                            <div>
                                <h4 class="font-bold text-gray-900">Call / Fax</h4>
                                <p class="text-gray-600 font-extrabold text-lg">(951) 780-3300 (Phone)</p>
                                <p class="text-gray-600 font-extrabold text-lg">(951) 780-3303 (Fax)</p>
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

                <!-- Google Maps Embed -->
                <div class="relative h-64 lg:h-96 w-full rounded-xl overflow-hidden shadow-2xl border-4 border-secondary-green">
                    <iframe
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3311.458641113032!2d-117.3481068847889!3d33.9037469806461!2m3!1f0!2f0!0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x80dca6006121408b%3A0x6522c0c79316b8b8!2s191%20Alessandro%20Blvd%20%239a%2C%20Riverside%2C%20CA%2092508!5e0!3m2!1sen!2sus!4v1672956983577!5m2!1sen!2sus"
                        width="100%"
                        height="100%"
                        style="border:0;"
                        allowfullscreen=""
                        loading="lazy"
                        referrerpolicy="no-referrer-when-downgrade"
                        class="absolute top-0 left-0 w-full h-full"
                    ></iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <p class="text-sm text-gray-400">&copy; 2025 mgrovemed.com. Mission Grove Medical Corporation. All rights reserved.</p>
            <p class="mt-2 text-xs text-gray-500">Address: 191 Alessandro Blvd #9a, Riverside, CA 92508 | Phone: (951) 780-3300 | Fax: (951) 780-3303</p>
        </div>
    </footer>

    <script>
        // Gemini API configuration
        const API_KEY = ""; // Canvas will provide this at runtime
        const API_URL = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-09-2025:generateContent?key=${API_KEY}`;
        const MAX_RETRIES = 5;

        // Elements
        const userQueryInput = document.getElementById('userQuery');
        const aiOutputDiv = document.getElementById('aiOutput');
        const loadingIndicator = document.getElementById('loadingIndicator');
        const symptomButton = document.getElementById('symptomButton');
        const woundButton = document.getElementById('woundButton');
        const originalSymptomText = symptomButton.textContent;
        const originalWoundText = woundButton.textContent;

        /**
         * Generates health advice based on the user query and selected mode.
         * @param {string} mode - 'symptoms' for Urgent Care check, 'wound' for Wound Care advice.
         */
        async function generateHealthAdvice(mode) {
            const userQuery = userQueryInput.value.trim();
            if (!userQuery) {
                aiOutputDiv.innerHTML = '<span class="text-red-600">Please enter a question or description of your symptoms first.</span>';
                return;
            }

            // Determine the System Instruction based on the mode
            let systemPrompt = "";
            let userQueryContext = userQuery;

            if (mode === 'symptoms') {
                systemPrompt = `You are a medical triage assistant for an Urgent Care Clinic. Your goal is to provide a brief, general, NON-DIAGNOSTIC summary based on the user's symptoms. Always include a disclaimer at the top stating this is for information only. Recommend seeking professional urgent care attention if symptoms are severe, persistent, or include red flags (chest pain, severe difficulty breathing, high fever). Your response must be in simple, easy-to-read language. Limit the response to 3-4 concise paragraphs.`;
                userQueryContext = `The user reports these symptoms: "${userQuery}". Provide a summary of possible common causes and clearly state when they should seek urgent care.`;
            } else if (mode === 'wound') {
                systemPrompt = `You are a basic first aid advisor for a Wound Clinic. Provide general, easy-to-follow, practical steps for caring for a MINOR wound (like a scrape, small cut, or minor burn). Emphasize wound hygiene (cleaning) and protection (dressing). Always include a disclaimer that professional help is needed for deep, infected, or non-healing wounds. Your response must be in clear bullet points. Limit the response to 5-7 bullet points.`;
                userQueryContext = `The user needs basic care advice for: "${userQuery}". Provide the advice.`;
            }

            // Prepare button state for loading
            const buttonToDisable = mode === 'symptoms' ? symptomButton : woundButton;
            const originalText = buttonToDisable.textContent;
            
            buttonToDisable.disabled = true;
            buttonToDisable.innerHTML = '<div class="inline-block w-4 h-4 border-2 border-t-2 border-white rounded-full animate-spin-slow"></div> Processing...';
            loadingIndicator.classList.remove('hidden');
            aiOutputDiv.textContent = ''; // Clear previous output

            try {
                let responseText = await callGeminiAPI(systemPrompt, userQueryContext);
                aiOutputDiv.textContent = responseText;
            } catch (error) {
                console.error("Gemini API call failed after multiple retries:", error);
                aiOutputDiv.innerHTML = '<span class="text-red-600">Sorry, we could not generate the health advice at this time. Please try again or call the clinic directly.</span>';
            } finally {
                // Restore button state
                buttonToDisable.disabled = false;
                buttonToDisable.innerHTML = originalText;
                loadingIndicator.classList.add('hidden');
            }
        }
        
        // --- Gemini API Call with Exponential Backoff ---

        async function callGeminiAPI(systemPrompt, userQueryContext) {
            const payload = {
                contents: [{ parts: [{ text: userQueryContext }] }],
                systemInstruction: { parts: [{ text: systemPrompt }] },
                // Use search grounding for up-to-date and reliable information
                tools: [{ "google_search": {} }],
            };

            for (let attempt = 0; attempt < MAX_RETRIES; attempt++) {
                try {
                    const response = await fetch(API_URL, {
                        method: 'POST',
                        headers: { 'Content-Type': 'application/json' },
                        body: JSON.stringify(payload)
                    });

                    if (!response.ok) {
                        if (response.status === 429 && attempt < MAX_RETRIES - 1) {
                            // Rate limit exceeded, apply exponential backoff
                            const delay = Math.pow(2, attempt) * 1000 + Math.random() * 1000;
                            await new Promise(resolve => setTimeout(resolve, delay));
                            continue; // Retry
                        }
                        throw new Error(`HTTP error! Status: ${response.status}`);
                    }

                    const result = await response.json();
                    const candidate = result.candidates?.[0];

                    if (candidate && candidate.content?.parts?.[0]?.text) {
                        return candidate.content.parts[0].text;
                    } else {
                        // Handle cases where the response structure is unexpected or content is missing
                        throw new Error("Received empty or malformed response from API.");
                    }
                } catch (error) {
                    if (attempt === MAX_RETRIES - 1) {
                        throw error; // Re-throw if last attempt failed
                    }
                    // For other errors, apply backoff and retry
                    const delay = Math.pow(2, attempt) * 1000 + Math.random() * 1000;
                    await new Promise(resolve => setTimeout(resolve, delay));
                }
            }
        }

        // Initialize state
        window.onload = function() {
             // Reset the placeholder text to ensure the initial instruction is visible
             aiOutputDiv.textContent = 'Results will appear here. Remember to contact us or call 911 for emergencies.';
        };
    </script>
</body>
</html>
