# Portfolio Website

This project is a personal portfolio website that showcases your skills, projects, and social links. It features an animated introduction, a responsive navigation bar, and interactive sections.

## Features

### 1. **Navigation Bar**

- Fixed at the top with smooth animations.
- Contains links to various sections like Home, About, Portfolio, Service, and Contact.
- Highlighted hover effects.

### 2. **Animated Text**

- Rotating text animation under the introduction heading (e.g., "Frontend Developer," "Youtuber," etc.).
- Text typing effect combined with visibility toggling for dynamic emphasis.

### 3. **Home Section**

- Includes a name, description, and call-to-action buttons:
  - Download CV button.
  - Social media links with hover effects.
- Profile image with circular rotating borders using CSS animations.

### 4. **Bars Animation**

- Full-page vertical bars animation displayed during page load.
- Creates a visually appealing entrance effect.

## Technologies Used

### **HTML**

- Structured the content for easy navigation and display.

### **CSS**

- Custom animations using `@keyframes` for:
  - Text display and typing effects.
  - Rotating circular borders.
  - Bars animation during page load.
- Responsive and visually attractive styling using Flexbox and CSS variables.
- `Boxicons` library for social media icons.

### **Fonts**

- Utilized the Poppins font from Google Fonts for modern and clean typography.

## File Structure

```
.
├── index.html     # Main HTML file
├── style.css      # Main CSS file
├── home.png       # Placeholder for profile image
└── README.md      # Project documentation
```

## Installation and Usage

### Step 1: Clone the Repository

```bash
git clone https://github.com/RatulInnovates/portfolio.git
cd portfolio
```

### Step 2: Open in Browser

Simply open the `index.html` file in your preferred browser to view the website.

## Key Sections

### **Navbar**

- Positioned using Flexbox for layout.
- Animated visibility effect using `@keyframes`.

### **Home Section**

- Includes rotating text with a typing animation.
- Styled buttons with hover effects for the CV and social media links.

### **Bars Animation**

- Adds dynamic entrance animation using vertical bars.
- Utilizes CSS variables for staggering animation delays.

### **Profile Image**

- Circular profile image with conic-gradient rotating borders.

## Customization

You can customize the content and appearance of the portfolio:

1. **Update Your Name and Roles**

   - Modify the `<h1>` and `<h2>` in the `index.html` file to reflect your name and roles.

2. **Replace the Profile Image**

   - Replace `home.png` with your own profile picture.

3. **Add Social Media Links**

   - Update the anchor tags inside the `.sci` div with your social media profile URLs.

4. **Change the Colors**

   - Update the `--i` values and color variables in the CSS file for a personalized theme.

## Preview

- **Navbar:**

- **Home Section:**

## Future Improvements

- Add additional sections like Projects, Services, and Contact forms.
- Improve accessibility with ARIA labels and semantic HTML.
- Implement JavaScript for enhanced interactivity (e.g., dynamic loading or light/dark mode).

## License

This project is open-source and free to use under the MIT license.

