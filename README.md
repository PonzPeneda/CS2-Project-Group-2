# Project title: Canteen Ordering App
## Problem:
Everyday, around 90 students end up having to skip lunch due to the long transaction process done in the canteen. The long lines made by this issue causes starvation and tiredness. 

## Description: 
Its an app that allows you to order in the canteen from anywhere (pre-order). You can check your balance, orders,          and when your order is ready for pickup or not.
## Objectives:
* Allow students to view canteen stocks, their balance, and reserve an order for breakfast, lunch and dinner
* Lessen the cases of cutting classes by allowing students to order in class
* Shorten the line by allowing students to order thru the web app rather than ordering f2f
## Features: 
Buy food, drinks or snacks, check canteen card balance, cash in using GCash picture awaiting canteen's response,              check when food is ready, check what foods are available in the canteen
## Requirements:
Fastapi, uvicorn, sqlalchemy, pydantic (backend/server requirements)
Flutter Software Framework that uses dart language (client side/app) so that we can make an app for PC, Mac,                   IOS, and Android.
## How to run:
Using Flutter framework, make the app in Dart langauge and build the app using `flutter build apk` then test it on a phone.
## Sample Interaction:
A student orders -> app sends http request to the server -> server responds by first checking if balance is sufficient then subtracting total balance by order cost -> canteen personnel sees the order and makes the food and marks the order as ready -> student grabs food from the canteen
## Contributers:
Jia Katrine A. Negros

Vic Giohann C. Nuevo

Ponce Jerone C. Peñeda
