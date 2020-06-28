---
layout: project
show_title: false
titles:
  # @start locale config
  en      : &EN       Firm Profile
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
##### Commercial

  <div class="slideshow-container">
  <center>
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-01.jpg">
      <div class="text">Caption Text</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-02.jpg">
      <div class="text">Caption Two</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-03.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-04.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-05.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-06.jpg">
      <div class="text">Caption Three</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-07.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-08.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-09.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-10.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-11.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-12.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-13.jpg">
      <div class="text">Caption Three</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-14.jpg">
      <div class="text">Caption Three</div>
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
