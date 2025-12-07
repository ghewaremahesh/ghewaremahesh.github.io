# Mahesh Gheware - Professional Portfolio

A modern, responsive portfolio website built with HTML, CSS, and JavaScript. This site showcases professional experience, skills, projects, and contact information.

## 🚀 Live Demo

Visit the live portfolio at: https://ghewaremahesh.github.io

## 📋 Features

- **Responsive Design**: Fully responsive layout that works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional design with smooth animations
- **Navigation**: Sticky navbar with smooth scrolling to sections
- **Hero Section**: Eye-catching introduction with call-to-action buttons
- **About Section**: Personal introduction and professional summary
- **Experience Timeline**: Detailed professional work experience
- **Skills Grid**: Organized skill categories with technology tags
- **Projects Showcase**: Featured projects with descriptions and technology stacks
- **Contact Section**: Multiple ways to get in touch
- **Mobile Menu**: Hamburger menu for mobile devices
- **Animations**: Smooth scroll animations and hover effects

## 📁 Project Structure

```
ghewaremahesh.github.io/
├── index.html           # Main HTML file
├── styles.css           # Styling and responsive design
├── script.js            # JavaScript for interactivity
├── _config.yml          # GitHub Pages configuration
├── .nojekyll            # Skip Jekyll processing
└── README.md            # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript**: DOM manipulation and animations
- **Font Awesome**: Icons for social links and contact methods
- **GitHub Pages**: Hosting and deployment

## 📝 How to Customize

### 1. Update Your Information

Edit `index.html` to customize:
- Name and job title in the hero section
- About section content
- Experience entries with your actual work history
- Skills and technology tags
- Project details and links
- Contact information and email

### 2. Change Colors

Edit the CSS variables at the top of `styles.css`:
```css
:root {
    --primary-color: #0066cc;
    --primary-dark: #0052a3;
    --secondary-color: #f0f0f0;
    /* ... more variables ... */
}
```

### 3. Add Your Social Links

In `index.html`, update the social links section with your actual profiles:
```html
<a href="https://linkedin.com/in/your-profile/" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
```

### 4. Update Contact Email

Change the email in the contact section and footer to your actual email address.

## 🚀 Deployment

This portfolio is already set up for GitHub Pages:

1. Push your changes to the `main` branch
2. GitHub will automatically deploy your site
3. Visit `https://github.com-username.github.io` to view your portfolio

### Local Testing

To test locally:

```bash
# Option 1: Using Python's built-in server
python -m http.server 8000

# Option 2: Using Node.js http-server
npx http-server

# Then open: http://localhost:8000
```

## 🎨 Customization Tips

- **Hero Gradient**: Modify the gradient in `.hero` class in `styles.css`
- **Add Projects**: Duplicate the `.project-card` div in the projects section
- **Add Skills**: Add new `.skill-category` sections for different skill types
- **Add Experience**: Duplicate the `.experience-item` div in the experience section

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔗 SEO & Meta Tags

The portfolio includes:
- Semantic HTML5 markup
- Meta viewport for mobile responsiveness
- Open Graph meta tags ready to be added
- Structured for SEO optimization

## 📄 License

This portfolio template is free to use and modify for personal or commercial purposes.

## 👤 Contact

- **LinkedIn**: https://linkedin.com/in/mahesh-gheware-4b8aa827b/
- **Email**: contact@example.com
- **Portfolio**: https://ghewaremahesh.github.io

---

Built with ♥ and hosted on GitHub Pages