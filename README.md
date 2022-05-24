# rc-22

_**JSX**_ 
ES2016/2015JS code -> Babel -> ES5 JS
Simple jsx to javascript convesion
```jsx
const App = () => {
  return <div> Mochiron Desu </div>
  }
```
Equivalent pure javascript code 
```javascript
const App = () => {
  return React.createElement("div", null, "Mochiron Desu");
  }
```
HTML
```html
<div style="background-color:red;"></div>
```
Javascript
```jsx
<div style={{backgroundColor:'red'}}></div>
``` 
