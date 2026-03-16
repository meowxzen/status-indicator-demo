# Zen State🌙

### Description📝

This is a minimalist web0based status indicator that reflects the current activity of my life based on the real-time clock. It uses a sleek, frosted-glass interface and a glowing neon indicator to provide a functional yet atmospheric "I am busy" or "I am sleeping" display.

### Technologies🛠️

`HTML5`
`CSS3`
`JavaScript(Vanilla)`

### Key Features✨

- Real-Time Logic: Automatically switches status text and colors based on the hour of the day.
- Glassmorphism UI: A modern, semi-transparent background with a blur effect.
- Neon Status Dot: A dynamic indicator that uses `currentColor` and `box-shadow` to create a vibrant glowing effect.

### The Process⚙️

- UI Foundation: I started by creating a centered glass container using `rgba` background and background blur to ensure readability against any wallpaper.
- State Login: I wrote a JavaScript function to partition the 24 hour day into four distinct phases: _Studying, Building, Sleeping and Rendering_.
- Visual Feedback: I linked the CSS `currentColor` property to the JavaScript style updates, ensuring the glow of the status dot alaways matches the current activity's theme.

### What I Learned🎓

- **DOM Manipulation:** How to efficiently update multiple CSS properties.
- **Time-Based Logic:** Using the `Date()` object to trigger UI changes without requiring a page refresh.
- **Advanced CSS Effects:** Mastering the `backdrop-filter` property and creating layered shadows to simulate neon light

### Running The Project🚀

1. Clone the repository to your local machine.
2. Ensure you have a background image of your choice named `bg.img` in the root folder (or update the CSS path).
3. Open `index.html` in any modern web browser.
4. The status will automatically update every minute to reflect your local time.

### Image🖼️

![Image](https://i.ibb.co/7Jw0jBk9/image.png)
