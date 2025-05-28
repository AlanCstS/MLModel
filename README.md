0 (~12,000)                           First               Second              Third
Learn ratio: default 0.001   -->  0.002         -->  0.0005        --> 0.002
Filtros: 16, 32, 64          -->  32, 64, 128   -->  16, 32, 64    --> 32, 64, 128
Dropout: 0.2                 -->  0.3           -->  0.3           --> 0.35
                                                                 Added Regularization L2 = 0.001 
                                                                           (Conv, Dense)

4th
0.0005        
32, 64, 128
0.3 (2)
0.002

5th (Reducción de imágenes ~7,500, 30 epochs)
0.00015
64, 128, 256, 128(new)
0.3 (2)
0.015

6th (40 epochs)
0.00015
64, 128, 256, 128(new)
0.3 (2)
0.03

7th (40 epochs) ACTUAL
0.00015
64, 128, 256, 128(new)
0.25 (2)
0.02

![image](https://github.com/user-attachments/assets/2799a9dd-430d-49d9-94ed-8a232675b247)

