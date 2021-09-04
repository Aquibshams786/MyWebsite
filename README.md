<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Aquib Shams</title>
    <link rel="stylesheet" href="css/style.css">
    <link rel="stylesheet" media="screen and (max-width:1232px)" href="css/phone.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Comfortaa&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=Nova+Flat&display=swap" rel="stylesheet">
</head>

<body>
    <nav id="navbar">
        <div id="logo">
            <img src="logo.jpeg" alt="Aquib.com">
        </div>
        <ul>
            <li class="item"><a href="#home">Home</a></li>
            <li class="item"><a href="#about-container">About</a></li>
            <li class="item"><a href="#services-container">Services</a></li>
            <li class="item"><a href="#client-section">Clients</a></li>
            <li class="item"><a href="#contact">Contact</a></li>
        </ul>
        
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome to Shams's World!</h1>
        <span class="abc">Hello! I am Aquib.</span>
            <span class="abc">I am offering bachelor of technology in 
                Heritage Institute of Technology, Kolkata. </span>
        <span class="abc1">Now, I am a full stack web developer
                 and web designer.</span>
        <button onclick="document.getElementById('btn').innerHTML='Under Development'" id="btn">SEE MY PORTFOLIO</button>
    </section>
    <secton id="about-container">
         <div id="pp">
             <img src="css/pp.jpeg" alt="">
         </div>
             
             <div id="about">
                <h1 class="h-primary1">
                    About Me
                </h1>
                <h3 id="about1">
                 I am a student of Heritage Institute of technology , Kolkata. I am pursuing bachelor of technology. I have started coding two years before, from my 
                 first code on codechef. I have 3 star on codechef and I am trying to get better.
                 Apart from competitive coding i am full stack web web developer. I have knowledge of many
                 languages you may witness below.
                </h3>
                 
             </div>
    </secton>
    <section id="services-container">
        <h1 class="h-primary1">SERVICES I OFFER</h1>
        <div id="services">
            <div class="box">
                <img src="css/web.jpg" alt="">
                <h2 class="h-secondary">WEB DESIGN</h2>
                <P>I can design the website as my client wants to and I am preety sure they will be purely
                    satisfied with the web design.
                </P>
            </div>
            <div class="box">
                <img src="css/code.png" alt="">
                <h2 class="h-secondary">CODING</h2>
                <P>I am a coder as well. I am doing competitive programming on codechef,
                     you may check in my portfolio.</P>
            </div>
            <div class="box">
                <img src="css/clean1.jpg" alt="">
                <h2 class="h-secondary">PHOTOGRAPHY</h2>
               <P>If you have some photo to edit or capture then you are browsing a perfect man.</P>
            </div>
            <div class="box">
                <img src="css/clean.png" alt="">
                <h2 class="h-secondary">CLEAN CODE</h2>
                <P>With my 2 years of experience in coding i can debug any code, whether it is regarding web
                    develpment or software development.
                </P>
            </div>
        </div>
    </section>
    <section id="hireme">
        <div id="hire">
            <h1 class="h-primary2">DO YOU HAVE AN INTRESTING PROJECT?</h1>
            <button onclick="document.getElementById('btn2').innerHTML='aquibshams2@gmail.com'"  id="btn2">HIRE ME!</button>
        </div>
    </section>
    <secton id="client-section">
        <h1 class="h-primary1">CLIENTS</h1>
        <div class="clients">
            <div class="client-item">
                <img src="css/647px-Apple_logo_black.svg.png" alt="">
            </div>
            <div class="client-item">
                <img src="css/google.png" alt="">
            </div>
            <div class="client-item">
                <img src="css/ipl.png" alt="">
            </div>
            <div class="client-item">
                <img src="css/samsung.png" alt="">
            </div>
            <div class="client-item">
                <img src="css/wipro.png" alt="">
            </div>
        </div>
    </secton>
    <section id="contact">
        <h1 class="h-primary1">
            FEEDBACK
        </h1>
        <div class="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="email">Email:</label>
                    <input type="email" name="name" id="email" placeholder="Email">
                </div>
                <div class="form-group">
                    <label for="message">Message:</label>
                    <textarea name="message" id="message"></textarea>
                    
                </div>
                <button onclick="func()"  id="btn1">SUBMIT</button>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            copyright &copy;www.aquibshams.coolpage.biz. All rights reserved|
        </div>
    </footer>
</body>
<script>
    function func(){
        window.alert("Thanks for the Feedback");
    }
</script>
</html>
