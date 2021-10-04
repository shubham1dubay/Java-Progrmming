import java.util.Scanner;
class Adder
{
    public int sum(int a,int b)
    {
        return a+b;
    }
    public int sum(int a,int b,int c)
    {
        return a+b+c;
    }
    public int sum(int a,int b,int c,int d)
    {
        return a+b+c+d;
    }
}
public class MethodoverLodaing 
{
 public static void main(String args[])
 {
     int num,num1,num2,num3;
     Scanner sc=new Scanner(System.in);
     System.out.println("Enteer first number");
     num=sc.nextInt();
     System.out.println("Enter secound number");
     num1=sc.nextInt();
     System.out.println("Enter third number");
     num2=sc.nextInt();
     System.out.println("Enetr four number");
     num3=sc.nextInt();
     Adder sh=new Adder();
     int x=sh.sum(num, num1, num2, num3);
     System.out.println("Sum"+x);
     
 }
}
