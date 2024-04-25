# Parcial Sistema de registro de Concesionario.

### Necesidad: Se tiene un concesionario donde se quiere desarrollar un sistema que permita llevar el registro de la siguiente infomación; Categoría de carros que lleve un `Id`, `nombre categoria`, `descripcón` y `distintivo`.Autos con `Id`, `nombre`, `marca`, `año de fabricación`, `precio` y `ref: Categoria de carros`. AutosPersona `Id`, `nombre`, `ref: Autos`, `ref: Persona`. Persona `Id`, `nombre`, `edad`, `genero`, `dirección` y `ocupación`. En el cual se tiene una relación de un Auto con su respectiva Categoria de carros y una relación de AutosPersona con Autos y Persona.  


#### Análisis: Definición de requerimientos. 

* Categoria de carros {Id, nombre, descripción, distintivo}
* Autos{Id, nombre, marca, año de fabricación, precio, ref:categoria de carros}
* AutosPersona {Id, nombre, ref:Autos, ref:persona}
* Persona {Id, nombre, edad, genero, direccion y ocupación}

1. RF1: Realizar la CRUD de categoria de carros, donde se requiere la siguiente estructura de la entidad : `categorria de carros {Id, nombre, descripción, distintivo}`.
- No puede existir un auto con el mismo Id
2. RF2: Realizar la CRUD de Autos que lleve la siguiente estructura: `Autos{Id, nombre, marca, año de fabricación, precio, ref:categoria de carros}`. 
3. RF3: Realizar la CRUD de AutosPersona con la siguiente estructura: `AutosPersona {Id, nombre, ref:Autos, ref:persona}`.
4. RF4: Realizar la CRUD de Persona con la siguiente estructura: `Persona {Id, nombre, edad, genero, direccion y ocupación}`.

#### Diseñar Base de Datos
Datos a tener en cuenta

`Categoria de carros`
| id |nombre | descripción| distintivo |
|----|-------|-----------|-----------|
|  1 |101gi    |C-101      |2500       |
|  2 |102    |C-102      |2400       |
|  3 |112    |B-112      |600        |
|  4 |112    |A-112      |1600       |
