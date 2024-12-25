# Breethe

Breethe is a minimalistic single-file HTML page that turns your display into a pure orange breathing light effect. This can be useful for creating a calming ambient light or for decorative purposes.

## Features

- Simple and lightweight
- Pure orange breathing light effect
- Fullscreen mode for immersive experience
- Customizable colors and timing

## Usage

1. **Open with Chrome/Chromium:**
   - Simply open the `breethe.html` file with Chrome or Chromium browser.
   - Press `F11` to enter fullscreen mode.

2. **Command Line:**
   - To start the page in fullscreen mode from the command line, you can use the following command:
     ```sh
     chromium-browser --start-fullscreen path/to/breethe.html
     ```
   - Replace `path/to/breethe.html` with the actual path to the `breethe.html` file.

## Customization

You can customize the breathing light effect by modifying the CSS variables in the `<style>` section of the `breethe.html` file. The variables are:

```css
html {
    --dark-color: #000;
    --bright-color: #ff9100;
    --cycle-time: 7s;
    --delay-time: 1s;
}
```

- `--dark-color`: The darkest color in the breathing cycle. Default is `#000` (black).
- `--bright-color`: The brightest color in the breathing cycle. Default is `#ff9100` (orange).
- `--cycle-time`: The total time for one complete breathing cycle. Default is `7s` (7 seconds).
- `--delay-time`: The delay time before the cycle starts. Default is `1s` (1 second).

You can change these values to customize the breathing effect to your liking.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](/bobwen-dev/breethe-html?tab=MIT-1-ov-file#MIT-1-ov-file) file for details.
