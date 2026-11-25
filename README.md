# Awesome-Monocular-RGB-Motion-Capture-Webcam-Tracking

# Top Monocular RGB Motion Capture & Webcam Tracking Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Single-Camera 3D Human Pose Estimation, Webcam Full-Body/Face/Hand Tracking, VTuber/VMC Streaming & Video-to-Mocap Pipelines*  
**Last updated: November 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Monocular RGB Motion Capture & Webcam Tracking**. These tools extract 3D skeletal poses, SMPL/SMPL-X body meshes, facial blendshapes, and finger kinematics from standard webcams or single RGB video feeds—streaming live into Blender, Unreal Engine, Unity, and VTuber avatars without specialized mocap suits.

**Examples** include Move.ai, DeepMotion, Plask, Rokoko Studio (Vision), Kinetix, RADiCAL Motion, Wonder Dynamics, Cascadeur Cloud, Anyworld, ActorCore, and `toyxyz/toyxyz_rgbmocap` (the category leaders). 

**Open-source emphasis**: This section is heavily expanded with every major active project for real-time webcam motion capture (`MediaPipe`, `OpenSeeFace`, `VSeeFace`/VMC bridges), monocular 3D human mesh recovery (`WHAM`, `4D-Humans`, `GVHMR`, `HybrIK`), and Blender/UE/Unity live-link receivers — ideal for indie game devs, 3D animators, VTubers, and computer vision researchers.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Move.ai (Move One)](https://move.ai)**  
  Cloud markerless motion capture platform extracting studio-grade 3D skeletal animations from single iPhone or multi-camera RGB videos.

- **[DeepMotion (Animate 3D)](https://deepmotion.com)**  
  Browser-based AI motion capture service converting standard RGB videos into 3D skeletal animations with physics simulation and foot-locking.

- **[Plask](https://plask.ai)**  
  Cloud AI motion capture and browser-based 3D keyframe animation editor enabling instant video-to-mocap extraction and retargeting.

- **[Rokoko Video & Studio](https://rokoko.com)**  
  AI-powered single-camera webcam/video motion capture service integrated directly with Rokoko Studio, Blender, Unity, and Unreal Engine.

- **[Kinetix](https://kinetix.tech)**  
  No-code cloud AI platform transforming standard monocular videos into 3D character emotes and game-ready animations.

- **[RADiCAL (RADiCAL Studio)](https://radicalmotion.com)**  
  Cloud-native real-time 3D motion capture platform streaming live monocular RGB skeletal tracking directly into 3D engines.

- **[Wonder Dynamics (Autodesk Flow Studio)](https://wonderdynamics.com)**  
  Cloud AI VFX platform automatically tracking, animating, lighting, and compositing 3D CG characters from single-camera live-action video.

- **[Cascadeur Cloud & AI AutoPosing](https://cascadeur.com)**  
  Physics-assisted 3D keyframe animation software featuring AI pose prediction and cloud-connected animation workflows.

- **[Anyworld](https://anyworld.ai)**  
  Generative AI platform creating interactive, physics-aware 3D characters and animated behaviors for virtual worlds and games.

- **[Reallusion ActorCore & AccuRIG](https://reallusion.com)**  
  Cloud library of motion-captured 3D animations and automated character rigging tools compatible with monocular mocap pipelines.


## Open-Source GitHub Projects

- **[toyxyz/toyxyz_rgbmocap](https://github.com)**  
  Open-source monocular RGB motion capture pipeline enabling accessible, camera-based full-body tracking and 3D character animation workflows.

- **[MediaPipe Holistic & Pose Landmarker (Google)](https://github.com)**  
  Industry-standard, real-time open-source ML pipeline tracking 33 body landmarks, 21 hand landmarks per hand, and 478 facial blendshapes from a single webcam at 30–60+ FPS.

- **[WHAM (World-grounded Humans with Accurate Motion)](https://github.com)**  
  State-of-the-art open-source monocular video-to-3D-mocap framework recovering accurate global world-space trajectories and foot-ground contacts even from moving cameras.

- **[GVHMR (World-Grounded Human Motion Recovery via Gravity-View Coordinates)](https://github.com)**  
  High-precision open-source monocular 3D human motion recovery model estimating drift-free global human trajectories from single-camera videos.

- **[4D-Humans (HMR 2.0)](https://github.com)**  
  Open-source transformer-based 3D human mesh recovery and tracking system reconstructing full-body SMPL motion from in-the-wild monocular video.

- **[NLF / Neural Localizer Fields & SMPLest-X](https://github.com)**  
  Modern open-source single-image and video 3D human pose and parametric mesh estimation models supporting whole-body, hand, and face recovery.

- **[OpenSeeFace](https://github.com)**  
  Fast, lightweight open-source CPU-friendly facial landmark and head-pose tracker widely used for webcam VTubing and VMC protocol streaming.

- **[FreeMoCap](https://github.com)**  
  Free, open-source markerless motion capture suite supporting both single-camera MediaPipe/YOLOv8 tracking and multi-webcam 3D triangulation with direct Blender export.

- **[BlendArMocap](https://github.com)**  
  Open-source Blender add-on performing real-time webcam tracking of hands, face, and full-body pose directly inside Blender via MediaPipe.

- **[MMPose (OpenMMLab)](https://github.com)**  
  Comprehensive open-source PyTorch toolbox for 2D/3D human pose estimation, whole-body tracking (`RTMPose`), hand pose, and animal/object keypoint detection.

- **[AlphaPose](https://github.com)**  
  Accurate open-source real-time multi-person whole-body pose estimation and tracking system supporting 136 keypoints (body, foot, face, and hands).

- **[OpenPose (CMU Perceptual Computing Lab)](https://github.com)**  
  The pioneering open-source real-time multi-person keypoint detection library for body, face, hands, and foot estimation from single RGB cameras.

- **[HybrIK (Hybrid Analytical-Neural Inverse Kinematics)](https://github.com)**  
  Open-source 3D human pose and shape estimation framework directly bridging 3D keypoint detection with analytical inverse kinematics for clean skeletal rotations.

- **[VMC (Virtual Motion Capture) Protocol & `vmc-osc` Bridges](https://vmc.info)**  
  Open-source OSC-based skeletal and blendshape streaming standard connecting webcam trackers (`OpenSeeFace`, `MediaPipe`) to VRM avatars, Unity, Unreal, and Blender.

- **[MocapNET](https://github.com)**  
  Open-source real-time 3D human pose estimator converting 2D RGB webcam skeletons directly into BVH (BioVision Hierarchy) skeletal rotations.

- **[EasyMocap](https://github.com)**  
  Open-source toolbox for 3D human motion capture and SMPL parameter reconstruction supporting both monocular RGB videos and multi-view camera setups.

- **[ExpyKit & Rokoko-style Retargeting Add-ons for Blender](https://github.com)**  
  Open-source Blender rigging and animation retargeting utilities for mapping raw monocular BVH/FBX/SMPL mocap outputs onto Rigify and game armatures.

### Additional Strong Open-Source Options

- **[YOLO11-Pose / Ultralytics Pose](https://github.com)** for ultra-fast real-time single-stage RGB keypoint detection on edge GPUs and webcams.
- **[KalidoKit](https://github.com)** for a lightweight browser-based kinematic solver converting MediaPipe 2D/3D webcam landmarks into smooth VRM/Live2D joint rotations.
- **[WiLoR / HaMeR](https://github.com)** for high-accuracy open-source 3D hand and finger mesh reconstruction from monocular RGB cameras.
- **[SMPL-X (`vchoutas/smplx`)](https://github.com)** for the standard open-source unified 3D body, face, and hand parametric model used by WHAM, GVHMR, and 4D-Humans.
- Many community **Blender BVH foot-skate cleanup scripts**, **Webcam-to-Unreal LiveLink OSC plugins**, and **Three.js / WebGPU real-time webcam avatar mirrors**.

**Frameworks for building custom systems**: Combine **MediaPipe / KalidoKit** (real-time webcam streaming), **WHAM / GVHMR** (offline high-accuracy video-to-mocap), **FreeMoCap / BlendArMocap**, and **Blender + ExpyKit** with **toyxyz/toyxyz_rgbmocap** for a complete, zero-suit monocular motion capture studio.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Monocular RGB motion capture suffers from inherent depth ambiguity, self-occlusion, and foot-sliding compared to optical multi-camera or inertial mocap suits; always apply temporal smoothing filters and inverse-kinematics foot locking in Blender, Unity, or Unreal Engine for production animation.
- Parametric body models (`SMPL`/`SMPL-X`) carry specific academic vs. commercial licensing terms; verify model licenses before shipping commercial games or films.

---

**Made for 3D animators, indie game developers, VTubers, and computer vision researchers.**  
Let's make monocular motion capture and webcam tracking more accurate, accessible, and open.
