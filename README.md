# Bootstrap Basics - Responsive Web Application

![Bootstrap](https://img.shields.io/badge/Bootstrap-5.3.2-purple)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)
![Responsive](https://img.shields.io/badge/Responsive-Yes-green)

A fully responsive web application demonstrating core Bootstrap concepts including forms, tables, navigation, and responsive utilities. This project showcases modern web development practices with Bootstrap's powerful CSS framework.

## 🚀 Live Demo

Open `index.html` in your browser to view the application.

## 📋 Overview

This project is part of the Coding Temple Software Engineering Bootcamp curriculum, designed to assess and demonstrate proficiency in Bootstrap fundamentals. The application features a complete user interface with form validation, data tables, responsive navigation, and mobile-first design principles.

## ✨ Features

### 🔐 User Registration System

- **Responsive Form Layout**: Side-by-side name fields using Bootstrap grid system
- **Form Validation**: Real-time validation for email and password fields
- **Professional Styling**: Clean, accessible form components with proper labeling

### 📊 Data Management

- **Interactive Table**: Displays user information with striped and hoverable rows
- **Responsive Design**: Table adapts to different screen sizes with horizontal scrolling
- **Sample Data**: Pre-populated with realistic user data for demonstration

### 🖼️ Visual Elements

- **Responsive Images**: Fluid images that scale with container width
- **Circular Profile Images**: Styled with Bootstrap's rounded-circle utility
- **Conditional Buttons**: Smart visibility controls based on screen size

### 🧭 Navigation

- **Collapsible Navbar**: Responsive navigation with hamburger menu for mobile
- **Brand Integration**: Logo placeholder with proper image handling
- **Accessible Links**: Well-structured navigation with proper ARIA labels

### 📱 Mobile-First Responsive Design

- **Breakpoint Management**: Optimized layouts for all device sizes
- **Touch-Friendly**: Properly sized interactive elements for mobile users
- **Performance Optimized**: Efficient CSS delivery via CDN

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and accessibility features
- **Bootstrap 5.3.2**: CSS framework for responsive design and components
- **CSS3**: Custom styling and responsive utilities
- **JavaScript**: Bootstrap's interactive components (via CDN)

## 🏗️ Project Structure

```
├── index.html          # Main application file
├── README.md           # Project documentation
└── assets/             # (Future: Custom assets)
```

## 🚀 Getting Started

### Prerequisites

- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection (for Bootstrap CDN)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/MArney86/CT_Knowledge_Check_Bootstrap_Basics_etc.git
   ```

2. **Navigate to project directory**
   ```bash
   cd CT_Knowledge_Check_Bootstrap_Basics_etc
   ```

3. **Open in browser**
   ```bash
   # Windows
   start index.html
   
   # macOS
   open index.html
   
   # Linux
   xdg-open index.html
   ```

## 📱 Responsive Breakpoints

| Device | Screen Size | Layout Changes |
|--------|-------------|----------------|
| Mobile | < 768px | Single column, hamburger menu, hidden secondary button |
| Tablet | 768px - 992px | Two-column forms, collapsed navigation |
| Desktop | > 992px | Full layout, all elements visible |

## 🎯 Key Implementation Details

### Form Validation

- Uses Bootstrap's built-in validation classes (`is-invalid`, `invalid-feedback`)
- Required field indicators for email and password
- Accessible error messaging

### Table Responsiveness

- Wrapped in `table-responsive-md` for medium breakpoint scrolling
- Striped rows (`table-striped`) for better readability
- Hover effects (`table-hover`) for interactive feedback

### Navigation Features

- Collapsible navigation with `navbar-toggler`
- Proper ARIA attributes for accessibility
- Active state management for current page

## 🎨 Bootstrap Components Used

- **Layout**: Containers, Grid System, Flexbox utilities
- **Forms**: Form controls, validation, labels
- **Tables**: Responsive tables, striped rows, borders
- **Navigation**: Navbar, collapse, toggler
- **Images**: Responsive images, rounded utilities
- **Buttons**: Button variants, responsive visibility
- **Utilities**: Spacing, display, text alignment

## 📚 Original Assignment Requirements

### Form Creation and Layout

- ✅ Bootstrap form components with First Name, Last Name, Email, Password fields
- ✅ Grid layout for side-by-side name fields
- ✅ Validation classes for required Email and Password fields
- ✅ Submit button styled with `btn-success`

### Table for Displaying Data

- ✅ Bootstrap table with hard-coded user data
- ✅ Striped and hoverable rows for enhanced readability
- ✅ Responsive table wrapper for mobile compatibility

### Image and Button Utilities

- ✅ Responsive image using `img-fluid` class in fluid container
- ✅ Circular image with `rounded-circle` utility
- ✅ Two buttons with responsive visibility controls

### Responsive Navigation Bar

- ✅ Navbar with Home, About, and Contact links
- ✅ Collapsible hamburger menu for smaller screens
- ✅ Bootstrap utilities and components for styling

### Responsiveness and Layout

- ✅ Bootstrap containers for proper structure
- ✅ Responsive design across all screen sizes
- ✅ Bootstrap utilities for responsive behavior

## 🤝 Contributing

This is an educational project, but suggestions and improvements are welcome:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/improvement`)
3. Commit your changes (`git commit -am 'Add improvement'`)
4. Push to the branch (`git push origin feature/improvement`)
5. Open a Pull Request

## 📄 License

This project is created for educational purposes as part of the Coding Temple curriculum.

## 👨‍💻 Author

**Coding Temple Student**
- GitHub: [@MArney86](https://github.com/MArney86)

## 🙏 Acknowledgments

- [Coding Temple](https://codingtemple.com/) for the comprehensive curriculum
- [Bootstrap Team](https://getbootstrap.com/) for the amazing framework
- [Placeholder Services](https://picsum.photos/) for demo images

---

*Built with ❤️ and Bootstrap 5*
