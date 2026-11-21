<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:0369a1&height=180&section=header&text=Complexity%20Curve%20Lab&fontSize=38&fontColor=ffffff" width="100%" alt="Complexity Curve Lab banner"></p>
<p align="center"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=19&pause=1000&color=38BDF8&center=true&vCenter=true&width=620&lines=Compare+algorithmic+growth;Explore+Big-O+curves+on+a+logarithmic+scale" alt="Animated tagline"></p>
<p align="center"><img src="assets/mark.svg" width="100" alt="Complexity curve icon"></p>
<p align="center"><img src="https://img.shields.io/github/license/CyberLoop-dev/complexity-curve-lab?style=flat-square" alt="License"><img src="https://img.shields.io/github/languages/top/CyberLoop-dev/complexity-curve-lab?style=flat-square" alt="Language"><img src="https://img.shields.io/github/stars/CyberLoop-dev/complexity-curve-lab?style=flat-square" alt="Stars"><img src="https://img.shields.io/github/last-commit/CyberLoop-dev/complexity-curve-lab?style=flat-square" alt="Last commit"></p>

## 🧭 Overview
Complexity Curve Lab is a compact educational visualizer for comparing common Big-O growth functions. Move the input size and inspect both the curves and their raw illustrative values.

## ✨ Features
- 📈 Plot O(1), O(log n), O(n), O(n log n), and O(n²).
- 🔎 Use a logarithmic vertical axis so large growth rates remain visible.
- 🎚️ Change the input size with a slider or number field.
- 🧮 Read illustrative operation counts at the selected input.
- 📚 Learn the shape of growth without running benchmark code.

## 🎬 Demo
No hosted demo is published. Start the local server and adjust the input-size control.

## 🚀 Quick Start
Requires Node.js 18 or newer.
```bash
npm start
```
Open [http://localhost:4179](http://localhost:4179).

## 🧰 Tech Stack
- Node.js built-in HTTP server
- SVG, HTML, CSS, and browser JavaScript
- No runtime dependencies

## 🗂️ Folder Structure
```text
complexity-curve-lab/
├── assets/mark.svg
├── public/{app.js,index.html,style.css}
├── .gitignore
├── LICENSE
├── package.json
├── README.md
└── server.js
```

## 🗺️ Roadmap
- [ ] Add common best/average/worst-case examples.
- [ ] Add custom user-defined growth functions.
- [ ] Add a printable comparison summary.

## 🤝 Contributing
Contributions are welcome. Label theoretical curves clearly and avoid presenting them as measured runtime benchmarks.

## 📄 License
Released under the [MIT License](LICENSE).

<p align="center"><img src="https://capsule-render.vercel.app/api?type=waving&color=0:0369a1,100:111827&height=100&section=footer" width="100%" alt="Footer wave"></p>