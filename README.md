
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <title>strona z zadaniem 17</title>
    <meta name="author" content="Kacper Wawrzyniek-Pekar">
    <meta name="classification" content="edukacja">
    <meta name="keywords" content="edukacja,pascal">
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: Arial, sans-serif;
        }
        #container {
            display: flex;
            flex-direction: column;
            height: 100%;
        }
        #top {
            height: 300px;
            display: flex;
        }
        #menu {
            width: 30%;
        }
        #main {
            width: 70%;
        }
        #bottom {
            height: calc(100% - 300px);
            overflow: hidden;
        }
        iframe {
            width: 100%;
            height: 100%;
            border: none;
        }
    </style>
</head>
<body>
    <div id="container">
        <div id="top">
            <div id="menu">
                <iframe src="MENU_PIN.html" name="MENU_PIN"></iframe>
            </div>
            <div id="main">
                <iframe src="WITAM.html" name="OKNO2"></iframe>
            </div>
        </div>
        <div id="bottom">
            <iframe src="MENU_POZ.html" name="OKNO3" scrolling="no"></iframe>
        </div>
    </div>
</body>
</html>
