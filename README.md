# Freediving Training Toolkit

A lightweight, static web application for freediving education, training structure, and basic physiological visualization.

---

## Overview

This project is a **100% static web tool** built with HTML, CSS, and JavaScript.  
It is designed for freedivers and instructors to support:

- training structure planning  
- basic physics understanding  
- performance tracking  
- simple dive logging  

It runs entirely in the browser and can be deployed on GitHub Pages.

---

## Live Demo

Once deployed via GitHub Pages:


https://peterk6e.github.io/freediving-toolkit/


---

## Features

### Physics Tools
- Depth → Pressure calculator
- Lung compression estimator
- Basic gas law reminder (PV = constant)

---

### Training Tools
- CO₂ table generator (structured apnea training)
- O₂ table generator
- Static apnea timer (STA)
- Breath-up cadence timer
- Session log (stored locally in browser)

---

### Performance Tools
- Depth ↔ time calculator
- Speed planner (descent/ascent)
- Breath-up structure generator

---

### Dive Log
- Local storage-based dive tracking
- Depth, time, notes
- Simple history viewer

---

## Safety Notice

Freediving involves serious risk including loss of consciousness and drowning.

This tool is:

- Educational only
- Not a medical device
- Not a safety system
- Not a physiological risk predictor

It does NOT include:

- Partial pressure oxygen (PPO₂) calculations  
- Hypoxia prediction models  
- Danger scoring systems  

---

## Technical Details

- Single-page application (`index.html`)
- No backend required
- No external dependencies
- Uses `localStorage` for persistence
- Fully responsive (mobile + desktop)
- Deployable on GitHub Pages

---

## Project Structure


freediving-toolkit/
│
├── index.html
├── about.html
├── README.md


---

## Deployment (GitHub Pages)

1. Push repository to GitHub
2. Go to **Settings → Pages**
3. Select:
   - Source: Deploy from branch
   - Branch: `main`
   - Folder: `/root`
4. Save
5. Access generated URL

---

## References

- AIDA International → https://www.aidainternational.org  
- SSI Freediving → https://www.divessi.com  
- Molchanovs → https://www.molchanovs.com  
- CMAS → https://www.cmas.org  
- FreedivingBase → https://freedivingbase.com  

---

## Limitations

- No backend or cloud sync
- No user accounts
- No physiological simulation engine
- No real-time safety monitoring
- No medical validation layer

---

## Future Improvements (optional roadmap)

- Structured session engine (coach-like workflows)
- Improved CO₂ / O₂ progression models
- Analytics on dive logs (progression tracking)
- UI dashboard improvements
- PWA offline mode

---

## License

MIT
