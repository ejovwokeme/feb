# **scribe**
*The only way to take notes in a modern world*

* Scribe is a web application that allows you to take both voice and text notes.
* The notes are separated by topics.
* Each user has an account.

### **Installation**
* Ensure you have Nodejs installed.
* ```cd``` into the directory containing the ```package.json``` file and run ```npm install``` to install all the dependencies.
* Make a directory called ```certs```, ```cd``` into it and run ```openssl req -x509 -newkey rsa:4096 -keyout key.pem -out cert.pem -days 365```
* Put the passphrase of the private key generated in the ```.env``` file.
* Also provide a *session secret* in the ```.env``` file. It can be anything...any random string.
* Make a directory called ```db```. Inside it, add two sub-directories with the names ```voice_notes``` and ```text_notes```

### **Start up**
* To start the app, ```cd``` into the directory with the app and run ```npm run start```
* In your browser, go to ```https://localhost:8080```

![alt text](./git_images/scribe_login.png)
![alt text](./git_images/scribe_signup.png)
![alt text](./git_images/scribe_home.png)
![alt text](./git_images/scribe_navbar.png)
![alt text](./git_images/scribe_topic.png)
![alt text](./git_images/scribe_addtext.png)
![alt text](./git_images/scribe_addvoice.png)
