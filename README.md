# Jared's Projects

## Concession Stand Cash Register/App
* **Technology:** [Framework7](https://framework7.io/), Javascript, HTML. Intended to be saved as a web app or ran via Apacahe Cordova.  
* **Inspiration:** Created to make my life easier when working at my college's concession stands.  
* **Info:** A simple app that lets the user add items to a order and automatically calculate the price. Then let the user input a payment amount and calculate the change due. The main screen shows all available items and is fully reprogrammable from within the app. The list of items is generated from a JSON array defined in the settings of the app.  
* **Video:** https://www.youtube.com/watch?v=w_GrgGA4acs


Main screen                |  Pay screen
:-------------------------:|:-------------------------:
The main interface of the app, allows the user to select items as a customer is ordering and see the price.  |  Allows the user to input the amount of cash being used to pay. The app will show the change due and the denominations of cash to give back.
![](https://i.imgur.com/avPrQzt.png)  |  ![](https://i.imgur.com/kC38tFu.png)

___

## Monopoly Bank App
* **Technology:** [Framework7](https://framework7.io/), WebSockets (NodeJS WS), Javascript, HTML. Intended to be accessed from a mobile browser, but can also be saved as a webapp.  
* **Inspiration:** Created because no one in my family trusts anyone to be the banker in Monopoly. The version of Monopoly we have uses Millions and Thousands of dollars.  
* **Info:** A fun app with the sole purpose of being the Monopoly banker. All players login and allows users to deposit and withdraw money from the bank. It also allows users to transfer money to another player via a dropdown menu of all players currently in the game. Every transaction made is shown publicly in the Transaction History.  
* **Video:** https://www.youtube.com/watch?v=qQaTFDGpn_o


Main screen                |  Amount Input screen
:-------------------------:|:-------------------------:
The main screen shows your current balance at the top of the screen and provides the 3 main functions of the bank.  |  This screen pops up anytime an amount needs to be entered. It has a convenient 10% button for when you need to pay your 10% taxes in game.
![](https://i.imgur.com/TqrYH0g.png)  |  ![](https://i.imgur.com/oZsYlWx.png)

___

## DIY Internet Connected Garage Door
* **Technology:** Hardware: Arduino, RaspberryPi, 5V Relay, Proximity sensor. Software: ExpressJS, C (Arduino)  
* **Inspiration:** I bought an Arduino starter kit and this was my first real project after learning how to blink an LED. The hardest part of this project was trying to take apart the garage door remote without breaking it.  
* **Info:** This was a project just for me to start out with on the Arduino. It exposes 2 API endpoints `getGarageStatus` & `toggleGarage`. I later modified it to provide exact progress of the garage door opening and closing (Using the proximity sensor)  


App                |  Hardware
:-------------------------:|:-------------------------:
Super simple app, realistically it would be better being compatiable with HomeKit.   |  Super simple hardware too. 5V relay controlled by the Arduino can trigger the button on the disassembled garage door remote.
![](https://i.imgur.com/XGU0KEQ.png)  |  <img src="https://i.imgur.com/zzhcCzJ.jpg" width="75%">

___

## School Grade Notifier
* **Technology:** [iNowAPI](https://github.com/jdf221/iNowAPI) (Made by me), NodeJS
* **Inspiration:** Created for fun and also so I wouldn't have to constatly check my grades until a teacher put an grade in.  
* **Info:** The main part of this project is the iNowAPI that I made. It works by using Puppeteer to load the school's grade website and extract the grades of assignments.  


Text messages                |  iNowAPI
:-------------------------:|:-------------------------:
![](https://i.imgur.com/PW8tuZj.png)  |  ![](https://i.imgur.com/fuDfLiH.png)

___

## College Schedule Utilities
* **Technology:** [ICS.js](https://github.com/nwcell/ics.js/) (Calendar file generator), [docxtemplater](https://docxtemplater.com/) (Word document templating in JS), Javascript Chrome Extension  
* **Inspiration:** By the 2nd semester of college I was already tired of manually adding my classes to my calendar. So I made a quick Chrome extension that parses the schedule webpage and downloads a .ics calendar file.  
* **Info:** Over time I added multiple features to the extension. The 3 features it has now: Class Calendar generator, Class Binder cover sheet generator, and a calendar generator that takes the college's academic calendar and lets me add it to my calendar easily. (Exam days and college deadlines)

