
## Project Description

The artifact chosen for this milestone is essentially an OpenGL model viewer. It was created in December of 2020 as part of CS-330, a course on computer 3D graphics programming. It is included in my ePortfolio partly because game programming is a focus of mine both as a hobby and as a potential career path, and therefore it is a project which is of interest to me and relevant to my future goals. 


## Skills demonstrated, improvements made

I believe the improved artifact showcases my skills in reworking and expanding a simple project into something more modular and reusable. They also showcase my skills of working with data formats, including defining, writing, and reading arbitrary custom binary data formats, such as the one used to store vertex, normal, and UV data. The improvements as of current include moving a slew of global variables into being part of class definitions which have been moved to separate files, better organizing the code for reuse and readability, as well as moving vertex data from being defined as part of the source code to being loaded from a file. 

Originally, I had planned to include a moving player-style camera, with potentially collision, as well as a room environment. These have not been completed in time for Milestone Two but are still part of the plan for this artifact. Code structure, organization, and readability concerns took higher priority over these specific functional enhancements. As such, I did not quite meet the course objectives I planned to meet, however I plan on rectifying this moving forward. 


## Skills learned and expanded

Regarding the process of enhancing the artifact, I learned quite a bit about how to declare and define classes using headers and separate cpp files in the process of enhancing this project. I had some experience doing similar things before in other languages such as Python, but it was my first time trying to move a monolithic C++ project to be something more modular, and much was learned in this process. I also learned about the use of lambdas as a way to use a class method in place of a function pointer in callbacks, and learned about lambdas in C++ and how they function in general. Finally, I learned about how to save and load 32-bit floating point data in a consistent binary fashion to a flatfile, as well as how to migrate a MinGW project to Visual Studio and, in the process, how to properly set up a .gitignore for Visual Studio and how to install the correct NuGet packages necessary for this project.

## [Link](https://github.com/Dizzy611/SNHUGLCapstone)

