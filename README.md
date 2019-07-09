# hello-world
Just another repository

import java.util.Scanner;
import javax.swing.JOptionPane;

public class BasicCal {

    public static void main(String[]args){
    
    int num1;
    int num2;
    String operation;
    
    Scanner input = new Scanner(System.in);
    
    System.out.println("Enter First Integer");
    num1 = input.nextInt();
    
    System.out.pritnln("Enter Second Integer");
    num2 = input.nextInt();
    
    Scanner op = new Scanner(System.in);
    
    System.out.println("Enter Desired Operaion0r");
    operation = op.next();
    
    if(operation =="+");
    {
    System.out.println("Equals" + (num1 + num2));
    }
    
    if(operation =="-");
    {
    System.out.println("Equals" + (num1 + num2));
    }
    
   if(operation =="*");
   {
   System.out.println("Equals" + (num1 * num2));
   }
   
   
   if(operation =="/");
   {
   System.out.println("Equals" + (num1 / num2));
   }
   
   }
   }
