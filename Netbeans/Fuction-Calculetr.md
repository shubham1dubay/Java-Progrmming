import java.util.Scanner;
class calculate
{
    int a,b,c;
    public void setA(int aa)
    {
        a=aa;
    }
    public void setB(int bb)
    {
        b=bb;
    }
    public int getSum()
    {
        c=a+b;
        return c;
    }
    public int getSub()
    {
        c=a-b;
        return c;
    }
     public int getMul()
    {
        c=a*b;
        return c;
    }
      public int getDiv()
    {
        c=a/b;
        return c;
    }
       public int getParcentage()
    {
        c=a%b;
        return c;
    }
}
public class ClassProgram
{
 public static void main(String args[])
 {
     Scanner sc=new Scanner(System.in);
     int x,y;
     System.out.println("Enter first number");
     x=sc.nextInt();
     System.out.println("Enter Secound number");
     y=sc.nextInt();
     calculate ab=new calculate();
     ab.setA(x);
     ab.setB(y);
     ab.getSum();
     ab.getSub();
     ab.getMul();
     ab.getDiv();
     ab.getParcentage();
     System.out.println("Sum   "+ab.getSum());
     System.out.println("Sum   "+ab.getSub());
     System.out.println("Sum   "+ab.getMul());
     System.out.println("Sum   "+ab.getDiv());
     System.out.println("Sum   "+ab.getParcentage());
 }
}
