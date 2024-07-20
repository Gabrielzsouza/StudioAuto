# StudioAuto 
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Fotografia</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900 font-sans">
    <header class="bg-white shadow">
        <div class="container mx-auto px-4 py-6">
            <h1 class="text-3xl font-bold text-center">Meu Portfólio de Fotografia</h1>
        </div>
    </header>
    <main class="container mx-auto px-4 py-6">
        <section id="portfolio" class="my-12">
            <h2 class="text-2xl font-semibold mb-4 text-center">Portfólio</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
                <!-- Adicione suas fotos aq![DSC_0555](https://github.com/user-attachments/assets/014f79f5-6911-4988-bbff-baaa715cba0c) ![DSC_0494](https://github.com/user-attachments/assets/a1eb843a-de23-46f9-ae83-06a8f8f6e00b) ![Uploading DSC_0428.JPG…]()


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
