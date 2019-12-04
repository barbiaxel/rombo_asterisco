# rombo_asterisco
Dibuja rombo con asteriscos
package ejercicio2;
//dibuja rombo
public class ejercicio2 {
	
	public static void main (String args[]){
		
		for (int i= 1; i<=4; i++){ 
			for (int espacios = 5 - i; espacios >0; espacios--)       
				System.out.print(" "); 
			for (int lineas = 1; lineas < 2 * i; lineas++) 
				System.out.print("*"); 
				System.out.println(""); 
				} 
		
		for (int i= 3; i>=1; i--){ 
			 for (int espacios = 5 - i; espacios >0; espacios--)       
				 System.out.print(" "); 
			 for (int lineas = 1; lineas < 2 * i; lineas++) 
				 System.out.print("*"); 
			  	System.out.println(""); 
		} 
	}
}
