# Comparative Performance Analysis of Rendering Optimization Methods in Unity Tuanjie Engine, Unity Global and Unreal Engine

# Abstract 
In the field of computer game development, Unity Technologies' game engine has a Chinese version called Tuanjie, developed by Unity China and officially released in January 2024. Tuanjie customizes with exclusive rendering optimization techniques such as a Nanite-like Virtual Geometry (VG) for geometric complexity optimization. While the VG system has garnered global attention, comprehensive performance comparisons with other Level of Detail (LOD) systems remain scarce. This study addresses this gap by constructing a benchmark scene with ten 3D mesh models (each containing 3 million polygons) to analyze the VG system's performance thoroughly. We conducted performance tests comparing the built-in LOD system of Unity Global, the VG of the Tuanjie engine and Nanite of Unreal Engine 5 (UE5). The data of GPU, CPU, and RAM usage along with FPS was collected and analyzed every 100 milliseconds over 4 minutes, yielding 2400 data points per engine. The comparative studies were conducted at five viewing distances (i.e. 0m, 100m, 200m, 300m, 400m) and with an empty scene. The results validate that UE5's Nanite system remains superior performance compared to both Tuanjie's VG and Unity Global's LOD systems. Moreover, Tuanjie's VG system outperforms Unity Global's LOD system in rendering distant objects while underperforming when rendering close objects. This comprehensive comparison highlights the strengths and weaknesses of each LOD system in our scenario. We hope the results can shed some light for researchers and game developers in the fields of game design and computer graphics development. 


### Authors:
- **[Muyi Bao](https://github.com/BaoBao0926/BaoBao0926.github.io)**, **Zeren Tao**, **Xiaohan Wang**, **Jiashuo Liu**, **Qilei Sun**


# Experimental Design
<img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/1.png" alt="ASP-VMUNet" width="800"/> 

# Implementation Details
<img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/2.1.png" alt="ASP-VMUNet" width="400"/>  <img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/2.2.png" alt="ASP-VMUNet" width="400"/> 

# Experimental Results
<img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/3.1.png" alt="ASP-VMUNet" width="800"/> 
<img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/3.2.png" alt="ASP-VMUNet" width="800"/> 
<img src="https://github.com/BaoBao0926/Comparative-Performance-Analysis-of-Rendering-Optimization-Method/blob/main/figure/3.3.png" alt="ASP-VMUNet" width="400"/> 
