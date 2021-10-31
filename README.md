# Dimensional-Expansion-of-X-Fields

Content:
- Interim Research Paper: Research paper based on experiments and results as of July. Final research paper will be available in January after the incorporation of Transformer Networks to the present model.
- Presentation: Slides for my presentation at Eleventh Annual Fall Term MIT PRIMES Conference from October 16-17, 2021.
- Code: The code used to produce the results.
- Render Videos: Some video results of image interpolation.

Abstract:
Generating images of the same scenes from different perspectives—whether that is from different points, from different angles, under varying illumination, or with other parameters—has a myriad of use cases, stretching from creating debug models to producing smooth videos. In the X-Fields model, hard-coded graphics tricks like lighting, 3D projection, and albedo are used to supplement neural networks in creating a differentiable map for the image parameters and the actual pixels using sample images and their corresponding coordinate values. Although X-Fields performs well on datasets of images concentrated on a 2D (x, y) plane relative to alternative interpolation methods, the original model cannot support broader use cases like the interpolation of images in different 3D (x, y, z) positions. After using the 3DB framework to generate 3D images and coordinates that we then pass through our dimensionally expanded version of the X-Fields model, we find that the new model can generate promising interpolation results with relatively sparse datasets and with large view angle changes; parameters such as learning rate, the bandwidth parameter in soft blending, and others have impact over the interpolation quality and construct trade-offs between training cost and interpolation quality; and that certain backgrounds (like the ocean) added to reference images can pose challenges for interpolation.
