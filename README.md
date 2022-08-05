# React-Native-101

expo
#####
rnfe

React
#####
create-react-app newapp
Cd newapp
Npm start

React-Native
#####
expo init AwesomeProject
cd AwesomeProject
npm start # you can also use: expo start


Class
#####
import React, { Component } from 'react';
import { Text, View } from 'react-native';

class HelloWorldApp extends Component {
  render() {
    return (
      <View style={{
          flex: 1,
          justifyContent: "center",
          alignItems: "center"
        }}>
        <Text>Hello, world!</Text>
      </View>
    );
  }
}

export default HelloWorldApp;


Function
#####
import React from 'react';
import { Text, View } from 'react-native';

const HelloWorldApp = () => {
  return (
    <View style={{
      flex: 1,
      justifyContent: 'center',
      alignItems: 'center'
    }}>
      <Text>Hello, world!</Text>
    </View>
  );
}

export default HelloWorldApp;

Start
#####
npm install -g expo-cli
expo init AwesomeProject
cd AwesomeProject
npm start 

Redux
#####
yarn add @reduxjs/toolkit
yarn add react-redux

TailWind
#####
yarn add npm install tailwind-react-native-classnames
<Text style={[tw`text-red-500 p-10`, styles.text]}>HomeScreen</Text>



