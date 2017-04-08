# Tinyurl
It aims to give a shorter url in emoji format with information regarding times of clicks, locations, history track from user's input. It is inspired by Google URL Shortener. 
# How to run it in you local

### Clone project to your local

`git clone https://github.com/ruihanzou/Tinyurl.git`

### To install requried pakage, go into app folder
	1. cd app
	2. npm install

### Go back to the parent folder at which docker-compose.yml is put after finishing the pakage installation

	cd ..

### Run the following command when your docker is up. 

	docker-compose up --build

<!--It takes a while if this is your first run.--> 

If your local server crashed due to the "MongoError," please make sure you're connecting to mlab. If not, you can configure the connection settings in server.js by using your own MONGODB URI. 

<!---->

You should able to see this sentence from your temrinal when the server is up. 

	Server started at port 3000


### When your local server is up, you should see the home page by entering the following URI in your address bar of your browser
	localhost

### Home Page 
![alt text](https://cloud.githubusercontent.com/assets/2655537/24829877/245fe47a-1c40-11e7-95e9-d3f8246eecf9.png "Home Page")

### USER MANAGEMENT
 You have to sign up first to use the user management feature
(![alt text]https://cloud.githubusercontent.com/assets/2655537/24831419/c4bb1b06-1c5e-11e7-9146-51d58e176a3e.png "User Management screenshot")
