!!!!!!IMPORTANT MESSAGE!!!!!!

*This is a first version of this app so there can be some bugs and I'm still working on this app

*This version is the first working version on this app (core features)

*You need to install mongoDB, mongoDBCompass and nodeJS on your PC to run this app! Also be sure that you can run this app on this addresses:
-Main app will be running at http://127.0.0.1:3000
-server will be running at http://127.0.0.1:3030

*More commits are on folder main for main app and server for server. I do this because I want to make able users to edit this two folders separately

1. Installation
a)Install mongodb and mongoDBCompass on your pc
b)Create db named:saveMoneyApp
c)Import to created db three collections from this folder:Expenses,Limits,users
d)Create new folder on your PC and copy folder main and server into this folder
e)Install nodeJS on your PC
f)Open created folders and in server folder type: node index.js in console to run local server it will be run on address 127.0.0.1 and port: 3030
g)Open main folder and type npm start in console
h) If you do everything correctly you will be able to see login menu you can test if everything is working type in login field admin and in login field admin if everything is ok you will be able to see main panel

2. Description
I created this app for fun and it may help users to control their expenses and save some money! This is the first version of this app so there can be some bugs and I'm still working on this app!

3. Usage
You need to log in to the app to see the main panel. If you don't have an account you can create a new one. After login/registration you will see main panel in which you will be able to see three main columns: Limits, Spend Money, Charts. If you click on limits you can set the new limit, set target (how much money you want to save at this limit), edit limit (it will increase your money by the value). After setting new limit you will need to choose limit expire time you can choose 1day 1 week and 1month after choosing one of the option you will create new limit and you at this moment you will be able to spend money, analyze your spend money data and in main panel you will see how much money left on this limit. When you click spend money you will be able to add a product that you buy you can set the name, cost and category. At this section if you add some products you will be able to see all yours expenses at this limit. In chart section you will be able to see all data collected in this running limit (limit data and expenses chart).

4. Technologies
I used to created this app mongoDB, ReactJS, JavaScript, React Router

Hope you will enjoy using this app!!