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
