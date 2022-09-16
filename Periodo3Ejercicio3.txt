import java.util.Scanner;
class Main {
  public static void main(String[]args) {
    Scanner ingresar = new Scanner(System.in);
    double nota; 
    
  System.out.println("Ingrese un numero desde 1 hasta 15");
  nota=ingresar.nextDouble();

  while(nota<1 | nota>15)
  {
  System.out.println("El numero proporcionado no es correcto");
    nota=ingresar.nextDouble();
    }
  }
}