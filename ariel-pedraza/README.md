##### How did you determine which rules should be placed in each new CSS file?

Anything that targeted only a HTML element (shows in red in atom) and only modified text or color I moved to the base css. Then I moved anything that dealt with margin, padding, floats to layout css. This required me to split some identical blocks into both files only keeping the lines that belonged. All css targeting IDs went to layout as a whole, and all css targeting classes went to modules css.

---

##### Did you do any refactoring of the existing CSS? If so, briefly explain what you did and why.

Splitting blocks to separate layout from text related css possibly counts as refactoring? Didn't touch HTML doc to rename anything.
