# slack-clone

/*html*/

<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta http-equiv="X-UA-Compatible" content="ie=edge" />
    

    <!-- link the font awesome CDN -->
    <link
      href="https://use.fontawesome.com/releases/v5.0.1/css/all.css"
      rel="stylesheet" href="lab-css-flexbox-slack/starter_code/stylesheets/style.css"
    />

    <!-- link your styles -->
    <link rel="stylesheet" href="./stylesheets/style.css" />
    <title>Where work happens | Slack</title>
  </head>



  <!-- NAVEGATION SECTION -->

  <body>

    <header class="menu">
      
      <a href="#">

        <img id="logo" src="./images/slack-logo.png" alt="slack_logo" />

      </a>

      <a href="hamburguer">

        <img id="navicon" src="./images/hamburgo.png" alt="menu" />

      </a>

      <nav>

        <ul>

          <li>Why Slack?</li>
          <li>Pricing</li>
          <li>About Us</li>
          <li>Your Workspaces</li>

        </ul>

      </nav>

    </header>


    
<!-- PRESENTATION SECTION -->

     <header>
      
      <!-- <img id="talking" src="./images/home_talking.png" alt="home_work_happening" /> -->
      
        <h1>Where Work<br>Happens</h1>
        <p>
          When your team needs to kick off a project, hire a new employee, deploy
          some code, review a sales contract, finalize next year's budget, measure
          an A/B test, plan your next office opening, and more, Slack has you
          covered.
        </p>
        
        <form action="mailto:admin@example.com" enctype="text/plain" method="post">
          <p>E-mail address: <input name="E-mail" type="text" id="E-mail" size="40"></p>
      
      <button type="button" name="button">GET STARTED</button>
      
      <p>Already using Slack? <a href="#">Sign in</a></p>

    </header>

    <main>
      
      <div>

        <h2>You're in good company</h2>
        <p>
          Millions of people around the world have already made Slack the place
          where their work happens.
        </p>


        <button>DISCOVER WHY</button>

          <img src="./images/airbnb-logo.png" alt="" />
          <img src="./images/capital-one-logo.png" alt="" />
          <img src="./images/harvard-logo.png" alt="" />
          <img src="./images/los-angeles-times-logo.png" alt="" />
          <img src="./images/oracle-logo.png" alt="" />
          <img src="./images/ticketmaster-logo.png" alt="" />

      </div>

      <div>
        
        <p>Try it for free</p>
        <p>Already using Slack? <a href="">Sign in</a></p>
        
        <button type="button" name="button">GET STARTED</button>
      
      </div>
    
    </main>
    
    <footer>
      
      <div>
        
        <img src="./images/iso-slack.png" alt="" />
        
          <ul>
            
            <li>COMPANY</li>
            <li>About Us</li>
            <li>Careers</li>
            <li>Blog</li>
            <li>Press</li>
            <li>Brand Guidelines</li>

          </ul>

          <ul>

            <li>PRODUCT</li>
            <li>Why Slack?</li>
            <li>Enterprise</li>
            <li>Customer Stories</li>
            <li>Pricing</li>
            <li>Security</li>

          </ul>

          <ul>

            <li>RESOURCES</li>
            <li>Download</li>
            <li>Help Center</li>
            <li>Guides</li>
            <li>Events</li>
            <li>App Directory</li>
            <li>API</li>

          </ul>

          <ul>

            <li>EXTRAS</li>
            <li>Podcast</li>
            <li>Slack Shop</li>
            <li>Slack at Work</li>
            <li>Slack Fund</li>

          </ul>

      </div>

      <div>

        <ul>

          <li>Status</li>
          <li>Privacy & Terms</li>
          <li>Contact Us</li>

        </ul>

        <div>

          <img src="./images/us-flag.png" alt="" />

          <span>English (US)</span>

          <i class="fas fa-chevron-down"></i>
          <i class="fab fa-twitter"></i>
          <i class="fab fa-facebook-f"></i>
          <i class="fab fa-youtube"></i>

        </div>

      </div>

    </footer>

  </body>

</html>





/*css*/

/*
background-grey: #F4F3F4;
button-purple: #192592
main-titles dark-grey: #2C303F;
paragraph grey: #5b5e6d;
nav grey: #5b5e6d;
*/



/* EXTRA SMALL SCREEN */

/*@media (min-width: 768px) {
    nav .row .img {
        padding: 15px;
    }

    .row .menu. div {
        dispaly: flex;
        align-content: space-between;
    }

    nav .div {
        display: flex;
        align-content: space-between
    }

    nav {
        border-bottom: 1px, grey;
    }
}

*/

/*
.menu {
    display: flex;
    justify-content: space-between;
}

.menu #logo {
    width: 100px;
}

#navicon {
    width: 25px;
    padding: 10px;
    
}
*/




.menu {
    z-index: 9999;
    display: flex;
    align-items: center;
    justify-content: space-between;
    width: 100%;
    padding: 10px 20px;
    color: white;
    border-bottom: 1px solid grey;
    transition: all .5s;
}

.menu.solid {
    background-color: white;
    color: black;
}

.menu nav {
    display: none;
}

.menu .logo {
    width: 15px;
    filter: brightness(50);
}

.menu.solid .logo {
    filter: brightness(1);
}

.menu .navicon {
    width: 50px;
}

.menu nav ul {
    display: flex;
    list-style: none;
    margin-top: 15px;
}

.menu li {
    margin: 0 10px
}



/* PRESENTATION SECTION */

header h1 {
    font-size: 70px;
}

br {
    font-size: 70px;
}

header p {
    font-size: 40px;
    color: #5b5e6d;
    width: 80%;
    text-align: center;
}

a[href^="mailto:"]

{ 
  font-family: sans-serif;
  color: black;
  font-size: 11px;
}

button {
    display: flex;
    background-color: rgb(3, 102, 214);
    color: white;
    border: none;
    width: 80%;
    justify-content: center;
    height: 40px;
    align-items: center;
}
