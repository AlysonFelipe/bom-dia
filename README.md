<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dedicação para Kinha</title>

    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">

    <!-- Custom CSS -->
    <style>
        body {
            background-image: "https://as1.ftcdn.net/v2/jpg/07/29/13/88/1000_F_729138814_4JyMv3q0DXCSmQgF2mdx2osM82ipQPDG.jpg";
            background-color: #cc0e1e;
            /* Cor de fundo rosa claro */
            text-align: center;
            padding-top: 50px;
        }

        .btn-primary {
            background-color: #007bff;
            /* Cor de fundo azul */
            color: #fff;
            /* Cor do texto branco */
            border: none;
            padding: 10px 20px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
        }

        .img-monkey {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <div class="container">
        <h1>Para Kinha,</h1>
        <h2>Bom Dia lindeza , tenha um otimo dia!! te amo
            sin sempi!
        </h2>
        <button class="btn btn-primary" onclick="showMonkey()">Clique Aqui</button>
        <img src="https://media1.tenor.com/m/LZMGRzgA8JAAAAAd/macaquinho-macaco.gif" class="img-monkey" id="img-monkey">
    </div>

    <!-- Bootstrap JS (opcional, para funcionalidades avançadas) -->
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.3/dist/umd/popper.min.js"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <script>
        function showMonkey() {
            var imgMonkey = document.getElementById("img-monkey");
            imgMonkey.style.display = "block";
        }
    </script>
</body>


</html>
