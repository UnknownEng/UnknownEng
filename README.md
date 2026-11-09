<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2ed6a0&height=200&section=header&text=Mansoor%20Ahmed&fontSize=58&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=UAV%20Autonomy%20%E2%80%A2%20Swarm%20Robotics%20%E2%80%A2%20ROS%202&descAlignY=58&descSize=18" alt="Mansoor Ahmed" />

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3200&pause=900&color=2ED6A0&center=true&vCenter=true&width=700&lines=Founder+%40+Aero+Mavericks;UAV+Autonomy+%26+Multi-Robot+Swarm+Engineer;ROS+2+%E2%80%A2+PX4%2FArduPilot+%E2%80%A2+Computer+Vision;Teknofest+Finalist+%E2%80%A2+Aerothon'25+3rd+Overall;Electrical+Engineering+%40+NUST+'27)](https://git.io/typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mansoorahmedrind-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/mansoorahmedrind/)
[![Portfolio](https://img.shields.io/badge/Portfolio-visit-2ed6a0?style=flat-square&logo=vercel&logoColor=black)](https://personal-portfolio-swart-sigma-44.vercel.app/)
[![Email](https://img.shields.io/badge/Email-ahmedmansoorrind1210-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:ahmedmansoorrind1210@gmail.com)
[![Fiverr](https://img.shields.io/badge/Fiverr-hire%20me-1DBF73?style=flat-square&logo=fiverr&logoColor=white)](https://www.fiverr.com/s/5r2dqg4)
![Profile Views](https://komarev.com/ghpvc/?username=UnknownEng&label=views&color=2ed6a0&style=flat-square)

</div>

---

## About me

I build **autonomous drones and multi-robot swarms**, from Gazebo simulation to real flight.

I'm an Electrical Engineering undergraduate at **NUST, Islamabad (Class of 2027)**, a **Rector's Gold Medalist**, and founder of **[Aero Mavericks](https://github.com/UnknownEng/Team-Website)**, a student UAV team that builds autonomous aircraft for disaster relief, medical delivery and precision missions. I've spent the last 2+ years working on UAV autonomy.

```yaml
focus:      [UAV autonomy, swarm robotics, precision landing, GPS-denied navigation]
stack:      [ROS 2, Nav2, MAVROS, PyMAVLink, PX4, ArduPilot, Gazebo]
vision:     [OpenCV, YOLOv8, depth cameras, visual-inertial SLAM]
hardware:   [Pixhawk, Raspberry Pi, ESP32, Arduino, radio telemetry]
currently:  Founder @ Aero Mavericks · Freelance Robotics Consultant
open_to:    [research collaborations, robotics/UAV internships, freelance autonomy work]
```

---

## Experience

| Role | Organization | When |
|---|---|---|
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

## Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🐝 [Resilient Swarm Formation](https://github.com/UnknownEng/resilient-swarm-formation)
Decentralized formation control for 5 robots: **no leader, no GPS, no central coordinator**. Each robot runs an EKF and a formation controller, and a **CBF-QP safety filter** checks every command before it reaches the motors.

- **100% convergence and 0 collisions** across a 550-run campaign
- Tested under 15% packet loss, 80 ms delay, one-way links and stalled robots

`ROS 2 Jazzy` `Gazebo Harmonic` `Python` `EKF` `CBF`

</td>
<td width="50%" valign="top">

### 🛩️ [Fail-Safe Indoor UAV Navigation](https://github.com/UnknownEng/Layered-ROS-2-Nav2-Architecture-for-Fail-Safe-Indoor-UAV-Navigation)
A layered **ROS 2 / Nav2** autonomy stack for GPS-denied indoor flight. A separate safety layer monitors every Nav2 velocity command and **brakes deterministically** for dynamic obstacles before the command reaches the flight controller.

`ROS 2` `Nav2` `Collision Monitor` `PX4/ArduPilot`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📷 [GPS-Denied Navigation via Depth Camera](https://github.com/UnknownEng/gps-denied-navigation-via-depth-camera)
UAV navigation without GPS, using onboard depth sensing and vision-based velocity control.

`Python` `Depth Camera` `MAVLink` `OpenCV`

</td>
<td width="50%" valign="top">

### 🗺️ [Drone Orthomosaic Mapping](https://github.com/UnknownEng/webodm-based-mapping-algorithm-using-drone)
A pipeline that turns UAV survey imagery into georeferenced orthomosaic maps with WebODM.

`Python` `WebODM` `Photogrammetry`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💊 [Sasta Dawa Finder](https://github.com/UnknownEng/sasta-dawa-finder) · [live](https://sasta-dawa-finder.vercel.app)
Search a medicine brand and find lower-cost alternatives with the same formula.

`JavaScript` `Vercel`

</td>
<td width="50%" valign="top">

### ⚖️ [LawerAI](https://github.com/UnknownEng/lawerai) · [live](https://lawerai-alpha.vercel.app)
An AI legal assistant.

`Python` `LLM` `Vercel`

</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>

<br/>

| Area | Repos |
|---|---|
| **Drones / CV** | [DJI Tello Face Tracking](https://github.com/UnknownEng/DJITello-Facetracking-Script) · [Tello Mapping](https://github.com/UnknownEng/DJI-Tello-Mapping-System) · [Tello Monitoring](https://github.com/UnknownEng/Tello-Mnitoring-system) · [Tello Keyboard Control](https://github.com/UnknownEng/KeyBoard-Control-DJI-Tello-Script) · [YOLOv8 Detection](https://github.com/UnknownEng/YOLOv8) · [Drone Digital Twin](https://github.com/UnknownEng/proj_drone_twin) · [Medical Response UAV](https://github.com/UnknownEng/medical-response-basic) |
| **Hardware** | [Arduino F450 Quadcopter](https://github.com/UnknownEng/Arduino-Based-F450-Quadcopter-Drone) · [Raspberry Pi on ArduCopter](https://github.com/UnknownEng/raspberry_pi-on-ArduCopter) · [CAD Drone Design](https://github.com/UnknownEng/CAD-Drone-Design) · [Designing LiDAR](https://github.com/UnknownEng/Designing-Lidar) · [4-DOF WiFi Robotic Arm](https://github.com/UnknownEng/4-DOF-Wifi-Web-Control-Motion-Repeater-Robotic-ARM) |
| **Web** | [Personal Portfolio](https://github.com/UnknownEng/Personal-Portfolio) · [Aero Mavericks Website](https://github.com/UnknownEng/Team-Website) |

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
