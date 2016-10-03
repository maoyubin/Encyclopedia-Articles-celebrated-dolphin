# Number.prototype.toString()

*The toString() method returns a string representing the specified Number object.*  

The Number object overrides the toString() method of the Object object; it does not inherit Object.prototype.toString(). For Number objects, the toString() method returns a string representation of the object in the specified radix.

## Syntax  

`numObj.toString([radix])`  

### Values  

If the radix is not specified, the preferred radix is assumed to be 10 and
When the numObj is not a whole number, the 'dot' sign is used to separate the decimal places.

```
var count = 10;
console.log(count.toString());    // displays '10'
console.log((17).toString());     // displays '17'
console.log((17.2).toString());   // displays '17.2'
```  

The toString() method parses its first argument, and attempts to return a string representation in the specified radix (base). For radixes above 10, the letters of the alphabet indicate numerals greater than 9. For example, for hexadecimal numbers (base 16), a through f are used.  

```
var x = 6;
console.log(x.toString(2));       // displays '110'
console.log((254).toString(16));  // displays 'fe'
```

If the numObj is negative, the sign is preserved. This is the case even if the radix is 2; the string returned is the positive binary representation of the numObj preceded by a - sign, not the two's complement of the numObj.  

```
console.log((-10).toString(2));   // displays '-1010'
console.log((-0xff).toString(2)); // displays '-11111111'
```  


## Browser Support   

| Chrome | Firefox  | IE | Opera | Safari | Android |  
|---|:--:|:--:|:----:|:---:|:---:|  
| Yes | Yes | Yes |Yes |Yes |Yes |

