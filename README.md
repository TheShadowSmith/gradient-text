# Gradient-Text Utility
A little CSS utility I created based on a text color effect I found while surfing the [Stadia Developer Website](https://stadia.dev).

# Gradient-Text Example
Add example here.

# How to use it
1. Swipe the `gradient-text` CSS class from the [gradient-text.css](https://github.com/TheShadowSmith/gradient-text/blob/master/gradient-text.css) file.
```sh
.gradient-text {
    -webkit-background-clip: text;
    background-image: -webkit-linear-gradient(107deg, #9b0063, #ff4c1d);
    color: gradient-color-at(#9b0063, #ff4c1d);
    -webkit-text-fill-color: transparent;
}
```
2. Modify the CSS gradient HEX values with whatever colors you wish to be in your gradient and change the angle of the gradient to whatever you prefer.
```sh
.gradient-text {
    -webkit-background-clip: text;
    background-image: -webkit-linear-gradient(ANGLE, HEX CODE 1, HEX CODE 2);
    color: gradient-color-at(HEX CODE 1, HEX CODE 2);
    -webkit-text-fill-color: transparent;
}
```
3. Add the "gradient-text" CSS class to `<div>` elements.
```sh
<div class="gradient-text">
        Gradient Text Demo
</div>
```