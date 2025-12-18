# 🌴 PamaTravel - Travel Agency Demo Website

<div align="center">

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)

**A modern, responsive travel agency website template built with HTML, CSS, and JavaScript**

[Features](#-features) • [Demo](#-demo) • [Installation](#-installation) • [Usage](#-usage) • [Project Structure](#-project-structure) • [Technologies](#-technologies) • [License](#-license)

</div>

---

## 📖 About

**PamaTravel** is a beautifully designed, fully responsive travel agency demo website. It showcases a modern UI/UX with smooth animations, interactive components, and a professional layout perfect for travel businesses. The website features travel packages, booking systems, destination galleries, and more.

### ✨ Key Highlights

- 🎨 **Modern & Beautiful Design** - Clean, professional interface with smooth animations
- 📱 **Fully Responsive** - Works seamlessly on desktop, tablet, and mobile devices
- ⚡ **Fast & Lightweight** - Optimized for performance
- 🎯 **User-Friendly** - Intuitive navigation and booking system
- 🌍 **Multi-Page Website** - Complete travel agency website structure

---

## 🚀 Features

### Core Features

- **🏠 Homepage** - Hero section with search functionality
- **📋 About Us** - Company information and services overview
- **🎯 Services** - Travel services showcase
  - Thailand Tours
  - Hotel Reservations
  - Travel Guides
  - Event Management
- **🌏 Destinations** - Popular travel destinations gallery
- **📦 Travel Packages** - Featured travel packages with pricing
- **📅 Online Booking** - Interactive booking form
- **👥 Travel Guides** - Team members showcase
- **💬 Testimonials** - Customer reviews carousel
- **📞 Contact** - Contact information and form

### Design Features

- ✨ Smooth scroll animations (WOW.js)
- 🎭 Interactive carousels (Owl Carousel)
- 📅 Date picker integration
- 🎨 Custom Bootstrap styling
- 🌈 Beautiful color scheme
- 📐 Professional typography

---

## 🎬 Demo

### Screenshots

The website includes multiple pages:
- **Home** (`index.html`) - Main landing page
- **About** (`about.html`) - About us page
- **Services** (`service.html`) - Services overview
- **Packages** (`package.html`) - Travel packages
- **Destination** (`destination.html`) - Destinations gallery
- **Booking** (`booking.html`) - Booking page
- **Contact** (`contact.html`) - Contact page
- **Team** (`team.html`) - Travel guides
- **Testimonial** (`testimonial.html`) - Customer reviews

---

## 📦 Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A local web server (optional, for development)

### Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/Pa-ma-Travel_Demo_website.git
   cd Pa-ma-Travel_Demo_website
   ```

2. **Open in browser**
   - Simply open `index.html` in your web browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (http-server)
     npx http-server
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Access the website**
   - Navigate to `http://localhost:8000` (or the port you specified)

---

## 💻 Usage

### Basic Usage

1. Open `index.html` in your web browser
2. Navigate through different pages using the navigation menu
3. Explore the features:
   - Browse travel packages
   - View destinations
   - Use the booking form
   - Check testimonials

### Customization

#### Changing Colors
Edit `css/style.css` to customize the color scheme:
```css
:root {
    --primary-color: #FF6B35; /* Change primary color */
    --secondary-color: #004E89; /* Change secondary color */
}
```

#### Updating Content
- Edit HTML files directly to change text content
- Replace images in the `img/` folder
- Modify `js/main.js` for custom JavaScript functionality

#### Adding New Pages
1. Create a new HTML file
2. Copy the structure from existing pages
3. Update navigation links in all pages

---

## 📁 Project Structure

```
Pa-ma-Travel_Demo_website/
│
├── 📄 index.html              # Main homepage
├── 📄 about.html              # About page
├── 📄 service.html            # Services page
├── 📄 package.html            # Packages page
├── 📄 destination.html        # Destinations page
├── 📄 booking.html            # Booking page
├── 📄 contact.html            # Contact page
├── 📄 team.html               # Team/Guides page
├── 📄 testimonial.html        # Testimonials page
├── 📄 404.html                # 404 error page
│
├── 📁 css/
│   ├── bootstrap.min.css      # Bootstrap framework
│   └── style.css              # Custom styles
│
├── 📁 js/
│   └── main.js                # Main JavaScript file
│
├── 📁 lib/                    # Third-party libraries
│   ├── animate/               # WOW.js animations
│   ├── easing/                # Easing functions
│   ├── owlcarousel/           # Carousel library
│   ├── tempusdominus/         # Date picker
│   ├── waypoints/             # Scroll waypoints
│   └── wow/                   # WOW.js library
│
└── 📁 img/                    # Images and assets
    ├── logo.png
    ├── about.jpg
    ├── destination-*.jpg
    ├── package-*.jpg
    ├── team-*.jpg
    └── testimonial-*.jpg
```

---

## 🛠️ Technologies

### Frontend Technologies

- **HTML5** - Structure and markup
- **CSS3** - Styling and animations
- **JavaScript (ES6+)** - Interactivity and functionality
- **Bootstrap 5** - Responsive framework
- **jQuery** - DOM manipulation

### Libraries & Plugins

- **WOW.js** - Scroll animations
- **Owl Carousel** - Image/testimonial carousels
- **Font Awesome** - Icons
- **Bootstrap Icons** - Additional icons
- **Tempus Dominus** - Date/time picker
- **Google Fonts** - Typography (Playfair Display, Dancing Script, etc.)

---

## 🎨 Design Features

- **Responsive Grid System** - Bootstrap-based layout
- **Modern Typography** - Google Fonts integration
- **Smooth Animations** - WOW.js scroll animations
- **Interactive Elements** - Hover effects, transitions
- **Professional Color Scheme** - Primary blue theme
- **Image Galleries** - Responsive image displays
- **Form Styling** - Beautiful form inputs and buttons

---

## 📝 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Opera (latest)

---

## 🤝 Contributing

Contributions are welcome! If you'd like to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Developer

**DevTeam**
- GitHub: [@MrPatchara](https://github.com/MrPatchara)

---

## 📧 Contact

**PamaTravel**
- 📍 Address: 66 Soi Borpla LatPhrao101 Rd. KhlongChan BangKapi 10240 Bangkok, Thailand
- 📞 Phone: +012 345 6789
- ✉️ Email: Contact@pamatravel.com

---

## 🙏 Acknowledgments

- Bootstrap team for the amazing framework
- All contributors and open-source libraries used
- Design inspiration from modern travel websites

---

<div align="center">

**⭐ If you like this project, give it a star! ⭐**

Made with ❤️ by DevTeam

</div>

