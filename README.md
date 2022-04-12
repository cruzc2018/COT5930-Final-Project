# COT5930-Final-Project
# Revisiting Data Augmentation for Skin Lession Classification

This project was built in Google Colab in conjuction with Google Drive and is meant to be modified/built/debugged in Google Colab. Can be edited and ran locally; however, it is not recommended for lower-end Desktops/PC's due to the size of the dataset, the constant moving of files, and intensive training times. 

Getting started:
1. Download the image data set from: https://www.kaggle.com/datasets/andrewmvd/isic-2019
  (beware that this is a 9.8GB zip file so it will take time depending on your internet connection)
2. Upload the zip file to your google drive
  (the default directory is the root folder; however, can be changed in the code to match your desired directory)
3. Clone or download this repo and extract the .ipynb
4. Upload the .ipynb to Google Colab
5. Run the .ipynb on Google Colab
  (It will ask for permission to acess your drive. It is also HIGHLY recommended you change runtime type to gpu instead of none or tpu due to the intensive calculations the network has to perform. Average train time is around 5 hours, unless early stopped)
