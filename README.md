# Handwritten-Myanmar-Consonants-Recognition

The project is a mini-thesis study for my Bachelor Degree. 
It was done in September, 2018.

### Project Description
Students can practice Myanmar consonants using this application. The system will provide a random voice command, and a student has to draw the consonant. The drawn image is saved and checked in the server (the Matlab program). Then, the result will be sent back and notified to the student. 

### Dataset (manually collected)
- 3300 words (100 words per consonant x 33 consonants)
- training = 2970 (90%), testing = 330 (10%)

### Applied Languages
- Matlab for classification, 
- Java (Android) for input query, 
- Firebase for storing input image (.jpg) and correct consonant (.txt)
- PHP for linking 

### Methodology
- Preprocessing: binarization, noise removal
- Segmentation: Projection
- Feature Extraction: Histogram of Oriented Gradients (HOGs)
- Classification: Back-propagation Neural Network (accuracy = 92.73%)
