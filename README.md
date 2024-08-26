# Box-Segmentation
Project modifying persense to be used for the downstream task of  carton box instance segmentation.


Follow the instructions of original persense github for directory set-up.
https://github.com/Muhammad-Ibraheem-Siddiqui/PerSense?tab=readme-ov-file

In the project the weights of sam_vit_b are used  
https://dl.fbaipublicfiles.com/segment_anything/sam_vit_b_01ec64.pth


Images and masks in folder data/Images should have the same name example 00.jpg for mask and 00.png for image the names of the images on the test folder are irrelevant.







Example directory set-up for data folder : ![Στιγμιότυπο οθόνης 2024-08-26 222403](https://github.com/user-attachments/assets/bea73760-5aa9-4056-b1a8-a707acff9f94)



persense.py is the original code of persense not yet edited to reflect modifications.
The project was developed in google colab enviroment.
The requirements.txt file should cover  most important imports.

To run  notebook follow instructions of original persense repo  here I provide the requirements.txt needed and test data.
Notebook should be  located and  run from  withing Persense folder.



The paths used need changing.




Changes have been made in the requirements.txt  , this one should be used not the one of the original persense.



Example  prompt : ![01](https://github.com/user-attachments/assets/c38def35-dd9a-46f4-bce2-a2f2e50f9444)


Resulting masks : ![img7](https://github.com/user-attachments/assets/22f9ea10-6478-4da9-b5aa-1b031b2638f9)
![img4](https://github.com/user-attachments/assets/4fd2cf21-825b-49da-9a3e-b6961c973a33)
