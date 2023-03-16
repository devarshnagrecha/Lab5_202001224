# Lab5_202001224

## IT314 - Software Engineering
### Lab 5 - Static Analysis




### Github repo : https://github.com/ndleah/python-mini-project.git

### Tool used : Pylint

## File 1 : 

![image](https://user-images.githubusercontent.com/75675815/225571980-7737092c-9cea-47fc-87e3-df0a4619691c.png)

## Code rating : 4.23 / 10

## Errors : 

1. Trailing-whitespace : Occurs when there is whitespace between the end of a line and the newline.
2. Superfluous-parens : When a single item in parentheses follows an if, for, or other keyword.
3. Missing-module-docstring : Occurs when a module has no docstring. Empty modules do not require a docstring.
4. Missing-function-docstring :  Missing function or method docstring occurs when a function or method has no docstring. 
5. Redefined-outer-name : Occurs when a variable’s name hides a name defined in the outer scope.
6. No-else-return : Occurs when there is unnecessary else after return
7. Inconsistent-return-statements : Either all return statements in a function should return an expression, or none of them should. If this rule is violated, error occurs
8. Unidiomatic-typecheck : Occurs when web use type() instead of isinstance() for a typecheck. 

## File 2 :

![image](https://user-images.githubusercontent.com/75675815/225576931-eb69a623-9f56-44d1-9ec7-c00a985e14ee.png)

## Code rating : 1.68 / 10

## Errors : 

1. Wildcard-import : This is a bad practice because it clutters namespace with unneeded modules, packages, variables, etc. Moreover, it takes time to load them too.
2. Import-error : Occurs when pylint has been unable to import a module.
3. Missing-function-docstring :  Missing function or method docstring occurs when a function or method has no docstring.
4. Invalid-name : Occurs when the name doesn’t conform to naming rules associated to its type (constant, variable, class…).
5. Unused-wildcard-import : Used  when an imported module or variable is not used from a 'from X import *' style import.
6. Unused-variable : Occurs  when a variable is defined but not used.


## File 3 :

![image](https://user-images.githubusercontent.com/75675815/225579342-e37bf00a-71b6-41ab-90e0-a0c1898449cd.png)

## Code rating : 9.29 / 10

## Errors :

1. Line-too-long : Occurs when a line is longer than a given number of characters.
2. Missing-module-docstring : Occurs when a module has no docstring. Empty modules do not require a docstring.
3. Invalid-name : Occurs when the name doesn’t conform to naming rules associated to its type (constant, variable, class…).
