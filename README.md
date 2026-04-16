# implementa-
programa que calculen el volumen de figuras geometricas 
#include <iostream>
using namespace std;

int main()
{

int radio, altura;
float volumen;
    
cout<< "ingrese la radio: ";
cin>> radio;

cout<< "ingrese la altura: ";
cin>> altura;

volumen = 3.1416 * (radio * radio) * altura;

cout<<"El volumen del cilindro es: "<<volumen;

    return 0;
}
