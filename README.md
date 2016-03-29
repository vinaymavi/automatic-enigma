# automatic-enigma
This is collections of JavaScript Programming questions.

## JS Basics 
* How a Primitive type have .toString() or other functions?
* What is data type of 10 and 10.0 ?
* Why it is single threaded?
* When Single threaded how it working asynchronously?
* what is difference between == and ===?
* What is the out put of.
```javascript
   var obj = {a:10,b:20};
   console.log(""+obj);    
```

## Functions 

* Function is an Object in JS.
```javascript
   function fun(){};
   fun.myname="I am function"; 
```
* What is output?

```javascript
 var a = 20;
 function myFun(a){
    a =10;
 }
 myFun(a);
 console.log(a); 
```

* What is output?
   
```javascript
 var a = {key:20};
 function myFun(a){
    a.key =10;
 }
 
 myFun(a);
 console.log(a.key); 
```