# Apple Website Clone using Three.js

This project is a clone of the Apple website, built using **Three.js** to showcase 3D elements and interactions. The goal is to replicate the clean, interactive experience of the official Apple website, integrating custom 3D models, animations, and smooth scroll interactions.

## Screenshots

![alt text](/public/screenshots/pic1.png)
![alt text](/public/screenshots/pic2.png)
![alt text](/public/screenshots/pic3.png)
![alt text](/public/screenshots/pic4.png)
![alt text](/public/screenshots/pic5.png)
![alt text](/public/screenshots/pic6.png)



## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [License](#license)

## Features

- Responsive design similar to the Apple website
- 3D models of Apple products using **Three.js**
- Smooth scroll animations and transitions
- Interactive product showcases with **OrbitControls** for 360-degree views
- Lightweight performance optimized for web browsers

## Technologies Used

- **Three.js**: A JavaScript library for creating 3D graphics in the browser.
- **React**: A JavaScript library for building user interfaces.
- **React Three Fiber**: A React renderer for Three.js, making 3D scenes easier to manage in React.
- **Tailwind CSS**: A utility-first CSS framework to create a responsive design.
- **Vite**: A fast build tool and development server.

## Installation

Follow the steps below to run the project locally:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/apple-website-clone.git
   cd apple-website-clone
   ```

2. **Install dependencies:**

   Run :
   `npm install`

3. **Start the development server:**

   Run :
   `npm run dev`

## Usage

Once the development server is running, you can view the Apple website clone in your browser at:

```
  http://localhost:3000
```

## Project Structure

Here's an overview of the project's structure:

```
apple-website-clone/
│
├── public/                    # Public assets
│   └── models/                # 3D models (e.g., iPhone, MacBook)
    └── assets/
├── src/                       # Source code
│   ├── components/            # React components
│   │   ├── Features.jsx       #Features portion
│   │   ├── Footer.jsx         #Footer of our website
│   │   └── Hero.jsx           #Hero section code
        └── Highlights.jsx     #Highlight area code
        └── HowItWorks.jsx     #How it works section of the website
        └── IPhone.jsx         #Iphone model three js code
        └── Lights.jsx         #Lights code for the model
        └── Loader.jsx         #Model viewing code (setting the canvas)
        └── Model.jsx          #Rendering code for the model
        └── ModelView.jsx      #Making the model view
        └── Navbar.jsx         #Navbar of our website
        └── VideoCarousel.jsx  #Moving video carousel code
│   ├── assets/                # Images and static assets
│   ├── styles/                # Tailwind CSS styles
│   └── App.jsx                # Main application component
│
├── README.md                  # This file
├── package.json               # Project metadata and dependencies
└── vite.config.js             # Vite configuration


```

## License

### Breakdown:

- **Installation instructions**: Provides steps to clone, install dependencies, and run the project.
- **Usage instructions**: Explains how to interact with the website and where to access it.
- **Project structure**: Helps users understand the folder organization.
- **Features and technologies**: Gives an overview of what the project does and the tech stack used.

Feel free to adjust the content to fit your specific project needs!
