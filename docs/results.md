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

<img width="1569" height="630" alt="Screenshot 2025-12-09 112233" src="https://github.com/user-attachments/assets/b2549550-bafb-4865-8d5d-0a782d84c931" />


<img width="400" height="400" alt="media_images_confusion_matrix_8_c23897708e17a3ac90f3" src="https://github.com/user-attachments/assets/ecd679d9-9665-4b87-8129-b373de133d62" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_e19b99433429f9f8dc0b" src="https://github.com/user-attachments/assets/af90bf37-2ed8-4e1a-a1cd-43342f0bdc3b" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_61a69143275eb38db84a" src="https://github.com/user-attachments/assets/1a8bef67-0c08-44ab-9aca-9cfa6c7b0a12" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_f4cc759e77f15f151cd0" src="https://github.com/user-attachments/assets/e4538df1-cc99-4381-a0ba-fae2ed476c74" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_e1e197d040f25b2a0e69" src="https://github.com/user-attachments/assets/ffb1ee70-0b53-4edc-bd32-09967d245acc" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_906c58257f11d97dea3b" src="https://github.com/user-attachments/assets/1603c09c-c183-4be9-b7a1-c6fa646f0575" />
<img width="400" height="400" alt="media_images_confusion_matrix_8_320ee2d2cb22eff42ff7" src="https://github.com/user-attachments/assets/b378962d-78bc-433c-809b-c454076babd0" />

<img width="1159" height="627" alt="Screenshot 2025-12-09 112841" src="https://github.com/user-attachments/assets/146480a5-eb8f-4959-837a-35606ce39fee" />
