<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS3 Image Manipulation</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="image-container">
        <img src="your-image-file.jpg" alt="Description of Image">
    </div>
</body>
</html>
.image-container img {
    box-shadow: 10px 10px 15px rgba(0, 0, 0, 0.5);
}
.image-container {
    background: linear-gradient(to right, #ff7e5f, #feb47b);
    padding: 20px;
    border-radius: 10px;
}
.image-container img {
    filter: blur(5px);
}
filter: grayscale(100%);  /* Converts the image to grayscale */
filter: brightness(0.5);  /* Darkens the image */
.image-container img {
    transform: rotate(15deg);
}
body {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
}

.image-container {
    margin: 20px;
    width: 250px;
}
