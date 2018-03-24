# javascript-spread-operator


## Duplicate array

```
> const arr = [1, 2, 3];
> const doublearr = [...arr, ...arr];

>> [1, 2, 3, 1, 2, 3]
```

## Convert iterables to arrays

```javascript
>  [...new Map().set(true,'yes').set(false,'no')]


>> [[true: 'yes], [false, 'no]]
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
