# Inputs
// User Inputs

import java.util.Scanner;

public class Input {
    
    public static void main(String[] args) {
        String line;
        String name;
        Scanner in = new Scanner(System.in);
        
        System.out.print("Hi! What is your name?");
        name = in.nextLine();
        System.out.println("Hi " + name + " How was your day?");
        line = in.nextLine();
        System.out.print("That's good to hear!");
        line = in.nextLine();
        System.out.println("Goodnight!");
    }
}
                    
                 
