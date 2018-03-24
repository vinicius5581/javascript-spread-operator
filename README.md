# javascript-spread-operator


## Combine arrays

```javascript
> arr1.push(...arr2);
> arr1.unshift(...arr2);

> var arr1 = ['two', 'three'];
> var arr2 = ['one', ...arr1, 'four', 'five'];
```

## Duplicate array

```
> const arr = [1, 2, 3];
> const doublearr = [...arr, ...arr];

>> [1, 2, 3, 1, 2, 3]
```

## Copy array

```javascript
const arr1 = [1, 2, 3];
const arr2 = [...arr1];
```

## Convert iterables to arrays

```javascript
>  [...new Map().set(true,'yes').set(false,'no')]


>> [[true: 'yes], [false, 'no]]
```

## Using `Math` functions

```javascript
> const numbers = [9, 4, 5, 1];
> Math.min(...numbers);

>> 1
```


## Convert string to character array

```javascript
> const str = "hello";
> const strChar = [...str];
> console.log(strChar);

>> ['h','e','l','l','o']
```


```javascript
doStuff(...condition ? [value] : [])
// same as:
(condition) ? doStuff(value) : doStuff();
```

## Destructuring
```javascript
> const {x, y, ...z} = {x: 1, y: 2, a: 3, b: 4};
> console.log(x);
> console.log(y);
> console.log(z);

>> 1
>> 2
>> {a: 3, b: 4}
```
