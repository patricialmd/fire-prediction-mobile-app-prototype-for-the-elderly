# Fire Prediction Mobile App Prototype for the Elderly 
![](https://github.com/patricialmd/fire_prediction_app_prototype_elderly/blob/main/Wide%20Awake%20.png)
This was designed as a university project with a focus on elderly-centred UI/UX design. This app serves as a warning alert system for future fires and allows users to prevent deaths or fire-related injuries from happening. 

## I. Motivation
Senior citizens aged 60 and above are at a greater risk of injury or death from home fires due to poor health, whether mental or physical, and other behavioral reasons. While smartphones can help, they are usually designed for younger people. And for fire alarms to be useful, they should be working properly and installed in the living room or bedroom where fires most commonly start. Wide awake was designed to bridge this gap, a fire prediction mobile app that detects smoke and fire in real-time and immediately alerts the elderly and their carers.

## II. Goal
To design a home-fire prediction smartphone app for the elderly using sensor and camera aided by Artificial Intelligence to protect the elderly from fires in their homes.  

## III. Tools Used
| Tool | Purpose |
|------|---------|
| ![JustInMind](https://img.shields.io/badge/JustInMind-6B4FBB?style=for-the-badge&logoColor=white) | Wireframing and prototyping |
| ![Microsoft Word](https://img.shields.io/badge/Microsoft_Word-2B579A?style=for-the-badge&logo=microsoft-word&logoColor=white) | Documentation |

## IV. Features of the App
| Feature | Description |
|---------|-------------|
| **Fire-and-smoke-detection** | This is based on video camera through the use of YOLOv2 model with Convolutional Neural Network that has a faster speed in image processing and sends real-time alert to the elderlies, their carers, and the fire emergency department if the fire or smoke detected is not yet made known to them by the elderly for more than 2 minutes since the fire/smoke started. |
| **Voice command** | This feature can be activated on the Settings by the elderly to alert them using an alarm sound and voice that there is a fire/smoke in their house. |
| **Audio detection** | This feature detects sound of something being burned. |
| **Global positioning statement (GPS)** | This tracks the  location of the elderly. |
| **Messaging feature** | This feature sends the elderly six customised fire related questions per day to know their condition inside their homes. |
| **Fire risk assessment** and **prevention tips** | Used for evaluating their homes and pointers on how to avoid fire. |

## V. Design Rationale
This project intends to make the mobile application elderly-friendly; thus, matching the app’s design interface with the elderly’s needs, requirements, or expectations. Their preferences on what should appear on the user interface cannot be ignored. Such matters include: the length and size of the text; graphics; kinds, locations and size of icons; and color schemes for contents and 
background. Behind these considerations are reasons given by researchers which usually point to older people’s mental and physical state including their poor or failing vision due to old age.  The following elements are used in Wide Awake’s implementation: 
| Elements | Description |
|----------|-------------|
| **Simplicity** | The design of the app is easy to understand, plain, use of minimum words as much as possible and the commands used are simple, not complex, to avoid confusion on the part of the user. For the elderly, usage of long-term memory which is linked to previous experiences is more helpful than short term memory which is related to discovering something different/new. Thus, user interface should apply graphics or functions that the elderly can relate to or identify with. Using pictures, photographs and a combination of both for menu icon for the elderly proved that even with decreasing ability to see, many old people are inclined to read the menu label so the menu label should use simple icons that could readily be understood by the user. Highlighted in this design are important menu buttons that could help the elderly as they are represented by simple familiar pictorial icons labelled with text in large font size appropriate for the elderly’s vision. Due to poor or declining visual ability, older adults prefer the following:  black and bigger font of text; colored text and graphics to highlight significant data; soft color which brings joy to the elderly using the application;  and clear and large graphics, buttons and icons so that senior citizens can click them error-free. |
| **Learnability** | The user interface is designed based on the ability of the user to understand how the mobile phone functions/operates. A study had been conducted on how older people navigate mobile interfaces while they determine usability challenges at the same time. Results showed that the respondents/participants had better chances of understanding the contents rather than the menus and icons of the navigation design and this finding can be a valuable consideration in the development of elderly-friendly mobile application.  |
| **Consistency** | The design of the user interface is dependable, meaning, it would not create any confusion when the elderly uses her mobile phone. In one study intended to find out the accessibility of social media mobile application interface for the elderly, results showed that what can be seen could easily be dealt with as compared with mental or intellectual issues. Proposed guidelines by the research would focus on color schemes, size of font, space and button of app. Cognitive issues still needed further study for the necessary guidelines.  |
| **Structure Principle** | The user interface is structured clearly, where similar/related things are arranged together and those that are not connected are not put together. Also, reliable models that are obvious and can easily be identified are used. Brightness, colour, and font are primarily considered in the design of the app since they influence the success and effortless smartphone usage of senior citizens. It need not be emphasized that as people grow old, they may have impaired eyesight or distorted vision; thus, viewing contents on the screen might take much longer time or even result in wrong interpretations.|

## VI. Scenarios and Wireframe Design
### 6.1 Scenarios
Included in this report are four scenarios for the user interface of the elderly. The user interface of the carer is different from the user interface of the elderly. In the scenarios described below, the elderly-user is assumed to be a female senior citizen named Maria.

### Scenario 1: Fire Alert - Real Fire
Patricia Ann La Madrid <patriciaalamadrid@gmail.com>
	
9:58 AM (21 minutes ago)
	
	
to me
## VI. Scenarios and Wireframe Design
### 6.1 Scenarios
Included in this report are four scenarios for the user interface of the elderly. The user interface of the carer is different from the user interface of the elderly. In the scenarios described below, the elderly-user is assumed to be a female senior citizen named Maria.

### Scenario 1: Fire Alert - Real Fire
In this scenario, the user receives a notification of a fire in her house. She is alerted of imminent danger so she needs to evacuate; she has to go to the nearest exit, then proceed to the nearest emergency assembly area where she determines if there is a real fire or just a false alarm. If the fire is real and she arrives at the assembly area in less than two minutes, she calls the fire service. Otherwise, if it took her a longer time to get there, the app automatically calls the fire service. The elderly also checks the triggered alarm in her house to know the smoke level and temperature of the area where the fire is.
![Scenario 1: Fire Alert](https://github.com/patricialmd/fire_prediction_app_prototype_elderly/blob/main/wireframes/Scenario1.png)

### Scenario 2: Fire Alert - False Alarm
This scenario is similar to scenario 1 with respect to the receipt of a fire notification by the elderly until she reaches the nearest emergency assembly area. The difference lies in the scenario that when she checks the status of the fire, there is no actual fire so she tests the sensor and camera to find out if these are functional. If these are not working, she calls the sensor and camera technician.
![Scenario 2: False Alarm](https://github.com/patricialmd/fire_prediction_app_prototype_elderly/blob/main/wireframes/Scenario2.png)

### Scenario 3: Daily Check-in Feature
In this scenario, the elderly receives notification for daily check-in every 7:00 AM. She has to press the check-in button to answer six questions regarding fire safety in her home and she is reminded to keep a fire-safe environment at all times. She has to answer all the questions on or before 11:30 AM each day; if she fails to do so, somebody from the Wide Awake app will call her.
![Scenario 3: Daily Check-in](https://github.com/patricialmd/fire_prediction_app_prototype_elderly/blob/main/wireframes/Scenario3.png)

### Scenario 4: Fire Risk Assessment & Prevention Tips
In this scenario, the user clicks the MORE tab for her to go to Fire Risk Assessment and Prevention Tips. If she finds the Fire Risk Assessment Page, she has to answer various General Fire Safety Questions and Process Fire Safety Questions. General Fire Safety Questions deal with Means of Detection, Means of Escape, and Management. On the other hand, Process Fire Safety Questions are focused on Ignition and Fuel. She can answer the questions with N/A, Unknown, Yes, No, or 0 Findings. If she completes answering the questions, the Status Page will appear showing how completely she answered the questions, date of creation and last date the Risk Assessment Page was modified. For the Fire Prevention Tips, she gets information on how fires can be prevented.
![Scenario 4: Risk Assessment](https://github.com/patricialmd/fire_prediction_app_prototype_elderly/blob/main/wireframes/Scenario4.png)

### 6.2 Wireframe Design
| Scenario | Visual Design | Ease of Understanding | Navigation and Interaction |
|----------|---------------|-----------------------|----------------------------|
| **Scenario 1: Fire Alert - Real Fire** | • Clear and visible icons, fonts, buttons for menu components<br> • Use of proper color (gray background, red for fire)<br> • Readable texts | Insightful and simple icons, menus, and content | Elderly are able to know where they are located in the app |
| **Scenario 2: Fire Alert - False Alarm** | • Familiar icons, fonts, and buttons for menu components<br> • Use of proper color (gray background, red for fire, blue for safety)<br> • Readable texts | Texts are easily understood | Easy to navigate |
| **Scenario 3: Daily Check-in Feature** | • Familiar icons, fonts, and buttons for menu components<br> • Use of Proper color (gray background, blue for safety)<br> • Readable texts | Texts are easily understood | This feature creates a habit for the senior citizens to respond to the daily customised questions |
| **Scenario 4: Fire Risk Assessment & Prevention Tips** | • Familiar icons, fonts, and buttons for menu components<br> • Use of Proper color (gray background, blue for safety)<br> • Readable texts | Assessments and fire tips are easily understood | Easy to navigate using the buttons such as back, next, save, modify, and the prevention tip button |

## VII. Methodology, Implementation and Result
### 7.1 Method: "Think Aloud Method"
1. A simple method and it does not require so much expertise.
2. It provides important insight and it can present clearly how the system actually works by mere observation and a few questions.
3. It is a cheap process.
4. There would be no problem in the availability of participants and collection of sample size  as  there are many elderly to choose from to be a part of the sample population at present.
5. The goal of the evaluation method is to assess the ability of the user to understand the tasks/messages given by the app and how well she could comply with them.

### 7.2 Implementation 
1. The tasks that users are required to do are presented on the interface in big letters, big and familiar fonts, and colors used are not glaring so as not to hurt the elderly’s eyes or poor vision.
2. While the user is doing her task, she is being observed.
3. She is asked to explain what she is doing and the reason why she is doing such tasks.
4. She has to describe what she thinks is happening.

### 7.3 Result
1. The comments/observations/findings are noted by the researcher/evaluator. 
2. Performance of a task is successful when the user does exactly what the message/situation demands.
3. The evaluation does not only get feedback but also measures the efficiency and usability of the Wide Awake app. 
4. Compared with other off-the shelf products, the Wide Awake app can compete with other apps in the market especially because it is designed to keep the elderly safe from fire in their homes. It is noteworthy to say that the elderly’s needs and requirements were considered in the creation of the app.

## VIII. Limitation and Conclusion
### 8.1 Limitation
The app is a prototype and has not beed tested at scale. Researchers and future technology can further improve it to make it more robust and worthwhile for elderly users. 

### 8.2 Conclusion
The **Wide Awake app** was designed with the elderly's needs and requirements at its core like clear simple language shown in big letters, big familiar fonts, and colors that are easy on declining vision. The benefits expected from the app are valid and measurable, and the findings can be generalised as they are common in everyday life and technological advances have come so far in seeking a fire-hazard free environment for the elderly. As technology continues to advance, apps like Wide Awake represent a meaningful step toward a safer, fire-hazard free environment for the elderly.
