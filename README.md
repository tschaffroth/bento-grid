# Frontend Mentor - Bento grid solution

This is a solution to the [Bento grid challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/bento-grid-RMydElrlOj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [GitHub](https://github.com/tschaffroth/bento-grid.git)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5
- Flexbox
- CSS Grid and TemplateGridAreas
- Mobile-first workflow

### What I learned

I have been using CSS Grid before - however in this challenge i learned about CSS Grid Areas. This was an exciting new concept to me an an easy solution for the provided layout.

You can see an example of how i used it below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.feature--hero {
  background-color: var(--COLOR-PURPLE-DARK);
  padding: 4rem 3.2rem;

  display: flex;
  flex-direction: column;
  align-items: center;

  grid-area: hero;
}

.feature--accounts {
  padding: 1.6rem 1.6rem;
  overflow: hidden;
  grid-area: accounts;
}

.feature--schedule {
  background-color: var(--COLOR-YELLOW-DARK);
  height: 21.6rem;
  padding: 1.6rem 1.6rem 0 1.6rem;
  overflow: hidden;
  position: relative;

  grid-area: schedule;
}

/* ... */

.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 3.2rem;
  grid-template-areas:
    "hero hero"
    "accounts schedule"
    "social-media social-media"
    "social-media social-media"
    "grow grow"
    "audience audience"
    "quickness ai";
}
```

## Author

- Frontend Mentor - [@tschaffroth](https://www.frontendmentor.io/profile/tschaffroth)
