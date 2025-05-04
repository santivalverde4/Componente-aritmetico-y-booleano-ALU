# Componente Aritmético y Booleano de la ALU

Este proyecto consiste en la implementación del componente aritmético y booleano de una Unidad Aritmético-Lógica (ALU) utilizando el lenguaje de descripción de hardware Verilog. Fue desarrollado como parte de un proyecto académico por Daniel Arce, Issac Villalobos, Brendan Ramírez y Santiago Valverde.

## Descripción

La ALU es un componente fundamental en los procesadores, encargado de realizar operaciones aritméticas y lógicas. En este proyecto, se diseñaron y codificaron los módulos necesarios para ejecutar operaciones básicas, incluyendo:

* **Operaciones Aritméticas**: suma, resta, incremento, decremento.
* **Operaciones Booleanas**: AND, OR, XOR, NOT.
* **Multiplexores**: para la selección de operaciones.
* **Registro de Estado**: para indicar condiciones como cero, acarreo, desbordamiento, etc.

## Estructura del Proyecto

El repositorio contiene los siguientes archivos principales:

* `ARITHMETIC.v`: Módulo que implementa las operaciones aritméticas.
* `BOOLEAN.v`: Módulo que implementa las operaciones booleanas.
* `MULTIPLEXOR.v`: Módulo que selecciona la operación a ejecutar.
* `STATUS.v`: Módulo que gestiona las banderas de estado de la ALU.
* `Documentacion.docx`: Documento que detalla el diseño, implementación y pruebas del proyecto.

## Requisitos

* Herramienta de simulación y síntesis compatible con Verilog (por ejemplo, ModelSim, Vivado, Icarus Verilog).
* Conocimientos básicos de diseño digital y Verilog.

## Instrucciones de Uso

1. Clona el repositorio:

   ```bash
   git clone https://github.com/santivalverde4/Componente-aritmetico-y-booleano-ALU.git
   ```


2\. Abre los archivos `.v` en tu entorno de desarrollo o herramienta de simulación.
3\. Compila y simula los módulos según las instrucciones de tu herramienta específica.
4\. Consulta el archivo `Documentacion.docx` para obtener detalles sobre las pruebas y resultados esperados.

## Contribuciones

Este proyecto fue desarrollado con fines educativos. Si deseas contribuir, puedes:

1. Hacer un fork del repositorio.
2. Crear una nueva rama para tus cambios.
3. Realizar tus modificaciones y hacer commits descriptivos.
4. Enviar un pull request detallando tus cambios.

## Licencia

Este proyecto está bajo la licencia MIT. Consulta el archivo [LICENSE](LICENSE) para más información.

---
