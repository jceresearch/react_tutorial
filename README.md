# react_tutorial
learning absolutely basics in react

npx create-react-app demo_app

cd my-app

Change App.js to:

import React, { Component } from 'react';

class App extends Component {
  render() {
    return (
      <div className="App">
        <h1>Hello World!</h1>
      </div>
    );
  }
}

export default App;


Then use in the terminal 
npm start