### NEU - CLS STEEL DEFECT DETECTION
- This dataset contains 6 different classes of steel surface defects, which are `Crazing`, `Inclusion`, `Scratches`, `Patches`, `Pitted Surface` and `Rolled in Scale`.
<br>
#### Steps
- Applied pre-processing techniques like `histogram equalization` and global and local thresholding techqniues to refine gray scale images which were dependent on classtype.
- Pre-trained **EfficientNet** was used to extract features of an image.
- Extracted features were applied supervised algorithm withh target labels with 100% prediction accuracy.

#### Surprisingly the models were giving above 95% accuracy even when 70-80% data was taken as a test, I guess the classes didnt have not so similar features which simplified the classification.
### Here are the results of pre-processing steps.

![image](https://github.com/user-attachments/assets/6d426bba-331d-4705-97d1-6daa06a025c0)
![image](https://github.com/user-attachments/assets/90dbbebd-380b-4eef-9bb6-677b0ebf74c7)

