- 👋 Hi, I’m @MachadoJefferson
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
MachadoJefferson/MachadoJefferson is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Scanner;

public class Main {

	public static void main(String[] args) {
		Scanner teclado = new Scanner(System.in);
		
		System.out.print("Por favor insira seu nome completo: ");		
		String nome = teclado.nextLine();
		
		System.out.print("Por favor insira sua Renda atual:: ");
		double renda = teclado.nextDouble();
		
		System.out.print("Para finalizar insira a sua idade: ");
		int idade = teclado.nextInt();
		
		if(renda>=3000 && idade >=18) {
			System.out.println("Parabens seu seguro foi aprovado!");
			System.out.println("Um de nossos consultores entrara em contato.");
				
		} else {
			System.out.println("Infelizmente seu seguro foi recusado.");
			
		}
		System.out.println("Obrigado por usar o programa");
		
		
		
		
		
	  teclado.close();
	
	}

}
