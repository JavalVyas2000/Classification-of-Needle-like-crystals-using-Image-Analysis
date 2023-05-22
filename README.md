# Classification-of-Needle-like-crystals-using-Image-Analysis

An image analysis method is studied and applied for determination of particle agglomeration for monitoring crystallization process. OpenCV, is used for image pre-processing and then the features extracted from them are used to identify and quantify primary crystals and agglomerates. The preprocessing included using the gaussian blur and then canny edge detection algorithm was used to get the boundaries of the particles. 

The contours are calculated using the openCV functionalities and then based on the parameters of convexity, concavity and circularity the classification was done. 

The initial test was done on about 80 particles of which 78 were found to be correctly classified with and error of less than 3%. This numbers might have to be varied based on the system setup and new thresholds are to be used. 

Pure Particle 

<img width="322" alt="image" src="https://github.com/JavalVyas2000/Classification-of-Needle-like-crystals-using-Image-Analysis/assets/73403218/18184cbb-fe6e-4f38-9b86-21ac901ec815">
<img width="216" alt="image" src="https://github.com/JavalVyas2000/Classification-of-Needle-like-crystals-using-Image-Analysis/assets/73403218/a072b618-fb30-4eeb-a2e1-d07a512023be">


Agglomerate Crystal 

<img width="338" alt="image" src="https://github.com/JavalVyas2000/Classification-of-Needle-like-crystals-using-Image-Analysis/assets/73403218/01a3082e-80d0-4a36-a473-8e7afb1cf549">
<img width="205" alt="image" src="https://github.com/JavalVyas2000/Classification-of-Needle-like-crystals-using-Image-Analysis/assets/73403218/c0c09e94-cde5-4840-84e3-29886da7e580">

Mixture sample

<img width="483" alt="Screenshot 2023-05-21 222548" src="https://github.com/JavalVyas2000/Classification-of-Needle-like-crystals-using-Image-Analysis/assets/73403218/8619b9fb-45f5-45f0-a1ec-940d7c2fdd95">
