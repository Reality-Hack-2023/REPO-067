# Haptic Vision

## Enhancing Navigation for the Visually Impaired through Virtual Reality and Haptic Feedback

<table>
  <tr>
    <td>
     Haptic Vision is an innovative assistive technology designed to improve navigation and spatial awareness for individuals with visual impairments. By integrating virtual reality (VR) and haptic feedback, Haptic Vision aims to enhance independence and quality of life for the visually impaired population.
    </td>
     <td>
      <img src="https://user-images.githubusercontent.com/39020723/218214123-f66f583e-3f93-461e-9d06-ebd59a3d3cc9.jpg" alt="project overview" width="2600px">
    </td>
  </tr>
</table>




## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Technology Stack](#technology-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Development Process](#development-process)
- [Challenges and Solutions](#challenges-and-solutions)
- [Future Work](#future-work)
- [Team](#team)
- [Demo and Pitch](#demo-and-pitch)

## Overview

<table>
  <tr>
    <td>
     Visual impairment affects approximately 253 million people worldwide (WHO, 2024), presenting significant challenges in daily activities such as navigation and environmental interaction. Haptic Vision addresses these challenges by leveraging cutting-edge technologies to create a more intuitive and informative navigational experience.
    </td>
     <td>
      <img src="https://github.com/user-attachments/assets/6f5de09e-6556-42d0-bec1-71d677a77542" alt="BCI headband" width="1200px">
    </td>
  </tr>
</table>

## Features

- Environmental mapping and 3D modeling of surroundings
- AI-powered object detection for common items (e.g., chairs, tables)
- Distance approximation using ray casting
- Haptic feedback with variable frequency (15-30 Hz) based on object proximity
- Complementary audio cues for enhanced awareness

## Technology Stack

- **Hardware**:
  - VR Headset: HTC Vive Pro Eye
  - Haptic Feedback: HaptX gloves
  - Spatial Tracking: Lighthouse system

- **Software**:
  - Development Platform: Unity 19.4.31f
  - SDKs: 
    - HaptX 2.0.0 beta 8
    - SRworks

- **Operating System**: Windows 11

## Installation

1. Ensure you have Unity 19.4.31f installed on your Windows 11 system.
2. Clone this repository to your local machine.
3. Open the project in Unity.
4. Install the required SDKs:
   - HaptX 2.0.0 beta 8
   - SRworks
5. Connect the HTC Vive Pro Eye headset and HaptX gloves to your system.
6. Set up the Lighthouse tracking system according to the manufacturer's instructions.
7. Build the project in Unity for your VR platform.

## Usage

1. Put on the HTC Vive Pro Eye headset and HaptX gloves.
2. Launch the Haptic Vision application.
3. The system will automatically start mapping your environment.
4. Move your hands to detect objects in your surroundings:
   - As your hands approach objects, you'll feel vibrations through the HaptX gloves.
   - The intensity of the vibrations increases as you get closer to objects.
   - Audio cues will provide additional information about detected objects.
5. Use the haptic and audio feedback to navigate your environment safely.

## Development Process

1. **Problem Definition**: Identified specific challenges faced by visually impaired individuals in navigation.
2. **Solution Ideation**: Collaborated on potential approaches, focusing on haptic feedback as the primary modality.
3. **Prototype Development**: Integrated VR and haptic technologies using Unity, implementing object detection and distance approximation algorithms.
4. **Testing and Refinement**: Conducted user testing with visually impaired individuals to gather feedback and improve the system.

## Challenges and Solutions

| Challenge | Solution |
|-----------|----------|
| SRworks compatibility | Used Unity v19.1 as recommended by VIVE mentors |
| Hand tracking with SRworks | Opted for fixed orientation and adjusted hand position for mesh interaction |
| Distance approximation accuracy | Cast hands a few units in front of their actual position for smoother interaction |
| Limited testing devices | Focused on frequency adjustment with constant amplitude for haptic feedback |

## Future Work

- Enabling audio feedback
- Implementing active scanning with an on/off feature
- Developing a smaller, more discreet headset
- Improving vision through XR glasses recalibration
- Exploring waypoint guidance functionality

## Team

<img src="https://user-images.githubusercontent.com/39020723/218876868-14bd8c83-4ce0-40ac-ae5d-9412d6a081ae.JPEG" alt="project overview" width="600px">

This project was made possible by the dedicated efforts of the Haptic Vision team. Christine, Leon, Winny, Malcolm, and Kyle

## Demo and Pitch

- [Pitch Video](https://youtu.be/4b5lR5_ubpw)
- [Demo Video 1](https://photos.app.goo.gl/2GCe3nBR772Doe9V9)
- [Demo Video 2](https://photos.app.goo.gl/ZfDBynpsBgJS3u7w7)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

We would like to thank:
- The VIVE team for their support and guidance
- Our visually impaired tester for their valuable feedback (Chris MacNally)
- The Unity and HaptX communities for their resources and support
