# Movie Website Frontend

This project is a movie website frontend built using HTML and Tailwind CSS. It includes features such as a responsive layout, a scrollable row for newly added movies, and various interactive elements to enhance the user experience.

## Table of Contents

1. [Demo](#demo)
2. [Features](#features)
3. [Tech Stack](#tech-stack)
4. [Getting Started](#getting-started)
5. [Project Structure](#project-structure)
8. [Future Improvements](#future-improvements)
9. [Acknowledgements](#acknowledgements)

## Demo

[Link to live demo or add a GIF/screenshot of the website]

## Features

- **Responsive Design**: Adapted for different screen sizes using Tailwind’s responsive utilities.
- **Scrollable Movie List**: Newly added movies and seasons are displayed in a scrollable row.
- **Interactive Hover Effects**: Movie posters and buttons have hover animations for a dynamic experience.
- **Fixed Background Overlay**: A background image with opacity overlay adds depth to the website design.

## Tech Stack

- **Tailwind CSS**: For all styling and layout adjustments.
- **HTML**: Basic structure of the website.
- **FontAwesome**: Icons for buttons and navigation.
- **Heroicons**: Icons for buttons and navigation.

## Getting Started

To set up this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/your-username/movie-website-frontend-tailwind.git
    cd movie-website-frontend
    ```

2. **Install Tailwind CSS** (if not included):
    - Add Tailwind CSS via CDN by adding this to the `<head>` of your HTML file:
      ```html
      <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
      ```
    - Or, set up Tailwind CSS via npm if you’re using a build tool (I recommend using Tailwind CSS CDN):
      ```bash
      npm install -D tailwindcss
      npx tailwindcss init
      ```

3. **Configure Tailwind**:
    - Add any customizations or paths to your HTML files in `tailwind.config.js`.
    - Compile the CSS if using Tailwind via npm:
      ```bash
      npx tailwindcss -o output.css
      ```

4. **Open the HTML file** in your browser to view the site.

## Project Structure

```plaintext
movie-website-frontend/
├── index.html              # Main HTML file
├── img/                    # Folder for images
├── styles.css              # Additional custom styles
└── README.md               # Project documentation
```

## Images

### 1. **Image 1**

<img src="src/img/Screenshot From 2024-11-08 10-41-38.png">

### 2. **Image 2**

<img src="src/img/Screenshot From 2024-11-08 10-48-11.png">

### 3. **Image 3**

<img src="src/img/Screenshot From 2024-11-08 10-48-15.png">

## Future Improvements

- **Dynamic Content**: Integrate with a backend to fetch and display real movie data.
- **Dark Mode Toggle**: Add a dark mode toggle for user preference.
- **Interactive Filter/Search**: Implement a search and filter functionality for genres or movie categories.
- **Pagination**: Add pagination or lazy loading to improve performance for large movie lists.

## Acknowledgements

- **Tailwind CSS Documentation**: For helpful resources on how to use Tailwind utilities effectively.
- **FontAwesome**: For the icons used in the buttons.
- **Heroicons**: For the icons used in the navigation bar.
