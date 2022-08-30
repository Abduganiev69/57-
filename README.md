# 57-
57Сумма цифр числа
public class Main
{
	public static void main(String[] args) {
	     java.util.Scanner myscanner= new java.util.Scanner(System.in);
	 	int a = myscanner.nextInt();
	 	System.out.println(((a / 10 )-(a/100*10)) + (a /100) +(a%10));
	}
}
