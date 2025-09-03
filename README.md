Basic calculator using switch case
import java.util.*;
public class Calculator {
    public static void main(String args[]){
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter First Number : ");
        int a=sc.nextInt();
        System.out.println("Enter Second Number : ");
        int b=sc.nextInt();
        System.out.println("Enter Operator : ");
        char ch=sc.next().charAt(0);
        System.out.println("Your Answer is : ");
        switch(ch){
            case '+':
            System.out.println(a+b);
            break;
            case '-':
            System.out.println(a-b);
            break;
            case '*':
            System.out.println(a*b);
            break;
            case '/':
            System.out.println(a/b);
        }
    }
}
