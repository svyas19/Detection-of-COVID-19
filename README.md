# Detection-of-COVID-19

Objective </br>

The objective of this project is to determine whether a person is infected by Coronavirus or not. Chest Radiography is currently one of the crucial methods for the detection of COVID- 19 in patients. Chest radiography includes Chest CT- Scans and Chest X-Ray. The project should be able to detect Covid-19 from either Chest X-ray or Chest CT-Scan or both.</br></br>

Introduction</br></br>

COVID-19</br>

Covid-19 is also termed as “Coronavirus(CoV).” It is a novel virus that was not identified in humans before 2020. Cov is the large family of SARS-Cov,  and it is seen to be transmitted from animals to humans. This virus causes illnesses such as common cold, respiratory problems, etc. The outbreak of this virus has resulted in a pandemic; it has affected 37.1 million people and has caused 1.07 Million fatalities worldwide till date.</br></br>

Why detection from Chest Radiography?</br>

To provide Immediate results.</br>
Currently, the Reverse transcription-polymerase chain reaction(RT PCR) test is taking 2-3 hours for the results.</br>
Extend of spread can be detected from chest radiography.</br>

![Project Description](https://github.com/svyas19/Detection-of-COVID-19/blob/main/Report_Covid-19%20Detection%20(1).jpg)</br>


A Multi-Model Neural Network Classification</br>
Classifier 1: Classification of Chest CT - Scan</br>
Classifier 2: Classification of Chest X-Ray </br>

Classifier 1 - Chest CT Scans</br>

Dataset</br>  
Dataset Used: CT Scans for COVID - 19</br>

Details :
Label 1 - NiCT - Images with no information (5705 Images)</br>
Label 2 - niCT - Negative Covid-19 CT Scans (9979 Images)</br>
Label 3 - piCT - Positive Covid-19 CT Scans (4001 Images )</br>
This data set has some images of shape ( 512 x 512 ) and some of (1211 x 1211) pixels. </br>

Data Pre-Processing</br>
The Images from Label “NiCT” were removed as they had no information, which can  help in classification.</br>

1)  Resizing </br>
Original Image Size : 512 x 512 Pixels and 1211 x 1211 Pixels</br>
Converted Image Size  : 75 x 75 , </br>
Reason: Faster Execution, Reducing computational complexity, and time.</br>

2) Normalization</br>
Method 1 - Using normalize() function - It does standard normalization, μ=0 and σ=1</br>
Method 2 - Using MinMax Scaler () - In this approach, the data is scaled to a fixed range ,  usually 0 to 1</br>

Processed Dataset :</br>
The dataset was processed into two new labels :</br>
Label: ‘1’ → Negative COVID - 19 (9979 Images)</br>
Label: ‘2’ → Positive COVID - 19 (4001 Images)</br>
Images from both the labels are converted into shape (75,75,3)</br>
3 represents the Channel.</br>

