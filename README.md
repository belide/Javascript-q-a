# Javascript-q-a
Javascript Interview Questions &amp; Answers

### 1) Comparing strings
```javascript
  var a = 'a';
  var b = 'b';
  if (a < b) { // true
    console.log(a + ' is less than ' + b);
  } else if (a > b) {
    console.log(a + ' is greater than ' + b);
  } else {
    console.log(a + ' and ' + b + ' are equal.');
  }
```
### 2) String Primitives and String Object
  ```javascript
  var s_prim = 'foo';
	var s_obj = new String(s_prim);
	console.log(typeof s_prim); // Logs "string"
	console.log(typeof s_obj);  // Logs "object"
  
  var s1 = '2 + 2';             // creates a string primitive
  var s2 = new String('2 + 2'); // creates a String object
  console.log(eval(s1));        // returns the number 4
  console.log(eval(s2));        // returns the string "2 + 2"  
  ```
 
 ### 3) String Length
  ```javascript
  var x = 'Mozilla';
  var empty = '';

  console.log('Mozilla is ' + x.length + ' code units long');
  /* "Mozilla is 7 code units long" */

  console.log('The empty string has a length of ' + empty.length);
  /* "The empty string has a length of 0" */
   ```
    
### 4) sub() and sup() methods
   ```javascript
  var superText = 'superscript'; 
  var subText = 'subscript'; 

  console.log('This is what a ' + superText.sup() + ' looks like.'); 
  // This is what a <sup>superscript</sup> looks like 

  console.log('This is what a ' + subText.sub() + ' looks like.'); 
  // This is what a <sub>subscript</sub> looks like.
  ```
### 5) slice() method
 ```javascript
var str1 = 'The morning is upon us.', // the length of str1 is 23.
    str2 = str1.slice(1, 8),
    str3 = str1.slice(4, -2),
    str4 = str1.slice(12),
    str5 = str1.slice(30);
console.log(str2); // OUTPUT: he morn
console.log(str3); // OUTPUT: morning is upon u
console.log(str4); // OUTPUT: is upon us.
console.log(str5); // OUTPUT: "
  ```
### 6) substring() method
 ```javascript
   var anyString = 'Mozilla';

// Displays 'Moz'
console.log(anyString.substring(0, 3));
console.log(anyString.substring(3, 0));

// Displays 'lla'
console.log(anyString.substring(4, 7));
console.log(anyString.substring(4));
console.log(anyString.substring(7, 4));
  ```
