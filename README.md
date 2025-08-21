<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Image Classifier</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>AI Image Classifier</h1>
        <p>Unggah gambar, dan AI akan menebak apa itu!</p>
        <input type="file" id="imageUpload" accept="image/*">
        <button id="classifyButton" disabled>Klasifikasikan Gambar</button>
        <div class="result-box">
            <img id="uploadedImage" src="#" alt="Gambar yang Diunggah" style="display:none;">
            <p id="predictionResult"></p>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html>
