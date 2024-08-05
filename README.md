import java.sql.SQLOutput;
import java.util.Scanner;

public class calculater {
    public static void main(String[] args){


        Scanner num1 = new Scanner(System.in);
        System.out.println("Enter the first number :- ");
        float a = num1.nextFloat();
        Scanner num2 = new Scanner(System.in );
        System.out.println("Enter the  second number ");
        float b = num2.nextFloat();
        System.out.println(" Enter your opration option ");
        System.out.println(" Enter 1 for SUM ");
        System.out.println(" Enter 2 for SUB ");
        System.out.println(" Enter 3 for MULTIPLY ");
        System.out.println(" Enter 4 for DIVISION ");
        float c,d,e,f;
        Scanner num3 = new Scanner(System.in);
        int OP = num3.nextInt();
        int action = OP;

 switch ( action) {

     case 1:
     c = a + b;
         System.out.println(" YOUR SUM IS OF BOTH NUMBER:- " +c);
         break;
     case 2:
     d = a - b;
         System.out.println(" YOUR SUB IS OF BOTH NUMBER:-" +d);
         break;
     case 3:
     e = a * b;
         System.out.println("  YOUR MULTIPLY IS OF BOTH NUMBER:- " +e);
         break;
     case 4:
     f = a/b;
         System.out.println("  YOUR DIVISION IS OF BOTH NUMBER:- " +f );
         break;
     default:
         System.out.println("PLEASE ENTER THE VALID OPTION");
         break;
 }

    }
}
