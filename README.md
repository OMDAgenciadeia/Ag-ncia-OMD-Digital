<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>OMD Digital - Agência de IA & Gestão de Redes Sociais</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Roboto:wght@300;400;700&display=swap');
        
        :root {
            --neon-blue: #08f7fe;
            --neon-purple: #f700ff;
            --deep-blue: #0c1016;
        }
        
        body {
            font-family: 'Roboto', sans-serif;
            background-color: var(--deep-blue);
            color: white;
            overflow-x: hidden;
        }
        
        h1, h2, h3, .neon-font {
            font-family: 'Orbitron', sans-serif;
        }
        
        .neon-text-blue {
            text-shadow: 0 0 10px var(--neon-blue), 0 0 20px var(--neon-blue);
            color: var(--neon-blue);
        }
        
        .neon-text-purple {
            text-shadow: 0 0 10px var(--neon-purple), 0 0 20px var(--neon-purple);
            color: var(--neon-purple);
        }
        
        .neon-border-blue {
            box-shadow: 0 0 10px var(--neon-blue), 0 0 20px var(--neon-blue), inset 0 0 10px var(--neon-blue);
            border: 1px solid var(--neon-blue);
        }
        
        .neon-border-purple {
            box-shadow: 0 0 10px var(--neon-purple), 0 0 20px var(--neon-purple), inset 0 0 10px var(--neon-purple);
            border: 1px solid var(--neon-purple);
        }
        
        .grid-bg {
            background-image: 
                linear-gradient(rgba(8, 247, 254, 0.05) 1px, transparent 1px),
                linear-gradient(90deg, rgba(8, 247, 254, 0.05) 1px, transparent 1px);
            background-size: 30px 30px;
        }
        
        .moving-bg {
            animation: moveBackground 120s linear infinite;
            background-image: radial-gradient(circle, rgba(8, 247, 254, 0.1) 0%, transparent 70%);
        }
        
        @keyframes moveBackground {
            0% { background-position: 0% 0%; }
            100% { background-position: 100% 100%; }
        }
        
        .float-animation {
            animation: floating 6s ease-in-out infinite;
        }
        
        @keyframes floating {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }
        
        .pulse-animation {
            animation: pulse 4s ease infinite;
        }
        
        @keyframes pulse {
            0% { opacity: 0.7; }
            50% { opacity: 1; }
            100% { opacity: 0.7; }
        }
        
        .neon-button {
            transition: all 0.3s ease;
        }
        
        .neon-button:hover {
            transform: scale(1.05);
            box-shadow: 0 0 15px currentColor, 0 0 30px currentColor;
        }
        
        .gradient-text {
            background: linear-gradient(90deg, var(--neon-blue), var(--neon-purple));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }
        
        .tech-circle {
            animation: spin 20s linear infinite;
        }
        
        @keyframes spin {
            from { transform: rotate(0deg); }
            to { transform: rotate(360deg); }
        }
    </style>
</head>
<body class="grid-bg moving-bg">
    <!-- Floating Particle Background -->
    <div class="fixed inset-0 overflow-hidden pointer-events-none">
        <div class="absolute w-2 h-2 bg-blue-400 rounded-full neon-border-blue" style="top: 20%; left: 30%;"></div>
        <div class="absolute w-3 h-3 bg-purple-500 rounded-full neon-border-purple" style="top: 60%; left: 70%;"></div>
        <div class="absolute w-1 h-1 bg-cyan-300 rounded-full neon-border-blue" style="top: 40%; left: 10%;"></div>
        <div class="absolute w-2 h-2 bg-purple-400 rounded-full neon-border-purple" style="top: 80%; left: 40%;"></div>
        <div class="absolute w-1 h-1 bg-blue-300 rounded-full neon-border-blue" style="top: 30%; left: 80%;"></div>
    </div>
    
    <!-- Header Nav -->
    <header class="relative z-50">
        <nav class="container mx-auto px-6 py-4">
            <div class="flex justify-between items-center">
                <div class="text-2xl font-bold neon-text-blue">OMD <span class="neon-text-purple">Digital</span></div>
                <div class="hidden md:flex space-x-8">
                    <a href="#servicos" class="text-white hover:neon-text-blue transition">Serviços</a>
                    <a href="#sobre" class="text-white hover:neon-text-purple transition">Sobre Nós</a>
                    <a href="#depoimentos" class="text-white hover:neon-text-blue transition">Depoimentos</a>
                    <a href="#contato" class="text-white hover:neon-text-purple transition">Contato</a>
                </div>
                <a href="https://dash.superagentes.ai/@omdigital" target="_blank" class="bg-gradient-to-r from-cyan-500 to-purple-600 text-white px-6 py-2 rounded-full neon-button font-bold hover:shadow-lg hover:shadow-cyan-500/50 transition">
                    Fale Conosco
                </a>
                <button class="md:hidden text-white focus:outline-none">
                    <i class="fas fa-bars text-2xl"></i>
                </button>
            </div>
        </nav>
    </header>
    
    <!-- Hero Section -->
    <section class="relative min-h-screen flex items-center overflow-hidden">
        <div class="absolute inset-0 z-0 opacity-20">
            <div class="absolute top-1/4 left-1/4 w-64 h-64 bg-blue-500 rounded-full mix-blend-screen filter blur-3xl opacity-20"></div>
            <div class="absolute top-1/2 right-1/4 w-72 h-72 bg-purple-500 rounded-full mix-blend-screen filter blur-3xl opacity-20"></div>
        </div>
        
        <div class="container mx-auto px-6 relative z-10">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-12 lg:mb-0">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6 gradient-text">
                        Inteligência Artificial para <span class="block">Revolucionar Seu Negócio</span>
                    </h1>
                    <p class="text-lg md:text-xl text-gray-300 mb-8 max-w-lg">
                        Há 7 anos transformando negócios com soluções de IA personalizadas. Integre a inteligência artificial no seu WhatsApp e leve sua empresa para o futuro!
                    </p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="https://dash.superagentes.ai/@omdigital" target="_blank" class="bg-gradient-to-r from-cyan-500 to-blue-600 text-white px-8 py-4 rounded-full neon-button font-bold text-center hover:shadow-lg hover:shadow-cyan-500/50 transition">
                            Fale com Nossa IA <i class="fas fa-arrow-right ml-2"></i>
                        </a>
                        <a href="#servicos" class="border border-cyan-400 text-cyan-400 px-8 py-4 rounded-full font-bold text-center hover:neon-border-blue hover:neon-text-blue transition">
                            Nossos Serviços
                        </a>
                    </div>
                    <div class="mt-8 flex flex-wrap gap-4">
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full bg-blue-500 flex items-center justify-center neon-border-blue">
                                <i class="fas fa-check text-white"></i>
                            </div>
                            <span class="ml-2 text-gray-300">+200 Empresas</span>
                        </div>
                        <div class="flex items-center">
                            <div class="w-10 h-10 rounded-full bg-purple-500 flex items-center justify-center neon-border-purple">
                                <i class="fas fa-globe text-white"></i>
                            </div>
                            <span class="ml-2 text-gray-300">Brasil e Exterior</span>
                        </div>
                    </div>
                </div>
                <div class="lg:w-1/2 flex justify-center relative">
                    <div class="relative w-full max-w-md">
                        <div class="absolute -top-20 -left-20 w-64 h-64 bg-blue-500 rounded-full filter blur-3xl opacity-20"></div>
                        <div class="absolute -bottom-20 -right-20 w-64 h-64 bg-purple-500 rounded-full filter blur-3xl opacity-20"></div>
                        
                        <div class="relative float-animation">
                            <div class="absolute -inset-4 rounded-3xl bg-gradient-to-r from-blue-600 to-purple-600 blur-md opacity-40"></div>
                            <img src="https://images.unsplash.com/photo-1620712943543-bcc4688e7485?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=900&q=80" alt="Inteligência Artificial OMD Digital" class="relative rounded-2xl z-10 border border-gray-800 shadow-2xl">
                        </div>
                        
                        <div class="absolute -bottom-10 -left-10 w-32 h-32 bg-blue-500 bg-opacity-20 rounded-full neon-border-blue flex items-center justify-center overflow-hidden">
                            <div class="w-24 h-24 tech-circle">
                                <img src="https://cdn-icons-png.flaticon.com/512/2103/2103633.png" alt="Tecnologia" class="w-full h-full object-contain">
                            </div>
                        </div>
                        
                        <div class="absolute -top-10 -right-10 w-28 h-28 bg-purple-500 bg-opacity-20 rounded-full neon-border-purple flex items-center justify-center overflow-hidden">
                            <div class="w-20 h-20 tech-circle" style="animation-direction: reverse;">
                                <img src="https://cdn-icons-png.flaticon.com/512/2289/2289147.png" alt="IA" class="w-full h-full object-contain">
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- WhatsApp Integration Section -->
    <section class="py-20 relative overflow-hidden">
        <div class="absolute top-0 left-0 w-full h-full opacity-10">
            <div class="absolute top-1/3 left-1/4 w-80 h-80 bg-blue-500 rounded-full filter blur-3xl"></div>
            <div class="absolute bottom-1/4 right-1/3 w-96 h-96 bg-purple-500 rounded-full filter blur-3xl"></div>
        </div>
        
        <div class="container mx-auto px-6 relative">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-6 neon-text-blue">
                    <span class="neon-text-purple">IA no WhatsApp</span> - O Futuro da Comunicação
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Integramos a inteligência artificial mais avançada diretamente no WhatsApp do seu negócio. Atendimento 24/7, vendas instantâneas e suporte personalizado.
                </p>
            </div>
            
            <div class="grid md:grid-cols-3 gap-10">
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:neon-border-purple transition duration-500">
                    <div class="w-16 h-16 bg-blue-500 bg-opacity-20 rounded-full neon-border-blue flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-robot text-2xl text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4 neon-text-blue">Atendimento Automatizado</h3>
                    <p class="text-gray-300 text-center">
                        Sua empresa nunca mais perderá um cliente por falta de atendimento. Nossa IA responde instantaneamente a qualquer hora.
                    </p>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-purple hover:neon-border-blue transition duration-500">
                    <div class="w-16 h-16 bg-purple-500 bg-opacity-20 rounded-full neon-border-purple flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-comments-dollar text-2xl text-purple-400"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4 neon-text-purple">Vendas Inteligentes</h3>
                    <p class="text-gray-300 text-center">
                        Nossa IA identifica oportunidades de venda e guia o cliente pelo funil de conversão com máxima eficiência.
                    </p>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:neon-border-purple transition duration-500">
                    <div class="w-16 h-16 bg-blue-500 bg-opacity-20 rounded-full neon-border-blue flex items-center justify-center mb-6 mx-auto">
                        <i class="fas fa-brain text-2xl text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold text-center mb-4 neon-text-blue">Aprendizado Contínuo</h3>
                    <p class="text-gray-300 text-center">
                        Quanto mais sua IA conversa, mais inteligente ela fica. Personalizada para o seu negócio e seu público.
                    </p>
                </div>
            </div>
            
            <div class="mt-16 text-center">
                <a href="https://dash.superagentes.ai/@omdigital" target="_blank" class="inline-block bg-gradient-to-r from-purple-500 to-cyan-600 text-white px-8 py-4 rounded-full neon-button font-bold hover:shadow-lg hover:shadow-purple-500/50 transition">
                    <i class="fas fa-bolt"></i>
                </a>
            </div>
        </div>
    </section>
    
    <!-- Services Section -->
    <section id="servicos" class="py-20 relative">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-6 neon-text-blue">
                    Nossos <span class="neon-text-purple">Serviços</span>
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Soluções completas em inteligência artificial e gestão de redes sociais para todos os nichos de mercado.
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:shadow-lg hover:shadow-blue-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-blue-500 bg-opacity-20 rounded-lg neon-border-blue flex items-center justify-center mb-6">
                        <i class="fas fa-robot text-xl text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-blue">IA para WhatsApp</h3>
                    <p class="text-gray-300 mb-4">
                        Atendimento automatizado 24 horas com inteligência artificial integrada diretamente ao WhatsApp Business.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Respostas instantâneas</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Triagem inteligente</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Relatórios de performance</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-purple hover:shadow-lg hover:shadow-purple-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-purple-500 bg-opacity-20 rounded-lg neon-border-purple flex items-center justify-center mb-6">
                        <i class="fas fa-chart-line text-xl text-purple-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-purple">Gestão de Redes Sociais</h3>
                    <p class="text-gray-300 mb-4">
                        Gestão profissional de todas as plataformas com conteúdo estratégico para engajar seu público.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Planejamento de conteúdo</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Monitoramento de resultados</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr=2 mt=1"></i>
                            <span>Análise de concorrência</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:shadow-lg hover:shadow-blue-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-blue-500 bg-opacity-20 rounded-lg neon-border-blue flex items-center justify-center mb-6">
                        <i class="fas fa-cogs text-xl text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-blue">Chatbots Personalizados</h3>
                    <p class="text-gray-300 mb-4">
                        Desenvolvimento de chatbots sob medida para websites, apps e plataformas internas.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Integração com sistemas</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Customização para seu negócio</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Processamento de linguagem natural</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-purple hover:shadow-lg hover:shadow-purple-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-purple-500 bg-opacity-20 rounded-lg neon-border-purple flex items-center justify-center mb-6">
                        <i class="fas fa-fingerprint text-xl text-purple-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-purple">CRMs Inteligentes</h3>
                    <p class="text-gray-300 mb-4">
                        Sistemas de relacionamento com cliente com inteligência artificial para otimizar vendas.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Segmentação preditiva</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Automação de fluxos</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Análise de sentimentos</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:shadow-lg hover:shadow-blue-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-blue-500 bg-opacity-20 rounded-lg neon-border-blue flex items-center justify-center mb-6">
                        <i class="fas fa-brain text-xl text-blue-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-blue">Consultoria em IA</h3>
                    <p class="text-gray-300 mb-4">
                        Identificamos as melhores aplicações de IA para acelerar seu crescimento e reduzir custos.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt=1"></i>
                            <span>Diagnóstico estratégico</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Implantação de soluções</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-blue-400 mr-2 mt-1"></i>
                            <span>Treinamento de equipes</span>
                        </li>
                    </ul>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-purple hover:shadow-lg hover:shadow-purple-500/30 transition duration-500">
                    <div class="w-14 h-14 bg-purple-500 bg-opacity-20 rounded-lg neon-border-purple flex items-center justify-center mb-6">
                        <i class="fas fa-ad text-xl text-purple-400"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 neon-text-purple">Tráfego Pago com IA</h3>
                    <p class="text-gray-300 mb-4">
                        Campanhas otimizadas por inteligência artificial para maximizar seu ROI em mídias sociais.
                    </p>
                    <ul class="space-y-2 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Segmentação avançada</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Otimização em tempo real</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-check text-purple-400 mr-2 mt-1"></i>
                            <span>Relatórios preditivos</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>
    
    <!-- About Section -->
    <section id="sobre" class="py-20 relative bg-gray-900 bg-opacity-50">
        <div class="absolute inset-0 overflow-hidden">
            <div class="absolute top-0 left-0 w-1/2 h-full bg-gradient-to-r from-blue-900 to-transparent opacity-20"></div>
            <div class="absolute top-0 right-0 w-1/2 h-full bg-gradient-to-l from-purple-900 to-transparent opacity-20"></div>
        </div>
        
        <div class="container mx-auto px-6 relative">
            <div class="flex flex-col lg:flex-row items-center">
                <div class="lg:w-1/2 mb-12 lg:mb-0 lg:pr-12">
                    <h2 class="text-3xl md:text-4xl font-bold mb-8 gradient-text">
                        A <span class="neon-text-blue">OMD Digital</span> no Mercado de IA
                    </h2>
                    <div class="space-y-6">
                        <p class="text-gray-300">
                            Há 7 anos no mercado de inteligência artificial, a OMD Digital se consolidou como referência no desenvolvimento de soluções inovadoras para empresas de todos os portes e segmentos.
                        </p>
                        <p class="text-gray-300">
                            Nossa trajetória inclui mais de 200 clientes satisfeitos no Brasil e exterior, provando que a excelência em IA não conhece fronteiras geográficas.
                        </p>
                        <p class="text-gray-300">
                            Liderada por <span class="neon-text-blue">Geraldo Oliveira</span>, especialista em marketing e desenvolvimento de IA, nossa equipe combina expertise técnica com visão estratégica para entregar resultados transformadores.
                        </p>
                    </div>
                    
                    <div class="mt-8 grid grid-cols-2 gap-4">
                        <div class="bg-gray-800 bg-opacity-50 rounded-xl p-4 neon-border-blue">
                            <div class="text-4xl font-bold neon-text-purple mb-2">7+</div>
                            <div class="text-gray-300">Anos no Mercado</div>
                        </div>
                        <div class="bg-gray-800 bg-opacity-50 rounded-xl p-4 neon-border-purple">
                            <div class="text-4xl font-bold neon-text-blue mb-2">200+</div>
                            <div class="text-gray-300">Clientes Atendidos</div>
                        </div>
                        <div class="bg-gray-800 bg-opacity-50 rounded-xl p=4 neon-border-blue">
                            <div class="text-4xl font-bold neon-text-purple mb=2">100%</div>
                            <div class="text-gray-300">Online</div>
                        </div>
                        <div class="bg-gray-800 bg-opacity=50 rounded-xl p-4 neon-border-purple">
                            <div class="text=4xl font-bold neon-text-blue mb-2">∞</div>
                            <div class="text-gray-300">Possibilidades</div>
                        </div>
                    </div>
                </div>
                
                <div class="lg:w-1/2 relative">
                    <div class="relative float-animation">
                        <div class="absolute -inset-4 rounded-3xl bg-gradient-to-r from-blue-600 to-purple-600 blur-lg opacity-30"></div>
                        <img src="https://images.unsplash.com/photo-1573164713988-8665fc963095?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=900&q=80" alt="Equipe OMD Digital" class="relative rounded-2xl z-10 border border-gray-700 shadow-xl">
                    </div>
                    
                    <div class="absolute -bottom-6 -left-6 w-48 h-48 bg-blue-500 bg-opacity-20 rounded-full neon-border-blue flex items-center justify-center overflow-hidden">
                        <div class="w-40 h=40 tech-circle" style="animation-duration: 25s;">
                            <img src="https://cdn-icons-png.flaticon.com/512/2285/2285533.png" alt="Dados" class="w-full h-full object-contain">
                        </div>
                    </div>
                    
                    <div class="absolute -top-6 -right-6 w-40 h-40 bg-purple-500 bg-opacity-20 rounded-full neon-border-purple flex items-center justify-center overflow-hidden">
                        <div class="w-32 h-32 tech-circle" style="animation-direction: reverse; animation-duration: 18s;">
                            <img src="https://cdn-icons-png.flaticon.com/512/2821/2821637.png" alt="Analytics" class="w-full h-full object-contain">
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    
    <!-- Testimonials -->
    <section id="depoimentos" class="py-20 relative overflow-hidden">
        <div class="container mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-5xl font-bold mb-6 neon-text-purple">
                    O Que <span class="neon-text-blue">Dizem</span> Sobre Nós
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                    Empresas que revolucionaram seus resultados com nossas soluções em inteligência artificial.
                </p>
            </div>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:neon-border-purple transition duration-500">
                    <div class="mb-6 flex items-center">
                        <div class="w-12 h-12 rounded-full bg-blue-500 bg-opacity-20 flex items-center justify-center neon-border-blue">
                            <i class="fas fa-quote-left text-blue-400"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-bold text-white">Marta Santos</h4>
                            <p class="text-sm text-gray-400">Empresa de Cosméticos</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "A IA no WhatsApp que a OMD desenvolveu para nós aumentou em 300% nossa taxa de conversão. Antes perdíamos vendas fora do horário comercial, agora vendemos 24 horas por dia!"
                    </p>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-purple hover:neon-border-blue transition duration-500">
                    <div class="mb-6 flex items-center">
                        <div class="w-12 h-12 rounded-full bg-purple-500 bg-opacity-20 flex items-center justify-center neon-border-purple">
                            <i class="fas fa-quote-left text-purple-400"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-bold text-white">Carlos Mendes</h4>
                            <p class="text-sm text-gray-400">Clínica Médica</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "A OMD Digital transformou nosso atendimento. Agendamentos triplicaram e a satisfação dos pacientes subiu para 98%. O chatbot médico deles é incrivelmente preciso."
                    </p>
                </div>
                
                <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-2xl p-8 neon-border-blue hover:neon-border-purple transition duration-500">
                    <div class="mb-6 flex items-center">
                        <div class="w-12 h-12 rounded-full bg-blue-500 bg-opacity-20 flex items-center justify-center neon-border-blue">
                            <i class="fas fa-quote-left text-blue-400"></i>
                        </div>
                        <div class="ml-4">
                            <h4 class="font-bold text-white">Ricardo Almeida</h4>
                            <p class="text-sm text-gray-400">E-commerce de Moda</p>
                        </div>
                    </div>
                    <p class="text-gray-300 italic">
                        "Depois que implementamos a IA da OMD Digital, nosso ticket médio subiu 45% em 3 meses. O sistema identifica perfeitamente necessidades e sugere produtos complementares."
                    </p>
                </div>
            </div>
        </div>
    </section>
    
    <!-- CTA Section -->
    <section class="py-20 relative overflow-hidden">
        <div class="absolute inset-0 bg-gradient-to-r from-blue-900 to-purple-900 opacity-20"></div>
        <div class="container mx-auto px-6 relative">
            <div class="bg-gray-900 bg-opacity-50 backdrop-blur-lg rounded-3xl p-12 text-center neon-border-purple">
                <h2 class="text-3xl md:text-4xl font-bold mb-6 gradient-text">
                    Pronto para <span class="block">Transformar Seu Negócio?</span>
                </h2>
                <p class="text-xl text-gray-300 max-w-3xl mx-auto mb-8">
                    Não importa seu nicho ou tamanho - temos a solução perfeita em IA para acelerar seu crescimento e otimizar seus processos.
                </p>
                <a href="https://dash.superagentes.ai/@omdigital" target="_blank" class="inline-block bg-gradient-to-r from-purple-500 to-cyan-600 text-white px-12 py-4 rounded-full neon-button font-bold text-xl hover:shadow-lg hover:shadow-purple-500/50 transition">
                    Fale com Nossa IA Agora <i class="fas fa-robot ml-3"></i>
                </a>
            </div>
        </div>
    </section>
    
    <!-- Footer -->
    <footer id="contato" class="bg-gray-900 bg-opacity-80 pt-20 pb-10 relative border-t border-gray-800">
        <div class="container mx-auto px-6">
            <div class="grid md:grid-cols-4 gap-10 mb-10">
                <div>
                    <h3 class="text-2xl font-bold mb-6 neon-text-blue">OMD <span class="neon-text-purple">Digital</span></h3>
                    <p class="text-gray-400 mb-4">
                        Especialistas em Inteligência Artificial e Gestão de Redes Sociais há 7 anos no mercado.
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="w-10 h-10 bg-blue-500 bg-opacity-20 rounded-full flex items-center justify-center neon-border-blue hover:text-blue-400 transition">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-purple-500 bg-opacity-20 rounded-full flex items-center justify-center neon-border-purple hover:text-purple-400 transition">
                            <i class="fab fa-facebook-f"></i>
                        </a>
                        <a href="#" class="w-10 h-10 bg-blue-500 bg-opacity-20 rounded-full flex items-center justify-center neon-border-blue hover:text-blue-400 transition">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                    </div>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6 neon-text-blue">Serviços</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">IA para WhatsApp</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-purple transition">Gestão de Redes Sociais</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">Chatbots Personalizados</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-purple transition">CRMs Inteligentes</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">Consultoria em IA</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6 neon-text-purple">Empresa</h4>
                    <ul class="space-y-3">
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">Sobre Nós</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-purple transition">Equipe</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">Cases</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-purple transition">Blog</a></li>
                        <li><a href="#" class="text-gray-400 hover:neon-text-blue transition">Contato</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-bold mb-6 neon-text-blue">Contato</h4>
                    <ul class="space-y-4 text-gray-400">
                        <li class="flex items-start">
                            <i class="fas fa-envelope text-purple-400 mr-3 mt-1"></i>
                            <span>oliveiramarketing28@gmail.com</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-globe text-blue-400 mr-3 mt-1"></i>
                            <span>bit.ly/OMD-IA</span>
                        </li>
                        <li class="flex items-start">
                            <i class="fas fa-map-marker-alt text-purple-400 mr-3 mt-1"></i>
                            <span>100% Online - Atendemos todo Brasil e Exterior</span>
                        </li>
                    </ul>
                </div>
            </div>
            
            <div class="pt-10 border-t border-gray-800 text-center">
                <p class="text-gray-500">
                    &copy; 2023 OMD Digital - Todos os direitos reservados. Desenvolvido com <i class="fas fa-heart text-red-500"></i> e IA por Geraldo Oliveira.
                </p>
            </div>
        </div>
    </footer>
    
    <!-- WhatsApp Float Button -->
    <div class="fixed bottom-6 right-6 z-50">
        <a href="https://dash.superagentes.ai/@omdigital" target="_blank" class="w-16 h-16 bg-green-500 rounded-full flex items-center justify-center shadow-xl hover:bg-green-600 transition neon-border-blue">
            <i class="fab fa-whatsapp text-white text-3xl"></i>
        </a>
    </div>

    <script>
        // Simple animation on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const animateOnScroll = function() {
                const elements = document.querySelectorAll('.neon-border-blue, .neon-border-purple');
                
                elements.forEach(el => {
                    const elementPosition = el.getBoundingClientRect().top;
                    const windowHeight = window.innerHeight;
                    
                    if (elementPosition < windowHeight - 100) {
                        el.style.opacity = '1';
                        el.style.transform = 'translateY(0)';
                    }
                });
            };
            
            // Initial check
            animateOnScroll();
            
            // Check on scroll
            window.addEventListener('scroll', animateOnScroll);
        });
    </script>
</body>
</html>
