# odin-admin-dashboard

## Description
An admin dashboard created based on a provided screenshot of a design (dashboard-project.png in the "img" folder).

My iteration of this project adheres to the guidelines set out by the maintainers of **The Odin Project**, a self-paced curriculum for learning web development (links at the bottom).

**Why did I complete this project?:** To demonstrate my understanding of intermediate CSS techniques, such as the combined use of grid with flexbox, dynamic grids, custom CSS properties, and sizing with `calc()` and `clamp()`.

## Preview

## Launching this Project
- Click here to run it in your browser: 
## What I Learned
- The combination of `repeat()` with `auto-fill` and `minmax()` properties is useful for creating dynamic grids, that change cell size and number of columns depending on the browser's window size.
- Creating custom CSS properties with `:root` and `var(--custom-property-name)` makes it easier to keep a consistent theme/color scheme.
- Both `calc()` and `clamp()` are extremely helpful when making responsive designs:
  - `calc()`: Good whenever basic math is needed for CSS properties. (E.g. can allow an .icon class with a base fixed `px` width, that also increases relatively by a fraction of `vw`, the viewport width)    
  - `clamp()`: Good for setting limits on a range of values (e.g. min, ideal, and max font sizes). Can be especially useful for 'fluid typography' that smoothly scales with changing window sizes.

### Sources
- Odin Project Full Stack JavaScript Path: https://www.theodinproject.com/paths/full-stack-javascript/
  - Odin Project "Intermediate" HTML and CSS Course: https://www.theodinproject.com/paths/full-stack-javascript/courses/intermediate-html-and-css
- Project Instructions: https://www.theodinproject.com/lessons/node-path-intermediate-html-and-css-admin-dashboard