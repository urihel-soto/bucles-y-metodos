# Actividad: Control de Flujo de una Aplicación en C#

## 1. Autores y Matrículas
- **Génesis Altagracia de la Cruz Perozo** | Matrícula: 26-SISN-2-051
- **Dalbert Yordani Hernández Alcántara** | Matrícula: 26-EISN-2-014
- **Emmanuel Javier Mercedes** | Matrícula: 26-EISN-2-023
- **Urihel Soto De Peña** | Matrícula: 26-EISN-2-032
- **Yokenddy Amparo Silvestre** | Matrícula: 26-EISN-2-002
- **Antoni Ramírez Mercedes** | Matrícula: 26-EISN-2-019

---

## 2. Descripción del Programa
Aplicación de consola desarrollada en **C#** diseñada para demostrar el control de flujo mediante la declaración, invocación y retorno de valores de funciones con parámetros. El sistema ofrece una interfaz interactiva que permite al usuario calcular el área de distintas figuras geométricas (triángulo, cuadrado y círculo) y evaluar la mayoría de edad de una persona.

---

## 3. Datos de Entrada
El programa solicita al usuario a través de la consola los siguientes valores según la operación seleccionada:
- **Opción del menú:** Selección de la función a ejecutar.
- **Para el área del triángulo:** Base y altura (valores numéricos).
- **Para el área del cuadrado:** Longitud de un lado (valor numérico).
- **Para el área del círculo:** Radio de la circunferencia (valor numérico).
- **Para validación de edad:** Edad de la persona (número entero).

---

## 4. Datos que Procesa
El programa principal (`Main`) lee los datos ingresados y los envía como argumentos a cuatro funciones específicas:
1. **Función Área del Triángulo:** Recibe la base y la altura, y calcula el área mediante la fórmula $\frac{\text{base} \times \text{altura}}{2}$.
2. **Función Área del Cuadrado:** Recibe el lado y calcula el área elevándolo al cuadrado ($\text{lado}^2$).
3. **Función Área del Círculo:** Recibe el radio y calcula el área multiplicando $\pi$ por el radio al cuadrado ($\pi \times \text{radio}^2$).
4. **Función Validación de Edad:** Recibe la edad entera y evalúa mediante una estructura condicional si es mayor o igual a 18 años para determinar el mensaje correspondiente.

---

## 5. Datos de Salida
- **Cálculos geométricos:** Muestra en pantalla el resultado numérico del área calculada para el triángulo, cuadrado o círculo según lo retornado por cada método.
- **Evaluación de edad:** Muestra un mensaje en pantalla indicando claramente si la persona es **mayor de edad** o **menor de edad**.

---

## 6. Tecnología Utilizada
- **Lenguaje de Programación:** C# (.NET Console Application)
- **Control de Versiones:** Git y GitHub
