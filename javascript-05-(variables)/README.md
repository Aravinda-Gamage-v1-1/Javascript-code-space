### Variables
Variables are containers for storing data
Javascript variables can be declared in 4 ways.
* Automatically
* Using var
* Using let
* Using const

#### Automatically
```
x = 5;
y = 6;
z = x + y;
```

#### Using var
```
var x = 5;
var y = 6;
var z = x + y;
```

The var keyword should only be used in code written for older browsers.

#### Using let
```
let x = 5;
let y = 6;
let z = x + y;
```

#### Using const
```
const x = 5; 
const y = 6;
const z = x + y;
```

These are const values can't be changed.
Always use const if the type should not be changed (Arrays and Objects)

#### Mixed 
```
const a = 5;
const b = 10;
let total = a + b;
```

