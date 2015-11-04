# Java code to generate a Random uppercase letter
  In this problem I need to write a project that displays a random uppercase letter using the Math.random() method. 
This code will display the  number between 65 to 90 corresponds to the uppercase letter between ‘A’ to ‘Z’ .
In this case I also use the if statement and random method to realize order, 
and then use print statements to display the result.  

## Code 

```java

public class Listing_4.16 {
	public static void main(String[] args) {
		
		int startingValue = 65;  //'A' is 65
		int endingValue = 90-startingValue + 1; /* 'Z' is 90,
		and we wanted to cover the range, so we added 1 more to ensure
		we would cover A through Z .
		*/
		/* From page 122 a + Math.random() * b gives us a random
		 *  number between a and a+ b*/
		int randomNumber;/*Make s new variable
		 and then fill it with a random number that is between or 
		 starting value and ending value. Then print it out.
		 */
		
		randomNumber = (int)(startingValue + Math.random() * endingValue);
		//System.out.println(randomNumber); // debugging statement
		System.out.println("The random number is : " + randomNumber);
		
		char letter = (char)randomNumber; // recast the number to s letter 
		System.out.println("The uppercase letter is: " + letter);   // Print it out
		

	}

}
```


### Console
```java
The random number is : 90
The uppercase letter is: Z
```


#### Command prompt
```
     Git is the open source distributed version control system that facilitates GitHub activities on your drive or desktop. First, starting a project in Eclipse, second Start a local repository, in this case, you should follow the list such as:
1.	Open the command prompt,  : Start >search for ‘ cmd’ > Strike Enter. 
2. Change drives to my thumb drive using our drive letter a colon “ : ”. E:\User\LAB>E:     
E:>
2.	 Use dir to see what is on the directory E:>dir 
3.	Use cd add your workplace, like E:\ Computer Science I\ Listing 4_16 project>
( In here ,I had some trouble to happened, when I use the git command, it display the result is” ‘ git ’ is not recognized as an internal or external command, operable program or batch file” then I can’t continue to use git to finish my work what I want to.)
4.	Set up my local repository.
5.	Use git add . to add all my files.

Thirdly, connect our local repository to our global repository.
Just follow:
1.	Open a browser of choice
2.	Go to Github and sign in: https://github.com/login
Add a new repository then  follow the instruction to …or create a new repository on the command line
echo # markdown-practice2 >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:yuanyuan01/markdown-practice2.git
git push -u origin master
…or push an existing repository from the command line
git remote add origin git@github.com:yuanyuan01/markdown-practice2.git
git push -u origin master
…or import code from another repository
You can initialize this repository with code from a Subversion, Mercurial, or TFS project.
Last time, use add, commit, and push to finished it.
```
##### Summary
```
In this problem I also should be using if statements and random method to finished my java program.
First at all, I was think about how to set up the random method what I want to use for.AS you know, 
I do like’ int number =50 + (int)(Math.random() * 50)’; then I can limit the number between 50 to 99 
it’s facilitate testing the code as soon as possible. 
The most difficult is running if statement to realize the number corresponds to the suppercase letter. 
```
