# 🕐 Glassmorphism Digital Clock

A modern and responsive **Glassmorphism Digital Clock** built with **HTML, CSS, and JavaScript**.
The project features a beautiful animated gradient background, floating particles, glassmorphism UI, real-time clock updates, and a dynamic date display.

---

## ✨ Features

* 🕐 Real-time digital clock
* 📅 Dynamic day, date, month, and year
* 🎨 Animated gradient background
* ✨ Glassmorphism card design
* 🌌 Floating particle animation
* 💫 Clock pulse/glow animation
* 🖱️ Interactive click effect
* 🪄 Hover animation on the clock card
* 📱 Fully responsive design
* 🔤 Uses **Poppins** and **Orbitron** fonts
* ⚡ Updates automatically every second
* 🎯 Clean and minimal UI

---

## 🌐 Live Demo

🔗 **Live Demo:**  https://rafiullah-najat.github.io/Glassmorphism-Digital-Clock/

---

## 🛠️ Technologies Used

* **HTML5** — Page structure
* **CSS3** — Styling, animations, responsive design, and glassmorphism
* **JavaScript (ES6)** — Real-time clock, date, particles, and interactions
* **Google Fonts**

  * Poppins
  * Orbitron

---

## 📂 Project Structure

```text
Glassmorphism-Digital-Clock/
│
├── index.html
├── style.css
├── script.js
└── README.md
```

---

## 🎨 Design

The project uses a modern **Glassmorphism** design approach with:

* Transparent backgrounds
* Background blur
* Soft borders
* Subtle shadows
* Glowing typography
* Animated gradients
* Floating particles

The clock card also includes a hover effect that slightly lifts and scales the component.

---

## ⚙️ How It Works

### 🕐 Real-Time Clock

JavaScript creates a new `Date()` object and retrieves:

* Hours
* Minutes
* Seconds
* Day
* Date
* Month
* Year

The clock is then updated every second using:

```javascript
setInterval(updateClock, 1000);
```

### 🌌 Floating Particles

The `createParticles()` function dynamically generates 50 particles and gives each particle a random:

* Horizontal position
* Animation delay
* Animation duration

This creates a continuously moving background effect.

### 🖱️ Click Interaction

When the clock card is clicked, it temporarily scales down to create a small button-like interaction effect.

---

## 📱 Responsive Design

The project includes a responsive breakpoint for smaller screens.

On mobile devices:

* Clock width increases
* Font sizes are reduced
* Card padding is adjusted
* Title size becomes smaller

```css
@media (max-width: 768px) {
    .clock {
        width: 80%;
    }

    .time {
        font-size: 3rem;
    }
}
```

---

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Glassmorphism-Digital-Clock.git
```

### 2. Navigate to the Project

```bash
cd Glassmorphism-Digital-Clock
```

### 3. Open the Project

Simply open:

```text
index.html
```

in your browser.

No additional dependencies or installation are required.
---

## 📚 What I Learned

While building this project, I practiced and improved my understanding of:

* DOM manipulation
* JavaScript `Date` object
* `setInterval()`
* Dynamic element creation
* CSS animations
* CSS `@keyframes`
* Glassmorphism UI
* CSS gradients
* `backdrop-filter`
* Responsive web design
* JavaScript event listeners
* Modern UI/UX techniques

---

## 👨‍💻 Author

**Rafiullah Najat**

Frontend Developer passionate about creating modern, responsive, and interactive web experiences.

---

## ⭐ Support

If you like this project, consider giving the repository a ⭐ on GitHub.

