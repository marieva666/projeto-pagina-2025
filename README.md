<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Baphomovie</title> <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0d0d0d; /* Fundo muito escuro */
            color: #e0e0e0; /* Texto claro para contraste */
            overflow-x: hidden; /* Evita rolagem horizontal */
        }
        .text-shadow-horror {
            text-shadow: 2px 2px 4px rgba(255, 0, 0, 0.6), -2px -2px 4px rgba(0, 0, 0, 0.8);
        }
        .glow-red {
            box-shadow: 0 0 15px rgba(255, 0, 0, 0.7), 0 0 30px rgba(255, 0, 0, 0.4);
              }
        .gradient-border {
            border-image: linear-gradient(to right, #8b0000, #ff0000, #8b0000) 1;
            border-width: 2px;
            border-style: solid;
        }
        .card-hover-effect:hover {
            transform: translateY(-5px) scale(1.02);
            box-shadow: 0 10px 20px rgba(255, 0, 0, 0.5);
        }
    </style>
</head>
<body class="flex flex-col min-h-screen">

    <header class="bg-black bg-opacity-80 shadow-lg py-4 px-6 md:px-12 flex justify-between items-center fixed w-full z-10 rounded-b-lg">
        <div class="flex items-center">
            <h1 class="text-3xl font-bold text-red-700 text-shadow-horror">Baphomovie</h1>
        </div>
        <nav class="hidden md:flex space-x-8">
            <a href="#" class="text-gray-300 hover:text-red-500 transition duration-300 text-lg font-semibold rounded-md p-2">Início</a>
            <a href="#" class="text-gray-300 hover:text-red-500 transition duration-300 text-lg font-semibold rounded-md p-2">Filmes</a>
            <a href="#" class="text-gray-300 hover:text-red-500 transition duration-300 text-lg font-semibold rounded-md p-2">Séries</a>
            <a href="#" class="text-gray-300 hover:text-red-500 transition duration-300 text-lg font-semibold rounded-md p-2">Contato</a>
        </nav>
        <button class="md:hidden text-gray-300 hover:text-red-500 focus:outline-none">
            <svg class="w-8 h-8" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path></svg>
        </button>
    </header>

    <main class="flex-grow pt-20">
        <section class="relative h-[60vh] md:h-[80vh] flex items-center justify-center text-center bg-cover bg-center" style="background-image: url('https://placehold.co/1920x1080/1a0000/ff0000?text=CENÁRIO+DE+HORROR');">
            <div class="absolute inset-0 bg-black opacity-70"></div>
            <div class="relative z-10 p-6 md:p-12 bg-black bg-opacity-70 rounded-xl shadow-2xl max-w-4xl mx-auto border-2 border-red-800 glow-red">
                <h2 class="text-4xl md:text-6xl font-extrabold text-red-600 mb-4 leading-tight text-shadow-horror">
                    Baphomovie </h2>
                <p class="text-xl md:text-2xl text-gray-300 mb-8">
                    Prepare-se para noites insones. Os pesadelos mais profundos esperam por você.
                </p>
                <button class="bg-red-800 hover:bg-red-900 text-white font-bold py-3 px-8 rounded-full text-xl transition duration-300 transform hover:scale-105 shadow-lg glow-red">
                    Assine Agora e Sinta o Pavor
                </button>
            </div>
        </section>

        <section class="py-16 px-6 md:px-12">
            <h3 class="text-3xl md:text-4xl font-bold text-red-500 mb-10 text-center text-shadow-horror">Lançamentos Macabros</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8">
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=FILME+1" alt="Pôster do Filme 1" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">O Sussurro das Sombras</h4>
                        <p class="text-sm text-gray-400">Um terror psicológico que vai te deixar sem fôlego.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=FILME+2" alt="Pôster do Filme 2" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">A Maldição da Casa Vazia</h4>
                        <p class="text-sm text-gray-400">Um clássico instantâneo do horror sobrenatural.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=FILME+3" alt="Pôster do Filme 3" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">Gritos na Floresta</h4>
                        <p class="text-sm text-gray-400">Quando a natureza se volta contra você.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=FILME+4" alt="Pôster do Filme 4" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">O Espelho do Medo</h4>
                        <p class="text-sm text-gray-400">Reflexos que revelam seus piores pesadelos.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=FILME+5" alt="Pôster do Filme 5" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">A Colheita Silenciosa</h4>
                        <p class="text-sm text-gray-400">O que acontece quando o campo não perdoa.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="py-16 px-6 md:px-12 bg-gray-950">
            <h3 class="text-3xl md:text-4xl font-bold text-red-500 mb-10 text-center text-shadow-horror">Clássicos do Pavor</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8">
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=CLÁSSICO+1" alt="Pôster do Clássico 1" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">O Exorcista</h4>
                        <p class="text-sm text-gray-400">O filme que definiu o gênero de possessão.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=CLÁSSICO+2" alt="Pôster do Clássico 2" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">Psicose</h4>
                        <p class="text-sm text-gray-400">A obra-prima de suspense de Hitchcock.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=CLÁSSICO+3" alt="Pôster do Clássico 3" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">O Iluminado</h4>
                        <p class="text-sm text-gray-400">Um hotel, um inverno e a loucura.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=CLÁSSICO+4" alt="Pôster do Clássico 4" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">Alien, o Oitavo Passageiro</h4>
                        <p class="text-sm text-gray-400">No espaço, ninguém pode ouvir você gritar.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=CLÁSSICO+5" alt="Pôster do Clássico 5" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">O Silêncio dos Inocentes</h4>
                        <p class="text-sm text-gray-400">Um jogo mortal de gato e rato.</p>
                    </div>
                </div>
            </div>
        </section>

        <section class="py-16 px-6 md:px-12">
            <h3 class="text-3xl md:text-4xl font-bold text-red-500 mb-10 text-center text-shadow-horror">Séries Arrepiantes</h3>
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-8">
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=SÉRIE+1" alt="Pôster da Série 1" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">A Residência Hill</h4>
                        <p class="text-sm text-gray-400">Uma família assombrada pelo passado.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=SÉRIE+2" alt="Pôster da Série 2" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">Midnight Mass</h4>
                        <p class="text-sm text-gray-400">Fé e terror se encontram em uma ilha isolada.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=SÉRIE+3" alt="Pôster da Série 3" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">Dark</h4>
                        <p class="text-sm text-gray-400">Viagens no tempo e segredos sombrios.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=SÉRIE+4" alt="Pôster da Série 4" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">American Horror Story</h4>
                        <p class="text-sm text-gray-400">Cada temporada, um novo pesadelo.</p>
                    </div>
                </div>
                <div class="bg-gray-900 rounded-lg overflow-hidden shadow-xl border border-red-900 transition duration-300 card-hover-effect">
                    <img src="https://placehold.co/300x450/330000/ff3333?text=SÉRIE+5" alt="Pôster da Série 5" class="w-full h-auto object-cover rounded-t-lg">
                    <div class="p-4">
                        <h4 class="text-lg font-semibold text-gray-100 mb-2">The Haunting of Bly Manor</h4>
                        <p class="text-sm text-gray-400">Amor e fantasmas em uma mansão assombrada.</p>
                    </div>
                </div>
            </div>
        </section>
    </main>

    <footer class="bg-black bg-opacity-90 py-8 px-6 md:px-12 text-center text-gray-500 text-sm rounded-t-lg">
        <p>&copy; 2025 Baphomovie. Todos os direitos reservados.</p> <div class="flex justify-center space-x-6 mt-4">
            <a href="#" class="text-gray-400 hover:text-red-500 transition duration-300">Email</a> <a href="#" class="text-gray-400 hover:text-red-500 transition duration-300">Suporte</a> <a href="#" class="text-gray-400 hover:text-red-500 transition duration-300">FAQ</a> </div>
    </footer>

</body>
</html>
