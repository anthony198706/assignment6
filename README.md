# assignment6
#Guessing game; 1 Attempt; Java

package ProgrammingExcercises;
import java.util.Random;
import java.util.Scanner;

　
　
public class HighLow {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		Random random = new Random();
		int Answer = random.nextInt(100);
		int numAttempts;
		int guess;
		Scanner input = new Scanner(System.in);
		
		System.out.println("I'm thinking of a number between 1-100.  Try to guess it");
		guess = input.nextInt();
		
		if (guess< Answer){
			System.out.println("Sorry, you are too low. I was thinking of " + Answer);	
		}
	
		else if (guess> Answer){
			System.out.println("Sorry, you are too high. I was thinking of " + Answer);		
		}
	
		else if (guess == Answer){
			System.out.println("You guessed it! What are the odds?!!");	
		
		
		}
	}

}
