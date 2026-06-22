# Cancer Cell Detection Using Deep Learning

Binary classification of breast cancer tumors (malignant vs benign) 
using the Wisconsin Breast Cancer Dataset — implemented in both 
PyTorch and TensorFlow/Keras for framework comparison.

## Project Structure
| Notebook | Framework | Test Accuracy |
|---|---|---|
| Cancer_Detection_PyTorch.ipynb | PyTorch | 93.9% |
| Cancer_Detection_TensorFlow.ipynb | TensorFlow/Keras | 95.6% |

## Dataset
- **Wisconsin Breast Cancer Dataset** (built into scikit-learn)
- 569 samples, 30 numeric features, 2 classes (malignant / benign)
- No external download required — loaded via `sklearn.datasets`

## Model Architecture
Same architecture implemented in both frameworks:
