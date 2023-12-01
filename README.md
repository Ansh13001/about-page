# about-page
# Demo About page using html and CSS
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us</title>
    <link rel="stylesheet" href="css.css">
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
            color: #333;
        }

        header {
            background-color: #8e44ad; /* Light Purple */
            color: #fff;
            text-align: center;
            padding: 20px;
            animation: fadeIn 1.5s ease-in-out;
        }

        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }

        section {
            margin: 20px;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }

        .c4 {
            color: #fdda0f; /* Yellow */
        }

        ol {
            list-style: none;
            padding: 0;
        }

        li {
            margin-bottom: 20px;
            border-bottom: 1px solid #ddd;
            padding-bottom: 10px;
        }

        img {
            border-radius: 50%;
            margin-right: 10px;
        }

        dl {
            margin: 0;
        }

        dt {
            font-size: 18px;
            font-weight: bold;
            margin-bottom: 5px;
            color: #8e44ad; /* Light Purple */
        }

        dd {
            font-style: italic;
            color: #fcfbfb;
        }

        footer {
            background-color: #8e44ad; /* Light Purple */
            color: #ecf0f1;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
            animation: rotateColor 5s linear infinite;
        }

        @keyframes rotateColor {
            0% {
                background-color: #8e44ad; /* Light Purple */
            }
            25% {
                background-color: #835083; /* Dark Purple */
            }
            50% {
                background-color: #e73cd6; /* Red */
            }
            75% {
                background-color: #9327ae; /* Green */
            }
            100% {
                background-color: #8e44ad; /* Light Purple */
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>About Us</h1>
        <p>Welcome to our webpage. <br>Learn more about the amazing team behind this website.</p>
    </header>
    <section>
        <header class="c4">
            <h1 style="text-align: center; color: #dfe35f;">Former Members of Our Team</h1>
            <ol>
                <li>
                    <img src="ankit.jpg" width="50" height="50">
                    <dl>
                        <font size="+1"><b>Ansh Kumar Sonker</b></font>
                        <dt></dt>
                        <dd>He is the one who applied and created HTML and CSS files.</dd>
                    </dl>
                </li>
                <li>
                    <img src="Agniva.jpg" width="50" height="50">
                    <dl>
                        <font size="+1"><b>Harshit</b></font>
                        <dt></dt>
                        <dd>He is the one who gave ideas about how this website should be created.</dd>
                    </dl>
                </li>
                <li>
                    <img src="Utkarsh.jpg" width="50" height="50">
                    <dl>
                        <font size="+1"><b>Ravi</b></font>
                        <dt></dt>
                        <dd>He is the one who contributed some help in a minor portion of our website.</dd>
                    </dl>
                </li>
            </ol>
        </header>
    </section>
    <footer>
        <p>&copy; 2023 Lovely Professional University. All rights reserved.</p>
    </footer>
</body>
</html>
