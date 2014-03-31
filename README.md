NumericalAnalysis
=================

Package about methods in Numerical Analysis for solving linear equations also can to handle machine numbers.

Sobre el programa
-----------------

El archivo MachineNumer.py contiene metodos para generar numeros de maquina indicandole ciertos parametros.

El archivo LinearEquation.py contiene metodos para resolver ecuaciones lineales.

Finalmente el archivo Main.py muestra un menu con el acceso a ambos programas.

Como ejecutar el programa?
------------------------

Guardar los tres archivos MachineNumber.py, LinearSolver.py y Main.py en una misma carpeta, luego 
dentro esa carpeta ejecutar el archivo Main.py.

Por ejemplo si usamos la terminal, nos dirigimos a la carpeta de los archivos y luego ejecutamos:

python Main.py

Como usarlo ?
-------------

Para el manejo de numeros de maquina se necesitan parametros como mantisa, base y las cotas del exponente 
de la base, el mismo programa indica los pasos.

Para resolver ecuaciones lineales necesitamos la matriz y el vector independiente, tambien en ciertos 
casos se necesita confirmar el tipo de resolucion: con pivotacion parcial, total o sin pivotacion.

Por hacer
---------

Agregar nuevos metodos y mejorar los existentes, por ejemplo:

- Metodo de Parlett y Reid
- Metodo de Aasen
- Completar el tema de condicionamiento

Basicamente agregar otro que falte y obviamente mejorar los existentes en busca de bugs.

Si alguiente quiere aportar solo haga un fork del project :).

