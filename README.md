# Ejercicios-repetitivos
mostrar números hasta el límite

public class Main {

    // Realizar un programa que dado por teclado un límite numérico (ejemplo 100) muetsre en pantalla todos los números hasta ese límite (empezando por 1)
    // Tenemos un límite hasta el que tenemos que contar
    // Ingresar ese límite

    public static void main (String[] args) {

        System.out.println("Ingresa el límite hasta el que quiere contar");
        Scanner teclado = new Scanner(System.in);
        int limite = teclado.nextInt();
        int cont = 1;

        while (cont <= limite) {
            System.out.println(cont);
            cont = cont + 1;
            //cont ++;

        }
    }

}
