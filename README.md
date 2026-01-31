![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Pose-green)
![Web](https://img.shields.io/badge/Web-Real--time-blue)
![License](https://img.shields.io/badge/License-MIT-yellow)
![Python](https://img.shields.io/badge/Python-3.x-blue)

# Front Squat Biomechanical Analysis
### Real-time posture analysis using computer vision

🚀 **Web app live:**  
https://lucalullo.github.io/front-squat-biomechanical-analysis/

Applicazione web per l’analisi biomeccanica del **front squat** tramite **visione artificiale in tempo reale**, basata su MediaPipe Pose.

L’app utilizza la fotocamera del dispositivo per rilevare i landmark corporei e fornisce **feedback automatico sulla risalita**, identificando errori comuni come il *hip shoot up* (bacino che sale prima del busto).

---

## 🎯 Obiettivi
- Analizzare il movimento del front squat in tempo reale
- Confrontare la velocità di risalita di bacino e spalle
- Fornire feedback vocale immediato
- Dimostrare un approccio biomeccanico semplice e interpretabile

---

## 🧠 Logica di analisi
- Rilevamento landmark con **MediaPipe Pose**
- Tracciamento asse verticale di:
  - anca
  - spalla
- Segmentazione automatica delle fasi:
  - discesa
  - bottom
  - risalita
- Valutazione del rapporto di velocità bacino/spalle

---

## 🛠️ Tecnologie utilizzate
- JavaScript (ES6)
- MediaPipe Pose
- HTML5 / CSS3
- Web APIs (Camera, Canvas, Speech Synthesis)
- Python (feature extraction & analysis prototyping)

## Autore
Luca Lullo
