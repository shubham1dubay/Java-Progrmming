import java.util.Scanner;
class fh
{
    public int Sum(int a,int b)
    {
        return a+b;
    }
    public int Sum(int a,int b,int c)
    {
        return a+b+c;
    }
    public int Sum(int a,int b,int c,int d)
    {
        return a+b+c+d;
    }
}
public class MethodOverloding 
{
 public static void main(String args[])
 {
     int num1,num2,num3;
     Scanner sc=new Scanner(System.in);
     System.out.println("Enter first number");
     num1=sc.nextInt();
     System.out.println("Enter secound number");
     num2=sc.nextInt();
     System.out.println("Enter thired number");
     num3=sc.nextInt();
     fh ab=new fh();
     int x=ab.Sum(num3, num3, num3, num3);
     System.out.println(x);
         
 }
}
