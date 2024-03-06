### Screenshot

![desktop](/assets/images/screenshot-recipe-desktop.png)
![mobile](/assets/images/screenshot-recipe-mobile.png)

### Built with

- Semantic HTML5 markup
- CSS custom properties

### Challenges

- Figuring out how much whitespace is between each section and heading: it can be a challenge when you don't have the exact Figma file for reference. However, this challenge is an opportunity to sharpen your attention to detail.

Once I figured out this solution below, through trial and error 😅, everything fell into place when it comes to figuring out the margins in between the sections.

```css
li {
  line-height: 1.5;
  margin-bottom: 8px;
}
```

- Creating the table section proved to be a formidable task for me as well as I didn't know how to remove the borders around it. However through meticulous web searching, stack overflow and mdn docs, I successfully figured out this solution to my problem.

```css
table {
  width: 100%;
  border-collapse: collapse;
}
```

Morever, I still quite don't know how to make the horizontal lines thinner 😆 I have only found solutions to make it thicker.

Overall, I thoroughly enjoyed working on this project. It taught me about the acceptable amount of whitespace in design, among other things. 😄
