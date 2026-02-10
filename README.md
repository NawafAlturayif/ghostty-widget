# 👻 Ghostty Widget

<div align="center">
  <video src="demo_animation.mp4" width="500" autoplay loop muted playsinline></video>
  <p><i>The best terminal deserves the best desktop icon.</i></p>
</div>

A desktop widget that displays an animated [Ghostty](https://ghostty.org/) terminal icon in ASCII art. Clicking the widget launches the Ghostty terminal.

Powered by [Übersicht](http://tracesof.net/uebersicht/).

## Demo

<div align="center">
  <video src="demo_terminal.mp4" width="500" autoplay loop muted playsinline></video>
</div>

## Prerequisites

- **macOS**
- **[Übersicht](http://tracesof.net/uebersicht/)**: The app used to run this widget.
- **[Ghostty](https://ghostty.org/)**: The terminal emulator itself.

## Installation

1.  Download this repository or the `ghossty.jsx` file.
2.  Open Übersicht and select **Open Widgets Folder** from the menu.
3.  Move the `ghossty.jsx` file into that folder.
4.  The widget should appear on your desktop.

## Configuration

You can customize the position of the widget by editing the `ghossty.jsx` file.

Look for the **CONFIG: POSITION** section near the top of the file:

```javascript
// ============================================================================
// CONFIG: POSITION
// ============================================================================
// Adjust these values to move the widget on your screen.
const position = {
  bottom: "17px",   // Distance from bottom
  left: "377px"     // Distance from left
};
```

## Credits

- ASCII Animation: [ghosttime](https://github.com/SohelIslamImran/ghosttime) by [SohelIslamImran](https://github.com/SohelIslamImran).
- Widget Logic: Built for the Ghostty community.

## License

MIT License
