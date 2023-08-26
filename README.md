# SpaceHack
Utilizing sophisticated data analytics and predictive modeling techniques to forecast outcomes of ISRO lunar missions accurately.
Welcome to the ISRO Lunar Landing Success Predictor repository. This project aims to simulate the evaluation process for predicting the success or failure of lunar landings conducted by the Indian Space Research Organisation (ISRO). The repository contains code that generates random lander and rover parameters, simulates the landing success prediction, and evaluates the success based on predefined criteria.

Terrain: The success criteria assume a "Flat" terrain is ideal. If the actual lander's terrain is not "Flat," the landing is deemed unsuccessful.

Propellant Mass: The lander's propellant mass is randomly generated between 1600 and 1800. The code calculates the difference between this value and the predefined success criteria's propellant mass. If the difference exceeds the negative of the success criteria's power margin (0.2), the landing is considered unsuccessful.

Power Margin: The power margin has a predefined acceptable range of ±0.2. If the difference between the lander's power margin and the success criteria's power margin exceeds this range, the landing is unsuccessful.

Communication: If the lander's communication is not "Good" as per the success criteria, the landing is considered unsuccessful.

Payloads: If the number of payloads on the lander is less than the predefined success criteria's payloads, the landing is unsuccessful.
