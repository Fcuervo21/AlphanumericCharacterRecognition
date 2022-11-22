
# Alphanumeric Character Recognition ⚙︎

- LIS4042 Artificial Vision
- Professor: Zobeida Guzmán
- Autumn 2022 
- UDLAP

Final project for the subject of Artificial Vision to generate an automation system for the extraction of alphanumeric characters through photographs.


## Authors

- Fernando Cuervo Ledesma 165972
- Jonathan Valencia Tescucano 168013
- Daniel Laug Velázquez 167452


## Description of the content
For a better study of the system, the code was separated into various files with their appropriate documentation.

 - 📄 File A "ImagePreprocessing.mlx" shows the code for image preprocessing and enhancement.
 - 📄 In file B "CRAFTandOCR.mlx" is the code where the CRAFT method (Pretrained Neural Network) with OCR is found.
 - 📂 In the image folder there is a series of images to be used as a test within the code.
 
  - The order of execution consists of the following:
     - To perform the preprocessing of the images using the A file, remember to place the appropriate paths for reading and writing images.
     - In file B, place the output file of file A as an input to carry out the CRAFT - OCR process.

- Because .mlx files cannot be opened on Github, their content was placed in the PDF files with the same name which display their content with their documentation.

#### Bag of Visual Words Files
- This file includes a classification method called Bag Of Visual Words which performs a classification through training, to later compare the trained model with an input image and show the Output of the detected text as a result, however, this process is not functional due to because it only identifies an individual character in a photograph.
- This file was placed as evidence of a classification process, extensive improvements must be made for this method to work.

## 🛠 Requirements

- MATLAB account
- In case of using Matlab online, the execution of the code is done directly, it is only necessary to place the correct path of the images.

- In case you are using MATLAB locally on your computer, at the moment of executing the code errors of lack of libraries will appear, for this:
    -
        - Click on the required libraries in the terminal (generally they are artificial vision libraries).
        - Install them.
        - Run again.
        

## Distribution of tasks
![Captura de Pantalla 2022-11-22 a la(s) 2 56 45](https://user-images.githubusercontent.com/63762598/203270144-700087e5-5add-476c-bd91-480e6b2f3797.png)




