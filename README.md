# RayTracer

This project was developed in just **6 days** at **ENSTA Paris** as part of the course **CSC_4IN04_TA**, in collaboration with my classmate [Yassine ZANNED](#).

## 🎯 Objective

Our goal was to implement a basic **ray tracing engine** from scratch, gradually adding features to render simple 3D scenes with realistic lighting.

## 🤔 Wait... In 6 days? Really?

Well... not exactly 😅

At first, we jumped in by copying code from a few YouTube tutorials — just to get a feel for how ray tracing works. That helped us get things moving, but we weren’t really learning *how* it all worked.

So we hit the reset button. We found a great tutorial that didn’t give away all the code, just the concepts — and it was broken down over 6 days. That became our new roadmap.

We then **re-implemented everything from scratch**, using that guide only as a high-level reference. It was intense, but we learned a ton.



## 🖼️ Features Implemented

- Ray-sphere intersection
- Camera positioning and viewing rays
- Basic Phong shading
- Light source handling and shadow casting
- Scene description hardcoded in code

## 🚀 Future Work

In the future, we aim to explore **parallel computing** techniques (e.g., multithreading or GPU acceleration) to **speed up image rendering**, especially for complex scenes or higher resolutions.

## 🛠️ How to Run

Make sure you have a C++ compiler. Compile and run one of the daily files like so:

```bash
g++ day6.cpp -o raytracer
./raytracer
