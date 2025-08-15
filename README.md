# vinay-developer-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Vinay - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100..900;1,100..900&display=swap" rel="stylesheet">

    <style>
        *{
            margin: 0;
            padding: 0;
        }
        body{
            background-color: rgb(17, 17, 35);
            color: white;
            font-family: "Roboto", sans-serif;
        }


        nav{
            display: flex;
            justify-content: space-around ;
            align-items: center;
            height: 80px;
            background-color: rgb(18, 17, 51);

        }
        nav ul{
            display: flex;
            justify-content: center;
        }
        nav ul li{
            list-style: none;
            margin: 0 24px;

        }
        nav ul li a{
            text-decoration: none;
            color: white;            

        }
        nav ul li a:hover{
            color: rgb(61, 133, 130);
            font-size: 1.02rem;
        }

        mian hr{
            border: 0;
            background: rgba(227, 225, 234, 0.301);
            height: 1.2px;
            margin: 60px 84px;
        }
        .left{
            font-size: 1.3rem;
        }
        .firstSection{
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin: 130px 0;
        }

        .firstSection > div{
            width: 30%;
            margin: auto;
        }
        .leftSection{
            font-size: 3rem;
            
        }
         .leftSection .btn{
            padding: 12px;
            background-color: rgb(52, 52, 114);
            color: white;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
            
        }
        .rightSection img{
            width: 70%;
            margin: 50px 0;

        }
        .purple{
            color: rgba(174, 6, 216, 0.465);
        }
        .text-grey{
            margin: 20px;
            color: gray;
        }
        #element{
            color: rgb(61, 133, 130);
            font-weight: bold;
        }
        .secondSection{
            max-width: auto;
            margin: auto;
            height: 80vh;
        }
        .secondSection h1{
            margin: 20px;
            font-size: 2.8rem;
        }

        .secondSection .box{
            background: white;
            width: 70vw;
            height: 3px;
            margin: 70px;
            display: flex;
        }

        .secondSection .vertical{
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 90px;
        }

        .image-top{
            width: 23px;
            position: relative;
            top: -32px;
            left: -9px;
        }
        .vertical-title{
            position: relative;
            top: 75px;
            width: 150px;
            font-size: 15px;
        }

        .vertical-desc{
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 10px;

        }
        footer{
            background-color: #1f1f4e;
        }
        .footer{
            display: flex;
            padding:  24px 123px;
            justify-content: space-evenly ;
        }

        .footer ul{
            list-style: none    ;
        }

        .footer > div{
            width: 223px;
        }

        footer .footer-rights{
            text-align: center;
            color: gray;
            padding: 12px 0;
        }

    </style> 
</head>
<body>
    <header>
        <nav>
            <div class="left">Vinay's Portfolio</div>
            <div class="'right">
                <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">service</a></li>
                <li><a href="/">Contact Me</a></li>
                </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class = "firstSection">
            <div class ="leftSection">
                Hey, My Name is <span class="purple">Vinay</span> 
                <div>and I am </div>
                  <span id="element"></span> 
                  <div class="button">
                    <button   class="btn">Download Resume</button>
                    <button   class="btn">Visit GitHub</button>
                  </div>
            </div>
            <div class="rightSection">
                <img src="devop.png" alt="">
            </div>
          
        </section>
        <hr>
        <section class="secondSection">
            <span class="text-grey">What I have done so far</span>
            <h1>Work Experience</h1>  
            <div class="box">
            <div class="vertical">
                <img class="image-top" src="html.png" alt="">
                <div class="vertical-title">
                    HTML Developer 
                </div>
                <div class="vertical-desc">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, pariatur blanditiis consequuntur sed vitae laborum facere doloremque harum, error quas et, minima quaerat reprehenderit expedita accusantium dicta porro. Blanditiis, natus!
                </div>    
            
            </div>
            <div class="vertical">
                <img class="image-top" src="nodejs.png" alt="">
                <div class="vertical-title">
                    Node.js Developer 
                </div>
                <div class="vertical-desc">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, pariatur blanditiis consequuntur sed vitae laborum facere doloremque harum, error quas et, minima quaerat reprehenderit expedita accusantium dicta porro. Blanditiis, natus!
                </div>    
    
            </div>
            <div class="vertical">
                <img class="image-top" src="python.png" alt="">
                <div class="vertical-title">
                    Python Developer 
                </div>
                <div class="vertical-desc">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, pariatur blanditiis consequuntur sed vitae laborum facere doloremque harum, error quas et, minima quaerat reprehenderit expedita accusantium dicta porro. Blanditiis, natus!
                </div>    
            
            </div>
            <div class="vertical">
                <img class="image-top" src="django.png" alt="">
                <div class="vertical-title">
                    Django Developer 
                </div>
                <div class="vertical-desc">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, pariatur blanditiis consequuntur sed vitae laborum facere doloremque harum, error quas et, minima quaerat reprehenderit expedita accusantium dicta porro. Blanditiis, natus!
                </div>    
            
            </div>
        
            <div class="vertical">
                <img class="image-top" src="kotlin.png" alt="">
                <div class="vertical-title">
                    Kotlin Developer
                </div>
                <div class="vertical-desc">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Mollitia, pariatur blanditiis consequuntur sed vitae laborum facere doloremque harum, error quas et, minima quaerat reprehenderit expedita accusantium dicta porro. Blanditiis, natus!
                </div>    
    
            </div>
        
            </div>           
            
        </section>
    </main>

    <footer>
        <div class="footer">
            <div class="footer-first">
                <h3>Vinay's Developer Portfolio</h3>
            </div>
            <div class="footer-second"></div>
            <ul>
                <li>Home</li>
                <li>About</li>
                <li>service</li>
                <li>Contact Me</li>
            </ul>
            <div class="footer-third">
                <ul>
                <li>Home</li>
                <li>About</li>
                <li>service</li>
                <li>Contact Me</li>
            </ul>
            </div>
            <div class="footer-fourth">
                <ul>
                <li>Home</li>
                <li>About</li>
                <li>service</li>
                <li>Contact Me</li>
            </ul>
            </div>
        </div>
        <div class="footer-rights">
                Copyright &#169; www.vinaysportfolio.com | All rights reserved 
        </div>
    </footer>
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
     <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#element', {
      strings: ['Web Developer', 'Video Editor', 'Content Creator'],
      typeSpeed: 50,
    });
  </script>
    
</body>
</html>
