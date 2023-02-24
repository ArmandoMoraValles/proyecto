# Declaration of primitive data types

In TS we need to declare the data type of a variable like in many other languages, this is very simple

**Numbers**
```
let myAge: number = 22;
myAge += 1;
console.log(myAge);//23
```
**Strings**
```
let myAge: number = 22;
myAge += 1;
console.log(myAge);//23
```
**Booleans**
``` 
let myBoolean: boolean = false;
myBoolean = true;
console.log(myBoolean);
```

In the case of placing a data inside a variable and the type of data declared in the variable does not match the type of data entered, we will have an error

```
let myName: string = 23 //This is bad
console.log(myName);
```
```
1 let myName: string = 23
      ~~~~~~

Found 1 error in primitiveDataTypes.ts:1
```

but if the code is compiled anyway, everything will be fine, this is because at the end of the day, node or the browsers will execute the JS code, so if we use TS we should not ignore the errors it throws but we can do it in some cases like this