# Program Details Timeline

A clean, modern, and visually appealing Timeline component designed to display event details, course essentials, or program schedules. Built entirely with HTML and pure CSS, it features a balanced, alternating left-to-right zigzag layout along a central vertical axis.

## ✨ Key Features

- **Pure HTML & CSS:** Lightweight and fast, requiring zero JavaScript.
- **Alternating Layout:** Beautiful zigzag timeline structure (left/right nodes) connected by a central axis line.
- **Icon Integration:** Uses FontAwesome 6.0 for clean, intuitive visual cues.
- **Modern Aesthetic:** Professional blue color palette with soft border radiuses and clear typography.
- **Easy to Customize:** Colors, fonts, icons, and text can be quickly adapted for any project.

## 🛠️ Technologies Used

- **HTML5:** Semantic content structuring.
- **CSS3:** Advanced layout management including Flexbox, CSS `calc()`, absolute positioning, and pseudo-elements (`::before`).
- **FontAwesome v6.0.0:** For scalable vector icons (served via CDN).

## 📂 Project Structure

```text
.
├── index.html     # The core timeline structure and text content
├── style.css      # The stylesheet containing the timeline design rules
└── README.md      # Project documentation
```

## 🚀 Getting Started

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/seljanzeynalovacode/Web_Task.git
   ```
2. Navigate to the project directory.
3. Open `index.html` in any modern web browser to view the timeline. No server installation is required.

## 🎨 Customization Guide

You can easily adapt this timeline for your own brand or event by modifying the `style.css` file:

- **Main Background:** Find the `body` selector and change `background: #2a5fd0;`.
- **Card Background:** Find the `.content` selector and modify `background: #3f84f2;`.
- **Icon Colors:** Find the `.icon` selector to change the icon and circle colors.
- **Content & Icons:** Open `index.html` to update titles, subtitles, and FontAwesome classes (e.g., `<i class="far fa-clock"></i>`).
