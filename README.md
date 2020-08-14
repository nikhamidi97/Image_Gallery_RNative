Name|Matric Number
----|------
Nik Hamidi Wan Hamat| 1712475
Umar Hakimi Zahabuddin|  1714851
Syed Muhammad Arif Sayed Ali |1718247

## TITLE : CLOUD GALLERY
### Introduction
    In this final project for movile application development course, we will develop an apps called Cloud Gallery. This apps allow user to take photo and stored it on our database. The app required user to register for them to have access to the cloud storage. User can used their own account to view other's photo that have been uploaded to the application. 

### Objective
    This project are aim to help us to explore on the creation of mobile app using online database and also help user to store their image to the cloud either for privacy or storage issues. To create a community that show interest in photography
### Features and functionalities
1. Register
   The most common feature for mobile application is register the id and password to login to our mobile application. We used firebase database to store the id and password
   of the users to be used
2. Login
    Login also is important to log into their own account of this application. we want to capture their interest and to store their own images.
3. Upload image from device
    Our mobile application can be used to upload user's own photo and they also can view other's photo through their account. We will store their photo in our database and call all the user's account to display the photo on the explore part.
4. Camera
    User can user our camera feature to capture the images that they like and upload it on our application to be stored
    
### Component and API
        1) import { NavigationContainer } from '@react-navigation/native';
            This component we used to track our screen. It can be used to moved to another specific screen that we need for our application
            
        2) import { createStackNavigator } from '@react-navigation/stack';
            It was used for transition wihtin our application between the screens.
            
        3) import React, { Component } from 'react';
            Common used when we are using jsx
            
        4) import {widthPercentageToDP as wp, heightPercentageToDP as hp} from 'react-native-responsive-screen';
            This component we used to specify the percentage of our width and height every view in our project. So the size of our view will be changed according to the mobile phone used
        
        5) import Icon from 'react-native-vector-icons/Ionicons';
            We used it for icon to be displayed
            
        6) import LinearGradient from 'react-native-linear-gradient';
            We want to make a gradient color for our specific background screen
            
        7) import { View, Text, StyleSheet,TextInput,TouchableOpacity, Btton, Alert, FlatList, ScrollView, StatusBar, Dimensions} from 'react-native';
            All of those are important component where we want to dispay our content. Stylesheet used to create the style of our specific content. Textinput is needed for user to key in their id, password, to search items and to register the account. While TouchableOpacity is used to create a touchable space for the user to click on it, for example we created button using touchableOpacity to moved to another screen. Button obviouly we used to move to another screen or create an alert using it. While Flatlist is used to render many items that we want to display on our application. Next, ScrollView is used to enble the scroll feature for user to view more content on the screen. We set the Statusbar of our apps. We get the screen height using the Dimensions.
            
        8) import auth from '@react-native-firebase/auth';
            Using this component, we can get authentication from our firebase for the user to log into their account.
            
        9) import * as Animatable from 'react-native-animatable';
            used to create screen animation for our splashscreen,login page screen and profile page.
            
        10) import { useTheme } from '@react-navigation/native';
        11) import MaterialIcons from 'react-native-vector-icons/MaterialIcons';
            This component also we used their library to import the icon 
            
        12) import { Card, Divider,IconButton} from 'react-native-paper';
        
        13) import { FAB } from 'react-native-paper';
            To created a floating button of our application. The button used for the camera feature where user can capture the images and upload it on our application
            
        14) import { createMaterialBottomTabNavigator} from '@react-navigation/material-bottom-tabs';
            We create our main pages using the bottom navigation where user can select Home, Search and Profile pages at the bottom bar.
### Sequence Diagram
![Sequence Diagram](/1.jpg)
### References
1. https://www.codeproject.com/Articles/1267698/How-to-Build-a-React-Native-Image-Gallery-Tutorial
2. https://guides.github.com/features/mastering-markdown/
3. https://github.com/react-native-community/react-native-image-picker
4. https://firebase.google.com/docs/auth/web/start
