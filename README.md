<!-- ======================= HEADER ======================= -->
<img src="./assets/header.gif" width="100%" alt="Jaz Winn — Software Engineer • Engines • Graphics • AI" />

<div align="center">

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&duration=3000&pause=800&color=24C6DC&center=true&vCenter=true&width=720&lines=Building+a+real-time+C%2B%2B20+3D+engine+%F0%9F%8E%AE;Writing+LLM+inference+in+C%2B%2B20+%2B+CUDA+%E2%9A%A1;Real-time+computer+vision+with+YOLO+%26+SAM+%F0%9F%93%B7;Rendering%2C+ECS%2C+reflection%2C+physics+%F0%9F%A7%A9;Always+shipping%2C+always+learning+%F0%9F%9A%80" alt="Typing intro" />
</a>

<br/>

<a href="https://jazwinn.github.io/Jaz-Portfolio/"><img src="https://img.shields.io/badge/Portfolio-24C6DC?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
<a href="https://www.linkedin.com/in/jazwinn-ng/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://mail.google.com/mail/?view=cm&to=ngjazwinn@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.instagram.com/jaz_winn/"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>

</div>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider" />

## <img src="https://raw.githubusercontent.com/MartinHeinz/MartinHeinz/master/wave.gif" width="30" alt="wave" /> About Me

```cpp
struct JazWinn {
    std::string role      = "Software Engineer";
    std::string builds    = "high-performance systems";

    std::vector<std::string> shipped = {
        "real-time C++20 3D engine (ECS, reflection, PhysX)",
        "LLM inference engine (C++20 + CUDA)",
        "real-time computer vision pipelines",
    };

    std::vector<std::string> exploring = {
        "LLMs", "Computer Vision", "Machine Learning"
    };

    std::vector<std::string> offline = {
        "running 🏃", "gym 💪", "making games 👾"
    };
};
```

- 🎮 I build **engines from the ground up** — renderers, Entity Component Systems, compile-time reflection, asset pipelines
- ⚡ I write **inference code with no ML frameworks** — tokenizer to KV cache to CUDA kernels
- 📷 I ship **computer vision tools** that run in real time on a single consumer GPU
- 💬 Open to **software engineering, graphics, and AI/ML roles** — [let's talk](https://www.linkedin.com/in/jazwinn-ng/)

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider" />

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 [InferenceEngine](https://github.com/jazwinn/InferenceEngine)
Transformer inference engine written **from scratch in C++20** with zero ML dependencies. Loads Hugging Face `.safetensors`, runs its own tokenizer and chat templates, and generates on CPU or through a **custom CUDA backend**. Chats with **Llama 3.2 1B** end to end.

![C++](https://img.shields.io/badge/C++20-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![CUDA](https://img.shields.io/badge/CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![LLM](https://img.shields.io/badge/LLM-302b63?style=flat-square)

</td>
<td width="50%" valign="top">

### 🎮 [KosEngine 2.0](https://github.com/jazwinn/Kos-Engine-2.0)
Modular, high-performance **real-time C++20 3D engine**. **ECS architecture**, **compile-time reflection**, C++ scripting, **PhysX** physics, an asset system, and automated testing with GoogleTest in CI.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![OpenGL](https://img.shields.io/badge/OpenGL-5586A4?style=flat-square&logo=opengl&logoColor=white)
![CMake](https://img.shields.io/badge/CMake-064F8C?style=flat-square&logo=cmake&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎯 [OneShotSeg](https://github.com/jazwinn/OneShotSeg)
Segment and track **any object from a single drawn box** — no training data, no labels, no fine-tuning. FastSAM + OSNet Re-ID tracking, **real time on one consumer GPU**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</td>
<td width="50%" valign="top">

### 🔀 [AdaptiveVisionPipeline](https://github.com/jazwinn/AdaptiveVisionPipeline)
Object detection that **watches its own performance** — a meta-controller reads motion, blur, lighting and confidence signals and **switches detection pipelines in real time**.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO-111F68?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🏷️ [Groundwork](https://github.com/jazwinn/Groundwork)
Label datasets and **train CV models from the browser**, fully local. Uses **SAM 3** for zero-shot auto-labelling and **Ultralytics YOLO** for training, export and ONNX conversion.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/Ultralytics-111F68?style=flat-square)
![ONNX](https://img.shields.io/badge/ONNX-005CED?style=flat-square&logo=onnx&logoColor=white)

</td>
<td width="50%" valign="top">

### 💪 [ELISS Push-Up Counter](https://github.com/jazwinn/OpenCV-ELISS-PushUpCounter)
Push-up assistant inspired by Singapore's **ELISS** machine — **YOLO pose estimation**, OpenCV, and custom biomechanics logic to judge every rep.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![YOLO](https://img.shields.io/badge/YOLO_Pose-111F68?style=flat-square)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)

</td>
</tr>
</table>

<details>
<summary><b>🗂️ More projects</b></summary>
<br/>

| Project | What it does | Stack |
|---|---|---|
| [Graphics-Engine](https://github.com/jazwinn/Graphics-Engine) | Ongoing graphics engine library | C++ · OpenGL |
| [BVH Spatial Data Structure](https://github.com/jazwinn/Spatial-Data-Structure-using-Bounding-Volume-Hierarchy-BVH-) | Faster 3D rendering with a Bounding Volume Hierarchy | C++ |
| [Kd-Tree Raytracing](https://github.com/jazwinn/Spatial-Data-Structure-using-Kd-Tree-for-Raytracing) | Accelerating a raytracer with a Kd-tree | C++ |
| [Procedural Cave Generation](https://github.com/jazwinn/Procedural-Cave-Generation) | Comparing procedural algorithms for cave systems | C++ |
| [OptimizedTransformerLayer](https://github.com/jazwinn/OptimizedTransformerLayer) | Transformer layer optimized for local hardware | Python |
| [Server-Client File Sharing](https://github.com/jazwinn/Server-Client-file-sharing) | TCP client/server with UDP file transfer | C++ |
| [React Stock Viewer](https://github.com/jazwinn/React-Web-Stock-Viewer) | Stock prices, news and AI summaries | React · Node · Tailwind |
| [Inventory Web App](https://github.com/jazwinn/Inventory-Web-Application) | Full-stack CRUD with a REST API | Java · Spring Boot · SQL |
| [RepoToTDD](https://github.com/jazwinn/RepoToTDD) | Generates a technical design doc from a repo | Python |

</details>

<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider" />

## 🛠️ Tech Stack

<div align="center">

<p align="center">
  <img src="https://skillicons.dev/icons?i=cpp,c,py,pytorch,opencv,cmake,git,docker,linux,visualstudio&perline=10" alt="C++, C, Python, PyTorch, OpenCV, CMake, Git, Docker, Linux, Visual Studio" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA" />
  <img src="https://img.shields.io/badge/OpenGL-5586A4?style=for-the-badge&logo=opengl&logoColor=white" alt="OpenGL" />
  <img src="https://img.shields.io/badge/Ultralytics_YOLO-111F68?style=for-the-badge" alt="Ultralytics YOLO" />
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face" />
</p>

</div>

<!-- GitHub Activity (hidden)
<img src="https://user-images.githubusercontent.com/74038190/212284100-561aa473-3905-4a80-b561-0d28506553ee.gif" width="100%" alt="divider" />

## 📊 GitHub Activity

<div align="center">

<img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=jazwinn&theme=tokyonight" width="100%" alt="Profile details" />

<img src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=jazwinn&theme=tokyonight" height="170" alt="Stats" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=jazwinn&theme=tokyonight" height="170" alt="Repos per language" />
<img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=jazwinn&theme=tokyonight" height="170" alt="Most commit language" />

<img src="https://streak-stats.demolab.com?user=jazwinn&theme=tokyonight&hide_border=true&border_radius=10" width="70%" alt="GitHub streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/jazwinn/jazwinn/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/jazwinn/jazwinn/output/github-snake.svg" />
  <img alt="Contribution snake animation" src="https://raw.githubusercontent.com/jazwinn/jazwinn/output/github-snake.svg" width="100%" />
</picture>

</div>
-->

<!-- ======================= FOOTER ======================= -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=0:24c6dc,50:302b63,100:0f0c29&height=120&section=footer" width="100%" alt="footer" />
