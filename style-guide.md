# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- Soft red: hsl(7, 99%, 70%)
- Yellow: hsl(51, 100%, 49%)
- Dark desaturated cyan (graphic design text): hsl(167, 40%, 24%)
- Dark blue (photography text): hsl(198, 62%, 26%)
- Dark moderate cyan (footer): hsl(168, 34%, 41%)

### Neutral

- Very dark desaturated blue: hsl(212, 27%, 19%)
- Very dark grayish blue: hsl(213, 9%, 39%)
- Dark grayish blue: hsl(232, 10%, 55%)
- Grayish blue: hsl(210, 4%, 67%)
- White: hsl(0, 0%, 100%)

## Typography

### Body Copy

- Font size: 18px

### Font

- Family: [Barlow](https://fonts.google.com/specimen/Barlow)
- Weights: 600
- Family: [Fraunces](https://fonts.google.com/specimen/Fraunces)
- Weights: 700, 900

## Icons

We provide the required social icons. But, if you prefer, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)

 {
}

h1.card-title.heading.fw-900 {
  box-sizing: border-box;
  color: #25564b;
  font-family: Fraunces,sans-serif;
  font-size: calc(1.375rem + 1.5vw);
  font-weight: 900;
  line-height: 1.2;
  margin-bottom: .5rem;
  margin-top: 0;
  word-wrap: break-word;
}

@media (min-width: 1200px) {
  h1.card-title.heading.fw-900 {
    font-size: 2.5rem;
  }
}

p.card-text.text-center.p-3 {
  box-sizing: border-box;
  color: #25564b;
  font-family: Barlow,sans-serif;
  font-size: 18px;
  line-height: 27px;
  margin-bottom: 1rem;
  margin-top: 0;
  padding: 1rem;
  text-align: center;
  word-wrap: break-word;
}

p.card-text.text-center.p-3:last-child {
  margin-bottom: 0;
}