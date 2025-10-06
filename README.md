<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Shivgauri Agro - Your Partner in Farming Success</title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Configure Tailwind for custom colors and font -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        'agro-green': '#16A34A', // A deep, strong green
                        'agro-yellow': '#FBBF24', // A harvest yellow/amber
                        'agro-dark': '#1F2937', // Dark gray for text
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style>
        /* Ensuring Inter is used */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
    </style>
</head>
<body class="bg-gray-50 font-sans antialiased text-agro-dark">

    <!-- Header & Navigation -->
    <header class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-3 flex justify-between items-center">
            <h1 class="text-2xl font-extrabold text-agro-green tracking-wider">
                शिवगौरी <span class="text-agro-dark">Agro</span>
            </h1>
            <!-- Primary CTA for Mobile/Desktop -->
            <a href="#contact" class="px-4 py-2 bg-agro-green text-white font-semibold text-sm rounded-lg shadow-lg hover:bg-green-700 transition duration-300 transform hover:scale-105">
                मुफ्त सलाह कॉल
            </a>
        </div>
    </header>

    <main>
        <!-- 1. Hero Section -->
        <section class="bg-gray-100 pt-16 pb-20 md:py-32">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
                <p class="text-lg md:text-xl text-agro-green font-semibold mb-3">भारत के किसानों के लिए समर्पित</p>
                <h2 class="text-4xl sm:text-5xl lg:text-7xl font-extrabold mb-6 leading-tight">
                    आपके खेत की प्रगति,<br class="hidden sm:inline"> हमारी <span class="text-agro-green">जिम्मेदारी।</span>
                </h2>
                <p class="text-lg md:text-xl text-gray-600 max-w-3xl mx-auto mb-10">
                    हम ऑन-कॉल मुफ्त विशेषज्ञ मार्गदर्शन प्रदान करते हैं, और विस्तृत समाधान के लिए सशुल्क ऑन-साइट फार्म विजिट की सुविधा भी उपलब्ध है।
                </p>
                <!-- UPDATED PHONE NUMBER HERE -->
                <a href="tel:8625830898" class="inline-flex items-center justify-center px-8 py-4 border border-transparent text-lg font-bold rounded-xl shadow-xl text-white bg-agro-yellow hover:bg-yellow-600 transition duration-300 transform hover:scale-105 ring-4 ring-agro-yellow/50">
                    <svg class="w-6 h-6 mr-3" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                    फ्री कॉल करें: 8625830898
                </a>
            </div>
        </section>

        <!-- 2. Services Section -->
        <section id="services" class="py-16 md:py-24 bg-white">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h3 class="text-3xl sm:text-4xl font-extrabold text-center mb-12">हमारी सेवाएँ: आपकी ज़रूरत के अनुसार</h3>

                <div class="grid md:grid-cols-2 gap-8 lg:gap-12">

                    <!-- Service Card 1: Free On-Call Consultation -->
                    <div class="bg-green-50 border-t-4 border-agro-green p-6 sm:p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                        <div class="flex items-center mb-4">
                            <div class="bg-agro-green/10 p-3 rounded-full mr-4">
                                <svg class="w-8 h-8 text-agro-green" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path></svg>
                            </div>
                            <h4 class="text-2xl font-bold text-agro-dark">मुफ्त फोन/वीडियो सलाह</h4>
                        </div>
                        <p class="text-gray-600 mb-6">
                            छोटी समस्याओं, त्वरित मार्गदर्शन, या प्रारंभिक सलाह के लिए। हम समझते हैं कि हर किसान को तुरंत मदद की ज़रूरत हो सकती है।
                        </p>
                        <ul class="list-disc list-inside space-y-2 text-gray-700 mb-8 ml-4">
                            <li>त्वरित फसल स्वास्थ्य जाँच</li>
                            <li>कीट या रोग की पहचान</li>
                            <li>सरकारी योजनाओं पर सामान्य जानकारी</li>
                        </ul>
                        <!-- UPDATED PHONE NUMBER HERE -->
                        <a href="tel:8625830898" class="block w-full text-center py-3 bg-agro-green text-white font-semibold rounded-lg hover:bg-green-700 transition duration-300">
                            अभी मुफ्त सलाह के लिए कॉल करें
                        </a>
                    </div>

                    <!-- Service Card 2: Paid On-Site Consultation -->
                    <div class="bg-yellow-50 border-t-4 border-agro-yellow p-6 sm:p-8 rounded-xl shadow-lg hover:shadow-xl transition duration-300">
                        <div class="flex items-center mb-4">
                            <div class="bg-agro-yellow/10 p-3 rounded-full mr-4">
                                <svg class="w-8 h-8 text-agro-dark" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17.657 16.657L13.414 20.9a1.998 1.998 0 01-2.828 0l-4.243-4.243m12.424-1.414l-4.242 4.242m-4.242-4.242L10.985 13.985a1.998 1.998 0 002.828 0l4.242-4.242m-12.424 0L10.985 6.985a1.998 1.998 0 012.828 0l4.242 4.242M12 21a9 9 0 100-18 9 9 0 000 18z"></path></svg>
                            </div>
                            <h4 class="text-2xl font-bold text-agro-dark">सशुल्क ऑन-साइट विज़िट</h4>
                        </div>
                        <p class="text-gray-600 mb-6">
                            गहन मिट्टी विश्लेषण, अनुकूलित फसल योजना, और आपके खेत पर व्यक्तिगत दौरा। (शुल्क लागू)
                        </p>
                        <ul class="list-disc list-inside space-y-2 text-gray-700 mb-8 ml-4">
                            <li>मिट्टी और जल का विस्तृत परीक्षण</li>
                            <li>फसल चक्र और उर्वरक की कस्टम योजना</li>
                            <li>खेत की उत्पादकता बढ़ाने के लिए व्यक्तिगत रिपोर्ट</li>
                        </ul>
                        <a href="#contact-form" class="block w-full text-center py-3 bg-agro-dark text-white font-semibold rounded-lg hover:bg-gray-700 transition duration-300">
                            ऑन-साइट विज़िट के लिए पूछताछ करें
                        </a>
                    </div>
                </div>
            </div>
        </section>
        
        <!-- 3. Gemini LLM Feature: Instant Crop Advice -->
        <section class="py-16 md:py-24 bg-agro-green/10" id="gemini-advice">
            <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
                <h3 class="text-3xl sm:text-4xl font-extrabold text-center mb-4 text-agro-dark">
                    ✨ तुरंत फसल विशेषज्ञ सलाह (Ask the AI)
                </h3>
                <p class="text-center text-lg text-gray-600 mb-8">
                    अपनी फसल और समस्या टाइप करें, और हमारा AI तुरंत प्राथमिक निदान और सामान्य समाधान देगा। (विस्तृत और व्यक्तिगत सलाह के लिए कृपया हमें कॉल करें!)
                </p>

                <div class="bg-white p-6 sm:p-8 rounded-xl shadow-2xl">
                    <div class="space-y-4">
                        <div>
                            <label for="crop_query" class="block text-sm font-medium text-gray-700">अपनी फसल का नाम और समस्या लिखें (जैसे: गेहूँ में पत्तियाँ पीली पड़ रही हैं)</label>
                            <textarea id="crop_query" rows="3" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-agro-green focus:border-agro-green" placeholder="कृपया 1-2 पंक्तियों में अपनी समस्या स्पष्ट करें..."></textarea>
                        </div>
                        <button onclick="generateAdvice()" id="adviceButton" class="w-full py-3 bg-agro-yellow text-agro-dark font-bold text-lg rounded-lg shadow-md hover:bg-yellow-600 transition duration-300 flex items-center justify-center disabled:opacity-50">
                            <svg class="w-5 h-5 mr-2 animate-spin hidden" id="loadingIcon" fill="none" viewBox="0 0 24 24" stroke-width="2" stroke="currentColor" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" d="M16.03 5.093l-4.524 9.048-4.524-9.048a1 1 0 011.664-.99l2.86 2.86 2.86-2.86a1 1 0 011.664.99z"></path></svg>
                            ✨ सलाह जनरेट करें
                        </button>
                    </div>

                    <!-- AI Results Area -->
                    <div id="aiResultContainer" class="mt-8 border-t border-gray-200 pt-6 hidden">
                        <h4 class="text-xl font-bold text-agro-green mb-3">AI विशेषज्ञ निदान:</h4>
                        <div id="aiResponse" class="p-4 bg-green-50 rounded-lg text-gray-700 whitespace-pre-wrap leading-relaxed"></div>
                        <div id="aiSources" class="mt-4 text-xs text-gray-500 italic border-t pt-2"></div>
                        <div class="mt-4 p-3 bg-yellow-100 border-l-4 border-agro-yellow rounded-lg">
                            <p class="text-sm font-semibold text-agro-dark">
                                💡 यह एक सामान्य AI निदान है। अपने खेत के लिए सटीक और व्यक्तिगत समाधान हेतु, कृपया **शिवगौरी एग्रो** के विशेषज्ञों को <a href="tel:8625830898" class="text-agro-green font-bold">8625830898</a> पर कॉल करें।
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- 4. About Us / Trust Section (Original 3) -->
        <section class="py-16 md:py-24 bg-gray-100">
            <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
                <h3 class="text-3xl sm:text-4xl font-extrabold text-center mb-12">हम कौन हैं: शिवगौरी एग्रो</h3>
                <div class="max-w-4xl mx-auto text-center">
                    <p class="text-lg text-gray-700 mb-6">
                        हम, शिव और गौरी, कृषि में दशकों के अनुभव के साथ यह मानते हैं कि सही समय पर सही सलाह किसी भी किसान की किस्मत बदल सकती है। 'शिवगौरी' नाम समृद्धि, उर्वरता और समर्पण का प्रतीक है, और हम इसी भावना से हर खेत को देखते हैं।
                    </p>
                    <p class="text-lg text-gray-700 font-semibold">
                        हमारा मिशन भारतीय किसानों को आधुनिक और टिकाऊ कृषि तकनीकों से सशक्त बनाना है।
                    </p>
                    <div class="mt-8 flex justify-center space-x-4">
                        <!-- Placeholder for founders' images/icons -->
                        <span class="inline-flex items-center justify-center h-16 w-16 rounded-full bg-agro-green/20 text-agro-green text-3xl font-bold">श</span>
                        <span class="inline-flex items-center justify-center h-16 w-16 rounded-full bg-agro-yellow/20 text-agro-yellow text-3xl font-bold">ग</span>
                    </div>
                </div>
            </div>
        </section>

        <!-- 5. Contact Form / CTA Section (Original 4) -->
        <section id="contact" class="py-16 md:py-24 bg-white">
            <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
                <h3 class="text-3xl sm:text-4xl font-extrabold text-center mb-4">ऑन-साइट विज़िट के लिए पूछताछ करें</h3>
                <p class="text-center text-lg text-gray-600 mb-12">कृपया यह फ़ॉर्म भरें, और हम जल्द ही आपसे संपर्क करेंगे।</p>

                <div id="contact-form" class="bg-gray-50 p-6 sm:p-10 rounded-xl shadow-2xl border border-gray-100">
                    <form onsubmit="handleSubmit(event)">
                        <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                            <div class="space-y-2">
                                <label for="name" class="block text-sm font-medium text-gray-700">आपका नाम</label>
                                <input type="text" id="name" name="name" required class="w-full p-3 border border-gray-300 rounded-lg focus:ring-agro-green focus:border-agro-green">
                            </div>
                            <div class="space-y-2">
                                <label for="phone" class="block text-sm font-medium text-gray-700">फ़ोन नंबर</label>
                                <input type="tel" id="phone" name="phone" required class="w-full p-3 border border-gray-300 rounded-lg focus:ring-agro-green focus:border-agro-green">
                            </div>
                        </div>

                        <div class="mt-6 space-y-2">
                            <label for="location" class="block text-sm font-medium text-gray-700">खेत का स्थान (राज्य और जिला)</label>
                            <input type="text" id="location" name="location" required class="w-full p-3 border border-gray-300 rounded-lg focus:ring-agro-green focus:border-agro-green">
                        </div>

                        <div class="mt-6 space-y-2">
                            <label for="message" class="block text-sm font-medium text-gray-700">आप किस चीज़ पर सलाह चाहते हैं?</label>
                            <textarea id="message" name="message" rows="4" required class="w-full p-3 border border-gray-300 rounded-lg focus:ring-agro-green focus:border-agro-green"></textarea>
                        </div>

                        <button type="submit" class="mt-8 w-full py-3 bg-agro-green text-white font-bold text-lg rounded-lg shadow-md hover:bg-green-700 transition duration-300">
                            पूछताछ सबमिट करें
                        </button>

                        <!-- Message Box for Submission Status -->
                        <div id="statusMessage" class="mt-4 p-3 bg-blue-100 text-blue-700 rounded-lg hidden"></div>
                    </form>
                </div>
            </div>
        </section>
    </main>

    <!-- Footer -->
    <footer class="bg-agro-dark py-8">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-gray-400">
            <p class="mb-2">© 2024 Shivgauri Agro. All rights reserved.</p>
            <p class="text-sm">
                <!-- UPDATED EMAIL AND PHONE NUMBER HERE -->
                ईमेल: <a href="mailto:gayatrisbairagi@gmail.com" class="text-agro-green hover:text-agro-yellow">gayatrisbairagi@gmail.com</a> | फ़ोन: <a href="tel:8625830898" class="text-agro-green hover:text-agro-yellow">8625830898</a>
            </p>
        </div>
    </footer>

    <!-- JavaScript for Form Submission and Gemini API -->
    <script>
        // --- Constants for Gemini API ---
        const apiKey = ""; // API key is provided by the environment
        const apiUrl = `https://generativelanguage.googleapis.com/v1beta/models/gemini-2.5-flash-preview-05-20:generateContent?key=${apiKey}`;
        const MAX_RETRIES = 5;

        // Utility function for exponential backoff
        async function exponentialBackoff(func, retries = 0) {
            try {
                return await func();
            } catch (error) {
                if (retries < MAX_RETRIES) {
                    const delay = Math.pow(2, retries) * 1000 + Math.random() * 1000;
                    await new Promise(resolve => setTimeout(resolve, delay));
                    return exponentialBackoff(func, retries + 1);
                } else {
                    console.error("Max retries reached. Failed to fetch from API.", error);
                    throw new Error("API request failed after multiple retries.");
                }
            }
        }

        /**
         * Handles the click event to generate crop advice using the Gemini API.
         */
        async function generateAdvice() {
            const queryTextarea = document.getElementById('crop_query');
            const adviceButton = document.getElementById('adviceButton');
            const loadingIcon = document.getElementById('loadingIcon');
            const aiResultContainer = document.getElementById('aiResultContainer');
            const aiResponseDiv = document.getElementById('aiResponse');
            const aiSourcesDiv = document.getElementById('aiSources');

            const userQuery = queryTextarea.value.trim();

            if (!userQuery) {
                aiResponseDiv.innerHTML = 'कृपया अपनी फसल और समस्या के बारे में लिखें।';
                aiResultContainer.classList.remove('hidden');
                return;
            }

            // UI State: Loading
            adviceButton.disabled = true;
            loadingIcon.classList.remove('hidden');
            aiResultContainer.classList.add('hidden');
            aiResponseDiv.textContent = '';
            aiSourcesDiv.textContent = '';

            const systemPrompt = "आप एक अनुभवी भारतीय कृषि सलाहकार हैं जो किसानों को हिंदी में सरल और विश्वसनीय सलाह देते हैं। उपयोगकर्ता एक फसल और उसमें आ रही समस्या के बारे में पूछ रहा है। उन्हें तुरंत, प्राथमिक, और सामान्य निदान और उपचार (quick remedies) प्रदान करें। अपनी प्रतिक्रिया को तीन स्पष्ट भागों में विभाजित करें: 1. संभावित निदान (Probable Diagnosis), 2. त्वरित उपाय (Immediate Remedy) - जो किसान तुरंत कर सकता है, और 3. आगे की सलाह (Next Steps) - जिसमें शिवगौरी एग्रो से संपर्क करने का सुझाव हो। जवाब में सिर्फ़ सलाह शामिल करें, कोई अनावश्यक परिचय या उपसंहार नहीं।";
            
            const payload = {
                contents: [{ parts: [{ text: userQuery }] }],
                tools: [{ "google_search": {} }],
                systemInstruction: {
                    parts: [{ text: systemPrompt }]
                },
            };

            const fetchFunc = async () => {
                const response = await fetch(apiUrl, {
                    method: 'POST',
                    headers: { 'Content-Type': 'application/json' },
                    body: JSON.stringify(payload)
                });
                if (!response.ok) {
                    throw new Error(`HTTP error! status: ${response.status}`);
                }
                return response.json();
            };

            try {
                const result = await exponentialBackoff(fetchFunc);
                const candidate = result.candidates?.[0];

                if (candidate && candidate.content?.parts?.[0]?.text) {
                    const text = candidate.content.parts[0].text;
                    aiResponseDiv.textContent = text;
                    
                    // Extract and display grounding sources
                    let sourcesHtml = 'स्रोत: ';
                    let sources = [];
                    const groundingMetadata = candidate.groundingMetadata;

                    if (groundingMetadata && groundingMetadata.groundingAttributions) {
                        sources = groundingMetadata.groundingAttributions
                            .map(attribution => ({
                                uri: attribution.web?.uri,
                                title: attribution.web?.title,
                            }))
                            .filter(source => source.uri && source.title);
                    }

                    if (sources.length > 0) {
                        sourcesHtml += sources.map(s => 
                            `<a href="${s.uri}" target="_blank" class="text-agro-green hover:underline">${s.title.substring(0, 50)}...</a>`
                        ).join(', ');
                        aiSourcesDiv.innerHTML = sourcesHtml;
                    } else {
                        aiSourcesDiv.textContent = 'कोई बाहरी स्रोत नहीं मिला।';
                    }

                } else {
                    aiResponseDiv.textContent = 'क्षमा करें, AI विशेषज्ञ इस समस्या का निदान नहीं कर पाया। कृपया हमें सीधे कॉल करें।';
                    aiSourcesDiv.textContent = '';
                }

                aiResultContainer.classList.remove('hidden');

            } catch (error) {
                aiResponseDiv.textContent = 'सलाह जनरेट करते समय एक त्रुटि हुई। कृपया थोड़ी देर बाद पुनः प्रयास करें या हमें सीधे कॉल करें।';
                aiSourcesDiv.textContent = '';
                aiResultContainer.classList.remove('hidden');
            } finally {
                // UI State: Complete
                adviceButton.disabled = false;
                loadingIcon.classList.add('hidden');
            }
        }


        // Simple JavaScript for On-Site Form Submission Message
        function handleSubmit(event) {
            event.preventDefault();
            const form = event.target;
            const name = document.getElementById('name').value;
            const statusMessage = document.getElementById('statusMessage');

            // Simulate form submission success
            statusMessage.textContent = `धन्यवाद, ${name} जी! आपकी पूछताछ सफलतापूर्वक प्राप्त हो गई है। हम 24 घंटे के भीतर आपसे संपर्क करेंगे।`;
            statusMessage.classList.remove('hidden');
            statusMessage.classList.remove('bg-red-100', 'text-red-700');
            statusMessage.classList.add('bg-blue-100', 'text-blue-700');
            form.reset();
        }
    </script>
</body>
</html>
