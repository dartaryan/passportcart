# passportcart
### PassportCard Game

A Hebrew browser-based game built with HTML5 Canvas and vanilla JavaScript where players control a character to collect beneficial items and shoot hazardous ones.

## Game Overview

Players control a PassportCard character that must:
- **Collect** green beneficial items (suitcases, tickets, health cards, etc.)
- **Shoot** red hazardous items (viruses, invoices, storms, etc.) with laser beams
- **Survive** by avoiding contact with hazards and preventing them from reaching the ground

## Features

- **Progressive Difficulty**: Game speed increases over time
- **Particle Effects**: Visual feedback for collisions and scoring
- **Floating Score Text**: Real-time score display with animations
- **Touch Controls**: Mobile-friendly interface with on-screen buttons
- **Lives System**: 3 lives with visual heart indicators
- **Responsive Design**: Adapts to different screen sizes

## Controls

### Desktop
- **Arrow Keys** or **A/D**: Move left/right
- **Spacebar**: Shoot laser beams

### Mobile
- **Touch buttons**: Left/Right movement and fire controls
- **Responsive layout** optimized for mobile devices

## Game Elements

### Collectible Items (Green)
- 🎒 Suitcase (10 points)
- 🎫 Ticket (15 points)
- 🩺 Health Card (25 points)
- ☀️ Sun (10 points)
- 📱 Smartphone (20 points)

### Hazardous Items (Red)
- 🦠 Virus (-1 life)
- 📃 Invoice (-1 life)
- 💉 Syringe (-1 life)
- 🧳 Luggage (-1 life)
- ⛈️ Storm (-1 life)

## Technical Details

- **Built with**: HTML5 Canvas, Vanilla JavaScript, Tailwind CSS
- **Responsive**: Uses CSS Grid and Flexbox
- **Animations**: CSS keyframes and Canvas animations
- **Icons**: Font Awesome integration
- **Typography**: Rubik font family (Hebrew support)

## Browser Support

- Modern browsers with Canvas support
- Mobile browsers (iOS Safari, Chrome Mobile)
- Touch event support for mobile controls

## Running the Game

Simply open `passportcard.html` in a web browser. No additional setup or dependencies required.
