## Hi there 👋

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>C.O.R.E. Speech and Debate Academy | Portfolio</title>
    <!-- Tailwind CSS for rapid styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;800&display=swap" rel="stylesheet">
    
    <!-- Custom Theme Colors based on your image -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        coreRed: '#B80000',
                        coreBlue: '#71C6EA',
                    },
                    fontFamily: {
                        sans: ['Poppins', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Poppins', sans-serif; }
        .hover-lift { transition: transform 0.2s ease-in-out; }
        .hover-lift:hover { transform: translateY(-3px); }
    </style>
</head>
<body class="bg-gray-50 text-gray-800">

    <!-- MAIN CONTAINER -->
    <div class="min-h-screen flex flex-col items-center justify-center p-6 lg:p-12">
        
        <div class="max-w-5xl w-full bg-white rounded-3xl shadow-2xl overflow-hidden flex flex-col md:flex-row">
            
            <!-- LEFT COLUMN: Portfolio & Links -->
            <div class="w-full md:w-3/5 p-8 lg:p-12 flex flex-col justify-center">
                
                <!-- EDIT YOUR NAME / ACADEMY NAME HERE -->
                <h3 class="text-coreBlue font-semibold tracking-wider uppercase mb-1">Portfolio & Booking</h3>
                <h1 class="text-4xl lg:text-5xl font-extrabold text-gray-900 mb-4 leading-tight">
                    Welcome to <span class="text-coreRed">C.O.R.E.</span><br>Speech & Debate.
                </h1>
                
                <!-- EDIT YOUR BIO HERE -->
                <p class="text-gray-600 mb-6 text-lg">
                    Hi! I am the founder and head coach of C.O.R.E. I help middle schoolers turn their fear of public speaking into their ultimate superpower through 1-on-1 coaching.
                </p>

                <!-- PORTFOLIO DETAILS -->
                <div class="space-y-4 mb-8">
                    <div class="flex items-start">
                        <span class="text-coreRed font-bold text-xl mr-3">✓</span>
                        <p class="text-gray-700"><strong>Confidence Building:</strong> Master the "Nervous = Excited" mindset.</p>
                    </div>
                    <div class="flex items-start">
                        <span class="text-coreRed font-bold text-xl mr-3">✓</span>
                        <p class="text-gray-700"><strong>Speech Structure:</strong> Learn the secret to structuring bulletproof arguments.</p>
                    </div>
                    <div class="flex items-start">
                        <span class="text-coreRed font-bold text-xl mr-3">✓</span>
                        <p class="text-gray-700"><strong>Stage Presence:</strong> Turn body language into your greatest asset.</p>
                    </div>
                </div>

                <!-- CALL TO ACTION LINKS -->
                <div class="flex flex-col sm:flex-row gap-4 mt-auto">
                    <!-- EDIT YOUR CALENDLY LINK HERE -->
                    <a href="https://calendly.com/YOUR_LINK_HERE" target="_blank" 
                       class="hover-lift flex-1 bg-coreRed text-white text-center font-bold py-3 px-6 rounded-full shadow-lg hover:bg-red-800 transition-colors">
                        Book Free Class
                    </a>
                    
                    <!-- EDIT YOUR YOUTUBE LINK HERE -->
                    <a href="https://youtube.com/YOUR_LINK_HERE" target="_blank" 
                       class="hover-lift flex-1 bg-white border-2 border-coreBlue text-coreBlue text-center font-bold py-3 px-6 rounded-full shadow hover:bg-blue-50 transition-colors">
                        Watch YouTube
                    </a>
                </div>

            </div>

            <!-- RIGHT COLUMN: Your Provided Image -->
            <div class="w-full md:w-2/5 bg-coreRed flex items-center justify-center p-6 border-l-4 border-coreBlue">
                <!-- IMPORTANT: Make sure your image is named 'core-promo.jpg' in the same folder -->
                <img src="core-promo.jpg" alt="C.O.R.E. Academy Promo" class="max-w-full h-auto rounded-xl shadow-xl hover-lift">
            </div>

        </div>

        <!-- FOOTER -->
        <footer class="mt-8 text-center text-gray-400 text-sm">
            <p>&copy; 2024 C.O.R.E. Speech and Debate Academy. All rights reserved.</p>
        </footer>

    </div>

</body>
</html><!--
**CORE-SpeechAndDebateAcademy/CORE-SpeechAndDebateAcademy** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
