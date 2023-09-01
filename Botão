<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Botão Interativo</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: black;
        }

        #botao {
            background-color: red;
            color: white;
            padding: 20px 40px;
            border: none;
            cursor: pointer;
            font-size: 16px;
        }

        #mensagem {
            display: none;
            text-align: center;
            font-size: 18px;
            color: white;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <button id="botao" onclick="exibirMensagem()">Clique em mim</button>
    <div id="mensagem"></div>
    <script>
        function exibirMensagem() {
            const botao = document.getElementById('botao');
            const mensagemDiv = document.getElementById('mensagem');
            const mensagem = "Diante da vastidão do tempo e da imensidão do universo, é um prazer inenarrável para mim dividir um planeta e uma época com você.";
            
            botao.style.display = 'none'; // Oculta o botão
            mensagemDiv.textContent = mensagem;
            mensagemDiv.style.display = 'block'; // Exibe a mensagem
        }
    </script>
</body>
</html>
