package apsP3;
 import java.util.Scanner;
public class ex4 {

	public static void main(String[] args) {
		Scanner tl =new Scanner(System.in);
		/* Faça um algoritmo que leia vários números e informe quantos desses números entre 100 e 200 foram digitados.
		 *  Quando o valor 0 (zero) for lido o algoritmo deverá cessar sua execução.
		 */

		int numerosinformado,contadorDvalor = 0;
		
		System.out.println("informe um número");
		numerosinformado=tl.nextInt();
		
		while(numerosinformado != 0) {
			 if(numerosinformado > 100 && numerosinformado < 200) {
				 contadorDvalor++;
				 
				 
			 }
			 System.out.println("informe um número");
				numerosinformado=tl.nextInt();
		}
		
		System.out.println("Foram digitados " + contadorDvalor + " números entre 100 e 200.");
	}

}
fimdoalgoritmo
