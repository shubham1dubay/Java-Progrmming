import java.util.Scanner;
public class WhileProdectofdigit
{
    public static void main(String args[])
 {
     int num,prod=1,rem;
     System.out.println("Enter the number");
     Scanner sc=new Scanner(System.in);
     num=sc.nextInt();
     while(num>0)
     {
         rem=num%10;
         prod*=rem;
         num/=10;
     }
     System.out.println("Sum digit num  "+prod);
 }
    
}
