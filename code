package java_projects;
import java.util.Scanner;
public class number_guess_game {
	public static void main(String[] args) {
		Scanner sc= new Scanner(System.in);
		int computer_number = (int)(Math.random() * 100) + 1; 
		int user_number=0;
		int count=0;
		System.out.println("Guess a number between 1 and 100:");
			while(user_number != computer_number) {
				user_number=sc.nextInt();
				if(user_number<1 || user_number>100) {
					System.out.println("Your guess is invalid. \n Enter a valid number between 0 to 100.");
					continue;
				}
				count++;
				if(user_number == computer_number) {
					System.out.println("Correct guess. \n Total guesses = "+count);
					}
				else if(user_number > computer_number) {
					System.out.println("Your guess is too High,Try Again. \n Total guesses = "+count);
				}
				else {
					System.out.println("Your guess is too Low,Try Again. \n Total guesses = "+count);
				}
		}
	}
}



/*
Math.random() gives a random decimal between 0.0 and 1.0.
Multiplying by 100 gives a value between 0.0 and 99.999...
(int) converts it to an integer between 0 and 99.
Adding +1 gives a final result from 1 to 100.
*/
