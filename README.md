# Hicon
https://hicons.cosm.ws

[![Twitter](https://img.shields.io/static/v1?label=twitter&message=follow&color=1E9BEB)](https://twitter.com/CosWiSe)
[![Dribbble](https://img.shields.io/static/v1?label=dribbble&message=visit&color=EA4C88)](https://dribbble.com/coswise)
[![Donate](https://img.shields.io/badge/donate-paypal-blue.svg?style=flat-square)](https://www.paypal.me/coswise/2.5)



## What about Hicons?
Hicons is a simple vector icon pack crafted for designers and developers.<br>
The idea is to create an open source asset with consistent and minimal design. 

Each icon is been designed on Figma using a 24x24 grid.

## Usage

### Via CSS

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

### Via JS

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

## Got any feedback or want to contribute?
Feel free to use the follow [Google Form](https://docs.google.com/forms/d/1cL-D9V5BozdThCYlTOdlYDpyY48pjJb9hkpwKm1UiN4/prefill?pli=1).

## Figma Source
Check my work on Figma from [here](https://www.figma.com/file/42BwBxXLl656mLxaQCHJ3t/Hicon-Pack?node-id=0%3A1).

## License
[MIT License](https://github.com/colebemis/feather/blob/master/LICENSE).
