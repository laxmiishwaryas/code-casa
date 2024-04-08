import java.util.*;
import java.util.Random;
import java.util.Random;
import java.util.Scanner;

class Numberguessinggame {
    public static void guessthenumber() {
        Scanner in = new Scanner(System.in);
        Random rand = new Random();
        int generatingnumber = rand.nextInt(100) + 1;
        System.out.println("Hi! welcome to the number guessing game");
        int guess, i;
        int attempts = 10;
        int score = 100; // Initial score

        for (i = 0; i < attempts; i++) {
            System.out.println("enter your guessed number between 1 to 100");
            guess = in.nextInt();
            if (generatingnumber == guess) {
                System.out.println("Congratulations! you won the game");
                System.out.println("Your score is: " + score);
                break;
            } else if (guess < generatingnumber) {
                System.out.println("your guess is too low try again!");
                score -= 10; 
            } else {
                System.out.println("your guess is too high");
                score -= 10; 
            }
        }
        if (i == attempts) {
            System.out.println("Your number of guesses is over");
            System.out.println("The actual number is " + generatingnumber);
            System.out.println("Your score is: " + score);
        }
    }

    public static void main(String arg[]) {
        Numberguessinggame n = new Numberguessinggame();
        n.guessthenumber();
    }
}
