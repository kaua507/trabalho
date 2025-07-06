
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <title>Kauã Marvila Feitosa - Página Pessoal</title>
    <style>
        body {
            background: linear-gradient(135deg, #dbeafe 0%, #f6d5f7 100%);
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }

        h1 {
            color: #2e72b8;
            text-align: center;
            margin-bottom: 10px;
            background: linear-gradient(90deg, #2e72b8 70%, #099a4d 100%);
            color: #fff;
            padding: 18px 0;
            border-radius: 12px;
            box-shadow: 0 2px 10px #b3b3b3;
        }

        p {
            font-size: 1.2em;
            text-align: justify;
            margin-bottom: 16px;
            background: #e7f9ee;
            padding: 16px;
            border-radius: 9px;
            box-shadow: 0 1px 4px #c8e6c9;
        }

        button {
            display: block;
            margin: 0 auto 15px auto;
            padding: 10px 22px;
            background: linear-gradient(90deg, #2e72b8 50%, #099a4d 100%);
            color: #fff;
            border: none;
            border-radius: 20px;
            font-size: 1em;
            cursor: pointer;
            font-weight: bold;
            box-shadow: 0 2px 8px #b3b3b3;
            transition: background 0.3s;
        }

        button:hover {
            background: linear-gradient(90deg, #099a4d 60%, #2e72b8 100%);
        }

        #mensagem {
            text-align: center;
            margin-bottom: 20px;
            color: #099a4d;
            font-weight: bold;
            font-size: 1.1em;
            min-height: 28px;
        }

        ul {
            margin-bottom: 20px;
            margin-top: 10px;
            background: #f0f5ff;
            padding: 20px 30px;
            border-radius: 10px;
            box-shadow: 0 1px 6px #b3b3b3;
            width: fit-content;
            margin-left: auto;
            margin-right: auto;
        }

        ul li {
            margin-bottom: 12px;
            font-size: 1.1em;
            color: #2e72b8;
            font-weight: bold;
        }

        .hobby-img {
            display: block;
            margin: 0 auto 25px auto;
            border-radius: 18px;
            width: 260px;
            height: auto;
            box-shadow: 0 2px 12px #a18cd1;
            border: 4px solid #2e72b8;
        }

        table {
            width: 480px;
            margin: 0 auto 18px auto;
            border-collapse: collapse;
            background: #fff0f6;
            box-shadow: 0 3px 14px #b3b3b3;
            border-radius: 12px;
            overflow: hidden;
        }

        th, td {
            border: 1px solid #e6c1e5;
            padding: 10px 16px;
            text-align: center;
        }

        th {
            background-color: #f6d5f7;
            color: #2e72b8;
            font-size: 1.1em;
        }

        td {
            background: #fdf3ff;
        }

        a {
            color: #fff;
            background: linear-gradient(90deg,#2e72b8 60%, #099a4d 100%);
            padding: 10px 18px;
            border-radius: 15px;
            font-weight: bold;
            text-decoration: none;
            transition: background 0.2s, color 0.2s;
            box-shadow: 0 1px 6px #b3b3b3;
        }

        a:hover {
            background: linear-gradient(90deg, #099a4d 80%, #2e72b8 100%);
            color: #fffbe0;
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- 1. Título principal -->
    <h1>Kauã Marvila Feitosa</h1>

    <!-- 2. Parágrafo com autobiografia -->
    <p>
        Olá! Meu nome é Kauã, tenho 18 anos, moro em Itapemirim e sou apaixonado por tecnologia, música e viagens. Gosto de aprender coisas novas e explorar diferentes culturas.
    </p>
    
    <!-- Botão e mensagem JS -->
    <button id="mensagem-btn">Clique para ver uma mensagem!</button>
    <div id="mensagem"></div>

    <!-- 3. Lista não ordenada com hobbies -->
    <ul>
        <li>Tocar violão</li>
        <li>Jogar videogame</li>
        <li>Viajar</li>
    </ul>
    <br>
    <!-- 4. Imagem representando um hobby -->
    <img src="https://img.freepik.com/fotos-gratis/vista-frontal-de-um-homem-tocando-violao_23-2148739944.jpg" alt="Pessoa tocando violão" class="hobby-img">
    <br><br>

    <!-- 5. Tabela com países -->
    <table>
        <tr>
            <th>País</th>
            <th>Imagem</th>
        </tr>
        <tr>
            <td>Japão</td>
            <td>
                <img src="https://estilo5ponto0mais.com.br/wp-content/uploads/2021/03/Vamos-fazer-um-tour-virtual-pelo-Japao-a-Terra-do-Sol-Nascente2.jpg" alt="Japão" width="100">
            </td>
        </tr>
        <tr>
            <td>Itália</td>
            <td>
                <img src="https://benditacidadania.com.br/wp-content/uploads/2021/02/roma-capital-da-italia.jpg" alt="Itália" width="100">
            </td>
        </tr>
        <tr>
            <td>Canadá</td>
            <td>
                <img src="https://a.travel-assets.com/findyours-php/viewfinder/images/res70/27000/27764-Moraine-Lake.jpg" alt="Canadá" width="100">
            </td>
        </tr>
    </table>

    <!-- 6. Link para site de interesse -->
    <div style="text-align:center;margin-top:30px;">
      <a href="https://www.tecmundo.com.br/" target="_blank">Acesse o Tecmundo para notícias de tecnologia!</a>
    </div>
    
    <script>
        document.getElementById('mensagem-btn').addEventListener('click', function() {
            document.getElementById('mensagem').textContent = 'Nunca pare de aprender e acreditar nos seus sonhos! ✨';
        });
    </script>
</body>
</html>
