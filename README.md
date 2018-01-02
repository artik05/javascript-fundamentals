# javascript-fundamentals

1> Intro
2> Variales
3> Operator
4> Function & objects
5> Array 
6> Loops
7> Inbuilt methods
8> Error

#Intro

Client side vs server side scripting lang

client means browser - Javascript, VBscript, 

server means backend machine - IIS , Tomcet (Java, C# , NodeJS, Ruby & rail)

initially this was used for validations - user input , showing errors

At Present - there are many javascrpt framework like jquey, angularjs, backbonejs, extjs, nodejs, emberjs 

these frameworks procide inbuilt components, tools , adv features which help to devlop webapplicaiton easily.

- more complex apps
- UI rich
- Good Performamnce
- Easy to maintain


# Javascript Basics

Testing - open crome -> developer tools -> console


##Variables
Variables - declared using var keywork.

var x, a , b;
var x = 10;
var x = a + b;

>a
error - Uncaught ReferenceError: a is not defined


> var a;
undefined  // this is valid value

> var a = 10;
>a;
10 // 10 is stored in variable a

> a + b;
NAN  - Not a number

>b = 10;

> a+b 
20


# Inbuilt Types 

boolean
number
string
object

to check type of any variable we use 

> typeOf(varName)
> a = "abc"
> typeof(a)
> "string"


??? Difference Between Undefined and Null

##Array

It defined as collection of similar entity or types

var a = [];
var a = [20, 3];

var arr = [10 , 20 ,30];
undefined
arr

var arr = [{ a : 'sdf' } , { b : 20}]; // to store object

common array methods

length 
foreach
filter
slice
some
push
pop
sort
reverse
find
findIndex
join



#operators

++
--
&&
!
!=
!==
==
===
> , <
>= , <=
 ? :
 ||

var a = b || 20; if b is defined then a = b otherwise a = 20;

if(a == b) 
if(a != b)
if(a == 10 && b == 20)

if(a >= 10 && b <= 20)

var c =  a == b ? 20 : 30;


#condition

If

if else

Switch


#Loops

For
While
do-while


##Function & objects

function functionNmae(){

}

funciton calulate(a, b){
  return a + b;
}

var functionNmae = function(){

};

functionNmae();


(function(){


});

## Objects - culy brackets , store things in key value pair

Parent of everything is Object;

var obj = {};
var obj = { name : 'abc' };

var objc = { method : function(){}}

var a = { name : 'sdf', cal : function(a , b){ return a + b}};

> a.cal();
NaN
> a.cal(10);
NaN
> a.cal(10,20);
30

