# TabulaRasa: A CSS Reset Stylesheet

TabulaRasa is a CSS reset stylesheet designed to provide a consistent starting point for your web projects by removing default styling and ensuring cross-browser compatibility. This allows you to take control of your design and apply your desired styles without any unwanted surprises.

## Details

TabulaRasa tackles several aspects of CSS resetting, including:

- Box-sizing: By setting `box-sizing: border-box` on all elements, TabulaRasa ensures that the dimensions of an element include padding and border, making it easier to control the layout.
- Typography: The reset stylesheet normalizes font sizes, line heights, and font weights for headings and other text elements. It also removes default margins and paddings.
- Lists: TabulaRasa removes list styles, such as bullets and numbers, and sets default margins and paddings to zero.
- Forms: The reset addresses form elements like buttons, inputs, and textareas by removing default appearances, borders, and background colors. It also sets consistent font and text styles for form elements.
- Table elements: TabulaRasa ensures a consistent appearance for tables by collapsing borders, setting default border colors, and removing default padding and margins.

In addition to these resets, TabulaRasa also includes a few accessibility improvements, such as setting `cursor: pointer` for buttons and ensuring focus styles are visible.


## How to use TabulaRasa

To use TabulaRasa in your web project, follow these steps:

1. Download the `tabularasa.css` file from this repository.
2. Add the following line to the `<head>` section of your HTML file:

```html
<link rel="stylesheet" href="path/to/tabularasa.css">
```

Make sure to replace `path/to/` with the correct path to the `tabularasa.css` file in your project directory.

3. Add your custom CSS styles after the `tabularasa.css` link in your HTML file, like this:

```html
<link rel="stylesheet" href="path/to/tabularasa.css">
<link rel="stylesheet" href="path/to/your-styles.css">
```

By doing this, your custom styles will override the reset styles provided by TabulaRasa.

## Browser Support

TabulaRasa has been tested and is compatible with the following browsers and their respective versions:

| Browser                      | Support | Minimum supported version |
| ---------------------------- | ------- | ------------------------- |
| Google Chrome                | ✅      | 49+                       |
| Mozilla Firefox              | ✅      | 45+                       |
| Microsoft Edge               | ✅      | 12+                       |
| Apple Safari                 | ✅      | 9.1+                      |
| Opera                        | ✅      | 36+                       |
| Microsoft Internet Explorer  | ❌      |                           |

Please note that while TabulaRasa aims to provide a consistent starting point for web projects, there may still be minor differences between browsers due to their specific implementations. It is always recommended to thoroughly test your project on various browsers and devices to ensure a smooth user experience.