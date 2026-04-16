# implementa-
programa que calculen el volumen de figuras geometricas 
#include <iostream>
using namespace std;
int main()
{
    int lado;
    float volumen;
    
    cout<<"ingrese un lado del cubo: ";      
    cin>> lado;
    
    volumen=lado*lado*lado;
    
    cout<<"el volumenes: "<<volumen;

    return 0;
}
