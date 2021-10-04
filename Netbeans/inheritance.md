class A
{
    public void method()
    {
        System.out.println("Base class memeber");
    }
}
class B extends A
{
    public void methosd()
    {
        System.out.println("Child class memeber");
    }
}
public class Inharitance 
{
public static void main(String args[])
{
    B obj=new B();
    obj.method();
    obj.methosd();
}
}
