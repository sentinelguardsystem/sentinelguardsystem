<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8"><!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentinel Guard System | Integrated Security & Network Solutions</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#080E1E',
                            navy: '#111B35',
                            teal: '#00A896',
                            cyan: '#02C39A',
                            accent: '#00D9A5',
                            lightBg: '#F0F5F9',
                            cardBg: '#152238',
                            cardBorder: '#1E2F4D'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #080E1E;
            color: #f1f5f9;
        }

        /* Abstract Tech Wave Pattern matching image */
        .cyber-wave-bg {
            background-color: #080E1E;
            background-image: 
                radial-gradient(circle at 80% 20%, rgba(2, 195, 154, 0.15) 0%, transparent 40%),
                radial-gradient(circle at 20% 80%, rgba(0, 168, 150, 0.12) 0%, transparent 50%),
                repeating-linear-gradient(45deg, rgba(2, 195, 154, 0.03) 0px, rgba(2, 195, 154, 0.03) 2px, transparent 2px, transparent 12px);
        }

        .wave-lines {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
            overflow: hidden;
            opacity: 0.35;
        }

        .glow-effect {
            box-shadow: 0 0 25px -5px rgba(2, 195, 154, 0.35);
        }

        .glow-effect-hover:hover {
            box-shadow: 0 0 30px 0px rgba(2, 195, 154, 0.5);
            transform: translateY(-2px);
        }

        .glass-panel {
            background: rgba(21, 34, 56, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(2, 195, 154, 0.2);
        }

        .custom-scrollbar::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #080E1E;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #00A896;
            border-radius: 4px;
        }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 antialiased selection:bg-brand-teal selection:text-white pb-16 md:pb-0 custom-scrollbar">

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-brand-teal via-brand-cyan to-brand-teal text-slate-950 font-bold text-xs md:text-sm py-2 px-4 shadow-md">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="hidden sm:flex items-center gap-2">
                <i class="fa-solid fa-shield-halved"></i>
                <span class="tracking-wide">SENTINEL GUARD SYSTEM — Integrated Security & Network Solutions</span>
            </div>
            <div class="mx-auto sm:mx-0 flex items-center gap-4 text-xs md:text-sm">
                <a href="tel:09517656601" class="hover:underline flex items-center gap-1.5 bg-slate-950/20 px-2.5 py-0.5 rounded-full">
                    <i class="fa-solid fa-phone"></i> 09517656601
                </a>
                <span class="text-slate-950/40">|</span>
                <a href="https://wa.me/639517656601" target="_blank" class="hover:underline flex items-center gap-1.5 bg-slate-950/20 px-2.5 py-0.5 rounded-full">
                    <i class="fa-brands fa-whatsapp"></i> WhatsApp Ready
                </a>
            </div>
        </div>
    </div>

    <!-- Main Navigation Bar -->
    <header class="sticky top-0 z-40 bg-brand-dark/95 backdrop-blur-md border-b border-slate-800/80 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo with Image & Text -->
            <a href="#" class="flex items-center gap-3.5 group">
                <div class="h-14 w-14 flex items-center justify-center p-1.5 bg-slate-900 rounded-xl border border-brand-teal/40 group-hover:border-brand-cyan transition-all shadow-md">
                    <img src="logo.png" alt="Sentinel Guard System Logo" class="h-11 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='https://placehold.co/200x200/0b132b/02c39a?text=SGS+Logo';">
                </div>
                <div>
                    <span class="text-xl font-black tracking-wider text-white block leading-none group-hover:text-brand-cyan transition-colors">SENTINEL</span>
                    <span class="text-xs font-bold tracking-widest text-brand-cyan block mt-1">GUARD SYSTEM</span>
                    <span class="text-[9px] text-slate-400 block tracking-tight">SECURING TODAY, PROTECTING TOMORROW.</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden md:flex items-center gap-7 font-semibold text-slate-300 text-sm">
                <a href="#packages" class="hover:text-brand-cyan transition-colors">CCTV Packages</a>
                <a href="#services" class="hover:text-brand-cyan transition-colors">Our Services</a>
                <a href="#hardware" class="hover:text-brand-cyan transition-colors">Equipment Showcase</a>
                <a href="#repair" class="hover:text-brand-cyan transition-colors">Repairs & Deals</a>
                <a href="#coverage" class="hover:text-brand-cyan transition-colors">Service Area</a>
            </nav>

            <!-- Header Action Button -->
            <div class="hidden lg:flex items-center gap-3">
                <button onclick="openQuoteModal()" class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-extrabold px-5 py-2.5 rounded-xl shadow-lg hover:brightness-110 transition-all text-sm flex items-center gap-2">
                    <i class="fa-solid fa-paper-plane"></i> Request Quote
                </button>
            </div>

            <!-- Mobile Menu Toggle Button -->
            <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white focus:outline-none p-2 rounded-lg bg-slate-800">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>
        </div>

        <!-- Mobile Dropdown Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-brand-navy border-b border-slate-800 px-6 py-4 space-y-3 shadow-2xl">
            <a href="#packages" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">CCTV Packages</a>
            <a href="#services" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Our Services</a>
            <a href="#hardware" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Equipment Highlights</a>
            <a href="#repair" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Repairs & Deals</a>
            <a href="#coverage" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5">Service Coverage Area</a>
            <button onclick="closeMobileMenu(); openQuoteModal()" class="w-full mt-2 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-extrabold py-3 rounded-xl text-center">
                Get Free Estimate
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative cyber-wave-bg overflow-hidden py-16 lg:py-24 border-b border-slate-800/80">
        <!-- SVG Graphic Waves in background matching photo -->
        <svg class="wave-lines" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" preserveAspectRatio="none">
            <path fill="none" stroke="#02C39A" stroke-width="1.5" d="M0,160 C320,300 420,0 740,160 C1060,320 1120,40 1440,160"></path>
            <path fill="none" stroke="#00A896" stroke-width="1" d="M0,180 C300,320 450,20 760,180 C1070,340 1100,60 1440,180"></path>
            <path fill="none" stroke="#02C39A" stroke-width="0.5" d="M0,140 C340,280 400,-20 720,140 C1040,300 1140,20 1440,140"></path>
        </svg>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Text Column -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 bg-slate-900/90 border border-brand-teal/40 px-4 py-2 rounded-full text-brand-cyan text-xs font-bold uppercase tracking-widest shadow-md">
                        <i class="fa-solid fa-shield-halved"></i> Integrated Security & Network Solutions
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-none">
                        SENTINEL GUARD
                        <span class="block text-transparent bg-clip-text bg-gradient-to-r from-brand-teal via-brand-cyan to-brand-accent mt-2">
                            SYSTEM INTEGRATED
                        </span>
                    </h1>

                    <p class="text-slate-300 text-lg md:text-xl font-light leading-relaxed max-w-2xl mx-auto lg:mx-0">
                        <strong class="text-white font-semibold">Securing Today, Protecting Tomorrow.</strong> Premier provider of full-spectrum CCTV surveillance, high-speed fiber & structured cabling, gate barriers, solar power, and total repair services for residential, commercial, and industrial sites.
                    </p>

                    <!-- CTA Buttons -->
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
                        <a href="#packages" class="w-full sm:w-auto px-8 py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl shadow-xl hover:scale-[1.02] transition-all text-center flex items-center justify-center gap-2">
                            <i class="fa-solid fa-boxes-packing text-lg"></i> View CCTV Packages
                        </a>
                        <a href="tel:09517656601" class="w-full sm:w-auto px-7 py-4 bg-slate-900/90 hover:bg-slate-800 text-white font-bold rounded-xl border border-slate-700 transition-all text-center flex items-center justify-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-cyan"></i> Call 09517656601
                        </a>
                        <a href="https://wa.me/639517656601" target="_blank" class="w-full sm:w-auto px-6 py-4 bg-emerald-600 hover:bg-emerald-500 text-white font-bold rounded-xl transition-all text-center flex items-center justify-center gap-2 shadow-lg">
                            <i class="fa-brands fa-whatsapp text-xl"></i> WhatsApp
                        </a>
                    </div>

                    <!-- Trust Bar Badges -->
                    <div class="pt-8 grid grid-cols-2 sm:grid-cols-4 gap-4 text-center border-t border-slate-800/90">
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">SECURE</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Trust</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">SERVICE</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Rely On</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">QUALITY</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Count On</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">PROTECTION</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Deserve</p>
                        </div>
                    </div>
                </div>

                <!-- Right Feature Banner / Emblem Showcase -->
                <div class="lg:col-span-5 space-y-6" id="repair">
                    <!-- High Impact Emblem Display -->
                    <div class="glass-panel p-6 rounded-3xl text-center relative overflow-hidden group">
                        <div class="absolute -top-12 -right-12 w-36 h-36 bg-brand-cyan/20 rounded-full blur-3xl"></div>
                        <img src="logo.png" alt="Sentinel Guard System Security emblem" class="h-44 mx-auto object-contain drop-shadow-2xl group-hover:scale-105 transition-transform duration-300" onerror="this.onerror=null; this.src='https://placehold.co/300x300/0b132b/02c39a?text=Sentinel+Guard+System';">
                        <div class="mt-4 pt-4 border-t border-slate-800">
                            <span class="text-xs font-bold uppercase tracking-widest text-brand-cyan">Professional Grade Security</span>
                            <h3 class="text-xl font-black text-white mt-1">Complete Systems & Installation</h3>
                        </div>
                    </div>

                    <!-- Repair Special Box -->
                    <div class="bg-gradient-to-br from-brand-cardBg to-slate-900 p-6 rounded-3xl border border-brand-teal/40 shadow-2xl relative overflow-hidden glow-effect">
                        <div class="flex items-center gap-4 border-b border-slate-800 pb-4 mb-4">
                            <div class="w-14 h-14 bg-brand-teal/20 text-brand-cyan rounded-2xl flex items-center justify-center text-2xl font-bold border border-brand-teal/30">
                                <i class="fa-solid fa-wrench"></i>
                            </div>
                            <div>
                                <span class="bg-amber-500/20 text-amber-300 border border-amber-500/40 text-[10px] font-black px-2.5 py-0.5 rounded-full uppercase tracking-wider">Special Offers & Deals</span>
                                <h3 class="text-2xl font-extrabold text-white mt-1">REPAIR SPECIAL</h3>
                            </div>
                        </div>
                        <p class="text-slate-300 text-sm mb-4">
                            <strong>All Security System Repairs:</strong> Fast, reliable troubleshooting, rewiring, component replacements, and setup for ALL major brands.
                        </p>
                        <ul class="space-y-2 text-xs text-slate-300 mb-5">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> On-site Diagnostic & Troubleshooting</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> DVR/NVR HDD Data Recovery & Replacements</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> Camera Re-alignment & Lens Cleaning</li>
                        </ul>
                        <button onclick="openQuoteModal('Security Repair Special Booking')" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-center">
                            Book Repair Technician Now
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Hardware & Equipment Showcase -->
    <section id="hardware" class="py-20 bg-brand-dark relative border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Interactive Equipment Specs</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">HARDWARE & EQUIPMENT HIGHLIGHTS</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">Click any hardware component below to view full photo gallery, technical specs, and compatibility info.</p>
            </div>

            <!-- Hardware Grid Cards -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-5" id="hardwareContainer">
                <!-- Javascript will populate interactive equipment cards -->
            </div>
        </div>
    </section>

    <!-- Special CCTV Camera Packages -->
    <section id="packages" class="py-20 bg-slate-950 relative border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Turnkey Surveillance Bundles</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">SPECIAL CCTV CAMERA PACKAGES</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">All-inclusive security packages equipped with HD cameras, high-capacity hard drives, RG6 cabling, professional installation, and mobile app configuration.</p>
            </div>

            <!-- Package Cards Grid -->
            <div class="grid md:grid-cols-3 gap-8 items-stretch">
                
                <!-- 4 Channel Package -->
                <div class="bg-brand-cardBg rounded-3xl border border-slate-800 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 hover:shadow-2xl">
                    <div class="bg-slate-900 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-slate-800 text-slate-300 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2 border border-slate-700">4-Channel Entry Set</span>
                        <h3 class="text-2xl font-black text-white">4 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">15,000</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (4x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>4-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>500GB HDD</strong> Dedicated Surveillance Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>80 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('4 Channel Package - ₱15,000')" class="w-full py-3.5 bg-slate-900 hover:bg-brand-teal hover:text-slate-950 font-black rounded-xl border border-slate-700 transition-all text-center">
                            Select 4-Channel Package
                        </button>
                    </div>
                </div>

                <!-- 8 Channel Package (Featured) -->
                <div class="bg-brand-cardBg rounded-3xl border-2 border-brand-cyan overflow-hidden flex flex-col shadow-2xl relative lg:-translate-y-2 glow-effect">
                    <div class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 text-xs font-black uppercase tracking-widest text-center py-2">
                        ⭐ Most Popular Choice
                    </div>
                    <div class="bg-slate-900/90 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-brand-cyan/20 text-brand-cyan border border-brand-cyan/40 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2">8-Channel Recommended</span>
                        <h3 class="text-2xl font-black text-white">8 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">26,900</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (8x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>8-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> Dedicated Surveillance Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>160 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('8 Channel Package - ₱26,900')" class="w-full py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-center shadow-lg">
                            Select 8-Channel Package
                        </button>
                    </div>
                </div>

                <!-- 16 Channel Package -->
                <div class="bg-brand-cardBg rounded-3xl border border-slate-800 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 hover:shadow-2xl">
                    <div class="bg-slate-900 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-slate-800 text-slate-300 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2 border border-slate-700">16-Channel Enterprise</span>
                        <h3 class="text-2xl font-black text-white">16 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">52,900</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (16x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>16-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> High Capacity Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>320 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('16 Channel Package - ₱52,900')" class="w-full py-3.5 bg-slate-900 hover:bg-brand-teal hover:text-slate-950 font-black rounded-xl border border-slate-700 transition-all text-center">
                            Select 16-Channel Package
                        </button>
                    </div>
                </div>

            </div>

            <!-- Package Inclusions Banner -->
            <div class="mt-12 bg-slate-900/90 border border-slate-800 rounded-2xl p-6 grid grid-cols-2 md:grid-cols-5 gap-4 text-center">
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-hard-drive text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">1TB / 500GB HDD</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Surveillance Drive</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-camera text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">HD Night Vision</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Clear Infrared Tech</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-ethernet text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">RG6 Cable</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Heavy Duty Shielded</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-user-gear text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">Pro Install</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Neat & Tested Wiring</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl col-span-2 md:col-span-1">
                    <i class="fa-solid fa-mobile-signal text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">Mobile App</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">24/7 Remote Access</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Services Section -->
    <section id="services" class="py-20 bg-brand-dark border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Comprehensive Capabilities</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">OUR SERVICES</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">End-to-end integration for security, networks, access controls, and power systems.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- Service 1 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">CCTV Surveillance Systems</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Design, deployment, and configuration for residential, commercial, and industrial security setups.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-wifi"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">WiFi & LAN Network Installation</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Fast, reliable, and secure wireless and local network architecture for homes and commercial buildings.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-sitemap"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Structured Cabling Solutions</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Clean, organized, and high-performance Cat6/Fiber data cabling installations with patch panel management.</p>
                </div>

                <!-- Service 4 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-road-barrier"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Gate Barrier & Vehicle Access</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Smart automated boom barriers, loop detectors, and card reader access systems for subdivisions and parking.</p>
                </div>

                <!-- Service 5 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-door-closed"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Access Control & Door Entry</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Biometric fingerprint readers, RFID cards, keypads, and magnetic lock door entry setups.</p>
                </div>

                <!-- Service 6 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-solar-panel"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Solar Power Systems</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Reliable off-grid and grid-tied solar power solutions providing uninterrupted backup energy.</p>
                </div>

                <!-- Service 7 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-server"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Server & Network Infrastructure</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Server rack cabinets, managed switches, routers, multi-WAN load balancing, and firewall deployments.</p>
                </div>

                <!-- Service 8 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Technical Support & Repair</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Preventative maintenance contracts, hardware replacements, rewiring, and rapid on-site emergency repairs.</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Service Coverage & Contact Section -->
    <section id="coverage" class="py-20 bg-slate-950 border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-12">
                
                <!-- Left Column: Service Area & Info -->
                <div class="lg:col-span-6 space-y-6">
                    <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Locations & Reach</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">SERVICE COVERAGE AREA</h2>
                    
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 space-y-4">
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-teal/20 text-brand-cyan rounded-xl flex items-center justify-center text-xl shrink-0 border border-brand-teal/30">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-extrabold text-white text-lg">Primary Service Areas</h4>
                                <p class="text-slate-300 text-base mt-1.5 leading-relaxed">
                                    <strong>Olongapo City</strong>, <strong>Subic Bay Freeport Zone</strong>, <strong>Zambales</strong>, <strong>Bataan</strong>, and nearby central Luzon provinces.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Direct Contact Card -->
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 space-y-5">
                        <h4 class="font-bold text-white text-lg border-b border-slate-800 pb-3 flex items-center justify-between">
                            <span>Direct Contact Lines</span>
                            <span class="text-xs font-semibold text-brand-cyan uppercase">24/7 Inquiries</span>
                        </h4>
                        <div class="space-y-4">
                            <a href="tel:09517656601" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-brand-teal/10 rounded-lg flex items-center justify-center text-brand-cyan text-lg group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                                    <i class="fa-solid fa-phone"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">Hotline Call</span>
                                    <span class="font-extrabold text-xl text-white">09517656601</span>
                                </div>
                            </a>

                            <a href="https://wa.me/639517656601" target="_blank" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-emerald-500/20 rounded-lg flex items-center justify-center text-emerald-400 text-lg group-hover:bg-emerald-500 group-hover:text-slate-950 transition-colors">
                                    <i class="fa-brands fa-whatsapp text-xl"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">WhatsApp Instant Chat</span>
                                    <span class="font-extrabold text-lg text-white">09517656601</span>
                                </div>
                            </a>

                            <a href="mailto:sentinelguardsystem@gmail.com" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-brand-teal/10 rounded-lg flex items-center justify-center text-brand-cyan text-lg group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                                    <i class="fa-solid fa-envelope"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">Official Email</span>
                                    <span class="font-bold text-sm text-white">sentinelguardsystem@gmail.com</span>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Interactive Inquiry Form -->
                <div class="lg:col-span-6 bg-brand-cardBg p-8 rounded-3xl border border-slate-800 shadow-2xl">
                    <h3 class="text-2xl font-black text-white mb-1">Request Free Estimate</h3>
                    <p class="text-slate-400 text-xs mb-6">Fill out your requirements below and our technical team will respond promptly.</p>
                    
                    <form onsubmit="handleFormSubmit(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Full Name</label>
                            <input type="text" required placeholder="John Doe" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Contact Phone</label>
                                <input type="tel" required placeholder="09123456789" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Location / Town</label>
                                <input type="text" required placeholder="Olongapo / Subic / Bataan" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Select Service Needed</label>
                            <select id="formServiceSelect" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                                <option>CCTV 4 Channel Package - ₱15,000</option>
                                <option>CCTV 8 Channel Package - ₱26,900</option>
                                <option>CCTV 16 Channel Package - ₱52,900</option>
                                <option>Security System Repair / Troubleshooting</option>
                                <option>WiFi & LAN Network Cabling</option>
                                <option>Gate Barrier & Access Systems</option>
                                <option>Solar Power Backup System</option>
                                <option>Custom Industrial Solution</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Project Details / Message</label>
                            <textarea rows="3" placeholder="Describe your property layout, number of points, or issue..." class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm"></textarea>
                        </div>
                        <button type="submit" class="w-full py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-sm uppercase tracking-wider shadow-lg">
                            Submit Request Now
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-brand-dark text-slate-500 py-12 border-t border-slate-800 text-xs text-center relative">
        <div class="max-w-7xl mx-auto px-4 flex flex-col items-center justify-center space-y-4">
            <img src="logo.png" alt="Sentinel Guard System Logo" class="h-16 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='https://placehold.co/200x200/0b132b/02c39a?text=Sentinel+Guard';">
            <div>
                <p class="text-white font-black text-base tracking-wider">SENTINEL GUARD SYSTEM - INTEGRATED SOLUTIONS</p>
                <p class="text-brand-cyan font-bold text-xs mt-1">Securing Today, Protecting Tomorrow.</p>
                <p class="text-slate-500 mt-2">&copy; 2026 Sentinel Guard System. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Mobile Bottom Quick Action Bar -->
    <div class="fixed bottom-0 inset-x-0 bg-slate-900/95 border-t border-slate-800 p-3 flex md:hidden gap-2 z-40 backdrop-blur-md shadow-2xl">
        <a href="tel:09517656601" class="flex-1 bg-brand-cyan text-slate-950 text-center font-black py-2.5 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider">
            <i class="fa-solid fa-phone text-sm"></i> Call 09517656601
        </a>
        <a href="https://wa.me/639517656601" target="_blank" class="flex-1 bg-emerald-600 text-white text-center font-black py-2.5 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider">
            <i class="fa-brands fa-whatsapp text-sm"></i> WhatsApp
        </a>
    </div>

    <!-- Hardware Item Details Modal -->
    <div id="hardwareModal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-brand-cardBg border border-slate-700 rounded-3xl max-w-2xl w-full p-6 sm:p-8 relative shadow-2xl max-h-[90vh] overflow-y-auto custom-scrollbar">
            <button onclick="closeHardwareModal()" class="absolute top-5 right-5 text-slate-400 hover:text-white bg-slate-900 w-9 h-9 rounded-full flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            
            <div id="modalHardwareContent">
                <!-- Javascript injects hardware detail content here -->
            </div>
        </div>
    </div>

    <!-- General Quote Modal -->
    <div id="quoteModal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-brand-cardBg border border-slate-700 rounded-3xl max-w-lg w-full p-6 sm:p-8 relative shadow-2xl">
            <button onclick="closeQuoteModal()" class="absolute top-5 right-5 text-slate-400 hover:text-white bg-slate-900 w-9 h-9 rounded-full flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <h3 id="quoteModalTitle" class="text-2xl font-black text-white mb-1">Request Estimate</h3>
            <p class="text-xs text-slate-400 mb-6">Leave your contact details and our technician will contact you.</p>
            
            <form onsubmit="handleQuoteSubmit(event)" class="space-y-4">
                <input type="text" required placeholder="Your Full Name" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan">
                <input type="tel" required placeholder="Phone Number" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan">
                <textarea rows="3" placeholder="Additional specifications or questions..." class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan"></textarea>
                <button type="submit" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-sm uppercase tracking-wider">
                    Submit Inquiry
                </button>
            </form>
        </div>
    </div>

    <script>
        // Data Structure for Equipment & Hardware Showcase
        const hardwareItems = [
            {
                id: 'bullet-dome-cameras',
                title: 'Bullet & Dome HD Cameras',
                category: 'Surveillance Hardware',
                icon: 'fa-video',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Bullet+%26+Dome+Cameras',
                summary: 'Weatherproof high-definition outdoor bullet and discreet indoor dome surveillance cameras.',
                specs: [
                    'Resolution: 1080p Full HD / 4K UHD Ultra Clear Options',
                    'Night Vision: Smart IR Infrared up to 30 Meters',
                    'Housing: IP67 Weatherproof Dust & Water Resistance',
                    'Wide Dynamic Range (WDR) for balanced glare compensation',
                    'Built-in Noise Reduction and Infrared Cut Filters'
                ]
            },
            {
                id: 'nvr-dvr',
                title: 'NVR & DVR Video Recorders',
                category: 'Central Processing',
                icon: 'fa-server',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Network+Video+Recorder+NVR',
                summary: 'High-capacity standalone video recording hubs with remote network access.',
                specs: [
                    'Channels: 4ch, 8ch, 16ch, and 32ch options available',
                    'Compression: H.265+ for 50% HDD space savings',
                    'Storage: Supports up to 10TB HDD capacities',
                    'Outputs: HDMI & VGA Dual Display Simultaneous Outputs',
                    'Mobile Support: Android & iOS live streaming app setup'
                ]
            },
            {
                id: 'poe-switches',
                title: 'PoE Network Switches',
                category: 'Networking Infrastructure',
                icon: 'fa-network-wired',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=PoE+Network+Switch',
                summary: 'Power over Ethernet switches providing centralized power & data cable delivery.',
                specs: [
                    'Ports: 4-Port, 8-Port, 16-Port, and 24-Port Gigabit PoE+',
                    'Power Budget: Standard IEEE 802.3af/at up to 30W per port',
                    'Extended Range: Long distance transmission mode up to 250m',
                    'Surge Protection: 6KV Lightning protection on all ports'
                ]
            },
            {
                id: 'security-monitors',
                title: 'Dedicated Security Monitors',
                category: 'Display & Control',
                icon: 'fa-desktop',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Security+Monitoring+Displays',
                summary: '24/7 continuous duty commercial grade surveillance monitors.',
                specs: [
                    'Screen Sizes: 19", 22", 24", and 32" Full HD LED Displays',
                    'Durability: Designed for continuous 24/7 commercial operation',
                    'Inputs: HDMI, VGA, and BNC video pass-through ports',
                    'Wide viewing angles with anti-glare protective coating'
                ]
            },
            {
                id: 'gate-barriers',
                title: 'Gate Barrier Systems',
                category: 'Access Control',
                icon: 'fa-road-barrier',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Automated+Gate+Barrier',
                summary: 'Heavy-duty motorized vehicle barriers for subdivisions & commercial buildings.',
                specs: [
                    'Speed: Rapid 1.5s - 6s adjustable boom arm movement',
                    'Features: Vehicle safety loop sensor & anti-smash auto reverse',
                    'Integrations: RFID long-range card readers & license plate cameras',
                    'Manual Release: Quick clutch key during power outage'
                ]
            },
            {
                id: 'intercom-keypads',
                title: 'Intercom & Access Keypads',
                category: 'Door Security',
                icon: 'fa-keyboard',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Intercom+%26+Access+Keypad',
                summary: 'Two-way audio/video door entry keypads and internal station screens.',
                specs: [
                    'Video Intercom: HD Camera with wide viewing angle',
                    'Authentication: PIN Keypad + RFID 125kHz / 13.56MHz cards',
                    'Mobile Remote: Answer doorbell calls directly from smartphone',
                    'Vandal-resistant metallic casing with backlit keys'
                ]
            },
            {
                id: 'smart-locks',
                title: 'Smart Magnetic Locks & Biometrics',
                category: 'Physical Security',
                icon: 'fa-lock',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Smart+Locks+%26+Biometrics',
                summary: 'Heavy-duty magnetic locks, drop bolts, and fingerprint readers.',
                specs: [
                    'Holding Force: 600lbs (280kg) heavy-duty electromagnetic lock',
                    'Biometric: 0.5 sec rapid fingerprint scanner recognition',
                    'Keyless Options: Fingerprint, PIN, RFID card, emergency mechanical key',
                    'Fail-safe / Fail-secure safety configurations'
                ]
            },
            {
                id: 'routers-access-points',
                title: 'Routers & Wi-Fi Access Points',
                category: 'Wireless Networks',
                icon: 'fa-wifi',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Enterprise+WiFi+Access+Points',
                summary: 'High-speed Dual-Band Wi-Fi 6 access points and multi-WAN routers.',
                specs: [
                    'Wi-Fi standard: Dual-Band Wi-Fi 6 AX1800 / AX3000 speeds',
                    'Seamless Roaming: Mesh technology for uninterrupted handoff',
                    'Multi-WAN: Load balancing for dual ISP backup connections',
                    'Guest Access: Isolated secure guest network captive portal'
                ]
            },
            {
                id: 'rg6-cabling',
                title: 'RG6 & Structured Cabling',
                category: 'Cabling Solutions',
                icon: 'fa-ethernet',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Structured+RG6+%26+Cat6+Cabling',
                summary: 'Pure copper RG6 coaxial cables, Cat6 network cables, and patch panels.',
                specs: [
                    'RG6 Coax: Heavy quad-shielding against signal interference',
                    'Cat6 Ethernet: 23AWG Solid Bare Copper for gigabit speed',
                    'Protective Conduit: Flexible PVC or EMT metal conduit routing',
                    'Neat patch panel termination and label organization'
                ]
            },
            {
                id: 'solar-power',
                title: 'Solar Backup Systems',
                category: 'Power Management',
                icon: 'fa-solar-panel',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Solar+Power+Backup+Setup',
                summary: 'Solar panels, LiFePO4 batteries, and hybrid off-grid inverters.',
                specs: [
                    'Inverters: Pure sine wave smart hybrid solar inverters',
                    'Battery: Long-life Lithium Iron Phosphate (LiFePO4) storage',
                    'Continuous Protection: Keeps security systems running during brownouts',
                    'Automated transfer switch for instant backup crossover'
                ]
            }
        ];

        // Populate Hardware Container on Page Load
        function renderHardwareGrid() {
            const container = document.getElementById('hardwareContainer');
            container.innerHTML = '';

            hardwareItems.forEach(item => {
                const card = document.createElement('div');
                card.className = 'bg-brand-cardBg/80 p-5 rounded-2xl border border-slate-800 text-center hover:border-brand-teal transition-all cursor-pointer group hover:-translate-y-1 hover:shadow-xl flex flex-col justify-between';
                card.onclick = () => openHardwareModal(item.id);

                card.innerHTML = `
                    <div>
                        <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-xl font-bold mx-auto mb-3 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                            <i class="fa-solid ${item.icon}"></i>
                        </div>
                        <h4 class="font-extrabold text-white text-sm mb-1 group-hover:text-brand-cyan transition-colors">${item.title}</h4>
                        <span class="text-[10px] text-brand-cyan/80 font-bold uppercase tracking-wider block mb-2">${item.category}</span>
                    </div>
                    <div class="pt-2 border-t border-slate-800/80 mt-2 flex items-center justify-center gap-1 text-[11px] font-bold text-slate-400 group-hover:text-white">
                        <span>View Specs</span>
                        <i class="fa-solid fa-chevron-right text-[10px] text-brand-cyan"></i>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        // Open Hardware Specs Modal
        function openHardwareModal(id) {
            const item = hardwareItems.find(h => h.id === id);
            if (!item) return;

            const modalContent = document.getElementById('modalHardwareContent');
            modalContent.innerHTML = `
                <div class="flex items-center gap-3 border-b border-slate-800 pb-4 mb-5">
                    <div class="w-12 h-12 bg-brand-teal/20 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold border border-brand-teal/30">
                        <i class="fa-solid ${item.icon}"></i>
                    </div>
                    <div>
                        <span class="text-xs font-bold text-brand-cyan uppercase tracking-widest">${item.category}</span>
                        <h3 class="text-2xl font-black text-white">${item.title}</h3>
                    </div>
                </div>

                <div class="grid md:grid-cols-2 gap-6 items-center">
                    <div class="bg-slate-900 rounded-2xl p-2 border border-slate-800 overflow-hidden">
                        <img src="${item.img}" alt="${item.title}" class="w-full h-48 sm:h-56 object-cover rounded-xl">
                    </div>
                    <div class="space-y-3">
                        <h4 class="text-sm font-extrabold text-white uppercase tracking-wider">Equipment Overview</h4>
                        <p class="text-slate-300 text-xs leading-relaxed">${item.summary}</p>
                        
                        <h4 class="text-sm font-extrabold text-white uppercase tracking-wider pt-2">Technical Specifications</h4>
                        <ul class="space-y-2 text-xs text-slate-300">
                            ${item.specs.map(spec => `<li class="flex items-start gap-2"><i class="fa-solid fa-circle-check text-brand-cyan mt-0.5"></i> <span>${spec}</span></li>`).join('')}
                        </ul>
                    </div>
                </div>

                <div class="mt-6 pt-5 border-t border-slate-800 flex flex-col sm:flex-row gap-3 justify-end">
                    <button onclick="closeHardwareModal()" class="px-5 py-2.5 bg-slate-900 text-slate-300 hover:text-white font-bold rounded-xl text-xs border border-slate-800">
                        Close Modal
                    </button>
                    <button onclick="closeHardwareModal(); openQuoteModal('Inquiry for ${item.title}')" class="px-6 py-2.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl text-xs uppercase tracking-wider hover:brightness-110">
                        Inquire About This Hardware
                    </button>
                </div>
            `;

            document.getElementById('hardwareModal').classList.remove('hidden');
        }

        function closeHardwareModal() {
            document.getElementById('hardwareModal').classList.add('hidden');
        }

        // Mobile Nav Dropdown Controls
        const mobileBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');

        mobileBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        function closeMobileMenu() {
            mobileMenu.classList.add('hidden');
        }

        // Quote Modal Functions
        function openQuoteModal(title = 'Request Estimate') {
            document.getElementById('quoteModalTitle').innerText = title;
            document.getElementById('quoteModal').classList.remove('hidden');
        }

        function closeQuoteModal() {
            document.getElementById('quoteModal').classList.add('hidden');
        }

        // Form Submission Notification Banner
        function showNotification(message) {
            const banner = document.createElement('div');
            banner.className = 'fixed top-6 right-6 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 px-6 py-4 rounded-2xl font-black shadow-2xl z-50 flex items-center gap-3 text-sm animate-bounce';
            banner.innerHTML = `<i class="fa-solid fa-circle-check text-xl"></i> <span>${message}</span>`;
            document.body.appendChild(banner);
            setTimeout(() => banner.remove(), 4000);
        }

        function handleFormSubmit(e) {
            e.preventDefault();
            showNotification('Thank you! Inquiry submitted successfully. We will call you back.');
            e.target.reset();
        }

        function handleQuoteSubmit(e) {
            e.preventDefault();
            closeQuoteModal();
            showNotification('Estimate request submitted! Our team will contact you shortly.');
            e.target.reset();
        }

        // Initialize grid on load
        window.onload = function() {
            renderHardwareGrid();
        };
    </script>
</body>
</html>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sentinel Guard System | Integrated Security & Network Solutions</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700;800;900&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        brand: {
                            dark: '#080E1E',
                            navy: '#111B35',
                            teal: '#00A896',
                            cyan: '#02C39A',
                            accent: '#00D9A5',
                            lightBg: '#F0F5F9',
                            cardBg: '#152238',
                            cardBorder: '#1E2F4D'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #080E1E;
            color: #f1f5f9;
        }

        /* Abstract Tech Wave Pattern matching image */
        .cyber-wave-bg {
            background-color: #080E1E;
            background-image: 
                radial-gradient(circle at 80% 20%, rgba(2, 195, 154, 0.15) 0%, transparent 40%),
                radial-gradient(circle at 20% 80%, rgba(0, 168, 150, 0.12) 0%, transparent 50%),
                repeating-linear-gradient(45deg, rgba(2, 195, 154, 0.03) 0px, rgba(2, 195, 154, 0.03) 2px, transparent 2px, transparent 12px);
        }

        .wave-lines {
            position: absolute;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            pointer-events: none;
            overflow: hidden;
            opacity: 0.35;
        }

        .glow-effect {
            box-shadow: 0 0 25px -5px rgba(2, 195, 154, 0.35);
        }

        .glow-effect-hover:hover {
            box-shadow: 0 0 30px 0px rgba(2, 195, 154, 0.5);
            transform: translateY(-2px);
        }

        .glass-panel {
            background: rgba(21, 34, 56, 0.85);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(2, 195, 154, 0.2);
        }

        .custom-scrollbar::-webkit-scrollbar {
            width: 8px;
        }
        .custom-scrollbar::-webkit-scrollbar-track {
            background: #080E1E;
        }
        .custom-scrollbar::-webkit-scrollbar-thumb {
            background: #00A896;
            border-radius: 4px;
        }
    </style>
</head>
<body class="bg-brand-dark text-slate-100 antialiased selection:bg-brand-teal selection:text-white pb-16 md:pb-0 custom-scrollbar">

    <!-- Top Announcement Bar -->
    <div class="bg-gradient-to-r from-brand-teal via-brand-cyan to-brand-teal text-slate-950 font-bold text-xs md:text-sm py-2 px-4 shadow-md">
        <div class="max-w-7xl mx-auto flex justify-between items-center">
            <div class="hidden sm:flex items-center gap-2">
                <i class="fa-solid fa-shield-halved"></i>
                <span class="tracking-wide">SENTINEL GUARD SYSTEM — Integrated Security & Network Solutions</span>
            </div>
            <div class="mx-auto sm:mx-0 flex items-center gap-4 text-xs md:text-sm">
                <a href="tel:09517656601" class="hover:underline flex items-center gap-1.5 bg-slate-950/20 px-2.5 py-0.5 rounded-full">
                    <i class="fa-solid fa-phone"></i> 09517656601
                </a>
                <span class="text-slate-950/40">|</span>
                <a href="https://wa.me/639517656601" target="_blank" class="hover:underline flex items-center gap-1.5 bg-slate-950/20 px-2.5 py-0.5 rounded-full">
                    <i class="fa-brands fa-whatsapp"></i> WhatsApp Ready
                </a>
            </div>
        </div>
    </div>

    <!-- Main Navigation Bar -->
    <header class="sticky top-0 z-40 bg-brand-dark/95 backdrop-blur-md border-b border-slate-800/80 shadow-lg">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 h-20 flex items-center justify-between">
            <!-- Brand Logo with Image & Text -->
            <a href="#" class="flex items-center gap-3.5 group">
                <div class="h-14 w-14 flex items-center justify-center p-1.5 bg-slate-900 rounded-xl border border-brand-teal/40 group-hover:border-brand-cyan transition-all shadow-md">
                    <img src="logo.png" alt="Sentinel Guard System Logo" class="h-11 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='https://placehold.co/200x200/0b132b/02c39a?text=SGS+Logo';">
                </div>
                <div>
                    <span class="text-xl font-black tracking-wider text-white block leading-none group-hover:text-brand-cyan transition-colors">SENTINEL</span>
                    <span class="text-xs font-bold tracking-widest text-brand-cyan block mt-1">GUARD SYSTEM</span>
                    <span class="text-[9px] text-slate-400 block tracking-tight">SECURING TODAY, PROTECTING TOMORROW.</span>
                </div>
            </a>

            <!-- Desktop Nav Links -->
            <nav class="hidden md:flex items-center gap-7 font-semibold text-slate-300 text-sm">
                <a href="#packages" class="hover:text-brand-cyan transition-colors">CCTV Packages</a>
                <a href="#services" class="hover:text-brand-cyan transition-colors">Our Services</a>
                <a href="#hardware" class="hover:text-brand-cyan transition-colors">Equipment Showcase</a>
                <a href="#repair" class="hover:text-brand-cyan transition-colors">Repairs & Deals</a>
                <a href="#coverage" class="hover:text-brand-cyan transition-colors">Service Area</a>
            </nav>

            <!-- Header Action Button -->
            <div class="hidden lg:flex items-center gap-3">
                <button onclick="openQuoteModal()" class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-extrabold px-5 py-2.5 rounded-xl shadow-lg hover:brightness-110 transition-all text-sm flex items-center gap-2">
                    <i class="fa-solid fa-paper-plane"></i> Request Quote
                </button>
            </div>

            <!-- Mobile Menu Toggle Button -->
            <button id="mobileMenuBtn" class="md:hidden text-slate-300 hover:text-white focus:outline-none p-2 rounded-lg bg-slate-800">
                <i class="fa-solid fa-bars text-xl"></i>
            </button>
        </div>

        <!-- Mobile Dropdown Menu -->
        <div id="mobileMenu" class="hidden md:hidden bg-brand-navy border-b border-slate-800 px-6 py-4 space-y-3 shadow-2xl">
            <a href="#packages" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">CCTV Packages</a>
            <a href="#services" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Our Services</a>
            <a href="#hardware" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Equipment Highlights</a>
            <a href="#repair" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5 border-b border-slate-800">Repairs & Deals</a>
            <a href="#coverage" onclick="closeMobileMenu()" class="block text-slate-200 hover:text-brand-cyan font-medium py-1.5">Service Coverage Area</a>
            <button onclick="closeMobileMenu(); openQuoteModal()" class="w-full mt-2 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-extrabold py-3 rounded-xl text-center">
                Get Free Estimate
            </button>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="relative cyber-wave-bg overflow-hidden py-16 lg:py-24 border-b border-slate-800/80">
        <!-- SVG Graphic Waves in background matching photo -->
        <svg class="wave-lines" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320" preserveAspectRatio="none">
            <path fill="none" stroke="#02C39A" stroke-width="1.5" d="M0,160 C320,300 420,0 740,160 C1060,320 1120,40 1440,160"></path>
            <path fill="none" stroke="#00A896" stroke-width="1" d="M0,180 C300,320 450,20 760,180 C1070,340 1100,60 1440,180"></path>
            <path fill="none" stroke="#02C39A" stroke-width="0.5" d="M0,140 C340,280 400,-20 720,140 C1040,300 1140,20 1440,140"></path>
        </svg>

        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
            <div class="grid lg:grid-cols-12 gap-12 items-center">
                
                <!-- Left Text Column -->
                <div class="lg:col-span-7 space-y-6 text-center lg:text-left">
                    <div class="inline-flex items-center gap-2 bg-slate-900/90 border border-brand-teal/40 px-4 py-2 rounded-full text-brand-cyan text-xs font-bold uppercase tracking-widest shadow-md">
                        <i class="fa-solid fa-shield-halved"></i> Integrated Security & Network Solutions
                    </div>

                    <h1 class="text-4xl sm:text-5xl lg:text-6xl font-black text-white tracking-tight leading-none">
                        SENTINEL GUARD
                        <span class="block text-transparent bg-clip-text bg-gradient-to-r from-brand-teal via-brand-cyan to-brand-accent mt-2">
                            SYSTEM INTEGRATED
                        </span>
                    </h1>

                    <p class="text-slate-300 text-lg md:text-xl font-light leading-relaxed max-w-2xl mx-auto lg:mx-0">
                        <strong class="text-white font-semibold">Securing Today, Protecting Tomorrow.</strong> Premier provider of full-spectrum CCTV surveillance, high-speed fiber & structured cabling, gate barriers, solar power, and total repair services for residential, commercial, and industrial sites.
                    </p>

                    <!-- CTA Buttons -->
                    <div class="flex flex-col sm:flex-row items-center justify-center lg:justify-start gap-4 pt-2">
                        <a href="#packages" class="w-full sm:w-auto px-8 py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl shadow-xl hover:scale-[1.02] transition-all text-center flex items-center justify-center gap-2">
                            <i class="fa-solid fa-boxes-packing text-lg"></i> View CCTV Packages
                        </a>
                        <a href="tel:09517656601" class="w-full sm:w-auto px-7 py-4 bg-slate-900/90 hover:bg-slate-800 text-white font-bold rounded-xl border border-slate-700 transition-all text-center flex items-center justify-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-cyan"></i> Call 09517656601
                        </a>
                        <a href="https://wa.me/639517656601" target="_blank" class="w-full sm:w-auto px-6 py-4 bg-emerald-600 hover:bg-emerald-500 text-white font-bold rounded-xl transition-all text-center flex items-center justify-center gap-2 shadow-lg">
                            <i class="fa-brands fa-whatsapp text-xl"></i> WhatsApp
                        </a>
                    </div>

                    <!-- Trust Bar Badges -->
                    <div class="pt-8 grid grid-cols-2 sm:grid-cols-4 gap-4 text-center border-t border-slate-800/90">
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">SECURE</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Trust</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">SERVICE</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Rely On</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">QUALITY</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Can Count On</p>
                        </div>
                        <div class="bg-slate-900/50 p-3 rounded-xl border border-slate-800">
                            <p class="text-brand-cyan font-bold text-xs uppercase tracking-wider">PROTECTION</p>
                            <p class="text-slate-200 font-semibold text-xs mt-1">You Deserve</p>
                        </div>
                    </div>
                </div>

                <!-- Right Feature Banner / Emblem Showcase -->
                <div class="lg:col-span-5 space-y-6" id="repair">
                    <!-- High Impact Emblem Display -->
                    <div class="glass-panel p-6 rounded-3xl text-center relative overflow-hidden group">
                        <div class="absolute -top-12 -right-12 w-36 h-36 bg-brand-cyan/20 rounded-full blur-3xl"></div>
                        <img src="logo.png" alt="Sentinel Guard System Security emblem" class="h-44 mx-auto object-contain drop-shadow-2xl group-hover:scale-105 transition-transform duration-300" onerror="this.onerror=null; this.src='https://placehold.co/300x300/0b132b/02c39a?text=Sentinel+Guard+System';">
                        <div class="mt-4 pt-4 border-t border-slate-800">
                            <span class="text-xs font-bold uppercase tracking-widest text-brand-cyan">Professional Grade Security</span>
                            <h3 class="text-xl font-black text-white mt-1">Complete Systems & Installation</h3>
                        </div>
                    </div>

                    <!-- Repair Special Box -->
                    <div class="bg-gradient-to-br from-brand-cardBg to-slate-900 p-6 rounded-3xl border border-brand-teal/40 shadow-2xl relative overflow-hidden glow-effect">
                        <div class="flex items-center gap-4 border-b border-slate-800 pb-4 mb-4">
                            <div class="w-14 h-14 bg-brand-teal/20 text-brand-cyan rounded-2xl flex items-center justify-center text-2xl font-bold border border-brand-teal/30">
                                <i class="fa-solid fa-wrench"></i>
                            </div>
                            <div>
                                <span class="bg-amber-500/20 text-amber-300 border border-amber-500/40 text-[10px] font-black px-2.5 py-0.5 rounded-full uppercase tracking-wider">Special Offers & Deals</span>
                                <h3 class="text-2xl font-extrabold text-white mt-1">REPAIR SPECIAL</h3>
                            </div>
                        </div>
                        <p class="text-slate-300 text-sm mb-4">
                            <strong>All Security System Repairs:</strong> Fast, reliable troubleshooting, rewiring, component replacements, and setup for ALL major brands.
                        </p>
                        <ul class="space-y-2 text-xs text-slate-300 mb-5">
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> On-site Diagnostic & Troubleshooting</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> DVR/NVR HDD Data Recovery & Replacements</li>
                            <li class="flex items-center gap-2"><i class="fa-solid fa-circle-check text-brand-cyan"></i> Camera Re-alignment & Lens Cleaning</li>
                        </ul>
                        <button onclick="openQuoteModal('Security Repair Special Booking')" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-center">
                            Book Repair Technician Now
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Hardware & Equipment Showcase -->
    <section id="hardware" class="py-20 bg-brand-dark relative border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Interactive Equipment Specs</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">HARDWARE & EQUIPMENT HIGHLIGHTS</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">Click any hardware component below to view full photo gallery, technical specs, and compatibility info.</p>
            </div>

            <!-- Hardware Grid Cards -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-5" id="hardwareContainer">
                <!-- Javascript will populate interactive equipment cards -->
            </div>
        </div>
    </section>

    <!-- Special CCTV Camera Packages -->
    <section id="packages" class="py-20 bg-slate-950 relative border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Turnkey Surveillance Bundles</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">SPECIAL CCTV CAMERA PACKAGES</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">All-inclusive security packages equipped with HD cameras, high-capacity hard drives, RG6 cabling, professional installation, and mobile app configuration.</p>
            </div>

            <!-- Package Cards Grid -->
            <div class="grid md:grid-cols-3 gap-8 items-stretch">
                
                <!-- 4 Channel Package -->
                <div class="bg-brand-cardBg rounded-3xl border border-slate-800 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 hover:shadow-2xl">
                    <div class="bg-slate-900 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-slate-800 text-slate-300 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2 border border-slate-700">4-Channel Entry Set</span>
                        <h3 class="text-2xl font-black text-white">4 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">15,000</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (4x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>4-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>500GB HDD</strong> Dedicated Surveillance Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>80 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('4 Channel Package - ₱15,000')" class="w-full py-3.5 bg-slate-900 hover:bg-brand-teal hover:text-slate-950 font-black rounded-xl border border-slate-700 transition-all text-center">
                            Select 4-Channel Package
                        </button>
                    </div>
                </div>

                <!-- 8 Channel Package (Featured) -->
                <div class="bg-brand-cardBg rounded-3xl border-2 border-brand-cyan overflow-hidden flex flex-col shadow-2xl relative lg:-translate-y-2 glow-effect">
                    <div class="bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 text-xs font-black uppercase tracking-widest text-center py-2">
                        ⭐ Most Popular Choice
                    </div>
                    <div class="bg-slate-900/90 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-brand-cyan/20 text-brand-cyan border border-brand-cyan/40 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2">8-Channel Recommended</span>
                        <h3 class="text-2xl font-black text-white">8 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">26,900</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (8x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>8-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> Dedicated Surveillance Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>160 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('8 Channel Package - ₱26,900')" class="w-full py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-center shadow-lg">
                            Select 8-Channel Package
                        </button>
                    </div>
                </div>

                <!-- 16 Channel Package -->
                <div class="bg-brand-cardBg rounded-3xl border border-slate-800 overflow-hidden flex flex-col hover:border-brand-teal transition-all duration-300 hover:shadow-2xl">
                    <div class="bg-slate-900 p-6 border-b border-slate-800 text-center relative">
                        <span class="inline-block bg-slate-800 text-slate-300 text-xs font-bold px-3 py-1 rounded-full uppercase tracking-wider mb-2 border border-slate-700">16-Channel Enterprise</span>
                        <h3 class="text-2xl font-black text-white">16 CHANNEL PACKAGE</h3>
                        <div class="mt-4 flex justify-center items-baseline">
                            <span class="text-slate-400 text-xl font-bold">₱</span>
                            <span class="text-4xl font-black text-brand-cyan">52,900</span>
                            <span class="text-slate-400 text-xs font-semibold ml-1.5 uppercase">All-In</span>
                        </div>
                    </div>
                    <div class="p-6 flex-1 flex flex-col justify-between space-y-6">
                        <ul class="space-y-3.5 text-slate-300 text-sm">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-video text-brand-cyan mt-1"></i>
                                <span><strong>High-Definition</strong> Dome/Bullet Cameras (16x)</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-server text-brand-cyan mt-1"></i>
                                <span>16-Channel Full HD DVR Recorder</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-hard-drive text-brand-cyan mt-1"></i>
                                <span><strong>1TB HDD</strong> High Capacity Drive</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-network-wired text-brand-cyan mt-1"></i>
                                <span>320 Meters High-Shielding RG6 Coaxial Cable</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-screwdriver-wrench text-brand-cyan mt-1"></i>
                                <span>Professional On-Site Installation</span>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-mobile-screen-button text-brand-cyan mt-1"></i>
                                <span>Remote Mobile Live Viewing App Setup</span>
                            </li>
                        </ul>
                        <button onclick="openQuoteModal('16 Channel Package - ₱52,900')" class="w-full py-3.5 bg-slate-900 hover:bg-brand-teal hover:text-slate-950 font-black rounded-xl border border-slate-700 transition-all text-center">
                            Select 16-Channel Package
                        </button>
                    </div>
                </div>

            </div>

            <!-- Package Inclusions Banner -->
            <div class="mt-12 bg-slate-900/90 border border-slate-800 rounded-2xl p-6 grid grid-cols-2 md:grid-cols-5 gap-4 text-center">
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-hard-drive text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">1TB / 500GB HDD</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Surveillance Drive</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-camera text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">HD Night Vision</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Clear Infrared Tech</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-ethernet text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">RG6 Cable</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Heavy Duty Shielded</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl">
                    <i class="fa-solid fa-user-gear text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">Pro Install</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">Neat & Tested Wiring</p>
                </div>
                <div class="p-3 bg-brand-cardBg/60 rounded-xl col-span-2 md:col-span-1">
                    <i class="fa-solid fa-mobile-signal text-brand-cyan text-2xl mb-2"></i>
                    <p class="text-xs font-extrabold text-white uppercase">Mobile App</p>
                    <p class="text-[10px] text-slate-400 mt-0.5">24/7 Remote Access</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Our Services Section -->
    <section id="services" class="py-20 bg-brand-dark border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center max-w-3xl mx-auto mb-16">
                <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Comprehensive Capabilities</span>
                <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">OUR SERVICES</h2>
                <p class="text-slate-400 mt-2 text-sm sm:text-base">End-to-end integration for security, networks, access controls, and power systems.</p>
            </div>

            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                
                <!-- Service 1 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-video"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">CCTV Surveillance Systems</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Design, deployment, and configuration for residential, commercial, and industrial security setups.</p>
                </div>

                <!-- Service 2 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-wifi"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">WiFi & LAN Network Installation</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Fast, reliable, and secure wireless and local network architecture for homes and commercial buildings.</p>
                </div>

                <!-- Service 3 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-sitemap"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Structured Cabling Solutions</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Clean, organized, and high-performance Cat6/Fiber data cabling installations with patch panel management.</p>
                </div>

                <!-- Service 4 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-road-barrier"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Gate Barrier & Vehicle Access</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Smart automated boom barriers, loop detectors, and card reader access systems for subdivisions and parking.</p>
                </div>

                <!-- Service 5 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-door-closed"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Access Control & Door Entry</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Biometric fingerprint readers, RFID cards, keypads, and magnetic lock door entry setups.</p>
                </div>

                <!-- Service 6 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-solar-panel"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Solar Power Systems</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Reliable off-grid and grid-tied solar power solutions providing uninterrupted backup energy.</p>
                </div>

                <!-- Service 7 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-server"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Server & Network Infrastructure</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Server rack cabinets, managed switches, routers, multi-WAN load balancing, and firewall deployments.</p>
                </div>

                <!-- Service 8 -->
                <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 hover:border-brand-teal transition-all group">
                    <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold mb-4 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <h3 class="text-lg font-bold text-white mb-2">Technical Support & Repair</h3>
                    <p class="text-slate-400 text-xs leading-relaxed">Preventative maintenance contracts, hardware replacements, rewiring, and rapid on-site emergency repairs.</p>
                </div>

            </div>
        </div>
    </section>

    <!-- Service Coverage & Contact Section -->
    <section id="coverage" class="py-20 bg-slate-950 border-b border-slate-800">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid lg:grid-cols-12 gap-12">
                
                <!-- Left Column: Service Area & Info -->
                <div class="lg:col-span-6 space-y-6">
                    <span class="bg-brand-teal/10 text-brand-cyan border border-brand-teal/30 font-bold tracking-widest uppercase text-xs px-3.5 py-1 rounded-full">Locations & Reach</span>
                    <h2 class="text-3xl sm:text-4xl font-black text-white mt-3">SERVICE COVERAGE AREA</h2>
                    
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 space-y-4">
                        <div class="flex items-start gap-4">
                            <div class="w-12 h-12 bg-brand-teal/20 text-brand-cyan rounded-xl flex items-center justify-center text-xl shrink-0 border border-brand-teal/30">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <h4 class="font-extrabold text-white text-lg">Primary Service Areas</h4>
                                <p class="text-slate-300 text-base mt-1.5 leading-relaxed">
                                    <strong>Olongapo City</strong>, <strong>Subic Bay Freeport Zone</strong>, <strong>Zambales</strong>, <strong>Bataan</strong>, and nearby central Luzon provinces.
                                </p>
                            </div>
                        </div>
                    </div>

                    <!-- Direct Contact Card -->
                    <div class="bg-brand-cardBg p-6 rounded-2xl border border-slate-800 space-y-5">
                        <h4 class="font-bold text-white text-lg border-b border-slate-800 pb-3 flex items-center justify-between">
                            <span>Direct Contact Lines</span>
                            <span class="text-xs font-semibold text-brand-cyan uppercase">24/7 Inquiries</span>
                        </h4>
                        <div class="space-y-4">
                            <a href="tel:09517656601" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-brand-teal/10 rounded-lg flex items-center justify-center text-brand-cyan text-lg group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                                    <i class="fa-solid fa-phone"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">Hotline Call</span>
                                    <span class="font-extrabold text-xl text-white">09517656601</span>
                                </div>
                            </a>

                            <a href="https://wa.me/639517656601" target="_blank" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-emerald-500/20 rounded-lg flex items-center justify-center text-emerald-400 text-lg group-hover:bg-emerald-500 group-hover:text-slate-950 transition-colors">
                                    <i class="fa-brands fa-whatsapp text-xl"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">WhatsApp Instant Chat</span>
                                    <span class="font-extrabold text-lg text-white">09517656601</span>
                                </div>
                            </a>

                            <a href="mailto:sentinelguardsystem@gmail.com" class="flex items-center gap-4 text-slate-200 hover:text-brand-cyan transition-colors group p-2 rounded-xl hover:bg-slate-900">
                                <div class="w-10 h-10 bg-brand-teal/10 rounded-lg flex items-center justify-center text-brand-cyan text-lg group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                                    <i class="fa-solid fa-envelope"></i>
                                </div>
                                <div>
                                    <span class="text-xs text-slate-400 block font-semibold">Official Email</span>
                                    <span class="font-bold text-sm text-white">sentinelguardsystem@gmail.com</span>
                                </div>
                            </a>
                        </div>
                    </div>
                </div>

                <!-- Right Column: Interactive Inquiry Form -->
                <div class="lg:col-span-6 bg-brand-cardBg p-8 rounded-3xl border border-slate-800 shadow-2xl">
                    <h3 class="text-2xl font-black text-white mb-1">Request Free Estimate</h3>
                    <p class="text-slate-400 text-xs mb-6">Fill out your requirements below and our technical team will respond promptly.</p>
                    
                    <form onsubmit="handleFormSubmit(event)" class="space-y-4">
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Full Name</label>
                            <input type="text" required placeholder="John Doe" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                            <div>
                                <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Contact Phone</label>
                                <input type="tel" required placeholder="09123456789" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Location / Town</label>
                                <input type="text" required placeholder="Olongapo / Subic / Bataan" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Select Service Needed</label>
                            <select id="formServiceSelect" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm">
                                <option>CCTV 4 Channel Package - ₱15,000</option>
                                <option>CCTV 8 Channel Package - ₱26,900</option>
                                <option>CCTV 16 Channel Package - ₱52,900</option>
                                <option>Security System Repair / Troubleshooting</option>
                                <option>WiFi & LAN Network Cabling</option>
                                <option>Gate Barrier & Access Systems</option>
                                <option>Solar Power Backup System</option>
                                <option>Custom Industrial Solution</option>
                            </select>
                        </div>
                        <div>
                            <label class="block text-xs font-bold text-slate-300 uppercase mb-1">Project Details / Message</label>
                            <textarea rows="3" placeholder="Describe your property layout, number of points, or issue..." class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white focus:outline-none focus:border-brand-cyan transition-colors text-sm"></textarea>
                        </div>
                        <button type="submit" class="w-full py-4 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-sm uppercase tracking-wider shadow-lg">
                            Submit Request Now
                        </button>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-brand-dark text-slate-500 py-12 border-t border-slate-800 text-xs text-center relative">
        <div class="max-w-7xl mx-auto px-4 flex flex-col items-center justify-center space-y-4">
            <img src="logo.png" alt="Sentinel Guard System Logo" class="h-16 w-auto object-contain drop-shadow" onerror="this.onerror=null; this.src='https://placehold.co/200x200/0b132b/02c39a?text=Sentinel+Guard';">
            <div>
                <p class="text-white font-black text-base tracking-wider">SENTINEL GUARD SYSTEM - INTEGRATED SOLUTIONS</p>
                <p class="text-brand-cyan font-bold text-xs mt-1">Securing Today, Protecting Tomorrow.</p>
                <p class="text-slate-500 mt-2">&copy; 2026 Sentinel Guard System. All Rights Reserved.</p>
            </div>
        </div>
    </footer>

    <!-- Mobile Bottom Quick Action Bar -->
    <div class="fixed bottom-0 inset-x-0 bg-slate-900/95 border-t border-slate-800 p-3 flex md:hidden gap-2 z-40 backdrop-blur-md shadow-2xl">
        <a href="tel:09517656601" class="flex-1 bg-brand-cyan text-slate-950 text-center font-black py-2.5 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider">
            <i class="fa-solid fa-phone text-sm"></i> Call 09517656601
        </a>
        <a href="https://wa.me/639517656601" target="_blank" class="flex-1 bg-emerald-600 text-white text-center font-black py-2.5 rounded-xl flex items-center justify-center gap-2 text-xs uppercase tracking-wider">
            <i class="fa-brands fa-whatsapp text-sm"></i> WhatsApp
        </a>
    </div>

    <!-- Hardware Item Details Modal -->
    <div id="hardwareModal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-brand-cardBg border border-slate-700 rounded-3xl max-w-2xl w-full p-6 sm:p-8 relative shadow-2xl max-h-[90vh] overflow-y-auto custom-scrollbar">
            <button onclick="closeHardwareModal()" class="absolute top-5 right-5 text-slate-400 hover:text-white bg-slate-900 w-9 h-9 rounded-full flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            
            <div id="modalHardwareContent">
                <!-- Javascript injects hardware detail content here -->
            </div>
        </div>
    </div>

    <!-- General Quote Modal -->
    <div id="quoteModal" class="fixed inset-0 bg-slate-950/85 backdrop-blur-md z-50 hidden flex items-center justify-center p-4">
        <div class="bg-brand-cardBg border border-slate-700 rounded-3xl max-w-lg w-full p-6 sm:p-8 relative shadow-2xl">
            <button onclick="closeQuoteModal()" class="absolute top-5 right-5 text-slate-400 hover:text-white bg-slate-900 w-9 h-9 rounded-full flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark text-lg"></i>
            </button>
            <h3 id="quoteModalTitle" class="text-2xl font-black text-white mb-1">Request Estimate</h3>
            <p class="text-xs text-slate-400 mb-6">Leave your contact details and our technician will contact you.</p>
            
            <form onsubmit="handleQuoteSubmit(event)" class="space-y-4">
                <input type="text" required placeholder="Your Full Name" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan">
                <input type="tel" required placeholder="Phone Number" class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan">
                <textarea rows="3" placeholder="Additional specifications or questions..." class="w-full bg-slate-900 border border-slate-800 rounded-xl px-4 py-3 text-white text-sm focus:outline-none focus:border-brand-cyan"></textarea>
                <button type="submit" class="w-full py-3.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl hover:brightness-110 transition-all text-sm uppercase tracking-wider">
                    Submit Inquiry
                </button>
            </form>
        </div>
    </div>

    <script>
        // Data Structure for Equipment & Hardware Showcase
        const hardwareItems = [
            {
                id: 'bullet-dome-cameras',
                title: 'Bullet & Dome HD Cameras',
                category: 'Surveillance Hardware',
                icon: 'fa-video',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Bullet+%26+Dome+Cameras',
                summary: 'Weatherproof high-definition outdoor bullet and discreet indoor dome surveillance cameras.',
                specs: [
                    'Resolution: 1080p Full HD / 4K UHD Ultra Clear Options',
                    'Night Vision: Smart IR Infrared up to 30 Meters',
                    'Housing: IP67 Weatherproof Dust & Water Resistance',
                    'Wide Dynamic Range (WDR) for balanced glare compensation',
                    'Built-in Noise Reduction and Infrared Cut Filters'
                ]
            },
            {
                id: 'nvr-dvr',
                title: 'NVR & DVR Video Recorders',
                category: 'Central Processing',
                icon: 'fa-server',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Network+Video+Recorder+NVR',
                summary: 'High-capacity standalone video recording hubs with remote network access.',
                specs: [
                    'Channels: 4ch, 8ch, 16ch, and 32ch options available',
                    'Compression: H.265+ for 50% HDD space savings',
                    'Storage: Supports up to 10TB HDD capacities',
                    'Outputs: HDMI & VGA Dual Display Simultaneous Outputs',
                    'Mobile Support: Android & iOS live streaming app setup'
                ]
            },
            {
                id: 'poe-switches',
                title: 'PoE Network Switches',
                category: 'Networking Infrastructure',
                icon: 'fa-network-wired',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=PoE+Network+Switch',
                summary: 'Power over Ethernet switches providing centralized power & data cable delivery.',
                specs: [
                    'Ports: 4-Port, 8-Port, 16-Port, and 24-Port Gigabit PoE+',
                    'Power Budget: Standard IEEE 802.3af/at up to 30W per port',
                    'Extended Range: Long distance transmission mode up to 250m',
                    'Surge Protection: 6KV Lightning protection on all ports'
                ]
            },
            {
                id: 'security-monitors',
                title: 'Dedicated Security Monitors',
                category: 'Display & Control',
                icon: 'fa-desktop',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Security+Monitoring+Displays',
                summary: '24/7 continuous duty commercial grade surveillance monitors.',
                specs: [
                    'Screen Sizes: 19", 22", 24", and 32" Full HD LED Displays',
                    'Durability: Designed for continuous 24/7 commercial operation',
                    'Inputs: HDMI, VGA, and BNC video pass-through ports',
                    'Wide viewing angles with anti-glare protective coating'
                ]
            },
            {
                id: 'gate-barriers',
                title: 'Gate Barrier Systems',
                category: 'Access Control',
                icon: 'fa-road-barrier',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Automated+Gate+Barrier',
                summary: 'Heavy-duty motorized vehicle barriers for subdivisions & commercial buildings.',
                specs: [
                    'Speed: Rapid 1.5s - 6s adjustable boom arm movement',
                    'Features: Vehicle safety loop sensor & anti-smash auto reverse',
                    'Integrations: RFID long-range card readers & license plate cameras',
                    'Manual Release: Quick clutch key during power outage'
                ]
            },
            {
                id: 'intercom-keypads',
                title: 'Intercom & Access Keypads',
                category: 'Door Security',
                icon: 'fa-keyboard',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Intercom+%26+Access+Keypad',
                summary: 'Two-way audio/video door entry keypads and internal station screens.',
                specs: [
                    'Video Intercom: HD Camera with wide viewing angle',
                    'Authentication: PIN Keypad + RFID 125kHz / 13.56MHz cards',
                    'Mobile Remote: Answer doorbell calls directly from smartphone',
                    'Vandal-resistant metallic casing with backlit keys'
                ]
            },
            {
                id: 'smart-locks',
                title: 'Smart Magnetic Locks & Biometrics',
                category: 'Physical Security',
                icon: 'fa-lock',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Smart+Locks+%26+Biometrics',
                summary: 'Heavy-duty magnetic locks, drop bolts, and fingerprint readers.',
                specs: [
                    'Holding Force: 600lbs (280kg) heavy-duty electromagnetic lock',
                    'Biometric: 0.5 sec rapid fingerprint scanner recognition',
                    'Keyless Options: Fingerprint, PIN, RFID card, emergency mechanical key',
                    'Fail-safe / Fail-secure safety configurations'
                ]
            },
            {
                id: 'routers-access-points',
                title: 'Routers & Wi-Fi Access Points',
                category: 'Wireless Networks',
                icon: 'fa-wifi',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Enterprise+WiFi+Access+Points',
                summary: 'High-speed Dual-Band Wi-Fi 6 access points and multi-WAN routers.',
                specs: [
                    'Wi-Fi standard: Dual-Band Wi-Fi 6 AX1800 / AX3000 speeds',
                    'Seamless Roaming: Mesh technology for uninterrupted handoff',
                    'Multi-WAN: Load balancing for dual ISP backup connections',
                    'Guest Access: Isolated secure guest network captive portal'
                ]
            },
            {
                id: 'rg6-cabling',
                title: 'RG6 & Structured Cabling',
                category: 'Cabling Solutions',
                icon: 'fa-ethernet',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Structured+RG6+%26+Cat6+Cabling',
                summary: 'Pure copper RG6 coaxial cables, Cat6 network cables, and patch panels.',
                specs: [
                    'RG6 Coax: Heavy quad-shielding against signal interference',
                    'Cat6 Ethernet: 23AWG Solid Bare Copper for gigabit speed',
                    'Protective Conduit: Flexible PVC or EMT metal conduit routing',
                    'Neat patch panel termination and label organization'
                ]
            },
            {
                id: 'solar-power',
                title: 'Solar Backup Systems',
                category: 'Power Management',
                icon: 'fa-solar-panel',
                img: 'https://placehold.co/600x400/0b132b/02c39a?text=Solar+Power+Backup+Setup',
                summary: 'Solar panels, LiFePO4 batteries, and hybrid off-grid inverters.',
                specs: [
                    'Inverters: Pure sine wave smart hybrid solar inverters',
                    'Battery: Long-life Lithium Iron Phosphate (LiFePO4) storage',
                    'Continuous Protection: Keeps security systems running during brownouts',
                    'Automated transfer switch for instant backup crossover'
                ]
            }
        ];

        // Populate Hardware Container on Page Load
        function renderHardwareGrid() {
            const container = document.getElementById('hardwareContainer');
            container.innerHTML = '';

            hardwareItems.forEach(item => {
                const card = document.createElement('div');
                card.className = 'bg-brand-cardBg/80 p-5 rounded-2xl border border-slate-800 text-center hover:border-brand-teal transition-all cursor-pointer group hover:-translate-y-1 hover:shadow-xl flex flex-col justify-between';
                card.onclick = () => openHardwareModal(item.id);

                card.innerHTML = `
                    <div>
                        <div class="w-12 h-12 bg-brand-teal/10 text-brand-cyan rounded-xl flex items-center justify-center text-xl font-bold mx-auto mb-3 border border-brand-teal/30 group-hover:bg-brand-teal group-hover:text-slate-950 transition-colors">
                            <i class="fa-solid ${item.icon}"></i>
                        </div>
                        <h4 class="font-extrabold text-white text-sm mb-1 group-hover:text-brand-cyan transition-colors">${item.title}</h4>
                        <span class="text-[10px] text-brand-cyan/80 font-bold uppercase tracking-wider block mb-2">${item.category}</span>
                    </div>
                    <div class="pt-2 border-t border-slate-800/80 mt-2 flex items-center justify-center gap-1 text-[11px] font-bold text-slate-400 group-hover:text-white">
                        <span>View Specs</span>
                        <i class="fa-solid fa-chevron-right text-[10px] text-brand-cyan"></i>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        // Open Hardware Specs Modal
        function openHardwareModal(id) {
            const item = hardwareItems.find(h => h.id === id);
            if (!item) return;

            const modalContent = document.getElementById('modalHardwareContent');
            modalContent.innerHTML = `
                <div class="flex items-center gap-3 border-b border-slate-800 pb-4 mb-5">
                    <div class="w-12 h-12 bg-brand-teal/20 text-brand-cyan rounded-xl flex items-center justify-center text-2xl font-bold border border-brand-teal/30">
                        <i class="fa-solid ${item.icon}"></i>
                    </div>
                    <div>
                        <span class="text-xs font-bold text-brand-cyan uppercase tracking-widest">${item.category}</span>
                        <h3 class="text-2xl font-black text-white">${item.title}</h3>
                    </div>
                </div>

                <div class="grid md:grid-cols-2 gap-6 items-center">
                    <div class="bg-slate-900 rounded-2xl p-2 border border-slate-800 overflow-hidden">
                        <img src="${item.img}" alt="${item.title}" class="w-full h-48 sm:h-56 object-cover rounded-xl">
                    </div>
                    <div class="space-y-3">
                        <h4 class="text-sm font-extrabold text-white uppercase tracking-wider">Equipment Overview</h4>
                        <p class="text-slate-300 text-xs leading-relaxed">${item.summary}</p>
                        
                        <h4 class="text-sm font-extrabold text-white uppercase tracking-wider pt-2">Technical Specifications</h4>
                        <ul class="space-y-2 text-xs text-slate-300">
                            ${item.specs.map(spec => `<li class="flex items-start gap-2"><i class="fa-solid fa-circle-check text-brand-cyan mt-0.5"></i> <span>${spec}</span></li>`).join('')}
                        </ul>
                    </div>
                </div>

                <div class="mt-6 pt-5 border-t border-slate-800 flex flex-col sm:flex-row gap-3 justify-end">
                    <button onclick="closeHardwareModal()" class="px-5 py-2.5 bg-slate-900 text-slate-300 hover:text-white font-bold rounded-xl text-xs border border-slate-800">
                        Close Modal
                    </button>
                    <button onclick="closeHardwareModal(); openQuoteModal('Inquiry for ${item.title}')" class="px-6 py-2.5 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 font-black rounded-xl text-xs uppercase tracking-wider hover:brightness-110">
                        Inquire About This Hardware
                    </button>
                </div>
            `;

            document.getElementById('hardwareModal').classList.remove('hidden');
        }

        function closeHardwareModal() {
            document.getElementById('hardwareModal').classList.add('hidden');
        }

        // Mobile Nav Dropdown Controls
        const mobileBtn = document.getElementById('mobileMenuBtn');
        const mobileMenu = document.getElementById('mobileMenu');

        mobileBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });

        function closeMobileMenu() {
            mobileMenu.classList.add('hidden');
        }

        // Quote Modal Functions
        function openQuoteModal(title = 'Request Estimate') {
            document.getElementById('quoteModalTitle').innerText = title;
            document.getElementById('quoteModal').classList.remove('hidden');
        }

        function closeQuoteModal() {
            document.getElementById('quoteModal').classList.add('hidden');
        }

        // Form Submission Notification Banner
        function showNotification(message) {
            const banner = document.createElement('div');
            banner.className = 'fixed top-6 right-6 bg-gradient-to-r from-brand-teal to-brand-cyan text-slate-950 px-6 py-4 rounded-2xl font-black shadow-2xl z-50 flex items-center gap-3 text-sm animate-bounce';
            banner.innerHTML = `<i class="fa-solid fa-circle-check text-xl"></i> <span>${message}</span>`;
            document.body.appendChild(banner);
            setTimeout(() => banner.remove(), 4000);
        }

        function handleFormSubmit(e) {
            e.preventDefault();
            showNotification('Thank you! Inquiry submitted successfully. We will call you back.');
            e.target.reset();
        }

        function handleQuoteSubmit(e) {
            e.preventDefault();
            closeQuoteModal();
            showNotification('Estimate request submitted! Our team will contact you shortly.');
            e.target.reset();
        }

        // Initialize grid on load
        window.onload = function() {
            renderHardwareGrid();
        };
    </script>
</body>
</html>
