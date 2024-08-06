
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
    git clone https://github.com/FaizanMir01/canvas-scroll-animation.git
    cd canvas-scroll-animation
    ```

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
