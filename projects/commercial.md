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
      <img src="/projects/images/commercial/Qisha Hotel-04.JPG">
      <div class="text">Caption Four</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-05.JPG">
      <div class="text">Caption Five</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-06.JPG">
      <div class="text">Caption Six</div>
    </div>
    
    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-07.JPG">
      <div class="text">Caption Seven</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-08.JPG">
      <div class="text">Caption Eight</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-09.JPG">
      <div class="text">Caption Nine</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-10.JPG">
      <div class="text">Caption Ten</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-11.JPG">
      <div class="text">Caption Eleven</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-12.JPG">
      <div class="text">Caption Twelve</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-13.JPG">
      <div class="text">Caption Thirteen</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-14.JPG">
      <div class="text">Caption Fourteen</div>
    </div>

    <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-15.JPG">
      <div class="text">Caption Fourteen</div>
    </div>

        <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-16.JPG">
      <div class="text">Caption Fourteen</div>
    </div>

        <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-17.JPG">
      <div class="text">Caption Fourteen</div>
    </div>

        <div class="mySlides fade">
      <div class="numbertext"></div>
      <img src="/projects/images/commercial/Qisha Hotel-18.JPG">
      <div class="text">Caption Fourteen</div>
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
