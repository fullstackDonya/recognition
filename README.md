# recognition


 UN MODEL QUI EFFECTUE LES TACHES SUIVANTES 

✅ Évaluation du pipeline

✅ Étapes bien réalisées :

✅ Téléchargement automatique du dataset

Found 28709 images belonging to 7 classes.
Found 7178 images belonging to 7 classes.

✅ Prétraitement avec ImageDataGenerator (normalisation)

✅ Architecture CNN bien adaptée à FER2013 (3 blocs conv + dense)

✅ Sauvegarde avec ModelCheckpoint sur la meilleure val_accuracy

✅ Prédiction en live sur la webcam avec face_cascade + cv2

✅ Sauvegarde finale au format .h5 et .keras

✅ Évaluer précisément la performance après entraînement

225/225 ━━━━━━━━━━━━━━━━━━━━ 11s 47ms/step - accuracy: 0.5848 - loss: 1.1853
Test accuracy: 0.58, Loss: 1.1846


✅ Afficher une matrice de confusion (facultatif mais utile)

               precision    recall  f1-score   support
       Angry       0.13      0.16      0.14       958
     Disgust       0.00      0.00      0.00       111
        Fear       0.14      0.09      0.11      1024
       Happy       0.24      0.26      0.25      1774
         Sad       0.17      0.15      0.16      1233
    Surprise       0.18      0.22      0.20      1247
     Neutral       0.12      0.11      0.11       831

    accuracy                           0.17      7178
   macro avg       0.14      0.14      0.14      7178
weighted avg       0.17      0.17      0.17      7178

![image](https://github.com/user-attachments/assets/ac8d9e93-a649-4a1b-95d9-ecc9b7e13012)

