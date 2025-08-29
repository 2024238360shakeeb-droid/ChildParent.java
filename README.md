# ChildParent.java
Extending Child Class from Parent Class


package FirstText;
class one{
	public void add() {
		int a,b,c;
		a=10;
		b=20;
		c=a+b;
		System.out.println("ADD"+c);
	}
}
class Two{
	public void name() {
		one obj=new one();
		obj.add();
	}
}
public class Hello {
	public static void main(String[] args) {
		Two obj=new Two();
		obj.name();
	}
}
