This is Fulan's first git project!
google homepage- it gives me the chance to know exactly what i have catched from previous course

java

methods
slice
substring
substr
replace // case-sensitive, replace(/example/i,"item")
toUppercase
concat()
trim()
padstart
padend

charAt
charCodeAt
string[]


      Property access might be a little unpredictable:

       It makes strings look like arrays (but they are not)
       If no character is found, [ ] returns undefined, while charAt() returns an empty string.
       It is read only. str[0] = "A" gives no error (but does not work!)

string.split()
-----------------------------------------------------------------------------
let a = 0;
alert( Boolean(a) ); // false
let b = "0";
alert( Boolean(b) ); // true
alert(a == b); // true!

alert( null === undefined ); // false
alert( null == undefined ); // true

null/undefined are converted to numbers: null becomes 0, while undefined becomes NaN.
alert( null > 0 );  // (1) false
alert( null == 0 ); // (2) false
alert( null >= 0 ); // (3) true

------------------------------------------------------------------------------
regular expressions
https://www.youtube.com/playlist?list=PL4cUxeGkcC9g6m_6Sld9Q4jzqdqHd2HiD

----------------------------------------
dev tools
https://developer.chrome.com/docs/devtools/
