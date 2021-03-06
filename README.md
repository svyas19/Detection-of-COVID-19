# Detection-of-COVID-19

## A Multi-Model Neural Network Classification</br>
### Classifier 1: Classification of Chest CT - Scan</br>
### Classifier 2: Classification of Chest X-Ray </br>

## 1. Introduction</br></br>


Covid-19 is also termed as “Coronavirus(CoV).” It is a novel virus that was not identified in humans before 2020. Cov is the large family of SARS-Cov,  and it is seen to be transmitted from animals to humans. This virus causes illnesses such as common cold, respiratory problems, etc. The outbreak of this virus has resulted in a pandemic; it has affected 37.1 million people and has caused 1.07 Million fatalities worldwide till date.</br></br>

## 2. Why detection from Chest Radiography?</br>

To provide Immediate results.</br>
Currently, the Reverse transcription-polymerase chain reaction(RT PCR) test is taking 2-3 hours for the results.</br>
Extend of spread can be detected from chest radiography.</br>

## 3. Overview
![Project Description](https://github.com/svyas19/Detection-of-COVID-19/blob/main/Report_Covid-19%20Detection%20(1).jpg)</br>


## 4. Dataset for CT Scans
![CT Scan](https://github.com/svyas19/Detection-of-COVID-19/blob/main/CT-Scan.png)</br>

## 5. Dataset for X-Ray
![X-Ray](https://github.com/svyas19/Detection-of-COVID-19/blob/main/X-Ray.png)</br>

## 6. Final Model Results </br>

Architecture : [(75x75X3), 512, 256, 128, 64, 2]</br>
Activation Function : ReLU</br>
Loss Function: Sum-of-Squares</br>
Weight Initialization: Glorot</br>
Momentum: 0</br>
Learning Rate :  0.01</br>
Regularization: L1 Regularization , L 1 = 0.01, L2 =0</br>

![Evaluation Results](https://github.com/svyas19/Detection-of-COVID-19/blob/main/Evaluation%20Results.png)</br>


