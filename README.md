# Explainable-AI-Techniques-for-Bone-Fracture-Detection-Using-Deep-Learning

Explainable AI for Bone Fracture Detection This project presents a deep learning-based solution for automated bone fracture detection from X-ray images, enhanced with Explainable AI (XAI) techniques to interpret model predictions and improve clinical trust. The model was trained on the FracAtlas dataset using a ResNet50 architecture, and explanations were generated using Grad-CAM, SHAP, LIME, and Saliency Maps.

Project Goals: Detect fractures from X-ray images using a binary image classifier. Apply four XAI methods to visualize which regions influenced the model’s predictions. Evaluate interpretability and accuracy to bridge the gap between AI and clinical usability

Techniques & Tools Used: Frameworks: TensorFlow, Keras, SHAP, LIME, OpenCV Model Architecture: ResNet50 (pre-trained on ImageNet) Explainability Methods: Grad-CAM SHAP (Shapley Additive Explanations) LIME (Local Interpretable Model-Agnostic Explanations) Saliency Maps

Results: Model Accuracy: 92.7% Precision: 0.91 Recall: 0.94 F1-Score: 0.93 Most Interpretable XAI Method: LIME (Mean precision: 0.0372, Mean accuracy: 0.894) Visual explanations aligned strongly with fracture regions annotated by experts.

Dataset: FracAtlas (by Abedeen et al.): Contains 4,083 X-ray images of fractures across shoulder, elbow, wrist, hip, and knee. Binary-labeled as fractured or non-fractured.
