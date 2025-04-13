# QuantumCSS

A lightweight, modern CSS framework for building beautiful, responsive websites with minimal effort.

![QuantumCSS Logo](docs/img/quantum-logo.png)

## What is QuantumCSS?

QuantumCSS is a fresh approach to CSS frameworks that focuses on simplicity, performance, and developer experience. I built it to solve common UI challenges without the bloat of larger frameworks.

## Features

- 🎨 **Clean design system** with consistent spacing and typography
- 📱 **Responsive 12-column grid** that works beautifully on all devices
- 🧩 **Modular architecture** - use only what you need
- 🔍 **Tiny footprint** (~15KB gzipped for the full framework)
- 🌙 **Dark mode support** built right in
- 🧰 **Utility classes** for rapid development
- ♿ **Accessibility-focused** with proper contrast and semantic markup
- 🚀 **Simple, intuitive API** that's easy to learn

## Installation

Getting started with QuantumCSS is super easy:

### Option 1: Direct Download

[Download the latest release](https://github.com/Deepakdumka1/css-framework/releases) and include it in your project:

```html
<!-- CSS -->
<link rel="stylesheet" href="path/to/quantum.css">

<!-- Optional JavaScript -->
<script src="path/to/quantum.js"></script>
```

### Option 2: NPM

```bash
npm install @deepakdumka/quantumcss --save
```

Then import in your project:

```javascript
// Import all styles
import '@deepakdumka/quantumcss/css/quantum.css';

// Optional JavaScript
import '@deepakdumka/quantumcss/js/quantum.js';

// Or import individual modules
import '@deepakdumka/quantumcss/css/quantum-base.css';
import '@deepakdumka/quantumcss/css/quantum-grid.css';
// etc...
```

### Option 3: CDN (Coming Soon)

```html
<!-- CSS -->
<link rel="stylesheet" href="https://cdn.example.com/quantumcss/0.1.0/quantum.min.css">

<!-- Optional JavaScript -->
<script src="https://cdn.example.com/quantumcss/0.1.0/quantum.min.js"></script>
```

## Quick Start

Here's a simple example to get you going:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My QuantumCSS Project</title>
  <link rel="stylesheet" href="path/to/quantum.css">
</head>
<body>
  <div class="container">
    <div class="row mt-4">
      <div class="col-sm-12 col-md-6">
        <div class="card">
          <div class="card-body">
            <h3 class="card-title">Getting Started</h3>
            <p>This is a simple card built with QuantumCSS.</p>
            <button class="btn btn-primary">Learn More</button>
          </div>
        </div>
      </div>
      
      <div class="col-sm-12 col-md-6">
        <div class="card">
          <div class="card-body">
            <h3 class="card-title">Responsive Design</h3>
            <p>Cards stack on mobile and display side-by-side on larger screens.</p>
            <button class="btn btn-secondary">See Examples</button>
          </div>
        </div>
      </div>
    </div>
  </div>
  
  <script src="path/to/quantum.js"></script>
</body>
</html>
```

## Documentation

Check out our [documentation](https://Deepakdumka1.github.io/css-framework/docs/) for detailed guides and examples:

- [Grid System](https://Deepakdumka1.github.io/css-framework/docs/#grid-system)
- [Typography](https://Deepakdumka1.github.io/css-framework/docs/#typography)
- [Components](https://Deepakdumka1.github.io/css-framework/docs/#components)
- [Utilities](https://Deepakdumka1.github.io/css-framework/docs/#utilities)

## Components

QuantumCSS includes essential components to jumpstart your projects:

- **Buttons** - Standard, outline, and various sizes
- **Cards** - Flexible containers for content
- **Forms** - Styled inputs, checkboxes, and validation
- **Navigation** - Responsive navbar and tabs
- **Alerts** - Contextual feedback messages
- **And more!**

## Customization

Make QuantumCSS your own by customizing the CSS variables:

```css
:root {
  --q-primary: #3366ff;
  --q-secondary: #6c5ce7;
  --q-success: #00b894;
  --q-danger: #ff5252;
  --q-warning: #fdcb6e;
  --q-light: #f8f9fa;
  --q-dark: #212529;
}
```

## Browser Support

QuantumCSS works in all modern browsers:

- Chrome
- Firefox
- Safari
- Edge
- Opera

## Contributing

I'd love your help making QuantumCSS better! Feel free to:

1. Fork the repository
2. Create your feature branch: `git checkout -b feature/cool-new-feature`
3. Commit your changes: `git commit -m 'Add some cool feature'`
4. Push to the branch: `git push origin feature/cool-new-feature`
5. Open a Pull Request

## License

QuantumCSS is released under the [MIT License](LICENSE).
