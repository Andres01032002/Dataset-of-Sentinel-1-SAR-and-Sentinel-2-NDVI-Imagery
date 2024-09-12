# Dataset-of-Sentinel-1-SAR-and-Sentinel-2-NDVI-Imagery

The code provided is designed to run in Google Colaboratory, where you must access the Drive storage and give the necessary permissions to access the Google Earth Engine catalog from the Google programming environment. You must be registered at (https://code.earthengine.google.com/) and use your username to initialize the environment.

![Interfaz_GEE](https://github.com/user-attachments/assets/cbc8c555-2eb0-493d-9a0d-29f82c0b2c75)

# It is essential to have this step to execute the code

![Interfaz_Colab_1](https://github.com/user-attachments/assets/ecbcb046-00d2-43e7-808c-dc8b88e7dcf2)

# Selection conditions

![Interfaz_Colab_2](https://github.com/user-attachments/assets/22dd2cc4-b817-453c-9818-b9f062b40cfa)

In this code, 5 images would be downloaded and only the images with certain properties would be taken into account, such as:

- Average cloud cover percentage less than 5%
- Average water percentage less than 40%
- Average vegetation percentage greater than 10%
  
All these decisions are made based on data provided by Google Earth Engine.
