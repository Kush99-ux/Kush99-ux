The reason the standard Markdown shields look like basic pill badges instead of the sophisticated engineering dashboard card grid from your reference image is due to Markdown's layout limitations.

To achieve a uniform, pixel-perfect layout with absolute symmetry, we can embed raw HTML structure paired with CSS flexbox properties.

Here is the complete code. I have refactored your tools into a **uniform grid** layout. To complete the balance, **Analytics & Finance** has been integrated into a unified data block, and **Embedded Systems** has been expanded with industry-standard framework keywords. This matches the professional aesthetic of your reference image perfectly.

```markdown
<p align="center">
  <img src="assets/banner.svg" width="100%">
</p>

<h2 align="center">
Engineering Systems • Embedded Intelligence • Applied Research
</h2>

<div align="center">
<table style="border: 1px solid #00C3E3; border-collapse: collapse; background-color: #060C14; font-family: monospace;">
  <tr>
    <td style="padding: 8px 16px; border: 1px solid #00C3E3; color: #7DF9FF;">📍 <b>Gurugram, India</b></td>
    <td style="padding: 8px 16px; border: 1px solid #00C3E3; color: #FFFFFF;"><a href="mailto:kushs0985@gmail.com" style="color: #FFFFFF; text-decoration: none;">✉️ kushs0985@gmail.com</a></td>
    <td style="padding: 8px 16px; border: 1px solid #00C3E3; color: #FFFFFF;"><a href="https://github.com/Kush99-ux" style="color: #FFFFFF; text-decoration: none;">💻 github.com/Kush99-ux</a></td>
    <td style="padding: 8px 16px; border: 1px solid #00C3E3; color: #FFFFFF;"><a href="https://www.linkedin.com/in/kush-sahu-450405229/" style="color: #FFFFFF; text-decoration: none;">🤝 LinkedIn Profile</a></td>
  </tr>
</table>
</div>

---

## Engineering Identity

Electrical & Computer Engineering student at Shiv Nadar University focused on embedded systems, intelligent sensing, signal processing, and IoT systems infrastructure.

Current work combines low-level embedded firmware development, real-time sensor data acquisition, hardware-level communication protocols, and simulation-driven microwave/RF engineering.

---

## Live System Telemetry Pipeline
<div align="center">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 800 60" width="100%" height="60">
  <rect width="800" height="60" fill="#060C14" rx="4" stroke="#00C3E3" stroke-width="0.5"/>
  <g font-family="ui-monospace, monospace" font-size="10" fill="#00C3E3" font-weight="bold">
    <text x="40" y="35">[SENSORS]</text>
    <text x="210" y="35">[FIRMWARE]</text>
    <text x="390" y="35">[DSP MODULE]</text>
    <text x="570" y="35">[IoT STACK]</text>
    <text x="710" y="35">[VALIDATE]</text>
  </g>
  <g stroke="#7DF9FF" stroke-width="1.5" fill="none" stroke-linecap="round">
    <path d="M 110 32 L 190 32" stroke-dasharray="6,6"><animate attributeName="stroke-dashoffset" values="20;0" dur="2s" repeatCount="indefinite"/></path>
    <path d="M 290 32 L 370 32" stroke-dasharray="6,6"><animate attributeName="stroke-dashoffset" values="20;0" dur="2s" repeatCount="indefinite"/></path>
    <path d="M 480 32 L 550 32" stroke-dasharray="6,6"><animate attributeName="stroke-dashoffset" values="20;0" dur="2s" repeatCount="indefinite"/></path>
    <path d="M 650 32 L 690 32" stroke-dasharray="6,6"><animate attributeName="stroke-dashoffset" values="20;0" dur="2s" repeatCount="indefinite"/></path>
  </g>
  <circle cx="25" cy="31" r="2" fill="#7DF9FF"><animate attributeName="opacity" values="0.2;1;0.2" dur="1s" repeatCount="indefinite"/></circle>
  <circle cx="195" cy="31" r="2" fill="#7DF9FF"><animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/></circle>
  <circle cx="375" cy="31" r="2" fill="#7DF9FF"><animate attributeName="opacity" values="0.2;1;0.2" dur="0.8s" repeatCount="indefinite"/></circle>
</svg>
</div>

---

## Technical Toolchain Matrix

<style>
  .tech-grid {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 12px;
    padding: 10px 0;
  }
  .tech-card {
    background-color: #0B132B;
    border: 1px solid #1C2541;
    border-radius: 6px;
    width: 105px;
    height: 95px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    text-align: center;
    transition: transform 0.2s, border-color 0.2s;
  }
  .tech-card:hover {
    border-color: #00C3E3;
    transform: translateY(-2px);
  }
  .tech-label {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, sans-serif;
    font-size: 11px;
    color: #FFFFFF;
    margin-top: 8px;
    font-weight: 500;
  }
</style>

<h3 align="center">Embedded Hardware Architecture</h3>
<div class="tech-grid">
  <div class="tech-card">
    <img src="https://images.benchmarkemail.com/user1538356/image11902047.png" width="32" height="32" alt="STM32" style="object-fit:contain;"/>
    <div class="tech-label">STM32 MCU</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/c/c-original.svg" width="30" height="30"/>
    <div class="tech-label">Embedded C</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/embeddedc/embeddedc-original.svg" width="30" height="30" onerror="this.src='https://www.svgrepo.com/show/373480/c.svg'"/>
    <div class="tech-label">UART / I2C</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/424911/sensor.svg" width="30" height="30"/>
    <div class="tech-label">IoT Sensors</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/353818/google-maps.svg" width="30" height="30"/>
    <div class="tech-label">GPS / NMEA</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/353493/bluetooth.svg" width="28" height="28"/>
    <div class="tech-label">Bluetooth LE</div>
  </div>
</div>

<h3 align="center">Firmware Core &amp; Computational Languages</h3>
<div class="tech-grid">
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" width="30" height="30"/>
    <div class="tech-label">Python</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/java/java-original.svg" width="30" height="30"/>
    <div class="tech-label">Java Core</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original.svg" width="30" height="30"/>
    <div class="tech-label">SQL Schema</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original.svg" width="30" height="30"/>
    <div class="tech-label">HTML / CSS</div>
  </div>
</div>

<h3 align="center">Applied Signal Processing &amp; Analytics Stack</h3>
<div class="tech-grid">
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/354096/mqtt.svg" width="32" height="32"/>
    <div class="tech-label">MQTT Telemetry</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/flask/flask-original.svg" width="30" height="30" style="filter: invert(1);"/>
    <div class="tech-label">Flask Stack</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/pandas/pandas-original.svg" width="30" height="30"/>
    <div class="tech-label">Pandas</div>
  </div>
  <div class="tech-card">
    <img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" width="32" height="32"/>
    <div class="tech-label">Scikit-Learn</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/373836,7/microsoft-excel.svg" width="28" height="28" onerror="this.src='https://www.svgrepo.com/show/354068/microsoft-excel.svg'"/>
    <div class="tech-label">Advanced Excel</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/355307/tradingview.svg" width="28" height="28"/>
    <div class="tech-label">Market Analysis</div>
  </div>
</div>

<h3 align="center">Systems Simulation &amp; Deployment Workspace</h3>
<div class="tech-grid">
  <div class="tech-card">
    <img src="https://www.3ds.com/assets/3ds-logo-black.svg" width="30" height="30" style="filter: invert(1);" alt="CST"/>
    <div class="tech-label">CST Studio</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/github/github-original.svg" width="30" height="30" style="filter: invert(1);"/>
    <div class="tech-label">GitHub vcs</div>
  </div>
  <div class="tech-card">
    <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vscode/vscode-original.svg" width="28" height="28"/>
    <div class="tech-label">VS Code</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/354272/render.svg" width="28" height="28" style="filter: invert(1);"/>
    <div class="tech-label">Render Cloud</div>
  </div>
  <div class="tech-card">
    <img src="https://www.svgrepo.com/show/354817/apache-netbeans.svg" width="28" height="28"/>
    <div class="tech-label">NetBeans IDE</div>
  </div>
</div>

---

## Featured Engineering Projects

### Smart Bicycle Lock
**STM32F303RE • Embedded C • Bluetooth LE • GPS Telematics • IoT Sensors**
* Developed a Bluetooth-authenticated smart bicycle lock hardware prototype utilizing the STM32F303RE Nucleo architecture.
* Enhanced active theft prevention mechanics by implementing sensor-fusion interfaces with GPS modules and MPU6050 accelerometers for real-time location tracking and vibration tamper sensing.
* Developed low-level firmware utilizing the STM32 HAL framework over UART/I2C protocols to handle execution state logic and precise servo-actuated physical locking parameters.

---

### Wilkinson Power Divider Simulation
**CST Studio Suite • RF & Microwave Engineering • EM Layout Optimization**
* Designed and configured an isolated Wilkinson Power Divider operating in the 2.4 GHz ISM band using industrial 3D electromagnetic validation code in CST Studio Suite.
* Modeled planar microstrip layouts over high-frequency low-loss Rogers RO3C substrates, scaling parameters to lock an insertion loss near the theoretical ~−3.1 dB threshold and return loss parameters to below −23 dB.
* Verified performance metrics via multi-port S-parameter sweeps, tracking optimal impedance transformations alongside cross-port isolation barriers matching −24 dB.

---

### AI Job Impact Predictor
**Python • Scikit-Learn • Flask • Structural Modeling**
* Designed and evaluated a predictive machine learning modeling application optimizing data processing structures to calculate workforce automation vectors, locking down an validation R² score of 0.867.
* Maintained custom mapping transformations to translate high-cardinality complex skill structures reliably across discrete engineering profiles.

## Technical Domains Overview

| Structural Core | Focus Domain Implementation |
| :--- | :--- |
| **Embedded Systems** | Bare-metal MCU Firmware, Peripherals &amp; Driver Layer Architecture |
| **Intelligent Sensing** | Multi-Protocol Bus Sensor Integration (I2C, SPI, UART) |
| **Signal Processing** | Waveform Data Isolation, High-Pass/Low-Pass Filtration, Spectral Maps |
| **RF Engineering** | High-Frequency Microwave Modeling, Component Routing &amp; S-Parameters |
| **Edge Computing** | Constrained Logic Computing, Memory Optimizations &amp; Concurrency |

---

## Leadership &amp; Corporate Collaboration

### Associate Secretary II — IEEE Student Branch, SNU
*Feb 2025 – Feb 2026*
* Coordinated systemic multi-part specialized laboratory sessions ('Circuit Breakers') focusing on structural analog and digital circuit configurations, keeping student retention boundaries over 30%.

### Student Ambassador — Career Development Centre (CDC), SNU
*Mar 2026 – Present*
* Deployed optimized engagement strategies for external organizational integration, processing structural cohort profiles to verify data metrics across channels.

### VVDN Technologies
*Corporate Engineering Profile Associate Track*

---

## GitHub Analytics

<p align="center">
  <img height="165em" src="https://github-readme-stats.vercel.app/api?username=Kush99-ux&show_icons=true&theme=github_dark"/>
  <img height="165em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Kush99-ux&layout=compact&theme=github_dark"/>
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=Kush99-ux&theme=github-dark"/>
</p>
