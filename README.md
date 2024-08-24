# SOSApp

SOSApp is a React Native mobile application designed to send emergency SOS messages, share the user's location, and record and upload video evidence to a cloud service. The app uses Firebase for authentication, Firestore for user data storage, and Twilio for sending SMS messages.

## Features

- **User Information Form**: Collects and stores user and guardian contact information.
- **Request Permissions**: Requests necessary permissions for camera, audio recording, and location access.
- **Send SOS**: Sends an SOS message with the user's current location to a guardian.
- **Record and Upload Video**: Records a video during an emergency and uploads it to Firebase Storage.
- **Share Video Link**: Sends the link to the recorded video via SMS using Twilio.

## Prerequisites

- Node.js and npm installed
- React Native CLI installed
- A Firebase project set up with Firestore and Storage
- Twilio account with an SMS-enabled phone number
- Android device or emulator

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/SOSApp.git
   cd SOSApp
