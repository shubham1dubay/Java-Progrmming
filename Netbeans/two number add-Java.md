import java.util.Scanner;
class Ab
{
    int num,num1,sum;
    public void setA(int a)
    {
        num=a;
    }
    public void setB(int b)
    {
        num1=b;
    }
    public int getSum()
    {
        sum=num+num1;
        return sum;
    }
}  
public class ClassJava 
{
 public static void main(String args[])
 {
     int x,y;
     Scanner sc=new Scanner(System.in);
     Ab c=new Ab();
     System.out.println("Enter first number");
     x=sc.nextInt();
     System.out.println("Enter secound number");
     y=sc.nextInt();
     c.setA(x);
     c.setB(y);
    System.out.println(c.getSum());
 }
}
