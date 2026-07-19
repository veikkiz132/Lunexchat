<!DOCTYPE html>
<html lang="fi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LunexChat</title>

    <style>
        *{
            margin:0;
            padding:0;
            box-sizing:border-box;
            font-family:Arial, Helvetica, sans-serif;
        }

        body{
            background:#121212;
            color:white;
        }

        header{
            background:#1e1e1e;
            padding:20px;
            display:flex;
            justify-content:space-between;
            align-items:center;
        }

        nav a{
            color:white;
            text-decoration:none;
            margin-left:20px;
            font-weight:bold;
        }

        .hero{
            text-align:center;
            padding:100px 20px;
        }

        .hero h1{
            font-size:60px;
            margin-bottom:20px;
        }

        .hero p{
            font-size:22px;
            color:#bbbbbb;
            margin-bottom:40px;
        }

        button{
            background:#00c853;
            color:white;
            border:none;
            padding:15px 35px;
            font-size:18px;
            border-radius:12px;
            cursor:pointer;
        }

        button:hover{
            background:#00e676;
        }
    </style>

</head>
<body>

<header>
    <h2>🎵 LunexChat</h2>

    <nav>
        <a href="#">Musiikki</a>
        <a href="#">Chat</a>
        <a href="#">Profiili</a>
    </nav>
</header>

<section class="hero">
    <h1>Tervetuloa LunexChatiin</h1>

    <p>Kuuntele musiikkia ja keskustele ystävien kanssa yhdessä paikassa.</p>

    <button>Aloita</button>
</section>

</body>
</html>
