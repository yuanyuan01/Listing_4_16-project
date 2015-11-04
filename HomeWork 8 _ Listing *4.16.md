# Java code to generate a Random uppercase letter

## Introduction
In this problem I need to write a project that displays a random uppercase letter using the Math.random() method. 
This code will display the  number between 65 to 90 corresponds to the uppercase letter between ‘A’ to ‘Z’ .
In this case I also use the if statement and random method to realize order, 
and then use print statements to display the result.  

## Project Outline
```java
//Declaring variables
// use special statement
```


## References & Literature
*  liang,Y. Daniel. *Introduction to JAVA Programming: Comprehensive Version. * 10th ed. n.p : Pearson, 201.print.
 
## Java Code
```java
public class Listing_4_16 {

	public static void main(String[] args) {
		// Using the Math.random() method to display the number
		int number =50 + (int)(Math.random() * 50);
		// Display a random number
        System.out.println(" The random number is: " + number);
        
	   //Check the number is available
		if(number <= 90 && number >=65){
			int i = number;
			char c =(char)i;
			//Display the random uppercase letter
			System.out.println("The uppercase letter is: " + c  );
		}
			
			else
			{ 
				// Tell user this number is no available in this case 
				System.out.println("This number is an invalid. ");
			
		}
	}
	}
```


## Console Output
```
The random number is: 66
The uppercase letter is: B
```

## Command Prompt
```
1. Open Eclipse and start new project
	a. may need to change to your workspace
2. Go to Github and start a new repository.

3. Use the command prompt to make the connections.


a. Navigate to the correct location. Looking for src and bin folders.
+Move to the E: drive:

C:\Users\LAB>E:

*dir* shows what is in the directory.
```
## Summary
```In this problem I also should be using if statements and random method to finished my java program. First at all, I was think about how to set up the random method what I want to use for.AS you know, I do like’ int number =50 + (int)(Math.random() * 50)’; then I can limit the number between 50 to 99 it’s facilitate testing the code as soon as possible. The most difficult is running if statement to realize the number corresponds to the suppercase letter. ``
