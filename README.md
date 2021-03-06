# Hicon
[hicon.me/](https://hicon.me/)

[![Twitter](https://img.shields.io/static/v1?label=twitter&message=follow&color=1E9BEB)](https://twitter.com/CosWiSe)
[![Dribbble](https://img.shields.io/static/v1?label=dribbble&message=visit&color=EA4C88)](https://dribbble.com/coswise)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://www.paypal.me/coswise/2.5)



## What about Hicon?
Hicon is a simple vector icon pack crafted for designers and developers, free and continuously growing.<br>
The idea is to create an open source asset with consistent and minimal design. 

Each icon is been designed on Figma using a 24x24 grid.

## Usage
### Via JS (Recommended)

Start adding the JS file and a short callback at the end of your document `<body>`.
You can download it from this [link](https://github.com/coswise/hicon-js) if you prefer a local setup.

```html
<body>
  <script src="https://cdn.jsdelivr.net/gh/coswise/hicon-js@latest/hicon.min.js"></script>
  <script>
    hicon.replace();
  </script>
</body>
```

To use the icons on your page, use the icon tag with `load-hicon` followed by the icon's name.

```html
<i load-hicon="hicon"></i>
<i load-hicon="arrow-right"></i>
<i load-hicon="dribbble"></i>
```

### Via CSS
### !NOTICE! - The WebFont is not update with the new version.

Start adding the stylesheet on your document `<head>`.
You can download it from this [link](https://github.com/coswise/hicon-css) if you prefer a local setup.

```html
<head>
  <link rel="stylesheet" href="hicon.min.css">
</head>
```

Or you ca use the CDN to pull the icons on your site.

```html
<head>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/coswise/hicon-css@latest/web-fonts/hicon.min.css">
</head>
```

To use the icons on your page, add the class `h` and a second class that start with the prefix `h-` followed by the icon's name.

```html
<i class="h h-hicon"></i>
<i class="h h-arrow-right"></i>
<i class="h h-dribbble"></i>
```

## Got any feedback or want to contribute?
Feel free to use the follow [Google Form](https://forms.gle/MfgyfSpiX8Er6xeN6).

## Figma Source
Check my work on Figma from [here](https://www.figma.com/file/42BwBxXLl656mLxaQCHJ3t/Hicon-Pack?node-id=0%3A1).

## License
[MIT License](https://github.com/colebemis/feather/blob/master/LICENSE).<br>
[Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0).

Hicon Pack is completely <strong>free</strong> to use on personal or commercial project. However, it will be appreciate if you add credit in your project.
## Contact
Email: <a href="mailto:hicon@cosm.ws" target="_blank">hicon@cosm.ws</a>
