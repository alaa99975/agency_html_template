#  html template - Creative Digital Agency

by Alaa mohammed Ali - king khaled university

A very professional and highly customizable template with lots of custom pages and useful features fora Creative Marketing Agency
![](https://github.com/KaushikShivam/neoDigital/raw/master/screenshot.png)


# Description

This template uses the following:
* Modern CSS
* BEM Methodology
* Custom 4 column grid
* SASS

# Installation

1. Clone the project to your local directory

*** https://github.com/alaa99975/agency_html_template
 
1. The project uses NPM for managing dependencies. Run npm install to install all the required dependencies
1. Run the watch script to view live changes to your CSS
1. Open the index.html file in your browser to view the website in all its glory (Live-server is recommended to view live changes automatically)

### ** Some examples of using your code**
`<!DOCTYPE html>
<html lang="en">

  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link href="https://fonts.googleapis.com/css?family=Lato:100,300,400,700,900" rel="stylesheet">

    <link rel="stylesheet" href="css/style.css">
    <title>NeoDigital</title>
  </head>

  <body>
    <header class="header">
      <nav class="nav">
        <a class="nav__logo" href="#"><img src="img/logo.png" alt="logo"></a>
        <ul class="nav__list">
          <li class="nav__item"><a href="#">Services</a></li>
          <li class="nav__item"><a href="#">Welcome</a></li>
          <li class="nav__item"><a href="#">About</a></li>
          <li class="nav__item"><a href="#">Get in touch</a></li>
        </ul>
      </nav>

      <div class="header__content">
        <div class="header__pagn">
          <ul>
            <li>&nbsp;</li>
            <li>&nbsp;</li>
            <li>&nbsp;</li>
          </ul>
        </div>

        <h1 class="heading-primary">Creative Digital Agency</h1>
        <p class="paragraph paragraph--animate">Neque porro <span>quisquam</span> est qui dolorem ipsum quia dolor
          sit amet,
          <span>consectetur</span>,adipisci velit.</p>
        <a href="#" class="btn btn--full btn--animate">Find out more</a>
      </div>
      <img src="img/arow-down.png" alt="Down arrow" class="header__arrow">
    </header>

    <main>

      <section class="section-visit">
        <div class="row">
          <div class="col-1-of-2 visit-box">
            <h3 class="heading-tertiary">Clean Design</h3>
            <p class="paragraph">
              It is a long <span>established</span> fact that a reader will  be distracted by the readable
              content
              of a  page when <span>looking</span> at its layout.
            </p>
            <a href="#" class="btn btn--full">Visit website</a>
          </div>
          <div class="col-1-of-2 visit-box">
            <h3 class="heading-tertiary">Design</h3>
            <p class="paragraph">
              It is a long established <span>fact that</span> a reader will  be distracted by the readable
              content
              of a <span>page when</span> looking at its layout.
            </p>
            <a href="#" class="btn btn--full">Contact us</a>
          </div>
        </div>
      </section>

      <section class="section-services">
        <div class="section-services__content">
          <h2 class="heading-secondary">Our Services</h2>
          <p class="paragraph">Neque porro <span>quisquam</span> est qui dolorem ipsum quia dolor
            sit amet,
            <span>consectetur</span>,adipisci velit.</p>
          <div class="service-box">
            <ul class="service-box__list">
              <li class="service-box__item"><a href="#">UI/UX</a></li>
              <li class="service-box__item"><a href=#>Responsive Design</a></li>
              <li class="service-box__item"><a href=#>Development</a></li>
              <li class="service-box__item"><a href=#>Mobile Apps</a></li>
              <li class="service-box__item"><a href=#>Commerce</a></li>
            </ul>
            <div class="service-box__img-box">
              <div class="row">
                <div class="col-1-of-2">
                  <img src="img/service.png" alt="Service box">
                </div>
                <div class="col-1-of-2">
                  <h3 class="heading-tertiary heading-tertiary--left">We made UI / UX Design</h3>
                  <p class="paragraph paragraph--left">Neque porro quisquam est qui dolorem ipsum quia
                    dolor sit
                    amet, consectetur, adipisci velit. <span>Neque porro</span> quisquam est qui dolorem
                    ipsum quia
                    dolor sit amet, consectetur, adipisci velit...</p>
                  <p class="paragraph paragraph--left">
                    Neque porro <span>quisquam est</span> qui dolorem ipsum quia dolor sit amet,
                    consectetur,
                    adipisci velit.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <section class="section-clients">
        <img class="section-clients__img" src="img/Nikon_LogoPNG-0.png" alt="Nikon">
        <img class="section-clients__img" src="img/envato-logo.png" alt="Envato">
        <img class="section-clients__img" src="img/Citibank-logo.png" alt="Citibank">
        <img class="section-clients__img" src="img/Activision_logo.png" alt="Activision">
      </section>

  

   

    </main>

  
  </body>

</html>`
