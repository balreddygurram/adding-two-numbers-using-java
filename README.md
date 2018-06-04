# adding-two-numbers-using-java
import java.util.Scanner;
public class Addition{

     public static void main(String []args){
         Scanner sc=new Scanner(System.in);
         System.out.println("enter first number");
         int firstNumber=sc.nextInt();
         System.out.println("enter Second number");
         int secondNumber=sc.nextInt();
         int sum=firstNumber + secondNumber;
         
        System.out.println(sum);
     }
}

