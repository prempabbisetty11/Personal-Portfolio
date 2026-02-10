# Personal-Portfolio
Developed a personal portfolio website to showcase my skills, projects, and experience. Designed using HTML, CSS, and JavaScript with responsive layout, highlighting areas like Web Development, Artificial Intelligence, Machine Learning, NLP, and Data Handling.
# Personal Portfolio Website

## Overview

This is a personal portfolio website for **Prem Pabbisetty**, a B.Tech student specializing in Artificial Intelligence and Machine Learning. The site showcases skills, projects, education, and contact information, and features a responsive design for both desktop and mobile devices.

## Features

- **Responsive Design:** Works on desktop and mobile screens.
- **Navigation Menu:** Hamburger menu for mobile view.
- **About Section:** Skills, projects, and education tabs.
- **What I Do:** Highlights expertise in web development, AI/ML, NLP, and data handling.
- **Portfolio:** Displays project images and descriptions.
- **Contact Form:** Allows visitors to send messages directly to your Google Sheet.
- **Download CV:** Button to download your resume.
- **Social Links:** LinkedIn, GitHub, Instagram, Facebook.

## File Structure

```
Personal-Portfolio/
│
├── index.html          # Main HTML file
├── style.css           # Custom CSS styles
├── images/             # Folder for logo and portfolio images
│   ├── logo.jpg
│   ├── 1696349697570.jpg
│   ├── portfolio1.jpg
│   ├── portfolio2.png
│   ├── portfolio3.png
│   └── portfolio4.jpg
├── Prem_Pabbisetty_CV_.pdf  # Resume file
```

## Google Sheets Integration

The contact form uses [Google Apps Script](https://script.google.com/) to send submissions to a Google Sheet.

- **Script URL:**  
  `https://script.google.com/macros/s/AKfycbz2P137o5BeeDWEOnWU9VKMVe-_rmby9zR-jVvKDTOyXwVBtchNjf9z-bEcnge52aQHkg/exec`
- **How it works:**  
  When a user submits the form, the data is sent via a POST request to the Apps Script, which adds the entry to your Google Sheet.
- **Setup:**  
  - Create a Google Sheet.
  - Write and deploy a Google Apps Script as a web app (set access to "Anyone, even anonymous").
  - Use the script URL in your HTML form handler.

## How to Run Locally

1. **Clone or download** this repository.
2. Place all files in a single folder.
3. Open `index.html` in your browser.
4. Make sure the `images` folder and `style.css` are in the same directory as `index.html`.

## How to Publish Online

- **GitHub Pages:**  
  Upload your files to a GitHub repository and enable GitHub Pages in repository settings.
- **Netlify/Vercel:**  
  Drag and drop your folder to [Netlify](https://www.netlify.com/) or [Vercel](https://vercel.com/) for instant deployment.

## Customization

- **Update images** in the `images/` folder.
- **Edit content** in `index.html` for your own skills, projects, and contact info.
- **Modify styles** in `style.css` for your preferred look.

## Credits

- Icons from [Font Awesome](https://fontawesome.com/)
- Portfolio template inspired by YouTube tutorials

---

**Contact:**  
Email: premsai620@gmail.com  
LinkedIn: [Prem Pabbisetty](https://www.linkedin.com/in/prem-pabbisetty-037a89262/)  
GitHub: [prempabbisetty11](https://github.com/prempabbisetty11)
