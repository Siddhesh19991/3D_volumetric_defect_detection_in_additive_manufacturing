# 3D Volumetric Defect Detection in Additive Manufacturing

This project was completed as my master’s thesis in the [Master’s in Statistics and Machine Learning program](https://liu.se/en/education/program/f7mml) at Linköping University.  
This thesis was carried out in collaboration with [InterSpectral](https://interspectral.com/), a company specializing in advanced data visualization solutions for the Additive Manufacturing industry. 

## Abstract
Additive manufacturing, commonly referred to as 3D printing, is transforming modern
production by enabling the manufacturing of complex geometries with reduced material
waste. However, the presence of anomalies during the build process remains a significant
challenge, often affecting part quality and leading to production inefficiencies.
This thesis investigates the use of 3D volume-based object detection techniques to iden-
tify defects within powder bed images. By treating image stacks as 3D volumes, this ap-
proach captures both spatial and temporal patterns, providing a richer representation of
the build process. Machine learning and deep learning methods are implemented and
evaluated to detect and localize defects using 3D bounding boxes.
Overall, traditional machine learning models like Random Forest and XGBoost outper-
formed deep learning architectures like ResNet in this study. Among the deep learning
models, those pretrained on Med3D, a dataset from the closely related field of medical
imaging, performed better than models trained from scratch or pretrained on unrelated
data such as Kinetics-400. This suggests that transfer learning from domains with simi-
lar data characteristics can improve the performance. However, even the best-performing
deep learning model lagged behind traditional methods, likely due to the relatively simple
structure of the powder bed images. These results suggest that traditional models leverag-
ing statistical features remain more effective in scenarios with low visual complexity.

## Code & Data
All code and data are proprietary to InterSpectral under a signed agreement. If you would like to discuss access or have any questions, please don’t hesitate to contact me at siddheshraw@gmail.com
