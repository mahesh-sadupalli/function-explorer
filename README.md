# Function Explorer

An interactive, browser-based visualization tool for exploring mathematical functions and their properties in real-time. Built with pure JavaScript and SVG, requiring no external dependencies.

## Live Demo

**[Launch Function Explorer →](https://mahesh-sadupalli.github.io/function-explorer/)**


## Features

### Current Implementation
- **📈 Linear Functions** - Explore y = mx + b with interactive controls
- **🎮 Real-time Interaction** - Adjust parameters and see immediate visual feedback
- **📐 Geometric Visualizations**
  - Slope triangle showing rise over run
  - X and Y intercept highlighting
  - Grid system with labeled axes
- **📏 Lipschitz Continuity** - Interactive demonstration with draggable points
- **🎨 Clean Interface** - Professional, responsive design
- **⚡ Zero Dependencies** - Pure HTML/CSS/JavaScript, no build process required
- **📱 Responsive Design** - Works seamlessly on desktop, tablet, and mobile

### Mathematical Concepts Illustrated
- Slope and intercept relationships
- Function continuity and boundedness
- Rate of change visualization
- Coordinate system navigation
- Linear transformations

## 🚀 Quick Start

### Option 1: Direct Browser
Simply open `index.html` in any modern web browser.

### Option 2: Local Server
```bash
# Using Python
python3 -m http.server 8000

# Using Node.js
npx serve

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 🛠️ Technology Stack

- **Frontend**: Vanilla JavaScript (ES6+)
- **Visualization**: SVG with dynamic rendering
- **Styling**: Pure CSS with modern properties
- **Deployment**: GitHub Pages
- **Version Control**: Git

## 📖 Usage Guide

1. **Select Function Type** - Choose from available mathematical functions
2. **Adjust Parameters** - Use sliders to modify function properties
3. **Toggle Visualizations** - Enable/disable different visual aids
4. **Use Presets** - Quick access to interesting function configurations
5. **Interactive Elements** - Drag points for Lipschitz demonstration

## 🗺️ Roadmap

### Phase 1: Core Functions (In Progress)
- [x] Linear functions (y = mx + b)
- [ ] Quadratic functions (y = ax² + bx + c)
- [ ] Exponential functions (y = aᵇˣ)
- [ ] Logarithmic functions (y = log_b(x))

### Phase 2: Advanced Functions
- [ ] Trigonometric (sin, cos, tan)
- [ ] Hyperbolic functions
- [ ] Polynomial (degree n)
- [ ] Rational functions

### Phase 3: Machine Learning Functions
- [ ] Activation functions (ReLU, Sigmoid, tanh)
- [ ] Leaky ReLU and variants
- [ ] Softplus
- [ ] GELU (Gaussian Error Linear Unit)

### Phase 4: Enhanced Features
- [ ] Function composition
- [ ] Derivative visualization
- [ ] Integration areas
- [ ] Animation system
- [ ] Export to SVG/PNG
- [ ] LaTeX equation rendering
- [ ] Dark mode

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Keep it dependency-free
- Maintain responsive design
- Add comments for complex calculations
- Test across different browsers
- Follow existing code style

## 📊 Project Structure

```
function-explorer/
│
├── index.html          # Main application file
├── README.md          # Project documentation
├── LICENSE            # MIT license file
└── .gitignore         # Git ignore rules
```

## 🌟 Inspiration & Acknowledgments

This project was inspired by:
- [Transformer Explainer](https://poloclub.github.io/transformer-explainer/) by Polo Club of Data Science
- Mathematical visualization tools like Desmos and GeoGebra
- The beauty of interactive education

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Mahesh Sadupalli**

- GitHub: [@mahesh-sadupalli](https://github.com/mahesh-sadupalli)
- Project Link: [https://github.com/mahesh-sadupalli/function-explorer](https://github.com/mahesh-sadupalli/function-explorer)

## 🙏 Support

If you find this project helpful, please consider:
- ⭐ Giving it a star on GitHub
- 🐛 Reporting bugs or suggesting features
- 📤 Sharing it with others who might find it useful

## 📚 Learning Resources

- [MDN Web Docs - SVG](https://developer.mozilla.org/en-US/docs/Web/SVG)
- [JavaScript.info](https://javascript.info/)
- [Mathematics for Machine Learning](https://mml-book.github.io/)

---

<p align="center">Made with ❤️ and mathematics</p>
