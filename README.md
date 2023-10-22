# Message-App
Hello, I am Nehal Singh currently pursuing Electronics Engineering from Indian Institute of Technology IIT (BHU), Varanasi.
### Project Documentation

## Key Features

User Authentication: Secure sign-in using email and password, as well as the convenience of Google Sign-In.
Group Chats: Create and manage group chats to facilitate collaboration and communication.
Video Calls: Conduct video calls with versatile features, including screen sharing and the option to raise a hand for participation.
Interactive Polls: Engage participants with real-time poll questions during video calls and conveniently download the results.
Meeting Notes: Take and share meeting notes with the help of a built-in rich text editor during video calls.
Seamless Communication: Continue group chats alongside video calls, ensuring uninterrupted conversations.
Admin Controls: Administrators have the authority to mute all participants and remove individuals as needed.
Attendance Management: Easily download an attendance list in CSV format for record-keeping.

## Technology Stack

Our platform is built using a modern technology stack to provide a robust and efficient user experience:

ReactJS: The core framework for building responsive and interactive user interfaces.
Bootstrap: A responsive design framework for a consistent and appealing UI.
Jitsi Meet: Our chosen video conferencing solution, known for easy integration and scalability.
ChatEngine: Facilitating real-time chat functionality within the application.
Firebase: Used for authentication, storage, and managing user data.

## Development Approach

Our development process adheres to agile methodology, emphasizing collaboration and flexibility throughout the project's lifecycle:

Project Design: The project began with a comprehensive design phase, during which we identified key features and explored available technology options.
Prototyping: We created early prototypes using various technologies, such as OpenVidu, WebRTC, and Jitsi Meet. After thorough evaluation, we selected Jitsi Meet for its ease of integration and ability to handle a large number of participants with minimal browser load.
Feature Expansion: We expanded the Jitsi Meet prototype to include additional features. ChatEngine was integrated for real-time communication, Firebase was employed for user authentication and data storage, and the user interface was enhanced. The innovative "Polls" feature was introduced for interactive participation.
Enhancing Communication: We integrated the chat feature into the video call component, transitioning from Jitsi Meet's chat to a more versatile group chat. Additionally, we introduced "Meeting Notes," enabling participants to collaboratively create and edit notes using a rich text editor during meetings.

This unique blend of features and technologies ensures an engaging and productive video conferencing experience for our users.

## Running this project!
* Before cloning the project make sure you have created a firebase project on Firebase Console

* To clone this repository run:
! $ git clone https://github.com/NehalSingh1618/Message-App.git 
* Next create a .env file in the root of the project directory, this is where you will put all your firebase config keys.
* Go to Firebase console and select the project you just created, Select Add App and select Web, follow the on-screen instructions until Firebase provides you with a config object, take each property of the provided object and fill these fields inside the .env file:
'''
markdown
 REACT_APP_API_KEY =
REACT_APP_AUTH_DOMAIN =
REACT_APP_DB_URL =
REACT_APP_PROJECT_ID =
REACT_APP_STORAGE_BUCKET =
REACT_APP_SENDER_ID =
REACT_APP_APP_ID =
REACT_APP_MEAS_ID =


## Start the Project:
''' npm start 

* Enjoy the App.
