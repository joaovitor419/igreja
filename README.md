 <!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Geração da Cruz</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #2c3e50;
            padding: 20px;
            color: white;
            text-align: center;
        }

        header h1 {
            margin: 0;
        }

        nav {
            margin-top: 10px;
        }

        nav a {
            color: white;
            margin: 0 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            text-decoration: underline;
        }

        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }

        .sobre, .eventos, .contato {
            margin-bottom: 40px;
        }

        h2 {
            color: #2c3e50;
        }

        footer {
            background-color: #2c3e50;
            color: white;
            text-align: center;
            padding: 15px 20px;
            position: relative;
            bottom: 0;
            width: 100%;
        }

        /* Responsividade básica */
        @media(max-width: 600px){
            nav a {
                display: block;
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Geração da Cruz</h1>
    <nav>
        <a href="#sobre">Sobre a Igreja</a>
        <a href="#eventos">Eventos</a>
        <a href="#contato">Contato</a>
    </nav>
</header>

<section id="sobre" class="sobre">
    <h2>Sobre a Igreja</h2>
    <p>Geração da Cruz é uma igreja que acredita na transformação através do amor de Jesus Cristo. Nosso objetivo é promover esperança, fé e união na comunidade, levando a palavra de Deus a todos os que desejam ouvir.</p>
</section>

<section id="eventos" class="eventos">
    <h2>Próximos Eventos</h2>
    <ul>
        <li><strong>Encontro de Jovens</strong> - 15 de Maio às 19h</li>
        <li><strong>Culto de Louvor</strong> - 20 de Maio às 18h</li>
        <li><strong>Campanha de Doações</strong> - Durante todo o mês de Maio</li>
    </ul>
</section>

<section id="contato" class="contato">
    <h2>Contato</h2>
    <p>Endereço: Rua das bênçãos, 123 - Bairro da Fé</p>
    <p>Telefone: (11) 98765-4321</p>
    <p>Email: contato@geracaodacruz.com</p>
</section>

<footer>
    <p>&copy; 2024 Geração da Cruz. Todos os direitos reservados.</p>
</footer>

</body>
</html>
