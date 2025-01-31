
# Java Email Client App

A simple Java Email Client App using **Swing** and **java.mail** classes.


## Screenshots

![App Screenshot]()
![image](https://github.com/user-attachments/assets/1903be72-50f1-48e2-a208-9ff3636ac3cf)

![Screenshot 2025-01-31 104406](https://github.com/user-attachments/assets/ca4b5191-cc26-4c23-95b8-44d21b80f84b)


## About the Project
This project is a beginner attempt at creating a Email Client App to read and compose emails from the users email inbox. Includes small but necessary features such as attaching files to composed emails, for better usability. This project is written exclusively in Java in order to grow my Java development skills. 

Created and inspired from Robert Johns project found here: [project tutorial](https://hackr.io/blog/how-to-build-a-java-email-client-app)


## Features

- Login and Authentication
- Fetch Emails from Users Inbox
- Navigate/Read Emails from Inbox
- Compose/Send Emails - with the ability to attach files from users computer
- Refresh Inbox for Current Emails

## Project Structure

```bash
📂 Project Root
├── 📂 .idea/artifacts              # Intellij artifacts/jar file
│   ├── JavaEmailClientApp_jar.xml   # Main application file jar file
├── 📂 lib      # Included dependencies
│   ├── jakarta.activation.jar       # jakarta github lib
│   ├── javax.mail.jar               # java.mail dependencies
├── 📂 src      # Source code
│   ├── AttachmentChooser.java       # Attachment Chooser -> file attachment class
│   ├── EmailClientGUI.java          # GUI Swing file -> executable file (Main.java)
│   ├── EmailReceiver.java           # Email Receiver - inbox fetcher class
│   ├── EmailSender.java             # Email Sender - email compose class
│   ├── EmailSessionManager.java     # java.mail session & properties class
```

    
## Run Locally

Clone the project

```bash
  git clone https://github.com/CARay1502/JavaEmailClientApp
```

Go to the project directory

```bash
  cd ../JavaEmailClientApp
```

Make sure dependecies are installed/included

```bash
  cd ../lib
```
- jakarta.activation.jar
- javax.mail.jar

Run the Project
```bash
  cd ../.idea/artifacts
  java -jar JavaEmailClientApp.jar
```
You can run either:
- **EmailClientApp_jar.xml**  Compiled application file w/ dependecies
- **EmailClientGUI.java**     Executable file (Main.java)


