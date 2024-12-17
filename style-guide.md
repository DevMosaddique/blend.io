# Essential Stuff

## Html import links

Google font

``` html
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=DM+Sans:wght@400;500&family=DM+Serif+Display&display=swap"
  rel="stylesheet">
```

Material icon

``` html
<link rel="stylesheet"
    href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@24,400,0..1,0" />
```

---

## CSS Variables

### Colors

``` css
--white: hsl(0, 0%, 100%);
--overlay-bg: hsla(0, 3%, 13%, 0.5);
```

Light colors

``` css
--light-background: hsl(40, 12%, 95%); /* Soft beige background */
--light-on-background: hsl(0, 3%, 13%); /* Primary dark text */
--light-on-background-variant: hsl(20, 3%, 19%); /* Slightly lighter text */
--light-primary: hsl(141, 42%, 50%); /* Green accent for buttons and links */
--light-primary-hover: hsl(141, 35%, 45%); /* Darker hover for green accent */
--light-primary-container: hsl(142, 76%, 90%); /* Light green container background */
--light-error: hsl(1, 73%, 42%); /* Error red */
--light-active-indicator: hsl(141, 52%, 88%); /* Highlighted active indicators */
--light-image-background: hsl(0, 0%, 80%); /* Light gray placeholder for images */
--light-badge-btn: hsl(30, 58%, 88%); /* Badge/button background */
--light-on-badge-btn: hsl(24, 7%, 14%); /* Badge button text */
--light-outline: hsl(10, 19%, 88%); /* Outline for inputs/cards */
--light-input-outline: hsl(7, 7%, 73%); /* Neutral input borders */
--light-input-outline-hover: hsl(9, 3%, 52%); /* Darker hover for input outlines */
--light-alpha-10: hsla(0, 0%, 0%, 0.1); /* 10% black alpha */
--light-alpha-20: hsla(0, 0%, 0%, 0.2); /* 20% black alpha */

```

Dark colors

``` css
--dark-background: hsl(0, 0%, 10%); /* Dark gray background */
--dark-on-background: hsl(0, 0%, 90%); /* Light text */
--dark-on-background-variant: hsl(0, 0%, 80%); /* Slightly dimmer text */
--dark-primary: hsl(141, 42%, 55%); /* Soft green accent */
--dark-primary-hover: hsl(141, 38%, 45%); /* Darker green hover */
--dark-primary-container: hsl(141, 22%, 20%); /* Deep green container */
--dark-error: hsl(1, 69%, 59%); /* Error red */
--dark-active-indicator: hsl(141, 25%, 22%); /* Active indicator background */
--dark-image-background: hsl(0, 0%, 30%); /* Dark gray for placeholders */
--dark-badge-btn: hsl(30, 28%, 13%); /* Badge button background */
--dark-on-badge-btn: hsl(30, 8%, 86%); /* Badge button text */
--dark-outline: hsl(11, 3%, 20%); /* Darker outline for cards */
--dark-input-outline: hsl(11, 3%, 29%); /* Input borders */
--dark-input-outline-hover: hsl(11, 3%, 58%); /* Lighter hover state */
--dark-alpha-10: hsla(0, 0%, 100%, 0.1); /* 10% white alpha */
--dark-alpha-20: hsla(0, 0%, 100%, 0.2); /* 20% white alpha */

```

### Typography

Font family

``` css
--font-primary: 'DM Serif Display', serif;
--font-secondary: 'DM Sans', sans-serif;
```

Font size

``` css
--fs-base: 62.5%;
--fs-display-large: 2.8rem;
--fs-display-medium: 3.2rem;
--fs-display-small: 2.6rem;
--fs-headline-small: 2.4rem;
--fs-title-medium: 1.6rem;
--fs-title-small: 1.4rem;
--fs-body-large: 1.6rem;
--fs-body-medium: 1.4rem;
--fs-label-large: 1.4rem;
--fs-label-medium: 1.2rem;
--fs-label-small: 1.1rem;
```

Font weight

``` css
--weight-regular: 400;
--weight-medium: 500;
```

### Border Radius

``` css
--radius-4: 4px;
--radius-8: 8px;
--radius-circle: 50%;
--radius-pill: 500px;
```

### Box Shadow

``` css
--shadow-1: 0 -1px 8px hsla(0, 0%, 0%, 0.2);
--shadow-2: 0 2px 4px 1px hsla(0, 0%, 0%, 0.3);
```

### Others

``` css
--header-height: 64px;
--mobile-nav-height: 80px;
--section-gap: 32px;
```

### Transition

``` css
--transition-timing-function: cubic-bezier(0.2, 0, 0, 1);
--transition-short: 200ms var(--transition-timing-function);
--transition-medium: 500ms var(--transition-timing-function);
```
