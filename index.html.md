<!DOCTYPE html>  
<html lang="en" class="dark scroll-smooth">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Abdul Manan | Master Life Strategist, Academic Mentor & Holistic Advisor</title>  
      
    <!-- Tailwind CSS CDN -->  
    <script src="https://cdn.tailwindcss.com"></script>  
      
    <!-- Google Fonts -->  
    <link rel="preconnect" href="https://fonts.googleapis.com">  
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;0,800;1,600&family=Plus+Jakarta+Sans:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">  
      
    <!-- Lucide Icons CDN -->  
    <script src="https://unpkg.com/lucide@latest"></script>  
  
    <!-- Tailwind Configuration -->  
    <script>  
        tailwind.config = {  
            darkMode: 'class',  
            theme: {  
                extend: {  
                    colors: {  
                        darkBg: '#0A0D14',  
                        cardBg: '#121722',  
                        borderCol: '#1E2638',  
                        goldPrimary: '#D4AF37',  
                        goldLight: '#F3E5AB',  
                        goldDark: '#997A15'  
                    },  
                    fontFamily: {  
                        sans: ['Plus Jakarta Sans', 'sans-serif'],  
                        serif: ['Playfair Display', 'serif']  
                    }  
                }  
            }  
        }  
    </script>  
  
    <style>  
        body {  
            font-family: 'Plus Jakarta Sans', sans-serif;  
            background-color: #0A0D14;  
            color: #F3F4F6;  
        }  
        .gold-gradient-text {  
            background: linear-gradient(135deg, #F3E5AB 0%, #D4AF37 50%, #AA820A 100%);  
            -webkit-background-clip: text;  
            -webkit-text-fill-color: transparent;  
        }  
        .gold-glow {  
            box-shadow: 0 0 25px rgba(212, 175, 55, 0.15);  
        }  
        .glass-panel {  
            background: rgba(18, 23, 34, 0.75);  
            backdrop-filter: blur(16px);  
            border: 1px solid rgba(30, 38, 56, 0.8);  
        }  
    </style>  
</head>  
<body class="min-h-screen flex flex-col selection:bg-goldPrimary selection:text-black">  
  
    <!-- Header / Navigation -->  
    <header class="fixed top-0 left-0 right-0 z-50 glass-panel border-b border-borderCol">  
        <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">  
            <div class="flex items-center space-x-3">  
                <div class="w-10 h-10 rounded-xl bg-gradient-to-br from-goldPrimary to-goldDark flex items-center justify-center font-bold text-black text-xl shadow-lg shadow-goldPrimary/20">AM</div>  
                <div>  
                    <span class="font-serif text-lg font-bold tracking-wide text-white">Abdul Manan</span>  
                    <span class="block text-xs text-goldPrimary tracking-widest uppercase">Master Strategist & Mentor</span>  
                </div>  
            </div>  
              
            <nav class="hidden md:flex items-center space-x-8 text-sm font-medium text-gray-300">  
                <a href="#expertise" class="hover:text-goldPrimary transition">Expertise</a>  
                <a href="#services" class="hover:text-goldPrimary transition">Services & Pricing</a>  
                <a href="#calculator" class="hover:text-goldPrimary transition">Planner</a>  
                <a href="#contact" class="hover:text-goldPrimary transition">Direct Connect</a>  
            </nav>  
  
            <div class="flex items-center space-x-4">  
                <a href="https://wa.me/923115840938?text=Hello%20Abdul%20Manan,%20I%20would%20like%20to%20book%20a%20consultation." target="_blank" class="hidden sm:inline-flex items-center space-x-2 bg-gradient-to-r from-goldPrimary to-goldDark text-black font-bold px-5 py-2.5 rounded-xl shadow-lg hover:brightness-110 transition">  
                    <i data-lucide="message-circle" class="w-4 h-4"></i>  
                    <span>Book on WhatsApp</span>  
                </a>  
                <button onclick="openAdminModal()" class="text-xs text-gray-400 hover:text-goldPrimary border border-borderCol px-3 py-2 rounded-lg transition flex items-center space-x-1">  
                    <i data-lucide="shield" class="w-3.5 h-3.5"></i>  
                    <span>Creator Login</span>  
                </button>  
            </div>  
        </div>  
    </header>  
  
    <!-- Hero Section -->  
    <section class="pt-36 pb-20 px-6 relative overflow-hidden">  
        <div class="absolute top-1/4 left-1/2 -translate-x-1/2 -translate-y-1/2 w-[600px] h-[600px] bg-goldPrimary/5 rounded-full blur-3xl pointer-events-none"></div>  
        <div class="max-w-5xl mx-auto text-center relative z-10">  
            <div class="inline-flex items-center space-x-2 px-4 py-2 rounded-full glass-panel border border-goldPrimary/30 text-goldLight text-xs font-semibold uppercase tracking-wider mb-6">  
                <i data-lucide="sparkles" class="w-3.5 h-3.5 text-goldPrimary"></i>  
                <span>Exclusive Elite Advisory & Academic Mentorship</span>  
            </div>  
            <h1 class="text-4xl md:text-6xl lg:text-7xl font-serif font-bold tracking-tight text-white mb-6 leading-tight">  
                Master Your Mind, Physique & <span class="gold-gradient-text">Destiny</span>.  
            </h1>  
            <p class="text-lg md:text-xl text-gray-300 max-w-3xl mx-auto mb-10 font-light">  
                Welcome to the digital sanctuary of Abdul Manan. Uncompromising guidance across advanced sciences, self-mastery, strategic career positioning, relationships, styling, and elite personal growth.  
            </p>  
            <div class="flex flex-col sm:flex-row items-center justify-center gap-4">  
                <a href="#services" class="w-full sm:w-auto px-8 py-4 rounded-xl bg-gradient-to-r from-goldPrimary to-goldDark text-black font-bold text-base shadow-xl hover:scale-105 transition">  
                    Explore Consultation Tiers  
                </a>  
                <a href="https://instagram.com/rocky_manaan1" target="_blank" class="w-full sm:w-auto px-8 py-4 rounded-xl glass-panel text-white font-semibold text-base hover:border-goldPrimary/50 transition flex items-center justify-center space-x-2">  
                    <i data-lucide="instagram" class="w-5 h-5 text-goldPrimary"></i>  
                    <span>Connect @rocky_manaan1</span>  
                </a>  
            </div>  
        </div>  
    </section>  
  
    <!-- Expertise Section -->  
    <section id="expertise" class="py-20 px-6 border-t border-borderCol bg-cardBg/50">  
        <div class="max-w-7xl mx-auto">  
            <div class="text-center max-w-2xl mx-auto mb-16">  
                <h2 class="text-3xl font-serif font-bold text-white mb-4">Multidisciplinary Mastery</h2>  
                <p class="text-gray-400">Deep, rigorous, and actionable expertise curated from specialized academic background and practical execution.</p>  
            </div>  
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="brain" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Self-Growth & Dark Psychology</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Advanced behavioral dynamics, cognitive reframing, study tactics, critical thinking frameworks, and personal motivation.</p>  
                </div>  
  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="dumbbell" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Dieting & Gym Physique Science</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Hypertrophy protocols, precision macronutrient scheduling, fat loss biochemistry, and tailored gym workout design.</p>  
                </div>  
  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="graduation-cap" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Sciences Mentorship & Career Counseling</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Academic tutoring for biology and zoology sciences group students, international Master's university positioning, and career pathing.</p>  
                </div>  
  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="heart-handshake" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Relationship Advice & Solutions</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Emotional intelligence, interpersonal relationship conflict resolution, clarity coaching, and empathy-driven solutions.</p>  
                </div>  
  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="sparkle" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Styling Sense & Perfume Science</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Facial structure grooming analysis, high-impact wardrobe curation, and signature olfactory profiling for niche and designer fragrances.</p>  
                </div>  
  
                <div class="glass-panel p-8 rounded-2xl hover:border-goldPrimary/40 transition group">  
                    <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6 group-hover:scale-110 transition">  
                        <i data-lucide="book-open" class="w-6 h-6"></i>  
                    </div>  
                    <h3 class="text-xl font-bold text-white mb-3">Islamic Teachings & History</h3>  
                    <p class="text-gray-400 text-sm leading-relaxed">Profound civilizational history, moral philosophy grounded in Islamic teachings, and principled decision-making framework.</p>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- Services & Pricing Section -->  
    <section id="services" class="py-20 px-6 border-t border-borderCol">  
        <div class="max-w-7xl mx-auto">  
            <div class="text-center max-w-2xl mx-auto mb-16">  
                <h2 class="text-3xl font-serif font-bold text-white mb-4">Advisory Sessions & Direct Services</h2>  
                <p class="text-gray-400">Select your transformative tier. Book securely and begin your direct 1-on-1 engagement with Abdul Manan.</p>  
            </div>  
              
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">  
                <!-- Tier 1 -->  
                <div class="glass-panel rounded-3xl p-8 flex flex-col justify-between border border-borderCol hover:border-goldPrimary transition">  
                    <div>  
                        <div class="text-xs uppercase font-bold text-goldPrimary tracking-widest mb-2">Strategy Starter</div>  
                        <h3 class="text-2xl font-bold text-white mb-4">1-on-1 Deep Consultation</h3>  
                        <div class="text-4xl font-extrabold text-white mb-6">$50 <span class="text-sm font-normal text-gray-400">/ 60 mins</span></div>  
                        <p class="text-gray-400 text-sm mb-6">Immediate tactical analysis and action plan for your most pressing personal, academic, or fitness bottleneck.</p>  
                        <ul class="space-y-3 text-sm text-gray-300 mb-8">  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>60-Minute Video Session</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Custom Action Roadmap PDF</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Direct WhatsApp Follow-up</span></li>  
                        </ul>  
                    </div>  
                    <a href="https://wa.me/923115840938?text=Hello%20Abdul%20Manan,%20I%20want%20to%20book%20the%201-on-1%20Deep%20Consultation%20($50)." target="_blank" class="w-full py-3.5 rounded-xl bg-goldPrimary/10 hover:bg-goldPrimary hover:text-black text-goldPrimary font-bold text-center transition">  
                        Book Session Now  
                    </a>  
                </div>  
  
                <!-- Tier 2 (Featured) -->  
                <div class="glass-panel rounded-3xl p-8 flex flex-col justify-between border-2 border-goldPrimary gold-glow relative">  
                    <div class="absolute -top-3.5 left-1/2 -translate-x-1/2 bg-gradient-to-r from-goldPrimary to-goldDark text-black text-xs font-bold px-4 py-1 rounded-full uppercase tracking-wider">Most Popular</div>  
                    <div>  
                        <div class="text-xs uppercase font-bold text-goldPrimary tracking-widest mb-2">Total Transformation</div>  
                        <h3 class="text-2xl font-bold text-white mb-4">30-Day Elite Mentorship</h3>  
                        <div class="text-4xl font-extrabold text-white mb-6">$250 <span class="text-sm font-normal text-gray-400">/ month</span></div>  
                        <p class="text-gray-400 text-sm mb-6">Comprehensive oversight across fitness programming, study schedule, dietary optimization, styling, and mindset.</p>  
                        <ul class="space-y-3 text-sm text-gray-300 mb-8">  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Weekly 1-on-1 Video Calls (4 sessions)</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Custom Gym & Diet Blueprint</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Priority Daily WhatsApp Access</span></li>  
                        </ul>  
                    </div>  
                    <a href="https://wa.me/923115840938?text=Hello%20Abdul%20Manan,%20I%20want%20to%20enroll%20in%20the%2030-Day%20Elite%20Mentorship%20($250)." target="_blank" class="w-full py-3.5 rounded-xl bg-gradient-to-r from-goldPrimary to-goldDark text-black font-bold text-center transition hover:brightness-110">  
                        Secure Your Spot  
                    </a>  
                </div>  
  
                <!-- Tier 3 -->  
                <div class="glass-panel rounded-3xl p-8 flex flex-col justify-between border border-borderCol hover:border-goldPrimary transition">  
                    <div>  
                        <div class="text-xs uppercase font-bold text-goldPrimary tracking-widest mb-2">Academic Mastery</div>  
                        <h3 class="text-2xl font-bold text-white mb-4">Sciences Group Tutoring</h3>  
                        <div class="text-4xl font-extrabold text-white mb-6">$120 <span class="text-sm font-normal text-gray-400">/ month</span></div>  
                        <p class="text-gray-400 text-sm mb-6">Rigorous academic coaching for zoology, biology, and sciences students aiming for top-tier university admissions.</p>  
                        <ul class="space-y-3 text-sm text-gray-300 mb-8">  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Bi-Weekly Intensive Tutorials</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>CV & Admissions Strategy</span></li>  
                            <li class="flex items-center space-x-3"><i data-lucide="check" class="w-4 h-4 text-goldPrimary"></i><span>Exam & Study Tactics Review</span></li>  
                        </ul>  
                    </div>  
                    <a href="https://wa.me/923115840938?text=Hello%20Abdul%20Manan,%20I%20want%20to%20book%20Sciences%20Group%20Tutoring%20($120)." target="_blank" class="w-full py-3.5 rounded-xl bg-goldPrimary/10 hover:bg-goldPrimary hover:text-black text-goldPrimary font-bold text-center transition">  
                        Enroll in Tutoring  
                    </a>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- Interactive Transformation Calculator -->  
    <section id="calculator" class="py-20 px-6 border-t border-borderCol bg-cardBg/50">  
        <div class="max-w-4xl mx-auto glass-panel p-8 md:p-12 rounded-3xl border border-goldPrimary/30">  
            <div class="text-center mb-10">  
                <h2 class="text-3xl font-serif font-bold text-white mb-2">Custom Transformation Planner</h2>  
                <p class="text-gray-400 text-sm">Build your customized session plan and get an instant cost estimate.</p>  
            </div>  
              
            <div class="space-y-6">  
                <div>  
                    <label class="block text-sm font-medium text-gray-300 mb-2">Select Primary Focus</label>  
                    <select id="calc-focus" onchange="updateCalculator()" class="w-full bg-cardBg border border-borderCol rounded-xl p-3 text-white focus:outline-none focus:border-goldPrimary">  
                        <option value="Personal Growth & Mindset">Personal Growth & Mindset Strategy</option>  
                        <option value="Gym & Dietary Optimization">Gym & Dietary Optimization</option>  
                        <option value="Sciences Tutoring & Academic Career">Sciences Tutoring & Academic Career</option>  
                        <option value="Styling & Olfactory Grooming">Styling & Olfactory Grooming</option>  
                        <option value="Relationships & Critical Thinking">Relationships & Critical Thinking</option>  
                    </select>  
                </div>  
  
                <div>  
                    <label class="block text-sm font-medium text-gray-300 mb-2">Session Frequency</label>  
                    <div class="grid grid-cols-3 gap-3">  
                        <button type="button" onclick="setFrequency(1)" id="freq-1" class="freq-btn py-3 rounded-xl border border-goldPrimary bg-goldPrimary/20 text-goldLight font-bold">1 Session ($50)</button>  
                        <button type="button" onclick="setFrequency(4)" id="freq-4" class="freq-btn py-3 rounded-xl border border-borderCol bg-cardBg text-gray-400 hover:border-goldPrimary">4 Sessions ($180)</button>  
                        <button type="button" onclick="setFrequency(8)" id="freq-8" class="freq-btn py-3 rounded-xl border border-borderCol bg-cardBg text-gray-400 hover:border-goldPrimary">8 Sessions ($320)</button>  
                    </div>  
                </div>  
  
                <div class="p-6 rounded-2xl bg-cardBg border border-borderCol flex flex-col sm:flex-row items-center justify-between gap-4">  
                    <div>  
                        <span class="text-xs text-gray-400 uppercase tracking-widest">Total Estimated Fee</span>  
                        <div id="calc-total" class="text-3xl font-extrabold text-goldPrimary">$50</div>  
                    </div>  
                    <button onclick="bookCustomPlan()" class="w-full sm:w-auto px-6 py-3.5 rounded-xl bg-gradient-to-r from-goldPrimary to-goldDark text-black font-bold flex items-center justify-center space-x-2 hover:brightness-110 transition">  
                        <i data-lucide="message-circle" class="w-4 h-4"></i>  
                        <span>Book Custom Plan on WhatsApp</span>  
                    </button>  
                </div>  
            </div>  
        </div>  
    </section>  
  
    <!-- Direct Contact Banner -->  
    <section id="contact" class="py-20 px-6 border-t border-borderCol bg-cardBg">  
        <div class="max-w-5xl mx-auto glass-panel p-10 md:p-14 rounded-3xl border border-goldPrimary/30 text-center relative overflow-hidden">  
            <div class="absolute inset-0 bg-gradient-to-r from-goldPrimary/5 to-transparent pointer-events-none"></div>  
            <h2 class="text-3xl md:text-4xl font-serif font-bold text-white mb-4">Ready to Transform Your Life?</h2>  
            <p class="text-gray-300 max-w-xl mx-auto mb-8 text-sm md:text-base">Connect directly with Abdul Manan via WhatsApp or Email for custom inquiries, urgent sessions, or direct booking.</p>  
              
            <div class="flex flex-wrap justify-center gap-4">  
                <a href="https://wa.me/923115840938" target="_blank" class="px-6 py-3 rounded-xl bg-emerald-600 text-white font-semibold flex items-center space-x-2 hover:bg-emerald-500 transition">  
                    <i data-lucide="message-circle" class="w-5 h-5"></i>  
                    <span>WhatsApp: 0311 5840938</span>  
                </a>  
                <a href="mailto:rockymanan34306@gmail.com" class="px-6 py-3 rounded-xl glass-panel text-white font-semibold flex items-center space-x-2 hover:border-goldPrimary transition">  
                    <i data-lucide="mail" class="w-5 h-5 text-goldPrimary"></i>  
                    <span>rockymanan34306@gmail.com</span>  
                </a>  
                <a href="https://instagram.com/rocky_manaan1" target="_blank" class="px-6 py-3 rounded-xl glass-panel text-white font-semibold flex items-center space-x-2 hover:border-goldPrimary transition">  
                    <i data-lucide="instagram" class="w-5 h-5 text-goldPrimary"></i>  
                    <span>@rocky_manaan1</span>  
                </a>  
            </div>  
        </div>  
    </section>  
  
    <!-- Footer -->  
    <footer class="py-10 px-6 border-t border-borderCol text-center text-sm text-gray-500">  
        <div class="max-w-7xl mx-auto flex flex-col sm:flex-row items-center justify-between gap-4">  
            <p>&copy; 2026 Abdul Manan. All Rights Reserved.</p>  
            <div class="flex items-center space-x-6">  
                <a href="https://instagram.com/rocky_manaan1" target="_blank" class="hover:text-goldPrimary transition">Instagram</a>  
                <a href="https://wa.me/923115840938" target="_blank" class="hover:text-goldPrimary transition">WhatsApp</a>  
                <button onclick="openAdminModal()" class="text-goldPrimary hover:underline font-medium">Creator Dashboard</button>  
            </div>  
        </div>  
    </footer>  
  
    <!-- Creator Admin Authentication Modal -->  
    <div id="admin-modal" class="fixed inset-0 z-50 bg-black/80 backdrop-blur-md hidden items-center justify-center p-4">  
        <div class="glass-panel w-full max-w-md rounded-3xl p-8 border border-goldPrimary/40 relative">  
            <button onclick="closeAdminModal()" class="absolute top-6 right-6 text-gray-400 hover:text-white"><i data-lucide="x" class="w-6 h-6"></i></button>  
              
            <div id="login-view">  
                <div class="w-12 h-12 rounded-xl bg-goldPrimary/10 text-goldPrimary flex items-center justify-center mb-6"><i data-lucide="shield-check" class="w-6 h-6"></i></div>  
                <h3 class="text-2xl font-serif font-bold text-white mb-2">Creator Portal Access</h3>  
                <p class="text-gray-400 text-sm mb-6">Enter your Master Admin PIN to unlock management controls.</p>  
                <input type="password" id="admin-pin" placeholder="Enter Admin PIN" class="w-full bg-cardBg border border-borderCol rounded-xl px-4 py-3 text-white mb-4 focus:outline-none focus:border-goldPrimary">  
                <button onclick="verifyAdmin()" class="w-full py-3.5 bg-gradient-to-r from-goldPrimary to-goldDark text-black font-bold rounded-xl shadow-lg hover:brightness-110 transition">Unlock Dashboard</button>  
            </div>  
  
            <div id="dashboard-view" class="hidden">  
                <div class="flex items-center justify-between mb-6">  
                    <h3 class="text-xl font-bold text-white">Creator Control Panel</h3>  
                    <span class="text-xs bg-emerald-500/20 text-emerald-400 px-3 py-1 rounded-full font-semibold">Active Creator</span>  
                </div>  
                <p class="text-gray-300 text-sm mb-6">Welcome, Abdul Manan. Your platform is live and visitors are currently able to book sessions directly to your WhatsApp (`+923115840938`).</p>  
                <div class="space-y-4">  
                    <div class="bg-cardBg p-4 rounded-xl border border-borderCol">  
                        <div class="text-xs text-gray-400 mb-1">Configured Email</div>  
                        <div class="text-white font-medium text-sm">rockymanan34306@gmail.com</div>  
                    </div>  
                    <div class="bg-cardBg p-4 rounded-xl border border-borderCol">  
                        <div class="text-xs text-gray-400 mb-1">Active Instagram</div>  
                        <div class="text-white font-medium text-sm">@rocky_manaan1</div>  
                    </div>  
                    <div class="bg-cardBg p-4 rounded-xl border border-borderCol">  
                        <div class="text-xs text-gray-400 mb-1">WhatsApp Direct Line</div>  
                        <div class="text-white font-medium text-sm">+92 311 5840938</div>  
                    </div>  
                </div>  
                <button onclick="closeAdminModal()" class="w-full mt-6 py-3 bg-borderCol text-white font-semibold rounded-xl hover:bg-gray-800 transition">Close Dashboard</button>  
            </div>  
        </div>  
    </div>  
  
    <!-- Interactive Scripts -->  
    <script>  
        lucide.createIcons();  
  
        let selectedFrequency = 1;  
        let pricePerSession = 50;  
  
        function setFrequency(count) {  
            selectedFrequency = count;  
            document.querySelectorAll('.freq-btn').forEach(btn => {  
                btn.className = 'freq-btn py-3 rounded-xl border border-borderCol bg-cardBg text-gray-400 hover:border-goldPrimary';  
            });  
              
            const activeBtn = document.getElementById(`freq-${count}`);  
            activeBtn.className = 'freq-btn py-3 rounded-xl border border-goldPrimary bg-goldPrimary/20 text-goldLight font-bold';  
              
            updateCalculator();  
        }  
  
        function updateCalculator() {  
            let total = selectedFrequency * pricePerSession;  
            if (selectedFrequency === 4) total = 180;  
            if (selectedFrequency === 8) total = 320;  
              
            document.getElementById('calc-total').innerText = `$${total}`;  
        }  
  
        function bookCustomPlan() {  
            const focus = document.getElementById('calc-focus').value;  
            const total = document.getElementById('calc-total').innerText;  
            const message = `Hello Abdul Manan, I used your custom planner on your website. I want to book ${selectedFrequency} session(s) focused on "${focus}" for ${total}.`;  
            window.open(`https://wa.me/923115840938?text=${encodeURIComponent(message)}`, '_blank');  
        }  
  
        function openAdminModal() {  
            document.getElementById('admin-modal').classList.remove('hidden');  
            document.getElementById('admin-modal').classList.add('flex');  
        }  
  
        function closeAdminModal() {  
            document.getElementById('admin-modal').classList.add('hidden');  
            document.getElementById('admin-modal').classList.remove('flex');  
        }  
  
        function verifyAdmin() {  
            const pin = document.getElementById('admin-pin').value;  
            if (pin === 'manan34306') {  
                document.getElementById('login-view').classList.add('hidden');  
                document.getElementById('dashboard-view').classList.remove('hidden');  
            } else {  
                alert('Invalid Admin PIN. Please enter your secure creator passcode.');  
            }  
        }  
    </script>  
</body>  
</html>  
