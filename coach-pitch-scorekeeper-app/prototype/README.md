# Diamond Dugout Dash: Softball Scorekeeping Prototype

A lightweight mobile-first scorekeeping app built for Coach Pitch softball, where traditional apps like GameChanger are too complex. Built with Loveable to experiment with AI prototyping tools and rapidly test a simplified interface.

**Live site:** [diamond-dugout-dash.loveable.app](https://diamond-dugout-dash.loveable.app)

---

## Overview

Coach Pitch softball has specific needs: limited pitch counts, simplified scoring rules, and fast-paced innings. Existing tools are often built for advanced leagues and don’t map well to real gameplay. I built this prototype to:

- Learn how to rapidly prototype with Loveable
- Solve a real usability gap for youth coaches
- Test how AI-generated tools handle real-world nuance

---

## Key Features

- Track runs, outs, and pitches
- Enforce 5-run limit in innings 1–5, no cap in 6th
- Set batting order (required for rule enforcement)
- Record basic game state with minimal taps

---

## Screenshots

### Team Set-Up
![Team Set-Up](https://github.com/user-attachments/assets/53f2910e-3729-4601-b530-321628df2868)


### Game Overview
![Game Overview](https://github.com/user-attachments/assets/77f4651d-8a11-463e-aa26-2420b28a1b75)


### Pitch and Run Counts
![Pitch and Run Counts](https://github.com/user-attachments/assets/29ecc85c-3f1b-4a96-8af7-13a9880256bb)


---

## Real-World Use & Iteration

I used this MVP app to score two live Coach Pitch softball games. It held up well in fast-paced play, but several friction points emerged that shaped the next set of feature requests.

This test surfaced areas where human error is likely—and where the interface needs to support more flexibility or correction. It also highlighted where the initial design over-simplified certain workflows, particularly around base runner movement and late-game scoring adjustments.

### Key Learnings

- **Setup adjustments are necessary mid-game**  
  Home and Away teams are often decided by coin flip *after* lineup entry, so toggling team roles post-setup is essential.

- **Score correction is a common need**  
  Runners are sometimes sent back by the umpire after a run is logged. The current app does not support subtracting or undoing a run.

- **Runner advancement needs more control**  
  The current click-based system sometimes selects the wrong player or fails to reflect multi-base hits. A more flexible system—such as drag-and-drop or directional arrows—is needed to match real gameplay more closely.

This field test validated the overall structure but also revealed clear areas for refinement before broader use. It’s a strong example of how lightweight prototyping and in-context testing accelerate product iteration—especially in fast-moving, error-sensitive environments like live sports scoring.

### Screenshots

**Team Setup View**  
![Team Setup 1.2](https://github.com/user-attachments/assets/fce5e582-bc3d-4174-8255-aa6b787a2667)


**Live Game View**  
![Game View 1.2](https://github.com/user-attachments/assets/b2e56f12-a207-4b05-8988-3cac5542cd05)


**Pitch & Run Count Interface**  
![Pitch Count 1.2](https://github.com/user-attachments/assets/13018818-4b5e-4c8c-83d8-221cb948070b)




---

## Tech Stack

- Built with: [Loveable](https://www.loveable.so)
- Style: Auto-generated HTML/CSS layout with minimal manual code
- Hosting: Loveable’s built-in deploy system
- Version: `v0.2 – Post-beta iteration notes added (2025-07-06)`

---

[← Back to Main Portfolio](https://github.com/lillianmbrown/ai-portfolio)
