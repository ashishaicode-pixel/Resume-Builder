# 📄 Resume Builder

A modern, user-friendly web application to create, preview, and download professional resumes in seconds. No sign-ups, no subscriptions—just pure simplicity!

---

## ✨ Features

- **🎨 Multiple Templates** - Choose from professional and modern resume designs
- **📝 Easy Form Filling** - Simple, intuitive form to enter your resume details
- **👀 Live Preview** - See your resume update in real-time as you fill the form
- **💾 Download as PDF** - Download your completed resume instantly
- **📱 Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **⚡ Fast & Lightweight** - No server required, everything runs in your browser
- **🎯 Modern UI** - Beautiful gradient design with smooth animations

---

## 🚀 Getting Started

### Option 1: Open in Browser (Recommended)
1. Download or clone this folder
2. Open `index.html` in your web browser
3. Select a resume template
4. Fill in your details
5. Preview and download your resume as PDF

### Option 2: Using a Local Server
If you want to use a local server:
```bash
# Using Python (Python 3.x)
python -m http.server 8000

# Using Node.js with http-server
npx http-server

# Using PHP
php -S localhost:8000
```
Then open `http://localhost:8000` in your browser.

---

## 📁 Project Structure

```
resume-builder/
├── index.html           # Template selection page
├── form.html            # Resume form page
├── script.js            # JavaScript logic
├── style.css            # Modern styling & animations
├── assets/              # Resume template preview images
│   ├── template1-preview.png.png
│   └── template2-preview.png.png
├── templates/           # Resume template HTML files
│   ├── template1.html
│   └── template2.html
└── README.md            # This file
```

---

## 📋 How to Use

### Step 1: Select Template
- Open `index.html`
- Choose between **Professional Resume** or **Modern Resume**
- Click on your preferred template

### Step 2: Fill Your Details
- Enter your personal information (name, email, phone, address)
- Add your professional summary
- List your education details
- Add work experience
- Include your skills (comma-separated)

### Step 3: Preview Your Resume
- Click "Preview Resume" to see how it looks
- Your resume updates instantly with your information

### Step 4: Download
- Click "Download PDF" to save your resume
- Choose a location and filename
- Done! Your professional resume is ready to use

---

## 🛠️ Technologies Used

- **HTML5** - Structure and semantic markup
- **CSS3** - Modern styling with gradients and animations
- **JavaScript (Vanilla)** - Core functionality
- **html2canvas** - Convert resume to image
- **jsPDF** - Generate PDF files

---

## 🎨 Design Features

- **Gradient Background** - Eye-catching purple gradient
- **Smooth Animations** - Elegant fade-in and slide transitions
- **Hover Effects** - Interactive card lifting and color changes
- **Custom Scrollbar** - Matches the modern color scheme
- **Responsive Layout** - Adapts to all screen sizes

---

## 💡 Tips for Best Results

1. **Keep it concise** - Use bullet points in experience and education
2. **Professional tone** - Maintain formal language throughout
3. **Valid email** - Double-check your contact information
4. **Recent photo** - If templates support images, use a professional headshot
5. **Proofread** - Check spelling and grammar before downloading

---

## 🔄 Customization

### Add More Templates
1. Create a new HTML file in the `templates/` folder
2. Design your resume template with a unique style
3. Add the template card to `index.html`
4. Update `script.js` to reference the new template

### Modify Colors
Edit the gradient colors in `style.css`:
```css
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Change Font
Update the font family in `style.css`:
```css
font-family: 'Your Font', sans-serif;
```

---

## 📱 Browser Compatibility

- ✅ Chrome/Edge (Latest)
- ✅ Firefox (Latest)
- ✅ Safari (Latest)
- ✅ Mobile Browsers (iOS Safari, Chrome Mobile)

---

## ⚙️ Requirements

- **None!** Just a modern web browser
- No installation needed
- No internet connection required (after loading the page)
- No dependencies to install

---

## 🤝 Contributing

Have ideas to improve this resume builder? Feel free to:
- Report bugs or issues
- Suggest new templates or features
- Improve the styling or animations
- Help with translations

---

## 📄 License

This project is free to use and modify for personal and commercial purposes.

---

## 💬 Feedback

Love the Resume Builder? Have suggestions? Feel free to reach out!

**Happy Resume Building! 🎉**

---

*Made with ❤️ to help you land your dream job*
