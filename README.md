# Counter Application 🔢

A modern, interactive counter application built with vanilla JavaScript that demonstrates core DOM manipulation techniques. Features a sleek glassmorphism design with real-time statistics tracking and keyboard shortcuts.

![Counter App Preview](https://img.shields.io/badge/Status-Live-success) ![JavaScript](https://img.shields.io/badge/JavaScript-ES6+-yellow) ![CSS3](https://img.shields.io/badge/CSS-Modern-blue) ![License](https://img.shields.io/badge/License-MIT-green)

## ✨ Features

- **🎯 Core Functionality**: Increment, decrement, and reset counter
- **📊 Statistics Tracking**: Real-time tracking of total clicks, max/min values
- **⌨️ Keyboard Shortcuts**: Full keyboard navigation support
- **📱 Responsive Design**: Works seamlessly on desktop and mobile devices
- **🎨 Modern UI**: Glassmorphism design with smooth animations
- **🔄 Visual Feedback**: Interactive button effects and state-based styling
- **🎭 Dynamic Themes**: Color changes based on counter values

## 🚀 Live Demo

[View Live Demo](https://gurjarsachin.github.io/counter-app) *(Replace with your actual GitHub Pages URL)*

## 📸 Screenshots

*Add screenshots of your application here*

## 🛠️ DOM Manipulation Techniques Demonstrated

This project serves as an educational example showcasing:

- **Element Selection**: `getElementById()`, `querySelector()`
- **Content Manipulation**: Dynamic text updates with `textContent`
- **Class Management**: `classList.add()`, `classList.remove()` for conditional styling
- **Style Manipulation**: Direct CSS property modifications for animations
- **Event Handling**: Click events and keyboard event listeners
- **Multiple Element Updates**: Synchronous updates across different UI components
- **Conditional Rendering**: State-based visual changes

## 🎮 Usage

### Basic Controls
- **Increment Button**: Increases counter by 1
- **Decrement Button**: Decreases counter by 1  
- **Reset Button**: Resets counter and statistics to 0

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `↑` or `+` | Increment counter |
| `↓` or `-` | Decrement counter |
| `Esc` or `R` | Reset everything |

### Visual Indicators
- **Green**: Positive values
- **Red**: Negative values
- **Blue**: Zero value
- **Special Effects**: Values ≥10 or ≤-10 get unique color themes

## 🚀 Getting Started

### Option 1: Direct Download
1. Download the `index.html` file
2. Open it in any modern web browser
3. Start clicking or use keyboard shortcuts!

### Option 2: Clone Repository
```bash
git clone https://github.com/your-username/counter-app.git
cd counter-app
open index.html
```

### Option 3: GitHub Pages
Visit the live demo link above for instant access.

## 💻 Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with advanced features
  - CSS Grid & Flexbox for layout
  - CSS Gradients and backdrop-filter
  - CSS Transitions and Transforms
  - Responsive design with media queries
- **Vanilla JavaScript (ES6+)**: Pure JavaScript without frameworks
  - Event handling and DOM manipulation
  - Local state management
  - Keyboard event processing

## 📂 Project Structure

```
counter-app/
├── index.html          # Complete application (HTML + CSS + JS)
├── README.md          # Project documentation
├── LICENSE            # MIT License
└── screenshots/       # (Optional) Application screenshots
```

## 🔧 Customization

The application is built with customization in mind:

### Modify Counter Step
```javascript
// Change increment/decrement value
counter += 5; // Instead of counter++
```

### Add New Keyboard Shortcuts
```javascript
case 'Space':
    // Add your custom action
    break;
```

### Customize Styling
- Edit CSS variables for colors
- Modify transition durations
- Change button sizes and spacing

## 🌟 Educational Value

This project is perfect for:
- **Learning DOM Manipulation**: Practical examples of core concepts
- **JavaScript Fundamentals**: Event handling, functions, and state management
- **CSS Modern Features**: Glassmorphism, animations, and responsive design
- **UI/UX Principles**: User feedback and interactive design
- **Code Organization**: Clean, readable JavaScript structure

## 🤝 Contributing

Contributions are welcome! Here are some ideas:
- Add sound effects
- Implement local storage for persistence
- Add more keyboard shortcuts
- Create different themes
- Add unit tests

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 Browser Compatibility

- ✅ Chrome 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ⚠️ Internet Explorer: Not supported (uses modern CSS features)

## 🐛 Known Issues

- None currently known. Please report any issues in the GitHub Issues section.

## 📈 Future Enhancements

- [ ] Add sound effects for button clicks
- [ ] Implement local storage for session persistence
- [ ] Add counter history/undo functionality
- [ ] Create multiple counter instances
- [ ] Add export functionality for statistics
- [ ] Implement different counting modes (by 2s, 5s, etc.)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Your Name**
- GitHub: [gurjarsachin](https://github.com/gurjarsachin)
- LinkedIn: [Your LinkedIn Profile](https://linkedin.com/in/your-profile)

## 🙏 Acknowledgments

- Inspiration from modern web design trends
- Glassmorphism design concept
- Vanilla JavaScript community for best practices

---

⭐ **Star this repository if you found it helpful!**

*Built with ❤️ and vanilla JavaScript*
