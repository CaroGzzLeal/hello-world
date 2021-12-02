# hello-world
# Carolina Gzz Leal A01284948
## Laboratory - branch - commits - pull-request - merge - markdown

**Actividad Github**

*Diciembre 2, 2021*

1. Actividad github
2. Método de calcular las frecuencias y leer archivo
3. Descargar los nuevos archivos de Serie y Episodios

- Proyecto programación
- Reto bloque
- Examen bloque


````c++

#include <iostream>
#include "Serie.hpp"
#include "Episodio.hpp"
#include "Series.hpp"
using namespace std;

void leeDatosSerie(std::string &_id, std::string &_titulo, int &_duracion, std::string &_genero, double &_calificacionPromedio, int &_cantEpisodios){ //función con pase de los parámetros de la serie por referencia
    
    cout << "Ingresa el id: ";
        cin >> _id;
    cout << "Ingresa el título: ";
    cin >> _titulo;
    cout << "Ingresa la duración en minutos: ";
    cin >> _duracion;
    cout << "Ingresa el género: ";
    cin >> _genero;
    cout << "Ingresa la calificación Promedio: ";
    cin >> _calificacionPromedio;
    cout << "Ingresa la cantidad de Episodios: ";
    cin >> _cantEpisodios;
    cout << "\n";
}
````
______

[youtube](https://www.youtube.com)
[markdown](https://www.markdownguide.org/cheat-sheet/)

![1aFoto](https://user-images.githubusercontent.com/89434246/144457655-5064a3ea-3a00-4665-92ea-874be8f96954.jpeg)

______

| Título1 | Título2 |
| ----------- | ----------- |
| Fila1 | Fila1 |
| Fila2 | Fila2 |

- [x] Mole con pollo
- [ ] Tamales
- [ ] Pay de manzana con nuez



````c++
Serie leeDatosSerie() {
    std::string id;
    std::string titulo;
    int duracion;
    std::string genero;
    double calificacionPromedio;
    int cantEpisodios;
    
    //Leer los datos de entrada
    cout << "Ingresa el id: ";
    cin >> id;
    cout << "Ingresa el título: ";
    cin >> titulo;
    cout << "Ingresa la duración en minutos: ";
    cin >> duracion;
    cout << "Ingresa el género: ";
    cin >> genero;
    cout << "Ingresa la calificación Promedio: ";
    cin >> calificacionPromedio;
    cout << "Ingresa la cantidad de Episodios: ";
    cin >> cantEpisodios;
    cout << "\n";
    return Serie(id, titulo, duracion, genero, calificacionPromedio, cantEpisodios);
}








