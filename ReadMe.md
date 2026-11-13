# Namruth S

Embedded systems · Robotics · Firmware

I design and build embedded systems across firmware, hardware, and system integration, with a focus on robotics and autonomous mobility. I work from concept through to deployment, and I care about deterministic timing, measurable performance, and designs that stay maintainable as they scale.

Electronics and Communication Engineering, REVA University.

<br>

## Engineering focus

| Discipline | Scope |
|:--|:--|
| Real-time firmware | Task scheduling and deterministic control loops on FreeRTOS |
| Embedded systems | Firmware for STM32 and ESP32 platforms |
| Motion control | Coordinated multi-servo control under real-time constraints |
| Robotics | Kinematics, gait generation and autonomous navigation for legged platforms |
| Sensor fusion | Combining multiple sensing sources into a state estimate for control |
| Hardware and PCB design | Schematic capture and board layout in KiCad |
| Embedded Linux | Raspberry Pi as a compute and integration layer |
| Edge AI and vision | Computer vision pipelines on embedded targets, built on OpenCV |
| Wireless and IoT | Sensor-driven wireless systems over MQTT |
| System integration | Bringing firmware, electronics and mechanics together into one working system |

<br>

## Featured work: RÄIQKÖNEN

A quadrupedal exploration robot for rough terrain and autonomous navigation. It is a long-running platform build covering hardware architecture, real-time control, sensing and onboard computation. Named after Kimi Räikkönen.

<!-- Verify this diagram against the actual architecture and edit labels to match. -->

```mermaid
flowchart LR
    S[Onboard sensors] --> F[State estimation<br/>sensor fusion]
    V[Edge vision] --> N[Navigation and<br/>gait planning]
    F --> N
    N --> K[Inverse kinematics]
    K --> C[Real-time servo control<br/>FreeRTOS]
    C --> A[Actuators]
    A -. feedback .-> S
```

**Supporting subsystems:** multi-servo real-time control, edge vision pipelines, custom PCB design, wireless sensing.

[Browse repositories](https://github.com/exotic-namruth?tab=repositories)

<br>

## Selected technologies

| | |
|:--|:--|
| Languages | C, C++, Python |
| Platforms | STM32, ESP32, Arduino, Raspberry Pi |
| Operating systems | FreeRTOS, Linux |
| Libraries and protocols | OpenCV, MQTT |
| Tools | KiCad, Git, VS Code |

<br>

## Currently

- Multi-servo real-time control for RÄIQKÖNEN
- Edge-based computer vision pipelines
- Custom PCB design and embedded hardware optimization
- Wireless, sensor-driven systems

Outside engineering: Formula 1, Oracle Red Bull Racing.

<br>

## GitHub

<p>
  <img alt="GitHub stats" height="165" src="https://github-readme-stats.vercel.app/api?username=exotic-namruth&hide_border=true&include_all_commits=true&count_private=true&theme=dark&bg_color=0d1117&title_color=94a3b8&text_color=cbd5e1&icon_color=64748b#gh-dark-mode-only" />
  <img alt="GitHub stats" height="165" src="https://github-readme-stats.vercel.app/api?username=exotic-namruth&hide_border=true&include_all_commits=true&count_private=true&title_color=475569&text_color=334155&icon_color=64748b#gh-light-mode-only" />
  <img alt="Top languages" height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=exotic-namruth&layout=compact&hide_border=true&langs_count=6&theme=dark&bg_color=0d1117&title_color=94a3b8&text_color=cbd5e1#gh-dark-mode-only" />
  <img alt="Top languages" height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=exotic-namruth&layout=compact&hide_border=true&langs_count=6&title_color=475569&text_color=334155#gh-light-mode-only" />
</p>

<br>

## Contact

[exotic.namruth@gmail.com](mailto:exotic.namruth@gmail.com) · [LinkedIn](https://www.linkedin.com/in/namruth-s-80122b31a)
