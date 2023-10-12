# Web_Design-Assignment-5
Variables:-Variables allow you to store and reuse values throughout your SCSS code.
Usage: Defined at the beginning of SCSS files, e.g., $black, $blue, $white, $bg-color.

Custom Properties:-Custom properties, also known as CSS variables, allow you to define values that can be reused in your stylesheets.
Usage: defined with :root { --property-name: value; }

Nesting:-Nesting allows you to write more concise and readable styles by nesting selectors inside one another.
Usage: Used extensively for structuring styles within blocks, like nesting styles for .header, .navbar, etc.

Interpolation:-Interpolation allows you to embed the values of variables or expressions into strings.
Usage: Used in the @include boxShadowInterpolation(0, 0.5rem, rgba(17, 17, 17, 0.3)); line in  .header .logo section.

Placeholder Selectors:-Placeholder selectors, defined using %, allow you to define reusable styles without generating extra CSS code.
Usage: Used for %button-styles in _buttons.scss. Then, extended in .btn class in .header.

Mixins:-Mixins allow you to group CSS declarations together and reuse them throughout your code.
Usage: @mixin boxShadowInterpolation($x, $y, $color) in your _buttons.scss and used in .header .logo for shadow.

Functions:-Functions perform computations and return a value, allowing you to create dynamic styles.

Maps:-Maps allow you to store key-value pairs, providing a convenient way to manage related data.
Used for $colors map in your _buttons.scss and accessed with map-get in .button-primary

Conditional Control:- Conditional control structures, like @if, @else if, and @else, allow you to apply styles conditionally based on certain criteria.
