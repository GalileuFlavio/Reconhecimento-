# Reconhecimento-
Reconhecimento Facial
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Reconhecimento Facial</title>
    <script defer src="https://cdn.jsdelivr.net/npm/@tensorflow/tfjs"></script>
    <script defer src="https://cdn.jsdelivr.net/npm/face-api.js"></script>
    <script defer src="app.js"></script>
</head>
<body>
    <h1>Reconhecimento Facial - Recife, PE</h1>
    <video id="video" width="720" height="560" autoplay muted></video>
    <canvas id="canvas"></canvas>
    <form id="userForm">
        <input type="text" id="email" placeholder="Email" required><br>
        <input type="text" id="phone" placeholder="Telefone" required><br>
        <button type="submit">Cadastrar</button>
    </form>
    <script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-app.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-auth.js"></script>
    <script src="https://www.gstatic.com/firebasejs/9.0.0/firebase-firestore.js"></script>
</body>
</html>
