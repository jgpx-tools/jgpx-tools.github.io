# JumpJump GPX Flow

A minimalist, automated GPX route generator designed for precision geometric routing and location-based simulations.

## Live Demo

**Experience the tool here:** [https://jgpx-tools.github.io](https://jgpx-tools.github.io)

*(Note: Replace the URL above with your actual organization page link)*

## Features

- **Smart Pathfinding**: Automatically sorts inputted coordinates to generate the shortest possible route.
- **Planting Mode (Loop Generation)**: Creates smooth, geometric circular paths with customizable radius, overlaps, and multi-pass strategies.
- **Harvest Mode (Arc & Offset)**: Generates randomized arc paths around target coordinates with a strict 40m global collision avoidance algorithm.
- **Dynamic Buffering**: Automatically calculates jump delays and stay durations based on distance curves (1 point = 1 second architecture).
- **Privacy First**: 100% pure client-side static web application. No tracking, no backend, and no server-side data collection. 

## Tech Stack

- HTML5 / CSS3 / JavaScript (Vanilla)
- [Leaflet.js](https://leafletjs.com/) for interactive maps
- [Lucide Icons](https://lucide.dev/) for minimalist UI icons

## 📄 License

This project is licensed under the [MIT License](LICENSE).
