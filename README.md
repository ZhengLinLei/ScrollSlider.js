<h1 align="center">ScrollSlider.js</h1>
<br>
<br>



<br>
<br>



<p align="center">
  <i>Create (video or image) slider with Javascript vanilla</i>
</p>

<p align="center">
  <a href="./CONTRIBUTING.md">Contributing</a>
  ·
  <a href="https://github.com/ZhengLinLei/ScrollSlider.js/issues">Issues</a>
</p>

<p align="center">
  <a href="https://opensource.org/licenses/Apache-2.0">
    <img src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" alt="ScrollSlider License" />
  </a>&nbsp;
  <a>
    <img src="https://img.shields.io/badge/version-0.3.1-brightgreen" alt="ScrollSlider Version" />
  </a>
</p>

<hr>


# How to use

## 1. Import the library

```html
<script src="../js/ScrollSlider.min.js"></script>
```

## 2. Create the slider

```html
<div class="scrollslider video-slider">
    <div class="slider__track">
        <ul class="slider__list">
            <li class="slider__slide">
                <img src="https://picsum.photos/1920/1080?random=1" alt="image 1">
            </li>
            <li class="slider__slide">
                <video autoplay muted loop>
                    <source src="video2.mp4" type="video/mp4"> 
                </video>
            </li>
            <li class="slider__slide">
                <img src="https://picsum.photos/1920/1080?random=3" alt="image 3">
            </li>
        </ul>
        <!-- The img tag can be changed to video tag -->
    </div>
</div>
```

## 3. Initialize the slider

```javascript
const slider = new ScrollSlider('.video-slider', 'WmhlbmdMaW5MZWk=', {
    // Options
});
```

## 4. Options

```javascript
const DefaultOptionsScroll = {
    //css3
    window_width: '100vw',
    track_width: '100%',
    //options
    start: 0,
    tooltips: false,
    tooltips_pos: "bottom", // "top", "center", "bottom" vertically
    tooltips_overflow: "no-overflow", // means set tooltips outside the slide windows "overflow" "no-overflow"
    navigation: true,
    navigation_overflow: "overflow"
}
```