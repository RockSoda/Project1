# Project1
# Starter For Firebase, React Native, Redux Applications With 100% Of Code In Common Between IOS And Android, with built In Authentication, Crud Example And Form Validation.

## Features

- Authentication
- CRUD ( Create, Read, Update, Delete )
- Form validation

## Preview

<img src="previewgif.gif" width="300">

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
