<!DOCTYPE html>
<html lang="th">
<head>
    <meta charset="UTF-8">
    <title>คำนวณพื้นที่สี่เหลี่ยมผืนผ้า</title>
</head>
<body>

    <h2>คำนวณพื้นที่สี่เหลี่ยมผืนผ้า</h2>

    <label>ความกว้าง:</label>
    <input type="number" id="width"><br><br>

    <label>ความยาว:</label>
    <input type="number" id="length"><br><br>

    <button onclick="calculateArea()">คำนวณ</button>

    <h3 id="result"></h3>

    <script>
        function calculateArea() {
            let width = document.getElementById("width").value;
            let length = document.getElementById("length").value;

            let area = width * length;

            document.getElementById("result").innerHTML =
                "พื้นที่ = " + area + " ตารางหน่วย";
        }
    </script>

</body>
</html>
