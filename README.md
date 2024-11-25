# African Hairstyles Catalog App

## Overview
The **African Hairstyles Catalog App** is an interactive and visually appealing web application designed to showcase various traditional and modern African hairstyles. Users can browse through a well-categorized catalog, view hairstyle details, and filter styles by categories such as Tresses, Naturelles, Protectrices, and more. The app supports a dark mode interface for enhanced user experience.

## Features
- **Dynamic Hairstyle Catalog**: Displays a grid of hairstyles with images, descriptions, pricing, and estimated time for completion.
- **Category Filters**: Users can filter hairstyles by different categories for a more focused browsing experience.
- **Dark Mode Support**: Includes dark and light mode options for better accessibility and user comfort.
- **Image Modal View**: Clicking on any hairstyle image opens a modal for an enlarged view.
- **Responsive Design**: The layout is optimized for both desktop and mobile devices.
- **Animation Effects**: Utilizes AOS (Animate on Scroll) for subtle and engaging animations.

## Technologies Used
- **HTML**
- **CSS**
- **JavaScript**
- **Tailwind CSS**
- **AOS Library**
- **Django** (for static file serving)

## Folder Structure
```
project-root/
|-- static/
|   |-- images/
|   |   |-- 1.JPEG
|   |   |-- ... (other images)
|-- templates/
|   |-- index.html
|-- css/
|   |-- styles.css
|-- js/
|   |-- main.js
|-- README.md
```

## How to Run
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/african-hairstyles-catalog.git
   ```
2. **Navigate to the Project Directory**:
   ```bash
   cd african-hairstyles-catalog
   ```
3. **Serve the App (Using Django)**:
   Make sure Django is installed, then run:
   ```bash
   python manage.py runserver
   ```
4. **Access the App**:
   Open your web browser and navigate to `http://127.0.0.1:8000/`.

## Customization
- **Adding New Hairstyles**: Update the `images` folder with new images and modify the `index.html` file to add new cards.
- **Adjusting Categories**: Modify the category filter buttons and corresponding data attributes in `index.html`.
- **Styling**: Customize `styles.css` for design tweaks and color scheme changes.

## Deployment
1. **Collect Static Files**:
   ```bash
   python manage.py collectstatic
   ```
2. **Deploy to Your Preferred Hosting Service** (e.g., Vercel, Heroku).

## License
This project is licensed under the MIT License.

## Contact
**Developer**: Alexandra Ebogo  
**Email**: alexandraebogo@icloud.com

Feel free to reach out for questions or suggestions!# andra-beauty
