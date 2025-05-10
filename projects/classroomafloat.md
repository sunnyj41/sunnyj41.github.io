---
layout: default
---

### A Classroom Afloat

<div class="carousel-container">
  <div class="carousel">
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom1.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom2.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom3.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom4.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom5.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom6.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom7.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom8.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom9.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom10.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom11.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom12.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom13.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom14.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom15.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom16.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom17.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom18.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom19.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom20.png" alt="">
    </div>
    <div class="carousel-item">
      <img src="/portfolio/assets/classroom21.png" alt="">
    </div>
  </div>
  <button class="carousel-button prev">❮</button>
  <button class="carousel-button next">❯</button>
</div>

<style>
.carousel-container {
  position: relative;
  max-width: 100%;
  margin: 20px 0;
  overflow: hidden;
}

.carousel {
  display: flex;
  transition: transform 0.5s ease-in-out;
}

.carousel-item {
  min-width: 100%;
  box-sizing: border-box;
}

.carousel-item img {
  width: 100%;
  height: 400px;
  object-fit: contain;
  background-color: white;
}

.carousel-button {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  background: rgba(0, 0, 0, 0.5);
  color: white;
  border: none;
  padding: 10px 15px;
  cursor: pointer;
  font-size: 18px;
  border-radius: 50%;
}

.carousel-button:hover {
  background: rgba(0, 0, 0, 0.8);
}

.prev {
  left: 10px;
}

.next {
  right: 10px;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const carousel = document.querySelector('.carousel');
  const items = document.querySelectorAll('.carousel-item');
  const prevButton = document.querySelector('.prev');
  const nextButton = document.querySelector('.next');
  let currentIndex = 0;

  function updateCarousel() {
    carousel.style.transform = `translateX(-${currentIndex * 100}%)`;
  }

  prevButton.addEventListener('click', () => {
    currentIndex = (currentIndex - 1 + items.length) % items.length;
    updateCarousel();
  });

  nextButton.addEventListener('click', () => {
    currentIndex = (currentIndex + 1) % items.length;
    updateCarousel();
  });
});
</script>

Learn world history by traveling to different locations and time periods in VR

Starting with Song Dynasty China, Ancient Crete, and Pre-Columbian Teotihuacan

&nbsp;

**Tech:**

Unity, C#

&nbsp;

**Collaborators:**

Lance Powell (project manager), Shyanne Russell (3D artist)

&nbsp;

[[back]](/portfolio/projects)

&nbsp;

&nbsp;