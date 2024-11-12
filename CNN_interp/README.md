# CNN Circuits: Interpretability Demonstration

This project demonstrates interpretability techniques applied to a Convolutional Neural Network (CNN) using PyTorch and Captum. We use a pre-trained ResNet18 model and explore several interpretability methods to visualize and understand the inner workings of the model.

## Project Structure

- **cnn_circuits.py**: Main script with code for interpretability techniques.
- **output/**: Directory that will contain the output images of feature maps, saliency maps, and Grad-CAM visualizations.

## Techniques

1. **Feature Maps**: Capturing feature maps from different layers helps understand which patterns the model detects at various stages.
2. **Saliency Maps**: Saliency maps highlight regions of the input that most impact the model’s predictions.
3. **Grad-CAM**: Grad-CAM visualizations show the regions of the input that activate specific filters in the final convolutional layers.

## Running the Code

1. Ensure you have the required dependencies by installing them from `requirements.txt`:

   pip install -r requirements.txt

2. Run the notebook!

3. You can also compare the saved visualizations in the output/ directory.

**Outputs:**
Sample images of feature maps, saliency maps, and Grad-CAM are generated for interpretability.
