# 🦎 Modern Reptile Cursor

A sleek, interactive reptile cursor that follows your mouse movements with fluid, organic motion. Built with vanilla JavaScript and HTML5 Canvas.

[Live Demo](https://lokesh-reddy18.github.io/Reptile-Cursor/)

## ✨ Features

- 🎨 Modern neon aesthetic with smooth animations
- 🦎 Procedurally generated reptile with customizable segments
- 🖱️ Responsive mouse following behavior
- 📱 Fullscreen canvas that adapts to window size
- ⚡ Optimized performance using requestAnimationFrame

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/Lokesh-reddy18/Reptile-Cursor.git
```

2. Open `index.html` in your web browser

3. Move your mouse around to see the reptile follow your cursor!

## 🛠️ Customization

You can customize the reptile's appearance and behavior by modifying these parameters in `script.js`:

```javascript
// Color customization
canvas.style.backgroundColor = "#1a1a1a"; // Background color
ctx.strokeStyle = "#00ff88"; // Reptile color
ctx.lineWidth = 2; // Line thickness

// Creature parameters
var legNum = Math.floor(4 + Math.random() * 8); // Number of legs (4-12)
setupLizard(
  6 / Math.sqrt(legNum), // Size
  legNum, // Number of legs
  Math.floor(6 + Math.random() * legNum * 4) // Tail length
);
```

## 🎮 Controls

- Move your mouse to control the reptile's movement
- The reptile will automatically follow your cursor with organic, fluid motion
- The creature's body segments will dynamically adjust to follow the path

## 🧪 Technical Details

The reptile cursor is built using:
- HTML5 Canvas for rendering
- Vanilla JavaScript for animation and physics
- RequestAnimationFrame for smooth animation
- Custom physics system for organic movement

## 📝 License

MIT License - feel free to use this in your own projects!

## 🤝 Contributing

Contributions are welcome! Feel free to:
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 🔗 Links

- [Live Demo](https://lokesh-reddy18.github.io/Reptile-Cursor/)
- [GitHub Repository](https://github.com/Lokesh-reddy18/Reptile-Cursor)
