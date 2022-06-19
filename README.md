**AI &amp; ROBOTICS HACKATHON 2022 - 18-19/6/2022**

**GROUP:** _KLPM-Untouchables_

Members: Mamadou Keita, Ningyang Li, Pham Duc Thinh, Mohib Ullah 

Dataset: The dataset from VARUNA company, image of Satelite.

Purpose: Crop Classification problem. We have 4 classes for classification: 

![image](https://user-images.githubusercontent.com/73902346/174478096-cc584174-0f77-485b-9d74-50a2751d9da4.png)


# Preprocessing-data


> Step 1: Statistical the data => Imbalance data 
> Step 2: Balance data

# Model

- Environment: on Google Colab environment
- Library: geopandas, rasterio, libpysal, contextily, mapclassify,etc
      https://pypi.org/project/rasterio/
- Training + validation:
Step 1: Split into 20% for validation and 80% for training 
Step 2: Select model: HyperResNet34 and CBAM block => get train accuracy and loss accuracy: ~95%

- Testing: Send the result to VARUNA team.
