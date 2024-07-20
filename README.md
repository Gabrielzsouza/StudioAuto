# StudioAuto
Site de portfólio de fotografia
├── index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Fotografia</title>
    <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 text-gray-900">
    <header class="bg-white shadow">
        <div class="container mx-auto px-4 py-6">
            <h1 class="text-3xl font-bold">Meu Portfólio de Fotografia</h1>
        </div>
    </header>
    <main class="container mx-auto px-4 py-6">
        <section id="portfolio">
            <h2 class="text-2xl font-semibold mb-4">Portfólio</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- Adicione suas fotos aqui -->
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto1.jpg" alt="Foto 1" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto2.jpg" alt="Foto 2" class="w-full h-48 object-cover">
                </div>
                <div class="bg-white shadow rounded overflow-hidden">
                    <img src="foto3.jpg" alt="Foto 3" class="w-full h-48 object-cover">
                </div>
            </div>
        </section>
        <section id="contato" class="mt-12">
            <h2 class="text-2xl font-semibold mb-4">Contato</h2>
            <p>Telefone: (XX) XXXX-XXXX</p>
            <p>Email: seuemail@exemplo.com</p>
            <p>Redes Sociais:</p>
            <ul>
                <li><a href="https://www.instagram.com/seuperfil" class="text-blue-500">Instagram</a></li>
                <li><a href="https://www.facebook.com/seuperfil" class="text-blue-500">Facebook</a></li>
                <li><a href="https://www.linkedin.com/in/seuperfil" class="text-blue-500">LinkedIn</a></li>
            </ul>
        </section>
    </main>
    <footer class="bg-white shadow mt-12">
        <div class="container mx-auto px-4 py-6">
            <p>&copy; 2023 Meu Nome. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
├── styles/
│   └── tailwind.css
└── README.md
