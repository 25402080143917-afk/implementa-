# implementa-
programa que calculen el volumen de figuras geometricas 
#include <iostream>
  using namespace  std;
int main()
{
   int   Abase , alt; 
   float volumen ;
    
    cout <<" escribe el area de la base del prisma: " ; 
     cin >> Abase; 
     cout<<"escribe la altura";
     cin>>alt;
     volumen = Abase*alt ; 
     cout <<" el volumen es : " << volumen;
    return 0;
}
