# Real-Time-weather-project
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Weather app</title>
    <link rel="shortcut icon" href="img/bg.jpg" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
</head>

<body>


    <div class="app-main" id="parent">
        <div class="header">
            <h4>Get Weather</h4>
        </div>
        <div class="searchInputBox">
            <input type="text" name="" id="input-box" class="input-box" placeholder="enter city name">
        </div>
        <div class="weather-body" id="weather-body">
            <!-- weather-body will be append through JavaScript -->
        </div>
            
    </div>
   

    <script src="script.js"></script>
    <!-- font awesome icon cdn  -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
        integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
    <!-- sweetalert cdn........ -->
    <script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>

</body>

</html>
