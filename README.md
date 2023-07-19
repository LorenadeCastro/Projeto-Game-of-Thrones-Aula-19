<!DOCTYPE html>

<html>

<head>

    <meta charset="UTF-8">

    <title>Projeto HTML e CSS</title>

    <style>

        body {
            font-family: 'Cambria';
            background-color: black;
            background-image: url(GOT\ 4.jpg);
            background-position-y: 124%;
            background-repeat: no-repeat;
            background-size: 1600px, 10000px;
            margin: 0px auto;
            padding: 5px;
            width: 900px;
            
            }

            .container {
            
            margin: 0px auto;
            padding: 10px;
            width: 800px;
            text-align: center;
            }

            .menu {
                position: fixed; top: 10px; width: 73%;
            }
            
       .menu a {
        color: red;
        padding: 10px;
        text-align: center;
        }

        .menu ul {
            margin: 10px;
            padding: 20px;
            font-size: 35px;
            text-align: center;
        }
        
        .menu ul li {
            display:inline;
        }

        .menu ul li a {
            margin: 0 auto;
        }

        .menu li {
            margin-top: 30px;
            padding-right: 100px;
            display: inline-block;
            color: red;
            font-size: 22px;
            font-weight: bold;
            text-align: center;
        }

        .menu li:hover {
            background: white;
            color: black;
            -moz-box-shadow: 5 2px 2px 5 white;
            -webkit-box-shadow: 0 3px 10px 0 yellow;
            text-shadow: 0px 0px 5px black;
            text-align: center;
            }

        .menu a {
            color: white;
        }
            
        footer {
            text-align: center;
        }
       
        img {            
           -webkit-mask-image: linear-gradient(to bottom, transparent 5%, white 40%);
           background-image: url(Projeto\ Game\ of\ Thrones.jpg);
           position: relative;
           right: -20px;
           
            }

        figcaption {
            position: relative;
            right: -20px;
            font-size: 20px;
        }

        h1 {
            color: white;
            font-family: 'Cambria';
            font-size: 45px;
            margin-bottom: 50px;
            text-shadow: 0.1em 0.1em 0.3em white;
        }

        p {
            color: white;
            font-size: 24px;
            margin-bottom: 14px;
        }

        .button {
            display: inline-block;
            padding: 2px 2px;
            background-color: black;
            color: black;
            font-weight: bold;
            text-decoration: none;
            border-radius: 5px;
            font-size: 10px;
            transition: background-color 0.3s ease;
            margin-top: 13px;
            position: relative;
            left: -3%;
            
        }

       
       
    </style>

</head>

<body>

    <div class="menu">
        
    <nav>
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About Game of Thrones</a></li>
            <li><a href="#">Characters</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>
</div>
        <br>   

    <div class="container">

        <br>
        <br>
        <br>
        <br>
        <br>


<main>
    <h1>Bem-vindo(a) ao meu projeto</h1>
</main>

    <br>
    <img src="Projeto Game of Thrones.jpg" width="550" height="550" alt="Daenerys Targaryen, Arya Stark, Brienne de Tarth, Jhon Snow e Sor Jorah Mormont.">
    <figcaption src="Projeto Game of Thrones.jpg"><font color="white"><i>"Daenerys Targaryen, Arya Stark, Brienne de Tarth, Jhon Snow e Sor Jorah Mormont.</i></font></figcaption>
    <br>
    
    <br>
    <br>

    <p>Clique no botão abaixo para conhecer os personagens em destaque:</p>
    <a href="#" class="button"><img src="GOT 6.jpg" width="90" height="80" alt="GOT 6.jpg"></a>
    
    <br>
    <br>
    <br>
    </div>

    <footer>
        <p><i>&copy; 2023 My website. All rights reserved.</i></p>
    </footer>
</body>
</html>

