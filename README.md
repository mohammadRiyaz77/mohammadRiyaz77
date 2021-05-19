
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        img {
            width: 380px;
            height: 400px;
            margin-left: 37%;
        }

        #btn1 {
            margin-left: 120px;
            padding: 7px;
            width: 12%;
            font-family: monospace;
            font-weight: bold;
            font-size: 15px;
        }

        button {
            margin-left: 458px;
            padding: 7px;
            width: 12%;
            font-family: monospace;
            font-weight: bold;
            font-size: 15px;
            color: white;
            background: rgb(63, 53, 53);
            border-radius: 10px;
            border-color: rgb(91, 72, 112);
            cursor: pointer;

        }

        button:hover {
            color: rgb(17, 17, 17);
            background-color: rgb(240, 202, 77);
        }
    </style>
</head>

<body>
    <h1 style="text-align: center;">Program for bulb ON and bulb OFF</h1>
    <img src="bulbOFF.jpg" alt="bulboff" id="offBulb"><br><br>
    <button onclick="glow()">Bulb ON</button>
    <button onclick="notglow()" id="btn1">Bulb OFF</button>
    <script>
        function glow() {
            document.getElementById("offBulb").src = "bulbON.jpg";
        }
        function notglow() {
            document.getElementById("offBulb").src = "bulbOFF.jpg";
        }
    </script>
</body>

</html>
