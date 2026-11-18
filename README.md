<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2ed6a0&height=200&section=header&text=Mansoor%20Ahmed&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=UAV%20Autonomy%20%E2%80%A2%20Swarm%20Robotics%20%E2%80%A2%20Founder%20%40%20Maverick%20Technologies&descAlignY=58&descSize=18" alt="Mansoor Ahmed" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=2ED6A0&center=true&vCenter=true&width=700&lines=UAV+Autonomy+%26+Multi-Robot+Swarm+Engineer;Founder+%40+Maverick+Technologies+%26+Aero+Mavericks;ROS+2+%E2%80%A2+PX4%2FArduPilot+%E2%80%A2+Computer+Vision;Teknofest+Finalist+%E2%80%A2+Aerothon'25+3rd+Overall;Electrical+Engineering+%40+NUST+'27)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mansoorahmedrind-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mansoorahmedrind/)
[![Portfolio](https://img.shields.io/badge/Portfolio-visit-2ed6a0?style=flat-square&logo=vercel&logoColor=black)](https://personal-portfolio-swart-sigma-44.vercel.app/)
[![Maverick Technologies](https://img.shields.io/badge/Maverick_Technologies-website-0f2027?style=flat-square&logo=astro&logoColor=white)](https://maverick-technologies.vercel.app)
[![Email](https://img.shields.io/badge/Email-ahmedmansoorrind1210-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ahmedmansoorrind1210@gmail.com)
[![Fiverr](https://img.shields.io/badge/Fiverr-hire%20me-1DBF73?style=flat-square&logo=fiverr&logoColor=white)](https://www.fiverr.com/s/5r2dqg4)
![Profile Views](https://komarev.com/ghpvc/?username=UnknownEng&label=views&color=2ed6a0&style=flat-square)

</div>

---

## About me

I build **autonomous drones and multi-robot swarms**, from Gazebo simulation to real flight, and I ship products people actually use.

I'm an Electrical Engineering undergraduate at **NUST, Islamabad (Class of 2027)**, a **Rector's Gold Medalist**, founder of **Aero Mavericks** (a student UAV team building autonomous aircraft for disaster relief, medical delivery and precision missions) and founder of **[Maverick Technologies](https://maverick-technologies.vercel.app)**, where I build apps for Pakistan and beyond.

```yaml
focus:      [UAV autonomy, swarm robotics, precision landing, GPS-denied navigation]
stack:      [ROS 2, Nav2, MAVROS, PyMAVLink, PX4, ArduPilot, Gazebo]
vision:     [OpenCV, YOLOv8, depth cameras, visual-inertial SLAM]
hardware:   [Pixhawk, Raspberry Pi, ESP32, Arduino, radio telemetry]
building:   [Maverick Technologies: consumer apps, health, legal & edtech tools]
open_to:    [research collaborations, robotics/UAV internships, freelance autonomy work]
```

---

## 🚁 Drones & UAV autonomy

<table>
<tr>
<td width="50%" valign="top">

### 🛩️ [Fail-Safe Indoor UAV Navigation](https://github.com/UnknownEng/Layered-ROS-2-Nav2-Architecture-for-Fail-Safe-Indoor-UAV-Navigation)
GPS-denied indoor flight with **ROS 2 Jazzy + Nav2 + SLAM Toolbox + ArduPilot DDS**. A layered safety stack (collision monitor, watchdog bridge, guarded takeoff) brakes deterministically for dynamic obstacles before commands reach the flight controller.

`ROS 2` `Nav2` `SLAM` `ArduPilot`

</td>
<td width="50%" valign="top">

### 🐝 [Resilient Swarm Formation](https://github.com/UnknownEng/resilient-swarm-formation)
Decentralized formation control for 5 robots: **no leader, no GPS, no central coordinator**. A **CBF-QP safety filter** checks every command. **100% convergence, 0 collisions** across 550 runs under packet loss, delay and stalled robots.

`ROS 2 Jazzy` `Gazebo Harmonic` `EKF` `CBF`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🧠 [RL-Based UAV Navigation](https://github.com/UnknownEng/Reinforcement-Learning-Based-UAV-Navigation)
**PPO** quadrotor navigation through procedurally generated forests with 3-D LiDAR, a rule shield and a barrier-function safety filter, validated in **PX4/Gazebo SITL**.

`PPO` `PX4` `LiDAR` `Safety filters`

</td>
<td width="50%" valign="top">

### 💊 [Medical Response Drone](https://github.com/UnknownEng/medical-response-basic)
Autonomous medical-delivery drone: **ArUco** marker search, precision landing, payload drop at a GPS target and failsafes. pymavlink + ROS/MAVROS with full SITL simulation.

`ArduPilot` `OpenCV` `MAVROS` `Precision landing`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🗺️ [Drone Mapping with WebODM](https://github.com/UnknownEng/webodm-based-mapping-algorithm-using-drone)
Survey planning from GeoTIFF, ArduPilot + MAVROS flight with geotagged capture, and **orthophoto, DSM and 3D model** generation. Verified in SITL + Gazebo.

`ArduPilot` `MAVROS` `WebODM` `Photogrammetry`

</td>
<td width="50%" valign="top">

### 🧭 [APF-Nav Obstacle Avoidance](https://github.com/UnknownEng/APF-Nav_Artificial_Potential_Field_Navigator-)
LiDAR-based 3D obstacle avoidance for a quadrotor using **Artificial Potential Fields** with vortex repulsion and local-minimum escape.

`ROS Noetic` `Gazebo 11` `LiDAR`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🖥️ [AeroMaverick GCS](https://github.com/UnknownEng/AeroMaverick-GCS)
Ground control station for **PX4 & ArduPilot** over MAVLink and MAVROS, for Windows and Android.

`MAVLink` `MAVROS` `Windows` `Android`

</td>
<td width="50%" valign="top">

### 🎮 [Drone Training Simulator](https://github.com/UnknownEng/drone-training-simulator)
Offline pilot-training simulator for Windows with a built-in ArduCopter-compatible flight controller and **real ArduPilot SITL** in lock-step.

`ArduPilot SITL` `Three.js` `Electron`

</td>
</tr>
</table>

| More drone work | |
|---|---|
| 🛠️ [Arduino F450 Quadcopter](https://github.com/UnknownEng/Arduino-Based-F450-Quadcopter-Drone) | Arduino flight controller (MPU-6050, PID, auto-level) with failsafes and a PC simulator that tests the real code |
| 🙂 [DJI Tello Face Tracking](https://github.com/UnknownEng/DJITello-Facetracking-Script) | Tello follows a face and holds a safe distance |
| 🗺️ [DJI Tello Mapping](https://github.com/UnknownEng/DJI-Tello-Mapping-System) | Mapping with a DJI Tello |
| 📷 [Tello Monitoring System](https://github.com/UnknownEng/Tello-Mnitoring-system) | Image capture and monitoring with a Tello |
| ⌨️ [Tello Keyboard Control](https://github.com/UnknownEng/KeyBoard-Control-DJI-Tello-Script) | Fly a Tello from your keyboard |

---

## 💼 Maverick Technologies: products

Apps I've built and shipped as founder of **[Maverick Technologies](https://maverick-technologies.vercel.app)**.

| Product | What it does | Get it |
|---|---|---|
| 🎙️ **[JohnD Personal Assistant](https://github.com/UnknownEng/JohnD-Personal-Assistant)** | Offline voice assistant for Windows, with Urdu support | [Download](https://github.com/UnknownEng/JohnD-Personal-Assistant/releases/latest) |
| ⚖️ **[LawerAI (قانون معاون)](https://github.com/UnknownEng/lawerai-app)** | AI legal assistant for Pakistani law | [Android app](https://github.com/UnknownEng/lawerai-app) · [Web](https://lawerai-alpha.vercel.app) |
| 📖 **[HURF (حرف)](https://github.com/UnknownEng/hurf-app)** | Urdu reading-difference screening for Class 1–5 students | [Android app](https://github.com/UnknownEng/hurf-app/releases/latest) |
| 👕 **[FitCheck](https://github.com/UnknownEng/fitcheck)** | AI closet scanner, outfit tracker, event stylist and laundry reminders | [Android app](https://github.com/UnknownEng/fitcheck) · [Web](https://fitcheck-wardrobe.vercel.app) |
| 🏪 **[Dukaan2Dream](https://github.com/UnknownEng/dukaan2dream-android)** | Loyal customers fund local brands' new outlets | [Android app](https://github.com/UnknownEng/dukaan2dream-android) · [Web](https://dukaan2dream.vercel.app) |
| 💊 **[Sasta Dawa Finder](https://github.com/UnknownEng/sasta-dawa-finder)** | Official DRAP medicine prices and cheaper brands with the same formula | [Web](https://sasta-dawa-finder.vercel.app) |

---

## 🔧 Other projects

| Project | What it does |
|---|---|
| 🦾 [4-DOF Wi-Fi Robotic Arm](https://github.com/UnknownEng/4-DOF-Wifi-Web-Control-Motion-Repeater-Robotic-ARM) | ESP32 robot arm controlled from your phone; record and replay moves, with a Wokwi simulation |
| 📡 [Designing LiDAR](https://github.com/UnknownEng/Designing-Lidar) | Real-time 2D LiDAR simulator: ray casting, noise, dropout and live range plots |
| 🚀 [Asclepius Crew Health](https://github.com/UnknownEng/asclepius-crew-health) · [live](https://asclepius-crew-health.vercel.app) | NASA Space Apps 2026: autonomous astronaut health monitoring with anomaly detection |
| 🔑 [Arduino RF/IR Capture & Replay](https://github.com/UnknownEng/Car-Key-FOB-Hacking-Device-Using-Arduino-UNO-and-RF-Module) | Educational RF/IR capture and replay demo (nRF24L01 + IRremote) with a Wokwi simulation |
| 🌐 [Personal Portfolio](https://github.com/UnknownEng/Personal-Portfolio) · [live](https://personal-portfolio-swart-sigma-44.vercel.app) | React 19 + Vite portfolio with an Express API and private CMS |

---

## Experience

| Role | Organization | When |
|---|---|---|
| **Founder** | Maverick Technologies | Present |
| **Founder & Team Captain** | Aero Mavericks | Nov 2025 – Present |
| **Freelance Robotics & Automation Consultant** | Fiverr | Nov 2025 – Present |
| **Drone Swarm Engineer** | INTELGENCY IT Solutions | Feb 2026 – Jun 2026 |
| **Research Student**: precision landing & swarm comms | CSN Lab, SEECS NUST | Jun 2025 – Jan 2026 |
| **Vice Captain & Electronics/Automation Lead** | Team Vitesse (NUST) | Feb 2024 – Sep 2025 |
| **Robotics Engineer Intern** | Aerial Robotics Lab, NUST | Jul 2024 – Sep 2024 |
| **Summer Intern**: industrial heat-tracing CAD design | Korea EHT Co., Ltd | Jul 2024 – Sep 2024 |
| **Web Developer** | One International Services | Sep 2024 – Dec 2024 |

<details>
<summary><b>What I did in each role</b></summary>

<br/>

**Aero Mavericks: Founder & Team Captain**
- Own the full UAV lifecycle: electronics design, system integration, embedded programming and flight-ready prototypes
- Captained the team at **National Aerothon'25** with an autonomous disaster-relief drone for medical sample collection. Won **3rd Overall** and the **"Swift Wing"** title
- Team Captain for the **IMechE Pakistan UAS Challenge**

**CSN Lab, SEECS: Research Student**
- Developed **precision landing** on static and moving platforms
- Implemented **drone-to-drone communication over radio telemetry**, so a swarm coordinates without a ground control station
- Designed multi-UAV coordination in Gazebo and validated it in real flight

**INTELGENCY IT Solutions: Drone Swarm Engineer**
- Engineered multi-UAV swarm capabilities and coordination for autonomous missions

**Team Vitesse: Vice Captain & Electronics/Automation Lead**
- **Teknofest International UAV Competition, Türkiye (2025):** built a UAV that lands on a moving unmanned surface vehicle (USV). **Finalist among 160+ international teams**
- Electronics and automation for the IMechE UAS Challenge 2024 and National DBF 2024 (finalist)

**Aerial Robotics Lab: Robotics Engineer Intern**
- Built UAV autonomy workflows with ROS and MAVROS on the ArduPilot stack (Mission Planner, QGC, MAVProxy)
- Built an ML-based pothole-detection UAV with onboard inference and server-side data transfer

</details>

---

## Research

- **A Layered ROS 2/Nav2 Architecture for Fail-Safe Indoor UAV Navigation with Deterministic Dynamic-Obstacle Braking** ([code](https://github.com/UnknownEng/Layered-ROS-2-Nav2-Architecture-for-Fail-Safe-Indoor-UAV-Navigation))
- **Resilient Decentralized Shape Formation of Multi-Robot Swarms Under Adversarial Real-World Faults in High-Complexity Disaster Environments** ([code](https://github.com/UnknownEng/resilient-swarm-formation))
- **A Review of Visual and Visual-Inertial SLAM Techniques for Dynamic-Environment Localization and Mapping in Autonomous UAVs**

---

## Achievements

| | |
|---|---|
| 🏅 | **Rector's Gold Medal**, NUST |
| 🇹🇷 | **Finalist**, Teknofest International UAV Competition 2025 (160+ international teams) |
| 🥉 | **3rd Overall + "Swift Wing"**, National Aerothon'25 (Team Captain) |
| ✈️ | **Finalist**, National Design, Build & Fly 2024 · **112 / 200**, International DBF 2026 |
| 🚀 | NASA Space Apps Challenge 2026 participant ([Asclepius](https://github.com/UnknownEng/asclepius-crew-health)) |
| 🪪 | Certified **UAS Remote Pilot**, Open Category A1/A3 |

---

## Tech stack

<div align="center">

**Robotics & autonomy**<br/>
![ROS 2](https://img.shields.io/badge/ROS_2-22314E?style=for-the-badge&logo=ros&logoColor=white)
![PX4](https://img.shields.io/badge/PX4-0B5A9E?style=for-the-badge&logoColor=white)
![ArduPilot](https://img.shields.io/badge/ArduPilot-1B1B1B?style=for-the-badge&logoColor=white)
![MAVLink](https://img.shields.io/badge/MAVLink-4B5563?style=for-the-badge&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-F58113?style=for-the-badge&logoColor=white)

**Languages & vision**<br/>
<img src="https://skillicons.dev/icons?i=py,cpp,c,js,ts,opencv&theme=dark" alt="languages" />

**Apps & web**<br/>
<img src="https://skillicons.dev/icons?i=react,nodejs,express,astro,electron,androidstudio&theme=dark" alt="apps and web" />

**Hardware & tools**<br/>
<img src="https://skillicons.dev/icons?i=arduino,raspberrypi,linux,ubuntu,git,docker,vercel&theme=dark" alt="tools" />

</div>

---

## GitHub stats

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=UnknownEng&theme=github_dark" alt="GitHub profile details" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=UnknownEng&theme=github_dark" alt="Repos per language" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=UnknownEng&theme=github_dark" alt="Most commit language" />

<img src="https://streak-stats.demolab.com/?user=UnknownEng&hide_border=true&background=0f2027&ring=2ed6a0&fire=2ed6a0&currStreakLabel=2ed6a0&sideLabels=c9d1d9&dates=8b949e&currStreakNum=ffffff&sideNums=ffffff" alt="GitHub streak" />

</div>

---

<div align="center">

**Open to** research collaborations · robotics/UAV internships · freelance autonomy projects

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mansoorahmedrind/)
[![Email](https://img.shields.io/badge/Email-Say%20hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:unknownengineer23@gmail.com)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2ed6a0,50:203a43,100:0f2027&height=100&section=footer" alt="" />

</div>
