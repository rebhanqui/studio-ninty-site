<!doctype html>
<html>

<head>
  <meta charset="utf-8">
  <title>Home</title>
  <style>
    body {
      /*change measurements as you go through 
      html course and eventually put CSS on external 
      file or build it as you go before connecting it*/
      margin-left: 10%;
      margin-right: 10%;
    }
/* Double check why alignment is off
    .intro-area {
      display: flex;
    }

    .about-area {
      display: flex;
    }

    .portfolio {
      display: flex;
    }

    .newsletter-area {
      display: flex;
    }*/

  </style>
</head>
<header></header>
<nav class="navi">
  <ul>
    <li><a href="#introduction">Home</a></li>
    <li><a href="#about-section">About</a></li>
    <li><a href="#portfolio-section">Portfolio</a></li>
    <li><a href="#newsletter-section">Newsletter</a></li>
    <!--add contact form somewhere before footer-->
  </ul>
</nav>
</body>
<!-- <div class="intro-area"> </div>-->
  <h1 id="#introduction">Lorem ipsum dolor sit.</h1>
  <main>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Quisque non tortor ligula. Maecenas fringilla pulvinar
      lorem. Mauris vel velit massa. Aenean id orci molestie, vehicula enim sed, venenatis velit. Etiam vulputate est
      ultrices elementum ultricies. Praesent sed tellus sollicitudin, bibendum nisl a, varius lacus. Mauris gravida
      justo
      felis, nec ultrices sapien venenatis a.</p>

<!--<div class="about-area"> </div>-->
  <h2 id="#about-section">Lorem ipsum dolor sit.</h2>
  <img
    src="C://Users/Rebekah Quinn/Documents/Studio Ninty/Studio Ninty Online/Images/photo-1509395062183-67c5ad6faff9.jpg"
    alt="image of phone with text saying: i deisng and develop experiences that make peoples lives simple" width="404px"
    height="404px" ;>
  <p>Curabitur rutrum dui quis mauris laoreet malesuada. In a enim erat. Fusce
    laoreet, tortor sit amet aliquam finibus, tellus purus mollis justo, in posuere sapien metus at massa. Nullam
    malesuada arcu consequat, aliquet sapien nec, interdum lectus. Duis imperdiet est in euismod aliquet.</p>

<!--<div class="portfolio-area"></div>-->
  <h3 id="portfolio-section">Lorem ipsum dolor sit.</h3>
  <img
    src="C://Users/Rebekah Quinn/Documents/Studio Ninty/Studio Ninty Online/Images/laika-notebooks-l24Db2ApdFM-unsplash.jpg"
    alt="image of files symbolizing portfolios" width="404px" height="404px" ;>
  <p>Ut a gravida
    purus, sed molestie lectus. Morbi gravida bibendum massa sed facilisis. Nulla tempor, sapien vel auctor blandit,
    ipsum libero ultricies ante, consectetur vulputate nunc enim eget risus. Aliquam at molestie erat.
  </p>

<!--<div class="newsletter-area"></div>-->
  <h4 id="newsletter-section">Lorem ipsum dolor sit.</h4>
  <img
    src="C://Users/Rebekah Quinn/Documents/Studio Ninty/Studio Ninty Online/Images/erica-steeves-G_lwAp0TF38-unsplash.jpg"
    alt="image of a letter" width="404px" height="404px" ;>
  <p>Duis imperdiet est in euismod aliquet. Ut a gravida purus, sed molestie lectus. Morbi gravida bibendum massa sed
    facilisis.</p>
  <form action="/signup-to-newsletter">
    <!--add link to page and figure out how to store emails later-->
    <input type="text" placeholder="Your E-Mail Address">
    <label for="newsletter-subscription-type">
      <input type="radio" name="follow-us" checked value="follower">Follow Our Projects
    </label>
    <label for="newsletter-subscription-type">
      <input type="radio" name="services" value="service-interest">Request Our Services
    </label>
    <label for="newsletter-subscription-type">
      <input type="radio" name="other-reasons" value="other">Other
    </label>
    <button type="submit">Subscribe</button>
    <p>
      <!--GDPR T&C's etc here-->
      <label for="agreement-of-tcs-gdpr">
        <input type="checkbox" required name="tcs-gdpr-yes"> Agree to <a href="#">T&Cs</a>
        <!--get t&cs/gdpr for this link above-->
      </label>Ut a gravida purus, sed molestie lectus.</p>

</form>
</main>
<footer>

</footer>

</html>
