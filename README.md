# Introductory Training - Circuits
**CNNs, Language Models, and Attention Visualizations in Neuronal Networks**

This repository demonstrates interpretability techniques for Convolutional Neural Networks (CNNs) and transformer-based Language Models (LMs). It is designed to explore and explain **mechanistic interpretability** — understanding how and why neural models make certain predictions.

## Notebooks

1. **CNN Interpretability**  
    `cnn_circuits.ipynb`  
    -> Interpreting CNN models with feature maps, saliency maps, and Grad-CAM visualizations.

2. **Language Model Interpretability**  
    `lm_circuits.ipynb`  
    -> Analyzing hidden states in GPT-2 to detect neural circuits using PCA, K-Means clustering, and t-SNE.

    `circuitsvis_attention.ipynb`  
   -> Using CircuitsVis to visualize attention patterns in GPT-2, revealing how specific attention heads focus on different tokens.

1. **Clone the Repository**:

    git clone https://github.com/IdaCy/circuit-detection-training.git
    cd circuit-detection-training

2. **Install Required Packages**:

Either use pip or conda:

    pip install -r requirements.txt

Or

    conda env create -f environment.yml
    conda activate circenv

3. **Download Sample Images!**

Add sample images to the images/ folder to test circuit detection on different inputs.

4. **Run The Notebooks and Experiment with Results**

## Example images by courtesy of Pixabay:
https://pixabay.com/photos/bicycle-bike-activity-cycle-789648/  
https://pixabay.com/vectors/bicycle-bike-cycling-transport-7876692/  
https://pixabay.com/photos/cat-kitten-pet-striped-young-1192026/  
https://pixabay.com/photos/woman-face-smile-lips-hairstyle-8592765/  
https://pixabay.com/photos/glencoe-scotland-nature-landscape-8299076/  
https://pixabay.com/photos/wood-boards-texture-wooden-brown-2045380/  
