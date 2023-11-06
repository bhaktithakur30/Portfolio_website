DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhakti - Developer Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        body {
            background-color: rgb(0,0,32);
            color: white;
            font-family:'poppins',sans-serif ;
        }

        nav{
            display: flex;
            justify-content: space-around;
            align-items: center;
            height: 80px;
            background-color: rgb(18,18,62);
        }
        nav ul{
            display: flex;
            justify-content: center;
        }
        nav ul li{
            list-style: none;
            margin: 0 23px;
        }

        nav ul li a{
            text-decoration: none;
            color: white;
        }
        nav ul li a:hover{
            color: rgb(153, 69, 232);
            font-size: 1.01rem;
        }

        main hr{
            border: 0;
            background: #7f78f7;
            height: 1.2px;
            margin: 60px 84px;
        }
        .left{
            font-size: 1.5rem;
        }

        .firstSection{
            display: flex;
            justify-content: space-around;
            align-items: center;
            margin: 80px 0;
        }

        .firstSection > div{
            width: 30%;
        }

        .leftSection{
            font-size: 2rem;    
        }
    
        .leftSection .buttons{
            padding: 50px 0;
        }
        .leftSection .btn{
            padding: 12px;
            background-color: #1e2167;
            color: white ;
            border: 2px solid white;
            border-radius: 6px;
            font-size: 20px;
            cursor: pointer;
        }

        .rightSection img{
            width: 80%;
            margin: 50px 0;
        }
        
        .purple{
            color: rgb(153, 69, 232);
        }
        .text-grey{
            color: gray;
        }

        #element{
            color: rgb(153, 69, 232);
        }
        .secondSection{
            max-width: 80vw;
            margin: auto;
            height: 80vh;
        }

        .secondSection .box{
            background: white;
            width: 80vw;
            height: 2px;
            margin: 56px 0;
            display: flex;
        }

        .secondSection .vertical{
            height: 93px;
            width: 1px;
            background-color: white;
            margin: 0 120px;
        }

        .image-top{
            width: 33px;
            position: relative;
            top: -32px;
            left: -9px;
        }

        .vertical-title{
            position: relative;
            top: 75px;
            width: 150px;
        }

        .vertical-desc{
            position: relative;
            top: 86px;
            color: gray;
            width: 150px;
            font-size: 9px;
        }
        footer{
            background-color: #0e0e1a;
        }

        .footer{
            display: flex;
            padding: 23px 122px;
            justify-content: space-evenly;
        }

        .footer ul{
            list-style: none;
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
           <div class="left">Bhakti's Portfolio</div>
           <div class="Right">
              <ul>
                <li><a href="/">Home</a></li>
                <li><a href="/">About</a></li>
                <li><a href="/">Services</a></li>
                <li><a href="/">Projects</a></li>
                <li><a href="/">Contact Me</a></li>
              </ul>
           </div>
        </nav>
    </header>

    <main>
        <section class="firstSection">
          <div class="leftSection">
               Hi, My name is <span class="purple">Bhakti</span>
               
               <div>and I am a passionate</div>
               <div>College Student</div>
               <span id="element"></span>
               <div class="buttons">
                <button class="btn">Downlode Resume</button>
                <button class="btn">Visit Github</button>
               </div>
          </div>
          <div class="rightSection">
        <img src="https://thumbs.dreamstime.com/z/businesswoman-sitting-office-vector-illustration-design-businesswoman-sitting-office-117844293.jpg" alt="">
          </div>
        </section>
<hr>
        <section class="secondSection">
            <span class="text-grey">What I have done so far</span>
            <h1>Work Experience</h1>

            <div class="box">
                <div class="vertical">
                    <img class="image-top" src="https://1000logos.net/wp-content/uploads/2020/08/Microsoft-PowerPoint-Logo.png"
                    alt="">
                    <div class="vertical-title">
                        Slide Presentation
                    </div>
                    <div class="vertical-desc">
                        Slide decks or digital documents that visually showcase professional work projects by individuals or agencies.Powerpoint is a tool to make a presentation more interactive and interesting.
                        
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="https://freelogopng.com/images/all_img/1656733637logo-canva-png.png"
                     alt="">
                    <div class="vertical-title">
                        Graphic Designer
                    </div>
                    <div class="vertical-desc">
                        One of the great things about networking as a graphic designer is that your work speaks for you. Canva is an online design tool that offers users the opportunity to create professional-looking posters,resumes,cards ,certificates and other media.
                        
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="https://4.bp.blogspot.com/-K3xPJlyU5mk/XGfNIFz6yyI/AAAAAAAAR80/A4JTnhu4ilUdnQ3TgtgE414oRw55owL8QCLcBGAs/s1600/HTML%2B5.png" alt="">
                    <div class="vertical-title">
                        HTML Developer 
                    </div>
                    <div class="vertical-desc">
                        HTML stands for Hyper Text Markup Language. HTML is the standard markup language for creating Web pages.HTML describes the structure of a Web page. HTML elements tell the brower how to display the content.
                        
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="https://th.bing.com/th/id/OIP.yUIb5S_kj98Eg5tT-Onx1AHaHa?pid=ImgDet&rs=1"
                    alt="">
                    <div class="vertical-title">
                        CSS Developer
                    </div>
                    <div class="vertical-desc">
                        CSS stands for Cascading Style Sheet .
                        CSS allows you to apply styles to web pages. More importantly, CSS enables you to do this independently of the HTML that makes up each web page. 
                        
                        
                    </div>
                </div>
                <div class="vertical">
                    <img class="image-top" src="https://logodownload.org/wp-content/uploads/2019/10/python-logo.png"
                     alt="">
                    <div class="vertical-title">
                        Python Developer
                    </div>
                    <div class="vertical-desc">
                        Python is an interpreted, object-oriented, high-level programming language with dynamic semantics. Python can be used on a server to create web applications.Python can be used alongside software to create workflows.
                    </div>
                </div>
                
                
            
        </section>
    
    </main>

    <footer>
       <div class="footer">
        <div class="footer-first">
            <h3>Bhakti's Developer Portfolio</h3>
        </div>
        <div class="footer-second">
            <ul>
                <li>c-language</li>
                <li>Python</li>
                <li>Java</li>
                <li>Javascript</li>
            </ul>
        </div>
        <div class="footer-third">
            <ul>
                <li>communication</li>
                <li>Leadership</li>
                <li>Presentation</li>
                <li>Time-management</li>
            </ul>
        </div>
        <div class="footer-fouth">
            <ul>
                <li>Sports</li>
                <li>Music</li>
                <li>Speaker</li>
                <li>Travel</li>
            </ul>
        </div>
    </div>
    <div class="footer-rights">
        Copyright © bhaktiportfolio.com | All rights reserved
    </div>
    </footer>
    
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>

    <script>
        var typed = new Typed('#element', {
          strings: ['Web Developer', 'Graphic Designer','Web Designer'],
          typeSpeed: 50,
        });
      </script>
    
</body>
</html>
