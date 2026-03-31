# netflix-clone
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            margin: 0%;
            background-color: black;
        }
        .logo{
            height: 80px;
            width: 150px;
            position: absolute;
            padding-left: 5px;
            padding-top: 2px;
        }
        .a{
            position: absolute;
            top: 40px;
            right: 40px;
        }
        header{
            height: 100px;
            width: 100%;
            border: solid 1px black;
            background-color: black;
        }
        section{
        height: 900px;
        width: 100%;
        border: solid 2px black;
        background-image: url("https://animeargentina.net/wp-content/uploads/2022/03/Netflix-Main.jpg"); 
        background-repeat: no-repeat;
        background-size: cover;
         } 
        h1{
        color: white;
        font-size: 80px;
        font-style: oblique;
        padding-top: 100px;
        }
        h4{
            color: white;
            font-style:normal;
            font-size: larger;
        }
        .b{
            color: white;
            height: 30px;
            width: 80px;
            background-color: red;
        }
        .c{
             color: white;
             font-style:oblique;
            height: 50px;
            width: 150px;
            background-color: red;
        }
        h2,h3,p{
            color: white;
        }
        .d{
            height: 400px;
            width: 100%;
            background-color: black;
            justify-content:space-between;
        }
        .e{
            height: 400px;
            width: 100%;
        }
        span{
            display: flex;
        }
        .n{
        color: white;
        display: flex;
        justify-content:space-between;
       }
        .p{
        color:white;
       }
       .q{
        color:white;
        font-size: 50px;
        border-width:100%;
        padding-left: 130px;
       }
        h6{
        color: white;
        font-size: 20px;
       }
       .o{
        display: flex;
        justify-content: space-evenly;
        text-decoration: none;
       }
       .r{
        color: white;
         margin-left: 150px;
         font-size: 20px;
       }
       a{
        color: white;
        font-size: 18px;
       }
       .abc{
        width: 250px;
       }
    </style>
</head>
<body>
    <header>
        <img class="logo" src="https://images.ctfassets.net/y2ske730sjqp/1aONibCke6niZhgPxuiilC/2c401b05a07288746ddf3bd3943fbc76/BrandAssets_Logos_01-Wordmark.jpg?w=940">
        <nav class="a">
            <select name="English">
                <optgroup>
                    <option>English</option>
                    <option>Hindi</option>
                </optgroup>
            </select>
            <button class="b">Sign up</button>
        </nav>
    </header>
    <section>
        <center>
            <h1>Unlimited movies,shows,and more</h1>
            <h4>Start at 149/-.Cancel at any time.</h4>
            <h4>Ready to watch? Enter your email to create or restart your membership.</h4>
            <input type="email" placeholder="Email address"  style="width:300px ; height: 50px;background-color: black;color: white;">
            <button class="c">Get Started ></button>
        </center>    
    </section>
    <article class="d">
        <h2 style="color: white;font-size: 50px;">Trending Now</h2>
        <img src="https://images.atomtickets.com/image/upload/w_520,h_780,q_auto/v1/ingestion-images-archive-prod/archive/33542d7b498c.jpg" height="300px" width="290px">
        <img src="https://m.media-amazon.com/images/M/MV5BMmU1NWM4ZTAtZGM0Ny00NTVmLTgxZGItZWUxZTk4Yjg0NWEyXkEyXkFqcGc@._V1_FMjpg_UX1000_.jpg" height="300px" width="290px">
        <img src="https://image.tmdb.org/t/p/original/rJ3SqkaVwovBHSCsOpUno2ctBo9.jpg" height="300px" width="290px">
        <img src="https://images.herzindagi.info/her-zindagi-english/images/2025/12/10/template/image/tere-ishq-mein-1765351449533.jpg" height="300px" width="290px">
        <img src="https://assetscdn1.paytm.com/images/cinema/Anaganaga-Oka-Raju-gallery--Gallery-ceebe330-c6c4-11ef-b2c7-1551bf0a8dd7.jpg" height="300px" width="290px">
    </article>
    <h2 style="color: white; font-size: 50px;">More reasons to join</h2>
       <article class="n">  
        <div class="abc">
            <h4>Enjoy on your TV</h4>
            <p class="p">Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
            <img src="https://tse3.mm.bing.net/th/id/OIP.rT1yzSKUipPjejQUIgYjuwHaEJ?pid=Api&P=0&h=180" height="75px" width="100px">
        </div>
        <div class="abc">
            <h4>Download your shows to watch offline</h4>
            <p class="p">Save your favourites easily and always have something to watch.</p>
            <img src="data:image/svg+xml;utf8,%3Csvg%20width%3D%22200%22%20height%3D%22200%22%20viewBox%3D%220%200%20200%20200%22%20xmlns%3D%22http%3A%2F%2Fwww.w3.org%2F2000%2Fsvg%22%3E%0A%20%20%3C!--%20Black%20Background%20--%3E%0A%20%20%3Crect%20width%3D%22200%22%20height%3D%22200%22%20fill%3D%22black%22%3E%3C%2Frect%3E%0A%20%20%0A%20%20%3C!--%20White%20Circle%20--%3E%0A%20%20%3Ccircle%20cx%3D%22100%22%20cy%3D%22100%22%20r%3D%2270%22%20fill%3D%22white%22%3E%3C%2Fcircle%3E%0A%20%20%0A%20%20%3C!--%20Download%20Arrow%20(Black)%20--%3E%0A%20%20%3Cline%20x1%3D%22100%22%20y1%3D%2265%22%20x2%3D%22100%22%20y2%3D%22115%22%20stroke%3D%22black%22%20stroke-width%3D%2210%22%20stroke-linecap%3D%22round%22%3E%3C%2Fline%3E%0A%20%20%3Cpolygon%20points%3D%2275%2C105%20100%2C135%20125%2C105%22%20fill%3D%22black%22%3E%3C%2Fpolygon%3E%0A%20%20%0A%20%20%3C!--%20Base%20Line%20--%3E%0A%20%20%3Cline%20x1%3D%2270%22%20y1%3D%22150%22%20x2%3D%22130%22%20y2%3D%22150%22%20stroke%3D%22black%22%20stroke-width%3D%2210%22%20stroke-linecap%3D%22round%22%3E%3C%2Fline%3E%0A%3C%2Fsvg%3E" height="75px" width="100px">
        </div>
        <div class="abc">
            <h4>Watch everywhere</h4>
            <p class="p">Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
            <img src="https://tse3.mm.bing.net/th/id/OIP.wNJWpibt9d4Bh06RGZvkBgHaHX?pid=Api&P=0&h=180" height="75px" width="100px">
        </div>
        <div class="abc">
            <h4>Create profiles for kids</h4>
            <p class="p">Send kids on adventures with their favourite characters in a space made just for them — free with your membership.</p>
            <img src="https://tse3.mm.bing.net/th/id/OIP.YNYq-QyNUFRPSb4D0oVOCAHaHa?pid=Api&P=0&h=180" height="75px" width="100px">
        </div>
    </article>
    <h3 style="color: white;font-size:50px">Frequently asked questions</h3>
    <article class="q">
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">What is Netflix?</p>
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">How much does Netflix cost?</p>
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">Where can i watch?</p>
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">How do i cancel?</p>
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">What can i watch on Netflix?</p>
        <p style="background-color:rgb(71, 70, 70); height: 70px; width:85%;">Is Netfix good for kids?</p>
    </article>
    <center>
        <h6>Ready to watch? Enter your email to create or restart your membership.</h6>
         <input type="" placeholder="Email Address" required style="width:520px; height:50px; background-color:black; color:white; border-radius:5px;border-color: white;" >
            <button class="c">Get Started  ></button>
    </center><br><br>
    <p class="r">Questions? Call 000-800-919-1743</p><br><br>
    <article class="o">
    <div>
        <p><a href="">FAQ</a></p>
        <p><a href="">Investor Relations</a></p>
        <p><a href="">Privacy</a></p>
        <p><a href="">Speed Test</a></p>
    </div>
    <div>
        <p><a href="">Help Centre</a></p>
        <p><a href="">Jobs</a></p>
        <p><a href="">Cokkies Preferences</a></p>
        <p><a href="">Legal Notices</a></p>
    </div>
    <div>
        <p><a href="">Account</a></p>
        <p><a href="">Ways to Watch</a></p>
        <p><a href="">Corporate Information </a></p>
        <p><a href="">Only on Netflix</a></p>
    </div>
    <div>
        <p><a href="">Media Centre</a></p>
        <p><a href="">Terms of Use</a></p>
        <p><a href="">Contact us</a></p>
    </div>
    </article><br><br><br>
    <footer>
        <select class="LANG" style="background-color: black; height: 35px;width: 90px; border-radius:13px;color:white;margin-left:150px">
        <optgroup label="">
            <option value="">TELUGU</option>
            <option value="">HINDI</option>
            <option value="">ENGLISH</option>
        </optgroup>
        </select><br><br>
        <p class="r" style="margin-left: 150px;">Netfix India</p><br>
        <p class="r" style="text-decoration: none; margin-left:150px">This page is protected by Google reCAPTCHA to ensure you're not a bot. <a href="">Learn More</a></p>
    </footer>
</body>
</html>
