# Browser Windows

__How to Switch between Windows?__

As soon as I open a URL in the browser, the driver focuses only on this particular window. Suppose I click on a link (in the footer). That links opens another browser window. Now I have 2 browser windows. But my driver focus is still on the parent window. The Parent Window is the earlier launched (original) browser window. The other window can be called a Child Window.

If I want to perform any action/operation/activity on the 2nd page (the child browser window), I cannot directly pass. Because the driver is still focused on the main page (the parent browser window).

To perform an action in the Child Window, I have to switch to it. My drver should swttch from one browser window to another, before I am able to to perform the action. Here's where the _switch_to_ command comes into the picture.

