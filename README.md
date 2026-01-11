# 🎫 TicketGen: Professional Event Registration System

## 📌 Description
TicketGen is a sleek, responsive web application designed for seamless event discovery and instant ticket generation. Built with a "glassmorphism" aesthetic, it allows users to browse upcoming academic and tech events, register with their details, and download a custom-generated PNG ticket featuring a unique QR code.

## ✨ Features
 - 📅 **Event Management:** Browse a curated list of upcoming summits, workshops, and masterclasses.
 - 🔍 **Smart Sorting:** Sort events by date (Earliest or Latest) to find what suits your schedule.
 - 📝 **Instant Registration:** User-friendly modal interface for quick sign-ups with email validation.
 - 🖼️ **Dynamic Ticket Generation:** Generates a high-quality visual ticket on the fly using HTML5 Canvas.
 - 🛡️ **Validation & Security**
      - **Email Validation:** Uses Regex to ensure users provide a correctly formatted email address.
      - **Canvas Security:** Implements `crossOrigin = 'Anonymous'` to safely handle external QR code images during the PNG generation process.
 - 📲 **QR Code Integration:** Every ticket includes a unique QR code containing event and attendee metadata.
 - 📥 **PNG Download:** One-click download to save your professional entry pass for offline use.
 - 📱 **Fully Responsive:** Optimized for desktop, tablet, and mobile devices.

## 🛠️ Technology Stack
 - **HTML5:** Semantic structure and Canvas API for image rendering.
 - **CSS3:** Advanced styling using CSS Variables, Flexbox, Grid, and smooth animations.
 - **JavaScript (Vanilla):** All logic for sorting, modal handling, and ticket generation—no heavy frameworks required.
 - **QR Server API:** Real-time generation of attendee-specific QR codes.

## 📖 How It Works
 - **Browse:** Scroll through the list of events or use the Sort by dropdown to organize them.
 - **View Details:** Click the Details button to see the Chief Guest, timing, and a brief description.
 - **Register:** Hit Register, enter your name and email, and click Generate Ticket.
 - **Preview & Download:** Your ticket will appear instantly in the sidebar. Review it and click Download Ticket (PNG) to save it to your device.

## 🚀 Live Demo
https://aaiswaryapm.github.io/TicketGen/

## 📂 Project Structure
```
TicketGen/
├── index.html              
├── style.css
├── script.js       
└── README.md
