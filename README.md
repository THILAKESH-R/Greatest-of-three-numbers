/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package greatest.of.three.number;
import java.util.Scanner;
/**
 *
 * @author cmd
 */
public class GreatestOfThreeNumber {

    /**
     * @param args the command line arguments
     */
    public static void main(String[] args) {
        int x,y,z;
    Scanner s=new Scanner(System.in);
    System.out.print("Enter the first number:");
    x=s.nextInt();
    System.out.print("Enter the second number:");
    y=s.nextInt();
    System.out.print("Enter the third number:");
    z=s.nextInt();
    if(x>y&&x>z)
    { 
      System.out.println("Largest number is"+x);
    }
    else if(y>x&&y>z)
    {
      System.out.println("Largest number is"+y);
    }
    else 
    { 
      System.out.println("Largest number is"+z);
        // TODO code application logic here
    }
    
}
