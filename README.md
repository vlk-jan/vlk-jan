# Jan Vlk

**Autonomous systems researcher | PhD candidate in Cybernetics and Robotics**

![Profile Banner](assets/banner.png)

I am a researcher and PhD student at the [Vision for Robotics and Autonomous Systems (VRAS) Group](https://cyber.felk.cvut.cz/research/groups-teams/vras/), [Czech Technical University in Prague](https://www.cvut.cz/en). My work connects perception and control: I build robots that understand difficult terrain, choose safe actions, and operate reliably outdoors.

Currently, I am developing physics-guided learning methods for terrain-aware robot navigation. My earlier research focused on LiDAR perception for autonomous driving, including unsupervised 4D panoptic segmentation and real-time deployment on robotic platforms.

I care about systems that survive contact with the real world. That shows up in my research and in competitions: our team placed **2nd at [Robotour 2025](https://robotika.cz/competitions/robotour/2025/en)** with an autonomous beer-delivery robot, and I placed **2nd at the Porsche Engineering Student Contest 2022** with autonomy software for a 1:10-scale vehicle.

## Research

My current interests include:

- **Physics-guided learning** for terrain-aware navigation and control
- **LiDAR perception**, especially semantic and instance segmentation in driving scenes
- **4D panoptic segmentation**, maintaining temporally consistent instance identities across point-cloud sequences
- **Multi-sensor fusion** combining LiDAR, cameras, and depth sensing
- **Autonomous navigation** in unstructured outdoor environments
- **Real-time deployment** on embedded platforms (NVIDIA Jetson) and mobile robots in the field

My dissertation topic is *Physics-Guided Learning for Machine Control*. The goal is to let autonomous robots exploit terrain properties obtained through perception and physics-informed neural networks, rather than treating the ground as an abstraction.

## Selected Work

### [FlowSeg4D](https://vlk-jan.github.io/publication/masters-thesis)

**Unsupervised 4D panoptic segmentation for LiDAR driving scenes.**

Developed for my master's thesis, FlowSeg4D combines unsupervised scene flow estimation with clustering to produce temporally consistent instance identities without labeled training data. On the SemanticKITTI validation benchmark, it achieves an **LSTQ of 46.9** with **zero labeled training samples** while processing LiDAR sequences online.

[Code](https://github.com/ctu-vras/FlowSeg4D) | [Live visualizer](https://vlk-jan.github.io/assets/demos/semkitti-vis/) | [Thesis](http://hdl.handle.net/10467/122473)

### [Autonomous Road Crossing](https://vlk-jan.github.io/publication/bachelors-thesis)

**Behavior-tree control for a mobile robot crossing through traffic.**

For my bachelor's thesis, I developed and evaluated a behavior-tree controller that tracks surrounding vehicles, reasons about safe crossing gaps, and decides when to cross. The system was validated both in simulation and on a Boston Dynamics Spot robot, earning the **CTU FEE Dean's Award**.

[Code](https://github.com/vlk-jan/road_crossing) | [Thesis](http://hdl.handle.net/10467/109306)

### [SimView](https://vlk-jan.github.io/simview/)

**A batched 3D simulation visualizer for robotics research.**

SimView renders parallel robot simulation runs side by side or overlaid on shared terrain. It includes a Python scene-building API, a Three.js viewer, timeline playback, terrain layers, telemetry plots, and a CLI for inspection and regression checks.

[Code](https://github.com/vlk-jan/simview) | [Live demo](https://vlk-jan.github.io/simview/demo/) | [PyPI](https://pypi.org/project/simview/)

### [map_data](https://vras-robotour.github.io/map_data/)

**OpenStreetMap data as navigation layers for autonomous robots.**

This package turns OSM features into footway, road, and barrier layers suitable for planning and costmap generation. It works as a standalone Python library, includes an interactive Leaflet viewer and route planning, and can also be deployed as a ROS 2 package.

[Code](https://github.com/vras-robotour/map_data) | [Live demo](https://vras-robotour.github.io/map_data/demo)

More projects, demos, and publication details are on [vlk-jan.github.io](https://vlk-jan.github.io/).

## Technical Skills

![Core languages](https://skillicons.dev/icons?i=python,cpp,latex,matlab,bash&theme=dark)

![Robotics and learning](https://skillicons.dev/icons?i=ros,pytorch,opencv&theme=dark)

![Tools and platforms](https://skillicons.dev/icons?i=git,docker,linux,vim,gazebo&theme=dark)

## Get in Touch

- [Personal website](https://vlk-jan.github.io/)
- [CV](https://vlk-jan.github.io/files/jan-vlk-cv.pdf)
- [Email](mailto:vlkjan6@fel.cvut.cz)
- [LinkedIn](https://www.linkedin.com/in/vlk-jan)

## GitHub Activity

![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=vlk-jan&theme=dark&hide_border=false&include_all_commits=false&count_private=false&layout=compact)

![GitHub stats](https://github-readme-stats.vercel.app/api?username=vlk-jan&theme=dark&hide_border=false&include_all_commits=false&count_private=false)
