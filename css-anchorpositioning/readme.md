Using GPT 5.2

Iteration 1 
Prompt - write me code using css anchor positioning api where I'll move an element around the screen with the mouse and the anchored tooltip will follow it in the appropriate position

- The dragging of element across the screen works fine. 
- The try fallbacks have not been used at all. 
- The tooltip is not really anchored to the element as expected

Iteration 2
Tried simplifying the superflous css with llm. But it still wrote
1. font sizes
2. unnecessary widths and heights
3. a tooltip arrow that doesn't work

So removed all of this.
It missed the crux of positioning ie adding the initial tooltip position. How can it try for fallbacks if there is nothing to start with? So I added position area and everything works much better.