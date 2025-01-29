# DESIGNTK 521 – Design Technology Core II

## Week 2 Porject Description
Welcome! This project brings together MQTT messaging and Gemini's Language Learning Model to help you understand sensor data in real-time. It listens for MQTT messages, sends the data to Gemini for some easy-to-read explanations, and displays the results right in your console. Plus, there's a separate script to test out Gemini's responses on its own, without the MQTT setup.


- [MQTT](./examples/mqtt)



## Installation 
###Clone the Repository
'''
git clone https://github.com/yourusername/DTI531_MQTT.git
cd DTI531_MQTT

'''
###Install Dependencies
'''
pip install -r requirements.txt

'''
###hidden API KEY
'''
GEMINI_API_KEY=your_gemini_api_key

'''

## MQTT Usage

### Run Publisher

```
python3 pub.py
```

### Run Subscriber

```
python3 sub.py
```

'''
Example: The MQTT script listens to a specified MQTT topic, grabs sensor data, and uses Gemini's LLM to break it down into easy-to-understand explanations.
Received MQTT message: {"temperature": 22.5, "humidity": 45}
Gemini Response: The current temperature is 22.5°C with a humidity level of 45%. Everything is within normal ranges.

'''






