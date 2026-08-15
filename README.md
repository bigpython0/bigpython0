# ♟️ Chess Engine & Motion Showcase

<div align="center">

  <!-- Badges -->
  <img src="https://img.shields.io/badge/C%2B%2B-20-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++20" />
  <img src="https://img.shields.io/badge/CMake-064F8C?style=for-the-badge&logo=cmake&logoColor=white" alt="CMake" />
  <img src="https://img.shields.io/badge/After%20Effects-9999FF?style=for-the-badge&logo=adobeaftereffects&logoColor=white" alt="After Effects" />
  <img src="https://img.shields.io/badge/CI%2FCD-Passing-brightgreen?style=for-the-badge&logo=githubactions&logoColor=white" alt="CI/CD" />
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License" />

  <p href="https://github.com/bigpython0">
    <strong>Eine hochperformante C++ Schach-Engine mit visualisierter Algorithmen-Logik.</strong>
  </p>

</div>

---

## 🎬 Visual Showcase (Motion & UI)

<!-- HAUPT-SHOWCASE: Großes GIF / Video-Demo -->
<div align="center">
  <img src="docs/assets/main-demo.gif" alt="Schachspiel Gameplay & Visuals" width="100%" />
  <p><em>Haupt-Demo: Gameplay-Flow, Smooth Cursor Tracking und Bewegungsvisualisierung.</em></p>
</div>

<br />

<!-- GRID SHOWCASE: Zweispaltiges Layout für Detail-GIFs -->
<table border="0" width="100%">
  <tr>
    <td width="50%" align="center">
      <img src="docs/assets/feature-minimax.gif" alt="Minimax Visualisierung" width="100%" />
      <br />
      <b>Visualisierung: Alpha-Beta Pruning</b>
      <p><small>Animierter Decision-Tree für Suchtiefe & Rechenschritte.</small></p>
    </td>
    <td width="50%" align="center">
      <img src="docs/assets/feature-ui.gif" alt="UI Interaktionen" width="100%" />
      <br />
      <b>UI & Micro-Interactions</b>
      <p><small>Mit AE aufbereitete Highlights für Zugoptionen & Bedrohungszonen.</small></p>
    </td>
  </tr>
</table>

---

## ✨ Features & Highlights

- **⚡ High-Performance Core:** Effiziente Spielfelddarstellung und Zugberechnung (Bitboards).
- **🎨 Motion-Enhanced Visuals:** Visualisierte Algorithmen und flüssige Interaktions-Overlays.
- **🛡️ Defensive Programming:** Abgesicherte Logik gegen seltene Ausnahmezustände (Patt, Rochade-Regeln).
- **🧪 Automatisierte Tests:** Vollständige Testabdeckung wichtiger Spielregeln via Unit-Tests.

---

## 🛠️ Tech Stack & Tools

- **Sprache & Build-System:** `C++20`, `CMake`
- **Testing:** `GoogleTest` / `Catch2`
- **Motion & Asset Pipeline:** `Adobe After Effects` (Motion Design, Highlighting, GIF/WebM Export)
- **CI/CD:** `GitHub Actions`

---

## 🚀 Quick Start

### Voraussetzungen
- C++20 kompatibler Compiler (GCC/Clang/MSVC)
- CMake ≥ 3.16

### Installation & Ausführen
```bash
# 1. Repository klonen
git clone [https://github.com/bigpython0/Chess.git](https://github.com/bigpython0/Chess.git)
cd Chess

# 2. Build-Ordner erstellen & kompilieren
mkdir build && cd build
cmake ..
make -j4

# 3. Spiel starten
./ChessApp
