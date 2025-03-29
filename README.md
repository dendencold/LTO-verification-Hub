<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LTO Verification Site</title>
    <style>
        body {
            background-color: rgba(0, 0, 255, 0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        input, button {
            margin-top: 10px;
            padding: 10px;
            width: 80%;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>LTO Verification</h1>
        <p>Enter vehicle registration number:</p>
        <input type="text" id="vehicleNumber" placeholder="Enter registration number">
        <button onclick="verifyVehicle()">Verify</button>
        <p id="result"></p>
    </div>
    <script>
        function verifyVehicle() {
            let vehicleNumber = document.getElementById('vehicleNumber').value;
            if (vehicleNumber) {
                document.getElementById('result').innerText = "Checking records for " + vehicleNumber;
                // Placeholder for backend verification logic
            } else {
                document.getElementById('result').innerText = "Please enter a registration number.";
            }
        }
    </script>
</body>
</html><!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LTO Verification Site</title>
    <style>
        body {
            background-color: rgba(0, 0, 255, 0.8);
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            font-family: Arial, sans-serif;
        }
        .container {
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        input, button {
            margin-top: 10px;
            padding: 10px;
            width: 80%;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>LTO Verification</h1>
        <p>Enter vehicle registration number:</p>
        <input type="text" id="vehicleNumber" placeholder="Enter registration number">
        <button onclick="verifyVehicle()">Verify</button>
        <p id="result"></p>
    </div>
    <script>
        function verifyVehicle() {
            let vehicleNumber = document.getElementById('vehicleNumber').value;
            if (vehicleNumber) {
                document.getElementById('result').innerText = "Checking records for " + vehicleNumber;
                // Placeholder for backend verification logic
            } else {
                document.getElementById('result').innerText = "Please enter a registration number.";
            }
        }
    </script>
</body>
</html>
