# AV1
Avance 1
#include <iostream>

using namespace std;

int main() {
	int opcion, opc;

	do {
		cout << "\t MENU" << endl;
		cout<< "1.Agregar un articulo" << endl;
		cout << "2.Salir" << endl;
		cout << "Eliga una de las opciones" << endl;
		cin >> opcion;

		switch (opcion) {
		case 1:

			cout<< "Agendar un articulo" <<endl;
			cout << "Ingresar el numero de articulo" << endl;
			cout << "Nombre del videojuego" << endl;
			cout << "Año de lanzamiento" << endl;
			cout << "Clasificacion" << endl;
			cout << "Caracteristicas" << endl;
			cout << "Descripción del juego" << endl;
			cout << "Genero" << endl;
			cout << "Precio unitario" << endl;
			cout << "Impuesto" << endl;
			cout << "Total a pagar" << endl;
			cin >> opc;
			if (opc == 1) {
				return 0;
			}
			break;

		case 2:cout << "Seguro que quieres ... ? ?  Si o No" << endl;
			cout << "1. Si" << endl;
			cout << "2. No" << endl;
			cin >> opc;
			if (opc == 1) {
				return 0;
			}
			else
			{
				return main();
			}
			break;
		default: cout << "Opcion invalida " << endl;
			break;
		}


		system("pause");
		system("cls");
	}while(opcion <= 2);
}
