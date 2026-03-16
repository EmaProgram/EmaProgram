<!DOCTYPE html>
<html class="dark" lang="en">
<head>
  <meta charset="utf-8" />
  <meta content="width=device-width, initial-scale=1.0" name="viewport" />
  <title>Emanuel Carpio | Portfolio</title>

  <script src="https://cdn.tailwindcss.com?plugins=forms,container-queries"></script>

  <link
    href="https://fonts.googleapis.com/css2?family=Space+Grotesk:wght@300;400;500;600;700&display=swap"
    rel="stylesheet"
  />
  <link
    href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:wght,FILL@100..700,0..1&display=swap"
    rel="stylesheet"
  />
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/devicon.min.css"
  />

  <script id="tailwind-config">
    tailwind.config = {
      darkMode: "class",
      theme: {
        extend: {
          colors: {
            "primary": "#0df2f2",
            "accent-purple": "#a855f7",
            "background-light": "#f5f8f8",
            "background-dark": "#102222",
            "card-dark": "#1a2e2e"
          },
          fontFamily: {
            "display": ["Space Grotesk", "sans-serif"]
          },
          borderRadius: {
            "DEFAULT": "0.25rem",
            "lg": "0.5rem",
            "xl": "0.75rem",
            "full": "9999px"
          }
        }
      }
    };
  </script>

  <style>
    .glass {
      background: rgba(26, 46, 46, 0.6);
      backdrop-filter: blur(12px);
      -webkit-backdrop-filter: blur(12px);
      border: 1px solid rgba(13, 242, 242, 0.1);
    }

    .glow-hover:hover {
      box-shadow: 0 0 20px rgba(13, 242, 242, 0.2);
      border-color: rgba(13, 242, 242, 0.4);
    }

    .hero-gradient {
      background: radial-gradient(
        circle at 50% 50%,
        rgba(13, 242, 242, 0.15) 0%,
        rgba(168, 85, 247, 0.05) 50%,
        transparent 100%
      );
    }

    .tech-icon {
      font-size: 2.25rem;
      line-height: 1;
    }
  </style>
</head>

<body class="bg-background-light dark:bg-background-dark text-slate-900 dark:text-slate-100 font-display selection:bg-primary selection:text-background-dark">
  <div class="relative min-h-screen w-full flex flex-col overflow-x-hidden">
    <header class="fixed top-0 w-full z-50 glass border-b border-primary/10">
      <div class="max-w-7xl mx-auto px-6 h-20 flex items-center justify-between">
        <div class="flex items-center gap-2 group cursor-pointer">
          <div class="size-10 bg-primary/20 rounded-lg flex items-center justify-center text-primary group-hover:bg-primary group-hover:text-background-dark transition-all duration-300">
            <span class="material-symbols-outlined text-2xl">terminal</span>
          </div>
          <span class="text-xl font-bold tracking-tight uppercase">
            Emanuel <span class="text-primary">Carpio</span>
          </span>
        </div>

        <nav class="hidden md:flex items-center gap-10">
          <a class="text-sm font-medium hover:text-primary transition-colors" href="#about">About</a>
          <a class="text-sm font-medium hover:text-primary transition-colors" href="#skills">Skills</a>
          <a class="text-sm font-medium hover:text-primary transition-colors" href="#projects">Projects</a>
          <a class="text-sm font-medium hover:text-primary transition-colors" href="#experience">Experience</a>
          <a class="px-5 py-2.5 bg-primary text-background-dark rounded-lg font-bold text-sm hover:opacity-90 transition-all shadow-lg shadow-primary/20" href="#contact">Contact</a>
        </nav>
      </div>
    </header>

    <main class="flex-grow pt-20">
      <section class="relative min-h-[90vh] flex items-center justify-center px-6 hero-gradient">
        <div class="max-w-5xl w-full text-center py-20">
          <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-primary/10 border border-primary/20 text-primary text-xs font-bold tracking-widest uppercase mb-8">
            <span class="relative flex h-2 w-2">
              <span class="animate-ping absolute inline-flex h-full w-full rounded-full bg-primary opacity-75"></span>
              <span class="relative inline-flex rounded-full h-2 w-2 bg-primary"></span>
            </span>
            Available for opportunities
          </div>

          <h1 class="text-6xl md:text-8xl font-bold mb-6 tracking-tighter leading-none">
            Emanuel <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-accent-purple">Carpio</span>
          </h1>

          <h2 class="text-2xl md:text-3xl font-light text-slate-400 mb-10 max-w-2xl mx-auto leading-relaxed">
            Software Developer focused on building <span class="text-white">responsive, polished, and user-centered</span> web applications.
          </h2>

          <div class="flex flex-col sm:flex-row items-center justify-center gap-4">
            <a class="w-full sm:w-auto px-8 py-4 bg-primary text-background-dark rounded-xl font-bold text-lg hover:scale-105 transition-transform flex items-center justify-center gap-2" href="#projects">
              View Projects <span class="material-symbols-outlined">arrow_forward</span>
            </a>
            <a class="w-full sm:w-auto px-8 py-4 bg-white/5 border border-white/10 text-white rounded-xl font-bold text-lg hover:bg-white/10 transition-all flex items-center justify-center gap-2" href="#">
              Download CV <span class="material-symbols-outlined">download</span>
            </a>
          </div>
        </div>

        <div class="absolute bottom-10 left-1/2 -translate-x-1/2 animate-bounce opacity-50">
          <span class="material-symbols-outlined text-3xl">keyboard_double_arrow_down</span>
        </div>
      </section>

      <section class="py-24 px-6 bg-background-dark" id="about">
        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-16 items-center">
          <div class="relative">
            <div class="aspect-square rounded-3xl overflow-hidden bg-primary/10 border-2 border-primary/20 relative z-10">
              <img
                class="w-full h-full object-cover grayscale hover:grayscale-0 transition-all duration-700"
                src="https://placehold.co/900x900/102222/0df2f2?text=Profile+Photo"
                alt="Developer portrait placeholder"
              />
            </div>
            <div class="absolute -bottom-6 -right-6 w-full h-full border-2 border-accent-purple/30 rounded-3xl -z-0"></div>
          </div>

          <div>
            <h3 class="text-primary font-bold tracking-widest uppercase text-sm mb-4">About Me</h3>
            <h2 class="text-4xl font-bold mb-6 leading-tight text-white">Building reliable digital products with a strong focus on usability.</h2>

            <p class="text-slate-400 text-lg mb-6 leading-relaxed">
              I am a software developer with experience in React, JavaScript, TypeScript, Firebase, MongoDB, and PostgreSQL, along with working knowledge of C++. My approach focuses on building reliable solutions that solve practical problems and deliver a smooth user experience across web and mobile platforms.
            </p>

            <p class="text-slate-400 text-lg mb-8 leading-relaxed">
              I have worked on responsive interfaces, debugging, UI improvements, and full-stack development. I also bring experience in testing workflows and AI evaluation, where I compared model responses, created rubrics, and reviewed repository changes with close attention to quality and consistency.
            </p>

            <div class="grid grid-cols-2 gap-6">
              <div class="p-4 rounded-xl bg-white/5 border border-white/10">
                <div class="text-lg font-bold text-primary mb-1">Focused on</div>
                <div class="text-xs uppercase tracking-wider text-slate-500">Clean Solutions</div>
              </div>
              <div class="p-4 rounded-xl bg-white/5 border border-white/10">
                <div class="text-lg font-bold text-accent-purple mb-1">Driven by</div>
                <div class="text-xs uppercase tracking-wider text-slate-500">User Experience</div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="py-24 px-6 relative overflow-hidden" id="skills">
        <div class="max-w-7xl mx-auto text-center mb-16">
          <h3 class="text-primary font-bold tracking-widest uppercase text-sm mb-4">Expertise</h3>
          <h2 class="text-4xl font-bold text-white">Technical Toolkit</h2>
        </div>

        <div class="max-w-6xl mx-auto grid grid-cols-2 md:grid-cols-4 lg:grid-cols-5 gap-6">
          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-primary/10 flex items-center justify-center text-primary group-hover:scale-110 transition-transform">
              <i class="devicon-react-original tech-icon"></i>
            </div>
            <span class="font-bold text-lg">React</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-yellow-500/10 flex items-center justify-center text-yellow-400 group-hover:scale-110 transition-transform">
              <i class="devicon-javascript-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">JavaScript</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-blue-500/10 flex items-center justify-center text-blue-400 group-hover:scale-110 transition-transform">
              <i class="devicon-typescript-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">TypeScript</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-orange-500/10 flex items-center justify-center text-orange-400 group-hover:scale-110 transition-transform">
              <i class="devicon-firebase-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">Firebase</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-green-500/10 flex items-center justify-center text-green-400 group-hover:scale-110 transition-transform">
              <i class="devicon-mongodb-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">MongoDB</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-sky-500/10 flex items-center justify-center text-sky-400 group-hover:scale-110 transition-transform">
              <i class="devicon-postgresql-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">PostgreSQL</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-indigo-500/10 flex items-center justify-center text-indigo-400 group-hover:scale-110 transition-transform">
              <i class="devicon-cplusplus-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">C++</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-cyan-500/10 flex items-center justify-center text-cyan-400 group-hover:scale-110 transition-transform">
              <i class="devicon-tailwindcss-original tech-icon"></i>
            </div>
            <span class="font-bold text-lg">Tailwind</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-red-500/10 flex items-center justify-center text-red-400 group-hover:scale-110 transition-transform">
              <i class="devicon-git-plain tech-icon"></i>
            </div>
            <span class="font-bold text-lg">Git</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-emerald-500/10 flex items-center justify-center text-emerald-400 group-hover:scale-110 transition-transform">
              <span class="material-symbols-outlined text-4xl">verified</span>
            </div>
            <span class="font-bold text-lg">Testing</span>
          </div>

          <div class="group p-8 glass rounded-2xl flex flex-col items-center gap-4 hover:border-primary/50 transition-all duration-300">
            <div class="size-16 rounded-xl bg-pink-500/10 flex items-center justify-center text-pink-400 group-hover:scale-110 transition-transform">
              <span class="material-symbols-outlined text-4xl">auto_awesome</span>
            </div>
            <span class="font-bold text-lg text-center">AI Evaluation</span>
          </div>
        </div>
      </section>

      <section class="py-24 px-6 bg-background-dark/50" id="projects">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row md:items-end justify-between mb-16 gap-6">
          <div>
            <h3 class="text-primary font-bold tracking-widest uppercase text-sm mb-4">Portfolio</h3>
            <h2 class="text-4xl font-bold text-white">Featured Projects</h2>
          </div>
          <a class="text-primary font-bold flex items-center gap-2 hover:gap-4 transition-all group" href="#">
            Browse all work
            <span class="material-symbols-outlined group-hover:translate-x-1 transition-transform">arrow_forward</span>
          </a>
        </div>

        <div class="max-w-7xl mx-auto grid md:grid-cols-2 gap-8">
          <div class="group glass rounded-3xl overflow-hidden glow-hover transition-all duration-500">
            <div class="aspect-video relative overflow-hidden">
              <img
                class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                src="https://placehold.co/1200x700/102222/0df2f2?text=Water+Management+System"
                alt="Water Management System project preview"
              />
              <div class="absolute inset-0 bg-background-dark/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4">
                <a class="px-4 py-2 rounded-full bg-white text-background-dark flex items-center gap-2 font-bold hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">link</span> Live Demo
                </a>
                <a class="size-12 rounded-full bg-white text-background-dark flex items-center justify-center hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">code</span>
                </a>
              </div>
            </div>
            <div class="p-8">
              <div class="flex gap-2 mb-4 flex-wrap">
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">React</span>
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">MongoDB</span>
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">JavaScript</span>
              </div>
              <h4 class="text-2xl font-bold text-white mb-2">Water Management System</h4>
              <p class="text-slate-400 mb-6">
                Full-stack web and mobile-friendly system built for a local community organization to manage water service records, user data, and operational workflows.
              </p>
            </div>
          </div>

          <div class="group glass rounded-3xl overflow-hidden glow-hover transition-all duration-500">
            <div class="aspect-video relative overflow-hidden">
              <img
                class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                src="https://placehold.co/1200x700/102222/a855f7?text=Collaborative+Task+Board"
                alt="Collaborative Task Board project preview"
              />
              <div class="absolute inset-0 bg-background-dark/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4">
                <a class="px-4 py-2 rounded-full bg-white text-background-dark flex items-center gap-2 font-bold hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">link</span> Live Demo
                </a>
                <a class="size-12 rounded-full bg-white text-background-dark flex items-center justify-center hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">code</span>
                </a>
              </div>
            </div>
            <div class="p-8">
              <div class="flex gap-2 mb-4 flex-wrap">
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">TypeScript</span>
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">Firebase</span>
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">Tailwind</span>
              </div>
              <h4 class="text-2xl font-bold text-white mb-2">Collaborative Task Board</h4>
              <p class="text-slate-400 mb-6">
                A responsive productivity platform designed to organize tasks, statuses, and team workflows with a clean interface and real-time data handling.
              </p>
            </div>
          </div>

          <div class="group glass rounded-3xl overflow-hidden glow-hover transition-all duration-500">
            <div class="aspect-video relative overflow-hidden">
              <img
                class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                src="https://placehold.co/1200x700/102222/0df2f2?text=Modern+Portfolio+Website"
                alt="Modern Portfolio Website project preview"
              />
              <div class="absolute inset-0 bg-background-dark/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4">
                <a class="px-4 py-2 rounded-full bg-white text-background-dark flex items-center gap-2 font-bold hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">link</span> Live Demo
                </a>
                <a class="size-12 rounded-full bg-white text-background-dark flex items-center justify-center hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">code</span>
                </a>
              </div>
            </div>
            <div class="p-8">
              <div class="flex gap-2 mb-4 flex-wrap">
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">React</span>
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">Tailwind</span>
                <span class="px-2.5 py-1 rounded bg-primary/10 text-primary text-[10px] font-bold uppercase tracking-wider">Responsive UI</span>
              </div>
              <h4 class="text-2xl font-bold text-white mb-2">Modern Portfolio Website</h4>
              <p class="text-slate-400 mb-6">
                A dark-themed portfolio interface focused on responsive layout, visual hierarchy, polished interactions, and a recruiter-friendly presentation.
              </p>
            </div>
          </div>

          <div class="group glass rounded-3xl overflow-hidden glow-hover transition-all duration-500">
            <div class="aspect-video relative overflow-hidden">
              <img
                class="w-full h-full object-cover group-hover:scale-110 transition-transform duration-700"
                src="https://placehold.co/1200x700/102222/a855f7?text=AI+Evaluation+Workflow"
                alt="AI Evaluation Workflow project preview"
              />
              <div class="absolute inset-0 bg-background-dark/40 opacity-0 group-hover:opacity-100 transition-opacity flex items-center justify-center gap-4">
                <a class="px-4 py-2 rounded-full bg-white text-background-dark flex items-center gap-2 font-bold hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">description</span> Case Study
                </a>
                <a class="size-12 rounded-full bg-white text-background-dark flex items-center justify-center hover:bg-primary transition-colors" href="#">
                  <span class="material-symbols-outlined">code</span>
                </a>
              </div>
            </div>
            <div class="p-8">
              <div class="flex gap-2 mb-4 flex-wrap">
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">AI Evaluation</span>
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">Rubrics</span>
                <span class="px-2.5 py-1 rounded bg-accent-purple/10 text-accent-purple text-[10px] font-bold uppercase tracking-wider">Code Review</span>
              </div>
              <h4 class="text-2xl font-bold text-white mb-2">AI Response Evaluation Workflow</h4>
              <p class="text-slate-400 mb-6">
                A case-study style project showing structured comparison of AI outputs, rubric design, and repository review workflows focused on quality and consistency.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section class="py-24 px-6 bg-background-dark" id="experience">
        <div class="max-w-4xl mx-auto">
          <div class="text-center mb-16">
            <h3 class="text-primary font-bold tracking-widest uppercase text-sm mb-4">Journey</h3>
            <h2 class="text-4xl font-bold text-white">Work Experience</h2>
          </div>

          <div class="space-y-12">
            <div class="relative pl-8 md:pl-0 border-l-2 border-primary/20 md:border-l-0">
              <div class="md:grid md:grid-cols-5 md:gap-12">
                <div class="md:col-span-1 md:text-right mb-4 md:mb-0">
                  <span class="text-primary font-bold">2025 - 2026</span>
                </div>
                <div class="md:col-span-4 relative">
                  <div class="hidden md:block absolute -left-[45px] top-1.5 size-4 rounded-full bg-primary border-4 border-background-dark"></div>
                  <h4 class="text-xl font-bold text-white mb-1">AI Evaluation Specialist (Contract)</h4>
                  <div class="text-accent-purple font-medium mb-4">Outlier</div>
                  <p class="text-slate-400">
                    Evaluated and compared AI-generated responses, created scoring rubrics based on quality criteria, and reviewed repository-level changes for accuracy and consistency. Contributed to evaluation workflows through structured analysis, detailed judgment, and close attention to technical and language quality.
                  </p>
                </div>
              </div>
            </div>

            <div class="relative pl-8 md:pl-0 border-l-2 border-primary/20 md:border-l-0">
              <div class="md:grid md:grid-cols-5 md:gap-12">
                <div class="md:col-span-1 md:text-right mb-4 md:mb-0">
                  <span class="text-slate-300 font-bold">2023 - 2024</span>
                </div>
                <div class="md:col-span-4 relative">
                  <div class="hidden md:block absolute -left-[45px] top-1.5 size-4 rounded-full bg-slate-500 border-4 border-background-dark"></div>
                  <h4 class="text-xl font-bold text-white mb-1">Full Stack Developer (Contract)</h4>
                  <div class="text-accent-purple font-medium mb-4">OTB Molle Molle</div>
                  <p class="text-slate-400">
                    Developed a water management system for a local community organization, building responsive web and mobile interfaces with React, JavaScript, and MongoDB. Worked across the full stack with a focus on usability, responsive design, and reliable data management.
                  </p>
                </div>
              </div>
            </div>

            <div class="relative pl-8 md:pl-0 border-l-2 border-primary/20 md:border-l-0">
              <div class="md:grid md:grid-cols-5 md:gap-12">
                <div class="md:col-span-1 md:text-right mb-4 md:mb-0">
                  <span class="text-slate-300 font-bold">2023 - 2024</span>
                </div>
                <div class="md:col-span-4 relative">
                  <div class="hidden md:block absolute -left-[45px] top-1.5 size-4 rounded-full bg-slate-500 border-4 border-background-dark"></div>
                  <h4 class="text-xl font-bold text-white mb-1">Computerized Information Technician (Contract)</h4>
                  <div class="text-accent-purple font-medium mb-4">Departmental Electoral Tribunal</div>
                  <p class="text-slate-400">
                    Provided direct assistance to citizens requesting official authorization certificates, handled records accurately, and supported administrative service processes with strong organization, precision, and attention to detail.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="py-24 px-6 relative" id="contact">
        <div class="max-w-7xl mx-auto glass rounded-[2.5rem] p-8 md:p-16 overflow-hidden relative">
          <div class="absolute top-0 right-0 w-64 h-64 bg-primary/10 blur-[100px] rounded-full"></div>
          <div class="absolute bottom-0 left-0 w-64 h-64 bg-accent-purple/10 blur-[100px] rounded-full"></div>

          <div class="grid lg:grid-cols-2 gap-16 relative z-10">
            <div>
              <h3 class="text-primary font-bold tracking-widest uppercase text-sm mb-4">Get in touch</h3>
              <h2 class="text-5xl font-bold text-white mb-8 leading-tight">
                Let's build something
                <span class="text-transparent bg-clip-text bg-gradient-to-r from-primary to-accent-purple">extraordinary</span>.
              </h2>

              <div class="space-y-6">
                <div class="flex items-center gap-4">
                  <div class="size-12 rounded-xl bg-white/5 border border-white/10 flex items-center justify-center text-primary">
                    <span class="material-symbols-outlined">mail</span>
                  </div>
                  <div>
                    <div class="text-xs text-slate-500 uppercase font-bold tracking-wider">Email</div>
                    <div class="text-lg font-medium">emanuelca.eca2@gmail.com</div>
                  </div>
                </div>

                <div class="flex items-center gap-4">
                  <div class="size-12 rounded-xl bg-white/5 border border-white/10 flex items-center justify-center text-accent-purple">
                    <span class="material-symbols-outlined">location_on</span>
                  </div>
                  <div>
                    <div class="text-xs text-slate-500 uppercase font-bold tracking-wider">Location</div>
                    <div class="text-lg font-medium">Cochabamba, Bolivia</div>
                  </div>
                </div>

                <div class="flex items-center gap-4">
                  <div class="size-12 rounded-xl bg-white/5 border border-white/10 flex items-center justify-center text-primary">
                    <span class="material-symbols-outlined">link</span>
                  </div>
                  <div>
                    <div class="text-xs text-slate-500 uppercase font-bold tracking-wider">Social</div>
                    <div class="flex gap-3 mt-1">
                      <a class="hover:text-primary transition-colors" href="#">GitHub</a>
                      <a class="hover:text-primary transition-colors" href="#">LinkedIn</a>
                    </div>
                  </div>
                </div>
              </div>
            </div>

            <form class="space-y-6">
              <div class="grid sm:grid-cols-2 gap-6">
                <div class="space-y-2">
                  <label class="text-sm font-bold text-slate-400 ml-1">Name</label>
                  <input class="w-full bg-white/5 border border-white/10 rounded-xl px-4 py-3 focus:border-primary focus:ring-0 transition-colors" placeholder="Your name" type="text" />
                </div>
                <div class="space-y-2">
                  <label class="text-sm font-bold text-slate-400 ml-1">Email</label>
                  <input class="w-full bg-white/5 border border-white/10 rounded-xl px-4 py-3 focus:border-primary focus:ring-0 transition-colors" placeholder="your@email.com" type="email" />
                </div>
              </div>

              <div class="space-y-2">
                <label class="text-sm font-bold text-slate-400 ml-1">Message</label>
                <textarea class="w-full bg-white/5 border border-white/10 rounded-xl px-4 py-3 focus:border-primary focus:ring-0 transition-colors" placeholder="Tell me about your project..." rows="4"></textarea>
              </div>

              <button class="w-full py-4 bg-primary text-background-dark font-bold rounded-xl hover:opacity-90 transition-opacity flex items-center justify-center gap-2" type="submit">
                Send Message <span class="material-symbols-outlined">send</span>
              </button>
            </form>
          </div>
        </div>
      </section>
    </main>

    <footer class="py-12 px-6 border-t border-white/5">
      <div class="max-w-7xl mx-auto flex flex-col md:flex-row items-center justify-between gap-8">
        <div class="flex items-center gap-2">
          <div class="size-8 bg-primary/20 rounded flex items-center justify-center text-primary">
            <span class="material-symbols-outlined text-xl">terminal</span>
          </div>
          <span class="font-bold tracking-tight">Emanuel Carpio</span>
        </div>

        <p class="text-slate-500 text-sm">© 2026 Emanuel Angel Carpio Achacollo. All rights reserved.</p>

        <div class="flex items-center gap-4">
          <a class="size-10 rounded-full bg-white/5 border border-white/10 flex items-center justify-center hover:text-primary transition-colors" href="#" aria-label="GitHub">
            <i class="devicon-github-original text-xl"></i>
          </a>
          <a class="size-10 rounded-full bg-white/5 border border-white/10 flex items-center justify-center hover:text-primary transition-colors" href="#" aria-label="LinkedIn">
            <i class="devicon-linkedin-plain text-xl"></i>
          </a>
          <a class="size-10 rounded-full bg-white/5 border border-white/10 flex items-center justify-center hover:text-primary transition-colors" href="mailto:emanuelca.eca2@gmail.com" aria-label="Email">
            <span class="material-symbols-outlined text-xl">mail</span>
          </a>
        </div>
      </div>
    </footer>
  </div>
</body>
</html>
