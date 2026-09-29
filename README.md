<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currículo - Herbert Gomes de Santana da Silva</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Google Fonts: Inter & Outfit -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Outfit:wght@600;700;800&display=swap" rel="stylesheet">
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        tech: {
                            50: '#f0f9ff',
                            100: '#e0f2fe',
                            500: '#0284c7',
                            600: '#0369a1',
                            700: '#0369a1',
                            900: '#0c4a6e'
                        }
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Outfit', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #334155;
            -webkit-print-color-adjust: exact;
            print-color-adjust: exact;
        }
        h1, h2, h3, .font-heading {
            font-family: 'Outfit', sans-serif;
        }

        @media print {
            body {
                background: white !important;
                padding: 0 !important;
            }
            .page-container {
                box-shadow: none !important;
                margin: 0 !important;
                width: 100% !important;
                max-width: none !important;
                border-radius: 0 !important;
                border: none !important;
            }
            @page {
                size: A4;
                margin: 0;
            }
        }
    </style>
</head>
<body class="py-6 px-4 print:py-0 print:px-0">

    <div class="page-container max-w-5xl mx-auto bg-white border border-slate-200/80 rounded-xl shadow-sm overflow-hidden grid grid-cols-1 md:grid-cols-12 print:grid-cols-12 min-h-[1050px]">
        
        <!-- ================= MAIN CONTENT (LEFT COLUMN - 7 COLS) ================= -->
        <main class="md:col-span-7 print:col-span-7 p-7 md:p-9 text-slate-700 flex flex-col justify-between">
            <div>
                <header class="mb-7 pb-5 border-b border-slate-100">
                    <h1 class="text-base sm:text-lg md:text-[1.35rem] font-extrabold uppercase text-slate-900 font-heading tracking-tight whitespace-nowrap overflow-hidden text-ellipsis">
                        HERBERT GOMES DE SANTANA DA SILVA
                    </h1>
                    <div class="flex items-center gap-2 mt-2">
                        <span class="w-2 h-2 rounded-full bg-tech-500"></span>
                        <p class="text-[11px] font-bold text-tech-600 uppercase tracking-wider">
                            Desenvolvimento de Sistemas & Tecnologia
                        </p>
                    </div>
                </header>

                <section class="mb-7">
                    <h2 class="text-xs font-bold text-slate-900 uppercase tracking-widest mb-2.5 font-heading flex items-center gap-2">
                        <span class="w-1.5 h-3.5 bg-tech-500 rounded-sm"></span>
                        Objetivo
                    </h2>
                    <p class="text-xs text-slate-600 leading-relaxed font-normal bg-slate-50 p-3.5 rounded-lg border border-slate-100">
                        Busco uma oportunidade na área de Tecnologia, onde possa colocar em prática meus conhecimentos, desenvolver novas habilidades e adquirir experiência profissional. Tenho vontade de aprender, contribuir com a equipe e crescer profissionalmente.
                </section>

                <section class="mb-7">
                    <h2 class="text-xs font-bold text-slate-900 uppercase tracking-widest mb-4 font-heading flex items-center gap-2">
                        <span class="w-1.5 h-3.5 bg-tech-500 rounded-sm"></span>
                        Experiência Profissional
                    </h2>
                    
                    <div class="space-y-4">
                        
                        <!-- Apoio Administrativo / Operacional -->
                        <div class="pb-3.5 border-b border-slate-100 last:border-0 last:pb-0">
                            <div class="flex justify-between items-baseline mb-1">
                                <h3 class="font-bold text-slate-900 text-xs sm:text-sm font-heading">Cartório</h3>
                                <span class="text-[10px] sm:text-[11px] text-slate-500 font-medium shrink-0 ml-2 bg-slate-100 px-2 py-0.5 rounded">1 ano e 8 meses</span>
                            </div>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Apoio em atividades administrativas, organizando documentos e garantindo que a equipe tivesse acesso às informações necessárias. Apoio à equipe em diversas atividades, colaborando na execução de tarefas diárias para garantir eficiência no trabalho.
                            </p>
                        </div>

                        <!-- Exército Brasileiro -->
                        <div class="pb-3.5 border-b border-slate-100 last:border-0 last:pb-0">
                            <div class="flex justify-between items-baseline mb-1">
                                <h3 class="font-bold text-slate-900 text-xs sm:text-sm font-heading">Exército Brasileiro</h3>
                                <span class="text-[10px] sm:text-[11px] text-slate-500 font-medium shrink-0 ml-2 bg-slate-100 px-2 py-0.5 rounded">1 ano</span>
                            </div>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Separação e organização de materiais e execução de atividades de manutenção da área verde.
                            </p>
                        </div>

                        <!-- Vendedor -->
                        <div class="pb-3.5 border-b border-slate-100 last:border-0 last:pb-0">
                            <div class="flex justify-between items-baseline mb-1">
                                <h3 class="font-bold text-slate-900 text-xs sm:text-sm font-heading">Vendedor</h3>
                                <span class="text-[10px] sm:text-[11px] text-slate-500 font-medium shrink-0 ml-2 bg-slate-100 px-2 py-0.5 rounded">6 meses</span>
                            </div>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                Atendimento ao cliente, esclarecendo dúvidas sobre produtos, separação de material e organização da loja.
                            </p>
                        </div>

                    </div>
                </section>

                <section>
                    <h2 class="text-xs font-bold text-slate-900 uppercase tracking-widest mb-3 font-heading flex items-center gap-2">
                        <span class="w-1.5 h-3.5 bg-tech-500 rounded-sm"></span>
                        Educação
                    </h2>
                    
                    <div class="space-y-2.5">
                        <div class="p-3 bg-slate-50 rounded-lg border border-slate-100">
                            <div class="flex justify-between items-start gap-2">
                                <div>
                                    <h3 class="font-bold text-slate-900 text-xs font-heading">Análise e Desenvolvimento de Sistemas</h3>
                                    <p class="text-[11px] text-slate-500 mt-0.5">Ensino Superior (Graduação)</p>
                                </div>
                                <span class="text-[10px] font-semibold text-tech-600 bg-tech-50 border border-tech-100 px-2 py-0.5 rounded shrink-0">01/2025 - 06/2027</span>
                            </div>
                        </div>

                        <div class="p-3 bg-slate-50 rounded-lg border border-slate-100">
                            <div class="flex justify-between items-start gap-2">
                                <div>
                                    <h3 class="font-bold text-slate-900 text-xs font-heading">Técnico em Desenvolvimento de Sistemas</h3>
                                    <p class="text-[11px] text-slate-500 mt-0.5">ETE Advogado José David Gil Rodrigues</p>
                                </div>
                                <span class="text-[10px] font-semibold text-tech-600 bg-tech-50 border border-tech-100 px-2 py-0.5 rounded shrink-0">02/2026 - 06/2027</span>
                            </div>
                        </div>
                    </div>
                </section>
            </div>
            
            <footer class="pt-5 mt-6 border-t border-slate-100 text-slate-400 text-[10px] tracking-wide text-center md:text-left">
                HERBERT GOMES DE SANTANA DA SILVA &bull; CURRÍCULO PROFISSIONAL
            </footer>
        </main>

        <!-- ================= SIDEBAR (RIGHT COLUMN - 5 COLS - LIGHT GRAY) ================= -->
        <aside class="md:col-span-5 print:col-span-5 bg-slate-50 border-l border-slate-200/80 p-7 md:p-8 flex flex-col justify-between">
            <div class="space-y-6">
                
                <!-- Contact Information -->
                <div>
                    <h2 class="text-xs font-bold uppercase tracking-wider text-slate-900 mb-3.5 pb-2 border-b border-slate-200 font-heading flex items-center justify-between">
                        <span>Contato</span>
                        <i class="fa-solid fa-address-book text-[10px] text-tech-500"></i>
                    </h2>
                    
                    <div class="space-y-3 text-xs">
                        <!-- Profile/Age -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-regular fa-user"></i>
                            </div>
                            <div>
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">Perfil</p>
                                <p class="font-medium text-slate-700">23 Anos // Solteiro</p>
                            </div>
                        </div>

                        <!-- Phone -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-solid fa-phone"></i>
                            </div>
                            <div>
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">Telefone</p>
                                <p class="font-medium text-slate-700">(81) 98599-8417</p>
                            </div>
                        </div>

                        <!-- Email -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-regular fa-envelope"></i>
                            </div>
                            <div class="min-w-0">
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">E-mail</p>
                                <a href="mailto:Herbert21santana@gmail.com" class="font-medium text-slate-700 hover:text-tech-600 truncate block transition">Herbert21santana@gmail.com</a>
                            </div>
                        </div>

                        <!-- Location -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-solid fa-location-dot"></i>
                            </div>
                            <div>
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">Endereço</p>
                                <p class="font-medium text-slate-700">Rua Guaraciaba, Nº 20</p>
                                <p class="text-slate-500 text-[11px]">CEP 51290-500</p>
                            </div>
                        </div>

                        <!-- LinkedIn -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-brands fa-linkedin-in"></i>
                            </div>
                            <div class="min-w-0">
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">LinkedIn</p>
                                <a href="https://www.linkedin.com/in/herbert-gomes-b4b528359/" target="_blank" class="font-medium text-tech-600 hover:underline truncate block text-[11px] mt-0.5">
                                    linkedin.com/in/herbert-gomes
                                </a>
                            </div>
                        </div>

                        <!-- GitHub -->
                        <div class="flex items-start gap-2.5">
                            <div class="w-6 h-6 rounded bg-white border border-slate-200/80 flex items-center justify-center text-tech-500 shrink-0 text-[11px] shadow-2xs">
                                <i class="fa-brands fa-github"></i>
                            </div>
                            <div class="min-w-0">
                                <p class="text-[10px] font-semibold uppercase text-slate-400 tracking-wider">GitHub</p>
                                <a href="https://github.com/herbert-2008" target="_blank" class="font-medium text-tech-600 hover:underline truncate block text-[11px] mt-0.5">
                                    github.com/herbert-2008
                                </a>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Complementary Tech Skills -->
                <div>
                    <h2 class="text-xs font-bold uppercase tracking-wider text-slate-900 mb-3 pb-2 border-b border-slate-200 font-heading flex items-center justify-between">
                        <span>Habilidades Técnicas</span>
                        <i class="fa-solid fa-code text-[10px] text-tech-500"></i>
                    </h2>
                    
                    <div class="flex flex-wrap gap-1.5">
                        <span class="px-2.5 py-1 bg-white border border-slate-200/90 text-slate-800 rounded-md text-[11px] font-medium shadow-2xs flex items-center gap-1.5">
                            <span class="w-1.5 h-1.5 rounded-full bg-tech-500"></span> Java <span class="text-[9px] text-slate-400">(Básico)</span>
                        </span>
                        <span class="px-2.5 py-1 bg-white border border-slate-200/90 text-slate-800 rounded-md text-[11px] font-medium shadow-2xs flex items-center gap-1.5">
                            <span class="w-1.5 h-1.5 rounded-full bg-tech-500"></span> SQL <span class="text-[9px] text-slate-400">(Básico)</span>
                        </span>
                        <span class="px-2.5 py-1 bg-white border border-slate-200/90 text-slate-800 rounded-md text-[11px] font-medium shadow-2xs flex items-center gap-1.5">
                            <span class="w-1.5 h-1.5 rounded-full bg-tech-500"></span> GitHub <span class="text-[9px] text-slate-400">(Básico)</span>
                        </span>
                        <span class="px-2.5 py-1 bg-white border border-slate-200/90 text-slate-800 rounded-md text-[11px] font-medium shadow-2xs flex items-center gap-1.5">
                            <span class="w-1.5 h-1.5 rounded-full bg-tech-500"></span> Banco de Dados <span class="text-[9px] text-slate-400">(Básico)</span>
                        </span>
                    </div>
                </div>

                <!-- Extracurricular Courses -->
                <div>
                    <h2 class="text-xs font-bold uppercase tracking-wider text-slate-900 mb-2.5 pb-2 border-b border-slate-200 font-heading flex items-center justify-between">
                        <span>Cursos Extracurriculares</span>
                        <i class="fa-solid fa-graduation-cap text-[10px] text-tech-500"></i>
                    </h2>
                    
                    <ul class="space-y-1.5 text-xs">
                        <li class="p-2 bg-white rounded border border-slate-200/80 flex items-center justify-between">
                            <span class="font-medium text-slate-700">Informática Profissional</span>
                            <i class="fa-solid fa-check text-[10px] text-emerald-500"></i>
                        </li>
                        <li class="p-2 bg-white rounded border border-slate-200/80 flex items-center justify-between">
                            <span class="font-medium text-slate-700">Excel Básico</span>
                            <i class="fa-solid fa-check text-[10px] text-emerald-500"></i>
                        </li>
                    </ul>
                </div>

                <!-- Soft Skills -->
                <div>
                    <h2 class="text-xs font-bold uppercase tracking-wider text-slate-900 mb-2.5 pb-2 border-b border-slate-200 font-heading flex items-center justify-between">
                        <span>Competências</span>
                        <i class="fa-regular fa-lightbulb text-[10px] text-tech-500"></i>
                    </h2>
                    
                    <div class="grid grid-cols-1 gap-1.5 text-xs text-slate-600">
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-angle-right text-[10px] text-tech-500"></i>
                            <span>Prestatividade & Responsabilidade</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-angle-right text-[10px] text-tech-500"></i>
                            <span>Trabalho em equipe</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-angle-right text-[10px] text-tech-500"></i>
                            <span>Proatividade & Organização</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-angle-right text-[10px] text-tech-500"></i>
                            <span>Empatia no atendimento</span>
                        </div>
                        <div class="flex items-center gap-2">
                            <i class="fa-solid fa-angle-right text-[10px] text-tech-500"></i>
                            <span>Vontade de aprender</span>
                        </div>
                    </div>
                </div>

            </div>
        </aside>

    </div>

</body>
</html>
