<html>
    
<head>
    <title>Resume</title>
    <script src="salu.js"></script>
    <link rel="stylesheet" type="text/css" href="style.css">
    <style>
        html {
            font-size: 18px;
            font-family: Arial, Helvetica, sans-serif;
        }
        h1 {
            font-size: 1.6rem;
            color: rgb(177, 80, 80);
        }
        div {
            font-size: large;
            font-style: italic;
            color: #7462e0;
        }
        .major{
            color: rgb(239, 255, 15);
        }
        h2{
            font-size: 1.4rem;
            color: brown;
        }
        #social-media{
            background-color: rgba(219, 219, 0, 0.336);
                    
        }
        /*comentarios en CSS*/
        <!--Comentario en html--> 
        /*corchetes para los estilos de donde se encuentra el codigo*/
    </style>
    <style class="css">
        a:visited {
            color: rgb(3, 34, 3)
        }
        a:link {
            color:green;
        }
        a:hover {
            background-color: rgb(253, 230, 17);
        }
        @media screen and (max-width: 480px){
        #encabezado{
            height: auto;
        }
        #contenido{
            width: auto;
        }
        #barra_lateral{
            display:none;
        }
    }
    </style>
</head>

<body>
    <body style="background-color:#dfae66 ;">
    <h1><u>Name: Ann</u></h1><hr>
    <!-- about me -->
    <div>Email: andreina.pul@gmail.com</div>
    <div>Address: Hawaii </div><br>
   
    <a href="mailto:andre@gmail.com">clickable text</a> <br>
    <a href="https://docs.microsoft.com/">Microsoft Technical Documentation</a><br>
    <a href="https://mail.google.com/mail/u/0/h/17uoyqbt4g5gh/?&cs=b&pv=tl&v=b">Email us!</a> <br>
    <a href="https://mail.google.com/mail/u/0/#inbox?compose=GTvVlcSMSqTHZkbQfrBtlsTLHqFbLXtvlTzmPwdMzRTsMsRMgfGhTzMwRRzGjTrjxvnBvQFXtZZld">andreina.pul@gmail.com</a>

    
    <h2><u>Social media:</u></h2>
    <!-- social media -->
    <div id="social-media">
        <ol reversed>
            <li><a href="some url">Github</a></li> 
            <li><a href="https://www.youtube.com/watch?v=bJBv4NUv1bE&list=RDBU79EyMjIrU&index=29">LinkedIn</a></li>
            <li><a href="some url">Twitter</a></li>
        </ol>
    </div>
    

    <h2>Education:</h2>
    <!-- education -->
    <img src="https://www.nationalgeographic.com.es/medio/2022/11/06/representacion-artistica-del-dia-de-la-extincion-de-los-dinosaurios_8682f80b_800x800.jpg"
     width="1000"
     height="1000">

    <img src="descargas/IMG_20230315_103400.jpg"/>

    <img src="1.png" alt="Picture of an employee.">
    <h3>School name</h3>
    <div class="major">
        <h4 style="background-color:#e2812654 ;">Major
        <ul>
            <li>GPA: 4.0</li>
            <li>Years attended</li>
        </ul>
    </div>
        
    <h2>Experience:</h2>
    <!-- experience -->
    <ul>
        <li>Microsoft</li> 
        <li>Azure</li>
        <li>Python</li>
    </ul>
    <h3>Company name</h3>
    <h4>Title</h4>
    <h4>Dates</h4>
    <ul>
        <li>Cool accomplishment</li>
        <li>Cool accomplishment</li>
    </ul>

    <h3>Cool hackathon</h3>
    <h4>Project title</h4>
    <h4>Dates</h4>
       
    <ul>
        <li>Cool accomplishment</li>
        <li>Cool accomplishment</li>
    </ul>
    <audio controls>
        <source src="78 I Gotta Feeling-Black Eyer Peas.mp3" type="audio/mp3">
            
    </audio>
    <form>
        <input type="text" placeholder="Name">
        <input type="password" placeholder="password" required>
        <input type="number" placeholder="phone number">
        <input type="email" placeholder="email">
        <input type="time">
        <input type="button" value="boton">
        <input type="submit" value="enviar">
    </form>
    <footer>Contact us!</footer>
</body>



</html>
