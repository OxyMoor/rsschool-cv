# OKSANA MOOR
## Front-end Developer
* Minsk
* telegram: @Oxy_Moor
* email: hikki0019@gmail.com

## Summary
Responsible, assiduous, hardworking. I know how to correctly allocate time. Due to my pharmaceutical education and work as a pharmacist, I can find a common language with people, resolve conflicts, study a lot of information in a short time. I am currently looking for a job as a Front-end Developer after successfully completing relevant courses.

## Skills
* HTML 5
* CSS 3 (flex, grid, SCSS/SASS, Bootstrap)
* JavaScript basic (Data types, cycles, functions, JS scope, BOM, DOM events, OOP, Event loop, JS animation, JSON)
* Webpack
* Git
* Manual testing
* English - A2/B1 Pre-Intermediate

## Code example
This is the code for responsive burger menu:
```
const navBtn = document.querySelector('.nav-open-btn');
const navBtnImg = document.querySelector('.nav-btn-img');
const nav = document.querySelector('.nav');

navBtn.addEventListener('click', () => {
    if (nav.classList.toggle('open')) {
        navBtnImg.src = './img/header/close-menu-btn.svg'
    } else {
        navBtnImg.src = './img/header/open-menu-btn.svg'
    }
});
```