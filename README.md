/******************************************************************************

                            Online Java Compiler.
                Code, Compile, Run and Debug java program online.
Write your code in this editor and press "Run" button to execute it.

*******************************************************************************/
import java.util.Random

public class Main{
	
	public static void main(String[] args) {
		System.out.println("Hello World");
	}
	
	
	public class Jogo{
	}
	
	public class Dado{
	    
	    public Dado(int ladosDado){
	        this.lados = ladosDado;
	    }
	    
	    public static int jogarDado(){
	        rand = new Random()
	        return rand.nextInt(this.lados) + 1;
	    }
	} 
}
