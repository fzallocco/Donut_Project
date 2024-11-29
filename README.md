# 3D Animations using Legacy and Web-based Technologies

## Project Description

To advance my understanding of low-level languages like C & C++, I decided to replicate 3D Animations projects available on YouTube. Due to the fact that native code is platform-dependent, I also added a platform-independent JavaScript/React version of the same program that ouputs the animation to your default web browser at the port `http://localhost:3000`.
In terms of execution and compiling speed, the C code is a much better option than the web app. However, it requires the user to have the latest gcc compiler version (I have 13.1.0), and some understanding of low level languages. More importantly, the C code may have undetectable performance differences across the latest hardware because of its simplicity. To ensure its viability across different operating systems, the C app needs to be compiled in all the mainstream operating systems that support the latest gcc compiler. This means that software incompatibility issues may arise if using outdated hardware or old version of the C compiler. For this reason, I included a web version of the same 3D animation that elminates the requirement of the gcc compiler specific to your OS, understanding of low-level languages, and expertise in troubleshooting errors in C/C++.

## Resources
There are several tutorial on YouTube that cover the spinning torus project in C/C++.
Lex Fridman's tutorial at `https://www.youtube.com/watch?v=DEqXNfs_HhY` delivers a brief overview of the project and the literature behind, including Andy Sloane's math explanation & JS code at `https://www.a1k0n.net/2011/07/20/donut-math.html`.
While I kept Lex Fridman's C code as is, I made minor changes to Andy Sloane's JS version to fit the app into a React project for better portability across mobile devices. Below are interesting resources covering how the C compiler performs Math calculations featured in the donut program.

Math library in C, stackoverflow: `https://stackoverflow.com/questions/2284860/how-does-c-compute-sin-and-other-math-functions`

Math libary in C, geeksforgeeks: `https://www.geeksforgeeks.org/sin-in-c/`

