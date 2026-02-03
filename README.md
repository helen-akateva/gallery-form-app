# Gallery & Form App

A JavaScript project featuring an interactive image gallery with lightbox functionality and a feedback form with local storage persistence.

## 🌟 Demo

[🔗 Live Demo](https://helen-akateva.github.io/gallery-form-app/)

## 📋 Description

This project demonstrates fundamental JavaScript concepts and DOM manipulation through two main features:

- **Image Gallery**: An interactive gallery that displays images with a lightbox feature, allowing users to view full-size images with descriptions
- **Feedback Form**: A contact form that saves user input to local storage, ensuring data persistence across page reloads

## 🛠️ Technologies

- **HTML5** - Semantic markup
- **CSS3** - Modern styling
- **JavaScript (ES6+)** - Core functionality
- **Vite** - Build tool and development server
- **SimpleLightbox** - Lightbox library for image gallery
- **LocalStorage API** - Data persistence for form

## ✨ Features

### Gallery
- Responsive image grid layout
- Lightbox functionality with SimpleLightbox library
- Image captions and descriptions
- Smooth transitions and animations
- Keyboard navigation support

### Form
- Email and message input fields
- Real-time data saving to localStorage
- Form validation
- Auto-population from localStorage on page load
- Data clearing on successful submission

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/helen-akateva/gallery-form-app.git
```

2. Navigate to the project directory:
```bash
cd gallery-form-app
```

3. Install dependencies:
```bash
npm install
```

4. Start the development server:
```bash
npm run dev
```

5. Open your browser and visit `http://localhost:5173`

## 📦 Build

To create a production build:

```bash
npm run build
```

## 📁 Project Structure

```
gallery-form-app/
├── src/
│   ├── index.html          # Main page with navigation
│   ├── 1-gallery.html      # Gallery page
│   ├── 2-form.html         # Form page
│   ├── css/                # Styles
│   ├── js/
│   │   ├── 1-gallery.js    # Gallery logic
│   │   └── 2-form.js       # Form logic with localStorage
│   └── img/                # Images
├── package.json
├── vite.config.js
└── README.md
```

## 💡 Usage

### Gallery
1. Navigate to the Gallery page
2. Click on any image to open it in lightbox mode
3. Use arrow keys or navigation buttons to browse through images
4. Press ESC or click outside to close the lightbox

### Form
1. Navigate to the Form page
2. Enter your email and message
3. Data is automatically saved to localStorage as you type
4. Submit the form to log the data and clear localStorage
5. Refresh the page to see your data restored from localStorage

## 👩‍💻 Author

**Olena Akatieva**

- LinkedIn: [linkedin.com/in/olena-akatieva](https://linkedin.com/in/olena-akatieva)
- GitHub: [@helen-akateva](https://github.com/helen-akateva)

## 📄 License

This project is open source and available under the ISC License.
