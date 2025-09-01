# Mobile Price Classification using Machine Learning on AWS SageMaker

Mobile price classification is a popular problem in machine learning, where the objective is to build a predictive model that can categorize mobile phones into different price ranges based on their features and specifications. Such a model helps automate the process of estimating the price category of a mobile device, which is valuable for both consumers and sellers.

For **consumers**, it provides insights that aid in comparing devices and making informed purchase decisions.  
For **sellers**, it can support competitive pricing strategies and offer a better understanding of market trends.

## Dataset

The dataset used for this task was sourced from Kaggle under the title **"Mobile Price Classification"**. It contains nearly 2000 entries of mobile phones with various features and specifications, along with their corresponding price range. By analyzing the features, the model can predict the price category of a mobile phone.

## Features

- **battery_power**: Total energy a battery can store (in mAh)  
- **blue**: Bluetooth availability (1 = Yes, 0 = No)  
- **clock_speed**: Speed at which the processor executes instructions  
- **dual_sim**: Dual SIM support (1 = Yes, 0 = No)  
- **fc**: Front camera resolution (in megapixels)  
- **four_g**: 4G support (1 = Yes, 0 = No)  
- **int_memory**: Internal memory (in GB)  
- **m_dep**: Mobile depth (in cm)  
- **mobile_wt**: Weight of the mobile phone  
- **n_cores**: Number of processor cores  
- **pc**: Primary camera resolution (in megapixels)  
- **px_height**: Pixel resolution height  
- **px_width**: Pixel resolution width  
- **ram**: Random Access Memory (in MB)  
- **sc_h**: Screen height (in cm)  
- **sc_w**: Screen width (in cm)  
- **talk_time**: Maximum duration a single battery charge lasts  
- **three_g**: 3G support (1 = Yes, 0 = No)  
- **touch_screen**: Touchscreen availability (1 = Yes, 0 = No)  
- **wifi**: WiFi support (1 = Yes, 0 = No)  

### Target Variable

- **price_range**: Indicates price category  
  - 0 = Low cost  
  - 1 = Medium cost  
  - 2 = High cost  
  - 3 = Very high cost
