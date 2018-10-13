# Lifeline-Natural_Disaster_Management_App
An app for providing critical info regarding people in "danger" to the rescuing authorities during natural disaster. 

# About the app
The purpose of this app is to assist rescue workers in the event of a natural disaster to increase efficiency of rescue operations and minimize casualties. Generally in such events, the workers scan the buildings floor by floor searching for people. This app shall ask the trapped people about information such as their location, health condition, condition of the place etc. and relay it to the respective rescue workers which shall be instrumental in managing the rescue operation. This will also solve multiple call handling problems and will provide accurate data to the rescue workers.

# How does it work 
The home screen of the app shall have 2 options - "I am a rescue worker" and "I am a victim". On tapping at the first i.e. rescue option, there shall be an option to type the location of the area hit. Upon receiving the location, a signal will be sent to all the phones having this app in that area which shall trigger a speech assistant. This speech assistant can also be opened using the second option i.e. the victim option. 

**Reason for 2 options** - If the user's phone is accessible to the user, he/she can tap the button and speak/type the required information. But sometimes, the phone may be a few metres away and self triggering shall be very helpful then. 

**Reason for speech** - As mentioned before, if the phone is a few metres away, speech is the only way of getting information. Also, typing might be difficult in that mental state and speaking is more convenient in such a situation.

The speech assistant shall ask a specific set of questions ->
1. What type of calamity are you facing?
2. What is your location? (Building name, floor No., Room type - kitchen, bedroom etc.) 
3. Are you able to move? 
4. Is there anyone else along with you? 
5. What is the current condition of your location? (Fire spread, building structure etc.) 

Then the user will answer all these questions by voice, which shall be converted to text, processed for keywords and this data will be provided to the rescue workers in a structured manner to facilitate rescue operations.


## Datasets and sensors used
There is a requirement of speech keyword classification in the version of this app. This can be done by two ways: 

1. Speech to text classification -> Text Keyword Classification
2. Speech Keyword Classification

There has been a lot of research going on which classification is better. Still, it is difficult to decide which one to use. Considering both of these methods as an option, here are some datasets and sensors that would be used for speech keyword classification:

**For the first approach:**
1. (Speech Keyword Dataset)[https://ai.googleblog.com/2017/08/launching-speech-commands-dataset.html]
2. (Phonetics dataset)[http://archive.phonetics.ucla.edu/]

Similar datasets are required for the second dataset. Also, the sensors that would be used are GPS, speech microphone, speaker,etc. 
