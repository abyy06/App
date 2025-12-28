<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Before You Send - Email Mistake Prevention App</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            50: '#eff6ff',
                            100: '#dbeafe',
                            500: '#3b82f6',
                            600: '#2563eb',
                            700: '#1d4ed8',
                            900: '#1e3a8a',
                        }
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-white text-gray-800 antialiased">

    <!-- Navigation (Minimal) -->
    <nav class="flex items-center justify-between px-6 py-4 max-w-7xl mx-auto">
        <div class="text-2xl font-bold text-brand-700">Before You Send</div>
        <a href="#cta" class="px-5 py-2.5 text-sm font-medium text-white bg-brand-600 rounded-full hover:bg-brand-700 transition-colors">
            Get Early Access
        </a>
    </nav>

    <!-- Hero Section -->
    <section class="relative px-6 py-16 md:py-24 lg:py-32 bg-gradient-to-br from-brand-50 to-white overflow-hidden">
        <div class="max-w-7xl mx-auto text-center relative z-10">
            <h1 class="text-4xl md:text-6xl font-extrabold text-gray-900 tracking-tight mb-6">
                Catch mistakes before you <br class="hidden md:block" />
                <span class="text-brand-600">embarrass yourself</span> or cause problems.
            </h1>
            <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10">
                The smart assistant for students and professionals. Ensure every email and assignment is perfect before you hit send.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="#cta" class="px-8 py-4 text-lg font-semibold text-white bg-brand-600 rounded-lg shadow-lg hover:bg-brand-700 hover:shadow-xl transition-all transform hover:-translate-y-0.5">
                    Get Early Access
                </a>
                <a href="#how-it-works" class="px-8 py-4 text-lg font-semibold text-brand-700 bg-brand-50 rounded-lg hover:bg-brand-100 transition-colors">
                    Learn More
                </a>
            </div>
        </div>
        <!-- Decorative Background Element -->
        <div class="absolute top-0 left-1/2 transform -translate-x-1/2 w-full h-full max-w-7xl opacity-30 pointer-events-none">
            <div class="absolute top-20 left-10 w-72 h-72 bg-brand-200 rounded-full mix-blend-multiply filter blur-3xl animate-blob"></div>
            <div class="absolute top-20 right-10 w-72 h-72 bg-purple-200 rounded-full mix-blend-multiply filter blur-3xl animate-blob animation-delay-2000"></div>
            <div class="absolute -bottom-8 left-1/3 w-72 h-72 bg-pink-200 rounded-full mix-blend-multiply filter blur-3xl animate-blob animation-delay-4000"></div>
        </div>
    </section>

    <!-- Problem Section -->
    <section class="py-16 md:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">We’ve All Been There</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">One small slip can have big consequences. Do these sound familiar?</p>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Problem 1 -->
                <div class="p-8 bg-gray-50 rounded-2xl border border-gray-100 hover:shadow-lg transition-shadow">
                    <div class="w-12 h-12 bg-red-100 text-red-600 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 9v2m0 4h.01m-6.938 4h13.856c1.54 0 2.502-1.667 1.732-3L13.732 4c-.77-1.333-2.694-1.333-3.464 0L3.34 16c-.77 1.333.192 3 1.732 3z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Wrong Attachments</h3>
                    <p class="text-gray-600">Sending the wrong file version or forgetting the attachment entirely. "Please find attached..." but nothing is there.</p>
                </div>
                <!-- Problem 2 -->
                <div class="p-8 bg-gray-50 rounded-2xl border border-gray-100 hover:shadow-lg transition-shadow">
                    <div class="w-12 h-12 bg-orange-100 text-orange-600 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 10h.01M12 10h.01M16 10h.01M9 16H5a2 2 0 01-2-2V6a2 2 0 012-2h14a2 2 0 012 2v8a2 2 0 01-2 2h-5l-5 5v-5z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Unprofessional Tone</h3>
                    <p class="text-gray-600">Coming across as too casual, angry, or unclear when you need to be professional and precise.</p>
                </div>
                <!-- Problem 3 -->
                <div class="p-8 bg-gray-50 rounded-2xl border border-gray-100 hover:shadow-lg transition-shadow">
                    <div class="w-12 h-12 bg-yellow-100 text-yellow-600 rounded-lg flex items-center justify-center mb-6">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4l3 3m6-3a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Last-Minute Panic</h3>
                    <p class="text-gray-600">Rushing to meet a deadline often leads to silly mistakes that could have been easily avoided.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Solution Section -->
    <section id="how-it-works" class="py-16 md:py-24 bg-brand-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">How It Works</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Your personal safety net for digital communication.</p>
            </div>
            <div class="grid md:grid-cols-3 gap-12 relative">
                 <!-- Connecting Line (Desktop) -->
                 <div class="hidden md:block absolute top-12 left-0 w-full h-0.5 bg-brand-200 z-0 transform -translate-y-1/2"></div>
                
                <!-- Step 1 -->
                <div class="relative z-10 text-center">
                    <div class="w-24 h-24 mx-auto bg-white rounded-full flex items-center justify-center shadow-md mb-6 border-4 border-brand-100">
                        <span class="text-3xl font-bold text-brand-600">1</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Smart Scan</h3>
                    <p class="text-gray-600">The app automatically scans your message draft, attachments, and recipient list in real-time.</p>
                </div>
                <!-- Step 2 -->
                <div class="relative z-10 text-center">
                    <div class="w-24 h-24 mx-auto bg-white rounded-full flex items-center justify-center shadow-md mb-6 border-4 border-brand-100">
                        <span class="text-3xl font-bold text-brand-600">2</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Clear Warnings</h3>
                    <p class="text-gray-600">Get instant alerts for missing files, risky phrasing, or potential recipient errors.</p>
                </div>
                <!-- Step 3 -->
                <div class="relative z-10 text-center">
                    <div class="w-24 h-24 mx-auto bg-white rounded-full flex items-center justify-center shadow-md mb-6 border-4 border-brand-100">
                        <span class="text-3xl font-bold text-brand-600">3</span>
                    </div>
                    <h3 class="text-xl font-bold text-gray-900 mb-3">Send with Confidence</h3>
                    <p class="text-gray-600">Fix issues with one tap and send your email knowing it’s 100% error-free.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-16 md:py-24 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Key Features</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Everything you need to protect your professional reputation.</p>
            </div>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Feature 1 -->
                <div class="p-6 bg-white border border-gray-200 rounded-xl hover:border-brand-300 hover:shadow-lg transition-all group">
                    <div class="w-10 h-10 bg-brand-100 text-brand-600 rounded-lg flex items-center justify-center mb-4 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M15.172 7l-6.586 6.586a2 2 0 102.828 2.828l6.414-6.586a4 4 0 00-5.656-5.656l-6.415 6.585a6 6 0 108.486 8.486L20.5 13"></path></svg>
                    </div>
                    <h3 class="text-lg font-bold text-gray-900 mb-2">Attachment Checker</h3>
                    <p class="text-sm text-gray-600">Ensures the files you meant to attach are actually there.</p>
                </div>
                <!-- Feature 2 -->
                <div class="p-6 bg-white border border-gray-200 rounded-xl hover:border-brand-300 hover:shadow-lg transition-all group">
                    <div class="w-10 h-10 bg-brand-100 text-brand-600 rounded-lg flex items-center justify-center mb-4 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z"></path></svg>
                    </div>
                    <h3 class="text-lg font-bold text-gray-900 mb-2">File Review</h3>
                    <p class="text-sm text-gray-600">Checks for proper file naming conventions and correct formats.</p>
                </div>
                <!-- Feature 3 -->
                <div class="p-6 bg-white border border-gray-200 rounded-xl hover:border-brand-300 hover:shadow-lg transition-all group">
                    <div class="w-10 h-10 bg-brand-100 text-brand-600 rounded-lg flex items-center justify-center mb-4 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 4.354a4 4 0 110 5.292M15 21H3v-1a6 6 0 0112 0v1zm0 0h6v-1a6 6 0 00-9-5.197M13 7a4 4 0 11-8 0 4 4 0 018 0z"></path></svg>
                    </div>
                    <h3 class="text-lg font-bold text-gray-900 mb-2">Recipient Detection</h3>
                    <p class="text-sm text-gray-600">Flags if you're sending sensitive info to the wrong person (e.g., Reply All).</p>
                </div>
                <!-- Feature 4 -->
                <div class="p-6 bg-white border border-gray-200 rounded-xl hover:border-brand-300 hover:shadow-lg transition-all group">
                    <div class="w-10 h-10 bg-brand-100 text-brand-600 rounded-lg flex items-center justify-center mb-4 group-hover:bg-brand-600 group-hover:text-white transition-colors">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14.828 14.828a4 4 0 01-5.656 0M9 10h.01M15 10h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-lg font-bold text-gray-900 mb-2">Tone Scan</h3>
                    <p class="text-sm text-gray-600">Analyzes your language to ensure it's professional and polite.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Target Users Section -->
    <section class="py-16 md:py-24 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Built For</h2>
                <p class="text-lg text-gray-600 max-w-2xl mx-auto">Whether you're studying or working, we've got your back.</p>
            </div>
            <div class="grid md:grid-cols-2 gap-8 max-w-4xl mx-auto">
                <!-- Students Card -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center">
                    <div class="w-16 h-16 bg-blue-100 text-blue-600 rounded-full flex items-center justify-center mb-6">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M12 14l9-5-9-5-9 5 9 5z"></path><path d="M12 14l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 14l9-5-9-5-9 5 9 5zm0 0l6.16-3.422a12.083 12.083 0 01.665 6.479A11.952 11.952 0 0012 20.055a11.952 11.952 0 00-6.824-2.998 12.078 12.078 0 01.665-6.479L12 14zm-4 6v-7.5l4-2.222"></path></svg>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-900 mb-3">Students</h3>
                    <p class="text-gray-600">Perfect for submitting assignments via email or portals. Never lose points for a silly mistake again.</p>
                </div>
                <!-- Offices Card -->
                <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 flex flex-col items-center text-center">
                    <div class="w-16 h-16 bg-indigo-100 text-indigo-600 rounded-full flex items-center justify-center mb-6">
                        <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4"></path></svg>
                    </div>
                    <h3 class="text-2xl font-bold text-gray-900 mb-3">Office Workers</h3>
                    <p class="text-gray-600">Sending professional emails with attachments? Ensure every client communication is flawless.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Call to Action Section -->
    <section id="cta" class="py-20 bg-gray-900 text-white text-center px-6">
        <div class="max-w-3xl mx-auto">
            <h2 class="text-3xl md:text-5xl font-bold mb-6">Don't let a small mistake cost you.</h2>
            <p class="text-xl text-gray-300 mb-10">One small check can save your reputation, your grade, or your job.</p>
            <form class="max-w-md mx-auto flex flex-col sm:flex-row gap-3">
                <input type="email" placeholder="Enter your email" class="flex-1 px-5 py-3 rounded-lg text-gray-900 focus:outline-none focus:ring-2 focus:ring-brand-500" required>
                <button type="submit" class="px-6 py-3 bg-brand-600 text-white font-semibold rounded-lg hover:bg-brand-500 transition-colors">
                    Join Waitlist
                </button>
            </form>
            <p class="text-sm text-gray-500 mt-4">Join 2,000+ others waiting for early access.</p>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-50 py-12 border-t border-gray-200">
        <div class="max-w-7xl mx-auto px-6 flex flex-col md:flex-row justify-between items-center">
            <div class="mb-4 md:mb-0">
                <span class="text-xl font-bold text-gray-900">Before You Send</span>
                <p class="text-sm text-gray-500 mt-1">© 2024 Before You Send. All rights reserved.</p>
            </div>
            <div class="flex space-x-6">
                <a href="#" class="text-gray-500 hover:text-brand-600 transition-colors">Privacy</a>
                <a href="#" class="text-gray-500 hover:text-brand-600 transition-colors">Terms</a>
                <a href="#" class="text-gray-500 hover:text-brand-600 transition-colors">Contact</a>
            </div>
        </div>
    </footer>

    <!-- Simple Animation Script -->
    <style>
        @keyframes blob {
            0% { transform: translate(0px, 0px) scale(1); }
            33% { transform: translate(30px, -50px) scale(1.1); }
            66% { transform: translate(-20px, 20px) scale(0.9); }
            100% { transform: translate(0px, 0px) scale(1); }
        }
        .animate-blob {
            animation: blob 7s infinite;
        }
        .animation-delay-2000 {
            animation-delay: 2s;
        }
        .animation-delay-4000 {
            animation-delay: 4s;
        }
    </style>
</body>
</html>
