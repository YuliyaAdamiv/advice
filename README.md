# advice
This project build at the basic structure of HTML in web design. You can see the solutions in working with blocks, responsive design, crossbrowser compatible. 
Live demo [_here_](https://yuliyazakharchuk.github.io/Advice/). 

## Table of Contents

- [advice](#advice)
  - [Table of Contents](#table-of-contents)
  - [General Information](#general-information)
  - [Technologies Used](#technologies-used)
  - [Screenshots](#screenshots)
  - [Setup](#setup)
    - [To open](#to-open)
  - [Notes](#notes)
  - [Contact](#contact)


## General Information

- The project consists of index.html, css files, images and javascript file.
- The purpose of your project was show work with different types of blocks, text files and javascript files.

## Technologies Used

- HTML
- CSS
- JavaScript
- jQuery


## Screenshots


![Example screenshot](./img/scren.png)


## Setup

### To open

- Download/clone from the Github
- Open `index.html` file


## Notes

1. Actual time I had spent on this task was 10 hours. 
2. This project has sticky header, [JS Slider](https://swiperjs.com/), used BEM key concepts, used SCSS.
3. You can find realization of the change text of the header used jQuery.

```Js
$(function() {
    $('.slider__inner, .news__slider-inner').slick({
        nextArrow: '<button type="button" class="slick-btn slick-next"></button>',
        prevArrow: '<button type="button" class="slick-btn slick-prev"></button>',
        infinite: false
    });
    $('select').styler();
    $('.header__btn-menu').on('click', function() {
        $('.menu ul').slideToggle()
    })

});
```

## Contact

Created by [@Yuliya_Adamiv](https://github.com/YuliyaAdamiv).
