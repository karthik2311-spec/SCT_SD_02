import java.util.Scanner;
import java.util.Random;

public class randomnumber 
{
    public static void main(String[] args) 
    {
        Scanner sc = new Scanner(System.in);
        Random random = new Random();

         System.out.println("Enter the minimum number: ");
        int min = sc.nextInt();

        System.out.println("Enter the maximum number: ");
        int max = sc.nextInt();

         int numberToGuess = random.nextInt(max - min + 1) + min;
         int userGuess = 0;
         int attempts = 0;

         System.out.println("Welcome to the Number Guessing Game! ");
        System.out.println("I have chosen a number between " + min + " and " + max + ".");
        System.out.println("Can you guess it?");

        while(userGuess != numberToGuess)
        {
            System.out.print("Enter your guess: ");
            userGuess = sc.nextInt();
            attempts++;

            if(userGuess < numberToGuess)
            {
                System.out.println("Too low! Try again.");
            }
            else if(userGuess > numberToGuess)
            {
                System.out.println("Too high! Try again.");
            }
            else
            {
                System.out.println("Congrats you guessed the number "+ numberToGuess + " in " + attempts + " attempts!");
            }
        }
        sc.close();
    }
}
