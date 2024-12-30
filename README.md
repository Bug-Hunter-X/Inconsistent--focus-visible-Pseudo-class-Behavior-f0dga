# Inconsistent :focus-visible Pseudo-class Behavior

This repository demonstrates an uncommon issue with the CSS `:focus-visible` pseudo-class.  In certain scenarios, the expected styling changes might not occur due to a lack of sufficient visual distinction between focused and unfocused states. This behavior can vary depending on browser, operating system, and accessibility settings.

The `bug.css` file contains the problematic code. `bugSolution.css` provides a potential solution.

## Problem
The `:focus-visible` pseudo-class may not trigger in cases where the focused styling is not sufficiently distinct from the unfocused state.  This can make focusing elements inconsistent across browsers and user configurations.