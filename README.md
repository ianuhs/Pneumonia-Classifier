# Pneumonia Classifier

This project explores the use of Convolutional Neural Networks (CNNs) for detecting pneumonia from chest X-ray images. Even though this was my first AI project, I wanted to create something meaningful, so I chose healthcare because I truly believe AI can improve lives. My goal wasn't just to build something that worked, but to learn how AI models like CNNs actually work and how to train them effectively. 

The models are trained using datasets from Kaggle: https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia/data

This project helped me explore:
- Transfer learning using pre-trained CNNs (ResNet)
- Evaluation metrics like accuracy, precision, recall, F1 score, ROC AUC, confusion matrices, etc. 
- Training techniques like data augmentation, weighted loss, and image preprocessing
- Impact of tuning learning rate, epoch count, and network depth
- Understanding training/validation loss and accuracy curves

After each training and evaluation session, I analyzed the performance to see what worked and what didn’t, and made adjustments accordingly. Below is a graph of how the models improved over time. 
<img width="985" height="583" alt="Screenshot 2025-08-08 at 1 15 55 AM" src="https://github.com/user-attachments/assets/8076c0d8-a04c-421b-8828-594793e50156" />
<img width="985" height="585" alt="Screenshot 2025-08-08 at 1 16 20 AM" src="https://github.com/user-attachments/assets/4e36b432-a533-4fe0-ab56-396aa7d89f0f" />


Here are some performance metrics from the latest model, Model 6.
<img width="996" height="465" alt="Screenshot 2025-08-08 at 1 17 00 AM" src="https://github.com/user-attachments/assets/43b17924-5ba8-4b76-99a4-367428361322" />
<img width="825" height="748" alt="Screenshot 2025-08-08 at 1 17 45 AM" src="https://github.com/user-attachments/assets/cdad89a5-e77b-4136-9ece-de26bed2628b" />


I highly encourage you to open the Jupyter Notebook in Colab. I documented my progress with terms and definitions, model analyses, and performance metrics. This is an ongoing project, as there is always room for improvement. Come along and learn with me!
