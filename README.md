# AI-Image-Analysis-Model-Training

A jupyter notebook that trains a variety of AI models for image analysis.

Used this dataset: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

I trained and compared the effectiveness of a CNN, an SVM, and an RF model for pneumonia detection on CT scans of peoples lungs. I found that the CNN was by far the best, unsurprisingly. I also employed X-AI tehchniques with CAM heatmaps and SHAP analysis to understand why the models made the judgements they did. Used a variety of libraries such as cv2, shap, numpy, matplotlib, tensorflow,sklearn, and skimage.

Training the CNN Model
![image](https://github.com/DanielJ-OBrien/AI-Image-Analysis-Model-Training/assets/99108127/9a88c7a2-9f4f-4f16-afce-7756de9a8e90)

SHAP Heatmap
![image](https://github.com/DanielJ-OBrien/AI-Image-Analysis-Model-Training/assets/99108127/0b097d50-9f3f-40d1-9e27-8261c2f1ccec)

CAM heatmap
![image](https://github.com/DanielJ-OBrien/AI-Image-Analysis-Model-Training/assets/99108127/668a564b-f8e1-4f48-878b-5c3e388b829c)

Final Results
![image](https://github.com/DanielJ-OBrien/AI-Image-Analysis-Model-Training/assets/99108127/667812ce-4494-4ec1-bf21-cbdf9df1540d)
