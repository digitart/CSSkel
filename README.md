# CSSkel
CSSkel is a fork of [Barebones](https://acahir.github.io/Barebones/) by Steve Acahir.
Is a simple, responsive boilerplate based off the popular [Skeleton](http://getskeleton.com) project by [Dave Gamache](https://twitter.com/dhg).

We start using it for small but serious projects so we have to appended some basic structures missing and fixed some class names to make it meaningful but short and logic.

While there are several other active forks of Skeleton, CSSkel, as in Barebones, require no external tools or dependencies such as CSS pre-processors. Simply download (or link) and go.

## Getting started

You can simply link to it using https:/ccskel.com/1.0.0/csskel.min.css becasue the whole point is to have it easy to start with. No other dependency, jasvascript or preprocessor required.

CSSkel can be downloaded via [zip file](https://github.com/digitart/CSSkel/archive/master.zip) or the repo can be cloned using `git clone https://github.com/digitart/CSSkel.git`.

Once you have your bare hands on CSSkel, use the [documentation and examples](https://digitart.github.io/CSSkel/) to get started.


### What's in the download?

The download includes CSSkel CSS, the minified version of CSSkel, [Normalize CSS](https://github.com/necolas/normalize.css/) as a reset, a sample favicon, and an index.html as a starting point. It also includes skeleton-legacy.css in case you are updating an existing site, though this stylesheet is not linked in the index.html template.

```
Skeleton/
├── index.html
├── css/
│   ├── csskel.css
│   ├── csskel.min.css
│   ├── normalize.css
│   └── skeleton-legacy.css
└── images/
    └── favicon.ico

```

## Why CSSkel?

Building off of Skeleton's [awesomeness](https://github.com/dhg/Skeleton#why-its-awesome):
- Updated to use CSS variables - No pre processor required but you can theme it just setting a few variables
- Uses CSS Grid to replace 12-column grid system
- Updated normalize to current version (3.0.2 -> 8.0.1)

Additional features planned and possible:
- Support for @media prefers-color-scheme (aka Dark Mode)
- Pending Release: Uses CSS env() function
- Include "extensions": instructions and templates for frequently used features:
    - Navigation boilerplate
    - Code formatting
    - Smooth Scrolling
- Add additional example site demonstrating CSS Grid layout flexibility
    


## Browser support

Barebones does make use of modern CSS features, but the base functionality is well supported.

- CSS Grid: [88% global browser support](https://caniuse.com/#feat=css-grid) and raising.
- CSS Variables: [87% global browser support](https://caniuse.com/#feat=css-variables) and raising.

The most notable missing support for both features is from IE 11 or earlier. That's probably the browser that your decision will depend on.

CSSkel includes a few experimental features inherited from Barebones that are not yet widely supported. If not supported, the brower will simply ignore those directives:
- prefers-color-scheme media query: Only currently available in Safari Technology Preview
- scroll-behavior: Chrome, Firefox
- CSS env(): Nothing included in CSSkel, but media queries were structured in such as way to make use of env() variables in the future
Both of these features can be achived using other methods. In the future these may be added to CSSkel as "extensions".

#### External dependencies

- normalize.css: Chrome, Edge, Firefox ESR+, Internet Explorer 10+, Safari 8+, Opera


## Acknowledgements

CSSkel is build upon the great work of the Skeleton project by [Dave Gamache](https://twitter.com/dhg) and Barebones by Steve Acahir. It wouldn't be possible without them. CSSkel oexists because Skeleton is no longer being maintained and Barebones still inherit the use of "rows" and "exesive-verbose-classes-on-every-div" that IMHO are no longer required in modern HTML design.

The [documentation page](https://csskel.com/) makes use of icons by [FontAwesome](https://fontawesome.com), [native css smooth scroll](https://developer.mozilla.org/en-US/docs/Web/CSS/scroll-behavior), and other great tidbits shared by many.


## License

All parts of CSSkel are free to use and abuse under the MIT license.


