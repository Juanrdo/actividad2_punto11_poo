# actividad2_punto11_poo
package salariobasico;
import java.util.Scanner;
public class Salariobasico {

    public static void main(String[] args) {
        double  horas,salariohora,mensualidad;
        Scanner ingresotecl = new Scanner (System.in);
       
        System.out.println("Ingrese el nombre:  ");
        String nombres = ingresotecl.next();
        
        System.out.println("Ingrese su salario basico por hora:  ");
        salariohora = ingresotecl.nextDouble();
        
        System.out.println("Ingrese el numero de horas trabajadas:  ");
        horas = ingresotecl.nextDouble();
        
        mensualidad=salariohora*horas;
        if (mensualidad>450000){
            System.out.println("empleado: "+ nombres +" salario: "+ mensualidad);
        }
        else {
            System.out.println("empleado: "+ nombres);
        }
        
        
    }
    
}
