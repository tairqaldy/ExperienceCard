# Profile Card

A **Profile Card** project showcasing a clean and modern design for representing personal or professional profiles. The card includes sections for About, Work Experience, and Contact Information. It is interactive and dynamically switches between sections.

## Table of Contents

- [Overview](#overview)
- [Technologies Used](#technologies-used)
- [Features](#features)
- [Challenges and Solutions](#challenges-and-solutions)
- [Usage Instructions](#usage-instructions)
- [Future Improvements](#future-improvements)

---

## Overview

This project is a simple, responsive profile card designed to display information about an individual, including their **bio**, **work experience**, and **contact details**. The design focuses on:

- **User-Friendly Interface**: Clean and interactive design elements.
- **Modern Technologies**: Leveraging CSS animations and dynamic DOM manipulation.
- **Professional Look**: Suitable for personal branding or as a template for various users.

---

## Technologies Used

- **HTML5**: For creating the structure of the card.
- **CSS3**: For styling, animations, and responsiveness.
- **JavaScript**: For dynamic interactions between sections.

### Additional Resources
- Fonts: [Google Fonts](https://fonts.google.com/) - *Jost* and *DM Sans*.
- Background Images: [Unsplash](https://unsplash.com/).

---

## Features

### Design
- **Responsive layout**: Adapts to different screen sizes.
- **Dynamic transitions**: Smooth animations when switching between sections.

### Content Sections
- **About**: Short bio with highlights of expertise.
- **Work Experience**: Timeline displaying career highlights.
- **Contact**: Includes location, phone, and email with icons.

### Social Links
- Direct access to Instagram, LinkedIn, GitLab, and GitHub profiles.

---

## Challenges and Solutions

### 1. Git Push Errors
**Problem**: Faced `src refspec main does not match any` and `Updates were rejected because the remote contains work that you do not have locally` errors when pushing to GitHub.

**Solution**:
- Initialized the repository locally with `git init`.
- Pulled the changes from the remote repository using:
  ```bash
  git pull origin main --allow-unrelated-histories
  ```
- Resolved any merge conflicts and successfully pushed changes using:
  ```bash
  git push -u origin main
  ```

### 2. Styling Consistency
**Problem**: Ensuring consistent design across different screen sizes.

**Solution**:
- Utilized relative units like `em` and `%`.
- Implemented media queries to adjust layout and font sizes.

### 3. SVG Icons Not Displaying Properly
**Problem**: Some icons (e.g., LinkedIn, GitHub) were not rendering correctly.

**Solution**:
- Ensured proper paths for SVG files.
- Verified compatibility with browsers and added fallback styles.

---

## Usage Instructions

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/tairqaldy/ExperienceCard.git
   ```
2. Navigate to the project folder:
   ```bash
   cd ExperienceCard
   ```
3. Open `index.html` in a browser to view the card.

### Customization
- Replace images and text in the HTML file to personalize the card.
- Modify the `styles.css` file to adjust colors, fonts, or layout.
- Update links in the **social** section to match your profiles.

---

## Future Improvements

1. **Theme Options**: Add light and dark mode for better user accessibility.
2. **More Interactivity**: Include collapsible sections or tabs.
3. **Database Integration**: Store and retrieve user data dynamically.
4. **Mobile Optimizations**: Further refine responsiveness for smaller screens.

---

## Contact
If you have any questions or feedback, feel free to reach out:

- **Email**: tair.caldy@mail.ru
- **Phone**: +7 (707) 167 7003
- **GitHub**: [@tairqaldy](https://github.com/tairqaldy)
- **LinkedIn**: [Tair Kaldybayev](https://www.linkedin.com/in/tair-kaldybayev-922198312/)

---

### License
This project is open source and available under the [MIT License](LICENSE).
