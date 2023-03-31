# Volumen-de-una-esfera-
#include <iostream>
using namespace std ; 
int main (){
    // Declaración de variables
    double radio, volumen;
    const double PI = 3.14159; // Declaración de constante pi

    // Pedimos al usuario el radio de la esfera
    cout << "Ingresa el radio de la esfera: ";
    cin >> radio;

    // Calculamos el volumen de la esfera
    volumen = (4.0/3.0) * PI * (radio * radio * radio);

    // Mostramos el resultado al usuario
    cout << "El volumen de la esfera es: " << volumen << endl;

    return 0;
