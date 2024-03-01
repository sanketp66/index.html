# index.html

<!DOCTYPE html>
<html>
<head>
    <title>Addition</title>
</head>
<body>
    <h2>Addition</h2>
    <label for="num1">Number 1:</label>
    <input type="number" id="num1"><br><br>
    <label for="num2">Number 2:</label>
    <input type="number" id="num2"><br><br>
    <button onclick="addNumbers()">Add</button><br><br>
    <p id="result"></p>

    <script>
        function addNumbers() {
            var num1 = parseInt(document.getElementById("num1").value);
            var num2 = parseInt(document.getElementById("num2").value);
            var result = num1 + num2;
            document.getElementById("result").innerHTML = "The sum is: " + result;
        }
    </script>
</body>
</html>
