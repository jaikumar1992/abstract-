# abstract-
abstract sample program

abstract class add // abstract must given class level name..if we used in variables or method. 
{
int a=5,b=10;
	abstract void show();
	abstract void display();
	{
	int c=a+b;
	System.out.println("the addition of two numbers......"+c);
	}
}
class sub extends add
{
	void show()
	{
	System.out.println("we are in abstract sub class.....");
	
	}
	void display()
		{
		int c=a-b;
		System.out.println("the value of c is..."+c); //*we can use inheritance here
		}
	
public static void main(String args[])
	{
	add t1=new sub();
	t1.show();
	t1.display();
	
	}	
}
