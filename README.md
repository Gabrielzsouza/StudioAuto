# StudioAuto
meu-site-fotografia/
├── index.html <!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Fotografia</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link href="public/styles.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
    <header class="bg-primary text-white shadow">
        <div class="container mx-auto px-4 py-6 flex justify-between items-center">
            <h1 class="text-3xl font-bold">Meu Portfólio</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#portfolio" class="hover:text-highlight">Portfólio</a></li>
                    <li><a href="#sobre" class="hover:text-highlight">Sobre</a></li>
                    <li><a href="#contato" class="hover:text-highlight">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>
    <main class="container mx-auto px-4 py-6">
        <section id="portfolio" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-secondary">Portfólio</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Adicione suas fotos aqui -->
                <div class="bg-white shadow rounded overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="foto1.jpg" alt="Foto 1" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="foto2.jpg" alt="Foto 2" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden transform hover:scale-105 transition-transform duration-300">
                    <img src="foto3.jpg" alt="Foto 3" class="w-full h-48 object-cover">
                </div>
            </div>
        </section>
        <section id="sobre" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-secondary">Sobre</h2>
            <p class="text-lg leading-relaxed">Sou um fotógrafo apaixonado por capturar momentos especiais. Com anos de experiência em fotografia de casamentos, retratos e paisagens, meu objetivo é criar imagens que contem histórias e emocionem.</p>
        </section>
        <section id="contato" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-secondary">Contato</h2>
            <form class="bg-white shadow rounded p-6">
                <div class="mb-4">
                    <label for="nome" class="block text-sm font-medium text-gray-700">Nome</label>
                    <input type="text" id="nome" name="nome" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-highlight focus:border-highlight">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-sm font-medium text-gray-700">Email</label>
                    <input type="email" id="email" name="email" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-highlight focus:border-highlight">
                </div>
                <div class="mb-4">
                    <label for="mensagem" class="block text-sm font-medium text-gray-700">Mensagem</label>
                    <textarea id="mensagem" name="mensagem" rows="4" class="mt-1 block w-full border-gray-300 rounded-md shadow-sm focus:ring-highlight focus:border-highlight"></textarea>
                </div>
                <button type="submit" class="bg-highlight text-white px-4 py-2 rounded-md shadow hover:bg-pink-600 transition-colors duration-300">Enviar</button>
            </form>
        </section>
    </main>
    <footer class="bg-primary text-white shadow mt-12">
        <div class="container mx-auto px-4 py-6 text-center">
            <p>&copy; 2023 Meu Nome. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
├── src/
│   └── styles/
│       └── tailwind.css @tailwind base;
@tailwind components;
@tailwind utilities;
├── tailwind.config.js module.exports = {
  purge: ['./src/**/*.{html,js}', './index.html'],
  darkMode: false, // or 'media' or 'class'
  theme: {
    extend: {
      colors: {
        primary: '#1a202c',
        secondary: '#2d3748',
        accent: '#4a5568',
        highlight: '#ed64a6',
      },
      fontFamily: {
        sans: ['Inter', 'sans-serif'],
      },
    },
  },
  variants: {
    extend: {},
  },
  plugins: [],
}
├── postcss.config.js npm run build:css
└── README.md
