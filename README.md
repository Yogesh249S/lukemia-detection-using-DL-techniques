## DATA SOURCE 📊
dataset (https://www.kaggle.com/datasets/avk256/cnmc-leukemia) 

## Credits 💳
This project is heavily inspired from **[this GitHub repository](https://github.com/fbaldi6/Lymphoblasts-Image-Classification/blob/main/README.md?plain=1)**


## Introduction
Acute Lymphoblastic Leukemia (ALL) is a fast-growing cancer of the blood and bone marrow, characterized by the development of many immature lymphocytes called lymphoblasts. It is the most common type of leukemia in children, particularly those between the ages of two and five, and the most common cause of death from pediatric cancers. Treatment depends on the type of ALL, age at diagnosis, and other factors. 

In recent years, the advent of convolutional neural networks has enabled to achieve excellent results in many image classification problems, including those in the field of medical imaging. With regard to the classification of leukemic B-lymphoblast cells, however, the task is challenging even when leveraging such technologies. Indeed, the visual similarity between abnormal and normal cells on the one hand, and the great diversity between cells from different subjects on the other hand, makes it particularly difficult to distinguish the two. For this reason, the ISBI Challenge 2019 was presented and, even after its completion, many researchers continue to study the problem.

## Results
In this work we tested both from scratch and pre-trained networks for the classification of malignant lymphoblasts cells. Then we proposed an ensemble solution able to combine the classification power of the best networks, optimizing the weights with a genetic algorithm. The results obtained are encouraging and show that it is possible to correctly classify almost all malignant cells, with a precision of 95.6% and a recall of 94.5%. Overall, our ensemble achieves an F1 weighted score of the 95.17%. 

There is still room for improvement, such as the use of hyperparameter optimization to further optimize our networks, which again for computational reasons was not possible. Finally, it would also be interesting to work directly on the raw images, while in the competition dataset they were already preprocessed.
