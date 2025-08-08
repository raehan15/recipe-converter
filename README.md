# Recipe Converter

A modern, responsive recipe scaling web app that helps you scale recipe ingredients up or down with intelligent fraction handling and a beautiful user interface.

## 🌟 Features

- **Smart Ingredient Scaling**: Scale recipes up or down with intelligent fraction and decimal handling
- **Fraction Support**: Handles Unicode fractions (½, ⅓, ¼), mixed numbers (1 1/2), and ranges
- **Beautiful UI**: Built with Tailwind CSS featuring smooth animations and modern design
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Accessibility**: WCAG compliant with proper ARIA labels and keyboard navigation
- **SEO Optimized**: Meta tags, Open Graph, Twitter Cards, and Schema.org markup
- **No Dependencies**: Pure HTML, CSS, and JavaScript - no build process required

## 🚀 Live Demo

Visit the live app: [Recipe Converter](https://raehan15.github.io/recipe-converter)

## 🛠️ Usage

1. Enter your recipe ingredients in the text area (one per line)
2. Specify your desired scaling factor (e.g., 2 for double, 0.5 for half)
3. Click "Scale Recipe" to get your adjusted ingredients
4. Copy the results or use them directly in your cooking

### Supported Formats

- Simple numbers: `2 cups flour`
- Fractions: `1/2 cup sugar`
- Mixed numbers: `1 1/2 cups milk`
- Unicode fractions: `½ cup butter`
- Ranges: `2-3 cloves garlic`
- Decimals: `1.5 tsp vanilla`

## 🏗️ Local Development

1. Clone the repository:

   ```bash
   git clone https://github.com/raehan15/recipe-converter.git
   cd recipe-converter
   ```

2. Open `index.html` in your browser or serve with a local server:

   ```bash
   # Using Python 3
   python -m http.server 8000

   # Using Node.js (if you have http-server installed)
   npx http-server
   ```

3. Navigate to `http://localhost:8000` in your browser

## 📁 Project Structure

```
recipe-converter/
├── index.html          # Main application page
├── about.html          # About page
├── contact.html        # Contact page
├── privacy.html        # Privacy policy page
└── README.md          # Project documentation
```

## 🎨 Technologies Used

- **HTML5**: Semantic markup with accessibility in mind
- **Tailwind CSS**: Utility-first CSS framework via CDN
- **Vanilla JavaScript**: No frameworks, pure JS for performance
- **Inter Font**: Modern, readable typography
- **GitHub Pages**: Free hosting for static sites

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

For questions or feedback, reach out to: convertrecipe@gmail.com

## 🙏 Acknowledgments

- Built with [Tailwind CSS](https://tailwindcss.com/)
- Icons and design inspiration from modern web design principles
- Hosted on [GitHub Pages](https://pages.github.com/)
