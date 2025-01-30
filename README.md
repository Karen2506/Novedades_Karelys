<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tienda de Ropa Karelys</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #5e2129;
            color: white;
            padding: 20px;
            font-size: 24px;
        }
        .container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin: 20px;
        }
        .producto {
            border: 1px solid #ddd;
            border-radius: 5px;
            padding: 15px;
            margin: 10px;
            width: 250px;
            text-align: center;
        }
        .producto img {
            max-width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .boton-comprar {
            background-color: #28a745;
            color: white;
            padding: 10px;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        .boton-comprar:hover {
            background-color: #218838;
        }
    </style>
</head>
<body>
	<header>
        <h1>Bienvenido a nuestra Tienda de Karelys</h1>
        <nav>
            <ul>
                <li><a href="#inicio">Inicio</a></li>
                <li><a href="#hombres">Ropa para Hombres</a></li>
                <li><a href="#mujeres">Ropa para Mujeres</a></li>
                <li><a href="#contacto">Contacto</a></li>
            </ul>
        </nav>
    </header>
		<section id="inicio">
        <h2>Ofertas Especiales</h2>
        <p>Descubre nuestras últimas tendencias en moda.</p>
    </section>
    <div class="container">
        <div class="producto">
            <img src="https://via.placeholder.com/200" alt="Producto 1">
            <h3>Camiseta Negra</h3>
            <p>$20.00</p>
            <button class="boton-comprar">Comprar</button>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/200" alt="Producto 2">
            <h3>Pantalón Vaquero</h3>
            <p>$35.00</p>
            <button class="boton-comprar">Comprar</button>
        </div>
        <div class="producto">
            <img src="https://via.placeholder.com/200" alt="Producto 3">
            <h3>Chaqueta de Cuero</h3>
            <p>$60.00</p>
            <button class="boton-comprar">Comprar</button>
        </div>
    </div>
	<footer id="contacto">
        <h2>Contacto</h2>
        <p>Email: karenadriana221018@gmail.com</p>
        <p>Teléfono: 0981756970</p>
    </footer>
</body>
</html>
