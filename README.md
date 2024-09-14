

# 📸 BlackLens Photography - README

## Overview

Welcome to the **BlackLens Photography** portfolio! This website is a **single-page HTML portfolio** built using **Tailwind CSS** for styling and **Cofic** for additional style management. The focus of this portfolio is to showcase the photographer’s best work with a clean and modern design, emphasizing visual storytelling through high-quality imagery.

The site includes:
- Hero Section with captivating imagery
- Service Overview (Wedding, Portrait, Commercial photography)
- Portfolio grid with featured images
- Client testimonials and contact information

---

## 💻 How to Set Up the Project

1. **Download the Repository**:
   Clone or download the repository to your local machine:
   ```bash
   git clone https://github.com/YourRepo/BlackLensPhotography.git
   ```

2. **File Structure**:
   - **index.html**: The main single-page HTML file for the portfolio.
   - **/assets**: Contains all the images, including portfolio images and brand logos.
   - **/css**: A folder where Tailwind directives are stored if needed for custom CSS.

3. **Installation**:
   Tailwind CSS and Cofic are included via CDN, so you do not need any additional npm installation. Simply open the `index.html` file in your browser to view the site.
   
4. **Tailwind CSS and Cofic Setup**:
   - **Tailwind CSS** is linked via CDN for styling:
     ```html
     <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
     ```
   - **Cofic** is included for extra style management:
     ```html
     <script src="https://cdn.cofic.io/latest/cofic.min.js"></script>
     ```

---

## 🖼️ Key Website Sections

### **Hero Section**:
This section is designed to make a strong visual impact with high-quality images and a bold headline:
```html
<section class="bg-black text-white h-screen flex flex-col justify-center items-center">
  <h1 class="text-5xl md:text-6xl font-bold">Capturing Timeless Moments</h1>
  <p class="text-lg md:text-xl mt-4">One Frame at a Time</p>
</section>
```

### **Portfolio Grid**:
A dynamic grid showcasing the photographer's best work across different categories:
```html
<section class="grid grid-cols-1 md:grid-cols-3 gap-6 p-10">
  <img class="w-full h-auto object-cover" src="assets/wedding1.jpg" alt="Wedding Moments">
  <img class="w-full h-auto object-cover" src="assets/portrait1.jpg" alt="Authentic Portraits">
</section>
```

### **Testimonials**:
Featuring client reviews to build trust and credibility:
```html
<section class="p-10 bg-gray-100">
  <div class="text-center mb-8">
    <h2 class="text-4xl font-bold">What Our Clients Say</h2>
  </div>
  <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
    <div class="p-6 bg-white rounded-lg shadow">
      <p>"Ethan's ability to capture raw emotions is unmatched. Highly recommend!"</p>
      <p class="mt-4 font-bold">- Sarah Jones</p>
    </div>
  </div>
</section>
```

---

## 🎨 Tailwind CSS Styling Guide

### **Fonts & Colors**:
- **Primary Fonts**: The portfolio uses **serif** and **sans-serif** combinations for readability and elegance:
   ```css
   font-family: 'Inter', sans-serif;
   ```
- **Colors**: The design relies on a **monochromatic black and white palette** to bring focus to the images:
   ```css
   bg-black, text-white, hover:text-gray-300
   ```

### **Button Styling**:
Buttons across the site use Tailwind classes for hover effects and transitions:
```html
<button class="bg-white text-black hover:bg-gray-300 px-4 py-2 rounded-full transition duration-300 ease-in-out">
```

---

## 🚀 Deployment Instructions

- **GitHub Pages**: Upload the HTML file to a GitHub repository and enable GitHub Pages from the settings.
- **Netlify** or **Vercel**: Drag and drop the project folder for automatic deployment.

---

## 🔗 Contact

For any questions or collaboration requests, feel free to contact:
- **Email**: hello@blacklensstudio.com
- **Phone**: +1 123-456-7890

---
