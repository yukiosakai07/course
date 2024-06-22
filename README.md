<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Google</title>
    <style>   
        a{
        display: block;
        margin-left: 93%;
        }
        img{
            display: block;
            position: absolute;
            margin-left: 33%;
            margin-top: 2%;
            width: 400px;
        }
        form{
            display: flex;
            position:absolute;
            margin-top: 200px;
            margin-left:30% ;
        }
        .text-area{
            font-size: medium;
            display: block;
            width:470px;
            height: 40px;
            border-radius: 20px;
            border: 2px black solid;
            }
        .submit-1, .button-2{
            background-color: white;
            display: flex;
            position: absolute;
            width: 120px;
            height: 35px;
            border-radius: 6px 6px 6px;
            border-color: whitesmoke;
            font-size: 15px;
            font-family: sans-serif;
        }
        .submit-1{
            margin-top: 80px;
            margin-left: 110px;
        }
        .button-2{
            margin-top: 80px;
            margin-left: 250px;
        }
        .text-area:hover,.submit-1:hover,.button-2:hover {
            cursor: pointer;
            background-color: whitesmoke;
            box-shadow: rgba(0, 0, 0, 0.24) 3px 3px 8px;
        }
    </style>
</head>
<body>
    <header>
        <div>
            <a  href="#">click me</a>
        </div>
    </header>
    <nav>
        <div>
            <img src="google.jpg">
        </div>
        <form action="https://google.com/search">
                <input class="text-area" type="text" name="q">
                <input class="submit-1" type="submit" value="Google Search">
                <input class="button-2" type="button" action="https://doodles.google/" value="I'm feeling lucky">
        </form>
    </nav>
    
</body>
</html>