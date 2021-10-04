import java.util.Scanner;
public class LcmLoop 
{
    public static void main(String args[])
    {
        int num1,num2,gcd;
        Scanner sc=new Scanner(System.in);
        System.out.println("Enter first number");
        num1=sc.nextInt();
        System.out.println("Enter secound number");
        num2=sc.nextInt();
        System.out.println("Enter gcd number");
        gcd=sc.nextInt();
        for(int a = 1; a <= num1 && a <= num2; ++a)
      {
         if(num1 % a == 0 && num2 % a == 0)
         {
            gcd = a;
         }
      }
      int lcm = (num1 * num2) / gcd;
      System.out.println("LCM of " + num1 + " and " + num2 + " is " + lcm + ".");
        
    }
}
