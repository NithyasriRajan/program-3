# program-3
import java.util.Scanner;
public class BiggestNumber
 
public static void main (String[]args)
  {
    int m,n,o;
    Scanner sc=new Scanner(System.in);
    System.out.println(" Enter the first number:");
    x=sc.nextInt();
    System.out.println("Enter the second number:");
    y=sc.nextInt();
    System.out.println("Enter the third number:");
    z=sc.nextInt();
   if(m>n&&m>o)
   {
     System.out.println("Largest number is:"+m);
   }
   else if(n>m&&n>o)
   {
     System.out.println("Largest number is:"+n);
   }
   else
   {
     System.out.println("Largest number is:"+o);
   }
 }
}
