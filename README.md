<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:0d2045&height=80&section=header" width="100%"/>

# ABUL HASNAT ABDULLAH
**BSc Mechanical Engineering · BUET**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINK_HERE)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB_HERE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:YOUR_EMAIL_HERE)
![Visitors](https://visitor-badge.laobi.icu/badge?page_id=abulhasnat-abdullah.abulhasnat-abdullah)

```yaml
◈ SPRINT  :  30-Day Robotics Simulation Intensive      [ACTIVE 🟢]
  TEAM    :  BUET Interplanetary Mars Rover
  ROLE    :  Sr. Coordinator · Software & Autonomy
             Technical Lead · ERC Remote
  STACK   :  C++ · Python · ROS2 · Nav2 · SLAM · Gazebo
```

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d2045,100:0d1117&height=60&section=footer" width="100%"/>

</div>
---

## `$ whoami`

> **Mechanical Engineering student at BUET**, carving a focused path into **Robotics & Automation**. My passion lives where mechanisms meet intelligence — kinodynamic motion planning, autonomous navigation, and industrial systems that actually work in the real world.
>
> **Senior Coordinator, Software & Autonomy Subteam** and **Technical Lead (ERC Remote)** at the **BUET Interplanetary Mars Rover Team** — shipping real autonomy software for competition-grade rovers under real competition pressure.
>
> Currently running a **🔥 30-day intensive robotics simulation sprint** — designing, simulating, and documenting complete robotic systems from scratch. Every day. No breaks.

---

## `$ cat /roles.yaml`

```yaml
identity:
  degree    : "BSc Mechanical Engineering"
  university: "Bangladesh University of Engineering & Technology (BUET)"
  goal      : "Robotics & Automation Engineer"

rover_team:
  team  : "BUET Interplanetary Mars Rover Team"
  roles :
    - title   : "Senior Coordinator"
      subteam : "Software & Autonomy"
      scope   : "Autonomy stack, ROS2 architecture, team coordination"
    - title   : "Technical Lead"
      event   : "ERC Remote (European Rover Challenge)"
      scope   : "Full technical leadership for remote competition entry"

sprint:
  name   : "30-Day Robotics Simulation Intensive"
  status : ACTIVE 🟢
  focus  :
    - Kinodynamic path planning (RRT* with dynamic constraints)
    - ROS2 Humble + MoveIt2 + Gazebo simulation pipeline
    - Warehouse AGV navigation stack
    - 3D terrain-aware localization
```

---

## `$ ls -la /skills`

### Core Stack

| Domain | Tools & Frameworks | Proficiency |
|--------|-------------------|-------------|
| **Programming** | C++, Python | ██████████ Proficient |
| **Robot OS** | ROS2 (Humble/Iron), rclpy, rclcpp | █████████░ Strong |
| **Navigation** | Nav2, SLAM Toolbox, AMCL | ████████░░ Strong |
| **Simulation** | Gazebo, RViz2, PyBullet | ████████░░ Strong |
| **Motion Planning** | MoveIt2, OMPL, Kinodynamic RRT* | ███████░░░ Advancing |
| **Modeling** | URDF, XACRO, SDF | ████████░░ Strong |
| **Autonomy** | Localization, Mapping, Path Planning | ████████░░ Strong |
| **Version Control** | Git, GitHub | █████████░ Strong |

### Also Working With
`OpenCV` · `Matplotlib` · `Linux / Ubuntu` · `CMake` · `YAML` · `Bash` · `SolidWorks`

---

## `$ git log --oneline --projects`

### 🏜️ BUET Mars Rover — Autonomy Stack *(Team Project)*
Full autonomous navigation and task execution system for a competition-grade Mars rover. Responsible for SLAM integration, Nav2 waypoint navigation, and ROS2 architecture as Software & Autonomy Senior Coordinator. Deployed for **ERC Remote**.

### 🌍 [`interplanetar_mars_rover_simulation`](https://github.com/abulhasnat-abdullah/interplanetar_mars_rover)
Gazebo simulation of the BUET Interplanetary Mars Rover with full Nav2 stack and SLAM. The digital twin before the real-world deployment.

### 📦 Warehouse AGV *(In Progress)*
Autonomous Ground Vehicle for warehouse logistics — Nav2 navigation stack, obstacle avoidance, and kinodynamically-constrained path replanning in a simulated warehouse environment.

### 🦾 [`arm_visualizer`](https://github.com/abulhasnat-abdullah/arm_visualizer)
Real-time 3D robot arm visualization engine. Renders joint states, end-effector trajectories, and workspace envelopes — kinematic analysis at a glance.

### 🎙️ [`voice_controlled_robot`](https://github.com/abulhasnat-abdullah/voice_controlled_robot)
Speech-to-command robotic control interface. Natural language parsed and mapped to motor commands — bridging human intent and machine action.

---

## `$ top` *(active processes)*

```
PID   NAME                              STATUS     INTENSITY
001   warehouse_agv_nav2_stack          RUNNING    █████████░
002   kinodynamic_rrt_star_planner      RUNNING    ████████░░
003   3d_terrain_aware_localization     RUNNING    ███████░░░
004   manipulator_arm_pipeline          RUNNING    ███████░░░
005   erc_remote_autonomy_prep          QUEUED     ██░░░░░░░░
```

---

## `$ cat /research_interests.md`

<details>
<summary><b>🧭 Kinodynamic Motion Planning</b> &nbsp;—&nbsp; <i>click to expand</i></summary>
<br>

> Sampling-based planners (RRT*, RRT-Connect) extended with velocity bounds, torque limits, and inertial dynamics. Focus on real-time replanning in dynamic environments where classic geometric planners fail.

- RRT* variants under physical (kinodynamic) constraints
- Real-time replanning under dynamic obstacles
- Benchmarking kinodynamic vs geometric planners on rover hardware

</details>

<details>
<summary><b>🗺️ Autonomous Mobile Robotics</b> &nbsp;—&nbsp; <i>click to expand</i></summary>
<br>

> Robust localization and mapping for GPS-denied environments — from warehouse floors to Mars analog terrain. Integrating heterogeneous sensor streams into coherent world models.

- SLAM in GPS-denied, unstructured environments
- Multi-sensor fusion: LiDAR + IMU + Camera
- Long-horizon navigation with semantic map representations

</details>

<details>
<summary><b>🏭 Industrial Automation & Human-Robot Collaboration</b> &nbsp;—&nbsp; <i>click to expand</i></summary>
<br>

> AGV systems that operate safely and efficiently in environments shared with human workers. Task planning that is aware of human intent and proximity.

- Kinodynamically-constrained AGV routing in warehouse settings
- Safe task planning alongside dynamic human presence
- Collision prediction and proactive replanning

</details>

<details>
<summary><b>🔴 Mars Analog Terrain Navigation</b> &nbsp;—&nbsp; <i>click to expand</i></summary>
<br>

> Traversability analysis and perception pipelines tailored for planetary surfaces — loose regolith, sharp rocks, and steep slopes that challenge classical navigation assumptions.

- Terrain classification and traversability scoring
- Perception pipelines for extraterrestrial surface types
- 3D terrain-aware localization for rover locomotion

</details>

---

## `$ cat /philosophy.txt`

> *"Mechanical Engineering taught me how systems **fail**.*
> *Robotics is teaching me how to make them **not**.*
>
> *A rover navigating Mars terrain autonomously,*
> *a warehouse AGV that never blocks an aisle —*
> *that's not magic. That's physics + planning + code,*
> *executed precisely.*
>
> *That's what I'm building toward."*
>
> — `abul@buet-robotics`

---

## `$ cat /roadmap.md`

- [x] Robot arm URDF modeling & visualization
- [x] ROS2 autonomy stack for Mars Rover (ERC Remote)
- [x] Gazebo simulation of Mars Rover with Nav2 + SLAM
- [x] Voice-controlled robot interface
- [ ] Warehouse AGV — full Nav2 simulation
- [ ] Kinodynamic RRT* implementation + benchmarking paper
- [ ] 3D terrain-aware localization on physical rover
- [ ] Multi-robot coordination system
- [ ] Publish research on constrained motion planning

---

## `$ git stats`

<div align="center">

[![GitHub Trophy](https://github-profile-trophy.vercel.app/?username=abulhasnat-abdullah&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

<div align="center">

<img height="160em" src="https://github-readme-stats.vercel.app/api?username=abulhasnat-abdullah&show_icons=true&theme=github_dark&hide_border=true&include_all_commits=true&count_private=true" />
<img height="160em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=abulhasnat-abdullah&layout=compact&theme=github_dark&hide_border=true&langs_count=8" />

</div>

<div align="center">

[![GitHub Streak](https://streak-stats.demolab.com?user=abulhasnat-abdullah&theme=github-dark-blue&hide_border=true&date_format=M%20j%5B%2C%20Y%5D)](https://git.io/streak-stats)

</div>

---

<div align="center">

**`Currently simulating · Always building · Shipping in public`**

*"The best engineers don't wait for the right opportunity. They simulate it first."*

</div>
