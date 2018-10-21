# Project1

## Features

- Authentication
- CRUD ( Create, Read, Update, Delete )
- Form validation

## Preview

<img src="01.png" width="300">
<img src="02.png" width="300">
<img src="03.png" width="300">
<img src="04.png" width="300">
<img src="05.png" width="300">
<img src="06.png" width="300">
<img src="07.png" width="300">
<img src="08.png" width="300">
<img src="09.png" width="300">


## Getting started

### Clone the Project

### npm install dependencies

````
npm install
````

## Firebase

### Create firebase app

### Add rules to firebase database

In firebase console navigate to, Database -> Rules and add following code snippet.

````
{
  "rules": {
    "users": {
      "$uid": {
        ".read": "$uid === auth.uid",
        ".write": "$uid === auth.uid"
      }
    }
  }
}
````

## Application

## IOS

````
react-native run-ios
````
