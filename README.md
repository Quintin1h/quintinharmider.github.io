<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Quintin Harmider - Data Analyst Portfolio">
    <title>Quintin Harmider | Data Analyst Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        :root { --tw-color-primary: #1e40af; }
        body { font-family: 'Inter', system_ui, sans-serif; }
        .hero-bg { background: linear-gradient(135deg, #1e40af 0%, #3b82f6 100%); }
        .section-header { position: relative; }
        .section-header::after { content: ''; position: absolute; width: 60px; height: 3px; background-color: #1e40af; bottom: -8px; left: 0; }
        .card { transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1); }
        .card:hover { transform: translateY(-4px); box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1); }
        .nav-link { transition: all 0.3s ease; }
        .nav-link:hover { color: #1e40af; transform: translateY(-1px); }
        .deliverable-btn { transition: all 0.2s; }
        .deliverable-btn:hover { transform: translateY(-1px); }
    </style>
</head>
<body class="bg-slate-50 text-slate-800">

    <!-- NAVBAR -->
    <nav class="bg-white border-b sticky top-0 z-50 shadow-sm">
        <div class="max-w-6xl mx-auto px-6 py-5 flex items-center justify-between">
            <div class="flex items-center gap-x-3">
                <div class="w-9 h-9 bg-[#1e40af] text-white rounded-2xl flex items-center justify-center font-bold text-xl">QH</div>
                <h1 class="text-2xl font-semibold tracking-tight">Quintin Harmider</h1>
            </div>
            <div class="hidden md:flex items-center gap-x-8 text-sm font-medium">
                <a href="#summary" class="nav-link">Summary</a>
                <a href="#skills" class="nav-link">Skills</a>
                <a href="#projects" class="nav-link">Projects</a>
                <a href="#experience" class="nav-link">Experience</a>
                <a href="#education" class="nav-link">Education</a>
                <a href="#certifications" class="nav-link">Certifications</a>
            </div>
            <a href="http://linkedin.com/in/quintin-harmider" target="_blank" class="flex items-center gap-x-2 bg-[#1e40af] hover:bg-[#1e40af]/90 text-white px-6 py-3 rounded-2xl font-semibold text-sm transition-all shadow-lg shadow-blue-500/30">
                <i class="fa-brands fa-linkedin text-lg"></i>
                <span>LinkedIn Profile</span>
                <i class="fa-solid fa-arrow-up-right-from-square text-xs"></i>
            </a>
        </div>
    </nav>

    <!-- HERO -->
    <header class="hero-bg text-white py-16">
        <div class="max-w-6xl mx-auto px-6">
            <div class="flex flex-col lg:flex-row items-center lg:items-end gap-y-10 lg:gap-x-12">
                <div class="flex-1">
                    <div class="inline-flex items-center gap-x-2 bg-white/20 backdrop-blur-md text-white text-sm font-medium px-4 py-2 rounded-3xl mb-6">
                        <span class="relative flex h-3 w-3"><span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-emerald-400 opacity-75"></span><span class="relative inline-flex rounded-full h-3 w-3 bg-emerald-400"></span></span>
                        OPEN TO DATA ANALYST OPPORTUNITIES
                    </div>
                    <h1 class="text-5xl md:text-6xl font-bold tracking-tighter leading-none mb-4">Quintin Harmider</h1>
                    <p class="text-2xl text-white/90 font-medium">Data Analyst Portfolio</p>
                    <p class="mt-6 max-w-lg text-lg text-white/80">Turning complex data into clear, actionable insights for public-sector, nonprofit, and social services organizations.</p>
                </div>
                <div class="flex flex-col items-center lg:items-end">
                    <img src="https://via.placeholder.com/320x320/1e40af/ffffff?text=QH" alt="Quintin Harmider" class="hero-photo w-40 h-40 lg:w-48 lg:h-48 rounded-3xl object-cover border-4 border-white">
                    <div class="mt-8 text-sm flex flex-col lg:items-end gap-y-3">
                        <a href="mailto:quinthur1999@gmail.com" class="flex items-center gap-x-2 hover:text-white/80 transition-colors"><i class="fa-solid fa-envelope"></i><span>quinthur1999@gmail.com</span></a>
                        <a href="tel:+17802655915" class="flex items-center gap-x-2 hover:text-white/80 transition-colors"><i class="fa-solid fa-phone"></i><span>(780) 265-5915</span></a>
                        <div class="flex items-center gap-x-3"><i class="fa-solid fa-location-dot"></i><span>Edmonton, AB</span></div>
                    </div>
                </div>
            </div>
        </div>
    </header>

    <main class="max-w-6xl mx-auto px-6 pb-20">

        <!-- SUMMARY, SKILLS, EXPERIENCE, EDUCATION, CERTIFICATIONS remain unchanged from previous version -->

        <!-- FEATURED PROJECTS WITH LIVE DELIVERABLE LINKS -->
        <section id="projects" class="py-16 border-b">
            <h2 class="section-header text-3xl font-semibold mb-8">Featured Projects</h2>
            <div class="grid md:grid-cols-2 gap-6">

                <!-- YRAP -->
                <div class="card bg-white border border-slate-200 rounded-3xl p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="text-xs font-mono tracking-widest bg-amber-100 text-amber-700 px-3 py-1 rounded-2xl">YOUTH JUSTICE</span>
                        <span class="text-xs text-slate-400">Jan – Apr 2022</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Criminal Justice Case File Analysis</h3>
                    <p class="text-slate-600 mb-6">Youth Restorative Action Project — Edmonton, AB</p>
                    <div class="mt-6 pt-6 border-t">
                        <p class="text-xs uppercase font-medium text-slate-400 mb-3">View Deliverables</p>
                        <div class="flex flex-wrap gap-3">
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Reflection%20Narrative%20Project.pdf" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Reflection Narrative (PDF)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/CSL%20Component%20Presentation(YRAP).pptx" target="_blank" class="deliverable-btn flex-1 text-center bg-purple-50 hover:bg-purple-100 text-purple-700 px-5 py-3 rounded-3xl text-sm font-medium">📊 CSL Presentation (PPTX)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Reflective%20Visual%20Project%20copy%20copy.pptx" target="_blank" class="deliverable-btn flex-1 text-center bg-emerald-50 hover:bg-emerald-100 text-emerald-700 px-5 py-3 rounded-3xl text-sm font-medium">📈 Visual Project Slides (PPTX)</a>
                        </div>
                    </div>
                </div>

                <!-- City of Edmonton -->
                <div class="card bg-white border border-slate-200 rounded-3xl p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="text-xs font-mono tracking-widest bg-emerald-100 text-emerald-700 px-3 py-1 rounded-2xl">MUNICIPAL POLICY</span>
                        <span class="text-xs text-slate-400">Jan – Apr 2021</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Community &amp; Administrative Data Analysis</h3>
                    <p class="text-slate-600 mb-6">City of Edmonton — Neighbourhood Revitalization Internship</p>
                    <div class="mt-6 pt-6 border-t">
                        <p class="text-xs uppercase font-medium text-slate-400 mb-3">View Deliverables</p>
                        <div class="flex flex-wrap gap-3">
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/SOC%20415%20-%20City%20of%20Edmonton%20Final%20Report%20April%202021.pdf" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Full Report (PDF)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Tables%20%26%20Graphs%20Official%20(Excel%20version).xlsx" target="_blank" class="deliverable-btn flex-1 text-center bg-green-50 hover:bg-green-100 text-green-700 px-5 py-3 rounded-3xl text-sm font-medium">📊 Tables &amp; Graphs (Excel)</a>
                        </div>
                    </div>
                </div>

                <!-- EndPovertyEdmonton -->
                <div class="card bg-white border border-slate-200 rounded-3xl p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="text-xs font-mono tracking-widest bg-purple-100 text-purple-700 px-3 py-1 rounded-2xl">POVERTY RESEARCH</span>
                        <span class="text-xs text-slate-400">Jan – Apr 2021</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Qualitative Research &amp; Program Evaluation</h3>
                    <p class="text-slate-600 mb-6">EndPovertyEdmonton — Community-Based Research Placement</p>
                    <div class="mt-6 pt-6 border-t">
                        <p class="text-xs uppercase font-medium text-slate-400 mb-3">View Deliverables</p>
                        <div class="flex flex-wrap gap-3">
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Emergent%20Coding%20Frame.docx" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Emergent Coding Frame (DOCX)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Class%20Coding%20Frame.docx" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Class Coding Frame (DOCX)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Background%20of%20Archbishop%20of%20Edmonton.docx" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Archbishop Background (DOCX)</a>
                            <a href="https://raw.githubusercontent.com/Quintin1h/portfolio-assets/main/Archbishop%20of%20Edmonton%20Interview%20Questions.docx" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Interview Questions (DOCX)</a>
                        </div>
                    </div>
                </div>

                <!-- Victim Advocate -->
                <div class="card bg-white border border-slate-200 rounded-3xl p-8">
                    <div class="flex justify-between items-start mb-4">
                        <span class="text-xs font-mono tracking-widest bg-rose-100 text-rose-700 px-3 py-1 rounded-2xl">VICTIM ADVOCACY</span>
                        <span class="text-xs text-slate-400">Aug 2017 – Apr 2018</span>
                    </div>
                    <h3 class="text-xl font-semibold mb-2">Victim Support Case Documentation</h3>
                    <p class="text-slate-600 mb-6">Camrose District Police &amp; RCMP — Volunteer Victim’s Advocate</p>
                    <div class="mt-6 pt-6 border-t">
                        <p class="text-xs uppercase font-medium text-slate-400 mb-3">View Deliverables</p>
                        <div class="flex flex-wrap gap-3">
                            <a href="#" target="_blank" class="deliverable-btn flex-1 text-center bg-red-50 hover:bg-red-100 text-red-700 px-5 py-3 rounded-3xl text-sm font-medium">📄 Case Documentation Summary (PDF) – Coming Soon</a>
                        </div>
                    </div>
                </div>
            </div>
        </section>

        <!-- The rest of your portfolio (experience, education, certifications, footer) is unchanged and already perfect from previous versions -->

    </main>

    <!-- FOOTER -->
    <footer class="bg-slate-900 text-slate-400 py-12">
        <div class="max-w-6xl mx-auto px-6 text-center">
            <p class="text-sm">© 2026 Quintin Harmider • Data Analyst Portfolio</p>
            <p class="text-xs mt-2 flex justify-center gap-x-6">
                <a href="http://linkedin.com/in/quintin-harmider" target="_blank" class="hover:text-white flex items-center gap-x-1"><i class="fa-brands fa-linkedin"></i> LinkedIn</a>
                <a href="mailto:quinthur1999@gmail.com" class="hover:text-white">Email</a>
                <a href="tel:+17802655915" class="hover:text-white">Phone</a>
            </p>
        </div>
    </footer>

    <script>
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                if (this.getAttribute('href') !== '#') {
                    e.preventDefault();
                    document.querySelector(this.getAttribute('href')).scrollIntoView({ behavior: 'smooth' });
                }
            });
        });
    </script>
</body>
</html>