# AI-Breaks-Cryptography

---
## "AI Breaks Cryptography" is a research oriented project where i try to break various Cryptography algorithms using Deep Learning and Known-Plaintext Attack

---
Author: Christeen T Jose 

[LICENSE](https://github.com/ChristeenTJose/AI-Breaks-Cryptography/blob/master/LICENSE)

Source Codes Used: Not Released

---
## Results and Updates: 
### Caesar Cipher:
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
  
  * Modle 3: Hidden layer with **39 units**

