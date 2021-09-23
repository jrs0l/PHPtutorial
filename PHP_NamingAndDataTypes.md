# PLP
Programming Language Project (PHP)


Naming variables in languages is one of the most important aspects of successful coding. Being able to find names for variables can be more difficult
than you would expect at times. This step is important because anyone can choose a name, but if that name does not support the variable it can be confusing and misleading.
Important naming is key because you are not going to be the obly one reading your code. Proper and functional naming will help other developers be able to understand your
code properly. Every language has a set of rules than are implied with there langauge. For PHP, these are the following.

  - A variable must start with the $ sign, followed by the name of the variable
  - A variables is assigned with the = operator, with the variable on the left-hand side and the expression to be evaluated on the right.
  - A variable name must start with a letter or the underscore character
  - A variable name cannot start with a number
  - A variable name can only contain alpha-numeric characters and underscores (A-z, 0-9, and _ )
  - Variable names are case-sensitive ($age and $AGE are two different variables)
  - Variables used before they are assigned have default values.
  - Variables in PHP do not have intrinsic types - a variable does not know in advance whether it will be used to store a number or a string of characters.

These rules are very important to follow when it comes to your code whether it is due to compiler/interpeter restrictions or if it is the standard across the board. PHP
forces these variable rules in order for the program to be ran successfully at the time of interpetation.

Languages when they are typed are described as static or dynamic. Static and dynamic data types are explained like so;
"The key difference between the two is that with static type checking, the type of variable is known at compile time
(it checks the type of variable before running) while with dynamic type checking, the type of variable is known at runtime
(it checks the type of variable while executing)" https://medium.com/@katalenelson/static-type-checking-and-dynamic-type-checking-134dd269118
PHP is conisdered to be a dynamically typed language because it checks the variables while the code is being executed.

The next data type were going to look at is weak and strong typed languages. Weak and strong type languages refer to whether a variable can change its type after it's defined.
Stong typed languages will have all type errors detected at the time of compiling/ when it is interpreted while weakly typed will run until it breaks. PHP is considered to be 
weakly typed language.




![vsphp](https://user-images.githubusercontent.com/91085020/134563742-9dd4185b-d13e-405f-b418-4baa4259de5f.png)

![x5local](https://user-images.githubusercontent.com/91085020/134563756-bf00a516-7b6a-4984-ba82-91f7dab71d65.png)
 
 If you see here, you will see that while running php, the example of x = '5' + 6 will print an error and not be compiled. To have php
 compile a sum of two numbers, you would want to type something like this 
 "<?php
    $x=5; 
    $y=6;
    $z=$x+$y;  
    echo "Sum: ",$z;    
?>:

when you check your work on a web browser you will find that you will get a response of "Sum11"
 

Sources: https://flowframework.readthedocs.io/en/stable/TheDefinitiveGuide/PartV/CodingGuideLines/PHP.html
https://www.greycampus.com/codelabs/php/variables
https://www.w3schools.com/php/php_variables_scope.asp
https://www.sitepoint.com/typing-versus-dynamic-typing/
https://stitcher.io/blog/what-php-can-be
