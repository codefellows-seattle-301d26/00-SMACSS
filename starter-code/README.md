##### How did you determine which rules should be placed in each new CSS file?

With help from the lovely SMACSS book I determined what each CSS rules was doing so I could properly place them in the right file. Things that affected the layout went into layout.css, things that affected appearance and reset.css went into base.css, and things such as classes, or whatever did not fit into the other files went into modules.css.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

I did not really do any refactoring. The only thing that I had to do was make sure that the import URL for the font stayed at the top of the file page in base.css and that the reset CSS rules came after that.
