![image](https://github.com/user-attachments/assets/bae30446-525f-45c5-bb63-f97b75f7294c)
---

# Frontend Mentor - Blog Preview Card Solution

This is a solution to the [Blog Preview Card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). This challenge helps practice and improve coding skills by building realistic projects.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Development Process](#development-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Future Development](#future-development)
  - [Useful Resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

---

## Overview

### The Challenge

Users should be able to:

- View hover and focus states for all interactive elements on the page
- View the page with a responsive layout on different devices (desktop and mobile)

### Screenshot

![image](https://github.com/user-attachments/assets/86227041-8516-4d3d-aa76-cd80a94fad43)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## Development Process

### Built With

- Semantic HTML5 to structure the content
- CSS3 for styling and layout
- Flexbox for element alignment
- Media queries for responsive card resizing (content inside the card remains unchanged)
- Display `block` and `flex` for layout adjustments
- Yellow and black color palette for a minimalist design

### What I Learned

This project was a great opportunity to improve my HTML and CSS skills, especially in terms of applying responsive design principles. I used `media queries` to adjust the card size based on the screen width, ensuring a consistent visual experience on both mobile and desktop devices without altering the content within the card.

#### Example of media query code used:

```css
@media only screen and (min-width: 375px) and (max-width: 800px) { 
    #content {
        display: block;
        margin-inline: auto;
        width: 327px;
        height: 501px;
        background: white;
        border: 1px solid black;
        border-radius: 20px;
    }
}
```

This code snippet shows how the card’s size is adjusted to fit within the specified screen width range, keeping the content layout inside the card intact.

### Future Development

I plan to continue exploring responsive design techniques, including adding animations to enhance interactivity. Additionally, I aim to improve my knowledge of CSS variables to streamline style organization and facilitate future customizations.

### Useful Resources

- [Alura Blog](https://www.alura.com.br/artigos) - Provided helpful tips for web design and CSS best practices.
- [Stack Overflow](https://stackoverflow.com/) - Helped troubleshoot issues and find solutions during development.
- [Google Gemini](https://developers.google.com/gemini) - Useful for understanding responsive design fundamentals.
- [Dev Media Blog](https://www.devmedia.com.br/) - Offered great insights into CSS techniques and HTML structuring.

## Author

- Frontend Mentor - [@aclf12](https://www.frontendmentor.io/profile/aclf12)
- LinkedIn - [Ana Ferreira](https://www.linkedin.com/in/aclf12)

## Acknowledgments

Thanks to Frontend Mentor for the opportunity to work on this project and to the resources that were essential for learning during the creation of this website.

---