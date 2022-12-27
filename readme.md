# Responsive landing page with register form

This is a solution to a challenge by Frontend Mentor (see below), but I did a bit more than that:

1- Added a popup window with a register form using about the same design characteristics.
2- Made it so that the page adjusts itself to any imaginable screen size.

## See it in action at
https://ddandev.github.io/huddle-challenge/

# Frontend Mentor - Huddle landing page with single introductory section solution

This is a solution to the [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).

# Next improvements:


1- When screen height is short, form popup has a scrollbar but it is a little outside the window. Solution: get it to crop at window's border radius or move it a bit to the left if possible.

2- On short screen height, the popup form should still have the proper padding at top and bottom, so the contents are not displayed all the way to the very ends of the vertical axis.

1 and 2 can be fixed by a little bit of refactoring and having everything inside a smaller container inside the popup window. So the contents are scrolled instead of the entire popup, and the overflow hiding happens at the inner edges.
