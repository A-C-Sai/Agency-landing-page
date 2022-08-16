# Agency-landing-page

In this workshop, you'll build a minimal landing page for an agency.

This mockup is built entirely using _flow layout_: no Flexbox, no grid, no absolute positioning. It relies heavily on padding, margin, and border.

- **Pay close attention to alignment.** For example, you should be able to draw a line along the left, and all text should be neatly aligned.

## Design tokens

In the early days of the web, sites would be built largely on "feel". Colors and sizes would be chosen based on the whims of the moment. This led to some very inconsistent-looking websites!

Nowadays, it's common to have a set of _design tokens_. A design token is a value that can be reused. Typically it's part of a collection or a scale.

We'll learn more about this idea later, but for now, you can copy/paste the values from this list as-needed. Don't worry about being DRY or using variables; Plop these values in, wherever you need them.

**If you find it difficult to use these tokens, or if you're not able to achieve a result you're happy with, don't worry about it.** Solve it however you can, and then watch the solution video to see how I did it.

### Spacing

This app uses an 8px unit. All spaces are a multiple of 8px:

- `8px`
- `16px`
- `24px`
- `32px`
- `48px`
- `64px`
- `96px`
- `128px`

When it comes to max widths (eg. the maximum width of the card), arbitrary values can be used.

### Font

1 font is used in this project: `Lato`. It is already included in the stylesheet.

For font sizes, the `rem` unit should be used.

The scale is:

- `1rem`
- `1.25rem`
- `1.5rem`
- `2rem`

Because the base font size is 18px, this works out in pixels to:

- `18px`
- `22.5px`
- `27px`
- `36px`

### Color palette

Primary (green):

- `hsl(160deg, 100%, 30%)`

Secondary (gold):

- `hsl(45deg, 100%, 50%)` (lighter)
- `hsl(45deg, 100%, 40%)` (darker)

Grays:

- `hsl(0deg, 0%, 0%)` (black)
- `hsl(0deg, 0%, 10%)` (very dark)
- `hsl(0deg, 0%, 30%)` (dark)
- `hsl(0deg, 0%, 40%)` (medium)
- `hsl(0deg, 0%, 60%)` (light)
- `hsl(0deg, 0%, 100%)` (white)

> What the HSL?
>
> You may be more familiar with color values in hexidecimal format, like `#FF0000`. In Module 0's "color" lesson, we go over what HSL color is and how it works. If you haven't already, it's worth reviewing before getting started!
