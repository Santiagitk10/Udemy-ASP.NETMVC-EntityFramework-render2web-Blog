# Udemy-ASP.NETMVC-EntityFramework-render2web-Blog


## Migración cuando se agrega una entidad

- En VisualStudio -> Herramientas -> Administrador de paquetes nuget -> Consola
- Recordar tener en "Proyecto predeterminado" el proyecto donde tenemos la capa de acceso a datos
- add-migration CreacionTablaArticulo
- update-database para actualizar la base de datos
Nota: Cada que se haga un cambio en la base de datos, ejemplo el tipo de datos de una columna, se debe agregar una nueva migración y luego hacer el update para que se refleje en la base de datos


## Scaffolding para identity framework. Rocordar que este scaffolding carca con la metodología Razor. Es decir con cshmtl y con archivo csharp asociado

- Sobre la solución. Limpiar la solución
- Compilar la solución
- Click derecho proyecto principal -> Agregar nuevo elemento con scaffold -> Identidad
- Seleccionar las páginas que se deseen, en este caso todas
- Seleccionar el contexto
