# Portfolio.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>QR Code Generator</title>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
</head>
<body>

    <h2>QR Code Generator</h2>
    <div id="qrcode"></div>

    <script>
        var qrCode = new QRCode(document.getElementById("qrcode"), {
            text: "https://yashrajnavalpure.com",
            width: 128,
            height: 128
        });
    </script>

</body>
</html>
