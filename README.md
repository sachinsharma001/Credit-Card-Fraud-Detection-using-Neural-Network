# Credit-Card-Fraud-Detection-using-Neural-Network
  - Dataset : https://www.kaggle.com/datasets/kartik2112/fraud-detection?select=fraudTrain.csv
    
  - Google Collab Link : https://colab.research.google.com/drive/1mayFYAeP1G3_fsPcGKk-P1UBUHZ7toMQ?usp=sharing
    
  - Github link : https://github.com/sachinsharma001/Credit-Card-Fraud-Detection-using-Neural-Network

  - Methodology: Artificial Neural Network

  - Accuracy : 99%
  
  ![Screenshot 2024-11-14 185633](https://github.com/user-attachments/assets/3882cf69-8599-4de4-a28d-7d9319fc40e1)
  
# Result Analysis 
  - Confusion Graph :- The confusion matrix shows the classified True Negatives and False Positives break-up as follows,
    
      - True Negatives (0, 0): The model accurately identified 99% of valid transactions in this case as non-fraudulent. This demonstrates how effectively the model avoids false positives.
    
      - False Positives (0, 1): The model was wrong only to a small extent of 0.65% in the classification of legitimate transactions as fraudulent, which once again speaks for the accuracy of the model.
    
      - False Negatives (1, 0): The model classified only 0.49% of the fraudulent transactions as not being fraud; therefore, the model has missed very few cases of fraud.
    
      - True Positives (1, 1): The model correctly classified 100% of the fraud cases as fraud and produced excellent recall
    
      ![image](https://github.com/user-attachments/assets/06d7a845-5030-4228-bf8e-52c6b706604f)
    
  - ROC-AUC Curve: demonstrates a high AUC value of 1.00, which stands for perfect class separation between fraudulent and nonfraudulent classes. Therefore, the curve above illustrates that the model is pretty   effective in highlighting the two-class distinction without an overlap; it somewhat increases its robustness concerning accuracy in fraud detection.
    
    ![image](https://github.com/user-attachments/assets/a2f4faa4-2a98-4ce3-be41-8b3326cde0d7)
    
  - Locations of Transactions with Fraud Indication : The geographical heatmaps represent the locations of transactions across United States. The red points signify fraudulent transactions, while the blue points represent actual transactions.
    
    ![image](https://github.com/user-attachments/assets/a4032b0a-2d48-416e-bdf1-c9cb232a3dd9)

    ![image](https://github.com/user-attachments/assets/5c2bc30d-929f-4cf5-a1a4-476c801774b6)

- Transacting Categories, at the hands of Fraud and Non-Fraud The bar chart shows some clear trends in the categories of transactions for fraudulent and for non-fraudulent transactions.
    
    ![image](https://github.com/user-attachments/assets/e46b81ed-56d9-4fc2-a095-9cbd05a8b423)
    
    ![image](https://github.com/user-attachments/assets/d9359af7-a27d-49cf-9126-8ea780753116)
    
  - Distribution of Transaction Amount, City Population, and Fraud Indicator : The distribution for each of the key features the transaction amount (amt), city population (city_pop), and the fraud indicator           (is_fraud)lays out the important patterns for development of a model in fraud detection.
    
    ![image](https://github.com/user-attachments/assets/a8e563ba-22ae-4d84-a163-b471f77d6a78)







