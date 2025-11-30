WellBeing Journey ☁️ – Mental Health Platform UI

A comforting, accessible, and Filipino-centered UI design made for mental health service providers and users seeking support.
Soft, gentle, and designed to feel like a safe place. 💙

🌟 Design Philosophy

WellBeing Journey is built around one core principle:
👉 Emotional safety first.
Every design choice ensures users feel welcomed, unjudged, and supported.

Core Design Principles

🌿 Comforting & Safe – Soft colors, friendly visuals, and emotional warmth

✨ Minimalist & Clean – Clarity over clutter, breathable whitespace

📱 Mobile-First & Intuitive – One-hand use with large tap targets

🟦 Rounded, Soft UI – Corner radius 16–24px with soft shadows

🎞️ Subtle Animations – Gentle, calm fade-ins and slides

🛡️ Anonymous & Respectful UX – Privacy-first approach

🇵🇭 Filipino-Centered – Cultural touches and native terms

♿ Accessible & Inclusive – WCAG compliant + screen reader support

💛 Gentle Monetization – “Coffee credits” for appreciation, not paywalls

😊 Emotionally Responsive – Mood-aware interactions, easy exit options

🎨 Design System
Color Palette
Light Theme

Primary: #667eea

Secondary: #f093fb

Background: #ffffff

Surface: #f8fafc

Text Primary: #1e293b

Text Secondary: #64748b

Dark Theme

Background: #0f172a

Surface: #1e293b

Text Primary: #f1f5f9

Text Secondary: #cbd5e1

Typography

Family: Inter (Google Fonts)

Weights: 300–700

Base size: 16px

Line height: 1.6

Spacing System

8px, 16px, 24px, 32px, 48px, 64px

Border Radius

8px, 16px, 24px, 32px

🚀 Features
Core Services

📝 Himpil – Anonymous venting space

🧑‍⚕️ Kalinga – Professional mental health services

☕ Tara Kape – 1-on-1 conversations with listeners

Interactive Elements

🌗 Theme toggle (light/dark)

📱 Mobile-friendly menu

🚶 Smooth scrolling

🎁 Coffee credits modal

✨ Scroll animations

Accessibility Features

ARIA labels

Full keyboard navigation

Focus indicators

Skip links

Respects reduced motion

High contrast mode

📱 Responsive Design
Breakpoints

Mobile: < 768px

Tablet: 768px – 1024px

Desktop: > 1024px

Mobile-first: card layouts, 48px buttons, slide transitions.

🛠️ Technical Implementation
File Structure
UI/
├── index.html
├── styles.css
├── script.js
└── README.md

Dependencies

Font Awesome 6.4.0

Inter Font

Vanilla JavaScript

Browser Support

Chrome 90+, Firefox 88+, Safari 14+, Edge 90+

🎯 User Experience
Emotional Safety Features

Gentle color transitions

Smooth 0.3s animations

Escape-to-close support

Anonymous-by-default design

Non-triggering wording

Filipino Cultural Integration

Names like Himpil, Kalinga, Tara Kape

Coffee as a symbol of connection

“Salamat” in gratitude messages

Respectful, warm tone

🔧 Customization
Theme Variables
:root {
  --primary-color: #667eea;
  --spacing-md: 1.5rem;
  --font-family: 'Inter', sans-serif;
}

Adding New Services

Add card structure

Add Filipino naming

Maintain consistent styling

Add ARIA tags

Extending Animations

Uses Intersection Observer:

const observer = new IntersectionObserver((entries) => {
  entries.forEach(entry => {
    if (entry.isIntersecting) {
      entry.target.classList.add('animate-in');
    }
  });
});

🚀 Getting Started

Clone or download

Open index.html

Resize to test responsiveness

Try keyboard + screen reader features

📊 Performance

FCP: < 1.5s

LCP: < 2.5s

CLS: < 0.1

FID: < 100ms

🤝 Contributing
Design Guidelines

Maintain emotional safety

WCAG AA compliance

Use Filipino cultural meaning

Keep UI minimalist

Code Guidelines

Semantic HTML

CSS variables

Document JS functions

Accessibility first

📞 Support

Design: Check philosophy section

Tech: Browser compatibility

Accessibility: Screen reader testing

Cultural help: Consult Filipino MH experts

📄 License

Designed for community mental health support.
Use respectfully and responsibly.

Made with ❤️ for the Filipino community
WellBeing Journey – Your quiet space to vent, talk, and heal. ☁️
