# javascript!

### variables

- `var b = true`: Boolean
- `var n = 5`: Number
- `var s = "hello"`: String
- `var a = [1, "hello", null]`: Array
- `var o = { key:"value", key2:42 }`: Object

### functions

```js
// function declaration (creating it)
function hello(arg){
    console.log(arg)
}
// function call
hello("print me")

// another way to declare a function
var funk = (arg) => {
    console.log(arg)
}

// as a member of a React class Component:
class Hello extends React.Component{
    funk = () => {
        console.log(this) // refers to "Hello"
    }
}

```

### objects

```js
// key/value pairs
var obj = {
    key:"value" // value must be a legit JS variable
}
// use dot notation to access a value:
obj.key
// destructuring:
var {key} = obj // now you can use the "key" variable
```

### arrays
```js
var arr = [1,2,"three",null]
// access by the index, (starting with 0):
arr[2] = "three"

//loop:
arr.map((item, index)=>{
    console.log(item, index)
})

// filter
arr.filter((item, index)=>{
    return typeof item === 'number' // return a condition that checks something for EACH item
})

// sort
arr.sort((a,b)=>{
    // return a negative numer, a positive number, or zero
    return a - b
})

//add an item to an array:
arr.push("new item")

// concatente two arrays:
arr.concat(arr2)

// take a sub-array
var arr2 = arr.splice(0,10)
```

### conditional statements
```js
var n = 5
if(n === 5){
    console.log("YAY ITS TRUE!")
}
// you can use >, <, !==
```
