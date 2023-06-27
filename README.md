# Deep Graph Networks for Large-Scale Graph Node Embedding Classification on Scientific Publication
![Visualization of PubMed Using Gephi]<https://github.com/JNAIC/Deep-Graph-NN/edit/main/Visualization_of_PubMed.gif>
This repository contains the code implementation for the research study titled "Deep Graph Networks for Large-Scale Graph Node Embedding Classification on Scientific Publication". The code includes the training process, model design, visualization, and other relevant functionalities.

## Table of Contents
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage](#usage)
- [Training](#training)
- [Model Design](#model-design)
- [Visualization](#visualization)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In this study, we propose a novel approach to scientific publication classification using deep graph networks. The code in this repository implements the methodology described in the research paper. It includes the necessary components for training the model, designing the deep graph network, and visualizing the results.



## Usage
Before running the code, make sure you have the necessary dataset available. In this study, we used the PubMed dataset, which is a large citation network that includes scientific publications.

## Training
To train the deep graph network on the PubMed dataset, follow these steps:


1. Train the model using the jupyter:
   ```
   train.py
   ```

2. Monitor the training progress and evaluate the model's performance.

## Model Design
The model design is implemented in the `model.py` file. It includes the construction of the deep graph network using GraphSAGE, batch normalization, and other relevant components. Feel free to modify the model architecture based on your requirements.

## Visualization
The code includes visualization functionalities to analyze the results of the trained model. You can find the visualization scripts in the `visualization` directory. Run the respective scripts to generate visualizations and gain insights into the classification results.

## Contributing
We welcome contributions to this project. If you find any issues or have suggestions for improvements, please feel free to submit a pull request or open an issue.

## License
This project is licensed under the [MIT License](LICENSE). Feel free to use and modify the
