# 11015310_Thesis


Stroke Lesion & Brain tumor detection with U-Net 2D

**Steps Invloved:**

1. Two different datasets were considerd, one for brain stroke lesion(ATLAS V.20) and other for brian tumor(BraTS).
2. Both the datasets were clubbed as one and used as single dataset.
3. Patients floder were shuffled before splitting train,test,validation data and resized iamge to 128*128.
4. Then passed images to model for trainig with 10 epochs.
