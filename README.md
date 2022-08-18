# LoveJava.java
A short grasp on numbers

   import java.util.Scanner;

   public class LoveJava
   {
      public static void main(String[] args)
      {
         Scanner keyboard = new Scanner (System.in);
         int valid = 0;
         int number = 0;
         while  (valid == 0)
         {
            System.out.println("Please enter a number from 10 to 24: ");
            number = keyboard.nextInt(); 
            System.out.println(" " + number + " ");
            if  (number >= 10 && number <=24) 
            {
               System.out.println("That is a valid number.");
               valid++;
            }
            else
            System.out.print("This number is not a valid number. ") ;
         }
      }
   }
