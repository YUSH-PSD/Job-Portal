# JobHunt - Job Portal Website

A modern, responsive job portal website built with HTML, CSS, and JavaScript. Find your dream job or hire the best talent.

![JobHunt Preview](assets/preview.png)

## 🚀 Features

- **Modern UI/UX** - Clean, professional design with smooth animations
- **Responsive Design** - Works perfectly on all devices
- **Job Listings** - Browse latest and top job openings
- **Easy Navigation** - Quick access to all sections
- **Client Testimonials** - Social proof from satisfied users
- **Newsletter Subscription** - Stay updated with new job opportunities
- **Multiple CTA Buttons** - Clear calls-to-action for job seekers and employers

## 📁 Project Structure

```
job-hunting-website/
├── index.html          # Main HTML file
├── style.css           # All styles
├── main.js             # JavaScript functionality
├── assets/            # Images and icons
│   ├── amazon.png
│   ├── bag.png
│   ├── client-1.jpg
│   ├── client-2.jpg
│   ├── client-3.jpg
│   ├── figma.png
│   ├── google.png
│   ├── linkedin.png
│   ├── microsoft.png
│   ├── offer-1.jpg
│   ├── offer-2.jpg
│   ├── offer-3.jpg
│   ├── steps-bg.png
│   ├── twitter.png
│   └── preview.png
└── README.md           # This file
```

## 🎨 Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom styles, animations, responsive design
- **JavaScript** - Interactive features, mobile menu
- **Remix Icons** - Icon library
- **Swiper.js** - Carousel/slider functionality
- **ScrollReveal** - Scroll animations

## 📦 Installation

1. Clone the repository:
```bash
git clone https://github.com/YUSH-PSD/Job-Portal.git
```

2. Open `index.html` in your browser or use a live server:
```bash
# Using Python
python -m http.server 8000

# Using VS Code
# Install "Live Server" extension and click "Go Live"
```

## 🚀 Deployment

### Option 1: GitHub Pages (Free)

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select `main` branch
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/Job-Portal/`

### Option 2: Netlify (Free)

1. Go to [Netlify](https://netlify.com) and sign up
2. Click **Add new site** → **Deploy manually**
3. Drag and drop your project folder
4. Your site will be deployed instantly

### Option 3: Vercel (Free)

1. Go to [Vercel](https://vercel.com) and sign up
2. Click **Add New Project**
3. Import your GitHub repository
4. Click **Deploy**
5. Your site will be live in seconds

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1023px
- **Desktop**: > 1024px

## 🔧 Customization

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --primary-color: #6a38c2;
    --primary-color-light: #6132b4;
    /* Add more customizations */
}
```

### Adding New Jobs
Edit the job cards in `index.html`:
```html
<div class="job__card">
    <div class="job__card__header">
        <img src="assets/company-logo.png" alt="job">
        <div>
            <h5>Company Name</h5>
            <h6>Location</h6>
        </div>
    </div>
    <h4>Job Title</h4>
    <p>Job description...</p>
    <div class="job__card__footer">
        <span>5 Positions</span>
        <span>Full Time</span>
        <span>$50,000/Year</span>
    </div>
</div>
```

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

- **GitHub**: [@YUSH-PSD](https://github.com/YUSH-PSD)
- **Project Link**: [https://github.com/YUSH-PSD/Job-Portal](https://github.com/YUSH-PSD/Job-Portal)
- **Project Live Demo**: https://jobportalwebbb.netlify.app/

---

⭐ If you found this project useful, please consider giving it a star!
