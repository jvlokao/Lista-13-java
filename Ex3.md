package lista13java;
import java.util.Scanner;
public class Ex3 {
	public static void main(String[] args) {
		int num1;
		Scanner entrada = new Scanner(System.in);
		System.out.println("Insira um numero para verificar seu dobro");
		num1 = entrada.nextInt();
		System.out.print("O dobro do numero é: ");
		System.out.print(num1*2);
	}	
}
