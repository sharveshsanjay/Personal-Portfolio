# 🌟 Personal Portfolio Website

Welcome to my personal portfolio website! This project showcases my skills, projects, and contact information in a clean, responsive design.


## 🚀 Features

- **Modern UI**: Clean, responsive design with animations
- **Project Showcase**: Highlight your best work with filters
- **Contact Form**: Integrated with EmailJS for direct messaging
- **Dark/Light Mode**: Toggle between color themes
- **Responsive**: Works on all device sizes

## 🛠️ Technologies Used

- **Frontend**: HTML5, CSS3, JavaScript
- **Frameworks**: [SwiperJS](https://swiperjs.com/) (for sliders), [EmailJS](https://www.emailjs.com/) (contact form)
- **Icons**: [Ionicons](https://ionicons.com/)
- **Hosting**: Netlify/Vercel/GitHub Pages

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-portfolio.git
Navigate to project directory:

bash
cd your-portfolio
Open index.html in your browser (no build required)

🔧 Configuration
For the contact form to work:

Get your EmailJS credentials:

SERVICE_ID - From Email Services tab

TEMPLATE_ID - From Email Templates tab

PUBLIC_KEY - From Account > API Keys

Add them in js/email.js:

javascript
emailjs.init({
  publicKey: "YOUR_PUBLIC_KEY",
});

const serviceID = "YOUR_SERVICE_ID";
const templateID = "YOUR_TEMPLATE_ID";
🎨 Customization
To personalize this portfolio:

Replace placeholder images in /assets/images

Update project data in js/projects.js

Modify colors in css/root.css

Edit personal info in index.html

🌐 Live Demo
Check out the live version:
👉 https://sharveshsanjay.netlify.app

📄 License
This project is licensed under the MIT License - see the LICENSE file for details.

🤝 Contributing
While this is a personal project, suggestions are welcome! Please open an issue first to discuss changes.

📧 Contact: sharveshsanjay10@gmail.com
🔗 Portfolio: sharveshsanjay.netlify.app



