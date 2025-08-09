# SAIK Agriventure Website

A modern, responsive static website for SAIK Agriventure - showcasing sustainable agriculture solutions and innovation.

## 🌟 Features

- **Responsive Design**: Optimized for all devices (desktop, tablet, mobile)
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Fast Loading**: Static site optimized for performance
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Interactive Elements**: Smooth scrolling, mobile navigation, contact form
- **Accessible**: Built with accessibility best practices

## 🚀 Live Demo

The website is automatically deployed to GitHub Pages at: `https://sicrisembay.github.io/saik-agriventure/`

## 📁 Project Structure

```
saik-agriventure/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with Flexbox and Grid
- **JavaScript**: Interactive functionality
- **Google Fonts**: Inter font family for typography

## 📱 Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Core values and company overview
3. **Services Section**: Detailed service offerings
4. **Contact Section**: Contact information and form
5. **Footer**: Quick links and additional information

## 🚀 Deployment to GitHub Pages

### Automatic Deployment (Recommended)

1. Push your code to the `main` branch
2. Go to your repository settings on GitHub
3. Navigate to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose `main` branch and `/ (root)` folder
6. Click "Save"
7. Your site will be available at `https://yourusername.github.io/saik-agriventure/`

### Manual Deployment

1. Create a new branch called `gh-pages`:
   ```bash
   git checkout -b gh-pages
   git push origin gh-pages
   ```
2. In repository settings, set the Pages source to the `gh-pages` branch

## 🔧 Local Development

To run the website locally:

1. Clone the repository:
   ```bash
   git clone https://github.com/sicrisembay/saik-agriventure.git
   cd saik-agriventure
   ```

2. Open `index.html` in your web browser or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

3. Open `http://localhost:8000` in your browser

## 🎨 Customization

### Colors
The main color scheme can be customized in `styles.css`:
- Primary Green: `#4a7c59`
- Dark Green: `#2c5530`
- Light Green: `#a8d5ba`

### Content
- Update company information in `index.html`
- Modify contact details in the contact section
- Replace placeholder content with your actual content

### Styling
- All styles are in `styles.css`
- Mobile-first responsive design
- CSS Grid and Flexbox for layouts

## 📞 Contact Form

The contact form includes:
- Client-side validation
- Responsive design
- Success/error messaging
- Form reset after submission

**Note**: The form currently shows a demo message. To make it functional, you'll need to:
1. Set up a backend service (e.g., Netlify Forms, Formspree, EmailJS)
2. Update the form action in `script.js`

## 🔍 SEO Features

- Semantic HTML structure
- Meta description and keywords
- Proper heading hierarchy
- Alt tags for images (when added)
- Schema markup ready

## 📈 Performance

- Optimized CSS and JavaScript
- Minimal external dependencies
- Compressed images (when added)
- Efficient animations using CSS transforms

## 🌐 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- IE 11+ (with some limitations)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📞 Support

For questions or support, please contact:
- Email: info@saikagriventure.com
- GitHub Issues: [Create an issue](https://github.com/sicrisembay/saik-agriventure/issues)

---

**Built with ❤️ for sustainable agriculture innovation**
