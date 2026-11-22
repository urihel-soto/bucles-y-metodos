using System;

class Program
{
    // =====================================================================
    // PARTE 1 - YOKENDDY
    // Esta es mi parte del código: abro la clase Program y hago las
    // funciones para calcular el área del triángulo y del cuadrado.
    // Sigue Antoni Ramirez.
    // =====================================================================

    // Funcion para calcular el area de un triangulo
    static double AreaTriangulo(double baseTriangulo, double altura)
    {
        return (baseTriangulo * altura) / 2;
    }

// =====================================================================
    // PARTE 3 - DALBERT HERNANDEZ
    // Esta es mi parte del código: inicio el programa principal (Main),
    // muestro el menú y hago las opciones 1 (triángulo) y 2 (cuadrado).
    // Sigue Emmanuel.
    // =====================================================================

    // Programa principal
    static void Main()
    {
        int opcion;

        do
        {
            Console.WriteLine("\n===== MENU PRINCIPAL =====");
            Console.WriteLine("1. Calcular area del triangulo");
            Console.WriteLine("2. Calcular area del cuadrado");
            Console.WriteLine("3. Calcular area del circulo");
            Console.WriteLine("4. Verificar edad");
            Console.WriteLine("5. Salir");
            Console.Write("\nSeleccione una opcion: ");

            opcion = Convert.ToInt32(Console.ReadLine());

            switch (opcion)
            {
                case 1:
                    Console.Write("\nIngrese la base del triangulo: ");
                    double baseT = Convert.ToDouble(Console.ReadLine());

                    Console.Write("Ingrese la altura: ");
                    double altura = Convert.ToDouble(Console.ReadLine());

                    double resultadoT = AreaTriangulo(baseT, altura);

                    Console.WriteLine("El area del triangulo es: " +
                        resultadoT);
                    break;

                case 2:
                    Console.Write("\nIngrese el lado del cuadrado: ");
                    double lado = Convert.ToDouble(Console.ReadLine());

                    double resultadoC = AreaCuadrado(lado);

                    Console.WriteLine("El area del cuadrado es: " +
                        resultadoC);
                    break;
    // Funcion para calcular el area de un cuadrado
    static double AreaCuadrado(double lado)
    {
        return lado * lado;
    }
// =============================================================
                // PARTE 4 - EMMANUEL
                // Esta es mi parte del código: hago las opciones 3 (círculo),
                // 4 (verificar edad), 5 (salir), la opción no válida y
                // cierro el programa.
                // Fin del código.
                // =============================================================

                case 3:
                    Console.Write("\nIngrese el radio del circulo: ");
                    double radio = Convert.ToDouble(Console.ReadLine());

                    double resultadoCirculo = AreaCirculo(radio);

                    Console.WriteLine("El area del circulo es: " +
                        resultadoCirculo);
                    break;

                case 4:
                    Console.Write("\nIngrese su edad: ");
                    int edad = Convert.ToInt32(Console.ReadLine());

                    string mensaje = VerificarEdad(edad);

                    Console.WriteLine(mensaje);
                    break;

                case 5:
                    Console.WriteLine("\nGracias por utilizar el programa.");
                    break;

                default:
                    Console.WriteLine("\nOpcion no valida. Intente nuevamente.");
                    break;
            }

        } while (opcion != 5);
    }
}
