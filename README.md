# AI-vs.-Cryptography

---
## "AI vs. Cryptography" is a fun research oriented project combining Cryptography, Deep Learning and Known-Plaintext Attack

---
Author: Christeen T Jose 

[LICENSE](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/LICENSE)

Source Codes Used: Not Released

---
## Results and Updates: 

---
### Caesar Cipher/ Shift Cipher:
#### Model used: Shallow Neural Network
All models have 1 input layer, 1 hidden layer and 1 output layer
The input and output layers have 26 units each.
3 different shallow neural networks were considered,depending on the number of units in hidden layer:
  * Model 1: Hidden layer with **13 units**
    * Number of trainable parameters: 1,417
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 757
      * Loss: 6.6227e-08 
      * Accuracy: 1.0000 
      * Validation loss: 1.3039e-07 
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A1.1%20-%20Caesar%20Cipher%20-%2013%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L1.1%20-%20Caesar%20Cipher%20-%2013%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 2.8312175004430173e-07
    
  * Model 2: Hidden layer with **26 units**
    * Number of trainable parameters: 2,106
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 492
      * Loss: 6.7469e-08 
      * Accuracy: 1.0000 
      * Validation loss: 7.8231e-08
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A1.3%20-%20Caesar%20Cipher%20-%2039%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L1.3%20-%20Caesar%20Cipher%20-%2039%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 1.0281799944777958e-07
  
  * Model 3: Hidden layer with **39 units**
    * Number of trainable parameters: 2,795
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 465
      * Loss: 3.2286e-08 
      * Accuracy: 1.0000 
      * Validation loss: 2.2352e-08
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A1.1%20-%20Caesar%20Cipher%20-%2013%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L1.1%20-%20Caesar%20Cipher%20-%2013%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 2.831220413668234e-08

---
### ROT13 Cipher:
#### Model used: Shallow Neural Network
All models have 1 input layer, 1 hidden layer and 1 output layer
The input and output layers have 26 units each.
3 different shallow neural networks were considered,depending on the number of units in hidden layer:
  * Model 1: Hidden layer with **13 units**
    * Number of trainable parameters: 1,417
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 620
      * Loss: 6.2088e-08 
      * Accuracy: 1.0000 
      * Validation loss: 5.9605e-08 
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A2.1%20-%20ROT13%20-%2013%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L2.1%20-%20ROT13%20-%2013%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 5.811452297166397e-08
    
  * Model 2: Hidden layer with **26 units**
    * Number of trainable parameters: 2,106
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 592
      * Loss: 4.0150e-08
      * Accuracy: 1.0000 
      * Validation loss: 1.2293e-07
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A2.2%20-%20ROT13%20-%2026%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L2.2%20-%20ROT13%20-%2026%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 1.9371508841459217e-08
  
  * Model 3: Hidden layer with **39 units**
    * Number of trainable parameters: 2,795
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 455
      * Loss: 2.4835e-08 
      * Accuracy: 1.0000 
      * Validation loss: 4.0978e-08
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A2.3%20-%20ROT13%20-%2039%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L2.3%20-%20ROT13%20-%2039%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 4.6193594727128584e-08

---
### Simple Substitution Cipher:
#### Model used: Shallow Neural Network
All models have 1 input layer, 1 hidden layer and 1 output layer
The input and output layers have 26 units each.
3 different shallow neural networks were considered,depending on the number of units in hidden layer:
  * Model 1: Hidden layer with **13 units**
    * Number of trainable parameters: 1,417
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 682
      * Loss: 8.6096e-08
      * Accuracy: 1.0000 
      * Validation loss: 1.2293e-07
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A3.1%20-%20SS%20-%2013%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L3.1%20-%20SS%20-%2013%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 1.415610029198433e-07
    
  * Model 2: Hidden layer with **26 units**
    * Number of trainable parameters: 2,106
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 510
      * Loss: 4.5945e-08
      * Accuracy: 1.0000 
      * Validation loss: 5.5879e-08
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A3.2%20-%20SS%20-%2026%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L3.2%20-%20SS%20-%2026%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 5.5134290022351706e-08
  
  * Model 3: Hidden layer with **39 units**
    * Number of trainable parameters: 2,795
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 434
      * Loss: 5.3396e-08 
      * Accuracy: 1.0000 
      * Validation loss: 8.1956e-08
      * Validation accuracy: 1.0000
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A3.3%20-%20SS%20-%2039%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L3.3%20-%20SS%20-%2039%20units.png)
    * Testing:
      * Test Accuracy: 1.0
      * Test Loss: 7.599591356211022e-08

---
### Caesar Cipher (Protected Version):
#### Model used: Shallow Neural Network
All models have 1 input layer, 1 hidden layer and 1 output layer
The input and output layers have 26 units each.
3 different shallow neural networks were considered,depending on the number of units in hidden layer:
  * Model 1: Hidden layer with **13 units**
    * Number of trainable parameters: 1,417
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 11
      * Loss: 3.2463 
      * Accuracy: 0.0417
      * Validation loss: 3.2337
      * Validation accuracy: 0.0625
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A4.1%20-%20Variable%20Key%20CC%20-%2013%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L4.1%20-%20Variable%20Key%20CC%20-%2013%20units.png)
    * Testing:
      * Test Accuracy: 0.03750000149011612
      * Test Loss: 3.242751359939575
    
  * Model 2: Hidden layer with **26 units**
    * Number of trainable parameters: 2,106
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 188
      * Loss: 3.0052
      * Accuracy: 0.1493
      * Validation loss: 3.1804
      * Validation accuracy: 0.0312
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A4.2%20-%20Variable%20Key%20CC%20-%2026%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L4.2%20-%20Variable%20Key%20CC%20-%2026%20units.png)
    * Testing:
      * Test Accuracy: 0.0625
      * Test Loss: 3.323150157928467
  
  * Model 3: Hidden layer with **39 units**
    * Number of trainable parameters: 2,795
    * Number of Non-trainable parameters: 0
    * Training:
      * Number of epochs till convergence of validation loss: 27
      * Loss: 3.2304
      * Accuracy:  0.0903
      * Validation loss: 3.2886
      * Validation accuracy: 0.0000e+00
      * Learning Curves:
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/A4.3%20-%20Variable%20Key%20CC%20-%2039%20units.png)
        * ![](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/Learning%20Curves/L4.3%20-%20Variable%20Key%20CC%20-%2039%20units.png)
    * Testing:
      * Test Accuracy: 0.03750000149011612
      * Test Loss: 3.285165309906006

---
