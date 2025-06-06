# Real-Time Gaze Heatmap Shader

Click image to Play
[![Preview Video](https://img.youtube.com/vi/8MFfP0brp5g/0.jpg)](https://youtu.be/8MFfP0brp5g)

## Why this matters for UX in VR/3D development

- **Immediate Attention Mapping**  
  Live visual feedback on user focus—no post-session analytics or external hardware needed.  
- **Iterative Design**  
  Spot “dead zones” and hotspots in real time; tweak lighting, geometry, or narrative cues accordingly.  
- **Accessibility & Comfort**  
  A subtle heatmap overlay guides players toward points of interest, reducing disorientation and improving onboarding.

## How it works at a glance

- **Raycasting**  
  Cast a ray from the camera’s forward vector each frame to detect the surface you’re looking at.  
- **Heat Accumulation**  
  Accumulate “heat” values on that material’s UV coordinates—areas you linger on grow brighter over time.  
- **Color Blending**  
  Blend a gradient overlay onto the material, with red for high-focus areas and green for emerging interest points.  
