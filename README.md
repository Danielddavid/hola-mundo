
#include <iostream>
#include <conio.h>

using namespace std;

main(){
	
	int op, num1, num2, num3, num4;
	
	cout<<"a) Sumar"<<endl;
	cout<<"b) Restar"<<endl;
	cout<<"c) Multiplicar"<<endl;
	cout<<"d) Dividir"<<endl;
	cout<<"Ingresa un opcion!"<<endl;
	cin>>op;
	
	switch(op){
		
		case 'a':
			
			cout<<"Ingresa los numeros que quieres Sumar! ";
			cout<<"Numero 1: ";
			cin>>num1;
			cout<<"Numero 2: ";
			cin>>num2;
			
			num3 = num1 + num2;
			
			cout<<"La suma de los numeros es: "<<num3;
			
			break;
			
		case 'b':
		
			cout<<"Ingresa los numeros que quieres Restar! ";
			cout<<"Numero 1: ";
			cin>>num1;
			cout<<"Numero 2: ";
			cin>>num2;
			
			num3 = num1 - num2;
			
			cout<<"La resta de los numeros es: "<<num3;
		
			break;
			
		case 'c':
			
			cout<<"Ingresa los numeros que quieres Multiplicar! ";
			cout<<"Numero 1: ";
			cin>>num1;
			cout<<"Numero 2: ";
			cin>>num2;
			
			num3 = num1 * num2;
			
			cout<<"La multiplicacion de los numeros es: "<<num3;
		
			break;
			
		case 'd':
			
			cout<<"Ingresa los numeros que quieres Dividir! ";
			cout<<"Numero 1: ";
			cin>>num1;
			cout<<"Numero 2: ";
			cin>>num2;
			
			num3 = num1 / num2;
			
			cout<<"La divicion de los numeros es: "<<num3;
		
			break;
		
			
	}
	
	
	
}










