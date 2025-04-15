# BinaryCSS

A lightweight, modern CSS framework I built for my own projects that's now ready to share with the world. Responsive, clean, and no unnecessary bloat.

![BinaryCSS Logo](docs/img/binary-logo.png)

## The Story Behind BinaryCSS

I got tired of using bloated CSS frameworks that took forever to load and came with a ton of stuff I never used. After complaining about this on Twitter for the 100th time, I finally decided to build my own framework during a two-week vacation. What started as a personal project has evolved into something I'm pretty proud of.

BinaryCSS focuses on what actually matters: performance, simplicity, and developer experience. I've been using it for my client projects for the past 8 months and it's been a huge time-saver.

## Features

- 🎨 **Clean design system** with consistent spacing and typography
- 📱 **Responsive 12-column grid** that actually makes sense
- 🧩 **Modular architecture** - only use what you need (I hate bloat!)
- 🔍 **Tiny footprint** (~15KB gzipped for everything)
- 🌙 **Dark mode support** because who doesn't love dark mode?
- 🧰 **Utility classes** for those times when you just need to add a quick fix
- ♿ **Accessibility** wasn't an afterthought - I built it in from day one
- 🚀 **Simple API** that won't make you read docs for hours

## Installation

Getting BinaryCSS into your project is super easy:

### Option a) Just Download It

[Grab the latest release](https://github.com/Deepakdumka1/css-framework/releases) and drop it into your project:

```html
<!-- CSS -->
<link rel="stylesheet" href="path/to/binary.css">

<!-- JS (only if you need the interactive components) -->
<script src="path/to/quantum.js"></script>
```

### Option b) NPM (my preferred way)

```bash
npm install @deepakdumka/BinaryCSS --save
```

Then import it:

```javascript
// Get everything
import '@deepakdumka/BinaryCSS/css/binary.css';

// JS components if you need them
import '@deepakdumka/BinaryCSS/js/binary.js';

// Or cherry-pick just what you need
import '@deepakdumka/BinaryCSS/css/binary-base.css';
import '@deepakdumka/BinaryCSS/css/binary-grid.css';
// etc...
```

### Option c) CDN (still working on this!)

I'm still setting up a proper CDN. For now, just use one of the options above. Will update soon!

## Quick Example

Here's how a simple BinaryCSS page looks:

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My BinaryCSS Project</title>
  <link rel="stylesheet" href="path/to/binary.css">
</head>
<body>
  <div class="container">
    <div class="row mt-4">
      <div class="col-sm-12 col-md-6">
        <div class="card">
          <div class="card-body">
            <h3 class="card-title">Getting Started</h3>
            <p>This is a simple card built with BinaryCSS.</p>
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

The docs are a work in progress (aren't they always?), but you can find what we have so far here:
[documentation](https://Deepakdumka1.github.io/css-framework/docs/)

- [Grid System](https://Deepakdumka1.github.io/css-framework/docs/#grid-system) - my favorite part!
- [Typography](https://Deepakdumka1.github.io/css-framework/docs/#typography)
- [Components](https://Deepakdumka1.github.io/css-framework/docs/#components)
- [Utilities](https://Deepakdumka1.github.io/css-framework/docs/#utilities)

## Components

I've included the components I use most often:

- **Buttons** - Standard, outline, and various sizes (no weird 3D effects, I promise)
- **Cards** - Simple but flexible containers
- **Forms** - Inputs, checkboxes, and basic validation
- **Navigation** - Navbar and tabs that don't break on mobile
- **Alerts** - For when you need to tell users something important
- **And more!** (I'm adding new ones as I need them)

## Customization

The whole framework uses CSS variables, so customizing is as easy as:

```css
:root {
  /* Your brand colors here */
  --q-primary: #3366ff;    /* my personal favorite blue */
  --q-secondary: #6c5ce7;
  --q-success: #00b894;    /* not too bright green */
  --q-danger: #ff5252;
  --q-warning: #fdcb6e;
  --q-light: #f8f9fa;
  --q-dark: #212529;
}
```

## Browser Support

Works in all modern browsers. IE? Sorry, I don't support dinosaurs.

- Chrome
- Firefox
- Safari
- Edge
- Opera

## Known Issues & Roadmap

- [ ] Mobile nav still has some quirks in Safari (working on it!)
- [ ] Need to improve keyboard navigation in dropdowns
- [ ] Planning to add a toast notification system in the next version
- [ ] Better theme customization tools

## Contributing

I'd love some help making this better! If you have ideas:

1. Fork the repo
2. Create your feature branch: `git checkout -b feature/your-awesome-idea`
3. Make some changes
4. Push to your branch: `git push origin feature/your-awesome-idea`
5. Open a PR and let's talk about it!

## License

MIT License - do what you want with it, just don't blame me if something breaks!
