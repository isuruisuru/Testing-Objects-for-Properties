# From the JavaScript Course from freeCodeCamp

### This will be useful to you when you go through the course.

Sometimes it is useful to check if the property of a given object exists or not. We can use the `.hasOwnProperty(propname)` method of objects to determine if that object has the given property name. `.hasOwnProperty()` returns `true` or `false` if the property is found or not.

### Task
Modify the function `checkObj` to test if an object passed to the function (`obj`) contains a specific property (`checkProp`). If the property is found, return that property's value. If not, return `"Not Found"`.


## Code 

```JavaScript
function checkObj(obj, checkProp) {
  // Only change code below this line
  
  if (obj.hasOwnProperty(checkProp)) {
    return obj[checkProp];
  } else {
    return "Not Found";
  }

  // Only change code above this line
}
```

### Note
> You can creat objects in the parameter `obj` when running the function `checkObj`.
> For Example:
`checkObj({country: "Sri Lanka", fruit: "Orange", vehicle: "car"}, "fruit");`
