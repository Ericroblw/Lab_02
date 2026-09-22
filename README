##Laboratorio 02 - Implementar objetos de programabilidad con SQL

Autor: Eric Emmanuel Ramírez Duanca

##Entorno de Desarrollo

Motor de base de datos: Microsoft SQL Server 2019 o posterior (o Azure SQL Database)

Base de datos de ejemplo: AdventureWorksLT

Cliente gráfico: SQL Server Management Studio (SSMS)

##Instrucciones para reproducir el trabajo

Para preparar el entorno y ejecutar los ejercicios, sigue estos pasos desde SSMS:

Restauración y conexión a la base de datos: Asegúrate de tener restaurada la base de datos de muestra AdventureWorksLT. Conéctate a tu instancia local de SQL Server, abre una "Nueva Consulta" (New Query) y selecciona la base de datos AdventureWorksLT en el selector superior o ejecuta USE AdventureWorksLT;.

Verificación de tablas maestras: Ejecuta las consultas de verificación sobre SalesLT.Customer, SalesLT.SalesOrderHeader y SalesLT.Product para confirmar el correcto acceso a los datos de prueba.

Implementación de objetos de programabilidad:

Vista (SalesLT.vCustomerOrders): Ejecuta el script de creación de la vista que simplifica las uniones (JOIN) entre clientes y cabeceras de órdenes.

Procedimiento Almacenado (dbo.AddOrderLineItem): Compila el procedimiento que gestiona la inserción transaccional atómica de líneas de pedido (SalesOrderDetail) y el recálculo automático del subtotal en el encabezado.

Función Escalar (dbo.fnOrderTotal): Crea la función de cálculo reutilizable para sumar importes de líneas por pedido.

Función de Valores de Tabla en Línea (dbo.GetCustomerOrders): Implementa la TVF parametrizada por cliente y pruébala tanto en consultas simples como con el operador CROSS APPLY.

Disparador y Auditoría (SalesLT.trg_LogOrderTotalChange): Crea la tabla dbo.OrderAudit y el trigger AFTER INSERT, UPDATE para registrar de forma automática cualquier alteración en los importes de pedido.

##Estructura del repositorio

lab2/
├── README.md              <-- (Este archivo explicativo del repositorio)
├── LAB_02.pdf             <-- (Documentación completa paso a paso con evidencias)
└── img/                   <-- (Carpeta con las capturas de pantalla de ejecución en SSMS)
    ├── Conectar-AdventureWorksLT.png
    ├── Creacion-vista.png
    ├── Creacion-vista-2.png
    ├── Procedimiento-almacenado.png
    ├── Procedimiento-almacenado-2.png
    ├── Calculos-reutilizables.png
    ├── Calculos-reutilizables-2.png
    ├── TVF.png
    ├── TVF-2.png
    ├── TVF-3.png
    └── Registro-cambios.png
