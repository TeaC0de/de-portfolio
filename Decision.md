# ⚙️ de-portfolio | Development Notes & Technical Decisions

This file collects the development-side decisions I made while building **de-portfolio**. It’s where I documented what I built, how I structured things, what I removed, and what I learned as I went.

It’s not a guide — just a log of my current understanding and the steps I took to build something that reflects where I am as a beginner in front-end development.

---

## 🛠️ Tech Stack

- **HTML** – for structure and content  
- **CSS** – written by hand (vanilla CSS, no frameworks)   
- **Fonts** – Dancing Script & Lora (Google Fonts)  
- **File structure** – simple static project without bundlers, frameworks, or pre-processing
- **Version control** – Git for local tracking + GitHub repo

I wanted to stay close to the basics and learn by writing everything myself first.

---

## 🔧 Development Notes

- Focused on handwritten structure and styling to learn foundational HTML/CSS 
- Avoided libraries and frameworks for now to fully understand layout and flow    
- JavaScript will be added in future phases — for interactivity like hover states, transitions, and small animations 
- Will gradually improve responsiveness and mobile layout as I go

---

## 📁 Project Structure

I kept the folder structure flat and simple — just enough to stay organized without overcomplicating things.

- Separate HTML pages for major sections   
- `/css`, `/js`, and `/assets` folders for separation  
- Using plain files, no frameworks or bundlers

The full structure is listed in the `README.md`, so I didn’t repeat it here.

---

## 🧱 Layout Choices

- Chose a **long-scroll layout** for smoother storytelling  
- **Projects** and **CV/Certifications** open in **new tabs** to avoid cluttering the main scroll  
- HTML uses semantic tags like `<section>` where possible  
- Navigation is built with anchor links — no JavaScript needed yet  
- CSS is written with variables for colors and font settings (`:root { --primary-color: ... }`)

---

## 🧠 What I Had to Learn

- How to structure anchor-based navigation without breaking the scroll  
- When to use `<div>` vs. `<section>` — still figuring that out  
- How to import fonts and set fallback values
- How to write custom properties in CSS and keep colors consistent  
- Basic accessibility considerations (like contrast and font size)

These were small things, but they taught me a lot about *how front-end actually works* in practice.

---

## 🔄 What I’d Do Differently Next Time

- Plan mobile layout from the beginning  
- Use Git from the very beginning instead of halfway through  
- Organize styles by component or section to reduce repetition  
- Possibly explore SCSS or Tailwind once I’m confident with vanilla CSS

---

## ✅ In Progress / Next Steps


- I’m using classic multi-page navigation — each major section opens as a separate `.html` file. The homepage itself is a single-scroll layout with anchor links for a smooth flow.
- I chose not to use JavaScript-based routing or SPA frameworks for now — keeping it static helps me focus on structure, layout, and fundamentals.
- Accessibility is still new to me — contrast and readable fonts were my first focus  
- Will add:
  - JavaScript for interactivity (e.g. hover effects, animations)
  - A contact form  
  - A more responsive layout   
  - Detailed project pages with screenshots and code samples

## 💭 Final Thoughts

This file isn’t polished — and it’s not meant to be. It’s just a record of how I approached this project. I’ll keep learning, keep refining, and update this as I go.
