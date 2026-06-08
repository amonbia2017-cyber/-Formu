
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Recursos SST Colombia | Formularios y Más</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Rajdhani:wght@400;600;700&display=swap');
        
        body {
            font-family: 'Rajdhani', sans-serif;
            background-image: 
                linear-gradient(rgba(0, 0, 0, 0.75), rgba(0, 0, 0, 0.85)),
                url('https://images.unsplash.com/photo-1521021833095-012750013c45?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80');
            background-size: cover;
            background-attachment: fixed;
            background-position: center;
            color: #f0f0f0;
        }

        .urban-border {
            border: 1px solid rgba(0, 180, 216, 0.3);
            box-shadow: 0 0 15px rgba(0, 180, 216, 0.2);
        }

        .btn-sst {
            background: linear-gradient(45deg, #00B4D8, #0077B6);
            transition: all 0.3s ease;
        }

        .btn-sst:hover {
            transform: translateY(-3px);
            box-shadow: 0 0 20px rgba(0, 180, 216, 0.6);
        }

        /* Estilos Juegos */
        .card-memory {
            width: 80px;
            height: 80px;
            background: #0077B6;
            cursor: pointer;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 40px;
            border-radius: 8px;
            transition: all 0.3s;
        }
        .card-memory.flipped {
            background: #90E0EF;
            color: #03045E;
        }

        .game-section {
            display: none;
        }
        .game-section.active {
            display: block;
        }
    </style>
</head>
<body>

    <!-- HEADER -->
    <header class="py-6 px-4 bg-black/50 backdrop-blur-md border-b border-cyan-500/30 sticky top-0 z-50">
        <div class="max-w-7xl mx-auto flex flex-col md:flex-row justify-between items-center">
            <h1 class="text-4xl font-bold text-cyan-400 mb-4 md:mb-0">
                <i class="fas fa-hard-hat mr-2"></i>SST COLOMBIA
            </h1>
            <nav class="space-x-4">
                <a href="#formatos" class="text-lg hover:text-cyan-300 transition">📋 Formularios</a>
                <a href="#videos" class="text-lg hover:text-cyan-300 transition">📺 Tutoriales</a>
                <a href="#juegos" class="text-lg hover:text-cyan-300 transition">🎮 Zona Gamer</a>
            </nav>
        </div>
    </header>

    <main class="max-w-7xl mx-auto p-4">

        <!-- HERO SECTION -->
        <section class="text-center my-12 py-12 urban-border rounded-xl bg-black/40">
            <h2 class="text-5xl font-bold mb-4 text-white">Herramientas y Formularios SST</h2>
            <p class="text-xl text-gray-300 max-w-3xl mx-auto">
                Todo lo que necesitas para tu Sistema de Gestión de Seguridad y Salud en el Trabajo, 
                basado en la normativa Colombiana (Decreto 1072, Resolución 031 de 2017 y más).
            </p>
            <div class="mt-8 flex justify-center gap-2 text-sm">
                <span class="bg-cyan-900/50 px-3 py-1 rounded-full">✅ Normatividad Legal</span>
                <span class="bg-cyan-900/50 px-3 py-1 rounded-full">✅ Editables en Excel</span>
                <span class="bg-cyan-900/50 px-3 py-1 rounded-full">✅ Fácil uso</span>
            </div>
        </section>

        <!-- SECCIÓN DE FORMATOS -->
        <section id="formatos" class="my-16">
            <h3 class="text-3xl font-bold mb-8 border-l-4 border-cyan-500 pl-4">📋 Venta de Formularios Excel</h3>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-6">
                
                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Matriz Legal SST</h4>
                    <p class="text-gray-400 mb-4">Identifica y controla los requisitos legales aplicables a tu empresa.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>

                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Matriz de Peligros y Riesgos</h4>
                    <p class="text-gray-400 mb-4">Evaluación cualitativa y cuantitativa según la GTC 45.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>

                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Inspecciones de Seguridad</h4>
                    <p class="text-gray-400 mb-4">Formatos listos para inspeccionar áreas, maquinaria y EPP.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>

                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Investigación de Accidentes</h4>
                    <p class="text-gray-400 mb-4">Formato guía para reportar e investigar incidentes y AT.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>

                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Capacitaciones y Asistencia</h4>
                    <p class="text-gray-400 mb-4">Control de asistencia, temas y evaluaciones de entrenamiento.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>

                <div class="bg-slate-900/70 p-6 rounded-xl urban-border hover:bg-slate-800/70 transition">
                    <i class="fas fa-file-excel text-green-400 text-5xl mb-4"></i>
                    <h4 class="text-2xl font-bold mb-2">Auditoría Interna SST</h4>
                    <p class="text-gray-400 mb-4">Lista de chequeo para verificar el cumplimiento del SG-SST.</p>
                    <a href="#" class="btn-sst text-white font-bold py-2 px-4 rounded-full inline-block">
                        <i class="fab fa-whatsapp mr-2"></i> Consultar Precio
                    </a>
                </div>
            </div>
        </section>

        <!-- SECCIÓN DE VIDEOS -->
        <section id="videos" class="my-16">
            <h3 class="text-3xl font-bold mb-8 border-l-4 border-cyan-500 pl-4">📺 Aprende SST en YouTube</h3>
            
            <div class="grid md:grid-cols-2 gap-8">
                
                <a href="https://www.youtube.com/results?search_query=normativa+sst+colombia+2024" target="_blank" class="bg-red-700/20 p-6 rounded-xl urban-border flex items-center gap-4 hover:bg-red-700/40 transition">
                    <i class="fab fa-youtube text-5xl text-red-500"></i>
                    <div>
                        <h4 class="text-xl font-bold">Normativa Vigente 2024</h4>
                        <p class="text-gray-400">Decretos, leyes y resoluciones actualizadas.</p>
                    </div>
                </a>

                <a href="https://www.youtube.com/results?search_query=como+hacer+matriz+de+riesgos+colombia" target="_blank" class="bg-red-700/20 p-6 rounded-xl urban-border flex items-center gap-4 hover:bg-red-700/40 transition">
                    <i class="fab fa-youtube text-5xl text-red-500"></i>
                    <div>
                        <h4 class="text-xl font-bold">Tutorial Matriz de Riesgos</h4>
                        <p class="text-gray-400">Paso a paso para elaborar tu matriz GTC 45.</p>
                    </div>
                </a>

                <a href="https://www.youtube.com/results?search_query=capacitaciones+sst+colombia" target="_blank" class="bg-red-700/20 p-6 rounded-xl urban-border flex items-center gap-4 hover:bg-red-700/40 transition">
                    <i class="fab fa-youtube text-5xl text-red-500"></i>
                    <div>
                        <h4 class="text-xl font-bold">Material para Capacitaciones</h4>
                        <p class="text-gray-400">Ideas y diapositivas para entrenar al personal.</p>
                    </div>
                </a>

                <a href="https://www.youtube.com/results?search_query=quien+quiere+ser+millonario+sst" target="_blank" class="bg-red-700/20 p-6 rounded-xl urban-border flex items-center gap-4 hover:bg-red-700/40 transition">
                    <i class="fab fa-youtube text-5xl text-red-500"></i>
                    <div>
                        <h4 class="text-xl font-bold">Juegos Didácticos SST</h4>
                        <p class="text-gray-400">Dinámicas para enseñar seguridad laboral.</p>
                    </div>
                </a>
            </div>
        </section>

        <!-- SECCIÓN DE JUEGOS -->
        <section id="juegos" class="my-16">
            <h3 class="text-3xl font-bold mb-8 border-l-4 border-cyan-500 pl-4">🎮 Zona de Aprendizaje Interactivo</h3>
            
            <div class="flex flex-wrap gap-4 mb-6">
                <button onclick="showGame('millonario')" class="btn-sst text-white px-6 py-3 rounded-lg font-bold">💰 ¿Quién quiere ser Millonario? SST</button>
                <button onclick="showGame('memoria')" class="bg-gray-700 hover:bg-gray-600 text-white px-6 py-3 rounded-lg font-bold">🧠 Juego de Memoria</button>
            </div>

            <!-- JUEGO QUIEN QUIERE SER MILLONARIO -->
            <div id="game-millonario" class="game-section active bg-slate-900/80 p-8 rounded-xl urban-border">
                <h4 class="text-3xl font-bold text-center mb-6 text-yellow-400">💰 ¿Quién quiere ser Millonario en SST?</h4>
                
                <div class="text-center mb-6">
                    <p id="pregunta" class="text-2xl mb-8 bg-slate-800 p-4 rounded">¿Cuál es la norma que establece el Sistema de Gestión en Colombia?</p>
                    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                        <button onclick="responder(0)" class="bg-cyan-600 hover:bg-cyan-500 p-3 rounded-lg text-left" id="opt0">Ley 1562 de 2012</button>
                        <button onclick="responder(1)" class="bg-cyan-600 hover:bg-cyan-500 p-3 rounded-lg text-left" id="opt1">Decreto 1072 de 2015</button>
                        <button onclick="responder(2)" class="bg-cyan-600 hover:bg-cyan-500 p-3 rounded-lg text-left" id="opt2">Resolución 2115 de 2017</button>
                        <button onclick="responder(3)" class="bg-cyan-600 hover:bg-cyan-500 p-3 rounded-lg text-left" id="opt3">Código Sustantivo del Trabajo</button>
                    </div>
                    <p id="resultado" class="mt-6 text-xl font-bold"></p>
                    <button onclick="siguientePregunta()" class="mt-4 bg-green-600 hover:bg-green-500 px-6 py-2 rounded hidden" id="nextBtn">Siguiente Pregunta</button>
                </div>
            </div>

            <!-- JUEGO DE MEMORIA -->
            <div id="game-memoria" class="game-section bg-slate-900/80 p-8 rounded-xl urban-border text-center">
                <h4 class="text-3xl font-bold mb-6 text-cyan-400">🧠 Encuentra los Pares de SST</h4>
                <p class="mb-4">Encuentra los símbolos relacionados con seguridad industrial.</p>
                <div id="tablero" class="grid grid-cols-4 gap-4 max-w-md mx-auto"></div>
                <button onclick="iniciarMemoria()" class="mt-6 btn-sst px-6 py-2 rounded">🔄 Reiniciar Juego</button>
            </div>

        </section>

    </main>

    <footer class="mt-20 py-8 bg-black/60 border-t border-cyan-500/30 text-center">
        <p class="text-gray-400">© 2025 Recursos SST Colombia | Diseño Urbano Bogotá 🇨🇴</p>
        <p class="text-sm text-gray-500 mt-2">Cumpliendo con los estándares de Seguridad y Salud en el Trabajo</p>
    </footer>

    <script>
        // LOGICA JUEGO MILLONARIO
        const preguntas = [
            {
                q: "¿Cuál es la norma que reglamenta el SG-SST?",
                o: ["Ley 1562", "Decreto 1072 de 2015", "Res 031", "Ley 50"],
                r: 1
            },
            {
                q: "¿Qué significa la sigla EPP?",
                o: ["Equipo Personal Protegido", "Elemento de Protección Personal", "Equipo de Prevención Permanente", "Elemento Provisional Personal"],
                r: 1
            },
            {
                q: "¿Quién es responsable de la seguridad en el trabajo?",
                o: ["Solo el Empleador", "Solo el Trabajador", "El Administrador de la ARP", "Ambos, Empleador y Trabajador"],
                r: 3
            },
            {
                q: "¿Qué es un accidente de trabajo?",
                o: ["Suceso repentino que sobreviene por causa o con ocasión del trabajo", "Cualquier dolor que sienta el trabajador", "Enfermedad que se desarrolla con el tiempo", "Accidente ocurrido en la casa"],
                r: 0
            }
        ];

        let indexPregunta = 0;

        function mostrarPregunta() {
            document.getElementById('pregunta').textContent = preguntas[indexPregunta].q;
            document.getElementById('opt0').textContent = preguntas[indexPregunta].o[0];
            document.getElementById('opt1').textContent = preguntas[indexPregunta].o[1];
            document.getElementById('opt2').textContent = preguntas[indexPregunta].o[2];
            document.getElementById('opt3').textContent = preguntas[indexPregunta].o[3];
            document.getElementById('resultado').textContent = '';
            document.getElementById('nextBtn').classList.add('hidden');
        }

        function responder(opcion) {
            if(opcion === preguntas[indexPregunta].r) {
                document.getElementById('resultado').textContent = "✅ ¡CORRECTO! Muy bien.";
                document.getElementById('resultado').className = "mt-6 text-xl font-bold text-green-400";
            } else {
                document.getElementById('resultado').textContent = "❌ INCORRECTO. Sigue aprendiendo.";
                document.getElementById('resultado').className = "mt-6 text-xl font-bold text-red-400";
            }
            document.getElementById('nextBtn').classList.remove('hidden');
        }

        function siguientePregunta() {
            indexPregunta++;
            if(indexPregunta >= preguntas.length) indexPregunta = 0;
            mostrarPregunta();
        }

        // LOGICA JUEGO MEMORIA
        const iconos = ['👷', '🦺', '⛑️', '🛡️', '🔧', '⚠️', '🚧', '🚑'];
        let cartas = [...iconos, ...iconos];
        let primeraCarta = null;
        let bloqueado = false;

        function mezclar(array) {
            return array.sort(() => Math.random() - 0.5);
        }

        function iniciarMemoria() {
            bloqueado = false;
            primeraCarta = null;
            const tablero = document.getElementById('tablero');
            tablero.innerHTML = '';
            cartas = mezclar(cartas);
            
            cartas.forEach((icono, index) => {
                const div = document.createElement('div');
                div.className = 'card-memory';
                div.dataset.icono = icono;
                div.innerHTML = '?';
                div.onclick = () => voltearCarta(div);
                tablero.appendChild(div);
            });
        }

        function voltearCarta(carta) {
            if(bloqueado || carta.classList.contains('flipped')) return;
            
            carta.classList.add('flipped');
            carta.textContent = carta.dataset.icono;

            if(!primeraCarta) {
                primeraCarta = carta;
            } else {
                if(primeraCarta.dataset.icono === carta.dataset.icono && primeraCarta !== carta) {
                    // Pareja encontrada
                    primeraCarta = null;
                } else {
                    bloqueado = true;
                    setTimeout(() => {
                        primeraCarta.classList.remove('flipped');
                        primeraCarta.textContent = '?';
                        carta.classList.remove('flipped');
                        carta.textContent = '?';
                        primeraCarta = null;
                        bloqueado = false;
                    }, 1000);
                }
            }
        }

        // MOSTRAR JUEGOS
        function showGame(game) {
            document.querySelectorAll('.game-section').forEach(el => el.classList.remove('active'));
            if(game === 'millonario') {
                document.getElementById('game-millonario').classList.add('active');
            } else {
                document.getElementById('game-memoria').classList.add('active');
                iniciarMemoria(); // Iniciar juego al entrar
            }
        }

        // INICIO
        mostrarPregunta();

    </script>
</body>
</html>
