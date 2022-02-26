# Blood-Spectorscopy
Blood analysis is traditionally done by taking blood samples from patients and performing various tests on them. Traditional procedures have a number of drawbacks, including painful sticks, lengthy processing times, and limited accessibility. This issue can be addressed by developing non-invasive methods such as the introduction of machine learning models that can classify the level of specific chemical components in blood samples based on their spectroscopic data. We'll use spectral data from a light beam directed at a sample in the Near Infrared (NIR) wavelength ranges (950 nm to 1350 nm). Unlike other wavelengths, NIR has the maximum penetration power and may penetrate deep into attenuated tissues. As a result, we can measure the quantity of energy absorbed for each wavelength using a beam of light with a range of wavelengths. The project is geared to generate a new level of health awareness in individuals with this type of analysis by making blood tests a commodity and a procedure that can be done without effort multiple times a day, similar to how we measure our weight. We may also include the model into new gadgets like wearables that allow patients to complete their blood tests in less than a minute at home and communicate the results to their doctor.

# Features Description
Absorbance: 170 of these labelled as absorbance0, absorbance1 and so on. This is an intensity spectrum of the target blood response to pointed light. 

Temperature: Temperature at the time of the measurement.

Humidity: Humidity at the time of the measurement.

Id: Unique identifier assigned to each measurement.

Hdl_cholesterol_human: The level of cholesterol high. Can be low, ok or high.

Cholesterol_ldl_human: The level of cholesterol low. Can be low, ok or high.

Hemoglobin(hgb)_human: The level of hemoglobin: Can be low, ok or high.

Each blood sample is scanned 60 times, we actually have 60 measurements for each. We have shuffled the measurements, so you won’t know which measurements are from the same sample. Hence, try to fight overfitting as much as possible because this could lead to overfitting.


