# Legibilidad

## Códigos

| Retos       | Enlace |
|------------------|--------|
| *Reto003Eda2* | [Repositorio](https://github.com/antoniogavilanes/23-24-eda2-ep/tree/main/entregas/antonioGavilanes/reto003) |
| *ExamenParcialPRG2*  | [Repositorio](https://github.com/antoniogavilanes/23-24-prg2-ep/tree/main/src) |
| *DBApi* | [Repositorio](https://github.com/antoniogavilanes/DB-API) |


## Nombrado

 Error tipográfico. [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L123)

No sigue la consistencia de nombres en español o inglés. [Reto003Eda2](https://github.com/antoniogavilanes/23-24-eda2-ep/blob/main/entregas/antonioGavilanes/reto003/Documento.java#12)


## Formato y Consistencia 

Uso de <"style"> vacío en HTML. [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L9).

onclick="eliminarTarea()", en vez de usar addEventListener [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L128).

if (asignatura != null) asignatura.mostrarAsignatura(); en una línea sin {} [ExamenParcialPRG2](https://github.com/antoniogavilanes/23-24-prg2-ep/blob/main/src/Profesor.java#L23)

## Comentarios

No contiene comentarios en todos los códigos.

## Código Muerto 

La estructura de los formularios de nueva tarea y editar tarea es casi idéntica. [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L22) [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L43).

## DRY

mostrarTareas() recalcula la fecha de entrega innecesariamente. [DBApi](https://github.com/antoniogavilanes/DB-API/blob/main/views/pages/index.ejs#L111)