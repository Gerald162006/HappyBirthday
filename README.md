

<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('red.jpg'); /* Replace with your background image URL */
            background-size: cover; /* Cover the entire viewport */
            background-position: center; /* Center the background image */
            text-align: center;
            padding: 50px;
            color: white; /* Change text color to white for better contrast */
        }

        .container {
            background-color: rgba(255, 255, 255, 0.8); /* Semi-transparent white background */
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
            padding: 20px;
            max-width: 950px; /* Limit the width of the container */
            margin: auto; /* Center the container */
        }

        h1 {
            color: #ff6347;
        }

        .images {
            display: flex;
            flex-direction: column; /* Stack images vertically */
            align-items: center; /* Center images */
            margin: 20px 0;
        }

        .row {
            display: flex; /* Use flexbox for rows */
            justify-content: center; /* Center the images in the row */
            margin: 10px 0; /* Add margin between rows */
        }

        .images img {
            margin: 10px; /* Add margin around images */
            border-radius: 10px;
            width: 300px; /* Adjust size as needed */
            height: auto;
        }

        p {
            font-size: 18px;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Birthday!</h1>
        <div class="images">
            <div class="row">
                <img src="pic1.jpg" alt="Birthday Cake">
                <img src="pic2.jpg" alt="Balloons">
                <img src="pic3.jpg" alt="Birthday Gifts">
            </div>
            <div class="row">
                <img src="pic4.jpg" alt="Party Hat">
                <img src="pic5.jpg" alt="Confetti">
                <img src="pic6.jpg" alt="Birthday Card">
            </div>
        </div>
        <p>Wishing you a day filled with love and joy!</p>
    </div>
</body>
</html>
