# JAVASCRIPT 
## 1.What is JavaScript?
###
JavaScript is a scripting language that enables you to create dynamically updating content, control multimedia, animate images, and pretty much everything else
###
## 2.Variables and Types
###
let userAge;

userAge=23;

var username="dhanavidhya";

console.log(userAge,username);
###
## 3.Comments in JavaScript
###
/*this is a function to calculate the sum of two numbers*/
function add(a,b)
{
    console.log(a+b);
}
###
## 4.Operations
###
let num1=25;

let num2=45;

console.log(num1+num2);

console.log(num1-num2);

console.log(num1*num2);

console.log(num1/num2);
###
## 5.Data Types
###
let num=20;

let str="name";

let bo=true;

const cars=["sabb","volvo","bmw"];
 
 ###
 ## 6.Functions in JavaScript
 ###
 function greetuser(name)
 {
    return "HELLO"+name;
 }
 let s=greetuser("priya");
 console.log.(s);
 ###
 ## 7.if Else in JavaScript
 ###
 let temp=25;
 if(temp>30)
 console.log("temp is greater than 30");
 else
 console.log("temp is lesser than 30");
 ###
## 8.for loop
###
for (let i=1;i<=5;i++)
{
    console.log(i);
}
###
## 9.Explain the difference between loose equality (==) and strict equality (===) with examples.

###
The equality (==) operator checks whether its two operands are equal, returning a Boolean result. Unlike the strict equality operator, it attempts to convert and compare operands that are of different types

const a = true;
const b = 'true';

console.log(a == b)
//output is true

const a = true;
const b = 'true';

console.log(a === b)
//output is false


