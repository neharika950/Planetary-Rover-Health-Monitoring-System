This comprehensive research combines fuzzy logic and artificial neural networks (ANNs) to address the challenges faced by Mars rovers in extreme environments. The fuzzy logic system interprets environmental and component performance parameters, enabling real-time risk assessment, while the ANN accurately predicts the Remaining Useful Life (RUL) of rover batteries. Together, these systems enhance the rover's operational reliability and mission success.

Key highlights include:

1. Fuzzy Logic for Environmental Assessment:  
   - Inputs include temperature, sensor functionality, and communication status.  
   - Membership functions and rules assess environmental risks.  
   - Integration with Simulink demonstrates real-time application.

2. Fuzzy Logic for Component Monitoring:  
   - Parameters include motor performance, wheel condition, and temperature.  
   - The system evaluates the rover's readiness and adaptability.

3. ANN for Battery RUL Prediction:  
   - Uses features like discharge time and voltage decrement.  
   - A single hidden layer with 10 neurons ensures robust learning.  
   - Achieved a high correlation (R > 0.97) between predicted and actual RUL.

4. Performance Evaluation:  
   - Regression analysis and prediction accuracy validate the ANN model.  
   - Integration of ANN and fuzzy logic enables proactive maintenance.

This integrated approach ensures adaptive, reliable rover performance and supports the longevity of Mars exploration missions.

![image](https://github.com/user-attachments/assets/b575189f-fe2e-4904-aefd-cd8a8077f2c2)
Fuzzy Logic Designer interface  showing the defined membership functions.

![image](https://github.com/user-attachments/assets/544f0de9-81ad-424e-b1d1-f5d582ba6bf0)
Simulink model illustrating the integration of the fuzzy logic system and system simulation.

![image](https://github.com/user-attachments/assets/323cebd7-0353-4b32-b55c-ed47c0af5450)
Fuzzy Logic  Designer for Rover Components

![image](https://github.com/user-attachments/assets/285cbdf3-f91b-47a0-a0b2-85532912f21c)
Simulink Model for Rover Components Using Fuzzy Logic

![image](https://github.com/user-attachments/assets/3efa27ab-9bc2-4184-8e42-75bd7c305bd4)
Regression Analysis of ANN Predictions for Battery RUL

![image](https://github.com/user-attachments/assets/a3f9f487-3d9d-4454-8594-5b6e87541f07)
Comparison of Actual vs. Predicted RUL Values




