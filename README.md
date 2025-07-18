<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Minha Casa Minha Vida - Seu Novo Lar</title>
    <!-- Carrega o Tailwind CSS para estilização -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Carrega a fonte Inter do Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <!-- Carrega o Font Awesome para o ícone do WhatsApp -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        /* Define a fonte Inter para todo o corpo da página */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-green-600 min-h-screen flex items-center justify-center p-4">
    <!-- Container principal do formulário, centralizado e com sombra -->
    <div class="bg-white rounded-lg shadow-xl p-8 max-w-md w-full mx-auto">
        <div class="text-center mb-6">
            <!-- Logo do Minha Casa Minha Vida (placeholder) -->
            <!-- Substitua esta URL pela imagem real do logo, se tiver uma -->
            <img src="https://placehold.co/200x100/007bff/ffffff?text=Minha+Casa+Minha+Vida+Logo" alt="Logo Minha Casa Minha Vida" class="mx-auto mb-4 rounded-md">
            <h1 class="text-3xl font-bold text-gray-800 mb-2">Realize o Sonho da Casa Própria!</h1>
            <p class="text-gray-600">Preencha seus dados para saber como o programa Minha Casa Minha Vida pode te ajudar.</p>
        </div>

        <!-- Formulário de captura de dados -->
        <form class="space-y-4">
            <div>
                <label for="nome" class="block text-gray-700 text-sm font-semibold mb-1">Nome Completo</label>
                <input type="text" id="nome" name="nome" placeholder="Seu nome"
                       class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
            </div>
            <div>
                <label for="telefone" class="block text-gray-700 text-sm font-semibold mb-1">Telefone (WhatsApp)</label>
                <input type="tel" id="telefone" name="telefone" placeholder="(XX) XXXXX-XXXX"
                       class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
            </div>
            <div>
                <label for="renda" class="block text-gray-700 text-sm font-semibold mb-1">Renda Familiar Mensal</label>
                <input type="number" id="renda" name="renda" placeholder="R$ 0,00"
                       class="w-full px-4 py-2 border border-gray-300 rounded-md focus:outline-none focus:ring-2 focus:ring-green-500">
            </div>
            <!-- Botão de envio dos dados, com cor verde e responsivo -->
            <button type="submit"
                    class="w-full bg-green-500 text-white font-bold py-3 px-4 rounded-md hover:bg-green-700 focus:outline-none focus:ring-2 focus:ring-green-500 focus:ring-opacity-50 transition duration-300 ease-in-out">
                Enviar Meus Dados
            </button>
        </form>

        <!-- Seção para contato direto via WhatsApp -->
        <div class="mt-6 text-center">
            <p class="text-gray-600 mb-3">Ou fale conosco diretamente pelo WhatsApp:</p>
            <!-- Botão do WhatsApp, com cor amarela e responsivo -->
            <!-- IMPORTANTE: Substitua '5511953282008' pelo seu número de telefone com DDD -->
            <a href="https://wa.me/5511953282008?text=Olá!%20Tenho%20interesse%20no%20programa%20Minha%20Casa%20Minha%20Vida." target="_blank"
               class="w-full inline-block bg-yellow-500 text-gray-800 font-bold py-3 px-4 rounded-md hover:bg-yellow-600 focus:outline-none focus:ring-2 focus:ring-yellow-500 focus:ring-opacity-50 transition duration-300 ease-in-out">
                <i class="fab fa-whatsapp mr-2"></i> Falar no WhatsApp
            </a>
        </div>
    </div>
</body>
</html>
