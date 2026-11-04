# Model Performance Comparison

The following table summarises the performance of MobileNetV2 and ResNet50 on the PlantVillage test dataset.

| Metric | MobileNetV2 | ResNet50 |
|---|---:|---:|
| Test Accuracy | 94.75% | 97.97% |
| Test Loss | 0.1569 | 0.0673 |
| Macro F1-score | 93.52% | 97.02% |
| Weighted F1-score | 94.69% | 97.97% |

## Observations

ResNet50 achieved higher test accuracy and F1-scores than MobileNetV2.

These results indicate that ResNet50 performed better on this particular test dataset. However, classification performance alone does not establish that it is the more suitable model for every application. Factors such as model size, inference speed, and performance on real-world images would also need to be considered.
