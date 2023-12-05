# IAW05_Tarea
Esta tarea consiste en realizar las siguientes tareas:


RA5_a: Se han identificado los lenguajes de guiones de servidor más relevantes.

    Indicar cinco lenguajes de guiones de servidor ampliamente utilizados.

RA5_c: Se ha reconocido la sintaxis básica de un lenguaje de guiones concreto.

    Indicar las dos formas más utilizadas de incluir comentarios en scripts en lenguaje php.

RA5_d: Se han utilizado estructuras de control del lenguaje.

    Diseñar un programa en php que calcula la potencia de una variable base $b elevado al exponente $e.
    Utilizar un bucle para ello. No se puede utilizar ninguna función matemática de php (como pow()).

    Con el programa diseñado antes, crear una función llamada potencia(), que acepta dos parámetros obligatorios $b y $e, y devuelve el resultado de $b elevado a $e. Controlar errores, como por ejemplo que no se devuelva nada si los parámetros no son números o están vacíos, o que cualquier número elevado a 0 da como resultado 1.
    Publicar una página llamada operacion.php, en la que se muestra la ejecución de la función potencia() con distintos parámetros, para demostrar que funciona bien.

RA5_f: Se han utilizado formularios para introducir información.

    Crear una página llamada datos.php. Página de recogida de datos con los siguientes requisitos:
        Esta página contendrá un formulario en el que se mostrarán campos para almacenar los datos del usuario:
            Nombre.
            Apellidos.
            email.
        Estos datos se podrán hacer persistentes con el botón etiquetado como "Guardar datos".

    Añadir la siguiente funcionalidad al script datos.php:
        Para que se guarden los datos todos los campos tienen que estar informados. Si no se dará un mensaje de error.
        El método a usar por el formulario será POST y el atributo action será la misma página. Al pulsar este botón los datos se guardan en variables de sesión con el mismo nombre.
        En caso de que ya exista una sesión, está página mostrará los campos del formulario con los contenidos de la sesión.
        La página incluye un enlace a la página sesion.php.
        Se valorará el diseño de la página.

    Crear un script sesion.php: Página que mostrará información sobre la sesión activa, que contendrá la siguiente información:
        Si la sesión está activa, la página, mostrará todos los datos almacenados en la sesión (nombre, apellidos y email).
        Un formulario para cerrar la sesión pulsando un botón "Destruir sesión", y con destino a la página sesion.php.
        La página incluye un enlace a la página datos.php.
        Se valorará el diseño de la página.

RA5_i: Se ha verificado el aislamiento del entorno específico de cada usuario.

    Explicar brevemente si en condiciones normales, es posible que un usuario tenga acceso a los datos de sesión de otros usuarios.
