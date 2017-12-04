##### How did you determine which rules should be placed in each new CSS file?

I decided to move anything that seemed like a reset or global setting into the
base file. So, for me this included all the resets and then the global font
setting using the asterisk. I then looked at all the content that seemed
noun-ish similar to how the SMACSS documentation stated and moved all that
content into the modules.css file. Finally, all the non-noun-ish rules which
for me were pretty much anything using a standard tag selector was moved into
the layout.css file.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

No. I left it as is. I discovered the background image wasn't displaying
properly from the get-go and neither was the horizontal ruler between the
header and rest of the body of the page.
