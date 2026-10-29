# Jakub Majewski

I'm a software engineer in Munich with a background in Management & Technology. I build software end to end: XR apps, real-time 3D from engineering CAD, machine learning, and knowledge tools for teams that use AI agents. At TUM I research Gaussian Splatting for real-time 3D on standalone headsets, together with [Qing Cheng](https://cvg.cit.tum.de/members/cheq) and supervised at [Prof. Daniel Cremers' Chair of Computer Vision and Artificial Intelligence](https://cvg.cit.tum.de/members/cremers).

**[majewski.studio](https://majewski.studio)** · [LinkedIn](https://www.linkedin.com/in/majewski-studio) · [contact@majewski.studio](mailto:contact@majewski.studio)

## Selected work

- **[Gaussian Splatting on Apple Vision Pro](https://github.com/jacobemanuel/gaussian-splatting-vision-pro)** · Research, TUM<br>
  Test bench that turns CAD models into Gaussian splats and measures them on a standalone headset: how close each trained model stays to the CAD original and what it costs to render. Each CAD model is rendered from 150 viewpoints spread evenly over a Fibonacci sphere. 470 splat models of five CAD models trained with OpenSplat on cloud GPUs, and 545,903 frames measured on the headset. Every number can be rebuilt from the raw records, which stay private for now. Public: the case study and [an open pull request to MetalSplatter](https://github.com/scier/MetalSplatter/pull/73).
- **[Large-scale Gaussian Splatting](https://github.com/jacobemanuel/large-scale-gaussian-splatting)** · Research, TUM-XR<br>
  Large Gaussian splat scenes on a standalone headset. The goal is an app that takes any finished splat scene, analyses it on the device and builds the level of detail it needs, so even a whole town stays smooth to move through. I test it on three large outdoor scenes I captured with TUM-XR: the Bismarck Tower near Lake Starnberg, the Alpine town of Leukerbad and the Technical University of Munich, processed in LCC Studio into 44.5, 23.3 and 24.1 million splats. Public: the three scenes on SuperSplat ([Bismarck Tower](https://superspl.at/scene/77398c1a), [Leukerbad](https://superspl.at/scene/5fceed98), [Technical University of Munich](https://superspl.at/scene/193ca7e8)) and the case study with the clips.
- **[receptionOS Visualizer](https://github.com/jacobemanuel/receptionos-visualizer-portfolio)** · Industry, client project<br>
  XR app for dental clinics that puts a patient's face scan, jaw scans and CBCT into one 3D scene at true scale: grab any part, see through layers or cut them open, correct the colour and measure on the scan surface, all on the headset and offline. I took it from an early proof of concept to the client release on my own. Public: the case study and [a code sample with seven tests](https://github.com/jacobemanuel/receptionos-visualizer-portfolio/tree/main/code/scene-lifecycle).
- **[Automotive XR](https://github.com/jacobemanuel/automotive-spatial-visualization-portfolio)** · Industry, in-house application<br>
  App for full-scale vehicle design reviews on a headset, in mixed reality on a physical seating buck (a mock-up with real seats and a real steering wheel) or in 360° environments. Since October 2025 I have developed it with a colleague, on requirements from my team lead, who owns the product. As technical lead I proposed the next architecture, which an external development partner is now building under my technical oversight.
- **[Automotive content pipeline](https://github.com/jacobemanuel/automotive-content-pipeline-portfolio)** · Industry<br>
  Workflow and tools that take car interiors from engineering CAD to the headset app. I took over the team's Blender add-on and have released eight versions of it: hierarchy and naming, decimation, normals and UVs in a few clicks, so a designer hands over a build that works in the app. Trim is fitted from reference photos with an AI agent laying out the UVs, in millimetres: quilting and stitching keep their real size while the seats lose about 70% of their triangles.
- **[LEKS](https://github.com/jacobemanuel/leks)** · Tooling, version 2.0<br>
  Local knowledge system for a long-running engineering project, read by people in Obsidian and queried by AI coding agents over MCP. In a scaling test with 10,027 pages, 91 of them real, 95% of searches finish within 68 ms. A hybrid search with a small local embedding model is in testing. Public: the case study and [the engine's code with 124 tests](https://github.com/jacobemanuel/leks/tree/main/engine).
- **[Probabilistic building energy prediction](https://github.com/jacobemanuel/building-energy-gpr)** · Course project, TUM<br>
  Heating and cooling load prediction for building designs, with a checked uncertainty range for each prediction. I compared three standard models on the same held-out splits and no single model won: the random forest was best on heating load, the Gaussian process on cooling load, with 97.6% of the variance explained. Its 90% ranges caught 91.6% of the true cooling loads, close to target, and were too cautious on heating, at 96.1%. Public: the code, data, tests and CI.
- **[AI Study Buddy](https://github.com/jacobemanuel/ai-study-buddy)** · Course project, TUM<br>
  Platform for a user study that compares an AI text tutor with a speaking avatar tutor. I was technical and product lead in a five-person student team and built the platform end to end. Public: the case study and [the platform's code](https://github.com/jacobemanuel/ai-study-buddy/tree/main/platform), whose 54 tests run in CI.
- **[XR safety training for industry](https://github.com/jacobemanuel/xr-safety-training-framework)** · Research, Linde Engineering and Gdańsk University of Technology<br>
  VR safety training and design reviews for industrial plants at Linde Engineering, where I produced content from storyboards to VR-ready CAD models, and a research framework for designing such training that grew out of it. Eleven trainings I worked on are published in the [Meta Quest store](https://www.meta.com/experiences/profile/9101055249993942/). At ACHEMA 2024 in Frankfurt I presented one of the trainings to Saudi Arabia's Deputy Minister of Industry and Mineral Resources. It won the faculty's award for the best master's thesis of 2024.

## Tools

- **Languages:** Python, C#, Swift
- **XR and 3D:** Unity, OpenXR, RealityKit, PolySpatial, SwiftUI, Metal, Blender, Unity Asset Transformer (Pixyz)
- **Machine learning:** PyTorch, NumPy, scikit-learn
- **GPU and cloud:** OpenSplat (CUDA, LibTorch), Google Cloud

## About

I study Management & Technology at TUM with Computer Engineering as my technology specialization. Before that I did an M.Sc. in Management, specialising in Quality and Innovation Projects Management, at Gdańsk University of Technology and got the [faculty's award for the best master's thesis of 2024](https://majewski.studio/assets/award-2024.pdf). I'm also Head of Strategic Development at [TUM-XR](https://tum-xr.com/), the university's student XR initiative, and a Senior Associate at [XR Association Munich e.V.](https://www.linkedin.com/company/xrmunich/)
