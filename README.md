![Doughnut.css](/donut.png | width=100)

# Doughnut.css

Doughnut.css is a classless CSS framework, built with the intention of being as small as possible without sacrificing aesthetics.

Browsers these days do a great job of rendering information, and with each operating system or browser, there are different defaults. But instead of seeing this as a nuisance, we can accept it and work with it - to create experiences tailored to each users preferred systems.

- It uses only system fonts
- No CSS variables (to minimise processing on the client side)
- Only includes what is necessary
- Minified & compressed

## Use & customisation

Doughnut.css is primarily built for simple, text-heavy sites, such as blogs and journals. It does contain basic styling for images, but is focused on keeping a small singular column of text to improve readibility.

Doughnut.css is built using Stylus, a CSS preprocessor which comes with it's own CLI. This allows for a single dependency to build and bundle the CSS, keeping even the development environment lightweight. Some variables such as heading and body fonts, and colours, are defined at the beginning of the file. These can be customised as and when desired.

This classless framework isn't designed to necessarily be the be all and end-all for your styling needs, but a great starting place where you want something lightweight and easy to use.

## Why Doughnut?

I was inspired to build this because of an idea known as [Doughnut economics](https://www.kateraworth.com/doughnut/), an idea founded by [Kate Raworth](https://www.kateraworth.com/), which explores the notion of using constraints (a social foundation, and planetary boundaries) as a foundation of the economy in order to create a sustainable, thriving world.

The idea being to use constraints of the browser, internet, and energy usage but without comprising aesthetics, readability, and enjoyment.

(There's also the added benefit that the name was available on npm).
