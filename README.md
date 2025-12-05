<!DOCTYPE html>
<html>
<head>
    <title>My Picture Gallery</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            text-align: center;
        }
        h1 {
            color: #333;
        }
        .gallery {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 30px;
        }
        .gallery img {
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
            border: 2px solid #555;
        }
    </style>
</head>
<body>

    <h1>My Picture Gallery</h1>

    <div class="gallery">
        <img src="/pic/FB_IMG_1760519949096.jpg" alt="Sample Picture 1">
        <img src="/pic/FB_IMG_1760519794933.jpg" alt="Sample Picture 2">
        <img src="/pic/FB_IMG_1760519842996.jpg" alt="Sample Picture 3">
    </div>

</body>
</html>
