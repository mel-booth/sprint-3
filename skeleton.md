What happens to the layout when you resize the screen to less than 550px? How do you think that works?

When the screen is made less than 550px wide the layout changes from a multi-column layout to a single-column layout, stacking columns on top of one another in logical order, rather than side by side. This happens because there has been a @media query added to the CSS which instructs the layout to change when the screen size is reduced below 550px wide.
