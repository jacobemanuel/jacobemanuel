# Jakub Majewski

I'm a software engineer in Munich with a background in Management & Technology. I build software end to end: XR apps, real-time 3D from engineering CAD, machine learning, and knowledge tools for teams that use AI agents. At TUM I research Gaussian Splatting for real-time 3D on standalone headsets, together with [Qing Cheng](https://cvg.cit.tum.de/members/cheq) and supervised at [Prof. Daniel Cremers' Chair of Computer Vision and Artificial Intelligence](https://cvg.cit.tum.de/members/cremers).

**[majewski.studio](https://majewski.studio)** · [LinkedIn](https://www.linkedin.com/in/majewski-studio) · [contact@majewski.studio](mailto:contact@majewski.studio)

## Selected work

- **[Gaussian Splatting on Apple Vision Pro](https://github.com/jacobemanuel/gaussian-splatting-vision-pro)** · Research, TUM<br>
  Test bench that measures how close a trained Gaussian splat model stays to the original 3D object and what it costs to render on a standalone headset. 470 models of five objects trained with OpenSplat on cloud GPUs, and 545,903 frames measured on the headset. Every number can be rebuilt from the raw records, which stay private for now. Public: the case study and [an open pull request to MetalSplatter](https://github.com/scier/MetalSplatter/pull/73).
- **[Large-scale Gaussian Splatting](https://github.com/jacobemanuel/gaussian-splatting-vision-pro/tree/main/large-scenes)** · Research, TUM-XR<br>
  Three large outdoor scenes I captured myself and processed in LCC Studio: the Bismarck Tower near Lake Starnberg, from the air and on the ground, the Alpine town of Leukerbad and the Technical University of Munich. The full scenes have 44.5, 23.3 and 24.1 million splats. On a standalone headset they run with a dynamic level of detail computed on the device, so not every splat is drawn in every frame. Public: the three scenes on SuperSplat ([Bismarck Tower](https://superspl.at/scene/77398c1a), [Leukerbad](https://superspl.at/scene/5fceed98), [Technical University of Munich](https://superspl.at/scene/193ca7e8)) and the case study with the clips.
- **[receptionOS Visualizer](https://github.com/jacobemanuel/receptionos-visualizer-portfolio)** · Industry, client project<br>
  XR app for dental clinics that aligns a patient's face scan, jaw scans and CBCT in 3D and measures across them in millimetres. I took it from an early proof of concept to the client release on my own. Public: the case study and [a code sample with seven tests](https://github.com/jacobemanuel/receptionos-visualizer-portfolio/tree/main/code/scene-lifecycle).
- **[Automotive XR](https://github.com/jacobemanuel/automotive-spatial-visualization-portfolio)** · Industry, in-house application<br>
  App for full-scale vehicle design reviews on a headset, in mixed reality on a physical seating buck (a mock-up with real seats and a real steering wheel) or in 360° environments. I took it over in October 2025, when it was still a research prototype. Since mid-2026 I own its platform, architecture and releases, working with a team of three and an external development partner.
- **[Automotive content pipeline](https://github.com/jacobemanuel/automotive-content-pipeline-portfolio)** · Industry<br>
  Workflow and tools that take car interiors from engineering CAD to the headset. Trim is fitted from reference photos and the measured geometry, in millimetres, starting with the seats: quilting and stitching keep their real size while the seats lose about 70% of their triangles. I also took over the team's Blender add-on and have released eight versions of it.
- **[LEKS](https://github.com/jacobemanuel/leks)** · Tooling, version 2.0<br>
  Local knowledge system for a long-running engineering project, read by people in Obsidian and queried by AI coding agents over MCP. In a scaling test with 10,027 pages, 91 of them real, 95% of searches finish within 68 ms. Public: the case study and [the engine's code with 124 tests](https://github.com/jacobemanuel/leks/tree/main/engine).
- **[Probabilistic building energy prediction](https://github.com/jacobemanuel/building-energy-gpr)** · Course project, TUM<br>
  Heating and cooling load prediction for building designs, with a checked uncertainty range for each prediction. I compared three standard models on the same held-out splits and no single model won: the random forest was best on heating load, the Gaussian process on cooling load, with 97.6% of the variance explained. Its 90% ranges caught 91.6% of the true cooling loads, close to target, and were too cautious on heating, at 96.1%. Public: the code, data, tests and CI.
- **[AI Study Buddy](https://github.com/jacobemanuel/ai-study-buddy)** · Course project, TUM<br>
  Platform for a user study that compares an AI text tutor with a speaking avatar tutor. I was technical and product lead in a five-person student team and built the platform end to end. Public: the case study and [the platform's code](https://github.com/jacobemanuel/ai-study-buddy/tree/main/platform), whose 54 tests run in CI.
- **[XR safety training for industry](https://github.com/jacobemanuel/xr-safety-training-framework)** · Research, Linde Engineering and Gdańsk University of Technology<br>
  Framework for designing VR safety training for industrial plants, grown out of my work on the Linde Virtual Academy at Linde Engineering. Eleven trainings I worked on are published in the [Meta Quest store](https://www.meta.com/experiences/profile/9101055249993942/). At ACHEMA 2024 in Frankfurt I presented one of the trainings to Saudi Arabia's Deputy Minister of Industry and Mineral Resources. It won the faculty's award for the best master's thesis of 2024.

## Tools

- **Languages:** Python, C#, Swift
- **XR and 3D:** Unity, OpenXR, Meta Quest, RealityKit, PolySpatial, SwiftUI, Metal, Blender, Unity Asset Transformer (Pixyz)
- **Machine learning:** PyTorch, NumPy, scikit-learn
- **GPU and cloud:** OpenSplat (CUDA, LibTorch), Google Cloud

## About

I study Management & Technology at TUM with Computer Engineering as my technology specialization. Before that I did an M.Sc. in Management at Gdańsk University of Technology and got the [faculty's award for the best master's thesis of 2024](https://majewski.studio/assets/award-2024.pdf). I'm also Head of Strategic Development at [TUM-XR](https://tum-xr.com/), the university's student XR initiative, and a Senior Associate at [XR Association Munich e.V.](https://www.linkedin.com/company/xrmunich/)
