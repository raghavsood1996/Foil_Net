# Foil_Net
The project aims at creating a Neural Network that can  predict lift coefficient of an airfoil within no time and requires user to have no specific knowledge of CFD Softwares to achieve the stated task. Adaptability of a Fully Connected Neural Network (FC) and a Convolutional Neural Network (CNN) are tested for learning underlying non-linearities of Navier-Stokes Equation. NACA 4-digit Airfoil profiles are obtained from UIUC airfoil database and lift data is generated using JavaFoil. Data Augmentation is done by choosing a range of Angle of Attack and Reynolds Number. The results for FC network are compared to CNN and is found that CNN can give more accurate predictions and can be easily scaled to profiles other than NACA 4-digit. 