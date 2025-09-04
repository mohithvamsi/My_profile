<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: #022;
            padding:10%;
        }
        .b-zero{
            padding:10%;
            height:800px;
            width: 800px;
            place-self: center;
            background: linear-gradient(45deg ,lightgreen ,rgb(13, 2, 138),red,black);
            animation: clock 4s infinite;
            opacity: 1;
            border-radius: 10%;
            z-index: 0;
        }
        .b-one{
            padding: 15%;
            height:80%;
            width: 80%;
            background-color: white;
            background-image: url(https://imgs.search.brave.com/V5RTYKqXj9P8ZlSPAci5iHSeSwMbIVhSdP33NMm6Es8/rs:fit:500:0:1:0/g:ce/aHR0cHM6Ly9tZWRp/YS5nZXR0eWltYWdl/cy5jb20vaWQvMjIy/ODg2NjAwMS92ZWN0/b3IvdGVhY2hlcnMt/ZGF5LWNhcmQtYmFj/a2dyb3VuZC5qcGc_/cz02MTJ4NjEyJnc9/MCZrPTIwJmM9TElC/d1NiR0kwc2JPMWp2/TnBYQm5zeVltMF9s/RjYzRkZwQ1hGQ0U1/amZuYz0);
            background-repeat: no-repeat;
            background-size: cover;
            animation: anti-clock 4s  infinite;
            border-radius: 10%;
            opacity: 1;
            z-index: 1;
        }
                @keyframes clock {
            0%{
                transform: rotate(0deg);
                border-radius: 10%;
                background: linear-gradient(45deg ,lightgreen ,rgb(13, 2, 138),red,black);
                opacity: 0.7;

            }
            50%{
                transform: rotate(180deg);
                border-radius: 50%;
                background: linear-gradient(45deg ,lightgreen ,rgb(221, 69, 4),rgb(16, 94, 221),black);
                opacity: 0.5;

            }
            100%{
                transform: rotate(360deg);
                border-radius: 10%;
                background: linear-gradient(45deg ,lightgreen ,rgb(13, 2, 138),red,black);
                opacity: 0.7;

            }
        }
        @keyframes anti-clock {
            0%{
                transform: rotate(0deg);
                border-radius:10% ;
                border-top-left-radius: 20%;
                opacity: 1;
            }
            50%{
                transform: rotate(-180deg);
                border-radius: 40%;
                border-top-left-radius: 10%;
                opacity: 1;
            }
            100%{
                transform: rotate(-360deg);
                border-radius: 10%;
                border-top-left-radius: 20%;
                opacity:1;
            }
        }
        

    </style>
</head>
<body>
    <div class="b-zero">
        <div class="b-one" style="opacity: 1;">



       </div>
    </div>
</body>
</html>
