# Eloquent Javascript Reading Chapter 04

## Objects

### Accessing Object properties:

> When using a dot, the word after the dot is the literal name of the property. When using square brackets, the expression between the brackets is evaluated to get the property name. **Whereas value.x fetches the property of value named “x”, value[x] tries to evaluate the expression x and uses the result, converted to a string, as the property name.**

This is why you have to use the square bracket notation when passing a variable in order to access object properties.

## A few notable string methods

* In the case of strings .indexOf method can search for a string containing more than one character.

```javascript
console.log("one two three".indexOf("ee"));
```

* padStart method

```javascript
console.log(String(6).padStart(3, "0"));
// → 006
```

## JSON

JSON is a serialization of the data - conversion into a flat description. 

* All properties have to be surrounded by double quotes
* JSON.stringify and JSON.parse functions allow to convert data to and from this format.