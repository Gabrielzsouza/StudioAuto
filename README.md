# StudioAuto 
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
    <header class="bg-white shadow">
        <div class="container mx-auto px-4 py-6">
            <h1 class="text-3xl font-bold text-center">Meu Portfólio de Fotografia</h1>
        </div> Sobre Mim
Olá! Meu nome é Gabriel Souza e sou um fotógrafo apaixonado por capturar momentos únicos e inesquecíveis. Minha criatividade é a força motriz por trás de cada clique, e encontro inspiração em tudo ao meu redor, especialmente no mundo automobilístico.
Acredito que a fotografia é uma forma de arte que vai além de simplesmente apertar o botão da câmera. É sobre ver o mundo de uma maneira diferente, encontrar beleza nos detalhes e transmitir emoções através de imagens. Minha abordagem é sempre buscar o ângulo perfeito, a luz ideal e o momento exato para criar fotos que falem por si mesmas.

O Que Eu Ofereço
Fotografia Automotiva: Capturo a elegância e a potência dos carros, desde clássicos até superesportivos modernos.
Eventos Automotivos: Registro a emoção e a adrenalina de eventos automobilísticos, como corridas, exposições e encontros de carros.
Retratos e Ensaios: Além do mundo automotivo, adoro fotografar pessoas, capturando suas personalidades e momentos especiais.
    </header>
    <main class="container mx-auto px-4 py-6">
        <section id="portfolio" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-center">Portfólio</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Adicione suas fotos aq!
ui --> 
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto1.jpg" alt="Foto 1" class="w-full h-48 object-cover">
                </div> 
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto2.jpg" alt="Foto 2" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto3.jpg" alt="Foto 3" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto4.jpg" alt="Foto 4" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto5.jpg" alt="Foto 5" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="![Uploading DSC_0428.JPG…]()
" alt="Foto 6" class="w-full h-48 object-cover"> 
                </div> 
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto7.jpg" alt="Foto 7" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto8.jpg" alt="Foto 8" class="w-full h-48 object-cover">
                </div>
            </div>
        </section>
        <section id="contato" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-center">Contato</h2>
            <div class="text-center">
                <p>Telefone: (85) 997508700 </p>
                <p>Email: Gabrielceara.gss@gmail.com</p>
                <p>Redes Sociais: @StudioAutos_ / @Gab.souzs </p>
                <ul class="flex justify-center space-x-4">
                    <li><a href="https://www.instagram.com/seuperfil" class="text-blue-500">Instagram</a></li>
                    <li><a href="https://www.facebook.com/seuperfil" class="text-blue-500">Facebook</a></li>
                    <li><a href="https://www.linkedin.com/in/seuperfil" class="text-blue-500">LinkedIn</a></li>
                </ul>
            </div>
        </section>
    </main>
    <footer class="bg-white shadow mt-12">
        <div class="container mx-auto px-4 py-6 text-center">
            <p>&copy; 2023 Meu Nome. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
@tailwind components;
@tailwind utilities;
├── tailwind.config.js module.exports = {
  purge: ['./src/**/*.{html,js}', './index.html'],
  darkMode: false, // or 'media' or 'class'
  theme: {
    extend: {},
  },
  variants: {
    extend: {},
  },
  plugins: [],
}
