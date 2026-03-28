# HandDraw Pro

A real-time drawing application that uses hand tracking to let you draw, erase, and manipulate artwork with natural gestures. Powered by MediaPipe Hands and built with vanilla JavaScript.

![HandDraw Pro Demo](demo.gif) <!-- Add a demo GIF if available -->

## Features

- **Gesture-Based Drawing**: Use your index finger to draw naturally
- **Multi-Gesture Support**:
  - ☝️ Index finger up = Draw
  - ✌️ Two fingers up = Erase
  - 🤌 Pinch (thumb + index) = Grab and move strokes
  - 🤏🤏 Both hands pinching = Scale and rotate grabbed content
  - ✊ Fist (hold for 900ms) = Undo last stroke
- **Multiple Layers**: Organize your artwork across 3 layers
- **Color Palette**: 10 vibrant colors including white, red, orange, yellow, green, cyan, blue, purple, pink, and black
- **Variable Brush Sizes**: S, M, L, XL with velocity-based width variation
- **Advanced Effects**:
  - Smooth stroke rendering with Chaikin algorithm
  - Particle effects on draw start
  - Ink trail visualization
  - Glowing effects for grabbed strokes
- **Camera Background**: Toggle between solid background and live camera feed
- **Replay Mode**: Watch your drawing process in action
- **Export**: Save your artwork as PNG
- **Responsive Design**: Adapts to different screen sizes

## How to Use

1. **Setup**: Allow camera access when prompted
2. **Drawing**: Point your index finger at the canvas and move to draw
3. **Erasing**: Show two fingers (index and middle) to erase
4. **Grabbing**: Pinch with thumb and index finger to grab nearby strokes
5. **Scaling/Rotating**: Use both hands to pinch and manipulate grabbed content
6. **Undo**: Make a fist and hold for a moment
7. **Layers**: Switch between 3 layers using the layer buttons
8. **Colors**: Select from the color palette on the left
9. **Brush Size**: Choose S, M, L, or XL sizes
10. **Export**: Click the save button to download your artwork as PNG

## Technical Details

- **Hand Tracking**: MediaPipe Hands with 5-frame landmark smoothing
- **Rendering**: HTML5 Canvas with custom variable-width stroke algorithm
- **Performance**: Optimized for real-time performance with efficient gesture detection
- **Browser Support**: Modern browsers with WebRTC camera access
- **Dependencies**: MediaPipe Hands library (loaded via CDN)

## Browser Requirements

- Modern web browser with WebRTC support
- Camera access permission
- JavaScript enabled

## Installation

No installation required! Simply open `Hand draw tracking.html` in a web browser that supports camera access.

## Development

The entire application is contained in a single HTML file with embedded CSS and JavaScript. To modify:

1. Clone the repository
2. Open `Hand draw tracking.html` in your editor
3. Make changes to the code
4. Test by opening the file in a browser



## Contributing

Contributions welcome! Please feel free to submit issues and pull requests.

## Credits

- Built with [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html)
- Inspired by gesture-based creative tools</content>
<parameter name="filePath">C:\Users\shero\Downloads\Draw-using-hand-tracking\README.md