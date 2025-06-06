# 🎨 Paint The Animal

> A fun, interactive drawing game with dark glassmorphism design where players draw animal silhouettes to win!

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🌟 Features

### 🎯 Core Gameplay
- **150+ Animals** to draw including mammals, birds, reptiles, insects, and more
- **Progressive Difficulty** with level system and streak bonuses
- **Smart Recognition** system that evaluates your drawings
- **Hint System** to help when you're stuck
- **Mobile & Desktop** compatible with touch and mouse support

### 🎨 Drawing Tools
- **Adjustable Brush Size** (2px - 20px)
- **Eraser Tool** for precise corrections
- **Clear Canvas** for fresh starts
- **Smooth Drawing** with anti-aliased lines

### 🌈 Visual Design
- **Dark Glassmorphism** aesthetic with glowing effects
- **Animated Gradients** and smooth transitions  
- **Particle Celebrations** for successful drawings
- **Responsive Design** that works on all screen sizes
- **Accessibility Features** with proper contrast and semantic markup

### 📊 Scoring System
- **Points** earned for correct drawings
- **Level Progression** based on streak performance
- **Streak Counter** for consecutive wins
- **Real-time Feedback** with success/error messages

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/r3dhulk/paint-the-animal.git
cd paint-the-animal
```

2. **Open the game**
```bash
# Simply open index.html in your browser
open index.html
# or
double-click index.html
```

3. **Start playing!**
   - Look at the target animal emoji
   - Draw the animal silhouette on the canvas
   - Click "Check Drawing" to see if you got it right
   - Use hints if needed and build your streak!

## 🎮 How to Play

### Basic Controls
- **Draw**: Click and drag on the canvas (or touch on mobile)
- **Erase**: Click the eraser button to toggle erase mode
- **Clear**: Remove everything from the canvas
- **Brush Size**: Adjust with the slider (2-20px)
- **Check Drawing**: Submit your drawing for evaluation
- **Next Animal**: Skip to a new animal
- **Hint**: Get a clue about the current animal

### Scoring
- **+10 points** per successful drawing (multiplied by level)
- **Streak bonus** for consecutive correct drawings
- **Level up** every 5 correct drawings in a row
- **Reset streak** on incorrect attempts

## 🐾 Animal Categories

The game features **150+ animals** across diverse categories:

- **🐱 Big Cats**: Lion, Tiger, Cheetah, Leopard, Jaguar, Lynx, Puma, etc.
- **🐵 Primates**: Monkey, Gorilla, Chimpanzee, Orangutan, Baboon, Lemur, etc.
- **🐻 Bears**: Polar Bear, Grizzly, Panda, Sun Bear, Sloth Bear, etc.
- **🦊 Canines**: Wolf, Fox, Coyote, Jackal, Dingo, etc.
- **🦌 Ungulates**: Deer, Elk, Moose, Antelope, Gazelle, Ibex, etc.
- **🐄 Cattle**: Buffalo, Bison, Yak, Highland Cattle, Longhorn, etc.
- **🐭 Rodents**: Mouse, Rat, Squirrel, Beaver, Capybara, etc.
- **🐧 Birds**: Eagle, Owl, Penguin, Peacock, Swan, etc.
- **🐠 Marine Life**: Whale, Dolphin, Shark, Octopus, Crab, etc.
- **🦋 Insects**: Butterfly, Bee, Ant, Spider, Dragonfly, etc.
- **🐸 Reptiles & Amphibians**: Frog, Turtle, Snake, etc.

## 💻 Technical Details

### Technologies Used
- **Pure HTML5** for structure
- **CSS3** with advanced features (backdrop-filter, gradients, animations)
- **Vanilla JavaScript** for game logic and canvas drawing
- **Canvas API** for drawing functionality
- **Touch Events** for mobile compatibility

### Browser Compatibility
- ✅ Chrome 88+
- ✅ Firefox 94+
- ✅ Safari 15.4+
- ✅ Edge 88+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

### Performance Features
- **Optimized Canvas Rendering** with efficient draw operations
- **Smooth 60fps Animations** using CSS transforms
- **Responsive Images** with emoji-based graphics
- **Memory Efficient** with proper event cleanup

## 🛠️ Customization

### Adding New Animals
```javascript
// Add to the animals array in script section
{name: "Your Animal", emoji: "🐾", hint: "Your hint here"}
```

### Modifying Colors
```css
/* Update CSS custom properties */
:root {
  --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
  --secondary-gradient: linear-gradient(135deg, #f093fb 0%, #f5576c 100%);
}
```

### Adjusting Difficulty
```javascript
// Modify success rate in checkDrawing() function
const success = Math.random() > 0.3; // 70% success rate
```

## 📱 Mobile Optimization

- **Touch-friendly** interface with large buttons
- **Responsive layout** that adapts to screen size
- **Gesture support** for drawing and erasing
- **Optimized performance** for mobile devices
- **Portrait/landscape** compatibility

## 🎯 Future Enhancements

- [ ] **AI-powered drawing recognition** using TensorFlow.js
- [ ] **Multiplayer mode** with real-time competition
- [ ] **Custom animal packs** and user-generated content
- [ ] **Drawing tutorials** and step-by-step guides
- [ ] **Achievement system** with badges and rewards
- [ ] **Social features** for sharing drawings
- [ ] **Offline mode** with service worker
- [ ] **Audio feedback** and sound effects

## 🤝 Contributing

We welcome contributions! Here's how you can help:

1. **Fork** the repository
2. **Create** a feature branch (`git checkout -b feature/amazing-feature`)
3. **Commit** your changes (`git commit -m 'Add amazing feature'`)
4. **Push** to the branch (`git push origin feature/amazing-feature`)
5. **Open** a Pull Request

### Contribution Ideas
- Add new animals with emojis and hints
- Improve drawing recognition algorithm
- Enhance visual effects and animations
- Add accessibility features
- Optimize performance
- Create documentation and tutorials

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Emoji Graphics** from Unicode Consortium
- **Glassmorphism Design** inspired by modern UI trends
- **Canvas API** documentation from MDN Web Docs
- **Touch Events** implementation based on web standards

## 📞 Support

If you encounter any issues or have questions:

- **Create an Issue** on GitHub
- **Check existing Issues** for solutions
- **Read the Documentation** for detailed guides
- **Contact** the maintainers

---

<div align="center">

**Made with ❤️ and lots of ☕**

[⭐ Star this repo](https://github.com/r3dhulk/paint-the-animal) • [🐛 Report Bug](https://github.com/r3dhulk/paint-the-animal/issues) • [💡 Request Feature](https://github.com/r3dhulk/paint-the-animal/issues)

</div>