### Q1.Difference between “ == “ and “ === “ operators.
    Ans1. Both are comparison operator. both return boolean value.
    == isuse for loose type checking and === use for strct type checking because === use to check data and their datatype
### Q2.What are the differences between var, let and const?
    Ans2. var,let and const are the keywords, introduce in ES6.
    Major difference between the are :

    1. var support hoisting where as let and const create temporal dead zone.
    2. var support redeclaration and re-initialization of variable where as let and const not support redeclaration and initialization
    3.var support global and function scope where as let and const support global and block scope.
### Q3.What is hoisting?
    Ans. HOisting is a default behaviour of javascript where variable and function declaration move to the top of the scope before code execution.
    Ex: console.log(a)
        var a=10//variable a ishoisted 
### Q4.What is a Temporal Dead Zone?
    Ans. when we trying to access the variable before its declaration with let and const keyword then we get a reference error.This scenario is known as tdz. 
    console.log(a)//can't access a   
    let a=10; 
### Q5. What is meant by first class functions
    Ans. Assining a function to a variable is known as first class function.
    Ex: 
    let p=function sum(){
        let a=2;
        let b=3;
        console.log("sum = ", a+b);
    }       
     p()//function call
### Q6. What are pure functions?
    Ans. Pure function are those function that gives the same result if the same argument are passed in the function.
    Ex:
    function sum(a,b){
        return a+b;
    }
    console.log(sum(2,4));
    console.log(sum(5,4));
    console.log(sum(2,7));
### Q7. What is execution context    
    Ans.

