# implementa-
programa que calculen el volumen de figuras geometricas 
/******************************************************************************
menu # figuras geometricas "implementa"

*******************************************************************************/
#include <iostream>
using namespace  std;
int main()
{
float p,c,pri,cili,radio,altura,volumen,alt,Abase,lado,h;
  int op;
  cout<<"escribe el numero de la opcion que necesitas " <<endl;
  cout<<"1.el volumen de prisma " <<endl;
  cout<<"2.el volumen del cubo " <<endl;
  cout<<"3.el volumen de la piramide " <<endl;
  cout<<"4.el volumen de un cilindro " <<endl;
  cin>>op;
  if (op==1) { 
      cout<<"escribe el area de la base del prisma ";
      cin>>Abase; 
      cout<<"escribe la altura ";
      cin>>h;
      volumen=Abase*h;
      cout<<"el volumen es " <<volumen; 
} else if(op==2) {
    cout<<"escribe el lado del cubo ";  
    cin>>lado; 
volumen=lado*lado*lado;
cout<<"el volumen es " <<volumen;
  }  else if (op==3) {
    cout<<"escribe la altura de la pirámide "; 
    cin>>alt; 
    cout<<"escribe el area de la base de la piramide ";
    cin>>Abase;
    volumen =(Abase*alt)/3;
    cout<<"el volumen es " <<volumen; 
} else if (op==4){
    cout <<"el radio del cilindro "; 
    cin>>radio;
    cout<<"escribe la altura ";
    cin>>altura;
volumen=3.1416*(radio*radio)*altura;
cout<<"el volumen del cilimdro es :" <<volumen;
}
else {
    cout<<"opcion invalida";
}
return 0;
}
