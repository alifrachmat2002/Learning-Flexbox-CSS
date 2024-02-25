# Flexbox CSS Learning Journey

Welcome to my Flexbox CSS learning repository! 🌟 In this repository, I'll be documenting my journey as I dive into the world of Flexbox, a powerful layout system in CSS.

## What is Flexbox?

Flexbox, or the Flexible Box Layout, is a layout model in CSS that allows you to design complex layouts more easily and efficiently. It provides a more efficient way to lay out, align, and distribute space among items in a container, even when their size is unknown or dynamic.

## Learning Goals

- Understand the basics of Flexbox
- Master the various properties and values
- Create responsive layouts with Flexbox
- Solve common layout problems with Flexbox

## Resources

Here are some resources I'll be using for my learning journey:

- [Learn Flexbox in 15 Minutes](https://www.youtube.com/watch?v=fYq5PXgSsbE&t=153s)


## Learning Key Points

### 1. `display: flex`
   - Transforms an element into a flex container, allowing for flexible layouts.

### 2. `justify-content`
   - Aligns items along the main axis of the flex container.

### 3. `align-items`
   - Aligns items along the cross axis of the flex container.

### 4. `flex-grow`
   - Defines the ability for a flex item to grow if necessary.

### 5. `flex-shrink`
   - Defines the ability for a flex item to shrink if necessary.

### 6. `flex-basis`
   - Defines the initial size of a flex item.

Here's a summary of what I've learned so far, demonstrated with CSS code:

```css
* {
    padding: 0;
    margin: 0;
}

.bg {
    background-color: grey;
}

p {
    margin: 5px;
}

.flexbox-container {
    height: 100%;
    display: flex;
    margin-top: 25vh;
    background-color: yellow;
    justify-content: center;
    align-items: start;
}

.flexbox {
    border: 1px solid black;
    width: 100px;
    margin: 10px;
    background-color: grey;
}

.flexbox-item-1 {
    min-height: 100px;
    flex-grow: 1;
    flex-basis: 1;
}

.flexbox-item-2 {
    min-height: 200px;
    flex-grow: 2;
    flex-basis: 1;
}

.flexbox-item-3 {
    min-height: 300px;
    flex-grow: 3;
    flex-basis: 1;
}

## Author

- LinkedIn - [Alif Rachmat Illahi](https://www.linkedin.com/in/alifrachmat/)
- GitHub - [@alifrachmat2002](https://github.com/alifrachmat2002)
- Frontend Mentor - [@alifrachmat2002](https://www.frontendmentor.io/profile/alifrachmat2002)
