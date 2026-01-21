<!DOCTYPE html>
<html>
<head>
    <title>CSS Properties Demo</title>

    <style>
        /* Background Property */
        body {
            background-color: lightblue;
            background-image: linear-gradient(to right, #74ebd5, #9face6);
            background-repeat: no-repeat;
            background-size: cover;
            font-family: Arial, sans-serif; /* Font Property */
        }

        /* Box Model */
        .box {
            width: 350px;
            height: auto;
            background-color: white;

            padding: 20px;         /* inside space */
            margin: 80px auto;     /* outside space */
            border: 3px solid black;

            border-radius: 10px;
            box-shadow: 0px 0px 10px gray;
        }

        /* Text Property + Font Property */
        h1 {
            color: darkblue;
            text-align: center;
            text-transform: uppercase;
            font-size: 24px;
            letter-spacing: 2px;
        }

        p {
            color: black;
            text-align: justify;
            font-size: 16px;
            line-height: 25px;

            font-style: italic;     /* Font property */
            font-weight: bold;
        }

        /* Button styling (box model also) */
        button {
            background-color: darkblue;
            color: white;

            padding: 10px 20px;
            border: none;
            margin-top: 15px;

            font-size: 15px;
            cursor: pointer;
            border-radius: 6px;
        }

        button:hover {
            background-color: green;
        }
    </style>

</head>

<body>

    <div class="box">
        <h1>CSS Demo Page</h1>

        <p>
            This webpage uses background properties, text properties, font properties
            and box model in CSS. Box model includes margin, padding, border and content.
        </p>

        <center>
            <button>Click Me</button>
        </center>
    </div>

</body>
</html>
