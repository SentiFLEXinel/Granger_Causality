# Granger Causality analysis of vegetation on global scales

This repository presents the Granger Causality algorithm used to evaluate causal effects of environmental land variables on vegetation products.
You can easily obtain causality maps that assess how different vegetation products (e.g. LAI, FAPAR, NDVI, SIF etc..) respond to fluctuations in water or energy availability (e.g. temperature, soil moisture etc..)

The code is explained with comments, you need to do some setting up the Google Cloud-Earth Engine-Colab coding environment. The access too Earth Engine datasets is done via a REST API client. It is advised that a Google Colab environment is used for this process. Also, you might want to check https://github.com/KMarkert/restee to get familiari with the "restee" client, that easily converts Earth Engine images to arrays
![gc](https://github.com/daviddkovacs/Granger_Causality_global/assets/123364246/74e4b62d-3173-47cf-8cc5-68d22c49e731)
