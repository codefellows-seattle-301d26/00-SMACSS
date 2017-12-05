##### How did you determine which rules should be placed in each new CSS file?

I placed anything that defined the default styling of how an element should look for all occurrences of that element in Base. Most of the rules were based on element selectors but there were also a few child selectors here as well.

In Layout I added anything that placed content elements on the page, such as float right, float left etc.

I placed smaller components that were within larger elements in the Modules file such as a recipe and a slogan

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not do ant refactoring.
