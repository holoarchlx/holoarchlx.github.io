---
layout: project
show_title: false
titles:
  # @start locale config
  en      : &EN       Green Building
  en-GB   : *EN
  en-US   : *EN
  en-CA   : *EN
  en-AU   : *EN
  zh-Hans : &ZH_HANS  公司简介
  zh      : *ZH_HANS
  zh-CN   : *ZH_HANS
  zh-SG   : *ZH_HANS
  zh-Hant : &ZH_HANT
  zh-TW   : *ZH_HANT
  zh-HK   : *ZH_HANT
  ko      : &KO      
  ko-KR   : *KO
  fr      : &KO
  fr-BE   : *FR
  fr-CA   : *FR
  fr-CH   : *FR
  fr-FR   : *FR
  fr-LU   : *FR
  # @end locale config
key: page-about
---
##### Green Building

  <div class="slideshow-container">
  <center>
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/11-CQ Skyscraper.JPG">
      <div class="text">* CQ Skyscraper</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/12-CQ Skyscraper.JPG">
      <div class="text">* CQ Skyscraper</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/13-CQ Skyscraper.JPG">
      <div class="text">* CQ Skyscraper</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/14-CQ Skyscraper.JPG">
      <div class="text">* CQ Skyscraper</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/21-Dashang Tower.JPG">
      <div class="text">* Dashang Tower</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/22-Dashang Tower.JPG">
      <div class="text">* Dashang Tower</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/23-Dashang Tower.JPG">
      <div class="text">* Dashang Tower</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/31-Hengzhou Island Hotel.JPG">
      <div class="text">* Hengzhou Island Hotel</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/32-Hengzhou Island Hotel.JPG">
      <div class="text">* Hengzhou Island Hotel</div>
    </div>                                

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/41-Guangzhou Central Library.JPG">
      <div class="text">* Guangzhou Central Library</div>
    </div>                                

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/42-Guangzhou Central Library.JPG">
      <div class="text">* Guangzhou Central Library</div>
    </div>           

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/51-CISDI Headquarters.JPG">
      <div class="text">* CISDI Headquarters</div>
    </div>      

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/52-CISDI Headquarters.JPG">
      <div class="text">* CISDI Headquarters</div>
    </div>            

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/53-CISDI Headquarters.JPG">
      <div class="text">* CISDI Headquarters</div>
    </div>           

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/green/61-Yuzhong Culture Center.JPG">
      <div class="text">* Yuzhong Culture Center</div>
    </div>                                         

  </center>
  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="next" onclick="plusSlides(1)">&#10095;</a>

  </div>
  <br>

  <div style="text-align:center">
    
  </div>

  <script>
  var slideIndex = 1;
  showSlides(slideIndex);

  function plusSlides(n) {
    showSlides(slideIndex += n);
  }

  function currentSlide(n) {
    showSlides(slideIndex = n);
  }

  function showSlides(n) {
    var i;
    var slides = document.getElementsByClassName("mySlides");
    var dots = document.getElementsByClassName("dot");
    if (n > slides.length) {slideIndex = 1}    
    if (n < 1) {slideIndex = slides.length}
    for (i = 0; i < slides.length; i++) {
        slides[i].style.display = "none";  
    }
    for (i = 0; i < dots.length; i++) {
        dots[i].className = dots[i].className.replace(" active", "");
    }
    slides[slideIndex-1].style.display = "block";  
    dots[slideIndex-1].className += " active";
  }
  </script>
