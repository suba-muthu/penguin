## About the project

* It is a basic Html and Css animation project.

## Tools used

* HTML
* CSS

## Learning

* :root selector -  matches the document's root element.
    * syntax - :root { css declarations; }.
    * :root - variables are often declared in the :root selector. putting your variables there will make them usable everywhere.
* Variable declarations begin with two dashes (-) and are given a name and a value.
    * syntax - --variable-name: value;
* var() - This function is used to insert the value of a CSS variable.
    * syntax - var(--name, value)
    * name - The variable name (must start with two dashes).
    * value - The fallback value (used if the variable is not found).
* linear-gradient - To create a linear gradient you must define at least two color stops.You can also set a starting point and a direction (or an angle) along with the gradient effect.
    * syntax - background-image: linear-gradient(direction, color-stop1, color-stop2, ...);
* transform property - applies a 2D or 3D transformation to an element. This property allows you to rotate, scale, move, skew, etc., elements.
    * transform: none|transform-functions|initial|inherit;
* animation property - It is a shorthand property.
    * syntax - animation: name duration timing-function delay iteration-count direction fill-mode play-state;
* @keyframes - The @keyframes rule specifies the animation code. It is used to define the flow of a CSS animation.
    * syntax - @keyframes animationname {keyframes-selector {css-styles;}}
    * Specify when the style change will happen in percent, or with the keywords "from" and "to", which is the same as 0% and 100%. 0% is the  beginning of the animation, 100% is when the animation is complete.
* z-index - It's specifies the stack order of an element.An element with greater stack order is always in front of an element with a lower stack order.
    * z-index: -1;