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
            transition:0.3s;
        }

        nav a:hover{
            color:#00e676;
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
            transition:0.3s;
        }

        button:hover{
            background:#00e676;
            transform:scale(1.05);
        }

        .features{
            display:flex;
            justify-content:center;
            flex-wrap:wrap;
            gap:25px;
            padding:50px;
        }

        .card{
            background:#1e1e1e;
            width:280px;
            padding:25px;
            border-radius:15px;
            text-align:center;
        }

        .card h3{
            margin-bottom:15px;
            color:#00e676;
        }

        footer{
            text-align:center;
            padding:30px;
            color:#888;
            margin-top:40px;
        }
    </style>

</head>
<body>

<header>

    <h2>🎵 LunexChat</h2>

    <nav>
        <a href="#">Musiikki</a>
        <a href="chat.html">Chat</a>
        <a href="#">Profiili</a>
    </nav>

</header>

<section class="hero">

    <h1>Tervetuloa LunexChatiin</h1>

    <p>Kuuntele musiikkia ja keskustele ystävien kanssa yhdessä paikassa.</p>

    <button onclick="window.location.href='chat.html'">
        Aloita
    </button>

</section>

<section class="features">

<div class="card">
<h3>💬 Keskustele</h3>
<p>Chattaa kavereiden kanssa reaaliajassa.</p>
</div>

<div class="card">
<h3>🎵 Musiikki</h3>
<p>Kuuntele suosikkikappaleitasi samalla kun keskustelet.</p>
</div>

<div class="card">
<h3>👥 Kaverit</h3>
<p>Löydä uusia ihmisiä ja aloita keskustelu.</p>
</div>

</section>

<footer>

© 2026 LunexChat

</footer>

</body>
</html>
