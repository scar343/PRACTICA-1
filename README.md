# PRACTICA-1
[convierta grados Celsius a Fahrenheit..txt](https://github.com/user-attachments/files/33910819/convierta.grados.Celsius.a.Fahrenheit.txt)
int main() {
 float celsius, fahrenheit;
 printf("Ingrese la temperatura en grados Celsius: ");
 scanf("%f", &celsius);
 fahrenheit = (celsius * 9.0 / 5.0) + 32;
 printf("La temperatura en Fahrenheit es: %.2f\n", fahrenheit);
 return 0;
}
