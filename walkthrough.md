# Fatema Anif Portfolio Website - Walkthrough

Welcome back! The sophisticated, high-end portfolio website for **Fatema Anif** was successfully completed in our previous session and is ready to go. We've preserved the "luxury design studio" aesthetic you requested with soft neutral tones, elegant typography, and a dynamic interactive feel.

Here is a quick overview of what has been implemented based on your exact specifications.

## The Design Aesthetic
- **Color Palette:** Soft neutrals (ivory background, charcoal text) paired with a deep, sophisticated accent color (warm dusty rose/gold tones).
- **Typography:** We paired the elegant `Playfair Display` serif for headings with the clean, minimalist `Inter` sans-serif for body text.
- **Micro-interactions:** The site features custom CSS animations (like `fade-in-up`, `fade-in-left`) that trigger smoothly as you scroll down the page, alongside refined hover states.

## Site Structure & Features

### 1. Hero Section
Features a full-screen layout with an abstract artistic background. The tagline **"Where Aesthetics Meet Purpose"** is prominently displayed under Fatema's name, accompanied by a bold Call To Action to view her work.

![Hero Background](file:///C:/Users/ACB/.gemini/antigravity/brain/cb8ff2c8-6d1c-407a-8ff2-6957f6ec73f6/hero_abstract_bg_1778410224358.png)

### 2. About Me
A split two-column layout focusing on the intersection of visual elegance and functionality, alongside a beautiful professional photo placeholder.

![Profile Photo Placeholder](file:///C:/Users/ACB/.gemini/antigravity/brain/cb8ff2c8-6d1c-407a-8ff2-6957f6ec73f6/profile_office.jpg)

### 3. Projects & Work
A curated 3-column grid showcasing different design disciplines (UI/UX, Editorial, Packaging). Each card features a smooth hover effect revealing a "View Case Study" button over the custom placeholder thumbnails.

````carousel
![Aura Skincare - UI/UX](file:///C:/Users/ACB/.gemini/antigravity/brain/cb8ff2c8-6d1c-407a-8ff2-6957f6ec73f6/project_thumb_1_1778410382496.png)
<!-- slide -->
![Maison Magazine - Editorial](file:///C:/Users/ACB/.gemini/antigravity/brain/cb8ff2c8-6d1c-407a-8ff2-6957f6ec73f6/project_thumb_2_1778410646978.png)
<!-- slide -->
![Lumière Fragrance - Packaging](file:///C:/Users/ACB/.gemini/antigravity/brain/cb8ff2c8-6d1c-407a-8ff2-6957f6ec73f6/project_thumb_3_1778410681982.png)
````

### 4. Skills & Expertise
A clean, grid-based layout of subtle badges highlighting Fatema's core competencies—from Figma and Adobe XD to Typography and Brand Identity.

### 5. Client Reviews
A fully functional javascript-driven testimonial carousel displaying client quotes, star ratings, and roles. 

### 6. Contact
A minimalist, high-end contact form on one side with quick access to professional social links (Behance, LinkedIn, Instagram) on the other. 

> [!TIP]
> **View the live site locally:**
> You can preview the site right now! The local web server is currently running. Simply open **http://localhost:8080** in your web browser to explore the animations and layout.

### Code Organization
All the files are neatly organized in your workspace:
- `index.html` - The semantic HTML5 structure and layout.
- `styles.css` - The custom CSS styling, animations, and responsive breakpoints.
- `script.js` - The logic for the mobile menu, scroll observer animations, and the review carousel.
- `serve.ps1` - A script to quickly boot up a local server.
