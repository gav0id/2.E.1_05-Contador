Ejercicio 2.E.1 05 - Contador

Lógica del programa
Para este ejercicio, diseñé la clase `Contador` enfocada en encapsular un valor numérico y controlar estrictamente cómo se modifica. Definí un único atributo de estado llamado `valor` (de tipo int).

Una característica destacada de esta implementación es el uso de la sobrecarga de constructores. Creé dos alternativas: un constructor que permite inicializar el contador con un número específico que le pasemos por parámetro, y un constructor por defecto (sin parámetros) que inicializa automáticamente el valor en 0.

Para el comportamiento de la clase, implementé cuatro métodos que manipulan el estado del objeto:
1. `incrementar()`: suma 1 al valor actual.
2. `decrementar()`: resta 1 al valor, incorporando una validación condicional (`if/else`) para evitar que el contador tome valores negativos (si ya está en 0, se mantiene en 0).
3. `resetear()`: devuelve el valor a 0 independientemente de su estado actual.
4. `getValor()`: un método de tipo getter que retorna el número almacenado actualmente.
   
Ejecución en consola (agregue un metodo main para probarlo)
<img width="1366" height="721" alt="imagen" src="https://github.com/user-attachments/assets/7e8e0436-15b2-417b-ae67-4cb84cd8ba47" />


