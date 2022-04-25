class Shape
{
	void draw()
	{
		System.out.println("shape has draw");
	}
	void erase()
	{
		System.out.println("shape has erase");
	}
}
class Triangle extends Shape
{
	void draw() 
	{
		System.out.println("triangle has draw");
	}
	void erase()
	{
		System.out.println("triangle has erase");
	}
}
class Square extends Shape
{
	void draw() 
	{
		System.out.println("Square has draw");
	}
	void erase()
	{
		System.out.println("square has erase");
	}
}
class Circle extends Shape
{
	void draw()
	{
		System.out.println("Circle has draw");
	}
	void erase()
	{
		System.out.println("Circle has erase");
	}
}
public class poly {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
Triangle obj=new Triangle();
obj.draw();
obj.erase();
Square obj1=new Square();
obj1.draw();
obj1.erase();
Circle obj2=new Circle();
obj2.draw();
obj2.erase();
	}

}
