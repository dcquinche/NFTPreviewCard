# NFT Preview Card Component
 Make It Real - This is a solution to the NFT Preview Card Component Project of the Make It Real course.


## Table of contents
 1. [The challenge](#the-challenge)
 2. [Screenshot](#screenshot)
 3. [My process](#my-process)
 4. [Built with](#built-with)
 5. [What I learned](#what-i-learned)
 6. [Useful resources](#useful-resources)
 7. [Author](#author)
 8. [Acknowledgments](#acknowledgments)


### The challenge
 Users should be able to:
 Watch the different display depending on the size of the device (mobile or desktop) and the change of the color and image in some items when someone hover the mouse over them.


### Screenshot

#### Mobile design
![Mobile design](https://github.com/dcquinche/NFTPreviewCard/blob/main/design/Mobile.png)

#### Desktop design
![Desktop design](https://github.com/dcquinche/NFTPreviewCard/blob/main/design/Desktop.png)

#### Card in active mode

![Active image](https://github.com/dcquinche/NFTPreviewCard/blob/main/design/ActiveImage.png)

![Active title](https://github.com/dcquinche/NFTPreviewCard/blob/main/design/ActiveTitle.png)

![Active name](https://github.com/dcquinche/NFTPreviewCard/blob/main/design/ActiveName.png)


### My process
First we organized the HTML structure for the mobile design and we added the layouts including the hover selector on the image, title and author's name. Then, we put a @media to change the size of the component for a better display on the desktop design.


### Built with
- HTML
- CSS
- Mobile-first workflow
- Media Query

### What I learned
- Hover pseudo class to make changes when you mouse over them.

- display none to hide an element.


#### Example 1
```
 span {
    color: white;
}

span:hover {
    color: hsl(178, 100%, 50%);
}

```

#### Example 2
```
#view {
    display: none;
}

#equilibrium:hover + #view {
    display: block;
}

#equilibrium:hover{
    filter: opacity(0.6) drop-shadow(0 0 0 hsl(178, 100%, 50%));
}

```


### Useful resources	
[Hover Selector](https://www.w3schools.com/cssref/sel_hover.asp) - You can find information about hover and useful examples to learn how to use it.


### Author
Diana Carolina Quinche Velez -
[Linkedin](https://www.linkedin.com/in/diana-carolina-quinche-v%C3%A9lez-06b9791b3/)


### Acknowledgments
Special acknowledgments to my team partner Sebastian Muñoz and our mentor German Escobar.