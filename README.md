# Slightly Better CSS

A webpage without any CSS is slightly too ugly, libraries like Bootstrap are way too heavy, and you have too much taste to use the other CSS libraries out there. Slightly Better CSS is a small, simple stylesheet for any project that needs to look just a little bit better.

We don't believe in classes or ID's, all our styling is around built-in variables, so you can write simple HTML. At only 2KB, Slightly Better CSS won't weight down your application, and is easily extendable.

Here's the updated **Installation** section with unpkg and jsDelivr added, along with download links:

---

## 📦 Installation

### Use Directly

Include the stylesheet in your project directly using the following link:

```html
<link
  rel="stylesheet"
  href="https://printerscanner.github.io/slightly-better-css/slightly-better.css"
/>
```

Alternatively, use a CDN:

- **unpkg**:
  ```html
  <link
    rel="stylesheet"
    href="https://unpkg.com/slightly-better-css/slightly-better.css"
  />
  ```
- **jsDelivr**:
  ```html
  <link
    rel="stylesheet"
    href="https://cdn.jsdelivr.net/npm/slightly-better-css/slightly-better.css"
  />
  ```

### Install via npm

You can also install Slightly Better CSS via npm:

```bash
npm install slightly-better-css
```

Then import it into your project:

```javascript
import "slightly-better-css";
```

### Clone the Repository

Want full control? Clone the repo and make adjustments to the CSS file as needed:

```bash
git clone https://github.com/printerscanner/slightly-better-css.git
```

### Download

- [Download slightly-better.css (un-minified)](https://unpkg.com/slightly-better-css/slightly-better.css)
- [Download slightly-better.min.css (minified)](https://unpkg.com/slightly-better-css/slightly-better.min.css)

## Customizing

If you like slightly better css but want a custom look, you can copy and paste these variables into your own stylesheet and swap your values.

```css
:root {
  --background-color: #c3c7cf;
  --text-color: #000000;
  --accent-color: #00000f;
  --muted-color: #f6f6f6;
  --font-family: "Neue Montreal", monospace;
  --font-size: larger;
}
```

Do you want a custom site but don't have the design chops? Visit our [automatic brand generator](https://printerscanner.github.io/automatic-brand-generator/) to have a brand made for you.

## Preview

![Screenshot](screenshot.png)

## Contributing

If you'd like to contribute to this repository feel free to fork/submit a pull request, and if you have any suggestions feel free to email me at abbeyyacoe@gmail.com.

## License

The theme is available as open source under the terms of the MIT License.
