<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Centered Adobe XD Embed</title>
    <style>
        /* Reset margin and padding for body and html */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        /* Ensure body and html fill the viewport */
        body, html {
            width: 100%;
            height: 100%;
            display: flex;
            justify-content: center;
            align-items: center;
            overflow: hidden;
            background-color: #f4f4f4; /* Optional: Customize background color */
        }

        /* Ensure iframe container centers within the viewport */
        .iframe-container {
            width: 100vw;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        /* Set iframe to fill the iframe container */
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div class="iframe-container">
        <iframe src="https://xd.adobe.com/embed/3eb60073-979c-48c9-a728-1ab20c1a8ac1-6be5/?fullscreen" allowfullscreen></iframe>
    </div>
</body>
</html>
