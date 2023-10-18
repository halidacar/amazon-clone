### Amazon-clone
Amazon clone application with React Native and mongoDB

# Create

  - npx create-expo-app <appName>

# Dependencies

  - npm add body-parser express mongoose jsonwebtoken no
  demailer nodemon
  - npm install @react-navigation/native-stack
  - npm install @react-navigation/native
  - npx expo install react-native-screens react-native-safe-area-context
  - npm install @react-navigation/bottom-tabs
  - npm i react-native-image-slider-box
  - npm add axios

# Scripts
  ```  "start": "nodemon index.js",``` (in package.json folder)
  -  after that in terminal go api folder and (npm start) for start mongodb

# Run
- expo start
------------------------------------------------------------

- ip adress: 0.0.0.0/0 for access anywhere

--------------------------------------------------------------

> [!NOTE]

> in the LoginScreen.js and RegisterScreen.js folder
 
```axios.post("http://localhost:8000/login", user)``` -> change the localhost to your pc ip adress

--------------------------------------------------------------
[!NOTE-2]
 In api folder:
``` .connect("mongodb+srv://userID:password@cluster0.tf88se9.mongodb.net/",```

Replace the username and password of the project you created in mongodb



> [!NOTE-2]

```
 const transporter = nodemailer.createTransport({
    //configure the email service with
    service: "gmail",
    auth: {
      user: "Type the email address you sent the email to.",
      pass: "Type the email app password from get the gmail security",
    },
  });
```
