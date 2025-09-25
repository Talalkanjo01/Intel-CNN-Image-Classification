# Intel Image Classification with CNN

## Project Description
This project was developed as part of the Akbank Deep Learning Bootcamp.  
The aim is to classify 6 different scene categories (Buildings, Forest, Glacier, Mountain, Sea, Street) using a Convolutional Neural Network (CNN).

## Dataset
- Intel Image Classification Dataset from Kaggle  
- Train: ~25,000 images  
- Test: ~14,000 images  
- Classes: Buildings, Forest, Glacier, Mountain, Sea, Street

## Methodology
- Data preprocessing with ImageDataGenerator  
- Data augmentation: rotation, shifting, zoom, horizontal flip  
- CNN architecture with 3 convolutional blocks, GlobalAveragePooling, Dropout, Dense layers  
- Activation functions: ReLU, Softmax  

## Results
- Accuracy after 10 epochs: ~75%  
- Accuracy after 20 epochs: ~82%  
- Loss and accuracy curves included in the notebook.  

## Hyperparameter Tuning
| Learning Rate | Val. Accuracy |
|---------------|---------------|
| 0.001         | ~82% |
| 0.0005        | ~80% |

## Additional Analysis
- Confusion Matrix  
- Eigen-CAM visualizations  

## Files
- Kaggle Notebook: [Intel CNN Notebook]([https://www.kaggle.com/YOUR_LINK_HERE](https://www.kaggle.com/code/talalkanjo/akbankderin-renmebootcamp-deneme-2))
- Saved model: `intel_cnn_model.h5`
