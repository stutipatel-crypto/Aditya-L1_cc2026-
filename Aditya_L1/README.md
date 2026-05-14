# Aditya_L1

## Getting Started

Open `index.html` in your web browser and start editing `sketch.js`.

## Running Locally

For projects with media files, use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx http-server

# Using VS Code Live Server extension
# Right-click index.html -> "Open with Live Server"
```

## Resources

- [p5.js 2.0](https://beta.p5js.org/)
- [p5.js Reference](https://p5js.org/reference/)
- # Aditya-L1 Mission Simulation using p5.js

## Project Overview
This project is an interactive animation and visualization of India's Aditya-L1 Mission developed using **p5.js**. The simulation demonstrates the complete mission journey of the Aditya-L1 spacecraft, from **rocket launch to satellite deployment**, **orbital transfer**, **L1 halo orbit insertion**, and **scientific payload visualization**.

The project provides an educational and visually engaging representation of how Aditya-L1 travels to the **Lagrange Point (L1)** to study the Sun.

---

## Objectives
- Simulate the launch sequence of Aditya-L1.
- Visualize rocket stage separation.
- Show satellite deployment from the launch vehicle.
- Demonstrate Earth orbit raising maneuvers.
- Simulate travel toward the L1 Lagrange Point.
- Visualize Halo Orbit around L1.
- Display and explain Aditya-L1 scientific payloads.

---

## Technologies Used
- JavaScript
- p5.js
- HTML5 Canvas
- Object-based Data Structures

---

## Mission Flow / Animation Stages

The project is divided into multiple animation frames.

### Frame One – Rocket Launch
- Rocket starts from the launch pad.
- Launch tower and ground are displayed.
- Clicking the screen launches the rocket.
- Flame animation appears during launch.

**Features**
- Vertical rocket movement
- Animated flame effect
- Launch pad visualization

---

### Frame Two – Rocket Ascending
- Rocket moves diagonally upward.
- Rotation effect is applied.
- Transition from atmosphere to space.

**Features**
- Rocket translation and rotation
- Smooth movement animation

---

### Frame Three – Rocket Dismantling / Satellite Deployment
This stage demonstrates rocket stage separation.

#### Stages of Separation
1. Boosters separate  
2. PS1 separates  
3. PS2 separates  
4. PS3 separates  
5. Payload fairing deployment  
6. Satellite released  

After dismantling, the satellite emerges from the rocket.

**Features**
- Realistic falling stages
- Separation physics using velocity
- Satellite deployment animation

---

### Frame Four – Earth Orbit Raising & Journey to L1
The satellite performs Earth orbit raising maneuvers.

Orbit sequence:
- Low Earth Orbit
- Intermediate Orbit 1
- Intermediate Orbit 2
- Final Orbit
- Escape trajectory toward L1

After escaping Earth's gravity, the spacecraft travels toward the L1 Point.

**Features**
- Elliptical orbit animation
- Smooth orbital transition
- Velocity-based movement
- Halo orbit insertion

---

### Frame Five – Lagrange Point Visualization
This frame visualizes:

- Sun
- Earth
- Moon orbit
- Lagrange Points (L1, L2, L3, L4, L5)

The satellite enters a Halo Orbit around L1.

#### Lagrange Points

| Point | Description |
|--------|-------------|
| L1 | Between Earth and Sun |
| L2 | Beyond Earth |
| L3 | Opposite side of Sun |
| L4 | Stable triangular point |
| L5 | Stable triangular point |

**Features**
- Halo orbit animation
- Lagrange point labels
- Earth-Moon system
- Orbital geometry

---

### Frame Six – Scientific Payloads
The final frame explains the 7 scientific instruments onboard Aditya-L1.

Users can click buttons to learn about each payload.

---

## Scientific Payloads

### 1. VELC
**Visible Emission Line Coronagraph**

- Type: Remote Sensing  
- Studies: Solar Corona  
- Purpose: Observes coronal mass ejections (CMEs)

---

### 2. SUIT
**Solar Ultraviolet Imaging Telescope**

- Type: Remote Sensing  
- Studies: Photosphere & Chromosphere  
- Purpose: Captures ultraviolet images of the Sun

---

### 3. SoLEXS
**Solar Low Energy X-ray Spectrometer**

- Type: Remote Sensing  
- Studies: Soft X-rays from Solar Corona  
- Purpose: Studies solar flare heating

---

### 4. HEL1OS
**High Energy L1 Orbiting X-ray Spectrometer**

- Type: Remote Sensing  
- Studies: Hard X-rays  
- Purpose: Examines energetic solar flares

---

### 5. ASPEX
**Aditya Solar Wind Particle Experiment**

- Type: In-situ Instrument  
- Studies: Solar Wind Particles  
- Purpose: Measures proton and ion variations

---

### 6. PAPA
**Plasma Analyser Package for Aditya**

- Type: In-situ Instrument  
- Studies: Solar Plasma  
- Purpose: Measures plasma properties

---

### 7. MAG
**Advanced Tri-axial High Resolution Magnetometers**

- Type: In-situ Instrument  
- Studies: Interplanetary Magnetic Field  
- Purpose: Measures magnetic field strength and direction

---

## User Interaction

### Mouse Controls

| Action | Result |
|--------|--------|
| Click Screen | Launch rocket |
| Multiple Clicks | Trigger dismantling stages |
| Click Payload Buttons | Show instrument details |

---

## Project Structure

```plaintext
Project Folder
│── index.html
│── sketch.js
│── assets/
│     └── Frame-3.png
│── README.md
```

---

## Important Variables

| Variable | Purpose |
|-----------|---------|
| `frame_one` | Launch scene |
| `frame_two` | Rocket ascent |
| `frame_three` | Dismantling |
| `frame_four` | Orbit transfer |
| `frame_five` | Lagrange visualization |
| `frame_six` | Payload explanation |
| `dismantleStep` | Controls rocket separation |
| `orbitLevel` | Earth orbit transitions |
| `haloAngle` | Halo orbit animation |
| `activePayload` | Selected payload |

---

## Special Features
- Rocket Launch Animation  
- Stage Separation Physics  
- Satellite Deployment  
- Earth Orbit Raising  
- L1 Halo Orbit Simulation  
- Lagrange Point Visualization  
- Interactive Payload Information  
- Dynamic Stars Background  
- Scanner Beam Effects  
- Educational Solar Science Visualization

---

## Future Improvements
- Add sound effects for rocket launch and separation
- Add realistic orbital physics
- Add mission timeline narration
- Improve satellite graphics
- Add zoom-in transitions
- Add pause/play controls

---

## Educational Importance
This project helps students understand:

- Space mission visualization
- Satellite deployment
- Orbital mechanics
- Lagrange points
- Solar observation missions
- Interactive scientific simulations

It is especially useful for learning about ISRO's Aditya-L1 mission in a visually engaging way.

---

## Author
Stuti patel , Raj kumar mali 
