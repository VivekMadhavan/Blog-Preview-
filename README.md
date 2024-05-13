# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Useful resources](#useful-resources)
- [Author](#author)



### Screenshot

<img width="831" alt="blog_preview - screenshot" src="https://github.com/VivekMadhavan/Blog-Preview-/assets/38138580/9814bdba-c743-4627-8938-535f76768373">


### Links

- Live Site URL: https://heartfelt-boba-712a83.netlify.app/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Clamp Function

### What I learned

I learned the basics of Flexbox design and the use of Clamp function to resize fonts without using media queries, although I need to work more on understanding how the function works effectively across device sizes.

```CSS
p {
    font-size: clamp(0.875rem,0.786rem + 0.41vw,1rem); /* based on min width of 360px and max width of 840px */
}

.primary-heading {
    font-size: clamp(1.3125rem,1.17rem + 0.625vw,1.5rem); /* based on min width of 360px and max width of 840px */
}
```

### Useful resources

- [Example resource 1](https://css-tricks.com/linearly-scale-font-size-with-css-clamp-based-on-the-viewport/) - This helped me resize font sizes using clamp.


## Author

- Frontend Mentor - [@VivekMadhavan](https://www.frontendmentor.io/profile/VivekMadhavan)
