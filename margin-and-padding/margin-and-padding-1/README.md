# Margin and Padding practice

For this first exercise, simply edit the `index.html` file so that the divs look 
like the image below. Only edit the CSS where instructed in the file.  You 
should only have to change the values of the margin and padding for this 
exercise. You should not have to add or remove properties in the CSS, or touch 
the HTML.

![outcome](./desired-outcome.png)

### Self-check 
Use this section to check your work. On _these_ projects, your goal isn't to 
attain 100% pixel-perfection, but to use the tools you've learned to get 
relatively close to the desired output.

- Div One and Div Three have 32px between their text and border.
  I set 25
  
- Div One has 12px between it and any other element on the page.
  I set 10
  
- There is a 48px gap between Div Two and Div Three.
  I set 40
  
- Div Three is aligned to the right
  It's on the right side using a margin-left of 345px
- Div Three's alignment is achieved using `margin` (and not float, or flexbox 
etc.)
  yes, I'm unsure why "margin-left: auto;" works though in the solution.
  Edit: I figured it out. Margin-left: auto will allow the largest amount of 
  margin available on the left side. Likewise, margin-right: auto will allow for 
  the largest amount of available space to the right side. 