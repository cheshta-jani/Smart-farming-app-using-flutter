This mobile app has many features:
1) User Management:
•	Users can register and login using Firebase authentication.
•	Users can manage their profile information.

2) Planting & Harvesting Data Management:
•	Users can add and view planting and harvesting information for various crops.
•	The app stores data like plant name, number of plants, date and estimated harvest date (week).

3) Real-time Monitoring:
•	The app integrates with a virtual IoT simulator (Node-RED) to receive real-time data on: Air temperature, air humidity, Soil moisture, soil salinity and soil Ph
•	Real-time sensor readings are displayed in the app.

4) Data Analysis:
•	The app implements a statistical analysis tool to generate a bar graph representing total harvesting yield for each harvested plant.

5) Plant Disease Detection:
•	The app integrates a trained TensorFlow Lite model for plant disease detection using images captured from the app.
•	The app provides suggestions and solutions for detected diseases.
• It detects 5 leaf diseases: corn common rust, corn gray leaf spot, potato early blight, strawberry leaf scorch, tomato leaf mold and tomato mosaic virus.
• The trained model can be found in assests folder as model.tflite file

6)News and weather Features:
The app integrates news and weather APIs to display:
•	Latest science news
•	Real-time weather information for the required location

Below are the screenshots for the same:

Signup Page:
 ![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/3484a551-794d-4e76-ba2b-7caab529ff9d)
 
Login Page:
 ![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/2f14b978-7f69-4a05-9242-9c9e38ba0df4)

Home Page:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/a903d728-58c9-476f-9637-beb50369af82)

Planting: 
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/f5a5697e-57c0-4171-b426-cf5dec38faae)

 ![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/e9af3a9b-f9d9-4bd2-8065-0cd0f588cfeb)

![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/0ca9a59c-70bc-43e2-9665-ebfbd7bc9986)

Harvesting:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/06d2e174-7351-4fc2-adc9-fa487a347b6c)

![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/12a262bc-814d-4126-8e62-579f81d924ed)

![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/3ce96e53-4da5-42da-b78b-304ecfc07290)

View Statistics Page:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/b964c72a-5d96-4e5f-8450-e218231ca823)

![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/a5c9ba7e-7227-4f6a-a1df-142140d3bd40)


IOT Monitoring:
![WhatsApp Image 2024-05-18 at 16 36 13_fb42df0f](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/4dbeedb2-62f2-457f-9a56-42dcdaf36147)

![WhatsApp Image 2024-05-18 at 16 36 13_5bfbcd73](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/999db6ae-f4fc-4e42-9246-172ff195c3db)

 
Values getting updated in database in realtime.
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/5290649c-7129-4797-9dc9-fa45df92cad5)

Node-RED simulator flow: 
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/b5c1109f-7c38-4cf0-aedf-bf3439b2f301)

Dashboard:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/3b59c719-1dff-415d-bef6-3fbfb0e3acbd)
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/0b6280a0-2c01-49fe-bf04-0e73967cb8dc)

Diseases Detection Page:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/6bb4a775-4346-48af-af5f-9e36ad5cd689)

My profile and logout page:
![image](https://github.com/cheshta-jani/Smart-farming-app-using-flutter/assets/122821547/d6c6cd7a-f4cd-4766-9aac-d62b7c708503)

