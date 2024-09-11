# Dataset-of-Sentinel-1-SAR-and-Sentinel-2-NDVI-Imagery

The code provided is designed to run in Google Colaboratory, where you must access the Drive storage and give the necessary permissions to access the Google Earth Engine catalog from the Google programming environment. You must be registered at (https://code.earthengine.google.com/) and use your username to initialize the environment.

![Interfaz_GEE](https://github.com/user-attachments/assets/cbc8c555-2eb0-493d-9a0d-29f82c0b2c75)
# It is essential to have this step to execute the code
![Interfaz_Colab_Code](https://github.com/user-attachments/assets/f9fc4efa-4eea-4c76-b578-1afb4836550a)

# Selection conditions

![Interfaz_Colab_Code_1](https://github.com/user-attachments/assets/8a9cc5c6-96d4-40bf-8776-dff37bd8d009)

In this code, 1000 images would be downloaded and only the images with certain properties would be taken into account, such as:

- Average cloud cover percentage less than 5%
- Average water percentage less than 40%
- Average vegetation percentage greater than 10%
  
All these decisions are made based on data provided by Google Earth Engine.
