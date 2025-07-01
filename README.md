# Javari Whilby - Portfolio Website

A modern, interactive portfolio website showcasing software engineering projects and skills. Built with vanilla HTML, CSS, and JavaScript, featuring a unique 3D rotating project carousel and smooth animations.

## Features

### Interactive 3D Project Carousel
- **4 Featured Projects** displayed in a rotating 3D carousel
- **Hover to Pause**: Animation stops when hovering over projects
- **Click to Visit**: Direct links to project repositories/demos
- **Project Overlays**: Detailed information appears on hover

### Responsive Navigation
- **Fixed Navigation Bar** with smooth scrolling
- **Active Section Highlighting** based on scroll position
- **Mobile-Friendly** collapsible design
- **JW Logo** branding

### Comprehensive Sections
- **Home**: Hero section with rotating project showcase
- **Projects**: Detailed project cards with technology stacks
- **About Me**: Personal introduction and achievement statistics
- **Proficiencies**: Animated skill bars for technical competencies
- **Contact**: Professional contact form and information

### Visual Design
- **Consistent Theme**: Dark blue (#25283B) and light gray (#D2D2D2) palette
- **Grid Background**: Subtle repeating pattern overlay
- **Custom Typography**: ICA Rubrik for headings, Poppins for body text
- **Smooth Animations**: CSS transitions and keyframe animations
- **Glassmorphism Effects**: Modern backdrop filters and transparency

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Advanced styling with CSS Grid, Flexbox, and animations
- **Vanilla JavaScript**: Interactive functionality and DOM manipulation
- **Custom Fonts**: Google Fonts integration
- **Responsive Design**: Mobile-first approach

## 📁 Project Structure

```
/
├── index.html          # Main HTML file with complete portfolio structure
├── style.css           # Comprehensive styling with animations and responsive design
├── README.md           # Project documentation (this file)
├── images/            # Image assets directory
│   ├── bg.png         # Background pattern image
│   ├── dragon_1.jpg   # Project showcase image 1 (E-Commerce Platform)
│   ├── dragon_2.jpg   # Project showcase image 2 (Task Management App)
│   ├── dragon_3.jpg   # Project showcase image 3 (Weather Dashboard)
│   ├── dragon_4.jpg   # Project showcase image 4 (Social Media Clone)
│   └── model.png      # Additional model/avatar image
```

## 🎯 Key Components

### 1. Navigation System
- Fixed-position navbar with smooth scroll navigation
- Active section highlighting
- Responsive design for mobile devices

### 2. 3D Project Carousel
- CSS 3D transforms creating a rotating cylinder effect
- 4 project showcases with hover interactions
- Pause animation on mouse hover
- Click functionality to visit project links

### 3. Skill Proficiency Bars
- Animated progress bars using CSS transitions
- Intersection Observer API for scroll-triggered animations
- Categorized by Frontend, Backend, and Database/Tools

### 4. Contact Form
- Styled form inputs with focus states
- Grid layout for contact information
- Professional design with gradient backgrounds

## 🚀 Getting Started

1. **Clone or download** the repository
2. **Open `index.html`** in a web browser
3. **Customize content**:
   - Update project links in the `data-link` attributes
   - Replace project images in the `/images` directory
   - Modify contact information
   - Adjust skill percentages in the proficiencies section

## 📱 Responsive Breakpoints

- **Desktop**: 1024px and above
- **Tablet**: 768px - 1023px
- **Mobile**: 767px and below

## 🎨 Color Palette

- **Primary Dark**: #25283B (Navigation, headings, accents)
- **Primary Light**: #D2D2D2 (Background, secondary text)
- **Background**: Linear gradients between primary colors
- **Accent**: Various shades of the primary palette

## ⚡ Performance Features

- **Smooth Scrolling**: CSS and JavaScript scroll behavior
- **Optimized Animations**: Hardware-accelerated CSS transforms
- **Lazy Loading**: Intersection Observer for skill bar animations
- **Responsive Images**: Optimized for different screen sizes

## 🔧 Customization

### Adding New Projects
1. Add project item to the carousel in `index.html`
2. Create corresponding project card in the projects section
3. Update the `--quantity` CSS variable to match project count
4. Add project image to `/images` directory

### Modifying Skills
1. Update skill items in the proficiencies section
2. Adjust `data-width` attributes for skill progress bars
3. Modify skill categories as needed

### Contact Information
1. Update contact details in the contact section
2. Modify form action attribute for form submission
3. Add social media links as needed

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 👨‍💻 Author

**Javari Whilby**
- Software Engineering Student
- Passionate about creating innovative web solutions

---

