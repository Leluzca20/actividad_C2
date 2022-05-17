//================================================
//==> Nombre del programa: Suma de dos número
//==> Archivo : suman.cpp
//==>Autor: Lely Alvarado
//==>Fecha de elaboración: 2022-01-20
//==>Fecha ultima actualización: 2022-05-17
//=================================================

#include<iostream>
using namespace std;

int main()
{
  int Lg_c=0, Lg_n;
  float  Lg_x, Lg_a=0;
  cout<<"Ingrese la cantidad de número a sumar:"; 
  cin>> Lg_n;
  do{
	  cout<<"Ingrese el número : "; 
	  cin>> Lg_x;
	   Lg_c= Lg_c+1;
	   Lg_a= Lg_a+ Lg_x;
  }while( Lg_c< Lg_n);


cout<<endl<<"//================================================"<<endl;
cout<<"//==> Nombre del programa: Suma de dos número"<<endl;
cout<<"//==> Archivo : suman.cpp"<<endl;
cout<<"//==>Autor: Lely Alvarado"<<endl;
cout<<"//==>Fecha de elaboración: 2022-01-20"<<endl;
cout<<"//==>Fecha ultima actualización: 2022-05-17"<<endl;
cout<<"//================================================="<<endl;
            
                                                                 
 
                                                              
 cout<<"La suma de los "<<Lg_n<<" números fue "<<lg_a<<endl;
  return 0;

}




