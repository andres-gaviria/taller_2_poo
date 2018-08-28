    ///// punto 1/////////
package primer_punto;
import java.util.Scanner;
public class primer_punto {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int numero_1,numero_2,numero_3,numero_4;
		
		System.out.println("ingrese el primer numero");
		numero_1 = sc.nextInt();
		System.out.println("ingrese el segundo numero");
		numero_2 = sc.nextInt();
		System.out.println("ingrese el tercer numero");
		numero_3 = sc.nextInt();
		System.out.println("ingrese el cuarto numero");
		numero_4 = sc.nextInt();
		
		System.out.println("posicion 4: "+numero_4);
		System.out.println("posicion 3: "+numero_3);
		System.out.println("posicion 2: "+numero_2);
		System.out.println("posicion 1: "+numero_1);
	}
}
////////////////punto 2////////////
package punto2;
import java.util.Scanner;
class segundo_punto {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int numero,doble,cuadruple,quintuple;
		
		System.out.println("suministre el numero a operar");
		numero = sc.nextInt();
		
		doble = numero * 2;
		cuadruple = numero * 4;
		quintuple = numero * 5;
		
		System.out.println("el doble del numero es: "+doble);
		System.out.println("el cuadruple del numero es: "+cuadruple);
		System.out.println("el quintuple del numero es: "+quintuple);
		
		
	}
}
///////////punto 3///////////////
package punto3;
import java.util.Scanner;
class tercer_punto {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int cen, resultado;
		
		System.out.println("suministre los centigrados a convertir");
		cen = sc.nextInt();
		
		resultado = 32 + (9 * cen/5);
		
		System.out.println("el resultado es: "+resultado+ " grados fahrenheit");	
	}
    }       
    /////////////////// punto 4///////////////////
    
    ////////////////////punto 5//////////////////
    package punto5;
import java.util.Scanner;
class quinto_punto {
	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int numero;
		double resultado;
		
		System.out.println("suministre la velocidad a operar");
		numero = sc.nextInt();
		
		resultado = numero * 0.2778;
		
		System.out.println("la velocidad convertida en: "+resultado+" m/s");
	}
}
//////////////////////////punto 6/////////////////////
package punto6;
import java.util.Scanner;

class sexto_punto {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		Scanner sc = new Scanner (System.in);
		int i,suma_pares=0,a;
		
		int cont, suma=0;
		cont = 1;
		while(cont <= 100){
			suma += cont;
			cont++;
		}	
		System.out.println("la suma de total es: "+suma);
		
	}
}
