# Kutsu
FYI: Kutsu is the Japanese term for shoes/footwear 😃

**TL;DR: Utilizing CNN (VGG16 model - transfer learning) to perform multiclass image classification on popular shoe brands.**

## Motivation:

- As a long time sneakerhead, I've always been interested in the different brands of shoes and their respective styles. I truly believe that a good pair of kicks can make or break an outfit! 

- Pairing this interest with my drive to learn more about machine learning, I decided to create a model that can classify images of shoes into their respective brands.

## Repository Architecture:

- Currently, I plan on using the following architecture for this project:
    - `data/` - contains the training and testing data (data retrieved from: [here](https://www.kaggle.com/datasets/die9origephit/nike-adidas-and-converse-imaged))

        - `train/` - contains the training data
        - `test/` - contains the validation data
    
    - `notebooks/` - contains the Jupyter notebook
    - `README.md` - contains the project description

## Current Approach:

- The VGG16 model is a CNN that was trained on the ImageNet dataset. The model is able to classify images into 1000 different classes. I plan on using this model to perform transfer learning on my own training set.

    - As we know, the early layers of a CNN mainly train on features such as colours, edges, borders, meaning that these characteristics are transferable (hence we use transfer learning from the VGG16 model).

Will continue to update this README as the project progresses! 👨‍💻
