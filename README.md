# Challenge_Alura_Store
## Descripción del proyecto:
Se realizará un análisis de ventas y observará el rendimiento de cada una de las 4 tiendas para finalmente decidir cual tienda se venderá, para que el cliente pueda invertir en un negocio nuevo.
La evaluación se hará basándose en estos cinco aspectos: facturación total de cada tienda (cuál tienda vende más); cuáles son las categorías más populares de cada tienda (cuáles productos se venden más en cada tienda); cuál es el promedio de evaluación de cada uno de los clientes; cuáles son los productos más y menos vendidos en cada tienda; y cuál es el costo promedio del envío. El análisis se realizó utilizando Python, la librería `pandas` para la manipulación y análisis de datos, y `matplotlib` para observar los resultados.

## Instalación
Para utilizar este proyecto, haga lo siguiente:

**Copiar el repositorio:**
  ```bash
  git clone https://github.com/DarkLyng/Challenge_Alura_Store
  cd Challenge_Alura_Store
  ```
## Dependencias
Este proyecto ocupa las siguientes librerías de Python. Para instalarlas haga lo siguiente:

```bash
pip install pandas matplotlib
```
## Ejecutando las pruebas

Cuando las dependencias ya estén instaladas, se puede ejecutar el análisis realizado de la siguiente forma:

1. **Abrir el notebook de Colab:**
     Abrir el archivo `.ipynb` en Google Colab.
   
3. **Activar las celdas:**
    Ejecutar cada celda del cuaderno en orden para importar los datos, luego se realiza el análisis, luego se generan las visualizaciones y por último se observa el informe final. También se puede ejecutar todas las celdas de una vez.

## Archivos de Datos

Los datos utilizados en este análisis se cargan por los URLs de GitHub proporcionados por Alura Latam:

*   Tienda 1: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_1%20.csv`
*   Tienda 2: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_2.csv`
*   Tienda 3: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_3.csv`
*   Tienda 4: `https://raw.githubusercontent.com/alura-es-cursos/challenge1-data-science-latam/refs/heads/main/base-de-datos-challenge1-latam/tienda_4.csv`

## Resumen del Análisis
### 1. Ingresos Totales:
* **Tienda 1:** 1150880400
* **Tienda 2:** 1116343500
* **Tienda 3:** 1098019600
* **Tienda 4:** 1038375700

La Tienda 1 es la que genera mayores ingresos, mientras que la Tienda 4 es la de los ingresos más bajos.

### 2. Ventas por Categoría:
Las categorías más vendidas en todas las tiendas son los Muebles y Electrónicos. Las categorías menos vendidas son los Libros, Instrumentos musicales y Artículos para el hogar.

### 3. Calificación Promedio de Clientes:
* **Tienda 1:** 3.98
* **Tienda 2:** 4.04
* **Tienda 3:** 4.05
* **Tienda 4:** 4.00

La Tienda 3 tiene la calificación promedio más alta y la Tienda 1 la más baja.

### 4. Productos Más y Menos Vendidos:
* **Tienda 1:**
  * Más vendidos: Microondas, TV LED UHD 4K, Armario (60 cada uno)
  * Menos vendidos: Auriculares con micrófono, Celular ABXY (33 cada uno)
* **Tienda 2:**
  * Más vendido: Iniciando en programación (65)
  * Menos vendido: Juego de mesa (32)
* **Tienda 3:**
  * Más vendido: Kit de bancas (57)
  * Menos vendido: Bloques de construcción (35)
* **Tienda 4:**
  * Más vendido: Cama box (62)
  * Menos vendido: Guitarra eléctrica (33)

### 5. Costo de Envío Promedio:
* **Tienda 1:** 26018.61
* **Tienda 2:** 25216.24
* **Tienda 3:** 24805.68
* **Tienda 4:** 23459.46

La Tienda 1 tiene el costo de envío promedio más alto y la Tienda 4 el más bajo.

## Conclusión
Finalmente, se concluyó que se debe vender la Tienda 4, ya que es la que genera menores ingresos totales, si le agregamos el costo promedio de envío, se observa que a pesar de ser más bajo que el de las demás tiendas, en especial de la Tienda 1, esto no representa un monto significativo, ya que sus ganancias continuan siendo inferiores.  
A pesar de tener mejores opiniones con respecto a la Tienda 1, no se compara en ingresos, ya que son superiores al resto de las tiendas, este aspecto tambien es preocupante, ya que a largo plazo podría generar pérdidas y mala reputación a la tienda, pero es posible discutirlo con los empleados o poner los empleados de la Tienda 4 en la Tienda 1 para que se encarguen del servico al cliente y con esto mejore la calificación.

## Autores
* **Alura Latam** - Documentación - [Alura Latam](https://github.com/alura-es-cursos)
* **Darlyng Rojas Ramírez** - Contribuyente - [DarkLyng](https://github.com/DarkLyng)


