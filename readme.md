# Fundsroom Website

A modern, responsive real estate website built with HTML, CSS, and JavaScript. This project showcases property listings, services, and provides a comprehensive platform for real estate business operations.

## 📋 Project Overview

This website has been standardized and restructured to provide a clean, professional interface for a real estate business. The site includes five main pages with integrated analytics and contact functionality.

## 🏗️ Project Structure

```
├── css/                    # Stylesheets
├── dashboard/              # Dashboard components
├── fonts/                  # Custom fonts
├── images/                 # Image assets
├── inc/                    # Include files
├── js/                     # JavaScript files
├── scss/                   # SASS stylesheets
├── vendor/                 # Third-party libraries
├── index-3.html           # Home page
├── about_us_01.html       # About Us page
├── service_01.html        # Services page
├── service_details.html   # Service details page
├── blog_03.html           # Blog page
└── contact.html           # Contact page
```

## 📄 Main Pages

1. **Home** (`index-3.html`) - Landing page with featured properties and services
2. **About Us** (`about_us_01.html`) - Company information and team details
3. **Services** (`service_01.html`) - Overview of real estate services offered
   - Redirects to `service_details.html` for detailed service information
4. **Blog** (`blog_03.html`) - Real estate news, tips, and articles
5. **Contact** (`contact.html`) - Contact form and location information

## ✨ Key Features

### Analytics Integration
- Google Analytics (gtag) script integrated across all pages
- Track user interactions and page visits
- Monitor website performance and user behavior

### Contact Functionality
- Functional contact form on the contact page
- Custom contact script implemented
- Successfully sends messages to designated recipients
- Located after the gtag script for proper tracking

### Customization
- **Updated Logo**: Custom Fundsroom branding implemented
- **Location Update**: Contact page features Fundsroom's actual location for accurate business representation
- **Responsive Design**: Mobile-friendly layout across all pages

### Service Details
- Interactive service navigation
- Detailed service information page (`service_details.html`)
- Seamless redirection from main services page

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, or Edge)
- A local web server (optional, for development)

## 📧 Contact Form Setup

The contact form is fully functional and includes:
- Name field
- Email field
- Message textarea
- Form validation
- Submission handling

Messages are successfully sent to the configured email address.

## 🔧 Technologies Used

- **HTML5** - Structure and content
- **CSS3** - Styling and animations
- **JavaScript** - Interactive functionality
- **SCSS** - Advanced styling with preprocessor
- **Google Analytics** - Website tracking and analytics
- **Responsive Design** - Mobile-first approach

## 📱 Responsive Design

The website is fully responsive and optimized for:
- Desktop computers (1920px and above)
- Laptops (1024px - 1919px)
- Tablets (768px - 1023px)
- Mobile devices (320px - 767px)

## 🎨 Customization

### Updating the Logo
The logo can be updated by replacing the image file in the `images/` directory and updating the reference in the HTML files.

### Modifying Contact Information
Update the location and contact details in `contact.html` to reflect your business information.

### Analytics Configuration
Replace the Google Analytics tracking ID in the gtag script with your own tracking ID.

## 📂 File Organization

The project follows a clean, organized structure:
- **Assets** are separated into logical folders (css, js, images, fonts)
- **Pages** are at the root level for easy access
- **Vendor files** are isolated in their own directory
- **SCSS files** are maintained for easier style management

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 👥 Authors

- **Ananyaa Gupta**
- **Rahul**
- **Shreya Talod**

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Thanks to all contributors who helped standardize and improve the website
- Special thanks to the session instructors for guidance on implementation
- Google Analytics for tracking capabilities

## 📞 Support

For support, please contact us through the contact form on the website or reach out to the development team.

**Note**: Ensure that all scripts and external dependencies are properly loaded before deployment. Test the contact form functionality and analytics tracking in a staging environment before going live.