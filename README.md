# 🎲 Random Number Generator

A modern, interactive web application for generating random numbers with visual analytics and a beautiful user interface.

## ✨ Features

- **🎯 Random Number Generation**: Generate single random numbers (1-100) or batches of 100 numbers
- **📊 Visual Heatmap**: Real-time chart showing the distribution of generated numbers
- **🌙 Dark Mode Toggle**: Switch between light and dark themes with persistent preferences
- **📱 Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **🎨 Modern UI**: Clean, gradient-based design with smooth animations

## 🚀 Live Demo

Open `index.html` in any modern web browser to start generating random numbers!

## 📁 Project Structure

```
random-number-generator/
├── index.html          # Main application file
├── styles.css          # All CSS styles and themes
└── README.md           # This documentation file
```

## 🛠️ How to Use

### Basic Usage
1. **Generate a Single Number**: Click the "Generate Random Number" button
2. **Generate 100 Numbers**: Click "Generate 100 Numbers" for batch generation
3. **View Statistics**: Watch the heatmap chart update in real-time
4. **Toggle Theme**: Click the 🌙/☀️ button in the top-right corner

### Features Explained

#### Random Number Generation
- Generates numbers between 1 and 100
- Each number has an equal probability of being selected
- Results are displayed immediately below the buttons

#### Heatmap Visualization
- Shows how many times each number (1-100) has been generated
- Color coding:
  - 🔴 Gray: 0 times generated
  - 🟡 Yellow: 1 time generated
  - 🟠 Orange: 2 times generated
  - 🔴 Red: 3+ times generated
- Updates in real-time as you generate numbers

#### Dark Mode
- Toggle between light and dark themes
- Your preference is automatically saved
- Smooth transitions between themes
- Optimized colors for both light and dark viewing

## 🎨 Design Features

- **Modern Gradient Buttons**: Beautiful hover effects with scale animations
- **Card-based Layout**: Clean container with subtle shadows
- **Responsive Typography**: Optimized font sizes and spacing
- **Smooth Animations**: CSS transitions for all interactive elements
- **Accessibility**: High contrast colors and clear visual hierarchy

## 🔧 Technical Details

### Technologies Used
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with flexbox, gradients, and animations
- **JavaScript**: Interactive functionality and chart generation
- **Chart.js**: Professional data visualization library

### Browser Compatibility
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

### Local Storage
The application uses browser localStorage to:
- Remember your theme preference (light/dark mode)
- Persist settings between sessions

## 🚀 Future Enhancements

Potential features to add:
- [ ] Dice rolling functionality
- [ ] Card shuffling and dealing
- [ ] Password generation
- [ ] Color palette generation
- [ ] Statistics export
- [ ] Custom number ranges
- [ ] Multiple chart types

## 📝 Development

### Getting Started
1. Clone or download this repository
2. Open `index.html` in your web browser
3. Start generating random numbers!

### File Organization
- **`index.html`**: Main HTML structure and JavaScript logic
- **`styles.css`**: All CSS styles, including dark mode themes
- **`README.md`**: Project documentation

### Customization
To modify the application:
- **Colors**: Edit the CSS variables in `styles.css`
- **Number Range**: Modify the JavaScript `Math.random()` calculations
- **Chart Style**: Adjust Chart.js configuration options

## 🤝 Contributing

Feel free to:
- Report bugs or issues
- Suggest new features
- Submit pull requests
- Share your customizations

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Happy Random Number Generating! 🎲✨** 