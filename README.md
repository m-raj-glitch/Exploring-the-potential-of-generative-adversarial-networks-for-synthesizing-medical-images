# Problem
In a developing Nation like India Medical Image samples are often less in number than required for various research and clinical studies.
Small data sets are major obstacles, in particular for supervised machine learning. To overcome this hurdle, some efforts have turned to the augmentation of existing data.

# gan
![image](https://user-images.githubusercontent.com/62300368/179840552-29a46759-8218-472f-963f-ef0c8bebc382.png)

A normal ML has only one Neural Network .But Gans consist of two neural networks

1.	GENERATOR
 Model that is used to generate new plausible examples from the problem domain.

2.	DISCRIMINATOR
 Model that is used to classify examples as real (from the domain) or fake (generated).


Trainig a gan on Brain MRI dataset
Input:
![nonDem40 jpg_resized](https://user-images.githubusercontent.com/62300368/179840894-6ca0e88d-a94b-4177-9496-b41d3a142f6c.jpg)
![mildDem700 jpg_resized](https://user-images.githubusercontent.com/62300368/179840954-de5afc8e-7204-44dc-a419-698d8873bae2.jpg)

Output:
![testing_18](https://user-images.githubusercontent.com/62300368/179840991-459de772-af78-4b52-ada5-e403a7828dba.png)
![testing_56](https://user-images.githubusercontent.com/62300368/179841015-61b6a1fb-8315-40ce-ba8e-ebd9619b6f73.png)


Advantages
1.	Cross modality image synthesis and image fusion.
images from CT, PET, and MR images differ from each other in terms of complexity and dimensionality to incorporate modalityspecific information which ultimately assists in better diagnosis. However, these diversities create a major constrain when it comes to cross-modality image synthesis. For instance, hybrid imaging involves simultaneous imaging from two modalities like MRI/PET, CT/PET imaging. The extraction of information of one modality from the hybrid images is usually a tough exercise.
2.	Reduced radiation dose with minimal loss of image quality in radiation dependent imaging modalities.
3.	Overall Cost effectivity
