# Factorial.java
//Factorial..............
import java.util.Scanner;
public class Factorial {
    public static void main(String[] args) {
        Scanner hl=new Scanner(System.in);
        int fact=1;
        System.out.print("Enter the num. :");
        int n=hl.nextInt();
        for(int i=1; i<=n; i++){
            fact= fact*i;
             
        }
       System.out.println("Fact.of"+n+"="+fact);
    }
}
