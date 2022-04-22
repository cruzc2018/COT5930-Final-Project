# COT5930-Final-Project
## Revisiting Data Augmentation for Skin Lession Classification

*This project was built in Google Colab in conjuction with Google Drive and is meant to be modified/built/debugged in Google Colab. Can be edited and ran locally; however, it is not recommended for lower-end Desktops/PC's due to the size of the dataset, the constant moving of files, and intensive training times.*

The use of convolutional neural networks in a field such as dermatology has had a growing interest in recent years with many applications including the classification of benign and malignant skin lesions. With such advances in the field, dermatologists can improve diagnosis and generate a better treatment plan. In the passing years there has been a significant focus on classifying benign and malignant skin lesions; however, the area that most needs attention is in being able to correctly classify instances from non-dermatoscopic images; not to mention, the lack of variety between the class definitions. A majority of the models are only trained to output a classification of benign or malignant. Arguably this is the more important classification for a skin lesion; however, what if a more specific diagnosis was required such as the sub categories that fall under benign or malignant such as melanoma, basal cell carcinoma, and seborrheic keratosis?

There already exist many models in the field; however, the idea behind our research was to not just make it more accurate by extensively testing different image augmentation for the best ones, but to also make the CNN more practical to use not just for medical imaging centers but, for the general population as well. We accomplished this by trying many different combinations of augmentations on the images as well as looking at current research in the field.

Getting started:
1. Download the image data set from: https://www.kaggle.com/datasets/andrewmvd/isic-2019
  (beware that this is a 9.8GB zip file so it will take time depending on your internet connection)
2. Upload the zip file to your google drive
  (the default directory is the root folder; however, can be changed in the code to match your desired directory)
3. Clone or download this repo and extract the .ipynb
4. Upload the .ipynb to Google Colab
5. Run the .ipynb on Google Colab
  (It will ask for permission to acess your drive. It is also HIGHLY recommended you change runtime type to gpu instead of none or tpu due to the intensive calculations the network has to perform. Average train time is around 5 hours, unless early stopped)

#### *Credit for this project goes to Christian Cruz & Sofia Feliciano and can be reached at {cruzc2018, felicianos2018}@fau.edu*
