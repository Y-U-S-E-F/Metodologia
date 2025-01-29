<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Metodología</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            line-height: 1.6;
            margin: 20px;
            padding: 20px;
            background: linear-gradient(to right, #e3f2fd, #90caf9);
            scroll-behavior: smooth;
        }
        .container {
            max-width: 850px;
            margin: auto;
            background: #fff;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.3);
            animation: fadeIn 1s ease-in;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-10px); }
            to { opacity: 1; transform: translateY(0); }
        }
        h1, h2, h3 {
            color: #333;
            text-align: center;
        }
        p {
            text-align: justify;
            font-size: 1.1em;
        }
        ul {
            margin-left: 20px;
            padding: 15px;
            background: #e3f2fd;
            border-radius: 8px;
            list-style: none;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }
        ul li {
            padding: 8px 0;
            position: relative;
        }
        ul li::before {
            content: '✔';
            color: #007BFF;
            font-weight: bold;
            position: absolute;
            left: -20px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background: #f9f9f9;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 3px 8px rgba(0, 0, 0, 0.2);
        }
        table, th, td {
            border: 1px solid #ddd;
            text-align: left;
            padding: 12px;
            transition: background 0.3s;
        }
        th {
            background: #007BFF;
            color: white;
        }
        tr:hover {
            background: #e3f2fd;
        }
        .back-to-top {
            display: block;
            margin: 20px auto;
            padding: 12px;
            width: 220px;
            background: #007BFF;
            color: white;
            text-align: center;
            text-decoration: none;
            border-radius: 8px;
            transition: background 0.3s, transform 0.2s;
            font-weight: bold;
        }
        .back-to-top:hover {
            background: #0056b3;
            transform: scale(1.08);
        }
    </style>
</head>
<body>
    <div class="container" id="top">
        <h1>Metodología</h1>
        <p>La metodología es el <strong>cómo</strong> vamos a llevar a cabo el proyecto. Es el camino para la consecución de objetivos.</p>
        
        <section>
            <h2>Principios, Estrategias y Método de Intervención</h2>
            <p>La metodología adoptada debe partir de los principios de la intervención social e incluir aquellos aspectos importantes a tener en cuenta con el colectivo de intervención.</p>
        </section>
        
        <section>
            <h2>Descripción de las Técnicas</h2>
            <p>En cuanto a la metodología que he empleado para la realización de mi trabajo, cabe destacar que se trata de un trabajo basado en la recolección de información cualitativa.</p>
            
            <p>Pasos que seguí para la investigación:</p>
            <ul>
                <li>Investigación sobre fuentes de información fiables.</li>
                <li>Selección de información relevante para el tema.</li>
                <li>Análisis y síntesis de la información obtenida.</li>
            </ul>
            
            <h3>Datos del SEPE</h3>
            <table>
                <tr>
                    <th>Aspecto</th>
                    <th>Descripción</th>
                </tr>
                <tr>
                    <td>Modalidades de contratación</td>
                    <td>Se analizaron los diferentes tipos de contratos disponibles.</td>
                </tr>
                <tr>
                    <td>Ayudas y subvenciones</td>
                    <td>Se detallaron las ayudas económicas según cada tipo de contrato.</td>
                </tr>
            </table>
        </section>
        
        <a href="#top" class="back-to-top" aria-label="Volver al inicio">⬆ Volver al inicio</a>
    </div>
</body>
