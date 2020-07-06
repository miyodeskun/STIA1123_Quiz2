# STIA1123_Quiz2

## Question 1
```
The ouput is:
Meow. I am a Cat. My name is Kurre
Woof. I am a Dog. My name is Vilma
Meow. I am a Cat. My name is Bamse
```
## Question 2
It means "many forms", and it occurs when we have many classes that are related to each other by inheritance.

## Question 3
In the program, the Cat and Dog were stored instances in the array of Animal (parent class). This is upcasting because of the child classes were cating to their parent class.

## Question 4
introduceYourself() method were never called because Cat & Dog class have override the method.

## Question 5
```
The ouput is:
Meow. I am a Cat. My name is Kurre
Morr. I am an Animal
Meow. I am a Cat. My name is Bamse
```

## Question 6
The name stored for the instances of Cat and Dog is inside the Animal class as a public String.

# Question 7
1. Declare an Animal array with an int variable (for count in the loop)
2. Initialize the array with size of class; 3.
3. Intialize Cat & Dog objects inside the Animal array.
4. Make a loop and inside it call the introduceYourself() method from each object inside the array.
- The counter will be increment by 1 and will stop untill the reached the length of the array.

## Question 8
Array works with some number of slots, each of which holds an individual item.

## Question 9
For loop is more appropriate loop statement.
```
for ( int i = 0; i < allAnimals.length; i++){
  allAnimals[i].introduceYourself();
}

