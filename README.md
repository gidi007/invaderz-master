# InvaderZ

A genetic evolution twist on the classic Space Invaders game. Watch as the invaders evolve and adapt to your play style using genetic algorithms!

## 🎮 Game Overview

InvaderZ puts you in command of Earth's last defense against an alien invasion. Unlike traditional Space Invaders, these aliens evolve through genetic algorithms, learning from each generation's successes to become more challenging opponents.


![Screenshot](./Screenshot.png)

## 🚀 How to Play

- **Controls:**
  - Move Left: Left Arrow or A key
  - Move Right: Right Arrow or D key
  - Shoot: Space Bar
  - Mobile: On-screen buttons

- **Game Rules:**
  - You can only fire one projectile at a time
  - Game ends if 5 invaders reach Earth
  - Each wave consists of 7 generations of evolving invaders
  - After 7 generations, a new wave starts with the best performers retained

## 🧬 Genetic Algorithm Implementation

The invaders evolve using the following mechanics:

1. **Initial Population:** Random invader shapes are generated
2. **Fitness Score:** Based on how far invaders penetrate Earth's atmosphere
3. **Evolution Process:** 
   - High-scoring invaders are crossed over using 6 different methods:
     - Horizontal half splits (2 variations)
     - Vertical half splits (2 variations)
     - Odd/Even gene combinations (2 variations)
   - 10% mutation chance to alter body shape and movement patterns
4. **Wave Reset:** Every 7 generations, a new population is created while retaining top performers

## 🎯 Key Features

- Shape-based movement patterns
- Real-time genetic evolution
- Progressive difficulty through adaptation
- Mobile-friendly design
 

## 📱 Mobile Installation

Add to your phone's home screen through your browser's "Add to Home Screen" option.

## 👤 Author

Created with ❤️ by Gideon Bawa || gidi007