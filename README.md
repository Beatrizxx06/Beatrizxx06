<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Beatriz Xavier Santana - Desenvolvedora</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            color: #333;
        }
        
        .glass-card {
            background: rgba(255, 255, 255, 0.15);
            backdrop-filter: blur(10px);
            border-radius: 20px;
            border: 1px solid rgba(255, 255, 255, 0.2);
            box-shadow: 0 8px 32px rgba(0, 0, 0, 0.1);
        }
        
        .skill-bar {
            background: rgba(255, 255, 255, 0.2);
            height: 8px;
            border-radius: 10px;
            overflow: hidden;
        }
        
        .skill-progress {
            height: 100%;
            border-radius: 10px;
            transition: width 2s ease-in-out;
        }
        
        .language-flag {
            width: 24px;
            height: 24px;
            border-radius: 50%;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            margin-right: 10px;
            font-size: 12px;
        }
        
        .animate-on-scroll {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.6s ease-out, transform 0.6s ease-out;
        }
        
        .animated {
            opacity: 1;
            transform: translateY(0);
        }
        
        .typewriter {
            overflow: hidden;
            border-right: 2px solid #fff;
            white-space: nowrap;
            animation: typing 3.5s steps(40, end), blink-caret 0.75s step-end infinite;
        }
        
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }
        
        @keyframes blink-caret {
            from, to { border-color: transparent }
            50% { border-color: #fff }
        }
        
        .certificate-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 12px 40px rgba(0, 0, 0, 0.2);
        }
        
        .certificate-card {
            transition: all 0.3s ease;
        }
    </style>
</head>
<body class="min-h-screen flex items-center justify-center p-4">
    <div class="max-w-6xl w-full mx-auto">
        <!-- Header Section -->
        <div class="glass-card p-8 mb-8 text-center">
            <div class="w-32 h-32 mx-auto mb-6 rounded-full border-4 border-white overflow-hidden">
                <img src="https://pin.it/aktl9GshP" class="w-full h-full object-cover">
            </div>
            <h1 class="text-4xl font-bold text-white mb-2">Beatriz Xavier Santana</h1>
            <p class="text-xl text-purple-100 mb-2 typewriter">Desenvolvedora & Estudante de ADS</p>
            <p class="text-purple-200 flex items-center justify-center">
                <i class="fas fa-graduation-cap mr-2"></i>
                2º Semestre - Análise e Desenvolvimento de Sistemas
            </p>
            <p class="text-purple-200">
                <i class="fas fa-university mr-2"></i>
                UNICID - Universidade Cidade de São Paulo
            </p>
        </div>

        <!-- About Section -->
        <div class="glass-card p-8 mb-8 animate-on-scroll">
            <h2 class="text-2xl font-semibold text-white mb-4">
                <i class="fas fa-user mr-2"></i>Sobre Mim
            </h2>
            <p class="text-purple-100 leading-relaxed">
                Sou uma estudante apaixonada por tecnologia no 2º semestre de Análise e Desenvolvimento de Sistemas na UNICID. 
                Aos 18 anos, já desenvolvi habilidades em diversas linguagens de programação e ferramentas de design, sempre 
                buscando aprender e me atualizar com as tendências do mercado. Meu objetivo é me tornar uma desenvolvedora 
                full-stack e contribuir com projetos inovadores que façam a diferença.
            </p>
        </div>

        <!-- Skills Section -->
        <div class="glass-card p-8 mb-8 animate-on-scroll">
            <h2 class="text-2xl font-semibold text-white mb-6">
                <i class="fas fa-code mr-2"></i>Habilidades Técnicas
            </h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                <!-- Programming Languages -->
                <div>
                    <h3 class="text-lg font-medium text-purple-200 mb-4">Linguagens de Programação</h3>
                    <div class="space-y-4">
                        <div>
                            <div class="flex justify-between text-white mb-1">
                                <span>HTML/CSS</span>
                                <span>90%</span>
                            </div>
                            <div class="skill-bar">
                                <div class="skill-progress bg-purple-400" style="width: 90%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-white mb-1">
                                <span>JavaScript</span>
                                <span>85%</span>
                            </div>
                            <div class="skill-bar">
                                <div class="skill-progress bg-purple-400" style="width: 85%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-white mb-1">
                                <span>Python</span>
                                <span>75%</span>
                            </div>
                            <div class="skill-bar">
                                <div class="skill-progress bg-purple-400" style="width: 75%"></div>
                            </div>
                        </div>
                        <div>
                            <div class="flex justify-between text-white mb-1">
                                <span>C</span>
                                <span>70%</span>
                            </div>
                            <div class="skill-bar">
                                <div class="skill-progress bg-purple-400" style="width: 70%"></div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Tools & Technologies -->
                <div>
                    <h3 class="text-lg font-medium text-purple-200 mb-4">Ferramentas & Tecnologias</h3>
                    <div class="grid grid-cols-2 gap-4">
                        <div class="bg-purple-600 bg-opacity-30 p-3 rounded-lg text-center text-white">
                            <i class="fas fa-pencil-alt text-2xl mb-2"></i>
                            <p>Design Gráfico</p>
                        </div>
                        <div class="bg-purple-600 bg-opacity-30 p-3 rounded-lg text-center text-white">
                            <i class="fas fa-paint-brush text-2xl mb-2"></i>
                            <p>UI/UX Design</p>
                        </div>
                        <div class="bg-purple-600 bg-opacity-30 p-3 rounded-lg text-center text-white">
                            <i class="fab fa-git-alt text-2xl mb-2"></i>
                            <p>Git</p>
                        </div>
                        <div class="bg-purple-600 bg-opacity-30 p-3 rounded-lg text-center text-white">
                            <i class="fas fa-database text-2xl mb-2"></i>
                            <p>Banco de Dados</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Certificates Section -->
        <div class="glass-card p-8 mb-8 animate-on-scroll">
            <h2 class="text-2xl font-semibold text-white mb-6">
                <i class="fas fa-certificate mr-2"></i>Certificados
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="certificate-card bg-purple-600 bg-opacity-30 p-6 rounded-lg">
                    <i class="fab fa-html5 text-4xl text-orange-500 mb-4"></i>
                    <h3 class="text-lg font-medium text-white mb-2">HTML/CSS</h3>
                    <p class="text-purple-200">Fundamentos e técnicas avançadas de desenvolvimento web</p>
                </div>
                <div class="certificate-card bg-purple-600 bg-opacity-30 p-6 rounded-lg">
                    <i class="fab fa-js-square text-4xl text-yellow-400 mb-4"></i>
                    <h3 class="text-lg font-medium text-white mb-2">JavaScript</h3>
                    <p class="text-purple-200">Programação front-end e lógica de programação</p>
                </div>
                <div class="certificate-card bg-purple-600 bg-opacity-30 p-6 rounded-lg">
                    <i class="fas fa-pencil-alt text-4xl text-red-400 mb-4"></i>
                    <h3 class="text-lg font-medium text-white mb-2">Design Gráfico</h3>
                    <p class="text-purple-200">Princípios de design e ferramentas gráficas</p>
                </div>
            </div>
        </div>

        <!-- Languages Section -->
        <div class="glass-card p-8 mb-8 animate-on-scroll">
            <h2 class="text-2xl font-semibold text-white mb-6">
                <i class="fas fa-globe-americas mr-2"></i>Idiomas
            </h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="bg-purple-600 bg-opacity-30 p-6 rounded-lg text-center">
                    <span class="language-flag bg-green-500 text-white">PT</span>
                    <h3 class="text-lg font-medium text-white inline">Português</h3>
                    <p class="text-purple-200 mt-2">Nativo</p>
                </div>
                <div class="bg-purple-600 bg-opacity-30 p-6 rounded-lg text-center">
                    <span class="language-flag bg-red-500 text-white">ES</span>
                    <h3 class="text-lg font-medium text-white inline">Espanhol</h3>
                    <p class="text-purple-200 mt-2">Intermediário</p>
                </div>
                <div class="bg-purple-600 bg-opacity-30 p-6 rounded-lg text-center">
                    <span class="language-flag bg-blue-500 text-white">EN</span>
                    <h3 class="text-lg font-medium text-white inline">Inglês </h3>
                    <p class="text-purple-200 mt-2">Básico</p>
                </div>
            </div>
            <div class="mt-6 text-center">
                <div class="bg-purple-600 bg-opacity-30 p-6 rounded-lg inline-block">
                    <span class="language-flag bg-red-600 text-white">JP</span>
                    <h3 class="text-lg font-medium text-white inline">Japonês</h3>
                    <p class="text-purple-200 mt-2">Básico</p>
                </div>
            </div>
        </div>

        <!-- Contact Section -->
        <div class="glass-card p-8 text-center animate-on-scroll">
            <h2 class="text-2xl font-semibold text-white mb-6">Vamos Conversar!</h2>
            <p class="text-purple-100 mb-6">Estou sempre aberta a novas oportunidades e colaborações</p>
            <div class="flex justify-center space-x-4">
                <a href="#" class="bg-purple-600 hover:bg-purple-700 text-white px-6 py-3 rounded-lg transition-colors">
                    <i class="fab fa-github mr-2"></i>GitHub
                </a>
                <a href="#" class="bg-blue-600 hover:bg-blue-700 text-white px-6 py-3 rounded-lg transition-colors">
                    <i class="fab fa-linkedin mr-2"></i>LinkedIn
                </a>
                <a href="#" class="bg-green-600 hover:bg-green-700 text-white px-6 py-3 rounded-lg transition-colors">
                    <i class="fas fa-envelope mr-2"></i>Email
                </a>
            </div>
        </div>
    </div>

    <script>
        // Animation on scroll
        document.addEventListener('DOMContentLoaded', function() {
            const animatedElements = document.querySelectorAll('.animate-on-scroll');
            
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('animated');
                    }
                });
            }, {
                threshold: 0.1
            });
            
            animatedElements.forEach(element => {
                observer.observe(element);
            });
            
            // Animate skill bars
            setTimeout(() => {
                document.querySelectorAll('.skill-progress').forEach(progress => {
                    progress.style.width = '0';
                    setTimeout(() => {
                        progress.style.width = progress.style.width;
                    }, 100);
                });
            }, 500);
        });
    </script>
</body>
</html>

