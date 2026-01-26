# Frontend Mentor - Sunnyside agency landing page solution

This is a solution to the [Sunnyside agency landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/sunnyside-agency-landing-page-7yVs3B6ef). This project showcases a responsive landing page with a focus on layout, image galleries, and testimonials, built with modern web technologies.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [Installation and Usage](#installation-and-usage)
- [My process](#my-process)
  - [Built with](#built-with)
  - [Architecture](#architecture)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [GitHub Repository](https://github.com/bhzeuscagd/sunnyside-agency-landing-page-main)
- Live Site URL: [Vercel Deployment](https://sunnyside-agency-landing-page-main-six-tan.vercel.app)

## Installation and Usage

### Prerequisites
- [Node.js](https://nodejs.org/) (Latest LTS recommended)
- [pnpm](https://pnpm.io/) or npm

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/bhzeuscagd/sunnyside-agency-landing-page-main.git
   ```
2. Navigate to the project directory:
   ```bash
   cd sunnyside-agency-landing-page-main
   ```
3. Install dependencies:
   ```bash
   pnpm install
   ```

### Usage
Start the development server:
```bash
pnpm run dev
```
Open [http://localhost:4321](http://localhost:4321) in your browser to see the result.

## My process

### Built with

- [Astro](https://astro.build/) - Web framework for content-driven websites.
- [Tailwind CSS v4](https://tailwindcss.com/) - Utility-first CSS framework.
- [Fontsource](https://fontsource.org/) - Self-hosted Open Source fonts (Barlow, Fraunces).
- Semantic HTML5 markup
- CSS Grid & Flexbox
- Mobile-first workflow

### Architecture

#### Component Map
The application is structured into modular Astro components to separate concerns and enhance maintainability:

- **`Layout`**: The main wrapper providing the HTML structure, metadata, and global font styles.
- **`Navbar`**: Contains the logo, navigation links, and the responsive mobile menu.
- **`Hero`**: The primary visual start of the landing page.
- **`InfoSection`**: Displays the brand's transformative services with distinct text and image layouts.
- **`Testimonials`**: A section showcasing client feedback.
- **`Gallery`**: A visual grid of four images.
- **`Footer`**: Contains the logo, navigation links, and social media icons.
- **`UI Components`**: Reusable low-level components:
  - **`Text-info`**: Reusable text blocks for info sections.
  - **`Image-Text`**: Combined image and text layouts.
  - **`Icons`**: SVG icons.

#### Data Flow & Styling
- **Static Generation**: The site is fully static for optimal performance.
- **Responsive Design**: Tailwind CSS utility classes handle all responsive breakpoints.
- **Scoped Styles**: Component-specific styles are handled via Tailwind and Astro's scoped CSS where necessary.

## Author
- Portfolio - [Cagd](https://portfolio-cagd.vercel.app/)
- Frontend Mentor - [@bhzeuscagd](https://www.frontendmentor.io/profile/bhzeuscagd)
- GitHub - [bhzeuscagd](https://github.com/bhzeuscagd)

## Acknowledgments
- [Frontend Mentor](https://www.frontendmentor.io) for the professional design resources and challenge.
- [Astro Docs](https://docs.astro.build) for the excellent documentation.
