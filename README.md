# 🎛️ recruiting-knob-ui

A programming challenge focused on custom ui elements built with snabby and SVG.


## Description

Knobs are interesting UI components in that they often closely model the controls found on physical appliances. When done well, they can provide a nice looking alternative to a traditional slider/range input.



## Task
Build a custom knob element with the following constraints:

* make the knob a custom html component. e.g., it should be possible to instantiate one of these knobs by putting html into a page, like this: `<custom-knob> </custom-knob>  ` https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements
* internally within the custom element, render the knob using `snabby`  https://github.com/mreinstein/snabby
* The element should be interactive; Should be able to use mouse and/or touch input to drag the knob position
* draw the knob graphic itself as an SVG element.
* fire an event when the knob's input value changes (see `index.html`for the expected API.)



### Sample SVGs

If you look at the source of  `index.html` you'll see  2 `<svg>`  tags that you can use to render the control in your implementation.

1- Here's how the knob should look "normally":

![normal](figures/normal.png)

2- Here's how it should look while being interacted with:

![active](figures/active.png)




## Additional Constraints
* you can assume ultra-modern browser feature support (custom elements v1, optional chaining, etc.) no need to polyfill or handle old browsers.



## Hints
A lot of things going into modern "high quality" UI components. Try to come up with something that _you_ think satisfies those important aspects, and explain them.




## Setup
- clone this repo
- serve this directory in any web server of your choosing
- open index.html and hack away!




## Miscellaneous Notes and Links
* snabby, the virtual dom rendering library you should use https://github.com/mreinstein/snabby
* a primer on custom elements v1: https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements




## Timeframe

Take as long as you need, and submit when ready. That said, it shouldn't take a week to make this.

Good Luck! 🚀
