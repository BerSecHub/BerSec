<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BerSec Chronicles</title>
    <style>
        body {
            background-color: black;
            color: #33ff33;
            font-family: 'Courier New', Courier, monospace;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        h1 {
            font-size: 3rem;
            margin-top: 20px;
            text-shadow: 0px 0px 20px #33ff33, 0px 0px 30px #009900;
        }

        .terminal {
            display: inline-block;
            background-color: #111;
            border: 3px solid #0f0;
            padding: 20px;
            text-align: left;
            width: 80%;
            margin: 20px auto;
            box-shadow: 0px 0px 20px #33ff33;
        }

        .blink {
            animation: blink-animation 0.8s steps(2, start) infinite;
            -webkit-animation: blink-animation 0.8s steps(2, start) infinite;
        }

        @keyframes blink-animation {
            to {
                visibility: hidden;
            }
        }

        @-webkit-keyframes blink-animation {
            to {
                visibility: hidden;
            }
        }

        a {
            color: #33ff33;
            text-decoration: none;
            font-weight: bold;
        }

        a:hover {
            text-decoration: underline;
        }

        footer {
            margin-top: 20px;
            font-size: 0.9rem;
            text-shadow: 0px 0px 10px #33ff33;
        }

        .ascii-art {
            font-family: monospace;
            white-space: pre;
            color: #33ff33;
            text-align: left;
            margin: 20px auto;
        }
    </style>
</head>
<body>
    <h1>BerSec Chronicles</h1>
    <div class="ascii-art">
        <pre>

 __      __     
|__) _ _(_  _ _ 
|__)(-| __)(-(_ 
                
        </pre>
    </div>
    <div class="terminal">
        <p>Welcome, explorer! You've entered the uncharted realms of <span style="color: lime;">offensive security</span>.</p>
        <p><span class="blink">&gt;</span> Dive into the art and science of <strong>ethical hacking</strong>, <strong>red teaming</strong>, and <strong>cyber warfare strategies</strong>.</p>
        <p><a href="https://github.com/yourusername/bersec-chronicles" target="_blank">Explore Repositories</a></p>
    </div>
    <footer>
        <p>&copy; 2025 BerSec Chronicles. Crafted with passion and code.</p>
    </footer>
</body>
</html>
