# CS-330 Portfolio: 3D Scene Project

## Project Overview
This repository contains my 3D scene project created for CS-330 Computational Graphics and Visualization. The project demonstrates skills in OpenGL, 3D modeling, texturing, lighting, and camera controls.

## Files Included
- **3D_Scene_YourName.zip**: Complete Visual Studio project with source code and executable
- **Design_Decisions_YourName.docx**: 2-page document explaining design choices

---

## Reflection

### How do I approach designing software?

My approach to designing software starts with understanding the requirements and breaking down the problem into smaller, manageable components. For this project, I began by analyzing the 2D image I needed to replicate and identifying the basic shapes that would make up each object. I planned the scene layout, considered which textures would enhance realism, and mapped out the lighting scheme before writing any code. This top-down approach helped me stay organized and ensured I met all the project requirements.

*What new design skills has your work on the project helped you to craft?*

Through this project, I developed several new design skills. I learned how to think in 3D space and break down complex objects into primitive shapes. I gained experience in texture mapping and understanding how UV coordinates work. I also developed a better understanding of lighting design - how different light types and positions can dramatically affect the mood and realism of a scene. The modular design of my code (separate classes for Camera, SceneManager, ShapeMeshes, etc.) taught me the importance of organizing code for reusability and maintainability.

*What design process did you follow for your project work?*

I followed an iterative design process that started with planning and progressed through multiple implementation phases. I first created the basic shapes without textures to ensure proper placement, then added textures, followed by lighting, and finally implemented camera controls. Each milestone built upon the previous one, allowing me to test and refine incrementally. I also incorporated feedback from instructors and peers to improve my design throughout the process.

*How could tactics from your design approach be applied in future work?*

The modular, iterative approach I used can be applied to any software development project. Breaking down complex problems into smaller, testable components is a universal software engineering principle. The practice of planning before coding, creating prototypes, and gathering feedback early is applicable to game development, web development, and even non-graphics programming. The skills I developed in thinking about user experience (camera controls, visual feedback) are transferable to any interactive application.

---

### How do I approach developing programs?

I approach program development by starting with a clear understanding of the problem, then writing clean, well-commented code that follows industry best practices. I use version control (Git) to track changes and regularly test my code to catch errors early. For this project, I wrote small functions that each did one thing well, making the code easier to debug and modify.

*What new development strategies did you use while working on your 3D scene?*

I learned to use shader programming for the first time, which required thinking about graphics at a low level. I used modern OpenGL (3.3+) with vertex and fragment shaders to control how objects are rendered. I also used the GLM library for matrix math, which was new to me. I learned to manage OpenGL resources like textures and vertex buffer objects properly to avoid memory leaks.

*How did iteration factor into your development?*

Iteration was crucial to my development process. Each milestone represented an iteration where I added new functionality or refined existing features. I frequently tested my code after small changes, which helped me catch issues early. For example, I tested each object with a simple color before adding textures, and tested each light individually before adding the second one. This iterative approach prevented me from having to debug massive changes all at once.

*How has your approach to developing code evolved throughout the milestones, which led you to the project's completion?*

My approach evolved from writing everything in one file to organizing code into logical classes and functions. Early milestones helped me establish the foundation, while later ones built upon it. I became more comfortable with OpenGL concepts and GLM math as I progressed. I also learned to better manage my time and plan ahead for upcoming milestones. By the end, I had developed a workflow that combines planning, implementation, testing, and refinement.

---

### How can computer science help me in reaching my goals?

Computer science provides the foundation for solving complex problems through logical thinking and systematic approaches. The skills I've developed in this course - 3D graphics, spatial reasoning, and interactive system design - directly support my career goals in game development and software engineering.

*How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future educational pathway?*

Computational graphics has given me a deeper understanding of linear algebra and matrix math, which is fundamental to many areas of computer science. I now understand how 3D objects are represented and transformed in digital space. This knowledge will support future coursework in areas like computer vision, machine learning (for image processing), and advanced graphics. The project-based learning approach has also reinforced the importance of hands-on practice in building technical skills.

*How do computational graphics and visualizations give you new knowledge and skills that can be applied in your future professional pathway?*

The skills I've developed are directly applicable to careers in game development, AR/VR, simulation, and data visualization. Understanding how to create interactive 3D worlds is valuable for anyone working in entertainment, education, healthcare (medical visualization), or architecture (building design). The problem-solving skills, attention to detail, and ability to work with complex systems are transferable to virtually any software development role. I can also apply these skills to create compelling data visualizations or interactive educational tools.
