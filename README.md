# implementa-
programa que calculen el volumen de figuras geometricas 
#include <iostream>
using namespace std;

int main()
{
    float base,alt,volumen;
    
    cout<<"Ingresa la  añtura de la base: ";
    cin>>base;
    
    cout<<"Ingresa la altura: ";
    cin>>alt;
    
    volumen=(base*alt)/3;
    
    cout<<"El volumen es: "<<volumen;

    return 0;
}
