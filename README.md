# convert-element-to-react

Convert HTML DOM elements to React

`npm i --save convert-element-to-react`

### Usage

```js
import React from "react";
import ReactDOM from "react-dom";
import convertElementToReact from "convert-element-to-react";

const App = convertElementToReact(htmlElement);

ReactDOM.render(App, document.getElementById("app"));
```

### Originally based on https://github.com/shaaijs/html-element-to-react
