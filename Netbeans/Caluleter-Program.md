import java.util.Scanner;
class Sc
{
    int num,num1,result;
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
        result=num+num1;
        return result;
    }
    public int getSub()
    {
        result=num-num1;
         return result;       
    }
    public int getMul()
    {
        result=num*num1;
        return result;
    }
      public int getDiv()
    {
        result=num/num1;
        return result;
    }
}
public class ClassJavaCalculate
{
 public static void main(String args[])
 {
     int x,y;
     Sc d=new Sc();
     Scanner ab=new Scanner(System.in);
     System.out.println("Enter first number");
     x=ab.nextInt();
     System.out.println("Enter secound number");
     y=ab.nextInt();
     d.setA(x);
     d.setB(y);
     d.getSum();
     d.getSub();
     d.getMul();
     d.getDiv();
     System.out.println("Add\t"+d.getSum()+"\nSub\t"+d.getSub()+"\nMul\t"+d.getMul()+"\nDiv\t"+d.getDiv());
 }
}
