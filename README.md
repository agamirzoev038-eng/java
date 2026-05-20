<!DOCTYPE html>
<html>
<head>
    <title>Tapşırıq 2</title>
</head>
<body>
    <input type="number" id="a" placeholder="Birinci ədəd">
    <input type="number" id="b" placeholder="İkinci ədəd">
    <button onclick="topla()">+</button>
    <button onclick="cix()">-</button>
    <p id="cavab"></p>
    <script>
        function topla() {
            let x = Number(document.getElementById("a").value);
            let y = Number(document.getElementById("b").value);
            document.getElementById("cavab").innerText = x + y;
        }
        function cix() {
            let x = Number(document.getElementById("a").value);
            let y = Number(document.getElementById("b").value);
            document.getElementById("cavab").innerText = x - y;
        }
    </script>
</body>
</html>
