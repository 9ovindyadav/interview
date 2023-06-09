## HTML and CSS interview questions

1. > what is the difference between absolute and fixed position ?

**Answer**:     
- " absolute " positioning is relative to the nearest positioned ancestor or the initial containing block, while " fixed " positioning is relative to the viewport.
- " absolute " positioning is not affected by scrolling, while " fixed " positioning remains fixed even when the page is scrolled.
- Both positioning types take the element out of the normal document flow and allow precise positioning using the " top ", " bottom ", " left ", and " right " properties.

2. > what is the purpose of z-index property ?

**Answer**: The z-index property in CSS is used to control the stacking order of positioned elements on a web page. It determines which elements appear in front of or behind other elements when they overlap in the z-axis (the depth or stacking order or layering of elements on the page).

3. > what is the difference between "visibility: hidden" and  "display: none" ?

**Answer**: 
- Visibility:
    - When an element is set to "visibility: hidden," it is still rendered on the page, but it is not visible. The element takes up space in the layout, and its dimensions affect the positioning of other elements. Essentially, it is as if the element is transparent.
     
    - The hidden element is not visible, but it still interacts with the page. For example, you can still click on it or access its content through screen readers. It does not disrupt the flow of the document.

- Display:

    - When an element is set to "display: none," it is completely removed from the flow of the document. The element is not rendered, and it does not take up any space on the page. Other elements behave as if the hidden element does not exist.
