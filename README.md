<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kalkulatro w JS</title>
    <script>
        function suma()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var suma = a + b;document.getElementById("wynik").innerHTML=suma;    
        }
        function roznica()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var roznica = a - b;
            document.getElementById("wynik").innerHTML=roznica;    
        }
        function mnozenie()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var mnozenie = a * b;document.
getElementById("wynik").innerHTML=mnozenie;    
        }
        function dzielenie()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var dzielenie = a / b;
            document.getElementById("wynik").innerHTML=dzielenie;    
        }
        function modulo()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var modulo = a % b;
document.getElementById("wynik").innerHTML=modulo;    
        }
        function dzielenie_c()
        {
            var a = document.getElementById("a").value;   
            a = parseInt(a);
            var b = document.getElementById("b").value;
            b = parseInt(b);
            var dzielenie_c = a / b;
            dzielenie_c = parseInt(dzielenie_c);
            document.getElementById("wynik").innerHTML=dzielenie_c;    
        }
        function potengowanie()
        {
            var a = document.getElementById("a").value;   
            a = parseFloat(a);
            var b = document.getElementById("b").value;
            b = parseFloat(b);
            var potengowanie = Math.pow(a,b);
            document.getElementById("wynik").innerHTML=potengowanie;    
        }
</script>
</head>
<body>
    <p1>PROSTY KALKULATOR</p1>
    <p>podaj wartosc a =</p>
    <input type="text" value="0" id="a">
    <p>podaj wartosc b =</p>
    <input type="text" value="0" id="b">
    <div id="wynik">TU BÄDZIE WYNIK</div>
    <input type="button" value="+" onclick="suma()">
    <input type="button" value="-" onclick="roznica()">
    <input type="button" value="*" onclick="mnozenie()">
    <input type="button" value="/" onclick="dzielenie()">
    <input type="button" value="%" onclick="modulo()">
    <input type="button" value="//" onclick="dzielenie_c()">
    <input type="button" value="**" onclick="potengowanie()">
</body>
</html>


