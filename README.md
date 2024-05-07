# Data-Collection-Massive-Project-AAI-Collaboration
The dataset used in this project is a combination of two sources from Kaggle:
1. Data with six classes: trash, glass, plastic, organic, paper, and cardboard.
   - [Link to dataset](https://www.kaggle.com/datasets/asdasdasasdas/garbage-classification)
2. Additional data with twelve classes: battery, biological, white-glass, brown-glass, cardboard, clothes, green-glass, metal, paper, plastic, shoes, and trash.
   - [Link to dataset](https://www.kaggle.com/datasets/mostafaabla/garbage-classification)
3. Final dataset after pre-processing
   - [Link to dataset](https://drive.google.com/drive/folders/1p_URIjIpd7PQY3v7YpOt_po4e3Wepzdf?usp=sharing)

## Dataset Preparation
The dataset was preprocessed by removing the "trash" class to avoid interference. Additionally, some classes were relabeled and balanced to ensure equal representation. The final dataset includes six classes: metal, glass, organic, paper, battery, and plastic.

## Model Architecture
Three pre-trained deep learning architectures were employed:
- VGG16
- VGG19
- ResNet50

## Data Preprocessing
Images were preprocessed according to the requirements of each model, such as resizing to 224x224 pixels and applying specific preprocessing functions.
