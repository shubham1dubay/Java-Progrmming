
import java.util.Scanner;

 interface Id
{
   public void show(); 
  
}
class shubham implements  Id

{
    String name,rollno;
    int aadharno;
    public shubham()
    {
      
      
    }
    public shubham(String name,String rollno,int aadharno)
    {
        this.name=name;
        this.rollno=rollno;
        this.aadharno=aadharno;
    }
    public void show()
    {
        System.out.println("Name: "+name);
        System.out.println("Rollno  "+rollno);
        System.out.println("Aadharno  "+aadharno);
    }
};
public class Interface
{
    public static void main(String[] args)
    {
       
      String name,rollno;
      int aadharno;
      Scanner sc=new Scanner(System.in);
        System.out.println("Enter name:");
        name=sc.nextLine();
        System.out.println("Enter Roll Number:");
        rollno=sc.nextLine();
        System.out.println("Enter Aadhar Number:");
        aadharno=sc.nextInt();

        shubham s=new shubham(name,rollno,aadharno);
        s.show();
    }
}
