# Basic Template

```html
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Plain TODO</title>
</head>
<body>
<div id="js-app" role="main">
    <form id="js-form">
        <input id="js-form-input" type="text" placeholder="What need to be done?">
        <input id="js-form-submit" type="submit" value="Add">
    </form>
    <ul id="js-todo-list">
        <li><input type="checkbox" class="todo"/>TODO</li>
    </ul>
</div>
</body>
</html>
````

## Data Flow


- View 
    - onLoad
    - Model#onChange
        - Update View


## component/element

- EventListener
- EventEmitter
- Array
    - push
    - splice
    - map
    - find
    - filter
    - forEach
- emit ... spread operator
- Map/Set?
- Function
    - call
    - bind or closure
- equability
- class
- ES module
- Build/Bundler tools
- Arrow Function
- default parameter
- DOM