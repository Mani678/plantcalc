# PlantCalc — Industrial Process Instrumentation Calculator

A professional-grade PWA (Progressive Web App) built for field technicians 
and process engineers working with instrumentation and process control systems.

## Features

### Four Process Variable Modules
- **Pressure** — Hydrostatic calculation, 9-unit converter, transmitter LRV/URV/4-20mA scaling
- **Level** — Dry leg DP, Wet leg DP (suppressed zero), live level from mA signal
- **Flow** — Orifice plate / DP flow, volumetric to mass flow, Reynolds number, flow unit converter
- **Temperature** — Unit converter, PT100/PT1000 RTD resistance, thermocouple mV reference, transmitter scaling

## PWA — Works Offline
Install directly from the browser on any device.
No app store. No subscription. No internet required after first load.

## Tech Stack
- Pure HTML / CSS / JavaScript
- Progressive Web App (Service Worker + Web Manifest)
- Zero dependencies — runs in any browser

## Deployment
Hosted on Vercel. Auto-deploys on every push to main branch.

## Roadmap
- [ ] PDF report export
- [ ] More flow calculators (control valve Cv, pipe sizing)
- [ ] FastAPI Python backend
- [ ] Calculation history / saved projects
- [ ] Multi-user SaaS

## Built For
Oil & gas, chemical plants, power generation, water treatment — 
any facility where instrumentation technicians need fast, reliable field calculations.
