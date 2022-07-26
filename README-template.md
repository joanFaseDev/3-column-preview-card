# Frontend Mentor - 3-column preview card component solution

This is a solution to the [3-column preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/3column-preview-card-component-pH92eAR2-). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## About myself

I'm an aspiring front-end developper which means this project is not the best learning material yet i always try to explain part of my process to the best of my abilities. Which brings me to my second point, english isn't my first language so please excuse me for any mispellings or grammatical errors, past or future.

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size
- See hover states for interactive elements

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it.

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- Solution URL: [Project on GitHub](https://github.com/joanFaseDev/3-column-preview-card)
- Live Site URL: [Project hosted through Vercel](https://3-column-preview-card-mu.vercel.app/)

## My process

### Analysis

- The card have two different layouts, one for mobile and the other for desktop computer. That means the card is responsive.
- In mobile design, the card is made out of three rows. In desktop design, it is made out of three columns. This pattern is easy to reproduce by using CSS Grid.
- The card can be divided into three parts (Sedans, Suvs and Luxury). Their content is different but their layout is the same. That means we can resuse a lot of css code by using class effectively.
- For each part, we can use a _section_ element. Nested in it, a _img_ for the svg icon, a _h2_ for the title, a _p_ for the description and an _a_ for the button.
- We can probably add a _div_ container between the _section_ and the other elements. By setting a width in percentage, we won't have to rely too much on padding which isn't too great for responsiveness.
- The padding inside each part doesn't seem to change too much between mobile layout and desktop layout, except for the space between the paragraph and the button which is bigger in desktop design.
- The buttons have an hover state where background-color and color switch. Can be reproduced with _transition_ and pseudo-class _:hover_.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Frontend Mentor - [@joanFaseDev](https://www.frontendmentor.io/profile/joanFaseDev)
