# Funciones

Las funciones son los componentes básicos de los programas Move. Se llaman desde transacciones de usuario y desde otras funciones y agrupan el código ejecutable en unidades reutilizables. Las funciones pueden tomar argumentos y devolver un valor. Se declaran con la palabra clave `fun` a nivel de módulo. Como cualquier otro miembro de un módulo, por defecto son privadas y sólo se puede acceder a ellas desde dentro del propio módulo. Sin embargo, es posible cambiar este funcionamiento con modificadores de visibilidad.

## Ejecutando el tutorial

> :information_source: Recuerda que debes navegar en tu terminal a este directorio:
>```sh
>cd backend/10_funciones
>```

Ingresa a tu terminal y ejecuta el siguiente comando:

```sh
sui move test
```

Deberías de obtener algo similar a esto:
```sh
INCLUDING DEPENDENCY Bridge
INCLUDING DEPENDENCY SuiSystem
INCLUDING DEPENDENCY Sui
INCLUDING DEPENDENCY MoveStdlib
BUILDING Funciones
Running Move unit tests
[debug] false
[debug] 1
[debug] 2
[ PASS    ] suiz3::funciones1::prueba
[debug] "Hola desde funciones1!"
[debug] "Sui"
[debug] 0
[debug] 100
[debug] "Hola desde funciones1!"
[debug] "Hola desde funciones1!"
[debug] "Hola desde funciones1!"
[ PASS    ] suiz3::funciones3::prueba
[debug] 200
[ PASS    ] suiz3::funciones2::prueba
[ PASS    ] suiz3::funciones4::prueba
Test result: OK. Total tests: 4; passed: 4; failed: 0
```

## Tutorial

Puedes encontrar la documentación para este tutorial dentro del archivo `sources/funciones.move`. Cada una de las declaraciones tiene un comentario para ayudarte a entender cada uno de los temas tocados.

> :information_source: Recuerda que puedes encontrar más información sobre las habilidades en la [documentación](https://move-book.com/move-basics/function) oficial del lenguaje Move.

## Reto

Simplemente lee la documentación y asegúrate de entenderla. A partir de ahora la mayoría de tutoriales contarán con múltiples funciones.