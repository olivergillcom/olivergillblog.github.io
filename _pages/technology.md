---
title: Technology Timeline
subtitle: What I got, and when I got it
description: A Personal Site.
featured_image: /images/demo/demo-portrait.jpg
---

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <script>document.getElementsByTagName("html")[0].className += " js";</script>
  <link rel="stylesheet" href="/js/timeline/css/style.css">
<!-- fix for margins -->
<style>
  .single h1, .single h2, .single h3, .single h4, .single h5, .single h6, .single p, .single ul, .single ol{
    max-width: 100%;
  }
</style>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.1.1/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

<!-- test shit-->
<style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }
  
  .active, .collapsible:hover {
    background-color: #555;
  }
  
  .contentInfo {
    padding: 0 18px;
    max-height: 0;
    overflow: hidden;
    transition: max-height 0.2s ease-out;
    background-color: #f1f1f1;
  }
  </style>
</head>
<body>
  <div class="flex justify-between items-center">
    <a class="btn btn--subtle" data-toggle="collapse" data-target="#gaming-pc">Muh PC</a>
    <button type="button" class="btn btn-info" data-toggle="collapse" data-target="#gaming-pc">Buttan</button>

    <a class="btn btn--subtle">Muh Tablet</a>
<!--
    <a href="#" onclick="ToggleVisibility('gaming-pc'); return false;" class="btn btn--subtle gaming-pc-button">
      <div class="filter__img filter__img--green">
        <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
      </div>
    </a>
    <a href="#0" class="btn btn--subtle">
      <div class="filter__img filter__img--purple">
        <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
      </div>
    </a>
    <a href="#0" class="btn btn--subtle">
      <div class="filter__img filter__img--red">
        <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
      </div>
    </a>
-->  
  </div>

  <button class="btn btn-primary" type="button" data-toggle="collapse" data-target="#collapseExample" aria-expanded="false" aria-controls="collapseExample">Button
  </button>

<div class="collapse" id="collapseExample">
  <div class="card card-body">
    Anim pariatur cliche reprehenderit, enim eiusmod high life accusamus terry richardson ad squid. Nihil anim keffiyeh helvetica, craft beer labore wes anderson cred nesciunt sapiente ea proident.
  </div>
</div>


  <section class="cd-timeline js-cd-timeline" style="padding-left: 0px;padding-right: 0px;">
    <div class="container max-width-lg cd-timeline__container">
      <div class="collapse" id="collapseExample">
        <div class="cd-timeline__block">
          <div class="cd-timeline__img cd-timeline__img--green">
            <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
          </div> <!-- cd-timeline__img -->
          <div class="cd-timeline__content text-component">
            <h2>OLI TOWER v5 (TBC)</h2>
            <a class="color-contrast-medium" style ="text-decoration: underline" href="https://uk.pcpartpicker.com/list/jdPmdm">PCPartPicker Part List</a>
            <div class="flex justify-between items-center">
              <span class="cd-timeline__date">In Development</span>
            </div>
            <hr>
            <ul class="computer">
              <li class="gpu">EVGA RTX 3090 FTW3 Ultra</li>
              <li class="case">Gamemax Abyss Infinity</li>

              <li class="cpu">TBC</li>content
              <li class="cooler">TBC</li>
              <li class="motherboard">TBC</li>
              <li class="memory">TBC</li>
              <li class="storage">TBC</li>
              <li class="psu">TBC</li>
            </ul>
            <button type="button" class="collapsible">More Info</button>
            <div class="contentInfo">
              <p class="color-contrast-medium">Something that will last at least five years and be capable of VR.</p>
            </div> 
          </div> <!-- cd-timeline__content -->
        </div> <!-- cd-timeline__block -->
      </div>
      <div class="cd-timeline__block collapse" id="gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--yellow">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>GPU & Case Update</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">January 2018</span>
          </div>
          <hr>
          <ul>
            <li class="gpu">EVGA GTX 1080 Ti FTW3 Hybrid</li>
            <li class="case">Thermaltake V21</li>
          </ul>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">Less of a power requirement, graphics cards are crazy loud when under load and I wanted to move hybrid watercooling for near-silent gaming. Unfortunately the addition of another radiator meant I needed to spring for a larger case.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block collapse" id="gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI TOWER v4</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">February 2016</span>
          </div>
          <hr>
          <ul>
            <li class="cpu">Intel Core i7-6700K</li>
            <li class="cooler">Corsair H100i GTX</li>
            <li class="motherboard">Asus Z170i PRO GAMING</li>
            <li class="memory">Corsair Vengeance LPX 32GB DDR4</li>
            <li class="storage">Samsung 950 PRO 512GB M.2</li>
            <li class="gpu">EVGA GTX 980 Ti FTW</li>
            <li class="case">Corsair 250D</li>
            <li class="psu">Corsair 750W 80+ Platinum</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OT4boxes.jpg">
            <img src="/images/pages/tech/OT4table.jpg">
            <img src="/images/pages/tech/OT4inside.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">First build after gaming hiatus, continued with Mini-ITX, though with a little added girth in the case for AiO watercooling radiator.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI TOWER v3</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">August 2015</span>
          </div>
          <hr>
          <ul>
            <li class="cpu">Intel Core i5-4690 @3.7GHz</li>
            <li class="cooler">Arctic Freezer 11 LP</li>
            <li class="motherboard">Asus H81i-PLUS</li>
            <li class="memory">Corsair Vengeance LP 16GB DDR4</li>
            <li class="storage">Samsung 840 EVO 250GB</li>
            <li class="gpu">EVGA GTX 960 2GB SSC ACX 2.0+</li>
            <li class="case">Fractal Design Node 304</li>
            <li class="psu">Corsair VS 550W 80+</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OT3.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">After having taken a break from gaming to concentrate on work, and selling my old machine - I needed something capable enough for photo and video editing. This pre-build from Scan fit the bill and the Micro-ATX case was a nice change from the previous E-ATX monster.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--yellow">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>GPU Update</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">July 2011</span>
          </div>
          <hr>
          <ul>
            <li class="gpu">EVGA GTX 590 Classified Edition</li>
          </ul>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">Even by now SLI had lost it's edge. As I was still on a triple monitor setup I moved to the single GTX 590 which had two GPU chips on one card.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI TOWER v2</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">September 2010</span>
          </div>
          <hr>
          <ul>
            <li class="cpu">Intel Core i7-980X @3.5GHz</li>
            <li class="cooler">Corsair H70</li>
            <li class="motherboard">Asus Rampage III Extreme</li>
            <li class="memory">Corsair Dominator-GT 12GB DDR3</li>
            <li class="storage">OCZ Revodrive 240GB PCIe</li>
            <li class="gpu">EVGA GTX 480 SC (x2 SLI)</li>
            <li class="case">Lian-Li PC-P80B Full Tower</li>
            <li class="psu">Corsair 1000W Gold</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OT2.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">First job, first full-fat build - no expense spared.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI TOWER</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">TBC 2008</span>
          </div>
          <hr>
          <ul>
            <li class="cpu">Intel Core2 Quad Q6600 @3.0GHz</li>
            <li class="cooler">Tuniq Tower 120</li>
            <li class="motherboard">Asus P5N32-SLi SE Deluxe</li>
            <li class="memory">Corsair Dominator 4GB DDR2</li>
            <li class="storage">Samsung Spinmaster 320GB</li>
            <li class="gpu">Asus EN8800GTX (x2 SLI)</li>
            <li class="case">Lian-Li PC-P80B Full Tower</li>
            <li class="psu">OCZ 900W MOD XSTREAM</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OT1.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">First Gaming-PC build. Over the top case and solid all round components, stretching to SLI 8800GTX's once I'd earned enough.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI VAIO</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Summer 2005</span>
          </div>
          <hr>
          <h5>Sony VAIO a317M</h5>
          <ul>
            <li class="cpu">Intel Pentium M 740 Centrino @1.73Ghz</li>
            <li class="memory">512MB RAM</li>
            <li class="gpu">ATI Radeon X600</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OV.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">17" Laptop primarily for school work but obviously powerful enough for the odd game.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block gaming-pc">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/images/pages/tech/pc-case-white-square.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->
        <div class="cd-timeline__content text-component">
          <h2>OLI DELL</h2>
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Summer 2002</span>
          </div>
          <hr>
          <h5>Dell Dimension 8200</h5>
          <ul>
            <li class="cpu">Intel Pentium 4</li>
            <li class="memory">512MB RAM</li>
            <li class="gpu">nVidia GeForce3 64MB</li>
          </ul>
          <div class="gallery" data-columns="3">
            <img src="/images/pages/tech/OD.jpg">
          </div>
          <button type="button" class="collapsible">More Info</button>
          <div class="contentInfo">
            <p class="color-contrast-medium">The first Windows XP computer in the house, and my first PC bought specifically for me.</p>
          </div> 
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

<!-- PC FINISH -->
<!--
GameBoy Colour & Advance
Nintendo 64
Playstation 2
Playstation 3
Xbox One + Kinect
Xbox One X
-->
<!--
Asus Transformer TF101
Samsung Series 7 Slate
Microsoft Surface RT
Google Nexus 7
Microsoft Surface Pro 2
Microsoft Surface Pro 3
HP Stream 7
Samsung Galaxy Tab S3
-->

<!--
Nokia 3310
Sony Ericsson T68i
Sony Ericsson T610
Sony Ericsson W850
Sony Ericsson Z800
(Nokia 6210)
Sony Ericsson P1
(Nokia 6310)
HTC HD2
(Nokia 6310)
Samsung Omnia 7
Nokia Lumia 800
Nokia Lumia 920
Nokia Lumia 1020
Google Nexus 5
One Plus One
Samsung Galaxy S6 Edge 
Samsung Galaxy S7 Edge 
Google Pixel 2 XL
One Plus 6T
Google Pixel 4 XL
-->


      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--red">
          <img src="/js/timeline/img/cd-icon-movie.svg" alt="Movie">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Title of section 2</h2>
          <p class="color-contrast-medium">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, optio, dolorum provident rerum aut hic quasi placeat iure tempora laudantium ipsa ad debitis unde?</p>
          
          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Jan 18</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--green">
          <img src="/js/timeline/img/cd-icon-picture.svg" alt="Picture">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Title of section 3</h2>
          <p class="color-contrast-medium">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Excepturi, obcaecati, quisquam id molestias eaque asperiores voluptatibus cupiditate error assumenda delectus odit similique earum voluptatem doloremque dolorem ipsam quae rerum quis. Odit, itaque, deserunt corporis vero ipsum nisi eius odio natus ullam provident pariatur temporibus quia eos repellat consequuntur perferendis enim amet quae quasi repudiandae sed quod veniam dolore possimus rem voluptatum eveniet eligendi quis fugiat aliquam sunt similique aut adipisci.</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Jan 24</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--yellow">
          <img src="/js/timeline/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Title of section 4</h2>
          <p class="color-contrast-medium">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, optio, dolorum provident rerum aut hic quasi placeat iure tempora laudantium ipsa ad debitis unde? Iste voluptatibus minus veritatis qui ut.</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Feb 14</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--yellow">
          <img src="/js/timeline/img/cd-icon-location.svg" alt="Location">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Title of section 5</h2>
          <p class="color-contrast-medium">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Iusto, optio, dolorum provident rerum.</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Feb 18</span>
            <a href="#0" class="btn btn--subtle">Read more</a>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->

      <div class="cd-timeline__block">
        <div class="cd-timeline__img cd-timeline__img--red">
          <img src="/js/timeline/img/cd-icon-movie.svg" alt="Movie">
        </div> <!-- cd-timeline__img -->

        <div class="cd-timeline__content text-component">
          <h2>Final Section</h2>
          <p class="color-contrast-medium">This is the content of the last section</p>

          <div class="flex justify-between items-center">
            <span class="cd-timeline__date">Feb 26</span>
          </div>
        </div> <!-- cd-timeline__content -->
      </div> <!-- cd-timeline__block -->
    </div>
  </section> <!-- cd-timeline -->
  <script src="/js/timeline/js/main.js"></script>

<!--
  <script>
    function ToggleVisibility(divClass)
    {
        var els = document.getElementsByClassName(divClass);
        for(var i = 0; i < els.length; i++)
        {
            els[i].style.visibility = els[i].style.visibility == "hidden" ? "visible" : "hidden";
        }
    }
  </script>
-->

    <script>
      var coll = document.getElementsByClassName("collapsible");
      var i;
      
      for (i = 0; i < coll.length; i++) {
        coll[i].addEventListener("click", function() {
          this.classList.toggle("active");
          var contentInfo = this.nextElementSibling;
          if (contentInfo.style.maxHeight){
            contentInfo.style.maxHeight = null;
          } else {
            contentInfo.style.maxHeight = contentInfo.scrollHeight + "px";
          } 
        });
      }
      </script>
</body>
