# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Accessibility and others](#Accessibility-and-others)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### Screenshot
<div align="center">
  <video src="https://github.com/RozangelaPeixoto/qrcode_component/assets/140510936/0588d6c6-04c4-4b93-b795-a99e929a2876">
</div>

### Links

- Solution URL: [Github](https://github.com/RozangelaPeixoto/qrcode_component/)
- Live Site URL: [Site](https://qrcode-component-gamma.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties (using BEM to name classes)
- Flexbox

### What I learned

It seems like a super simple project, but when I stopped to read an feedback from the same project that someone else had posted I realized that although I thought I had delivered something very similar to what the design asked for, there were several issues that I could improve and this taught me even more about semantics, flexbox, height and width of elements, margin and how to use them all in favor of responsiveness. And for the first time I searched about accessibility and discover Google Lighthouse, a tool that has its own panel in Chrome DevTools, it was incredible how it helped me, because it not only points out the problem, but explains how you can solve it.

### Accessibility and others

Using the Google Lighthouse I made some changes to my code to improve my scores. Here's the result:
<div align="center">
  <video src="https://github.com/RozangelaPeixoto/qrcode_component/assets/140510936/1e6d5dbf-364f-4ec8-84ce-e1872adf38a1">
</div>

Things that I change:
- [Issue] Links must be distinguishable without relying on color [Solution] I styled links with an underline.
- [Issue] Background and foreground colors do not have a sufficient contrast ratio. [Solution] I change the gray text to a darker color.

### Continued development

In the future I want to improve my skills in this topics: 
- Responsivity (Flexbox and Grid)
- Accessibility 
- SASS

### Useful resources

- [Question Stack Overflow](https://stackoverflow.com/questions/31000885/align-an-element-to-bottom-with-flexbox) - This helped me position the elements without using flexbox properties as it wasn't working the way I want.
- [Google Lighthouse](https://developer.chrome.com/docs/lighthouse) - How I only met this tool now?! And how this is on my browser without I knowing its potential?!

## Author

- Frontend Mentor - [@RozangelaPeixoto](https://www.frontendmentor.io/profile/RozangelaPeixoto)
- Instagram - [@dev_roxmelo](https://www.instagram.com/dev_roxmelo/)

## Acknowledgments

I want to thank two people:
- Jessica Chan, an youtuber that taught me several tips about the workflow to build a project.
- Grace (@grace-snow), an amazing person who always helps people on frontend mentor, it was your feedback that I read.
