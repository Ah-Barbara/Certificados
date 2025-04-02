# Certificados
[Java_1.pdf](https://github.com/user-attachments/files/19560358/Java_1.pdf) <br>
[Java_2.pdf](https://github.com/user-attachments/files/19560361/Java_2.pdf)<br>
[Java_3.pdf](https://github.com/user-attachments/files/19560363/Java_3.pdf)<br>
[Java_4.pdf](https://github.com/user-attachments/files/19560364/Java_4.pdf)<br>
[Java_5.pdf](https://github.com/user-attachments/files/19560365/Java_5.pdf)
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Certificados</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f4f4f4;
        }
        .container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            max-width: 1200px;
            margin: auto;
        }
        .certificado {
            background: white;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        .certificado img {
            width: 100%;
            height: auto;
            border-radius: 5px;
        }
        .certificado h3 {
            margin-top: 10px;
            font-size: 1.2em;
        }
        @media (max-width: 768px) {
            .container {
                grid-template-columns: repeat(2, 1fr);
            }
        }
        @media (max-width: 480px) {
            .container {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="certificado">
            <img src="c:\Users\barba\Downloads\Java_5_page-0001.jpg" alt="Certificado 1">
            <h3>Certificado 1</h3>
        </div>
        <div class="certificado">
            <img src="c:\Users\barba\Downloads\Java_4_page-0001.jpg" alt="Certificado 2">
            <h3>Certificado 2</h3>
        </div>
        <div class="certificado">
            <img src="c:\Users\barba\Downloads\Java_3_page-0001.jpg" alt="Certificado 3">
            <h3>Certificado 3</h3>
        </div>
    </div>
</body>
</html>
