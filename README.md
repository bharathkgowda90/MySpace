# Principal Product Designer Portfolio

A modern, responsive portfolio website showcasing design work, case studies, and expertise of a Principal Product Designer.

## 🎨 Overview

This portfolio website is designed to present product design work in a clean, professional, and engaging manner. It features a modern design aesthetic with smooth animations, comprehensive case studies, and a focus on user experience.

## ✨ Features

- **Responsive Design**: Fully responsive layout that works seamlessly across desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, contemporary design with smooth animations and transitions
- **Project Showcase**: Featured projects with detailed case studies
- **About Section**: Professional bio, expertise areas, and work experience
- **Design Process**: Clear visualization of the design methodology
- **Contact Section**: Easy-to-find contact information and social links
- **Case Study Template**: Detailed project page template for comprehensive case studies
- **Accessibility**: Built with accessibility best practices in mind
- **Performance Optimized**: Fast loading times and optimized assets

## 🚀 Quick Start

1. Clone the repository:
   ```bash
   git clone <repository-url>
   ```

2. Open `index.html` in your web browser to view the portfolio

3. For local development with live reload, you can use any local server:
   ```bash
   # Using Python
   python -m http.server 8000

   # Using Node.js http-server
   npx http-server

   # Using PHP
   php -S localhost:8000
   ```

4. Visit `http://localhost:8000` in your browser

## 📁 Project Structure

```
portfolio/
├── index.html              # Main portfolio page
├── project-template.html   # Case study template
├── css/
│   ├── styles.css          # Main stylesheet
│   └── project.css         # Case study page styles
├── js/
│   └── script.js           # Interactive functionality
├── images/                 # Image assets (add your own)
└── README.md              # This file
```

## 🎯 Customization

### Update Personal Information

1. **Hero Section** (`index.html` lines 32-48):
   - Update the hero title and subtitle
   - Modify the tagline to reflect your specialty

2. **About Section** (`index.html` lines 173-247):
   - Replace bio text with your own story
   - Update expertise areas
   - Modify work experience

3. **Projects** (`index.html` lines 52-171):
   - Replace project descriptions
   - Update metrics and outcomes
   - Add your own project images
   - Link to detailed case studies

4. **Contact Information** (`index.html` lines 309-329):
   - Update email address
   - Add your social media links
   - Modify contact methods

### Add Your Projects

1. Duplicate a project card section in `index.html`
2. Update project details:
   - Project title and description
   - Project category/tag
   - Key highlights and metrics
   - Technology tags
   - Link to case study

3. For detailed case studies, use `project-template.html` as a starting point

### Customize Colors

Update CSS variables in `css/styles.css` (lines 13-18):

```css
:root {
    --primary-color: #2d3748;
    --accent-color: #667eea;
    /* Modify other color variables */
}
```

### Add Images

1. Create folders in `images/` directory:
   ```
   images/
   ├── projects/
   ├── profile/
   └── case-studies/
   ```

2. Replace placeholder images with your actual images
3. Update image paths in HTML files

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6+)**: Interactive functionality
- **Google Fonts**: Inter and Playfair Display
- **CSS Custom Properties**: Easy theming
- **Intersection Observer API**: Scroll animations
- **Responsive Design**: Mobile-first approach

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🎨 Design Features

- **Typography**: Combination of Inter (body) and Playfair Display (headings)
- **Color Scheme**: Purple gradient accent colors with neutral base
- **Layout**: CSS Grid and Flexbox for modern layouts
- **Animations**: Subtle fade-in effects and smooth transitions
- **Icons**: Using emoji for visual interest (can be replaced with icon library)

## 📝 Content Guidelines

### Writing Case Studies

1. **Overview**: Brief project summary and context
2. **Challenge**: Problem you were solving
3. **Research**: Methods and insights
4. **Solution**: Your design approach
5. **Impact**: Metrics and outcomes
6. **Learnings**: Key takeaways

### Project Descriptions

- Focus on impact and outcomes
- Include specific metrics when possible
- Highlight your role and contributions
- Keep descriptions concise but informative

## 🚀 Deployment

### GitHub Pages

1. Push your code to GitHub
2. Go to repository Settings → Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Configure build settings (none needed for static site)
3. Deploy automatically on push

### Vercel

1. Import your GitHub repository in Vercel
2. No configuration needed
3. Auto-deploy on push

## 📄 License

This portfolio template is free to use for personal and commercial projects.

## 🤝 Contributing

Feel free to fork this project and customize it for your own use. If you have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

For questions or issues, please open an issue in the repository.

---

**Built with ❤️ for Product Designers**