<div style="background-color:#0d1117; border:2px solid #ff004f; padding:16px; border-radius:12px; margin-bottom:24px;">

<p align="center" style="color:#ff004f; font-weight:700; font-size:16px;">
⚠️ EDUCATIONAL & RESEARCH USE ONLY ⚠️
</p>

<p style="color:#ff7a90; text-align:center;">
This project is developed strictly for <b>educational, academic, and authorized research purposes</b>.
Any use of this code, hardware design, or concepts outside a controlled and explicitly permitted
environment is solely the responsibility of the user.
</p>

<p style="color:#ff7a90; text-align:center;">
The author assumes <b>no liability</b> for misuse, damage, or unauthorized deployment of this project.
By accessing or using this repository, you acknowledge full responsibility for compliance with
applicable laws, policies, and ethical standards.
</p>

</div>
<div style="background-color:#0d1117; color:#c9d1d9; padding:24px; border-radius:12px">

<h1 align="center" style="color:#58a6ff;">Plug’n’Pwn</h1>

<p align="center" style="color:#8b949e;">
ESP32-Based Programmable USB HID Platform<br>
Academic & Laboratory Research Project
</p>

<p align="center">
<img src="ESP32.jpg" width="420">
</p>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Overview</h2>

<p>
Plug’n’Pwn is an ESP32-based programmable USB Human Interface Device (HID) platform developed to study and demonstrate
implicit trust relationships in modern operating systems. The device enumerates as a standard USB keyboard and executes
predefined keystrokes upon insertion, enabling controlled command execution in authorized laboratory environments.
</p>

<p style="color:#8b949e;">
This repository contains implementation artifacts only. A complete technical report is provided separately.
</p>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Scope</h2>

<ul>
<li>Academic research</li>
<li>Laboratory experimentation</li>
<li>Physical access security analysis</li>
<li>USB trust model evaluation</li>
</ul>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">High-Level Operation</h2>

<pre style="background-color:#161b22; padding:16px; border-radius:8px; color:#c9d1d9;">
[1] Device inserted into system
[2] OS enumerates device as USB HID (keyboard)
[3] Controlled initialization delay
[4] Predefined keystrokes injected
[5] Payload triggered from removable storage
[6] Execution completes silently
</pre>

<p style="color:#8b949e;">
Detailed timing logic and execution flow are documented in the technical report.
</p>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Hardware Platform</h2>

<ul>
<li>ESP32 microcontroller (USB-capable)</li>
<li>MicroSD card and adapter</li>
<li>USB interface</li>
<li>Test environment: Windows 10 / Windows 11</li>
</ul>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Repository Structure</h2>

<pre style="background-color:#161b22; padding:16px; border-radius:8px; color:#c9d1d9;">
Plug-n-Pwn/
├── code/
│   └── code.py
├── docs/
│   └── PlugnPwn_Report.pdf
├── media/
│   └── images/
│       └── esp32.jpg
├── demo/
│   └── DEMO_LINKS.md
└── README.md
</pre>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Performance Summary</h2>

<pre style="background-color:#161b22; padding:16px; border-radius:8px; color:#c9d1d9;">
Execution latency : ~2 seconds
Tested reliability: >95% (Windows 10 / 11)
Execution context : User-level
Persistence       : None (by design)
</pre>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Demonstration</h2>

<p>
Recorded demonstrations are provided via external links.
See: <code>demo/DEMO_LINKS.md</code>
</p>

<hr style="border:1px solid #30363d">

<h2 style="color:#58a6ff;">Ethical Use</h2>

<p style="color:#8b949e;">
This project is intended strictly for educational and research purposes.
All testing was conducted in controlled environments with explicit authorization.
Unauthorized use is prohibited.
</p>

<hr style="border:1px solid #30363d">

<p align="center" style="color:#6e7681;">
Plug’n’Pwn — Academic USB HID Research Project
</p>

</div>
