# Asthma-Risk-Prediction
# ABSTRACT:

Air pollution poses a significant threat to global health, particularly in relation to respiratory conditions, contributing to over 8 million deaths annually. The impact is widespread, with more than 4.2 million deaths attributed to outdoor exposure and an additional 3.8 million linked to indoor pollution. Respiratory symptoms induced by pollutant agents are evident, with a pronounced interference in asthma outcomes, including incidence, prevalence, hospital admissions, emergency department visits, mortality, and asthma attacks. Amidst the ongoing COVID-19 situation, the risk escalates for older adults and individuals with complications like hypertension and diabetes during hospital admissions. Addressing this concern, an essential in-house monitoring framework for predicting asthma risk is proposed. The proposed Asthma Risk Prediction framework utilizes deep learning algorithms to estimate vulnerability based on particulate matter (PM) levels in the living environment and outdoor weather conditions. Employing Convolutional Neural Networks, the framework categorizes predicted peak expiratory flow rate (PEFR) levels into three groups: "Green" (Safe), "Yellow" (Moderate Risk), and "Red" (High Risk). When conditions indicate potential asthma risk, proactive measures such as activating air purifiers and notifying first responders are initiated. The hardware implementation involves PM sensors for detection, with a Raspberry Pi serving as the edge node to predict risk levels and trigger the response system. 

KEYWORDS-edge computing, machine learning, iot, Asthma prediction, particulate matter (PM), peak expiratory flow rates (PEFR), convolutional neural network, Raspberry  

# Algorithm: 


Algorithm explaining the proposed system working in real-time Input: PM2.5, PM10, outdoor temperature, humidity. Output: Safe, Moderate or High asthma risk prediction. Data processing stage on the Raspberry Pi: Collect PM2.5, PM10 using SDS011; Collect weather data using Openweather map; Data hosting the input features to server; Real-time stage on the Smartphone:


