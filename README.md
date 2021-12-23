# Mi Carrito

## Informacion de la app

Mi Carrito es una aplicación de registro de compras y ventas para un carro de
comidas/foodtruck. Esta enteramente desarrollada en Python utilizando la
librería Kivy y algunos elementos de KivyMD.

La aplicación con integración a una base de datos SQLite donde almacena la
información y cuenta de tres módulos los que son:

-   Compras: Aquí se almacenan los ingresos de productos e insumos necesarios
    para la operación del carrito. Tiene la opción de un ingreso rápido y un
    ingreso estándar. El ingreso rápido ya tiene ciertos productos que su
    categoría y unidad de medida ya son conocidas y evita tener que reingresar
    esa información cada vez que sea requerido.

-   Ventas: Aquí se puede seleccionar las opciones del menú, separadas por
    Comidas y Bebidas. Al final entrega un resumen del pedido y devuelve el
    total de la compra. Si eventualmente se quiere cambiar el valor total de la
    venta, el cuadro de texto lo permite.

-   Reportes: La aplicación permite la exportación de reportes en formato xlsx,
    con posibilidad de seleccionar el reporte requerido (Insumos o Ventas) y de
    filtrar rangos de fecha. Una vez indicado, el reporte es enviado via correo
    electrónico y a la vez almacenados de forma local en el teléfono.

## Deploy en Android

El deploy a Android se hace mediante de la compilación de los archivos usando el
script del archivo Compilador_Kivy mediante Google Colab y del archivo
buildozer_local.spec. Este archivo debe ser renombrado como buildozer.spec. Este
script instala todas las depoendencias de PythonForAndroid y las librerías
necesarias para la aplicación

Siga los pasos y cuando genere el buildozer.spec debe eliminarlo, reemplazarlo
por buildozer_local.spec, renombrado.

Se incluye también el archivo requirements.txt para instalar las librerías en su
entorno virtual.

Si te gusta mi trabajo y quieres contactarme, puedes visitar mi linkedin o
escribir a mi correo electrónico.

-   Linkedin:
    [www.linkedin.com/in/fortegaseguel](http://www.linkedin.com/in/fortegaseguel)

-   Email: felix.ortega@outlook.com
