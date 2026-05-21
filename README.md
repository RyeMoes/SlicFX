<div align="center">
  <h1>🔪 SlicFX (Beta 1)</h1>
  <p><b>The zero-friction composition and visual effects suite for OBS Studio.</b></p>
  <p><i>Developed by RyeMoes</i></p>
  <br>
  <br>
</div>

---

## 🚀 The Ultimate OBS Composition Suite

[cite_start]I got sick of complex nested scenes, mask files, and installing 10 different plugins just to make my stream look good[cite: 1940, 1941]. [cite_start]So, I built a unified, zero-friction composition suite[cite: 1941]. 

[cite_start]This is a free, highly optimized OBS plugin designed to bring Apple-style, one-click premium aesthetics to your stream[cite: 1941]. [cite_start]No more fighting with the OBS engine, no more rubber-banding group boxes, and no more Photoshop masking files[cite: 1942]. [cite_start]Drop a SlicFX source into your scene, and it just works[cite: 1943].

---

## 🟢 What's Included in Beta 1

### Custom Sources
* [cite_start]**Slic Frosted Glass:** A true, zero-setup frosted glass adjustment layer[cite: 1944]. [cite_start]It automatically reads the Z-order and blurs exactly what is physically behind it[cite: 1945]. [cite_start]Powered by a custom 8-pass Kawase blur pipeline with a 480p downsample, it gives you massive, buttery-smooth blur without melting your GPU[cite: 1946]. [cite_start]Includes an exponential crossfade at the lowest levels for pixel-perfect sharpness, plus built-in noise generation and color tinting[cite: 1947].
* [cite_start]**Slic Source Instance:** The zero-performance clone[cite: 1951]. [cite_start]Creates a lightweight, frame-by-frame duplicate of any master source that passes directly through the GPU cache with virtually zero overhead[cite: 1952].
* [cite_start]**Slic Adjustment Layer:** A pure, full-resolution pass-through layer[cite: 1953]. [cite_start]Drop this above your gameplay and webcam, right-click it, and add standard OBS Color Correction or LUTs to grade your entire scene at once[cite: 1954].

### Custom Filters
* [cite_start]**Slic Background Removal:** Cleanly cut out your webcam without a green screen[cite: 1948]. [cite_start]Powered by a highly optimized, real-time AI inference engine (Robust Video Matting)[cite: 1949]. [cite_start]It is hardware-agnostic, meaning you don't need an RTX card to get a perfect cutout[cite: 1950].
* [cite_start]**Slic Rounded Corners:** The #1 most requested UI fix[cite: 1955]. [cite_start]Just drop this filter on your webcam or game capture and drag a slider for perfect, procedural rounded corners[cite: 1956].
* [cite_start]**Slic Blur:** A dedicated, highly optimized Gaussian blur filter for individual items[cite: 1957]. [cite_start]Perfect for quickly hiding Discord chats, IP addresses, or sensitive UI elements[cite: 1958].

---

## ⚡ Under the Hood

[cite_start]SlicFX isn't just a collection of visual tricks; it is a custom rendering pipeline built directly into the OBS C++ API[cite: 1959, 1960].

* [cite_start]**Deep Recursive Traversal:** Slic Frosted Glass dynamically maps your scene graph, meaning it perfectly respects folders, crops, and nested transforms[cite: 1961].
* [cite_start]**Screen-Space UVs:** The glass acts as a true 1:1 "window"[cite: 1962]. [cite_start]You can drag it, crop it, and resize it anywhere on your canvas, and the background will dynamically shift through it flawlessly[cite: 1963].

---

## 🛠️ Installation

<details>
<summary><b>Click to expand Installation Steps</b></summary>
<br>

1. [cite_start]Download the latest `SlicFX-Beta1-Windows.zip` from the Releases tab[cite: 1964].
2. [cite_start]Extract the contents directly into your `C:\Program Files\obs-studio` directory[cite: 1965].
3. Launch OBS.
4. [cite_start]You will find your new tools under the **Add Source -> SlicFX** menu, and the filters in your standard right-click **Filters** menu (look for the "Slic" prefix!)[cite: 1966].

</details>

---

## 🔮 The Roadmap & SlicBot

[cite_start]SlicFX Beta 1 is just the foundation[cite: 1967]. [cite_start]I am actively developing more premium visual tools (Slic Drop Shadow, Slic Outer Stroke, Slic Animated Gradients)[cite: 1968]. 

But the real magic is coming soon. [cite_start]SlicFX is designed from the ground up to be the visual anchor for **SlicBot**—an upcoming, web-based broadcast dashboard[cite: 1969]. [cite_start]SlicBot will allow you to completely automate your SlicFX sources, trigger smooth cinematic slide-in animations, and manage your entire OBS layout remotely without ever opening the OBS window[cite: 1970]. Stay tuned.

---

## 🐛 Beta Feedback & Support

This is Beta 1! [cite_start]Every PC hardware setup is different[cite: 1971]. [cite_start]If you encounter weird visual glitches, crashes, or feature requests, please drop them in the Issues tab[cite: 1972]. [cite_start]I am actively refining the C++ engine and want to make this the most stable suite in the streaming space[cite: 1973].

---

## 📜 Credits & Licensing

[cite_start]SlicFX is an open-source project licensed under the **GPL-3.0 License**[cite: 2488, 2489].

* [cite_start]**Robust Video Matting (RVM):** Slic Background Removal is powered by the Robust Video Matting (RVM) model[cite: 2494]. [cite_start][PeterL1n/RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting) (Licensed under GPL-3.0)[cite: 2495].
