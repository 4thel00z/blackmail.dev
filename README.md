# blackmail.dev

## Motivation

I want a simple blog, where I can rant about code and hacking.

## Features

### Themes via @import Directive

You can easily switch between different themes for your blog by using the `@import` directive in your `style.css`. The available themes are:

- `theme-default.css`: The default dark theme, a bit dull.
- `theme-moonlight.css`: A theme inspired by [Moonlight GitHub](https://github.com/Moonlight-theme/Github).
- `theme-tokynoight.css`: A theme inspired by [Tokyonight Vim theme](https://vimcolorschemes.com/folke/tokyonight.nvim).

To apply a theme, simply add the `@import` statement at the top of your `style.css` file. For example, to use the default theme:

```css
@import url('theme-moonlight.css');
```

### Page size

Go to index.html and change the `pageSize` variable to the number of posts you want to display per page.

```javascript
const pageSize = 15; // Configurable page size
```

## License

This project is licensed under the GPL-3 license.
