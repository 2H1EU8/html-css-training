# Colors

## System colors

- `transparent` is a fully transparent color. It is also the initial value of background-color
- `currentColor` is the contextual computed dynamic value of the color property. If you have a text color of red, and then set border-color to be currentColor, it will also be red. If the element that you define currentColor on doesn't have a value for color defined, currentColor will be computed by the cascade instead.

# Sizing Units in CSS

CSS has several different units for specifying sizes, lengths, and other values. They can be broadly categorized into:

## Absolute Units

These units are fixed and represent a real-world measurement.

- **px (pixels)**: Represents a pixel on the screen. It's relative to the viewing device.
- **pt (points)**: Traditionally used in print media (1pt = 1/72 of an inch).
- **pc (picas)**: Another unit traditionally used in print (1pc = 12pt).
- **in (inches)**: Represents inches (1in = 2.54cm = 96px).
- **cm (centimeters)**: Represents centimeters.
- **mm (millimeters)**: Represents millimeters.

## Relative Units

These units are relative to another length property. This makes them more flexible and adaptable to different screen sizes and resolutions.

- **em**: Relative to the font-size of the element itself. For example, if an element has `font-size: 16px;` then `1em` will be `16px`. If used on the `font-size` property itself, it's relative to the _parent_ element's font size.
- **rem**: Relative to the font-size of the root element (`<html>`). This makes it easier to create consistent sizing across your entire site.
- **vw**: Relative to 1% of the viewport's width.
- **vh**: Relative to 1% of the viewport's height.
- **vmin**: Relative to the smaller dimension of the viewport (width or height).
- **vmax**: Relative to the larger dimension of the viewport (width or height).
- **ch**: Represents the width of the "0" (zero) glyph of the font used to render.
- **ex**: Represents the x-height of the font (typically the height of the lowercase "x").
- **%**: Represents a percentage value, relative to another value (often the parent element's size).

## Choosing the Right Unit

- For screen sizes, `px`, `em`, `rem`, `vw`, and `vh` are commonly used.
- `rem` is great for consistent scaling across the site, based on the root font size.
- `em` is useful when you want sizing relative to the current element's font size.
- `vw` and `vh` are useful for creating layouts that adapt to the viewport size.
- Avoid absolute units like `in`, `cm`, `mm` for screen display, as they may not scale well across different devices. They are more appropriate for print stylesheets.
