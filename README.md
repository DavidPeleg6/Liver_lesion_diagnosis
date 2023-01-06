# Sheba_Liver_Fat
Project with Sheba medical center on AI for Ultrasound Images for Liver Fat patients 
![198590231-6b1714d6-84ae-4e97-847f-c853599f2c5e](https://user-images.githubusercontent.com/26568166/211051446-6d90621a-db8b-42d2-84c6-a6edbda2e10e.png)



# Project Golas
1. Classify fibrosis stage F0-F4 according to the US images and additional data
  - Compare to the SWE method
  - Check if additional data increase the accuracy (more images, BMI, vital signs, blood tests etc.)
  - “Ground truth”: Biopsy 
  - Improve the accuracy in F1-F3
2. Give confidence level for the classification according to number of images used:
  - Check if more images increases the accuracy
  - Improve the accuracy in F1-F3
  - Tool to decide how many images to take
3. Can the images classify S levels?

# 2D-SWE ultrasound
  - 2D shear wave elastography is a technique embedded in ultrasound machines
  - It allows the interrogation of the tissue by acoustic radiation force impulses induced into the tissues by focused ultrasonic beams and captures the propagation of resulting shear waves in real time. 
  - Elasticity is displayed using a color-coded image superimposed on a B-mode image, and at the same time, a quantitative estimation of liver stiffness (LS) can be performed in a certain region of interest (ROI)
  - Multiple samples may increase the accuracy of the classification by examining more ROIs
![198589967-6564c4e5-5197-48f7-a6ec-2813eaafc447](https://user-images.githubusercontent.com/26568166/211051475-58826e5f-a261-4735-aa1f-818310e676fe.png)

 

![198590076-995cbeed-2bbd-41db-bddd-dba17fe67591](https://user-images.githubusercontent.com/26568166/211051494-ee264f20-e212-4004-b9a6-fe30f0186b9b.png)

