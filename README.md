# Great World Academy - Course Selling Website

A modern, responsive course selling website built with vanilla HTML, CSS, and JavaScript. The website showcases an online learning platform offering various programming and technology courses.

![Website Preview](https://img.shields.io/badge/Status-Live-brightgreen)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)

## 🚀 Features

- **Responsive Design**: Mobile-first approach that works seamlessly across all devices
- **Modern UI/UX**: Clean, professional design with smooth gradients and animations
- **Course Catalog**: Dynamic course grid populated via JavaScript
- **Interactive Elements**: Contact form, enrollment buttons, and navigation
- **SEO Friendly**: Properly structured HTML with semantic elements
- **Fast Loading**: Lightweight vanilla JavaScript implementation

## 📚 Courses Offered

The platform currently features 6 courses:

1. **Web Development: From Zero to Deployed** - ₹1,499 (8 weeks)
2. **Python for Data** - ₹1,299 (6 weeks)  
3. **React Bootcamp** - ₹1,699 (6 weeks)
4. **Design Systems** - ₹999 (4 weeks)
5. **DevOps Basics** - ₹1,199 (5 weeks)
6. **Portfolio Projects** - Free (4 weeks)

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and modern HTML features
- **CSS3**: Custom styling with flexbox, grid, and animations
- **JavaScript (ES6+)**: Dynamic content generation and user interactions
- **Vercel**: Deployment and hosting configuration

## 📁 Project Structure

```
Web-test/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── vercel.json         # Vercel deployment configuration
└── README.md           # Project documentation
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser
- Basic text editor (VS Code recommended)
- Node.js (optional, for development server)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/shivangupadhyy/Web-test.git
   cd Web-test
   ```

2. **Open locally**
   - Simply open `index.html` in your web browser, or
   - Use a local development server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (http-server)
   npx http-server
   
   # Using VS Code Live Server extension
   ```

3. **View in browser**
   - Navigate to `http://localhost:8000` (or the port shown)

## 🌐 Live Demo

The website is deployed and can be viewed at: [Your Vercel URL]

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px  
- **Desktop**: > 1024px

## ✨ Key Sections

### Header & Navigation
- Brand logo with "Great World Academy"
- Responsive navigation menu
- Call-to-action button

### Hero Section
- Compelling headline and description
- Featured course showcase
- Action buttons for browsing courses

### Courses Grid
- Dynamically generated course cards
- Course details including price and duration
- Interactive enrollment buttons

### Contact Section  
- Contact form with validation
- Company information
- Social media links

### Footer
- Copyright information
- Year auto-update

## 🔧 Customization

### Adding New Courses
Edit the `courses` array in the JavaScript section of `index.html`:

```javascript
const courses = [
  { 
    title: 'Course Title', 
    sub: 'Short description', 
    price: '₹999', 
    duration: '4 weeks', 
    long: 'Detailed description of the course content.' 
  }
];
```

### Styling Changes
Modify `styles.css` to update:
- Color scheme and branding
- Typography and spacing
- Layout and responsive behavior

### Content Updates
Update `index.html` to change:
- Company name and branding
- Text content and descriptions
- Contact information

## 📊 Performance

- **Lightweight**: No external dependencies or frameworks
- **Fast Load Time**: Optimized vanilla implementation
- **SEO Optimized**: Semantic HTML structure
- **Accessible**: Proper ARIA attributes and keyboard navigation

## 🚀 Deployment

### Vercel (Recommended)
The project includes `vercel.json` configuration:

```bash
vercel --prod
```

### Other Platforms
- **Netlify**: Drag and drop the project folder
- **GitHub Pages**: Push to GitHub and enable Pages
- **Traditional Hosting**: Upload files via FTP

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support or questions:
- **Email**: Contact through the website form
- **Location**: Hyderabad, India
- **Social**: Follow us on Twitter, LinkedIn, and YouTube

## 🎯 Future Enhancements

- [ ] User authentication and login system
- [ ] Payment gateway integration
- [ ] Course progress tracking
- [ ] Video content integration
- [ ] Mobile app development
- [ ] Advanced search and filtering
- [ ] User reviews and ratings

---

**Made with ♥ by Great World Academy Team**

*Learn. Build. Ship.*