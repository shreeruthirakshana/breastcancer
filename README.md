# breastcancer
The process of mapping images involves using a reference number along with a text file to associate each image with a specific identifier. 
The reference number acts as a key, allowing each image to be linked to a specific record in the text file.
 
 The text file includes following fields:
          1st column: MIAS database reference number.

          2nd column: Character of background tissue: 
                F - Fatty 
                G - Fatty-glandular
                D - Dense-glandular

          3rd column: Class of abnormality present:
                CALC - Calcification
                CIRC - Well-defined/circumscribed masses
                SPIC - Spiculated masses
                MISC - Other, ill-defined masses
                ARCH - Architectural distortion
                ASYM - Asymmetry
                NORM - Normal

          4th column: Severity of abnormality;
                B - Benign
                M - Malignant
                
          5th,6th columns: x,y image-coordinates of centre of abnormality.

          7th column: Approximate radius (in pixels) of a circle enclosing the abnormality.

The breast cancer detection works with mammographic images (all -mias dataset).
The model is built using two models:
             1)CNN(98.64%)
             2)LeNet(83.23%)
