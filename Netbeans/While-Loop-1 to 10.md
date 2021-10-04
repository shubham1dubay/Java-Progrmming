import java.util.Scanner;
public class WhileLop 
{
 public static void main(String args[])
 {
     int num;
     System.out.println("Enter the number");
     Scanner sc=new Scanner(System.in);
     num=sc.nextInt();
     while(num>=2)
     {
         System.out.println(num);
         num=num-2;
     }
 }
}
