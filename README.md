
<html lang="pt-BR" class="scroll-smooth">
<head>
    <base target="_self">
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OMD Digital - Gestão Automatizada em Redes Sociais</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/@preline/preline@2.0.0/dist/preline.min.js"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        'neon-blue': '#00f0ff',
                        'dark-blue': '#001a33',
                    },
                    animation: {
                        'pulse-slow': 'pulse 5s cubic-bezier(0.4, 0, 0.6, 1) infinite',
                        'float': 'float 6s ease-in-out infinite',
                    },
                    keyframes: {
                        float: {
                            '0%, 100%': { transform: 'translateY(0)' },
                            '50%': { transform: 'translateY(-20px)' },
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .hero-gradient {
            background: linear-gradient(135deg, rgba(0,31,63,0.9) 0%, rgba(0,0,0,0.8) 100%);
        }
        .neon-text {
            text-shadow: 0 0 10px rgba(0, 240, 255, 0.7), 0 0 20px rgba(0, 240, 255, 0.5);
        }
        .neon-border {
            box-shadow: 0 0 15px rgba(0, 240, 255, 0.7);
        }
        .video-container {
            position: relative;
            padding-bottom: 56.25%;
            height: 0;
            overflow: hidden;
        }
        .video-container iframe {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body class="bg-dark-blue text-gray-100 font-sans antialiased">
    <!-- Header -->
    <header class="fixed w-full z-50 bg-dark-blue/90 backdrop-blur-md border-b border-neon-blue/20">
        <nav class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex items-center justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0">
                        <span class="text-2xl font-bold text-neon-blue">OMD <span class="text-white">Digital</span></span>
                    </div>
                </div>
                <div class="hidden md:block">
                    <div class="ml-10 flex items-baseline space-x-8">
                        <a href="#home" class="nav-link px-3 py-2 rounded-md text-sm font-medium hover:text-neon-blue transition">Home</a>
                        <a href="#services" class="nav-link px-3 py-2 rounded-md text-sm font-medium hover:text-neon-blue transition">Serviços</a>
                        <a href="#testimonials" class="nav-link px-3 py-2 rounded-md text-sm font-medium hover:text-neon-blue transition">Depoimentos</a>
                        <a href="#about" class="nav-link px-3 py-2 rounded-md text-sm font-medium hover:text-neon-blue transition">Sobre</a>
                        <a href="#contact" class="nav-link px-3 py-2 rounded-md text-sm font-medium hover:text-neon-blue transition">Contato</a>
                    </div>
                </div>
                <div class="md:hidden">
                    <button type="button" class="mobile-menu-button inline-flex items-center justify-center p-2 rounded-md text-neon-blue hover:text-white focus:outline-none">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </nav>
        
        <!-- Mobile menu -->
        <div class="mobile-menu hidden md:hidden bg-dark-blue border-t border-neon-blue/20">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="nav-link block px-3 py-2 rounded-md text-base font-medium hover:text-neon-blue transition">Home</a>
                <a href="#services" class="nav-link block px-3 py-2 rounded-md text-base font-medium hover:text-neon-blue transition">Serviços</a>
                <a href="#testimonials" class="nav-link block px-3 py-2 rounded-md text-base font-medium hover:text-neon-blue transition">Depoimentos</a>
                <a href="#about" class="nav-link block px-3 py-2 rounded-md text-base font-medium hover:text-neon-blue transition">Sobre</a>
                <a href="#contact" class="nav-link block px-3 py-2 rounded-md text-base font-medium hover:text-neon-blue transition">Contato</a>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section id="home" class="hero-gradient pt-32 pb-20 px-4 sm:px-6 lg:px-8">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="space-y-8">
                    <h1 class="text-4xl md:text-6xl font-bold leading-tight neon-text">
                        <span class="block">Transforme Seu Negócio</span>
                        <span class="text-neon-blue">Com Gestão Automatizada</span>
                    </h1>
                    <p class="text-xl text-gray-300 max-w-lg">
                        Tenha uma IA 24h atendendo seus clientes de forma humanizada enquanto você foca no que realmente importa: seu negócio!
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <a href="#contact" class="bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-4 px-8 rounded-lg transition duration-300 transform hover:scale-105 text-center">
                            Fale Conosco Agora
                        </a>
                        <a href="#services" class="border-2 border-neon-blue text-neon-blue hover:bg-neon-blue/10 font-bold py-4 px-8 rounded-lg transition duration-300 transform hover:scale-105 text-center">
                            Nossos Planos
                        </a>
                    </div>
                    <div class="flex items-center space-x-4 pt-4">
                        <div class="flex -space-x-2">
                            <img class="w-10 h-10 rounded-full border-2 border-neon-blue" src="https://randomuser.me/api/portraits/women/44.jpg" alt="Client">
                            <img class="w-10 h-10 rounded-full border-2 border-neon-blue" src="https://randomuser.me/api/portraits/men/32.jpg" alt="Client">
                            <img class="w-10 h-10 rounded-full border-2 border-neon-blue" src="https://randomuser.me/api/portraits/women/68.jpg" alt="Client">
                        </div>
                        <div>
                            <p class="text-sm text-gray-300">+500 clientes satisfeitos</p>
                            <div class="flex items-center">
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <i class="fas fa-star text-yellow-400"></i>
                                <span class="ml-2 text-gray-300">5.0 (200+ reviews)</span>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="relative">
                    <div class="relative rounded-xl overflow-hidden neon-border">
                        <!-- Carousel -->
                        <div class="carousel relative h-96 w-full">
                            <div class="carousel-inner relative w-full overflow-hidden">
                                <div class="carousel-item active relative float-left w-full">
                                    <img src="https://images.unsplash.com/photo-1600880292203-757bb62b4baf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" class="block w-full h-full object-cover" alt="Business people smiling">
                                    <div class="absolute inset-0 bg-gradient-to-t from-dark-blue/90 via-dark-blue/30 to-transparent"></div>
                                    <div class="absolute bottom-0 left-0 p-6">
                                        <h3 class="text-xl font-bold text-white">Gestão Completa para Seu Negócio</h3>
                                        <p class="text-gray-300">Deixe a OMD Digital cuidar das suas redes sociais</p>
                                    </div>
                                </div>
                                <div class="carousel-item relative float-left w-full">
                                    <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1484&q=80" class="block w-full h-full object-cover" alt="Team meeting">
                                    <div class="absolute inset-0 bg-gradient-to-t from-dark-blue/90 via-dark-blue/30 to-transparent"></div>
                                    <div class="absolute bottom-0 left-0 p-6">
                                        <h3 class="text-xl font-bold text-white">Atendimento 24h com IA</h3>
                                        <p class="text-gray-300">Nunca perca um cliente por falta de resposta</p>
                                    </div>
                                </div>
                                <div class="carousel-item relative float-left w-full">
                                    <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" class="block w-full h-full object-cover" alt="Business growth">
                                    <div class="absolute inset-0 bg-gradient-to-t from-dark-blue/90 via-dark-blue/30 to-transparent"></div>
                                    <div class="absolute bottom-0 left-0 p-6">
                                        <h3 class="text-xl font-bold text-white">Resultados Comprovados</h3>
                                        <p class="text-gray-300">Aumente suas vendas com nossas estratégias</p>
                                    </div>
                                </div>
                            </div>
                            <button class="carousel-control-prev absolute top-1/2 left-2 transform -translate-y-1/2 bg-neon-blue/30 hover:bg-neon-blue/50 rounded-full p-2 text-white">
                                <i class="fas fa-chevron-left"></i>
                            </button>
                            <button class="carousel-control-next absolute top-1/2 right-2 transform -translate-y-1/2 bg-neon-blue/30 hover:bg-neon-blue/50 rounded-full p-2 text-white">
                                <i class="fas fa-chevron-right"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="bg-dark-blue py-12 px-4 sm:px-6 lg:px-8 border-b border-neon-blue/20">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div class="p-6">
                    <div class="text-4xl font-bold text-neon-blue mb-2">24/7</div>
                    <div class="text-gray-300">Atendimento</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-neon-blue mb-2">500+</div>
                    <div class="text-gray-300">Clientes</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-neon-blue mb-2">98%</div>
                    <div class="text-gray-300">Satisfação</div>
                </div>
                <div class="p-6">
                    <div class="text-4xl font-bold text-neon-blue mb-2">3x</div>
                    <div class="text-gray-300">Mais Vendas</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-20 px-4 sm:px-6 lg:px-8 bg-dark-blue">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 neon-text">Nossos <span class="text-neon-blue">Serviços</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">Oferecemos soluções completas para impulsionar seu negócio nas redes sociais</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Basic Plan -->
                <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20 hover:border-neon-blue transition duration-300 transform hover:scale-105">
                    <div class="mb-6">
                        <h3 class="text-2xl font-bold text-neon-blue mb-2">Pacote Básico</h3>
                        <p class="text-gray-300">Gestão essencial para pequenos negócios</p>
                    </div>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$149,90</span>
                        <span class="text-gray-400">/mês</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Gestão de 2 redes sociais</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>10 posts/mês</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Relatórios mensais</span>
                        </li>
                        <li class="flex items-center text-gray-400">
                            <i class="fas fa-times text-red-400 mr-2"></i>
                            <span>Sem IA</span>
                        </li>
                    </ul>
                    <a href="#contact" class="block w-full bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-3 px-6 rounded-lg text-center transition">Contratar</a>
                </div>
                
                <!-- Premium Plan -->
                <div class="bg-gray-900 rounded-xl p-8 border-2 border-neon-blue transform scale-105 relative">
                    <div class="absolute top-0 right-0 bg-neon-blue text-dark-blue text-xs font-bold px-3 py-1 rounded-bl-lg rounded-tr-lg">MAIS POPULAR</div>
                    <div class="mb-6">
                        <h3 class="text-2xl font-bold text-neon-blue mb-2">Pacote Premium</h3>
                        <p class="text-gray-300">Solução com automação para médias empresas</p>
                    </div>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$550,00</span>
                        <span class="text-gray-400">/mês</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Gestão de 4 redes sociais</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>30 posts/mês</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Automação no instagram</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Relatórios semanais</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Estratégias personalizadas</span>
                        </li>
                    </ul>
                    <a href="#contact" class="block w-full bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-3 px-6 rounded-lg text-center transition">Contratar</a>
                </div>
                
                <!-- Enterprise Plan -->
                <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20 hover:border-neon-blue transition duration-300 transform hover:scale-105">
                    <div class="mb-6">
                        <h3 class="text-2xl font-bold text-neon-blue mb-2">Pacote Empresarial</h3>
                        <p class="text-gray-300">Solução completa para grandes negócios</p>
                    </div>
                    <div class="mb-6">
                        <span class="text-4xl font-bold">R$2.599,00</span>
                        <span class="text-gray-400">/mês</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Gestão ilimitada de redes</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Posts diários</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>IA 24h avançada</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Relatórios diários</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Consultoria estratégica</span>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-check text-neon-blue mr-2"></i>
                            <span>Gestor dedicado</span>
                        </li>
                    </ul>
                    <a href="#contact" class="block w-full bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-3 px-6 rounded-lg text-center transition">Contratar</a>
                </div>
            </div>
        </div>
    </section>

    <!-- AI Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 bg-gradient-to-r from-dark-blue to-gray-900">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div class="order-2 md:order-1">
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 neon-text">IA 24h <span class="text-neon-blue">Humanizada</span></h2>
                    <p class="text-xl text-gray-300 mb-6">
                        Nossa inteligência artificial atende seus clientes de forma natural e humanizada, garantindo que nenhuma mensagem fique sem resposta, mesmo fora do horário comercial.
                    </p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Respostas instantâneas 24 horas por dia</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Tom de voz personalizado para sua marca</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Aprendizado contínuo para melhor atendimento</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Integração com WhatsApp, Instagram e Facebook</span>
                        </li>
                    </ul>
                    <a href="#contact" class="inline-block bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-3 px-6 rounded-lg transition">Saiba Mais</a>
                </div>
                <div class="order-1 md:order-2">
                    <div class="relative">
                        <div class="absolute inset-0 bg-neon-blue/20 rounded-2xl -rotate-6"></div>
                        <div class="relative bg-gray-900 rounded-2xl p-6 border border-neon-blue/30">
                            <div class="flex items-center mb-4">
                                <div class="w-3 h-3 rounded-full bg-red-500 mr-2"></div>
                                <div class="w-3 h-3 rounded-full bg-yellow-500 mr-2"></div>
                                <div class="w-3 h-3 rounded-full bg-green-500 mr-2"></div>
                                <div class="ml-auto text-sm text-gray-400">IA Chat</div>
                            </div>
                            <div class="space-y-4">
                                <div class="flex items-start">
                                    <img src="https://randomuser.me/api/portraits/women/33.jpg" class="w-8 h-8 rounded-full mr-3" alt="Client">
                                    <div class="bg-gray-800 rounded-lg p-3 max-w-xs">
                                        <p class="text-sm">Olá, gostaria de saber o horário de funcionamento hoje</p>
                                    </div>
                                </div>
                                <div class="flex items-start justify-end">
                                    <div class="bg-neon-blue text-dark-blue rounded-lg p-3 max-w-xs">
                                        <p class="text-sm">Olá! Nosso horário hoje é das 10h às 22h. Posso ajudar com mais alguma coisa? 😊</p>
                                    </div>
                                    <img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=765&q=80" class="w-8 h-8 rounded-full ml-3" alt="OMD AI">
                                </div>
                                <div class="flex items-start">
                                    <img src="https://randomuser.me/api/portraits/women/33.jpg" class="w-8 h-8 rounded-full mr-3" alt="Client">
                                    <div class="bg-gray-800 rounded-lg p-3 max-w-xs">
                                        <p class="text-sm">Tem promoção para aniversariantes?</p>
                                    </div>
                                </div>
                                <div class="flex items-start justify-end">
                                    <div class="bg-neon-blue text-dark-blue rounded-lg p-3 max-w-xs">
                                        <p class="text-sm">Sim! Aniversariantes ganham 20% de desconto apresentando documento com foto. Posso reservar uma mesa para você? 🎉</p>
                                    </div>
                                    <img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=765&q=80" class="w-8 h-8 rounded-full ml-3" alt="OMD AI">
                                </div>
                            </div>
                            <div class="mt-4 pt-4 border-t border-gray-800">
                                <div class="flex items-center">
                                    <input type="text" placeholder="Digite sua mensagem..." class="flex-1 bg-gray-800 rounded-full py-2 px-4 text-sm focus:outline-none focus:ring-2 focus:ring-neon-blue">
                                    <button class="ml-2 bg-neon-blue text-dark-blue rounded-full p-2">
                                        <i class="fas fa-paper-plane"></i>
                                    </button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section id="testimonials" class="py-20 px-4 sm:px-6 lg:px-8 bg-dark-blue">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 neon-text">Depoimentos de <span class="text-neon-blue">Clientes</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">Empresários que transformaram seus negócios com a OMD Digital</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Pizza Place -->
                <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20 hover:border-neon-blue transition duration-300">
                    <div class="flex items-center mb-6">
                        <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Pizzaria Owner">
                        <div>
                            <h4 class="text-xl font-bold">Carlos Silva</h4>
                            <p class="text-neon-blue">Pizzaria Sabor da Vila</p>
                        </div>
                    </div>
                    <div class="text-gray-300 mb-6">
                        <p>"A OMD Digital revolucionou nosso atendimento. A IA responde clientes mesmo de madrugada e nossas vendas aumentaram 40% em 3 meses!"</p>
                    </div>
                    <div class="flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
                
                <!-- Hair Salon -->
                <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20 hover:border-neon-blue transition duration-300">
                    <div class="flex items-center mb-6">
                        <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Salon Owner">
                        <div>
                            <h4 class="text-xl font-bold">Ana Paula</h4>
                            <p class="text-neon-blue">Salão Bella Donna</p>
                        </div>
                    </div>
                    <div class="text-gray-300 mb-6">
                        <p>"Nunca mais perdi uma cliente por falta de resposta. A IA agenda horários e envia lembretes automaticamente. Minha agenda está sempre cheia!"</p>
                    </div>
                    <div class="flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
                
                <!-- Car Dealership -->
                <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20 hover:border-neon-blue transition duration-300">
                    <div class="flex items-center mb-6">
                        <img src="https://randomuser.me/api/portraits/men/75.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Dealership Owner">
                        <div>
                            <h4 class="text-xl font-bold">Roberto Almeida</h4>
                            <p class="text-neon-blue">Auto Premium</p>
                        </div>
                    </div>
                    <div class="text-gray-300 mb-6">
                        <p>"Com a gestão da OMD, nossos anúncios de carros têm 3x mais engajamento. A IA qualifica leads e agenda test-drives automaticamente. Impressionante!"</p>
                    </div>
                    <div class="flex">
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                        <i class="fas fa-star text-yellow-400"></i>
                    </div>
                </div>
            </div>
            
            <!-- More testimonials in a carousel -->
            <div class="mt-12">
                <div class="carousel-testimonials relative">
                    <div class="carousel-testimonials-inner flex overflow-x-auto snap-x snap-mandatory space-x-6 pb-6">
                        <!-- Clinic -->
                        <div class="flex-shrink-0 w-full md:w-1/2 lg:w-1/3 snap-start">
                            <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20">
                                <div class="flex items-center mb-6">
                                    <img src="https://randomuser.me/api/portraits/women/68.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Clinic Owner">
                                    <div>
                                        <h4 class="text-xl font-bold">Dra. Juliana</h4>
                                        <p class="text-neon-blue">Clínica Saúde Total</p>
                                    </div>
                                </div>
                                <div class="text-gray-300 mb-6">
                                    <p>"Nossa clínica nunca teve tanta visibilidade. A IA responde dúvidas sobre planos de saúde e marca consultas 24h por dia. Pacientes adoram!"</p>
                                </div>
                                <div class="flex">
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Restaurant -->
                        <div class="flex-shrink-0 w-full md:w-1/2 lg:w-1/3 snap-start">
                            <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20">
                                <div class="flex items-center mb-6">
                                    <img src="https://randomuser.me/api/portraits/men/65.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Restaurant Owner">
                                    <div>
                                        <h4 class="text-xl font-bold">Marcos Oliveira</h4>
                                        <p class="text-neon-blue">Restaurante Sabor & Arte</p>
                                    </div>
                                </div>
                                <div class="text-gray-300 mb-6">
                                    <p>"As postagens diárias e stories automatizados triplicaram nosso movimento. A IA até sugere pratos do dia baseado no estoque. Genial!"</p>
                                </div>
                                <div class="flex">
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                </div>
                            </div>
                        </div>
                        
                        <!-- Lawyer -->
                        <div class="flex-shrink-0 w-full md:w-1/2 lg:w-1/3 snap-start">
                            <div class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20">
                                <div class="flex items-center mb-6">
                                    <img src="https://randomuser.me/api/portraits/women/32.jpg" class="w-16 h-16 rounded-full border-2 border-neon-blue mr-4" alt="Lawyer">
                                    <div>
                                        <h4 class="text-xl font-bold">Dra. Fernanda</h4>
                                        <p class="text-neon-blue">Advocacia Lima & Associados</p>
                                    </div>
                                </div>
                                <div class="text-gray-300 mb-6">
                                    <p>"A IA qualifica clientes e agenda consultas jurídicas. Nossa produtividade aumentou e os clientes ficam impressionados com o atendimento."</p>
                                </div>
                                <div class="flex">
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                    <i class="fas fa-star text-yellow-400"></i>
                                </div>
                            </div>
                        </div>
                    </div>
                    <button class="carousel-testimonials-prev absolute top-1/2 left-0 transform -translate-y-1/2 -translate-x-4 bg-neon-blue/30 hover:bg-neon-blue/50 rounded-full p-3 text-white">
                        <i class="fas fa-chevron-left"></i>
                    </button>
                    <button class="carousel-testimonials-next absolute top-1/2 right-0 transform -translate-y-1/2 translate-x-4 bg-neon-blue/30 hover:bg-neon-blue/50 rounded-full p-3 text-white">
                        <i class="fas fa-chevron-right"></i>
                    </button>
                </div>
            </div>
        </div>
    </section>

    <!-- Video Inspiration Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 bg-gradient-to-r from-gray-900 to-dark-blue">
        <div class="max-w-7xl mx-auto">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 neon-text">Inspiração para <span class="text-neon-blue">Seu Negócio</span></h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">Assista e inspire-se com histórias de sucesso</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="video-container rounded-xl overflow-hidden neon-border">
                    <iframe src="https://www.youtube.com/embed/0loRNim6wwc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="video-container rounded-xl overflow-hidden neon-border">
                    <iframe src="https://www.youtube.com/embed/A4pba47DCUg" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
                <div class="video-container rounded-xl overflow-hidden neon-border">
                    <iframe src="https://www.youtube.com/embed/4m_fQVOrm7w" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 px-4 sm:px-6 lg:px-8 bg-dark-blue">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12 items-center">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 neon-text">Sobre a <span class="text-neon-blue">OMD Digital</span></h2>
                    <p class="text-xl text-gray-300 mb-6">
                        Somos uma agência especializada em gestão automatizada de redes sociais com inteligência artificial, ajudando empresas de todos os tamanhos a alcançarem seu potencial máximo no digital.
                    </p>
                    <ul class="space-y-4 mb-8">
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Atendimento 24 horas para Brasil e exterior</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Equipe especializada em mais de 15 nichos de mercado</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Tecnologia de ponta com IA humanizada</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-neon-blue mt-1 mr-3"></i>
                            <span class="text-gray-300">Resultados comprovados e mensuráveis</span>
                        </li>
                    </ul>
                    <div class="flex space-x-4">
                        <a href="https://instagram.com/omdagenciadigitaloficial" target="_blank" class="social-link bg-gray-800 hover:bg-pink-600 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="https://facebook.com/omddigital" target="_blank" class="social-link bg-gray-800 hover:bg-blue-600 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="mailto:oliveiamarketing28@gmail.com" class="social-link bg-gray-800 hover:bg-red-600 text-white w-10 h-10 rounded-full flex items-center justify-center transition">
                            <i class="fas fa-envelope"></i>
                        </a>
                    </div>
                </div>
                <div class="relative">
                    <div class="absolute inset-0 bg-neon-blue/20 rounded-2xl rotate-6"></div>
                    <img src="https://images.unsplash.com/photo-1552664730-d307ca884978?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1470&q=80" class="relative rounded-2xl w-full h-auto" alt="OMD Team">
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-20 px-4 sm:px-6 lg:px-8 bg-gradient-to-r from-neon-blue to-blue-500">
        <div class="max-w-7xl mx-auto text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6 text-dark-blue">Pronto para Transformar Seu Negócio?</h2>
            <p class="text-xl text-dark-blue/90 mb-8 max-w-3xl mx-auto">
                Comece hoje mesmo e tenha uma IA 24h atendendo seus clientes enquanto você foca no crescimento do seu negócio.
            </p>
            <div class="flex flex-col sm:flex-row justify-center gap-4">
                <a href="https://wa.me/5538999857924" class="bg-dark-blue hover:bg-black text-neon-blue font-bold py-4 px-8 rounded-lg transition duration-300 transform hover:scale-105 text-center">
                    <i class="fab fa-whatsapp mr-2"></i> Fale no WhatsApp
                </a>
                <a href="#contact" class="border-2 border-dark-blue text-dark-blue hover:bg-dark-blue/10 font-bold py-4 px-8 rounded-lg transition duration-300 transform hover:scale-105 text-center">
                    Outras Formas de Contato
                </a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 px-4 sm:px-6 lg:px-8 bg-dark-blue">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div>
                    <h2 class="text-3xl md:text-4xl font-bold mb-6 neon-text">Entre em <span class="text-neon-blue">Contato</span></h2>
                    <p class="text-xl text-gray-300 mb-8">
                        Tem dúvidas ou quer saber mais sobre nossos serviços? Preencha o formulário ou entre em contato diretamente por nossos canais.
                    </p>
                    
                    <div class="space-y-6">
                        <div class="flex items-start">
                            <div class="bg-neon-blue/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-phone-alt text-neon-blue"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-bold text-neon-blue mb-1">Telefone/WhatsApp</h4>
                                <a href="https://wa.me/5538999857924" class="text-gray-300 hover:text-neon-blue transition">(38) 99985-7924</a>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-neon-blue/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-envelope text-neon-blue"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-bold text-neon-blue mb-1">Email</h4>
                                <a href="mailto:oliveiamarketing28@gmail.com" class="text-gray-300 hover:text-neon-blue transition">oliveiamarketing28@gmail.com</a>
                            </div>
                        </div>
                        
                        <div class="flex items-start">
                            <div class="bg-neon-blue/20 p-3 rounded-lg mr-4">
                                <i class="fas fa-map-marker-alt text-neon-blue"></i>
                            </div>
                            <div>
                                <h4 class="text-lg font-bold text-neon-blue mb-1">Redes Sociais</h4>
                                <div class="flex space-x-4">
                                    <a href="https://instagram.com/omdagenciadigitaloficial" target="_blank" class="text-gray-300 hover:text-neon-blue transition">
                                        <i class="fab fa-instagram text-xl"></i>
                                    </a>
                                    <a href="https://facebook.com/omddigital" target="_blank" class="text-gray-300 hover:text-neon-blue transition">
                                        <i class="fab fa-facebook-f text-xl"></i>
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <form class="bg-gray-900 rounded-xl p-8 border border-neon-blue/20">
                        <div class="grid grid-cols-1 gap-6">
                            <div>
                                <label for="name" class="block text-gray-300 mb-2">Nome</label>
                                <input type="text" id="name" class="w-full bg-gray-800 border border-gray-700 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-neon-blue text-white" placeholder="Seu nome completo">
                            </div>
                            <div>
                                <label for="email" class="block text-gray-300 mb-2">Email</label>
                                <input type="email" id="email" class="w-full bg-gray-800 border border-gray-700 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-neon-blue text-white" placeholder="seu@email.com">
                            </div>
                            <div>
                                <label for="phone" class="block text-gray-300 mb-2">Telefone</label>
                                <input type="tel" id="phone" class="w-full bg-gray-800 border border-gray-700 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-neon-blue text-white" placeholder="(00) 00000-0000">
                            </div>
                            <div>
                                <label for="business" class="block text-gray-300 mb-2">Tipo de Negócio</label>
                                <select id="business" class="w-full bg-gray-800 border border-gray-700 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-neon-blue text-white">
                                    <option value="">Selecione...</option>
                                    <option value="restaurant">Restaurante/Lanchonete</option>
                                    <option value="salon">Salão de Beleza</option>
                                    <option value="clinic">Clínica Médica</option>
                                    <option value="lawyer">Advocacia</option>
                                    <option value="auto">Loja de Automóveis</option>
                                    <option value="other">Outro</option>
                                </select>
                            </div>
                            <div>
                                <label for="message" class="block text-gray-300 mb-2">Mensagem</label>
                                <textarea id="message" rows="4" class="w-full bg-gray-800 border border-gray-700 rounded-lg py-3 px-4 focus:outline-none focus:ring-2 focus:ring-neon-blue text-white" placeholder="Conte-nos sobre seu negócio e como podemos ajudar"></textarea>
                            </div>
                            <div>
                                <button type="submit" class="w-full bg-neon-blue hover:bg-neon-blue/90 text-dark-blue font-bold py-3 px-6 rounded-lg transition">Enviar Mensagem</button>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 py-12 px-4 sm:px-6 lg:px-8 border-t border-neon-blue/20">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold text-neon-blue mb-4">OMD Digital</h3>
                    <p class="text-gray-400">
                        Transformando negócios através da gestão automatizada em redes sociais com inteligência artificial.
                    </p>
                </div>
                <div>
                    <h4 class="text-lg font-bold text-white mb-4">Serviços</h4>
                    <ul class="space-y-2">
                        <li><a href="#services" class="text-gray-400 hover:text-neon-blue transition">Pacote Básico</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-neon-blue transition">Pacote Premium</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-neon-blue transition">Pacote Empresarial</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-neon-blue transition">IA 24h Humanizada</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold text-white mb-4">Links Rápidos</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-neon-blue transition">Home</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-neon-blue transition">Serviços</a></li>
                        <li><a href="#testimonials" class="text-gray-400 hover:text-neon-blue transition">Depoimentos</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-neon-blue transition">Sobre</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-neon-blue transition">Contato</a></li>
                    </ul>
                </div>
                <div>
                    <h4 class="text-lg font-bold text-white mb-4">Contato</h4>
                    <ul class="space-y-2">
                        <li class="flex items-center">
                            <i class="fas fa-phone-alt text-neon-blue mr-2"></i>
                            <a href="https://wa.me/5538999857924" class="text-gray-400 hover:text-neon-blue transition">(38) 99985-7924</a>
                        </li>
                        <li class="flex items-center">
                            <i class="fas fa-envelope text-neon-blue mr-2"></i>
                            <a href="mailto:oliveiamarketing28@gmail.com" class="text-gray-400 hover:text-neon-blue transition">oliveiamarketing28@gmail.com</a>
                        </li>
                        <li class="flex items-center">
                            <i class="fab fa-instagram text-neon-blue mr-2"></i>
                            <a href="https://instagram.com/omdagenciadigitaloficial" target="_blank" class="text-gray-400 hover:text-neon-blue transition">@omdagenciadigitaloficial</a>
                        </li>
                        <li class="flex items-center">
                            <i class="fab fa-facebook-f text-neon-blue mr-2"></i>
                            <a href="https://facebook.com/omddigital" target="_blank" class="text-gray-400 hover:text-neon-blue transition">Omd omddigital</a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="border-t border-gray-800 mt-12 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-400 text-sm mb-4 md:mb-0">© 2023 OMD Digital. Todos os direitos reservados.</p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-neon-blue transition text-sm">Termos de Serviço</a>
                    <a href="#" class="text-gray-400 hover:text-neon-blue transition text-sm">Política de Privacidade</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- Back to Top Button -->
    <button class="back-to-top fixed bottom-8 right-8 bg-neon-blue text-dark-blue w-12 h-12 rounded-full flex items-center justify-center opacity-0 invisible transition-all duration-300 transform translate-y-4">
        <i class="fas fa-arrow-up"></i>
    </button>

    <script>
        // Mobile menu toggle
        document.querySelector('.mobile-menu-button').addEventListener('click', function() {
            document.querySelector('.mobile-menu').classList.toggle('hidden');
        });

        // Smooth scrolling for navigation links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    document.querySelector('.mobile-menu').classList.add('hidden');
                }
            });
        });

        // Carousel functionality
        let currentSlide = 0;
        const slides = document.querySelectorAll('.carousel-item');
        const totalSlides = slides.length;

        function showSlide(index) {
            slides.forEach((slide, i) => {
                slide.classList.toggle('active', i === index);
            });
        }

        document.querySelector('.carousel-control-prev').addEventListener('click', function() {
            currentSlide = (currentSlide - 1 + totalSlides) % totalSlides;
            showSlide(currentSlide);
        });

        document.querySelector('.carousel-control-next').addEventListener('click', function() {
            currentSlide = (currentSlide + 1) % totalSlides;
            showSlide(currentSlide);
        });

        // Testimonials carousel
        const testimonialsInner = document.querySelector('.carousel-testimonials-inner');
        const testimonials = document.querySelectorAll('.carousel-testimonials-inner > div');
        let currentTestimonial = 0;
        const totalTestimonials = testimonials.length;

        function scrollTestimonial(direction) {
            if (direction === 'next') {
                currentTestimonial = (currentTestimonial + 1) % totalTestimonials;
            } else {
                currentTestimonial = (currentTestimonial - 1 + totalTestimonials) % totalTestimonials;
            }
            
            const scrollPosition = testimonials[currentTestimonial].offsetLeft - 
                                 testimonialsInner.offsetLeft;
            
            testimonialsInner.scrollTo({
                left: scrollPosition,
                behavior: 'smooth'
            });
        }

        document.querySelector('.carousel-testimonials-prev').addEventListener('click', () => scrollTestimonial('prev'));
        document.querySelector('.carousel-testimonials-next').addEventListener('click', () => scrollTestimonial('next'));

        // Back to top button
        const backToTopButton = document.querySelector('.back-to-top');
        window.addEventListener('scroll', function() {
            if (window.pageYOffset > 300) {
                backToTopButton.classList.remove('opacity-0', 'invisible', 'translate-y-4');
                backToTopButton.classList.add('opacity-100', 'visible', 'translate-y-0');
            } else {
                backToTopButton.classList.remove('opacity-100', 'visible', 'translate-y-0');
                backToTopButton.classList.add('opacity-0', 'invisible', 'translate-y-4');
            }
        });

        backToTopButton.addEventListener('click', function() {
            window.scrollTo({
                top: 0,
                behavior: 'smooth'
            });
        });

        // Form submission
        document.querySelector('form').addEventListener('submit', function(e) {
            e.preventDefault();
            alert('Mensagem enviada com sucesso! Entraremos em contato em breve.');
            this.reset();
        });

        // Social links
        document.querySelectorAll('.social-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                window.open(this.getAttribute('href'), '_blank');
            });
        });

        // Nav links
        document.querySelectorAll('.nav-link').forEach(link => {
            link.addEventListener('click', function(e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
    </script>
</body>
</html>

