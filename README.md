<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JaparmySholly - Academic Research Consultant</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;1,400&family=Lato:wght@300;400;700;900&display=swap" rel="stylesheet">
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* Custom Font Setup */
        .font-serif { font-family: 'Playfair Display', serif; }
        .font-sans { font-family: 'Lato', sans-serif; }
        
        /* Academic Pattern Background */
        .bg-academic-pattern {
            background-color: #f3f4f6;
            background-image: radial-gradient(#cbd5e1 1px, transparent 1px);
            background-size: 24px 24px;
        }

        /* Gold Gradient Text */
        .text-gold-gradient {
            background: linear-gradient(to right, #b48811, #fcd34d, #b48811);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            background-clip: text;
        }

        /* Card Hover Effect */
        .service-card {
            transition: all 0.3s ease;
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0, 0, 0, 0.1), 0 4px 6px -2px rgba(0, 0, 0, 0.05);
        }
    </style>
</head>
<body class="bg-academic-pattern min-h-screen flex items-center justify-center p-4 font-sans text-slate-800">

    <!-- Flyer Container (A4-ish aspect ratio max-width) -->
    <div class="bg-white w-full max-w-2xl shadow-2xl rounded-xl overflow-hidden relative flex flex-col">
        
        <!-- Header Section -->
        <div class="bg-slate-900 text-white p-8 md:p-12 text-center relative overflow-hidden">
            <!-- Decorative Circles -->
            <div class="absolute top-0 left-0 w-32 h-32 bg-yellow-500 rounded-full mix-blend-multiply filter blur-xl opacity-10 animate-blob"></div>
            <div class="absolute top-0 right-0 w-32 h-32 bg-blue-500 rounded-full mix-blend-multiply filter blur-xl opacity-10 animate-blob animation-delay-2000"></div>

            <div class="relative z-10">
                <div class="inline-flex items-center justify-center p-3 bg-white/10 rounded-full mb-4 backdrop-blur-sm border border-white/20">
                    <i data-lucide="graduation-cap" class="w-8 h-8 text-yellow-400"></i>
                </div>
                <h1 class="font-serif text-4xl md:text-5xl font-bold mb-2 tracking-wide">JaparmySholly</h1>
                <p class="text-yellow-400 font-bold uppercase tracking-widest text-sm md:text-base mb-6">Academic Research Consultant</p>
                
                <div class="inline-block bg-white/10 backdrop-blur-md px-6 py-2 rounded-full border border-white/20">
                    <p class="text-sm md:text-base font-light italic">
                        🎓 Specializing in <span class="font-bold text-white">UK & Canada</span> University Standards
                    </p>
                </div>
            </div>
        </div>

        <!-- Main Content -->
        <div class="p-8 md:p-12 flex-grow flex flex-col justify-center">
            
            <div class="text-center mb-10">
                <h2 class="text-2xl font-serif font-bold text-slate-800 mb-3">Navigate Complexity with Ease</h2>
                <p class="text-slate-600 max-w-md mx-auto">
                    I help students turn academic stress into success by providing expert guidance tailored to rigorous international standards.
                </p>
            </div>

            <!-- Services Grid -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6 mb-10">
                
                <!-- Service 1 -->
                <div class="service-card bg-slate-50 p-6 rounded-lg border border-slate-100 flex items-start space-x-4">
                    <div class="bg-blue-100 p-3 rounded-lg text-blue-800 shrink-0">
                        <i data-lucide="book-open" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Thesis & Dissertation</h3>
                        <p class="text-sm text-slate-600">Comprehensive guidance from proposal to final submission.</p>
                    </div>
                </div>

                <!-- Service 2 -->
                <div class="service-card bg-slate-50 p-6 rounded-lg border border-slate-100 flex items-start space-x-4">
                    <div class="bg-yellow-100 p-3 rounded-lg text-yellow-700 shrink-0">
                        <i data-lucide="bar-chart-3" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Data & Presentation</h3>
                        <p class="text-sm text-slate-600">Statistical analysis and professional slide deck creation.</p>
                    </div>
                </div>

                <!-- Service 3 -->
                <div class="service-card bg-slate-50 p-6 rounded-lg border border-slate-100 flex items-start space-x-4">
                    <div class="bg-purple-100 p-3 rounded-lg text-purple-700 shrink-0">
                        <i data-lucide="clipboard-list" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Assignment Guides & Coursework</h3>
                        <p class="text-sm text-slate-600">Structured outlines and expert support for module assignments.</p>
                    </div>
                </div>

                <!-- Service 4 -->
                <div class="service-card bg-slate-50 p-6 rounded-lg border border-slate-100 flex items-start space-x-4">
                    <div class="bg-indigo-100 p-3 rounded-lg text-indigo-700 shrink-0">
                        <i data-lucide="sparkles" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">AI Humanization</h3>
                        <p class="text-sm text-slate-600">Plagiarism reduction and refining AI-generated content.</p>
                    </div>
                </div>
                
                <!-- Service 5
                <div class="service-card bg-slate-50 p-6 rounded-lg border border-slate-100 flex items-start space-x-4 md:col-span-2">
                    <div class="bg-emerald-100 p-3 rounded-lg text-emerald-700 shrink-0">
                        <i data-lucide="check-circle-2" class="w-6 h-6"></i>
                    </div>
                    <div>
                        <h3 class="font-bold text-slate-900 mb-1">Proofreading & Formatting</h3>
                        <p class="text-sm text-slate-600">Professional formatting and meticulous error correction.</p>
                    </div>
                </div> -->

            </div>

            <!-- CTA Section -->
            <div class="bg-slate-900 rounded-xl p-8 text-center text-white relative overflow-hidden group cursor-default">
                <div class="absolute inset-0 bg-gradient-to-r from-blue-900 to-slate-900 opacity-90"></div>
                <div class="relative z-10">
                    <h3 class="font-serif text-2xl font-bold mb-2">Ready to Succeed?</h3>
                    <p class="text-blue-200 mb-6 text-sm">Turn your academic stress into success today.</p>
                    
                    <button class="bg-yellow-500 hover:bg-yellow-400 text-slate-900 font-bold py-3 px-8 rounded-full transition-colors duration-300 shadow-lg flex items-center justify-center mx-auto gap-2">
                        <i data-lucide="message-circle" class="w-5 h-5"></i>
                        DM to secure your grades today
                    </button>
                </div>
            </div>

        </div>
        
        <!-- Footer Stripe -->
        <div class="bg-slate-100 p-4 text-center border-t border-slate-200">
            <p class="text-xs text-slate-500 uppercase tracking-widest font-bold">Professional • Confidential • Expert</p>
        </div>

    </div>

    <script>
        // Initialize Lucide Icons
        lucide.createIcons();
    </script>
</body>
</html>