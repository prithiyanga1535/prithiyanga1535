import.java.util.Scanner;
class asmd
{
static int a,b;
static float c;
public static void main(String arg[])
{
Scanner s1=new Scanner(System.in);
a=s1.nextInt();
b=s1.nextInt();
c=a+b;
System.out.println("The addition is:"+c);
c=a-b;
System.out.println("The subtraction is:"+c);
c=a*b;
System.out.println("The multiplication is:"+c);
c=a/b;
System.out.println("The division is :"+c);
}
}
