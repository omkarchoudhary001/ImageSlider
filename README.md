# Image Slider README

## Overview

Welcome to the Image Slider project! This is a simple and customizable image slider built using HTML, CSS, and JavaScript. It allows you to display a series of images in a slideshow format on your website.
![Screenshot (34)](https://github.com/omkarchoudhary001/ImageSlider/assets/109873576/d94a6f71-8ae3-4b77-a2ca-fd2423ee5a7c)

## Features

- Responsive design: The image slider is designed to work seamlessly on various screen sizes, from desktops to mobile devices.
- Customizable: Easily customize the appearance and behavior of the slider by modifying the CSS and JavaScript code.
- Lightweight: The code is lightweight and optimized for performance to ensure smooth transitions between images.

## How to Use

1. **Download the Repository:**
   - Clone the repository using `git clone` or download the ZIP file.

2. **Include Files:**
   - Copy the `index.html`, `styles.css`, and `script.js` files to your project.

3. **Add Images:**
   - Place your desired images in the `images` folder.

4. **Customize Settings (Optional):**
   - Open the `script.js` file to customize slider settings, such as transition speed, autoplay, and more.

5. **Include Dependencies (Optional):**
   - If not already included, make sure to include the latest versions of jQuery or other libraries if you plan to use them.

6. **Include Styles (Optional):**
   - Customize the styles in the `styles.css` file to match your website's design.

7. **Embed HTML:**
   - Add the following HTML code where you want the image slider to appear:

     ```html
     <div class="slider-container">
       <div class="slider">
         <!-- Images will be dynamically added here -->
       </div>
       <div class="prev-btn" onclick="changeSlide(-1)">&#10094;</div>
       <div class="next-btn" onclick="changeSlide(1)">&#10095;</div>
     </div>
     ```

8. **Initialize Slider:**
   - Initialize the slider by adding the following script just before the closing `</body>` tag:

     ```html
     <script>
       document.addEventListener("DOMContentLoaded", function() {
         initSlider();
       });
     </script>
     ```

9. **Test Your Slider:**
   - Open your HTML file in a web browser and test the image slider.
   - ![Screenshot (33)](https://github.com/omkarchoudhary001/ImageSlider/assets/109873576/4edba9d1-b304-4296-8486-1e197946a9ac)


## Configuration Options

The `script.js` file contains various configuration options that you can adjust to customize the image slider according to your needs. These options include:

- `imageFolder`: Specify the folder where your images are stored.
- `transitionSpeed`: Adjust the speed of image transitions.
- `autoplay`: Enable or disable autoplay functionality.
- `autoplaySpeed`: Set the autoplay interval.

Feel free to explore and modify these options to suit your requirements.
