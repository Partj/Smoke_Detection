# Smoke_Detection
A Machine Learning Algorithm to check the probability of a smoke alarm going off when certain conditions are met.
This model was trained using a decision tree.
Sklearn library was used to train the model in python.

***How does a Smoke detector work?***

Smoke alarms use two types of detection technologies to detect particles in the air: ionization detectors and photoelectric detectors. 

Ionization detectors use a small amount of radioactive material to ionize the air molecules between two metal plates, producing an electric current. When smoke particles enter the chamber, they reduce the current, triggering the alarm. 

Photoelectric detectors detect light reflected off particles from a light beam inside the sensing chamber. When there are enough particles present to reach a certain threshold level of light, the alarm sounds. The radioactive material used in ionization detectors is safely shielded, and the radiation levels in the device are much lower than natural background radiation.

***Why are Factors like Temperature and Humidity Important in smoke detection?***

Smoke alarms can trigger when the temperature is very cold or if a door adjacent to a heated area is opened, causing condensation (water vapor) to form in the detection chamber. Since the sensor is designed to detect particles, the presence of water droplets in the sensor will set off the alarm. Smoke alarms typically work within a temperature range of 40 to 100 degrees Fahrenheit (4-38 degrees Celsius). If the smoke alarm is installed in a garage or attic where temperature fluctuations and condensation are common, it is recommended to replace it with a heat alarm that is not affected by condensation.

**<u>Decision tree visalized</u>**
![smoke_detected](https://user-images.githubusercontent.com/113210030/230684280-d2e4ad60-9d75-4dd7-a1d2-151299eb8cae.svg)

**Accuracy of the model with code**
![accuracy](https://user-images.githubusercontent.com/113210030/230684635-f7dbd9ae-d2c0-4a4d-9eed-1a8e71c6d694.png)


***Sources:***

https://www.nist.gov/how-do-you-measure-it/how-do-smoke-detectors-work#:~:text=Smoke%20alarms%20detect%20fires%20by,Smoke%20alarms%20save%20lives.

https://www.kidde.com/home-safety/en/us/support/help-center/browse-articles/articles/nuisance_smoke_alarms_when_its_cold_outside.html#:~:text=Your%20smoke%20alarm%20may%20sound,unit%20will%20go%20into%20alarm.
