# Fashion Sale Website

This repository contains a simple, stylish fashion sale website showcasing a sale with a focus on minimalistic fashion for men, women, and kids. The website is designed to be visually appealing with a black-and-white theme that includes images of fashion categories, a promotional banner, and buttons for shopping.

## Features

### Header Section
- Displays a sale announcement with a link to shop now.
- The background color is black with a golden link, making it prominent and eye-catching.

### Fashion Sale Section
- A stylish section featuring a background image for the fashion sale.
- Contains a brief description of the sale and a "Shop Now" button for easy navigation.
- Two buttons (`<` and `>`) are provided for potential future functionality to navigate between sale items.

### Fashion Categories Section
- Three sections representing different categories of fashion: Men’s, Women’s, and Kid’s fashion.
- Each category is represented by a circular image with text inside indicating the category name.
- A modern, clean design with images displayed in 200px by 200px squares.

### Button Actions
- "Shop Now" buttons are provided in the sale description and each category, which could be linked to shopping pages in a future implementation.

### Responsive Design
- The layout uses `flexbox` for the category section (`s2`), ensuring that the images are properly aligned and responsive on different screen sizes.

## How It Works

### HTML Structure:
- **Header**: Contains a simple sale message with a clickable "Shop Now" link.
- **Sale Section**: Displays an image (`fashion.jpg`) with two buttons for navigation and a brief description of the sale.
- **Categories Section**: Three div elements styled with background images (`mf.jpeg`, `wf.jpeg`, `kf.jpeg`) that represent different fashion categories, with text centered on the images.
- **Styling**: The CSS is structured to provide a minimalistic look with modern designs using colors such as black, red, light coral, and goldenrod.

### CSS Styling:
- **Positioning**: The `.st` section has a background image with `position: relative;` allowing the buttons and text inside to be positioned absolutely over it.
- **Flexbox Layout**: The `.s2` section uses `display: flex` to create a responsive layout for the three fashion category images, with `gap: 30px` ensuring space between each category.
- **Typography**: The page uses a combination of cursive and system fonts, with contrasting colors for text to enhance visibility and appeal.
  
## Technologies Used

- **HTML**: Structure for the website, including the header, sections, and buttons.
- **CSS**: Custom styling for layout, color, background images, and text styling.
- **Flexbox**: Used for the category section to ensure a flexible, responsive layout.
- **Positioning**: CSS positioning techniques (absolute and relative) to create the layered effects in the sale section.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Harisankar-A-18/FashionWebsite-HTML-CSS
    ```

2. Navigate to the project directory

3. Open the `index.html` file in your preferred web browser to view the page.

## Usage

- **Shop Now**: The "Shop Now" buttons are placeholders for linking to a shopping page or store.
- **Responsive Layout**: The website adjusts its layout for different screen sizes, ensuring a smooth experience on both mobile and desktop devices.

## Screenshot

### Fashion Sale Website
![image](https://github.com/user-attachments/assets/c3b314ff-ae45-4f24-a9b2-1d9e5b83ebac)


## Limitations

- **Functionality**: The buttons and links do not currently have actual functionality. The `Shop Now` button is a placeholder that can be linked to a shopping page.
- **Images**: Ensure the background images (`fashion.jpg`, `mf.jpeg`, `wf.jpeg`, `kf.jpeg`) are available in the project directory or update the `src` attributes to valid paths.
- **Mobile Optimization**: While the website is responsive, additional mobile-specific styling might be necessary for further optimization.

