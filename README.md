# Time-TaskCA2
CA2
package odd.even;

import java.util.Scanner;

/**
 *
 * @author laissantos
 */
public class OddEven {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
       
    int num;  //only numbers 
     System.out.println("Please, enter an integer number: ");
     //The input provided by user is stored in num
    Scanner input = new Scanner(System.in);
    num = input.nextInt();
    //if number is divisible by 2, it's an even number
    //else odd number
   try{
    if(num%2==0)
      System.out.println("You entered a even number.");
    else
      System.out.println("You entered a odd number."); 
   }catch(Exception e) {
       System.out.println("This is not a valid number");
    }
    }   
}
