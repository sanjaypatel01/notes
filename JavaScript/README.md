## What is EcmaScript?

Ecmascript is a standard on which javascript is based.

##Ways to execute Javascript
1. Browser console
2. NodeJs
3. In HTML using <javascript>.


Java Script Variables

Dynamically typed language - can change assigned value from one type to another type in runtime. like int to string.

<code>
let a =67;
console.log(a);

a = "sanjay";

console.log(a);
</code>

He it will work and print 67 and sanjay.

### Rules for choosing variable names
- variables are case sensitive
- variable must begin with $, underscore or a letter.
- variable can also have digits but can not be at the beginning
- Reserved key words can't be used.

### Video 3: var let vs const

var was used pre es6, should avoid using this.
- var is globally scoped while let & const are block scoped
- var can be updated & re-declared within its scope.
- let can be updated but not redeclared
- const can neither be updated nor be re-declared.
- var variables are initialized with undefined where as let and const variable are not initialized.
- const must be initialized during declaration unlike let and var.

https://replit.com/@SanjayPatel9/003varconstlet


### Video 4: Data Types
  NULL
  NUMBER
  SYMBOL
  STRING
  BOOLEAN
  BIGINT
  UNDEFINED
  
  Non Primitive data type - Object
  
  typeof any data type
  let a = 12;
  console.log(typeof a);
  
  const dic = {
  a:"Apple",
  b:"Bat"
  }
  
  console.log (dic.b)
  console.log(dic[b])
  Both will print same.
  
  
Exponential operator 
4**3 = 64

  
  If variables are int and string Type different.
===.   > equal value and type
  
!==.  > not equal value or not equal type
  
  let a = 6;
  let b = "6"
  
  Try to print 
  a === b >  false
  a !=== b > true
  
  
  Logical operators
  &&  > AND
  ||   > OR
  !    > Not 
  
  Bitwise Operators
  & , |
  
  Comments
  Use either // Single line 
  or /*   */   Multiline comment
  
  
  Conditional Operators
  if ..
  if .. else
  if .. else if .. else
  
  
Alert - to give some message
  alert('you are not logged in');
  
Prompt -- To get input from user
  prompt("Enter your age : ");
 Prompt value will always be string
  typeof a
  
  
  Conversion from String to Number 
  int a = Number.parseInt(str);
  
  
  Ternary Operator - ? :
  
  ;   -- is optional at the end of line
  
  Loops
  for loop
  for(let a=0; a < 5; a++){
                     ---
  }
                     
 for in loop
   let obj = {
   "Sanjay" : 90,
   "Ajay" : 78

   }
  //here obj need not be iterable
  for(let a in obj) {                 
    console.log(a);
     console.log(obj[a])
  }
                   
//here obj need be iterable Array
  for(let a of "sasnjay") {                 
    console.log(a);
 }
 
                     
 let has block scope
 var has global scope
                     
### Functions
 Declaration                    
function = functionName(a, b) {
   return ...                  
}
  
Execution
functionName(5, 6)
                     
Arrow function
const sum = (a, b) {
return a+b
}
                     
var marks = {
   "a" : 90,
   "b" : 70
}
                     
for(int i=0; i < Object.keys(marks).length; i++) {
  console.log(Object.keys(marks)[i] + "" + marks[Object.keys(marks)[i]])
}
Same as above 
for(let key : marks) {
  console.log(key + " : " + marks[key])
}
  
  
  ### Strings
  
  let str = "sanjay"
  console.log (str[0])
  here str is also consider as array
  
  Tempplate literals (Modern Java Script) - using backtick `. This is also string interpolation
  let b1 = "sanjay";
  let b2 = "kumar"
  
  let sentence = ` ${b1} 's last name is ${b2}`
  console.log(sentence)
  
  
  Escape sequence String
  let fruit = 'ban\'ana'
  
  \n --- New line
  \r --- Carriage return
  \t --- Tab
  
  ### String Methods
  
  let name='sanjay'
  console.log(name.length)
  length is a property
  console.log(name.toUpperCase())
  console.log(name.toLowerCase())
  
  console.log(name.slice(2, 4))
  startIndex included
  endIndex excluded
  
  console.log(name.slice(2);
  Starting index to end

  let name = "Sanjay Kumar"
  name.replace('Kumar', 'Patel')
  if first string exists then it will be replaced with the 2nd one.
  
  
                     
