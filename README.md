<html lang="en" class="scroll-smooth"><head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Taroge Academy Public School</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://code.iconify.design/3/3.1.0/iconify.min.js"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin="">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600&amp;display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        /* Custom scrollbar for webkit */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #f4f4f5; }
        ::-webkit-scrollbar-thumb { background: #d4d4d8; border-radius: 4px; }
        ::-webkit-scrollbar-thumb:hover { background: #a1a1aa; }
        
        /* Custom Focus Rings for "Linear" feel */
        .focus-ring:focus-within {
            box-shadow: 0 0 0 2px rgba(99, 102, 241, 0.2);
            border-color: #6366f1;
        }
    </style>
</head>
<body class="bg-white text-zinc-900 antialiased selection:bg-indigo-100 selection:text-indigo-900">

    <!-- Navigation -->
    <nav class="fixed top-0 w-full z-50 border-b border-zinc-100 bg-white/80 backdrop-blur-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo -->
                <div class="flex items-center gap-2">
                    <div class="w-8 h-8 bg-zinc-900 rounded-lg flex items-center justify-center text-white">
                        <span class="iconify" data-icon="lucide:graduation-cap" data-width="18" data-stroke-width="1.5"></span>
                    </div>
                    <span class="text-sm font-semibold tracking-tight uppercase">TAROGE<span class="text-zinc-400">ACADEMY</span></span>
                </div>

                <!-- Desktop Menu -->
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#about" class="text-xs font-medium text-zinc-500 hover:text-zinc-900 transition-colors">About</a>
                    <a href="#academics" class="text-xs font-medium text-zinc-500 hover:text-zinc-900 transition-colors">Academics</a>
                    <a href="#campus" class="text-xs font-medium text-zinc-500 hover:text-zinc-900 transition-colors">Campus Life</a>
                    <a href="#news" class="text-xs font-medium text-zinc-500 hover:text-zinc-900 transition-colors">News</a>
                </div>

                <!-- CTA -->
                <div class="flex items-center gap-4">
                    <a href="#portal" class="hidden sm:block text-xs font-medium text-zinc-500 hover:text-zinc-900">Parent Portal</a>
                    <a href="#admissions" class="inline-flex items-center justify-center px-4 py-2 text-xs font-medium text-white bg-zinc-900 rounded-md hover:bg-zinc-800 transition-all shadow-sm">
                        Apply Now
                    </a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="absolute inset-0 -z-10 h-full w-full bg-[linear-gradient(to_right,#f4f4f5_1px,transparent_1px),linear-gradient(to_bottom,#f4f4f5_1px,transparent_1px)] bg-[size:4rem_4rem] [mask-image:radial-gradient(ellipse_60%_50%_at_50%_0%,#000_70%,transparent_100%)]"></div>
        
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-zinc-50 border border-zinc-200 mb-8">
                <span class="relative flex h-2 w-2">
                  <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-indigo-400 opacity-75"></span>
                  <span class="relative inline-flex rounded-full h-2 w-2 bg-indigo-500"></span>
                </span>
                <span class="text-xs font-medium text-zinc-600">Admissions Open for 2024-25</span>
            </div>
            
            <h1 class="text-5xl md:text-7xl font-semibold tracking-tighter text-zinc-900 mb-6 max-w-4xl mx-auto">
                Architecting the <br>
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-zinc-900 via-zinc-600 to-zinc-400">Future Leaders.</span>
            </h1>
            
            <p class="text-lg text-zinc-500 max-w-2xl mx-auto mb-10 leading-relaxed font-light">
                Taroge Academy Public School merges traditional values with cutting-edge innovation. We nurture curiosity, critical thinking, and character in a world-class environment.
            </p>
            
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
                <a href="#admissions" class="w-full sm:w-auto px-6 py-3 bg-zinc-900 text-white text-sm font-medium rounded-lg hover:bg-zinc-800 transition-colors flex items-center justify-center gap-2">
                    Begin Registration
                    <span class="iconify" data-icon="lucide:arrow-right" data-width="16" data-stroke-width="1.5"></span>
                </a>
                <a href="#virtual-tour" class="w-full sm:w-auto px-6 py-3 bg-white border border-zinc-200 text-zinc-700 text-sm font-medium rounded-lg hover:bg-zinc-50 transition-colors flex items-center justify-center gap-2">
                    <span class="iconify" data-icon="lucide:play-circle" data-width="16" data-stroke-width="1.5"></span>
                    Virtual Tour
                </a>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="border-y border-zinc-100 bg-zinc-50/50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-12">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8">
                <div class="text-center md:text-left">
                    <p class="text-3xl font-semibold tracking-tight text-zinc-900">25+</p>
                    <p class="text-xs font-medium text-zinc-500 mt-1 uppercase tracking-wider">Years of Excellence</p>
                </div>
                <div class="text-center md:text-left">
                    <p class="text-3xl font-semibold tracking-tight text-zinc-900">100%</p>
                    <p class="text-xs font-medium text-zinc-500 mt-1 uppercase tracking-wider">University Acceptance</p>
                </div>
                <div class="text-center md:text-left">
                    <p class="text-3xl font-semibold tracking-tight text-zinc-900">1:12</p>
                    <p class="text-xs font-medium text-zinc-500 mt-1 uppercase tracking-wider">Teacher Ratio</p>
                </div>
                <div class="text-center md:text-left">
                    <p class="text-3xl font-semibold tracking-tight text-zinc-900">50+</p>
                    <p class="text-xs font-medium text-zinc-500 mt-1 uppercase tracking-wider">Sports &amp; Activities</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Bento Grid / Features -->
    <section id="academics" class="py-24 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="mb-16">
                <h2 class="text-3xl font-semibold tracking-tight text-zinc-900">Holistic Education</h2>
                <p class="text-zinc-500 mt-4 max-w-xl">Our curriculum is designed to balance rigorous academics with creative arts and physical development.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 auto-rows-[300px]">
                <!-- Large Item -->
                <div class="md:col-span-2 row-span-1 md:row-span-2 relative group overflow-hidden rounded-2xl border border-zinc-200 bg-zinc-50 p-8 flex flex-col justify-end">
                    <div class="absolute inset-0 bg-[radial-gradient(#e5e7eb_1px,transparent_1px)] [background-size:16px_16px] [mask-image:radial-gradient(ellipse_50%_50%_at_50%_50%,#000_70%,transparent_100%)]"></div>
                    <div class="relative z-10">
                        <div class="h-10 w-10 bg-white rounded-lg border border-zinc-100 flex items-center justify-center mb-4 shadow-sm">
                            <span class="iconify text-indigo-600" data-icon="lucide:microscope" data-width="20" data-stroke-width="1.5"></span>
                        </div>
                        <h3 class="text-xl font-semibold text-zinc-900 mb-2">STEM &amp; Innovation Labs</h3>
                        <p class="text-sm text-zinc-500 max-w-md">State-of-the-art robotics, physics, and chemistry laboratories where theoretical knowledge meets practical application.</p>
                    </div>
                </div>

                <!-- Small Item 1 -->
                <div class="relative group overflow-hidden rounded-2xl border border-zinc-200 bg-white p-6 hover:shadow-lg transition-all duration-300">
                    <div class="h-8 w-8 bg-zinc-50 rounded-md flex items-center justify-center mb-4">
                        <span class="iconify text-zinc-900" data-icon="lucide:book-open" data-width="18" data-stroke-width="1.5"></span>
                    </div>
                    <h3 class="text-lg font-medium text-zinc-900 mb-2">Global Library</h3>
                    <p class="text-xs text-zinc-500 leading-relaxed">Access to over 50,000 physical volumes and digital journals from universities worldwide.</p>
                </div>

                <!-- Small Item 2 -->
                <div class="relative group overflow-hidden rounded-2xl border border-zinc-200 bg-white p-6 hover:shadow-lg transition-all duration-300">
                    <div class="h-8 w-8 bg-zinc-50 rounded-md flex items-center justify-center mb-4">
                        <span class="iconify text-zinc-900" data-icon="lucide:trophy" data-width="18" data-stroke-width="1.5"></span>
                    </div>
                    <h3 class="text-lg font-medium text-zinc-900 mb-2">Athletics Program</h3>
                    <p class="text-xs text-zinc-500 leading-relaxed">Olympic-size swimming pool, synthetic turf football fields, and indoor basketball courts.</p>
                </div>
                
                <!-- Wide Small Item -->
                <div class="md:col-span-3 lg:col-span-1 relative group overflow-hidden rounded-2xl border border-zinc-200 bg-indigo-600 p-6 text-white flex flex-col justify-between">
                    <div>
                        <span class="iconify mb-4 opacity-80" data-icon="lucide:palette" data-width="24" data-stroke-width="1.5"></span>
                        <h3 class="text-lg font-medium mb-2">Arts &amp; Culture</h3>
                        <p class="text-xs opacity-80 leading-relaxed">Regular exhibitions, drama productions, and music conservatories.</p>
                    </div>
                    <div class="mt-4 flex items-center gap-2 text-xs font-medium opacity-90 cursor-pointer hover:gap-3 transition-all">
                        View Gallery <span class="iconify" data-icon="lucide:arrow-right" data-width="14"></span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- News & Updates -->
    <section id="news" class="py-24 border-t border-zinc-100">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-end mb-12">
                <div>
                    <h2 class="text-2xl font-semibold tracking-tight text-zinc-900">Campus News</h2>
                    <p class="text-sm text-zinc-500 mt-2">Latest happenings at Taroge.</p>
                </div>
                <a href="#" class="text-xs font-medium text-indigo-600 hover:text-indigo-700 flex items-center gap-1">View All <span class="iconify" data-icon="lucide:chevron-right" data-width="14"></span></a>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- News Item -->
                <article class="group cursor-pointer">
                    <div class="aspect-video bg-zinc-100 rounded-lg mb-4 overflow-hidden">
                        <!-- Placeholder for image -->
                        <div class="w-full h-full bg-gradient-to-br from-zinc-200 to-zinc-300 group-hover:scale-105 transition-transform duration-500"></div>
                    </div>
                    <div class="flex items-center gap-2 text-xs text-zinc-400 mb-2">
                        <span>Oct 24, 2023</span>
                        <span>•</span>
                        <span class="text-indigo-600 font-medium">Achievement</span>
                    </div>
                    <h3 class="text-base font-medium text-zinc-900 group-hover:text-indigo-600 transition-colors">Taroge Debate Team Wins Nationals</h3>
                </article>

                <!-- News Item -->
                <article class="group cursor-pointer">
                    <div class="aspect-video bg-zinc-100 rounded-lg mb-4 overflow-hidden">
                         <div class="w-full h-full bg-gradient-to-br from-zinc-200 to-zinc-300 group-hover:scale-105 transition-transform duration-500"></div>
                    </div>
                    <div class="flex items-center gap-2 text-xs text-zinc-400 mb-2">
                        <span>Oct 18, 2023</span>
                        <span>•</span>
                        <span class="text-indigo-600 font-medium">Event</span>
                    </div>
                    <h3 class="text-base font-medium text-zinc-900 group-hover:text-indigo-600 transition-colors">Annual Science Fair Registration Open</h3>
                </article>

                <!-- News Item -->
                <article class="group cursor-pointer">
                    <div class="aspect-video bg-zinc-100 rounded-lg mb-4 overflow-hidden">
                         <div class="w-full h-full bg-gradient-to-br from-zinc-200 to-zinc-300 group-hover:scale-105 transition-transform duration-500"></div>
                    </div>
                    <div class="flex items-center gap-2 text-xs text-zinc-400 mb-2">
                        <span>Sep 30, 2023</span>
                        <span>•</span>
                        <span class="text-indigo-600 font-medium">Community</span>
                    </div>
                    <h3 class="text-base font-medium text-zinc-900 group-hover:text-indigo-600 transition-colors">Charity Drive raises $50k for Local Shelter</h3>
                </article>
            </div>
        </div>
    </section>

    <!-- Registration / Admissions Section -->
    <section id="admissions" class="py-24 bg-zinc-50 border-t border-zinc-200">
        <div class="max-w-3xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <div class="inline-flex items-center justify-center h-12 w-12 rounded-xl bg-white border border-zinc-200 shadow-sm mb-6">
                    <span class="iconify text-zinc-900" data-icon="lucide:file-signature" data-width="24" data-stroke-width="1.5"></span>
                </div>
                <h2 class="text-3xl font-semibold tracking-tight text-zinc-900">Admission Registration</h2>
                <p class="text-zinc-500 mt-3 text-sm">Complete the form below to register your child for the upcoming academic year. Please ensure all details are accurate.</p>
            </div>

            <form class="bg-white shadow-xl shadow-zinc-200/50 rounded-2xl border border-zinc-100 overflow-hidden">
                <!-- Section 1: Student Info -->
                <div class="p-8 border-b border-zinc-100">
                    <h3 class="text-sm font-semibold uppercase tracking-wider text-zinc-400 mb-6 flex items-center gap-2">
                        <span class="iconify" data-icon="lucide:user" data-width="16"></span> Student Information
                    </h3>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <!-- First Name -->
                        <div class="space-y-1">
                            <label class="text-xs font-medium text-zinc-700">First Name</label>
                            <input type="text" class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all placeholder:text-zinc-300" placeholder="John">
                        </div>
                        
                        <!-- Last Name -->
                        <div class="space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Last Name</label>
                            <input type="text" class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all placeholder:text-zinc-300" placeholder="Doe">
                        </div>

                        <!-- DOB -->
                        <div class="space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Date of Birth</label>
                            <input type="date" class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all text-zinc-600">
                        </div>

                        <!-- Grade -->
                        <div class="space-y-1 relative">
                            <label class="text-xs font-medium text-zinc-700">Applying for Grade</label>
                            <div class="relative">
                                <select class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all appearance-none text-zinc-600 cursor-pointer">
                                    <option>Select Grade...</option>
                                    <option>Kindergarten</option>
                                    <option>Grade 1</option>
                                    <option>Grade 2</option>
                                    <option>Grade 3</option>
                                    <option>Grade 4</option>
                                    <option>Grade 5</option>
                                    <option>Grade 6</option>
                                    <option>Grade 7</option>
                                    <option>Grade 8</option>
                                    <option>High School (9-12)</option>
                                </select>
                                <span class="iconify absolute right-3 top-3 text-zinc-400 pointer-events-none" data-icon="lucide:chevron-down" data-width="16"></span>
                            </div>
                        </div>

                        <!-- Gender (Custom Radio) -->
                        <div class="md:col-span-2 space-y-1">
                            <label class="text-xs font-medium text-zinc-700 block mb-2">Gender</label>
                            <div class="flex gap-4">
                                <label class="flex items-center gap-2 cursor-pointer group">
                                    <input type="radio" name="gender" class="hidden peer">
                                    <div class="w-4 h-4 rounded-full border border-zinc-300 peer-checked:border-indigo-600 peer-checked:border-4 transition-all"></div>
                                    <span class="text-sm text-zinc-600 group-hover:text-zinc-900">Male</span>
                                </label>
                                <label class="flex items-center gap-2 cursor-pointer group">
                                    <input type="radio" name="gender" class="hidden peer">
                                    <div class="w-4 h-4 rounded-full border border-zinc-300 peer-checked:border-indigo-600 peer-checked:border-4 transition-all"></div>
                                    <span class="text-sm text-zinc-600 group-hover:text-zinc-900">Female</span>
                                </label>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Section 2: Parent/Guardian Info -->
                <div class="p-8 bg-zinc-50/30">
                    <h3 class="text-sm font-semibold uppercase tracking-wider text-zinc-400 mb-6 flex items-center gap-2">
                        <span class="iconify" data-icon="lucide:users" data-width="16"></span> Guardian Information
                    </h3>
                    
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                        <!-- Guardian Name -->
                        <div class="md:col-span-2 space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Full Name</label>
                            <input type="text" class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all">
                        </div>

                        <!-- Email -->
                        <div class="space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Email Address</label>
                            <div class="relative">
                                <span class="iconify absolute left-3 top-3 text-zinc-400" data-icon="lucide:mail" data-width="16"></span>
                                <input type="email" class="w-full bg-white border border-zinc-200 text-sm rounded-lg pl-9 pr-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all" placeholder="parent@example.com">
                            </div>
                        </div>

                        <!-- Phone -->
                        <div class="space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Phone Number</label>
                            <div class="relative">
                                <span class="iconify absolute left-3 top-3 text-zinc-400" data-icon="lucide:phone" data-width="16"></span>
                                <input type="tel" class="w-full bg-white border border-zinc-200 text-sm rounded-lg pl-9 pr-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all" placeholder="+1 (555) 000-0000">
                            </div>
                        </div>

                        <!-- Address -->
                        <div class="md:col-span-2 space-y-1">
                            <label class="text-xs font-medium text-zinc-700">Residential Address</label>
                            <textarea rows="3" class="w-full bg-white border border-zinc-200 text-sm rounded-lg px-3 py-2.5 outline-none focus:border-indigo-500 focus:ring-1 focus:ring-indigo-500 transition-all resize-none"></textarea>
                        </div>
                    </div>
                </div>

                <!-- Footer/Submit -->
                <div class="p-8 bg-zinc-50 border-t border-zinc-100 flex items-center justify-between">
                    <p class="text-xs text-zinc-400">By clicking Register, you agree to our terms.</p>
                    <button type="button" class="bg-zinc-900 text-white text-sm font-medium px-6 py-2.5 rounded-lg hover:bg-zinc-800 focus:ring-4 focus:ring-zinc-200 transition-all flex items-center gap-2">
                        Submit Application
                        <span class="iconify" data-icon="lucide:send" data-width="14"></span>
                    </button>
                </div>
            </form>
        </div>
    </section>

    <!-- Simple Footer -->
    <footer class="bg-white border-t border-zinc-100 py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8 mb-8">
                <div class="col-span-1 md:col-span-2">
                    <div class="flex items-center gap-2 mb-4">
                        <div class="w-6 h-6 bg-zinc-900 rounded-md flex items-center justify-center text-white">
                            <span class="iconify" data-icon="lucide:graduation-cap" data-width="14"></span>
                        </div>
                        <span class="text-sm font-semibold tracking-tight uppercase">TAROGE</span>
                    </div>
                    <p class="text-sm text-zinc-500 max-w-xs">Empowering the next generation of thinkers, creators, and leaders through excellence in education.</p>
                </div>
                <div>
                    <h4 class="text-sm font-semibold text-zinc-900 mb-3">Quick Links</h4>
                    <ul class="space-y-2 text-sm text-zinc-500">
                        <li><a href="#" class="hover:text-zinc-900 transition-colors">Admissions</a></li>
                        <li><a href="#" class="hover:text-zinc-900 transition-colors">Academic Calendar</a></li>
                        <li><a href="#" class="hover:text-zinc-900 transition-colors">Careers</a></li>
                        <li><a href="#" class="hover:text-zinc-900 transition-colors">Contact Us</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-sm font-semibold text-zinc-900 mb-3">Contact</h4>
                    <ul class="space-y-2 text-sm text-zinc-500">
                        <li class="flex items-center gap-2"><span class="iconify" data-icon="lucide:map-pin" data-width="14"></span> 123 Education Lane, Cityville</li>
                        <li class="flex items-center gap-2"><span class="iconify" data-icon="lucide:phone" data-width="14"></span> +1 (555) 123-4567</li>
                        <li class="flex items-center gap-2"><span class="iconify" data-icon="lucide:mail" data-width="14"></span> info@taroge.edu</li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-zinc-100 pt-8 flex flex-col md:flex-row justify-between items-center gap-4">
                <p class="text-xs text-zinc-400">© 2024 Taroge Academy Public School. All rights reserved.</p>
                <div class="flex gap-4">
                    <a href="#" class="text-zinc-400 hover:text-zinc-900 transition-colors"><span class="iconify" data-icon="lucide:twitter" data-width="16"></span></a>
                    <a href="#" class="text-zinc-400 hover:text-zinc-900 transition-colors"><span class="iconify" data-icon="lucide:instagram" data-width="16"></span></a>
                    <a href="#" class="text-zinc-400 hover:text-zinc-900 transition-colors"><span class="iconify" data-icon="lucide:linkedin" data-width="16"></span></a>
                </div>
            </div>
        </div>
    </footer>

</body></html>


