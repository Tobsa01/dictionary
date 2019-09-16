###### **React App**

### General Information

React is a framework made by facebook.
It simplifies the Web Frontend development
React is seperated in React Hooks and the "normal React"
React is a single side application

# React Hooks
    * works with functions
    * is the way which React/Facebook wants to go

# Normal React
    * works with classes
    * inhirets from classes

### Work Flow React

React Manipulates the HTML DOM renderer
Each Time something changes the React.Dom-render rerenders the whole side (as default)
thats called React lifecycle and crash sometimes with other frameworks especially when it manipulates the HTML DOM too
For this u can manipulate the lifecycle and tell react what have to be instanced first
when it doesn#t rerender all you can save a lot of calculation time 
But only needed if you work with big tables

### How to create a React App

First of all You need nodeJs 
make a new folder and direct to it with a console

>npm install create-react-app [app name]

to start the react app use this command

>npm start

there are many option for React when starting like clarifying the port (in default 3000)

### Frameworks which work good with react

    * react-redux (handling of states)
    * jest (for testing but for snapshot use react test renderer)
    * enzyme (to simulate changes on specific components and proof the output)
    * storybook (with this  you dont need to rerender the whole side storybook can render some components)
        * console addon
        * action addon
        * knobs addon
        * notes addon
    * RSAA (for making easy backend request) 
    * react router (for making url) 