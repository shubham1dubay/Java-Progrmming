import java.util.Scanner;
public class WhileSumDigit
{
 public static void main(String args[])
 {
     int num,sum=0,rem;
     System.out.println("Enter the number");
     Scanner sc=new Scanner(System.in);
     num=sc.nextInt();
     while(num>0)
     {
         rem=num%10;
         sum+=rem;
         num/=10;
     }
     System.out.println("Sum digit num  "+sum);
 }
}
