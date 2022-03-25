# trabalho_de_java-poo
trabalho de pesquisa de java e poo




1 questao:

package com.program;

import java.util.Scanner;

public class Program {
	
		public static void main(String[] args) {
			System.out.println(" informe o valor :");
			Scanner scan = new Scanner ( System.in);
			
			double raio = scan.nextFloat();
			double area = Math.PI * raio * raio ;
			
			System.out.print(" a área é :");
			System.out.print( String.format(" % .4f" , area));


}

}





2 questao :

package com.program;

import java.text.DecimalFormat;
import java.util.Scanner;

//import java.util.Scanner;

public class Program {
	
		public static void main(String[] args)  {
			
			Scanner input = new Scanner(System.in);
			DecimalFormat df = new DecimalFormat("0.000");
			double A, B, C, pi ;
			double TRIANGULO, CIRCULO, TRAPEZIO, QUADRADO, RETANGULO;
			
			pi = 3.14159;
			A = input.nextDouble();
			B = input.nextDouble();
			C = input.nextDouble();
			
			
			TRIANGULO = A * C /2 ;
			CIRCULO = pi * C * C ;
			TRAPEZIO = (A + B)*C/2;
			QUADRADO = B*B ;
			RETANGULO = A*B;
			
			    System.out.println("VALOR DA ÁREA DO TRIÂGULO: "+ df.format(TRIANGULO));
			    System.out.println("VALOR DA ÁREA DO CÍRCULO: "+ df.format(CIRCULO));
			    System.out.println("VALOR DA ÁREA DO TRAPÉZIO: " + df.format(TRAPEZIO));
				System.out.println("VALOR DA ÁREA DO QUADRADO: " + df.format(QUADRADO) );
				System.out.println("VALOR DA ÁREA DO RETÂNGULO: " + df.format(RETANGULO));
			
			
    }

}

3 questao:

        double a = 3 ;
        double b = - 15 ;
        double c = 12 ;
        double delta, x1, x2 ;

		delta = Math.pow(b, 2.0) - 4*a*c;
		x1 = (-b + Math.sqrt(delta))/ (2.0 * a);
		x2 = (-b - Math.sqrt(delta))/ (2.0 * a);
		 
		System.out.println("VALOR DE DELTA: "+ delta);
		System.out.println("VALOR DE X1: " +x1);
		System.out.println("VALOR DE X2: " +x2 );
	
		
	}
			

}
