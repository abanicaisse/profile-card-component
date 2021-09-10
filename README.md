# Frontend Mentor - Profile card component solution

This is a solution to the [Profile card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

## Overview

### The challenge

- Build out the project to the designs provided

### Screenshot

1. Desktop Design
![FEM-profile-card-component(1)](https://user-images.githubusercontent.com/84383548/132904309-21d75c69-12e6-44b6-b9a4-8f2afd206d11.png)

1. Mobile Design <br>
![FEM-profile-card-component(2)](https://user-images.githubusercontent.com/84383548/132904323-5bc4a4bc-894f-45b7-a23f-ac72be2089c2.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

- CSS flexbox
- CSS grid
- CSS absolute and relative positioning
- CSS before and after Pseudo elements
- HTML5 Markup
- CSS background-image properties
- CSS background-images positionning and sizing

Some HTML code from the project

```html
<body>
  <div class="card">
    <div class="bg-section"></div>
    <div class="card__profile">
      <img src="/assets/images/image-victor.jpg" alt="Victor" />
      <h3>Victor Crest <span>26</span></h3>
      <br />
      <p>London</p>
    </div>
    <hr />
    <div class="card__stats">
      <p>
        80K <br />
        <span>Followers</span>
      </p>
      <p>
        803K <br />
        <span>Likes</span>
      </p>
      <p>
        1.4K <br />
        <span>Photos</span>
      </p>
    </div>
  </div>

  <footer>
    <div class="attribution">
      Challenge by
      <a href="https://www.frontendmentor.io?ref=challenge" target="_blank"
        >Frontend Mentor</a
      >. Coded by
      <a href="https://www.github.com/abanicaisse">Aba Wandjvou Nicaisse</a>.
    </div>
  </footer>
</body>
```

Some CSS code from the project

```css
body {
  width: 100%;
  height: 100%;
  font-family: var(--font-Kumbh);
  display: grid;
  place-items: center;
  background-color: rgb(47, 164, 168);
  background-image: url("/assets/images/bg-pattern-bottom.svg"),
    url("/assets/images/bg-pattern-top.svg");
  background-repeat: no-repeat;
  /* background-size: cover; */
  background-position: top -200% left -20%, bottom -200% right -20%;
}

.card {
  width: min(25rem, 90%);
  border-radius: 0.5rem;
  display: grid;
}

.card .bg-section {
  padding: 5rem 0;
  background-image: url("/assets/images/bg-pattern-card.svg");
  background-repeat: no-repeat;
  background-size: cover;
  background-position: center center;
  border-top-left-radius: 0.5rem;
  border-top-right-radius: 0.5rem;
}

.card .card__profile {
  width: 100%;
  background-color: white;
  text-align: center;
}

.card .card__profile > img {
  border: 5px solid white;
  border-radius: 50%;
  margin-top: -3.5rem;
}

.card .card__profile > h3 {
  color: var(--clr-blue-200);
  font-family: var(--font-Kumbh);
  font-size: 1.5rem;
  font-weight: 700;
  padding: 1rem 0;
}
}
```

## Author

- Twitter - [@abanicaisse](https://www.twitter.com/abanicaisse)
- Frontend Mentor - [@abanicaisse](https://www.frontendmentor.io/profile/abanicaisse)
- CodePen - [My codepen](https://www.codepen.io/Nicaisse)
