# Experiments, Results, and Visualizations

## Batch Size Experiment
- Batch size 16 → **90% validation accuracy**
- Batch size 64 → **85% accuracy**

Smaller batches generalize better on this dataset.

## Learning Rate Experiment
- LR = 0.001 → unstable, ~50% accuracy
- LR = 0.0001 → smooth, **90% accuracy**

Lower learning rate = better convergence.

## Augmentation Experiment
- With augmentation → stable **90%**
- Without augmentation → fluctuated, ended at **80%**

Augmentation reduced overfitting.

## Architecture Comparison
- AlexNet best: **90% accuracy**
- ResNet18 best: **95% accuracy**

ResNet18 had fewer misclassifications and lower loss.

---

## Visualizations
Add screenshots from W&B here:

- Accuracy curves  
- Loss curves  
- Confusion matrix  
- Model comparison  

(Just drag images into the Markdown editor to upload automatically)

