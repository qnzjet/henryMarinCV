# 📄 Henry Marin — CV Website

This is a **responsive, single-page résumé/CV** built in plain **HTML + CSS**.  
It’s designed to be lightweight, print-friendly, and easily editable for updates.

---

## 🚀 Features

- **Responsive Layout**  
  Works well on desktop and mobile. Floats collapse into a stacked layout on small screens.

- **Clean Typography & Sections**  
  Uses the *Rokkitt* font for headings and *Lato* for body text (via Google Fonts).

- **Animated Fade-in**  
  Subtle `fade-in` animations for main blocks (`.instaFade`, `.quickFade`).

- **Sections Included**  
  - Header with **name, title, headshot, contact info**
  - **Work Experience** with dates and descriptions
  - **Key Skills** with multi-column display
  - **Education**

- **Print Friendly**  
  Minimal colors and clean layout for printing as PDF.

---

## 📂 Project Structure
/cv-project
├── index.html   # Main CV content
├── style.css    # Styling, layout, animations
└── hmlogo.jpg   # Profile image/logo (replace with your own)

---

## 🛠 How to Use

1. Clone/download this repo or copy the files into a folder.
2. Open `index.html` in your browser to view the CV.
3. Edit `index.html` to update:
   - Name, title, and contact info
   - Work Experience items
   - Skills list
   - Education section
4. Customize `style.css` for colors, fonts, or layout.

---

## 🎨 Customization Tips

- **Fonts**: Change the Google Fonts link in `<head>` to another family.
- **Colors**:  
  - Header line and section titles use `#cf8a05` (accent orange).  
  - Background card uses `#f3f3f3` on top of page background `#181818`.  
  - Update in `style.css` to match your brand.
- **Animations**: Remove `.instaFade` / `.quickFade` classes in `index.html` if you don’t want fade-ins.
- **Profile image**: Replace `hmlogo.jpg` with your own photo/logo (square image recommended).

---

## 📸 Screenshot (example)

![CV Screenshot](https://via.placeholder.com/800x600?text=CV+Preview)

*(replace with an actual screenshot of your CV once rendered)*

---

## 📦 Deployment

- **Local**: Just open `index.html` in a browser.
- **Web hosting**: Upload the folder to GitHub Pages, Netlify, or any static host.
- **PDF Export**:  
  In Chrome: `File → Print → Save as PDF` for a clean résumé PDF.

---

## 🧭 Roadmap / Ideas

- Add a **Projects** section
- Add **social links** (LinkedIn, GitHub, portfolio site)
- Dark-mode toggle
- Convert into a simple **React/Vue component** for live updates

---

## 📜 License

This CV template is open for personal use.  
Feel free to fork, edit, and share — just keep attribution appreciated.
