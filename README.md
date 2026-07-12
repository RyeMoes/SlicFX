<div align="center">

  <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/logo.png" width="400">
  <h1><a href="https://slicfx.com">SlicFX.com</a></h1>
  <p><b>A simplified all in one composition and visual effects suite for OBS Studio.</b></p>

</div>

---

# Why SlicFX?

I got tired of complex nested scenes, mask files, and installing 10 different plugins just to make my stream look good.  I was spending more time tinkering with settings offline than I was streaming. So I built a unified, zero-friction composition suite.

SlicFX is a free plugin designed to bring easy-to-use premium aesthetics to your stream. No more fighting with the OBS engine, no more nested scenes to have a simple frosted glass look, no more making 4 chained filters to animate something around the screen.

SlicFX has all the effects you need bundled in one plugin. Drop a source or filter into your stream, and it just works.

---

<div align="center">
  <table style="width: auto; border-collapse: collapse;">
    <tr>
      <td style="width: 350px; padding: 5px;">
        <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/preview-1.png">
      </td>
      <td style="width: 350px; padding: 5px;">
        <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/preview-2.png">
      </td>
    </tr>
  </table>
</div>

# SlicFX Sources & Filters

<table>

<tr bgcolor="#0d1117">
  <td>
    <h3>Slic Frosted Glass</h3>
    <h4>Source &amp; Filter</h4>
    The easiest way to get that blurred frosted glass background in OBS. It automatically applies a blur and texture to whatever is physically behind it. No more nested scene nightmares required. Use it as a free-standing source for glass panels or as a filter when the glass should follow an existing source. (Note: Slic Frosted Glass uses a Dual-Filtering / Kawase Blur method and can be reverse engineered. Not recommended for hiding sensitive data)
    <br>
 <center></center><img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/frosted-glass.png" width="300">
  </td>
</tr>
</table>
<table>
<tr bgcolor="#161b22">
  <td width="40%" valign="middle">
    <h3>Slic Adjustment Layer</h3>
    <h4>Source</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/adjustment-layer.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="0" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#161b22">
  <td colspan="2">
    Drop this invisible, pass-through layer above your other sources, right-click it, and add any filter to it. This will apply the filter to anything that is behind this adjustment layer in real time, like in modern video editing software.
  </td>
</tr>
  </table>
<table>
<tr bgcolor="#0d1117">
  <td width="40%" valign="middle">
    <h3>Slic Source Copy</h3>
    <h4>Source</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/source-copy.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#0d1117">
  <td colspan="2">
    A lightweight duplicate of any source. You can crop, filter, and transform this new instance independently without changing your original source, all while passing data directly through the GPU cache with virtually zero overhead.
  </td>
</tr>
  
</table>
<table>
  
<tr bgcolor="#161b22">
  <td width="40%" valign="middle">
    <h3>Slic 3D Warp</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/3d-warp.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#161b22">
  <td colspan="2">
    Turn your flat 2D sources into 3D space. Easily adjust the pitch, yaw, and roll sliders to tilt your gameplay captures, webcams, or any other source at cinematic angled perspectives while automatic bounds compensation helps keep transformed edges from being clipped.
  </td>
</tr>

</table>
<table>

<tr bgcolor="#0d1117">
  <td width="40%" valign="middle">
    <h3>Slic Animation</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/logo.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#0d1117">
  <td colspan="2">
    Applied directly to the source you want to animate/move (not the scene the source is in), add up to 10 steps in a single filter. This virtually eliminates the confusing, complex, and tedius filter chains.
  </td>
</tr>

</table>
<table>

<tr bgcolor="#161b22">
  <td width="40%" valign="middle"align="center">
    <h3>Slic Background Removal</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/background-removal.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#161b22">
  <td colspan="2">
    For those without RTX cards, this filter can cleanly cut out your webcam without a green screen. It uses a highly optimized AI engine called Robust Video Matting. While NVIDIA Broadcast is still recommended if you can use it, this filter is perfect for those who cannot.
  </td>
</tr>

</table>
<br>
<table>
  
<tr bgcolor="#0d1117">
  <td width="40%" valign="middle" align="center">
    <dl>
      <dd>
        <h3>Slic Blur</h3>
        <strong>Filter</strong>
      </dd>
    </dl>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/blur.png" width="300">
  </td>
</tr>

<tr bgcolor="#0d1117">
  <td colspan="2">
    A dedicated simple blur filter. (Note: Slic Blur uses a Dual-Filtering / Kawase Blur method and can be reverse engineered. Not recommended for hiding sensitive data)
  </td>
</tr>

</table>
<br>
<table>
  
<tr bgcolor="#161b22">
  <td width="40%" valign="middle">
    <h3>Slic Crop/Pad</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/crop-pad.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#161b22">
  <td colspan="2">
    Use this filter to crop or pad the bounds of a sourceusing visual sliders while the source stays locked in place on your canvas. Tradtional Crop/Pad available as well.
  </td>
</tr>

<tr bgcolor="#0d1117">
  <td width="40%" valign="middle">
    <h3>Slic Mask</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/mask.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#0d1117">
  <td colspan="2">
    This Mask goes far beyond circles and rectangles. Build stars, gears, speech bubbles, hearts, animals, and other shapes. You can also use another source as the mask or load a static image. Rotation, scale, position,skew, mirroring, and corner controls finish the job.
  </td>
</tr>

<tr bgcolor="#161b22">
  <td width="40%" valign="middle">
    <h3>Slic Outline</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/outline.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#161b22">
  <td colspan="2">
    Outline can hug a webcam cutout, mask, graphic, or any edged source. Shape the thickness and placement, then choose solid, shadow, glow, bevel. After that, turn on an animation mode and the colors on the border will animate around the source.
  </td>
</tr>

<tr bgcolor="#0d1117">
  <td width="40%" valign="middle">
    <h3>Slic Rounded Corners</h3>
    <h4>Filter</h4>
  </td>
  <td width="60%" align="center">
    <img src="https://raw.githubusercontent.com/RyeMoes/SlicFX/refs/heads/main/images/rounded-corners.png" width="300">
  </td>
</tr>
<tr>
  <td colspan="2" height="1" bgcolor="#30363d"></td>
</tr>
<tr bgcolor="#0d1117">
  <td colspan="2">
    The absolute easiest way to get rounded coners on your webcam (or any other source) in OBS. Just drop this filter onto your source and drag the radius slider for perfect, procedural curved edges. Zero Photoshop mask files required.
  </td>
</tr>

</table>

---

## Installation

<details>

<summary><b>Click to expand Installation Steps</b></summary>

<br>

1. Download the latest `SlicFX-Windows.zip` from the Releases tab.

2. Extract the contents directly into your OBS directory. (Default location is `C:\Program Files\obs-studio`)

3. Launch OBS Studio.

4. You will find your new tools under the **Add Source** menu and the filters in your standard right-click **Filters** menu (look for the "Slic" prefix).

</details>

---

## The Roadmap

SlicFX Beta 1 is just the foundation. I am actively developing more premium visual tools, including:

### On the Table for Future Versions of SlicFX

* Slic Effect - A library of real-time filters (Heatwave, Glitch, VHS, Water, etc.) to give your stream a unique cinematic edge.
* Slic Displacement - Adding dynamic pixel-warping for custom glitch and refractive looks.
* Slic Custom Shader - A sandbox loader for power users to compile custom .hlsl code.

### SlicStream

SlicFX is designed from the ground up to be easy to use, but it will be even easier with the **SlicStream** — an upcoming API for controling SlixFX outside of OBS. While the SlicFX Plugin is and always will be free, SlicStream is designed to turn the free SlicFX Plugin into a full production studio.

* **Smart Auto-Layouts** - Playing a new game?  Choose the game name in your dash board or make an API call and SlicStream will automatically move/resize your camera for optimum placement in a location that doesn't cover any of the game's UI elements.

* **Automated Animations** - Want your camera to do a barrel roll? Forget manual filter chains. Just save your camera source in the dashboard and call the "Barrel Roll" API. SlicStream will build the filters, tweak the settings, and execute the animation in real-time.

* **The Cost** - SlixFX Plugin is and always will be free. SlicStream will also be free with a Twitch sub to my channel or included in the $4.99 Patreon tier.. SlicStream eliminates the "tinkering" phase, allowing you to focus on your stream while the bot manages your production values. SlicStream will make filters, change the settings, and execute them in realtime without the need for you to spend time tinkering with the settings of the always free SlicFX Plugin.

Stay tuned.

---

## Beta Feedback & Support

This is Beta 1, and every PC hardware setup is different.

If you encounter visual glitches, crashes, compatibility issues, or have feature requests, please open an issue in the repository. I am actively refining the C++ engine and want to make SlicFX the most stable and polished visual suite that I can.

---

## Credits & Licensing

SlicFX is open-source software developed by **RyeMoes** and licensed under the **GNU General Public License v3.0 (GPL-3.0)**. The full license text is available in the `LICENSE` file.

SlicFX makes use of the following third-party components:

* **Robust Video Matting (RVM)**: Fused background removal powered by the RVM model. [PeterL1n/RobustVideoMatting](https://github.com/PeterL1n/RobustVideoMatting) (Licensed under GPL-3.0). *Model weights are downloaded dynamically at runtime.*
* **MediaPipe Selfie Segmentation**: Person segmentation safety net model. Developed by Google and converted to ONNX by the [onnx-community](https://huggingface.co/onnx-community/mediapipe_selfie_segmentation) (Licensed under Apache-2.0).
* **ONNX Runtime (1.18.0)**: Machine learning inference engine. Developed by Microsoft (Licensed under MIT).
* **DirectML**: GPU acceleration backend for DirectX 12 hardware. Developed by Microsoft (Licensed under MIT).
* **[Aitum Vertical Canvas](https://github.com/Aitum/obs-vertical-canvas):** In the Slic Animation editor, selecting a scene that lives on a vertical (secondary) canvas asks the vertical-canvas plugin to switch its dock to that scene — via its published `aitum_vertical_switch_scene` command. This is purely a convenience and the *only* place SlicFX calls another plugin. If the vertical-canvas plugin isn't installed, it simply skips the call.

For full license agreements and third-party notices, please see the `licenses/` directory included with the plugin installation.
