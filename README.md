<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-B">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagem corrigida.png</title>
    <!-- Carregando Tailwind CSS para estilo rápido -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Um fundo escuro suave para a página */
        body {
            background-color: #1a202c; /* bg-gray-900 */
        }
    </style>
</head>
<body class="flex items-center justify-center min-h-screen text-white">

    <div class="p-8 bg-gray-800 rounded-lg shadow-xl text-center">
        
        <h1 class="text-3xl font-bold mb-6">Feliz Aniversário!</h1>
        
        <p class="mb-6 text-gray-300">Pare de conversar e venha comemorar!</p>
        
        <!--
            Aqui é onde a imagem é carregada.
            Certifique-se que o nome do arquivo aqui é EXATAMENTE igual
            ao nome do arquivo que você subiu para o GitHub.
            
            Eu recomendo renomear "imagem (4).jpg" para algo simples como "aniversario.jpg"
            e então alterar o "src" abaixo para "aniversario.jpg".
        -->
        <img 
            src="imagem (4).jpg" 
            alt="Cartão de feliz aniversário com mascotes de futebol americano"
            class="rounded-lg shadow-lg max-w-full h-auto mx-auto"
            style="max-width: 600px;"
        >
        
    </div>

</body>
</html>
