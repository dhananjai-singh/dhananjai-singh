## Hi, I'm Dhananjai

I'm a CS student, and most of my time goes into medical tech: models and small hardware for screening problems that need more trained eyes than there are doctors.

### What I'm working on

**[Diabetic Retinopathy Detection](https://github.com/dhananjai-singh/Diabetic-Retinopathy-Detection)**
Grading diabetic retinopathy (stages 0 to 4) from retinal fundus photos. I trained a custom CNN and a ResNet-50 on the APTOS 2019 dataset. The classes are very imbalanced, so a lot of the work went into the loss function. Grad-CAM heatmaps show which part of the retina the model based its answer on. There's a Gradio demo and a Next.js dashboard on top.
PyTorch, OpenCV, Gradio, Next.js

**[Counterswing](https://github.com/dhananjai-singh/Counterswing)**
A wearable that measures how well your arms and legs stay in sync while you walk. Reduced or out-of-phase arm swing can be an early sign of some gait disorders. An insole picks up heel strikes, a wrist IMU tracks arm swing, and the two boards talk over ESP-NOW. Each stride gets a phase angle and a coordination score, and a Random Forest running on the phone classifies the walk.
ESP32, Flutter, scikit-learn, BLE

### Other things I've built

- [ClaimRight](https://github.com/dhananjai-singh/ClaimRight): checks the deductions in Indian health-insurance claims against IRDAI rules and drafts the complaint letter
- [Praman](https://github.com/dhananjai-singh/Praman): a rebuilt Madhya Pradesh certificate portal that gives instant, explained decisions on the legal deadline
- [CertChain](https://github.com/dhananjai-singh/CertChain): academic certificates on a blockchain, verifiable by QR code
- [Personal Command Center](https://github.com/dhananjai-singh/Personal-Command-Center): my own app for tasks, habits, fitness and notes
- [Edge-Fog DDoS Detection](https://github.com/dhananjai-singh/Edge-Fog-DDoS-Detection) and [Live DDoS Attack Map](https://github.com/dhananjai-singh/Live-DDoS-Attack-Map): catching DDoS traffic at the edge, and a live 3D map of attacks
- [World Cup 2026 Predictor](https://github.com/dhananjai-singh/World-Cup-2026-Predictor): XGBoost plus a thousand simulated tournaments
- [Crafty](https://github.com/dhananjai-singh/Crafty): a Minecraft mod with an AI helper in chat
- [AI Router](https://github.com/dhananjai-singh/AI-Router): a CLI that picks which AI model should handle a coding task

### Tools I use most

Python, PyTorch, scikit-learn, OpenCV, TypeScript, Next.js, Flutter, FastAPI, ESP32 and Arduino, PostgreSQL
