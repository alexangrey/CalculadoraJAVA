void main() {

    String texto;
    int opcion;

    IO.println("1. Sumar");
    IO.println("2. Restar");
    IO.println("3. Multiplicar");
    IO.println("4. Dividir");

    texto = IO.readln("Seleccione una opción: ");
    opcion = Integer.parseInt(texto);

    texto = IO.readln("Ingrese el primer valor: ");
    int num1 = Integer.parseInt(texto);

    texto = IO.readln("Ingrese el segundo valor: ");
    int num2 = Integer.parseInt(texto);

    switch(opcion){

        case 1:

            IO.println("El resultado es: " + (num1 + num2));

        break;

        case 2:

            IO.println("El resultado es: " + (num1 - num2));

        break;

        case 3:

            IO.println("El resultado es: " + (num1 * num2));

        break;

        case 4:

            if(num2 != 0){

                double division = (double) num1 / num2;

                IO.println(String.format("El resultado es: %.2f", division));

            }else{

                IO.println("No se puede dividir entre cero.");

            }

        break;

        default:

            IO.println("Opción incorrecta.");

    }

}