# Final Results and Conclusion

This section presents the final academic outcomes of the DermAI graduation project, including quantitative performance results, system evaluation, limitations, and future research directions.

---

## Quantitative Performance Results

The final trained convolutional neural network demonstrated stable and consistent performance across both validation and test datasets.  
Figure X illustrates a comparison between validation and test performance metrics, including accuracy, precision, recall, and F1-score.

The model achieved an accuracy of approximately **84%** on the test dataset, indicating effective classification capability for benign and malignant skin lesions.  
Precision and recall values were observed to be within the range of **74%–75%**, reflecting a balanced trade-off between false positive and false negative predictions.  
The resulting F1-score of approximately **74%** further confirms the consistency and reliability of the model’s predictive performance.

The close alignment between validation and test results suggests good generalization behavior and limited overfitting, supporting the robustness of the proposed approach.

---

## System Evaluation

The DermAI system successfully integrates frontend, backend, and artificial intelligence components into a cohesive end-to-end workflow.  
Users are able to upload skin lesion images, receive classification results, and view visual explanations through an intuitive web-based interface.

The modular architecture of the system enhances maintainability and allows independent development and evaluation of each system component.  
Explainable AI techniques, specifically Grad-CAM visualizations, contribute to improved interpretability by highlighting image regions that influenced the model’s decisions.

---

## Academic Contribution

This project provides several academic contributions, including:
- Application of deep learning techniques to a real-world medical image analysis problem
- Comparative evaluation of multiple convolutional neural network architectures
- Use of cross-validation strategies to enhance model robustness
- Integration of explainable AI methods to improve transparency and trustworthiness

The project demonstrates the potential of artificial intelligence as a supportive tool in healthcare-oriented decision support systems.

---

## Limitations

Despite promising results, the project has certain limitations:
- Dependence on publicly available datasets, which may not fully represent real clinical environments
- Binary classification limited to benign and malignant categories
- Absence of clinical validation by medical professionals

These limitations indicate areas where further research and validation are required.

---

## Future Work

Future enhancements to the DermAI system may include:
- Expanding the dataset with clinically verified images
- Extending the model to support multi-class skin disease classification
- Improving performance through advanced ensemble learning techniques
- Conducting clinical studies in collaboration with dermatology experts

---

## Conclusion

DermAI demonstrates the effectiveness of combining deep learning techniques with web-based system architectures to support early skin cancer detection.  
The system achieves stable and reliable performance while maintaining interpretability and usability.

Overall, the project fulfills its academic objectives and provides a solid foundation for future research and potential real-world deployment, while emphasizing that it serves as an assistive tool and does not replace professional medical diagnosis.
