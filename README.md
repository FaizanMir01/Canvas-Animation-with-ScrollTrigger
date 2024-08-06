
# Canvas Animation with ScrollTrigger

This project demonstrates a canvas animation synchronized with scroll events using GSAP (GreenSock Animation Platform) and Tailwind CSS for styling. The animation plays frame-by-frame images as the user scrolls down the page.

## Table of Contents

- [Demo](#demo)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)

## Demo

You can see a live demo of the project [here](#).

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/canvas-scroll-animation.git
    cd canvas-scroll-animation
    ```

2. Ensure you have a local server to serve the files, as loading local images directly might not work with some browsers due to CORS policies. You can use a simple HTTP server like `http-server` in Node.js.

    Install `http-server` if you don't have it:
    ```bash
    npm install -g http-server
    ```

3. Start the server:
    ```bash
    http-server
    ```

4. Open your browser and navigate to `http://localhost:8080` (or whichever port `http-server` specifies).

## Usage

1. Place your frame images in the `frames` directory. Ensure the images are named sequentially in the format `ezgif-frame-001.jpg`, `ezgif-frame-002.jpg`, etc.

2. Open the `index.html` file in your browser. The animation should play as you scroll down the page.

## Dependencies

- [Tailwind CSS](https://tailwindcss.com/) - A utility-first CSS framework.
- [GSAP](https://greensock.com/gsap/) - A powerful JavaScript library for animations.
- [ScrollTrigger](https://greensock.com/scrolltrigger/) - A plugin for GSAP to trigger animations based on scroll events.

These dependencies are included via CDN links in the `index.html` file.

## Project Structure

```plaintext
canvas-scroll-animation/
│
├── frames/
│   ├── ezgif-frame-001.jpg
│   ├── ezgif-frame-002.jpg
│   └── ... (up to ezgif-frame-125.jpg)
│
├── index.html
└── README.md
