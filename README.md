# Blood-Spectorscopy
Blood analysis is traditionally done by taking blood samples from patients and performing various tests on them. These procedures have several drawbacks, including painful sticks, lengthy processing times, and limited accessibility. This paper is set to develop non-invasive methods such as the introduction of machine learning models that can classify the level of specific chemical components in blood samples such as high-density lipoprotein cholesterol, low-density lipoprotein cholesterol and hemoglobin levels based on their spectroscopic data such that blood tests becomes an effortless procedure just like the way we measure our weights. Spectral data is collected from a light beam directed at a sample in the Near Infrared (NIR) wavelength ranges (950 nm to 1350 nm). This data is provided by Bloodsai for a Zindi competition. A model is built by training, and then is employed to predict the testing set data. The maximum accuracy observed after prediction is 58.22%. In this paper, we try to use multiple models and adjust hyperparameters to improve the ability of the model. The evaluation results show that Logistic Regression unoptimized performed better than other models to predict high-density lipoprotein cholesterol, low-density lipoprotein cholesterol and hemoglobin levels.

# Features Description
Absorbance: 170 of these labelled as absorbance0, absorbance1 and so on. This is an intensity spectrum of the target blood response to pointed light. 

Temperature: Temperature at the time of the measurement.

Humidity: Humidity at the time of the measurement.

Id: Unique identifier assigned to each measurement.

Hdl_cholesterol_human: The level of cholesterol high. Can be low, ok or high.

Cholesterol_ldl_human: The level of cholesterol low. Can be low, ok or high.

Hemoglobin(hgb)_human: The level of hemoglobin: Can be low, ok or high.

Each blood sample is scanned 60 times, we actually have 60 measurements for each. We have shuffled the measurements, so you won’t know which measurements are from the same sample. Hence, try to fight overfitting as much as possible because this could lead to overfitting.

# Acknowledgement
I wish to thank BloodsAi and Zindi for introducing this challenge and providing the data. It was indeed an interesting experience. 

