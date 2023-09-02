/* # Netflix_Clone.github.io
Netflix is an American subscription video on-demand over-the-top streaming service owned and operated by Netflix, Inc. The service primarily distributes films and television series produced by the media company of the same name from various genres, and it is available internationally in multiple languages.
Html Code of this project */


<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Netflix Clone Webpage</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css" integrity="sha512-z3gLpd7yknf1YoNbCzqRKc4qyor8gaKU1qmn+CShxbuBusANI9QpRohGBreCFkKxLhei6S9CQXFEbbKuqLg0DA==" crossorigin="anonymous" referrerpolicy="no-referrer" />
    <link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,200;0,300;0,400;0,500;0,700;0,800;0,900;1,100&display=swap" rel="stylesheet">
</head>
<body>
  <header>
    <nav>
        <img src="images/logo.png" class="logo">
        <div>
          
            <button class="language-btn"><i class="fa-solid fa-globe"></i>English <img src="images/down-icon.png" alt=""></button>
            <button>Sign In</button>
        </div>
    </nav>

    <div class="content">
      <h1>Unlimited movies, TV shows and more</h1>
      <h3>Watch anywhere. Cancel anytime.</h3>
      <p>Ready to watch? Enter your email to create or restart your membership.</p>
      <div class="sign-in">
        <input type="email" placeholder="Email address" required>
        <button type="submit" class="language-btn">Get Started<i class="fa-solid fa-angle-right"></i></button>
      </div>
    </div>
  </header>
  
  
    <div class="feature">
      <div class="row">
        <div class="text">
          <h2>Enjoy on your TV</h2>
          <p>Watch on smart TVs, PlayStation, Xbox, Chromecast, Apple TV, Blu-ray players and more.</p>
        </div>
        <div class="img">
          <img src="images/tv.png" style="width: 110%;">
          <video muted loop autoplay >
            <source src="video1.m4v">
          </video>
        </div>
      </div>
      <div class="row">
        <div class="img">
          <img src="images/feature-2.png" >
        </div>
        <div class="text">
          <h2>Download your shows to watch offline</h2>
          <p>Save your favourites easily and always have something to watch.</p>
        </div>
      </div>
      <div class="row">
        <div class="text">
          <h2>Watch everywhere</h2>
          <p>Stream unlimited movies and TV shows on your phone, tablet, laptop, and TV.</p>
        </div>
        <div class="img">
          <img src="images/device-pile-in.png" style="width: 110%;">
          <video muted loop autoplay width="400" style="top: 40px; left: 20%;">
            <source src="video2.m4v">
          </video>
        </div>
      </div>
      <div class="row">
        <div class="img">
          <img src="images/feature-4.png" >
        </div>
        <div class="text">
          <h2>Create profiles for kids</h2>
          <p>Send children on adventures with their favourite characters in a space made just for them—free with your membership.</p>
        </div>
      </div>
    </div>
  
    <div class="faq">
      <h2>Frequently Asked Questions</h2>
      <ul class="accordion">
        <li>
          <input type="radio" name="accordion" id="first">
          <label for="first">What is Netflix?</label>
          <div class="content-accordion">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid ad quidem nulla, distinctio cum reiciendis corporis labore blanditiis officiis harum repudiandae nesciunt voluptatem totam quod libero aperiam ducimus reprehenderit possimus omnis quibusdam dolorum sequi! Vel nobis reiciendis fugiat labore libero.</p>
          </div>
        </li>
        <li>
          <input type="radio" name="accordion" id="Second">
          <label for="Second">How much the Netflix cost?</label>
          <div class="content-accordion">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid ad quidem nulla, distinctio cum reiciendis corporis labore blanditiis officiis harum repudiandae nesciunt voluptatem totam quod libero aperiam ducimus reprehenderit possimus omnis quibusdam dolorum sequi! Vel nobis reiciendis fugiat labore libero.</p>
          </div>
        </li>
        <li>
          <input type="radio" name="accordion" id="third">
          <label for="third">Where can i watch?</label>
          <div class="content-accordion">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid ad quidem nulla, distinctio cum reiciendis corporis labore blanditiis officiis harum repudiandae nesciunt voluptatem totam quod libero aperiam ducimus reprehenderit possimus omnis quibusdam dolorum sequi! Vel nobis reiciendis fugiat labore libero.</p>
          </li>
        </li>
        <li>
          <input type="radio" name="accordion" id="fifth">
          <label for="fifth">How do i cancel?</label>
          <div class="content-accordion">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Nulla reiciendis, quod eos dolore vitae cumque possimus ea distinctio maxime quidem, voluptatum incidunt harum rem atque omnis consectetur culpa similique iusto cupiditate. Nihil unde, veritatis fuga est officia iusto numquam eum ducimus dolor omnis error blanditiis, sunt quod culpa autem exercitationem reprehenderit, minima quos enim. Vero corrupti repellendus reiciendis! Aspernatur vitae architecto, perferendis et est vel laborum a sequi unde labore repudiandae voluptatibus quo ex soluta ut minima eum veniam earum tenetur quasi molestiae necessitatibus? Nisi odio magnam alias mollitia beatae!.</p>
          </div>
        </li>
        <li>
          <input type="radio" name="accordion" id="sixth">
          <label for="sixth">What can i watch on Netflix?</label>
          <div class="content-accordion">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid ad quidem nulla, distinctio cum reiciendis corporis labore blanditiis officiis harum repudiandae nesciunt voluptatem totam quod libero aperiam ducimus reprehenderit possimus omnis quibusdam dolorum sequi! Vel nobis reiciendis fugiat labore libero.</p>
          </div>
        </li>
        <li>
          <input type="radio" name="accordion" id="fourth">
          <label for="fourth">Is Netflix good for kids?</label>
          <div class="content-accordion">
            <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Aliquid ad quidem nulla, distinctio cum reiciendis corporis labore blanditiis officiis harum repudiandae nesciunt voluptatem totam quod libero aperiam ducimus reprehenderit possimus omnis quibusdam dolorum sequi! Vel nobis reiciendis fugiat labore libero.</p>
          </div>
        </li>
      </ul>

      <small>Ready to watch? Enter your email to create or restart your membership.</small>
      <div class="sign-in">
        <input type="email" placeholder="Email address" required>
        <button type="submit" class="language-btn">Get Started<i class="fa-solid fa-angle-right"></i></button>
      </div>
    </div>

    <div class="footer">
      <h2>Questions? Call <a href="" style="text-decoration: underline; color: #b9b9b9;">000-800-919-1694</a></h2>

      <div class="row">
        <div class="col">
          <a href="#">FAQ</a>
          <a href="#">Media Center</a>
          <a href="#">Ways to Watch</a>
          <a href="#">Cookie Preferences</a>
          <a href="#">Speed Test</a>
        </div>
        <div class="col">
          <a href="#">Help Center</a>
          <a href="#">Investor Relations</a>
          <a href="#">Terms of Use</a>
          <a href="#">Corporate Information</a>
          <a href="#">Legal Notice</a>
        </div>
        <div class="col">
          <a href="#">Account</a>
          <a href="#">Jobs</a>
          <a href="#">Privacy</a>
          <a href="#">Contact Us</a>
          <a href="#">Only on Netflix</a>
        </div>
      </div>
      <button class="language-btn"><i class="fa-solid fa-globe"></i>English <img src="images/down-icon.png" alt=""></button>
      <p class="copyright">Netflix India</p>
    </div>
</body>
</html>

/*css file of this project*/

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
    list-style: none;
    scroll-behavior: smooth;
    font-family: 'Poppins', sans-serif;
}
body{
    background-color: #000;
    color: #fff;
}
header{
    width: 100%;
    height: 100vh;
    background-image: linear-gradient(rgba(0,0,0,0.7),rgba(0,0,0,0.7)),url(images/header-image.jpg);
    background-position: center;
    background-size: cover;
    position: relative;
    padding: 10px 8%;
}
nav{
    display: flex;
    justify-content: space-between;
    align-self: center;
    padding: 10px 0;
}
.logo{
    width: 150px;
    cursor: pointer;
}
nav button{
    border: 0;
    outline: 0;
    background: #db0001;
    color: #fff;
    padding: 7px 20px;
    font-size: 14px;
    border-radius: 4px;
    margin-left: 10px;
}
nav button i{
    margin-right: 8px;
}
.language-btn{
    display: inline-flex;
    align-items: center;
    background: transparent;
    border: 1px solid #fff;
    padding: 7px 10px;
}
.language-btn img{
    width: 10px;
    margin-left: 10px;
}
.content{
    margin: 20vh auto;
    width: 70%;
    text-align: center;
    display: flex;
    flex-direction: column;
    align-items: center;
}
.content h1{
    font-size: 3em;
    font-weight: 600;
    line-height: 70px;
    max-width: 800px;
    margin-top: 20px;
}
.content h3{
    margin-top: 20px;
    font-weight: 400;
}
.content p{
    margin-top: 30px;
    font-size: 20px;
    font-weight: 300;
}
.sign-in{
    /* border: 2px solid red; */
    display: flex;
    gap: 20px;
    width: 70%;
    margin-top: 20px;
}
.sign-in i{
    margin-left: 8px;
}
.sign-in input{
    flex-grow: 1;
    background-color: rgba(0,0,0,0.7);
    border: 1px solid #535251;
    padding: 10px 20px;
    border-radius: 5px;
    color: #fff;
}
.sign-in .language-btn{
    display: flex;
    align-items: center;
    font-size: 24px !important;
    border: 0;
    outline: 0;
    background: #db0001;
    color: #fff;
    padding: 7px 20px;
    border-radius: 5px;
}
.feature{
    padding: 50px 12%;
    font-size: 22px;
}
.row{
    display: flex;
    width: 100%;
    align-items: center;
    flex-wrap: wrap;
    padding: 50px 0px;
}
.text{
    flex-basis: 50%;
    margin-bottom: 20px;
}
.img{
    position: relative;
    flex-basis: 50%;
    margin-bottom:20px;
}
.img>video{
    position: absolute;
    top: 20%;
    left: 68px;
    z-index: -1;
}
.img video source{
    display: block;
    width: 90%;
    margin: auto;
}
.img{
    flex-basis: 50%;
    margin-bottom: 20px;
}
.img img{
    display: block;
    width: 90%;
    margin: auto;
}
.feature h2{
    font-size: 50px;
    font-weight: 600;
    margin-bottom: 20px;
}
.faq{
    padding: 10px 12%;
    text-align: center;
    font-size: 18px;
}
.faq h2{
    font-size: 40px;
    font-weight: 600;
}
.accordion{
    margin: 60px auto;
    width: 100%;
    max-width: 750px;
}
.accordion li{
    width: 100%;
    padding: 5px;
}
.accordion li label{
    display: flex;
    align-items: center;
    padding: 20px;
    font-size: 18px;
    font-weight: 500;
    background-color: #303030;
    margin-bottom: 2px;
    cursor: pointer;
    position: relative;
}
label::after{
    content: '+';
    position: absolute;
    right: 20px;
    font-size: 34px;
    transition: transform 0.5s;
}
input[type="radio"]{
    display: none;
}
.accordion .content-accordion{
    background-color: #303030;
    text-align: left;
    padding: 0 20px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.5s , max-padding 0.5s;
}
.accordion input[type="radio"]:checked + label + .content-accordion{
    max-height: 600px;
    padding: 30px 20px;
}
.accordion input[type="radio"]:checked + label::after{
    transform: rotate(135deg);
}
.faq{
    padding: 50px 15% 10px;
    border-top: 6px solid #303030;
}
.faq .sign-in{
    max-width: 600px;
    margin: 20px auto 60px;
}
.feq small{
    font-size: 13px;
}
.footer{
    padding: 50px 15% 10px;
    border-top: 6px solid #303030;
    color: #777;
}
.footer h2{
    font-size: 16px;
    font-weight: 300;
    margin-bottom: 30px;
    font-weight: 500;
}
.footer .col{
    flex-basis: 25%;
    flex-grow: 1;
    margin-bottom: 20px;
}
.footer .col a{
    display: block;
    text-decoration: underline;
    color: #bab9b9;
    font-size: 14px;
    margin-bottom: 10px;
    font-weight: 500;
}
.footer .row{
    align-items: flex-start;
    padding: 10px 0;
}
.footer .language-btn{
    color: #fff;
}
.footer .language-btn i{
    margin-right: 8px;
}
.copyright{
    font-size: 14px;
    margin-top: 20px;
    margin-bottom: 10px;
}

