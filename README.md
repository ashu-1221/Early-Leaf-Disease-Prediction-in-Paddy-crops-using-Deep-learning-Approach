# Early-Leaf-Disease-Prediction-in-Paddy-crops-using-Deep-learning-Approach
# Early Leaf Diseases Prediction in Paddy Crop using Deep Learning Model

## Introduction
At present, more than 50 % of the world’s population is dependent on rice for its survival. But there are various diseases that decrease the productivity of the paddy crop. The most affecting paddy leaf diseases are Brown spot, Hispa, & Rice blast. These illnesses restrict rice plants fromgrowing and producing as they should, which might result in significant economic and ecological losses. The harm to the crop and the losses to the farmers can both be significantly reduced if these diseases are quickly and accurately recognized at an early stage. So, In this project, we have considered four classes for the classification of the leaf category. We used deep learning techniques to detect the actual disease of affected plants. We implemented three architectures i,e. VGGNet16, RenNet101,&AlexNet. Out of these three, Alexnet has the highest Accuracy. The AlexNet model has achieved training & testing accuracy of 92.35% and 85.27% respectively in our dataset.


## Disease Description
1. **Rice blast (Pyricularia grisea)**:- It is caused by Magnaporthe oryzae fungus & is one the most common disease in rice plants which can be usually observed during the seedling stages.This disease is found in approximately more than 80 countries across the world. Its first occurrence was in China and was known as ”rice fever disease”. It can attack the various parts of the plant, which causes severe damage. It attacks the stem, collar, neck, or branches of the panicles. It is a major disease because of its destructive nature under favorable conditions .Also. It is capable of causing losses of up to 100%. An image showing paddy leaf affected by Rice blast is shown below.

![Leaf blast](https://github.com/user-attachments/assets/9a6af221-e7a7-4374-9520-e2006a875173)

2. ** Hispa** :- The lower epidermis of rice leaf blades is all that remains after rice Hispa scrapes the upper surface. It also burrows through the tissues of the leaves. Plants get weaker when damage is severe. The conditions that support the insect’s abundance include heavy rains, especially during the premonsoon or early monsoon periods, followed by abnormally little precipitation. Disease is shown in the following figure.

 ![Hispa 2](https://github.com/user-attachments/assets/79ee3049-49b3-4dda-ac55-d0eb069338d7)  ![Hispa 1](https://github.com/user-attachments/assets/adbd7c49-5693-4cfc-9f76-3260e4b22154)


3. **Brown Spot**:- It has brown, small, and circular lesions. Fully formed lesions have an oval or circular shape, a light brown to grey centre, and a reddish brown edge brought on by the poison the fungi generate. High relative humidity of (86–100%) and temperatures between 16 and 36 °C are conducive to developing this disease. It frequently occurs in soils that are neither wet nor nourished. Disease is shown below.
  ![Brown spot 2](https://github.com/user-attachments/assets/771977fc-1a0f-44f9-be18-3eb08fcc2b55)  ![Brown spot](https://github.com/user-attachments/assets/43c0315b-7a02-469a-ba14-a9bf72115d8c)

## Features
- **Disease Detection**: Identifies and classifies 4 paddy leaf diseases i,e. Rice Leaf Blast, Brown Spot, Hispa, Normal  .
- **Deep Learning Models**: Utilizes VGGNet16, ResNet101, and AlexNet for disease classification.
- **High Accuracy**: Achieved a training accuracy of 92.35% and a testing accuracy of 85.27% with the AlexNet model.



  




    



## Dataset
The dataset used for this project contains total 5447 images of paddy leaves affected by various diseases, categorized into the following classes:
- Brown Spot
- Hispa
- Rice Blast
- Normal

 the dataset is preprocessed and split into training and testing sets before using the scripts.

## Results
The AlexNet model achieved the highest accuracy among the tested architectures:
- **Training Accuracy**: 92.35%
- **Testing Accuracy**: 85.27%
- 


## Research Paper link-  
https://ieeexplore.ieee.org/document/10136038

@INPROCEEDINGS{10136038,
  author={Bajpai, Abhishek and Tiwari, Naveen Kumar and Tripathi, Ashutosh Kumar and Tripathi, Vibha and Katiyar, Devesh},
  booktitle={2023 2nd International Conference on Paradigm Shifts in Communications Embedded Systems, Machine Learning and Signal Processing (PCEMS)}, 
  title={Early leaf diseases prediction in Paddy crop using Deep learning model}, 
  year={2023},
  volume={},
  number={},
  pages={1-6},
  keywords={Deep learning;Training;Biological system modeling;Computational modeling;Crops;Computer architecture;Predictive models;Paddy leaf disease;Machine learning;Deep learning;VGGNet16;RenNet101;AlexNet},
  doi={10.1109/PCEMS58491.2023.10136038}}

