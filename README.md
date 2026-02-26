# Wide Awake: A Mobile app prototype that predicts home fire and notifies the elderly and their carers when smoke/fire is detected

This app serves as a warning alert system for future fires and allows users to prevent deaths or fire-related injuries from happening. It will be released on both iOS and Android.

## I. Motivation
The primary motivation behind Wide Awake app is the fire safety of the elderly. Should fires occur in their homes, older people whose ages range from 60 years or more (Cassidy et al., 2021, Salman et al., 2022) have greater possibilities of succumbing to death or having injuries due to poor health, whether mental or physical, or other behavioral reasons (Karemaker et al., 2021). It is therefore of paramount importance to maintain safety measures that can effectively help the elderly avoid death or injury by fire in their own houses (Karemaker et al., 2021). To be useful to senior citizens, fire alarms in their homes should be working properly and installed in the living room or bedroom where fires usually happen (Cassidy et al., 2021). Smartphones can help the elderly but they are usually designed for younger people; thus, senior citizens may have difficulty in navigating/using the user interface of such gadgets (Awan et al., 2021). The elderly can be confused and/or baffled by new technologies due to age-related problems, physical abilities, memory decline, mental models, cognitive or sensory functions, and the design of smartphone apps may not have considered their needs or requirements (Awan et al., 2021). 

The **features of the Wide Awake app** are the following: 
- **Fire-and-smoke-detection** which is based on video camera through the use of YOLOv2 model with Convolutional Neural Network that has a faster speed in image processing (Saponara et al., 2021) and sends real-time alert to the elderlies, their carers, and the fire emergency department if the fire or smoke detected is not yet made known to them by the elderly for more than 2 minutes since the fire/smoke started;
- **Voice command** feature can be activated on the Settings by the elderly to alert them using an alarm sound and voice that there is a fire/smoke in their house,
- **Audio detection** feature detects sound of something being burned. This is similar to Google Nest feature (Google Nest, n.d.);
- **Global positioning statement (GPS)** - tracks the  location of the elderly;
- **Messaging feature** - sends the elderly six customised fire related questions per day to know their condition inside their homes. This is like the Snug Safety app feature (Snug Safe, n.d., Snug Safety, n.d.); and
- **Fire risk assessment** (similar to Fire Guard app feature (Fire Guard, n.d.)) and **prevention tips** for evaluating their homes and pointers on how to avoid fire.

Overall, this project aims to design a home-fire prediction smartphone app for the elderly using sensor and camera aided by Artificial Intelligence to protect the elderly from fires in their homes.  

## Design Rationale
This project intends to make the mobile application elderly-friendly; thus, matching the app’s design interface with the elderly’s needs, requirements, or expectations. Their preferences on what should appear on the user interface cannot be ignored. Such matters include: the length and size of the text; graphics; kinds, locations and size of icons; and color schemes for contents and 
background. Behind these considerations are reasons given by researchers which usually point to older people’s mental and physical state including their poor or failing vision due to old age.  The following elements are used in Wide Awake’s implementation and they are the following: 
- Simplicity - relates to easy recall of undertakings to be done (Abdul Razak et al.). The design of the app is easy to understand, plain (Sulaiman and Sohaimi, Yusof et al., 2014, Abdullah and Abdul Hamid, 2019, Ziefle and Bay, 2006, Norman, 1995), use of minimum words as much as possible (Sulaiman and Sohaimi, Lorenz and Oppermann, 2009) and the commands used are simple, not complex, to avoid confusion on the part of the user (Abdul Razak et al.). For the elderly, usage of long-term memory which is linked to previous experiences is more helpful than short term memory which is related to discovering something different/new (Abdul Razak et al.). Thus, user interface should apply graphics or functions that the elderly can relate to or identify with (Abdul Razak et al.). Using pictures, photographs and a combination of both for menu icon for the elderly proved that even with decreasing ability to see, many old people are inclined to read the menu label so the menu label should use simple icons that could readily be understood by the user (Restyandito et al., Li and Luximon, 2020). Highlighted in this design are important menu buttons that could help the elderly as 
they are represented by simple familiar pictorial icons labelled with text in large font size appropriate for the elderly’s vision (Restyandito et al.). Due to poor or declining visual ability, older adults prefer the following:  black and bigger font of text; colored text and graphics to highlight significant data; soft color which brings joy to the elderly using the application;  and clear and large graphics, buttons and icons so that senior citizens can click them error-free (Abdullah and Abdul Hamid, 2019, Azir Rezha et al., 2014).
- Learnability – The user interface is designed based on the ability of the user to understand how the mobile phone functions/operates (Ji et al., 2006, Norman, 1995). A study had been conducted on how older people navigate mobile interfaces while they determine usability challenges at the same time (Li and Luximon, 2020). Results showed that the respondents/participants had 
better chances of understanding the contents rather than the menus and icons of the navigation design and this 
finding can be a valuable consideration in the development of elderly-friendly mobile application (Li and Luximon, 2020, Dodd et al., 2017).  
- Consistency - The design of the user interface is dependable, meaning, it would not create any confusion when the elderly uses her mobile phone (Ji et al., 2006, Norman, 1995). In one study intended to find out the accessibility of social media mobile application interface for the elderly, results showed that what can be seen could easily be dealt with as compared with mental or intellectual issues (Chang et al.). Proposed guidelines by the research would focus on color schemes, size of font, space and button of app (Chang et al.). Cognitive issues still needed further study for the necessary guidelines (Chang et al.).  
- Structure Principle - The user interface is structured clearly, where similar/related things are arranged together and those that are not connected are not put together (Ji et al., 2006). Also, reliable models that are obvious and can easily be identified are used (Ji et al., 2006). Brightness, colour, and font are primarily considered in the design of the app since they influence the success and effortless smartphone usage of senior citizens  (Preeyanont, 2017). It need not be emphasized that as people grow old, they may have impaired eyesight or distorted vision; thus, viewing contents on the screen might take much longer time or even result in wrong interpretations (Preeyanont, 2017).

Overall, I intend to create an app that can protect old people and spare them from injuries, near-death experiences and even death itself when the monster known as fire visits their homes.

## References
REFERENCES 
ABDUL RAZAK, F., RAZAK, N., WAN ADNAN, W. & AHMAD, N. How simple is simple: our experience with older adult users.  ACM 
International Conference Proceeding Series, 2013. ACM, 379-387. 

ABDULLAH, N. & ABDUL HAMID, N. F. B. 2019. Interface design features of mobile application for senior citizens. Indonesian Journal of 
Electrical Engineering and Computer Science, 14, 436. 

AWAN, M., ALI, S., ALI, M., ABRAR, M. F., ULLAH, H. & KHAN, D. 2021. Usability Barriers for Elderly Users in Smartphone App Usage: An 
Analytical Hierarchical Process-Based Prioritization. Scientific programming, 2021, 114. 

AZIR REZHA, N., MAKSOM, Z. & NAIM, C. 2014. Tackling design issues on elderly smartphone interface design using activity centered design approach. ARPN J. Eng. Appl. Sci, 9, 1190-1196. 

CASSIDY, P., MCCONNELL, N. & BOYCE, K. 2021. The older adult: Associated fire risks and current challenges for the development of future fire safety intervention strategies. Fire and materials, 45, 553-563. 

CHANG, J. J., HILDAYAH BINTI ZAHARI, N. S. & CHEW, Y. H. The Design of Social Media Mobile Application Interface for the Elderly. 
2018. IEEE, 104-108. 

DODD, C., ATHAUDA, R. & ADAM, M. 2017. Designing user interfaces for the elderly: a systematic literature review. 

FIRE GUARD. n.d. https://apps.apple.com/gb/app/fireguard/id1097475653 [Accessed]. 

GOOGLE NEST. n.d. Available: Available: https://play.google.com/store/apps/details?id=com.nest.android&hl=en_AU&gl=US [Accessed]. 

HOEHLE, H., ALJAFARI, R. & VENKATESH, V. 2016. Leveraging Microsoft׳s mobile usability guidelines: Conceptualizing and developing 
scales for mobile application usability. International journal studies of human-computer studies, 89, 35-53. 

JI, Y. G., PARK, J. H., LEE, C. & YUN, M. H. 2006. A Usability Checklist for the Usability Evaluation of Mobile Phone User Interface. International journal of human-computer interaction, 20, 207-231. 

KAREMAKER, M., TEN HOOR, G. A., HAGEN, R. R., VAN SCHIE, C. H. M., BOERSMA, K. & RUITER, R. A. C. 2021. Elderly about home fire 
safety: A qualitative study into home fire safety knowledge and behaviour. Fire safety journal, 124, 103391. 

LEUNG, R., MCGRENERE, J. & GRAF, P. 2011. Agerelated differences in the initial usability of mobile device icons. Behaviour & information technology, 30, 629-642. 

LI, Q. & LUXIMON, Y. 2020. Older adults' use of mobile device: usability challenges while navigating various interfaces. Behaviour & 
information technology, 39, 837-861. 

LORENZ, A. & OPPERMANN, R. 2009. Mobile health monitoring for the elderly: Designing for diversity. Pervasive and mobile computing, 5, 
478-495. 

NORMAN, D. A. 1995. The psychopathology of everyday things. Readings in Human–Computer Interaction. Elsevier.

PREEYANONT, S. 2017. User Interface on Smartphone for Elderly Users. International journal of automation and smart technology, 7, 147-155. 

RESTYANDITO, KURNIAWAN, E. & WIDAGDO, T. M. M. Mobile Menu Representation for Elderly. Cham: Springer International Publishing. 

SALMAN, H. M., WAN AHMAD, W. F. & SULAIMAN, S. 2022. A design framework of a smartphone user interface for elderly users. 
Universal access in the information society. 

SAPONARA, S., ELHANASHI, A. & GAGLIARDI, A. 2021. Real-time video fire/smoke detection based on CNN in antifire surveillance systems. 
Journal of real-time image processing, 18, 889-900. 

SNUG SAFE. n.d. Available: https://www.snugsafe.com/ [Accessed].

SNUG SAFETY. n.d. Available: https://play.google.com/store/apps/details?id=snugsafety.com.snugsafety&hl=en_AU&gl=US 
[Accessed]. 

SULAIMAN, S. & SOHAIMI, I. S. An investigation to obtain a simple mobile phone interface for older adults. 2010. IEEE, 1-4. 

YUSOF, M. F. M., ROMLI, N. & YUSOF, M. F. M. 2014. Design for elderly friendly: Mobile phone application and design that suitable for elderly. International Journal of Computer Applications, 95. 

ZIEFLE, M. & BAY, S. 2006. How to overcome disorientation in mobile phone menus: A comparison of two different types of navigation 
aids. Human-Computer Interaction, 21, 393-433.
