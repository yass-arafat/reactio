Don't forgot to check the WIKI pages for more deatails about Project.

# React

## Project setup:
- To create react app run in terminal
 `npx create-react-app project_name`. here npx is a package runner which gets installed when npm gets installed.

## Component:
Two types:
1) **Stateless Functional Component** - they are normal JavaScript functions which returns htm snippet.
- They can receive an object of properties and return HTML(JSX)
e.g. 
```
function getName(props){
return <h1>Hello, {props.name}</h1>;
}
```
2) **Stateful Class Component** - Class should extend React.Component class and must need to return render() method. 
- they can also optinally receive an object of properties and return HTML(JSX)
- Apart from the props, it can also maintain a private **state** for it's self where one can store variable, list etc. for creating dom
e.g.
```
class Hello extends React.Component{
 render() {
  return <h1>Hello, {this.props.name}</h1>
 }
}
```

## JSX
- JavaScript XML to write XML like code for elements and components.
- It will have a tag name, attributes and children.

## Destructuring
- Destructuring is a convenient way to extract multiple keys from an object or array simultaneously and assign the values to local variables.
- A good link about destructuring https://medium.com/@lcriswell/destructuring-props-in-react-b1c295005ce0
