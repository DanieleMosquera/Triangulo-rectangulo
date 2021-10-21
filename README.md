# Triangulo-rectangulo
Calcular la hipotenusa de un triángulo rectángulo

<html>
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hipotenusa</title>
</head>
<body>
    <?php 

    $ca = 3;
    $co = 4;
    $hipotenusa = 0;

    $hipotenusa = sqrt(pow(3, 2)+pow(4, 2));

    echo '<h1>Hipotenusa de un triángulo rectángulo</h1>', '<br/>';
    echo 'Cateto adyacente del triángulo: '.$ca, '<br/>';
    echo 'Cateto opuesto del triángulo: '.$co, '<br/><br/>';
    echo 'Hipotenusa del triángulo: '.$hipotenusa, '<br/>';

    ?>
</body>
</html>
