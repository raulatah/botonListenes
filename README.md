<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Searcher</title>
</head>
<body>
    <div class="container">
        <p>aiksjdnakjsdnbasjdajshdbajshdbakjbdahjbsdjhasbdjhabsdjabsdjhbasjdbajshdbajksdbhajkshbdjahsbdjkasbdjhabsdjhbasjdhbasjhdbajsdbajsdbajksbdajkshbdkjahbsdkjashbdjkashbdjkahbdjkahbdjkahbsdjahbsdjkahbsdjhasbdjhbdjahsbdjahsbdjahbd</p>
 <button class="Motor">Motor</button> <button id="Coche">Coche</button> <button id="Ruedas">Ruedas</button>
 </div>
    <script>
var contenedor = document.querySelector(".container");

contenedor.addEventListener('click', (e) => {
    if(e.target.classList.contains("Motor")){
        var alerta = confirm("Vas a acceder a : https://www.motorpasion.com/");
        if(alerta === true){
             window.location = 'https://www.motorpasion.com/'
        }else{
            new Audio('info.mp3').play();
        }
    }
})

    </script>
