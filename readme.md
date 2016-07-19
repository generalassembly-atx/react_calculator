# React Calculator 

Tonight you will be building a Calculator with React.

### Set Up
You have been provided with a static html page `calc.html` that already includes babel and react. You simply need to add your react code inside the script tags in the file and open in the browser.

### Steps

- Start by using a React example to render a component on the page:
```js
class HelloMessage extends React.Component {
  render() {
    return (<div>Hello {this.props.name}</div>);
  }
};

ReactDOM.render(<HelloMessage name="John" />, document.getElementById('container'));
```
- Next, modify the code to render a Calculator component and move the static html into the render method.
- 

### Bonus
