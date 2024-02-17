<!-- scrap
~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ • ~ •
~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~ ~
EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES •
• EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES
EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES •

{{< carousel images="{https://cdn.pixabay.com/photo/2016/12/11/12/02/mountains-1899264_960_720.jpg, gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}

{{< carousel images="gallery/*" aspectRatio="21-9" interval="2500" >}}

EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES •
• EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES
EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES • EXAMPLES •



<style>
.slide {
  display: flex;
  align-items: center;
  justify-content: center;
}

.slide img {
  width: 100%;
}
</style>

<div class="slides">

  <div class="slide">
    <img src="test1.jpg">
  </div>

  <div class="slide">
    <img src="test2.jpg">
  </div>

  <div class="slide">
    <img src="img/test3.jpg">
  </div>

</div>

<script>
const slides = document.querySelectorAll('.slide');

let index = 0;

function updateSlide() {
  slides.forEach(slide => {
    slide.style.display = 'none';
  });

  slides[index].style.display = 'flex';
}

updateSlide(); // Initial
</script>


<!-- Added buttons back -->

<button class="prev">Prev</button>
<button class="next">Next</button>

<script>

// Button refs
const prevButton = document.querySelector('.prev');
const nextButton = document.querySelector('.next');

// Click handlers
prevButton.addEventListener('click', () => {
  index = Math.max(index - 1, 0); // Prevent going below 0
  updateSlide();
});

nextButton.addEventListener('click', () => {
  index = Math.min(index + 1, slides.length - 1); // Prevent going past last slide
  updateSlide();
});

</script>



<style>
.slideshow-container {
  width: 400px;
  position: relative;
}

.slideshow {
  display: block;
  flex-wrap: nowrap;
  overflow: hidden;
  width: 100%;
  animation: slide 20s infinite;
  transition: margin-left 0.5s ease-out;
}

.slideshow img {
  width: 100%;
  flex-shrink: 0;
}

.controls {
  position: absolute;
  top: 50%;
  width: 100%;
}

.controls button {
  font-size: 1.5em;
  border: none;
  background: none;
  color: #444;
  cursor: pointer;
}

.prev {
  position: absolute;
  left: 0;
}
.next {
  position: absolute;
  right: 0;
}
</style>

<div class="slideshow-container">

  <div class="slideshow">
    <img src="test1.jpg">
    <img src="test2.jpg">
    <img src="img/test3.jpg">
  </div>

  <div class="controls">
    <button class="prev">←</button>
    <button class="next">→</button>
  </div>

</div>

<script>
const slides = document.querySelector('.slideshow');
const prevButton = document.querySelector('.prev');
const nextButton = document.querySelector('.next');

let index = 0;

const updateSlidePosition = () => {
  slides.style.marginLeft = `-${index * 100}%`;
}

prevButton.addEventListener('click', () => {
  index = (index > 0) ? index - 1 : 0;
  updateSlidePosition();
})

nextButton.addEventListener('click', () => {
  index = (index < 2) ? index + 1 : 2;
  updateSlidePosition();
})
</script>



<style>
.slideshow-container {
  width: 800px;
  position: relative;
}

.slideshow {
  display: flex;
  width: 100%;
  animation: slide 20s infinite;
}

.controls {
  position: absolute;
  top: 50%;
  width: 100%;
}

.controls button {
  font-size: 1.5em;
  border: none;
  background: none;
  color: #444;
  cursor: pointer;
}

.prev {
  position: absolute;
  left: 0;
}

.next {
  position: absolute;
  right: 0;
}

</style>

<div class="slideshow-container">

  <div class="slideshow">
    <img src="test1.jpg">
    <img src="test2.jpg">
    <img src="img/image3.jpg">
  </div>

  <div class="controls">
    <button class="prev">Prev</button>
    <button class="next">Next</button>
  </div>

</div>




.slideshow {
  width: 800px;
  height: 400px;
}

.slideshow img {
  width: 800px;
  height: 400px;
}

<div class="slideshow-container">
  <div class="slideshow">
    <img src="test1.jpg">
    <img src="test2.jpg">
    <img src="img/test3.jpg">
  </div>
</div>

.slideshow-container {
  width: 800px;
  overflow: hidden;
}

<div class="controls">
  <button class="prev">Prev</button>
  <button class="next">Next</button>
</div>


<style>
.slideshow {
  display: flex;
  animation: slide 20s infinite;
}

@keyframes slide {
  0% {margin-left: 0;}
  25% {margin-left: -100%;}
  50% {margin-left: -200%;}
  75% {margin-left: -300%;}
}
</style>

<div class="slideshow">

  <img src="test1.jpg">
  <img src="test2.jpg">
  <img src="img/test3.jpg">

</div>

<code>hellosh?</code> <code>hellosh?</code> <code>hellosh?</code>
{{< carousel images="{img/test3.jpg, img/test4.jpg}" >}}






<div style="width: 100%;">
</div>
{{< carousel images="{zoom2.png},{zoom3.png}" width="100%" >}}
{{< carousel images="{https://cdn.pixabay.com/photo/2016/12/11/12/02/mountains-1899264_960_720.jpg, gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}

<div class="carousel">

  <img src="img/ie/iphone/zoom2.png" alt="Image 1">
  <img src="/img/ie/iphone/zoom1.png" alt="Image 2">

</div>

{{< carousel images="{img/ie/iphone/zoom1.png}" aspectRatio="9-16" >}}
{{< carousel images="{img/ie/iphone/*}" aspectRatio="9-16" >}}

{{< carousel images="img/ie/iphone/*" aspectRatio="16-9" interval="2500" >}}

{{< carousel images="{https://cdn.pixabay.com/photo/2016/12/11/12/02/mountains-1899264_960_720.jpg, gallery/03.jpg, gallery/01.jpg, gallery/02.jpg, gallery/04.jpg}" >}}


<div class="carousel">

  <img src="/content/posts/post3/img/ie/iphone/zoom1.png" alt="Image 1">

  <img src="/content/posts/post3/img/ie/iphone/zoom2.png" alt="Image 2">

  <img src="/anytype/content/posts/post3/img/ie/iphone/zoom3.png" alt="Image 3">

</div>


-->
