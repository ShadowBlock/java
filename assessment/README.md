# ICS0014 JAVA TECHNOLOGIES - PRACTICAL ASSESSMENT
This assessment is for you to get overview on what have you learnt about Java so far and challenge yourself with solving
exercises. The exercises are meant to be solved individually, so please try to use your own knowledge. If you decide to
take the assessment together with your course mates, then please use this opportunity for discussion only and write your
own code.
## Exercises
Assessment consists of multiple parts of the exercise. Please complete all the parts!
The assessment is going to be about Cats, different breeds, cats' behavior and so on :).

## Part 1 - preparation

Create class Cat. We should be able to know cat's name, breed, fur color, eye color and favorite toys.
NB! Pay attention on how information about favourite toys can be stored in the program!
In addition, we need to know the name and the color of each toy.
Create some Main class that contains public static void main method to run the program.


## Part 2 - working with class instances

In your Main class, create a list of Cat instances. Each instance should be created using constructor.
Use System.out.println method to demonstrate printing the list of cats.
When printing Cat class's instances, we should see some readable information, e.g. {{name}} the Cat is {{breed}}, has {{fur color}} fur and {{eye color}} eyes.

Now you can choose what do you want to do of these options:

Add the list of favourite toys with readable information into the message above, so that printing Cat instance would also contain list of cat's favourite toys.
String representation for a toy in this case should look like {{toy name}}, {{toq color}} color.
OR

Your Cat class should have special method that returns String of list of toys
and each toy's string representation should look like {{toy name}} is {{cat name}}'s favourite toy. It has {{toy color}} color



## Part 3 - logic

In Main class, create class variable that represents list of possible cat names.
In Main class, create class variable that represents list of possible cat breeds.
In Main class, create class variable that represents list of possible cat fur colors.
In Main class, create class variable that represents list of possible cat eye colors.
In Main class, create class variable that represents list of possible toy names.
In Main class, create class variable that represents list of possible toy colors.
In Main class, create method that is capable to generate a list of cats, randomly choosing all the necessary properties.
NB! I encourage you to use some AI tools to generate all this data :).

From next steps, you can choose if you want to create some methods in Cat class or in Main class. The most important thing is that these
methods are callable and code is executable.

Create such method that gets a list of cats as argument and returns a Map with cats grouped by eye color.
Create such method that gets a list of cats as argument and returns a Map with cats grouped by breed.
Create such method that gets a list of cats and toy's name as arguments, and returns a List with cats that have the toy with given name among their favourite toys.
Create such method that gets a list of cats as argument and returns a List of all the toys that are given cats' favourites. NB! The return list should not contain duplicates!
Create such method that gets a list of cats, name of the property and desired value of the property to be filtered by as arguments,
and returns a List of the cats that are filtered by given property by given property value.
NB! If you find the last step complicated, then show your skills in creating multiple methods and each method should be responsible for each property to be filtered by.
