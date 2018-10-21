# Project1

## Features

- Authentication
- CRUD ( Create, Read, Update, Delete )
- Form validation

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
