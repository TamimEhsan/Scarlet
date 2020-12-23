# Scarlet

<img height="300" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/logo.jpg">

Scarlet is a car warehouse management system made with JavaFX and Java networking. This is the term project of Level-1 Term-2. 

NB. Due to covid pandemic our usual term project was cancelled and this easy version was given.

Full demo of the project can be found [Scarlet: A Car retailer simulating software using JavaFX and Socket Networking](https://youtu.be/8guI1ndLWDQ)

## Task assigned

We were to implement a model of a car buy,sell system.

The server has the data stored and will be used for communication between clients and server side login validation.

The viewer needs no login validation. But the manufacturer side will be validated from server.

The user can view cars in the showroom and buy them. The user can also search cars using different attributes. And the manufacturers can edit or delete existing car or add new car. Every update needs to be reflected on other users too. Every interaction should be done in javafx.

## Architecture 

The system is designed into two part: frontend and backend. The front end shows two type of behaviours: Manufacturer and user. The front end and backend is connected by socket.

- Frontend
  - Server
- Backend
  - Manufacturer
  - Buyer

### Design patterns

In this I used namely two pattern

- Singleton
- MVC (Model View Controller)

And wanted to use the observable pattern too. But at one point it seemed unnecessary as Java has Observable array doing what I need.

## Features

The main features of the project are

- Implementation of Java networking with TCP using socket
- Implementing server
- Multiple client
- JavaFX based gui designed with material theme
- Server side validation
- Auto update of data

### The UIs

#### Login

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/login.gif">

#### Data Show

<img height="200" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/listCell.jpg">

#### User consoles

The Menu

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/clientMenu.jpg">

Search car console

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/search.jpg">

Live search

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/liveSearch.gif">

#### Manufacturer Console

Manufacturer console

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/manufacturerConsole.jpg">

Add car console

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/addCar.jpg">

Validation of data

<img height="400" align='center' src="https://github.com/TamimEhsan/Scarlet/blob/master/Assets/validation.jpg">
