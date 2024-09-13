/*
 * Write a simple program to calculator
 */

import java.util.Scanner;
public class cal {
    public static void main(String[] args) {
        Scanner in=new Scanner(System.in);

        int num1,num2;
        System.out.println("Enter two numbers:");
        num1=in.nextInt();
        num2=in.nextInt();

        System.out.println("Enetr + for additon\n"+
                            "Enter - for subtraction\n"+
                            "Enter * for multip;ication\n"+
                            "Enter / for division"
        );
        char op;
        op=in.next().charAt(0);
        if(op=='+'){
            System.out.println(num1+num2);
        }
        else if(op=='-'){
            System.out.println(num1-num2);
        }
        else if(op=='*'){
            System.out.println(num1*num2);
        }
        else if(op=='/'){
            System.out.println(num1/num2);
        }
        else{
            System.out.println("Wrong choose");
        }
    }
    
}
# calulator
This is my second project
