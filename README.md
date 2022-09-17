# Blockchain-application-for-Electronic-Health-Records-EHR-
# Guidelines to setup and run the project:
To setup and run the project, please follow the following guidelines.
## Set up metamask
1- Please install the metamask extension on your google chrome browser. If you already have the extension installed, please delete it and renstall it in order to avoid having problems in running the app.

2- Once metamask extension has been installed successfully, click get started

3- Click on import wallet

4- Click "I agree"

5- Enter the following secret phrase: myth like bonus scare over problem client lizard pioneer submit female collect

6- Enter any password you desire and confirm it

7- Click agree and confirm

8- Click on Etherm Monnait in the top right corner of the screen. A dropdown menu will appear. Click on add network and enter the following:

    a) Network name: Private Network

    b) New RPC URL: http://ec2-18-118-132-239.us-east-2.compute.amazonaws.com:8545/

    c) Chain ID: 1337

    d) Currency Symbol: ETH
    
    Note: Ignore the warning that you will get when you enter the chain id. Just click save to save the network settings
9- Click on the the circular icon in the top right corner (next to the private network button) and click on create account. Keep doing so until you have **10 accounts**

## Run the application
1- Open the project folder in microsoft visual studio code

2- Install the node modules in the contracts and frontend folders

3- Run in the terminal of visual studio the following:
    
    #cd Frontend
    #npm i react-app-rewired
    #npm start
    
    Note: the app should run properly. However, there is a chance it might not run right way. Ex. it might tell you create-react-app does not exist. IN THAT CASE npm i anything that is missing (i.e. npm i create-react-app). AFTER THAT THE APP SHOULD RUN PROPERLY.

4- Once the app is launched and the login page is rendered, log into  **one of the 10 clinic accounts**. The username is accX (where X is an integer from 1 to 10) and the password is 13456.

5- Metamask will launch once you click login and will ask you to connect to the correct metamask account. **Make sure you are connected to the correct metamask account (i.e. if you are logging in with acc6 as your username then you should be connected to metamask account 6)**
    
6- If you log out of the clinic account and log in to a **different** account, **make sure you click on metamask and change the meta mask account that you're connected to**

