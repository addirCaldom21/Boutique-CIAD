<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CIAD Boutique</title>

    <style>
        body{
            margin:0;
            font-family: Arial, Helvetica, sans-serif;
            background:#f5f5f5;
        }

        header{
            background:black;
            color:white;
            text-align:center;
            padding:30px;
        }

        header h1{
            margin:0;
            font-size:45px;
        }

        header p{
            font-size:18px;
        }

        .productos{
            display:grid;
            grid-template-columns: repeat(auto-fit, minmax(250px,1fr));
            gap:20px;
            padding:40px;
        }

        .card{
            background:white;
            border-radius:15px;
            overflow:hidden;
            box-shadow:0px 4px 10px rgba(0,0,0,0.2);
            transition:0.3s;
        }

        .card:hover{
            transform:scale(1.03);
        }

        .card img{
            width:100%;
            height:300px;
            object-fit:cover;
        }

        .info{
            padding:20px;
            text-align:center;
        }

        .info h2{
            margin:10px 0;
        }

        .precio{
            color:green;
            font-size:22px;
            font-weight:bold;
        }

        button{
            background:black;
            color:white;
            border:none;
            padding:12px 20px;
            border-radius:10px;
            cursor:pointer;
            margin-top:10px;
        }

        button:hover{
            background:#444;
        }

        footer{
            background:black;
            color:white;
            text-align:center;
            padding:20px;
            margin-top:30px;
        }
    </style>
</head>
<body>

    <header>
        <h1>CIAD Boutique</h1>
        <p>Moda y estilo para todos</p>
    </header>

    <section class="productos">

        <div class="card">
            <img src="https://images.unsplash.com/photo-1521572163474-6864f9cf17ab?q=80&w=1200&auto=format&fit=crop" alt="">
            <div class="info">
                <h2>Playera Casual</h2>
                <p class="precio">$350 MXN</p>
                <button>Comprar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1541099649105-f69ad21f3246?q=80&w=1200&auto=format&fit=crop" alt="">
            <div class="info">
                <h2>Sudadera Moderna</h2>
                <p class="precio">$650 MXN</p>
                <button>Comprar</button>
            </div>
        </div>

        <div class="card">
            <img src="https://images.unsplash.com/photo-1529139574466-a303027c1d8b?q=80&w=1200&auto=format&fit=crop" alt="">
            <div class="info">
                <h2>Conjunto Fashion</h2>
                <p class="precio">$950 MXN</p>
                <button>Comprar</button>
            </div>
        </div>

    </section>

    <footer>
        © 2026 CIAD Boutique
    </footer>

</body>
</html>
