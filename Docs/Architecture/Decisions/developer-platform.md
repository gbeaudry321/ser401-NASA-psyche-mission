# Developer Platform for NASA Psyche Mission VR Experience
***Time to read: 2 min***

|||
|--|--|
|Status|Accepted|
|Decision Maker(s)|Gavin Beaudry, Esaias Glasco, Grant Kelsay, Will Mastronardi, Chris Rogers|
|Decision Date|September 23, 2023|
|Last Revision Date| |
|Superseded Date| |
|Superseded By| |

## Context and Problem Statement
The NASA Psyche mission is a significant scientific endeavor to explore the metallic asteroid Psyche, located in the asteroid belt between Mars and Jupiter. As part of NASA's public outreach efforts, a VR experience is being developed as a capstone project to explore and learn about the mission in an immersive way. The choice of the development platform is a critical decision in ensuring the success of this VR experience.

## Scope
This ADR refers to the 3D virtual reality developer platform to be used by the team.

## Considered Options
|Decision|Option|
|--|--|
|Accepted|Unreal Engine 5|
|Denied|Unity|
|Denied|WebXR|

## Rationale
1. **Realistic Graphics and Physics:** Unreal Engine is renowned for its powerful rendering capabilities and physics simulations, making it well-suited for creating highly realistic and immersive VR experiences. This aligns with the project's goal of providing users with a visually engaging and accurate representation of the Psyche asteroid.
2. **Performance:** Unreal Engine's performance optimization and scalability capabilities are well-documented. This ensures that the VR experience can run smoothly on a wide range of hardware configurations, including high-end VR headsets and more accessible platforms.
3. **Cross-Platform Compatibility:** Unreal Engine supports multiple platforms, including PC, VR headsets (such as Oculus Rift 2 and HTC Vive), and even mobile devices. This flexibility ensures that the VR experience can reach a broad audience.
4. **Community and Resources:** Unreal Engine has a large and active development community. This provides access to a wealth of resources, tutorials, and plugins that can expedite development and troubleshooting efforts.
5. **Interactivity:** Unreal Engine offers a robust set of tools and features for creating interactive and dynamic VR environments. This will allow us to implement engaging features, such as realistic physics-based interactions and user-driven exploration, enhancing the educational and experiential value of the project.

## Decision Outcome
The choice of Unreal Engine as the development platform for the NASA Psyche mission VR Experience is expected to result in a high-quality, immersive VR experience that aligns with the project's goals. The decision takes into account the project's technical requirements, available resources, and the potential for a rich and interactive user experience.