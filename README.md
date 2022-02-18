# Watches
A page where I made a list of my favorite watches including some vintage ones.
<!DOCTYPE html>
<html lang = "en">
    <head>
        <meta charset="UTF-8">
        <title>More Practice</title>
        <link rel="stylesheet" href = css/Watches.css>
        <script src = "js/date and slides.js"></script>
    </head>
    <body>
        <section class="title">
            <div>
        <h1>Different Types of Watches</h1>
        </div>
        </section>
   <section>
       <div>
        <h2>Field Watches</h2>
        </div>
        <div class="field">
        <nav>
        <a href = https://www.hamiltonwatch.com/en-us/h69439363-khaki-field-mechanical.html>Hamilton</a>
        <a href = https://www.macys.com/shop/product/seiko-mens-automatic-5-sports-green-nylon-strap-watch-43mm?ID=13059131&pla_country=US&CAGPSPN=pla&cm_mmc=Google_Watches_PLA-_-G_PLA_Watches_-_Seiko_Seiko-_-200646994774-_-pg1051703792_c_kclickid__kenshoo_clickid__KID_EMPTY_347019891_43037301986_200646994774_pla-545524644621_29665208897USA__c_KID_&trackingid=469x1051703792&m_sc=sem&m_sb=Google&m_tp=PLA&m_ac=Google_Watches_PLA&m_ag=Seiko&m_cn=G_PLA_Watches_-_Seiko&m_pi=go_cmp-347019891_adg-43037301986_ad-200646994774_pla-545524644621_dev-c_ext-_prd-29665208897USA&gclid=CjwKCAjw8KmLBhB8EiwAQbqNoF6dApNVQiiRD5Lx-XWrX92XmYal9DR_YqTEV0KMTxSPo0iH6XSl2RoC8XMQAvD_BwE>Seiko</a>
         </nav>
         </div>
         </section>
        <section>
            <div>
         <h2>Dive Watches</h2>
         </div>
         <div class="dive">
         <nav>
             <a href = https://en.yema.com/products/yema-superman-heritage-u-s-edition-ysup2019c41>Yema Superman</a>
             <a href = https://www.lorierwatches.com/products/neptune-siii-black-gilt>Lorier Neptune</a>
            </nav>
            </div>
            </section>
   <section>
        <div>
         <h2>Luxury</h2>
         </div>
         <div class="luxury">
         <nav>
             <a href = https://www.rolex.com/watches/day-date/m228239-0033.html>Rolex Day Date</a>
             <a href = https://www.oris.ch/en/watch/big-crown-pointer-date/01-754-7741-4065-07-5-20-63>Oris Big Crown</a>

         </nav>
         </div>
            </section>
         
         <section>
             <div>
         <h2>Favorite Watches</h2>
         </div>
         <div>
         <ul>
             <li>Yema Superman</li>
             <li>Rolex Day-Date</li>
             <li>Marathon</li>
             <li>Vostok</li>
         </ul>
         </div>
         </section>
         <section>
             <div>
             <h2>Unusual Watches</h2>
             </div>
             <div>
             <nav>
                 <a href = http://vostok.watch/product/russian-watch-vostok-prestige-retro-2403-583565/ >Vostok</a>
                 <a href = https://www.bulova.com/us/en/product/96A248.html?utm_medium=shopping&utm_campaign=bulova&byPassIntlRedirect=true&gclid=CjwKCAjw8KmLBhB8EiwAQbqNoCZ3zkQ91R1Xg6s5eWvG_Zlzo6prFKf2Yx9u-PNoDy5HUIa6YrWo9hoC2OAQAvD_BwE>Bulova</a>
             </nav>
             </div>
             <!--Picture Slideshow-->
            
            
             <section>
                 <div class="slideshow-container">
                     <p>Vintage Watches</p>
              
             <div class="slideshow fade">
              <div class="numbertext">1/3</div>
              <img src="images/vintage rolex.jpeg" style="width: 50%">
              <div class="text">Vintage Rolex 1</div>
              </div>

              <div class="slideshow fade">
              <div class="numbertext">2/3</div>
              <img src="images/vintage omega.jpeg" style="width: 50%">
              <div class="text">Vintage Omega 2</div>
              </div>

              <div class="slideshow fade">
              <div class="numbertext">3/3</div>
              <img src="images/vintage bulova.jpeg" style="width: 50%">
              <div class="text">Vintage Bulova</div>
              </div>
              <!--Buttons-->
              <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
              <a class="next" onclick="plusSlides(1)">&#10095;</a>
            </div>
           
            <br>

            <!--DotsandCircles-->
            <div style="text-align:center">
                <span class="dot" onclick="currentSlide(1)"></span>
                <span class="dot" onclick="currentSlide(2)"></span>
                <span class="dot" onclick="currentSlide(3)"></span>
              </div>

             </section>
         </section>
         <section id="date">
         <body onload="setDate()">
            <p> The current date is </p>
         </section>

    </body>
