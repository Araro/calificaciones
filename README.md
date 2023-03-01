# Formato de calificaciones

En el presente repositorio podrás descargar el formato para llevar el control de calificaciones por materia.

## Instrucciones

### Pestaña "Alumnos"
En esta pestaña debe realizar el llenado de los datos principales de la materia a evaluar.

1. Realice el llenado de los datos del profesor, en donde deberá introducir el nombre del profesor, la academia a la cual pertenece y el periodo que se esta evaluando.
2. Introduzca la información en e el apartado de datos de la asignatura, deberá escribir el nombre de la asignatura, a que grupo se va a impartir y el número de temas (Unidades) que se van a evaluar (Hasta un máximo de 10 Temas).
    - Nota : El número de temas (Unidades) que introduzca en el formato activara las pestañas correspondientes de cada tema para poder realizar la evaluación, asegurese de introducir el número de temas correcto.
3. La celda de número de alumnos se actualizará automaticamente cuando realice el llenado de la lista de asistencia, especificamente de la columna "NO. DE CONTROL"
4. Introduzca los números de control y los nombres de los alumnos que pertenecen a la materia a evaluar.
    - La columna de "NO." se llena automaticamente dependiendo de la cantidad de números de control introduzca.
5. Las columnas de TELEFONO y OBSERVACIONES son opcionales.    

### Pestaña "Principal"
En esta pestaña se visuaiza el concentrado de las calificaciones finales de cada Tema (Unidad), así como los indices de reprobación parcial y final.
No se debe realizar ninguna modificación en esta pestaña, se llena automaticamente con la información de las otras pestañas y los datos itroducidos en la pestaña de "Alumnos"

### Pestaña "Tema N"
Esta es la pestaña donde podrá introducir las evaluaciones de cada una de las actividades realizadas durante el desarrollo de cada Tema (Unidad), de igual manera podrá realizar el pase de lista de cada sesión.
    - Nota: Se tiene hasta un máximo de 10 pestañas para evaluar Temas de la materia. Solo se activarán las pestañas de acuerdo al número de Temas que introdujo en la pestaña de "Alumnos", puede ocultar las pestañas restantes.
1. Las columnas desde la columna A hasta donde se encuentra la "Calificación Final" se llenan automaticamente, no debe modificar ninguna celda de esas colunnas.
2. Introduzca el nombre de cada rubrica de evaluación, así como el porcentaje de cada rubrica con respecto a la calificación final del Tema correspondiente. (La suma de los porcentajes de los diferentes instrumentos de evaluación debe ser 100%).
    - Nota: Puede ocultar las columnas correspondientes a la rubricas de evaluación que no se están utilizando.
3. Debajo del porcentaje de la rubrica de evaluación, coloca el nombre y número de la evaluación del instrumento. Por ejemplo, puedes colocar EV1. Si tienes mas de una evaluación de este mismo instrumento puedes colocar los que sean necesarios. EV1, EV2, EV3...
    - Nota: Si no colocas este dato, no te permitirá introducir las calificaciones correspondientes a esa columna.
    - Nota: Puede ocultar las columnas que no este utilizando para introducir alguna evaluación.
4. Si realizas más de tres evaluaciones de un mismo instrumento, puedes insertar las columnas que sean necesarias. Asegúrate de insertar dichas columnas antes de la tercera o última evaluación. No insertes columnas después de la última evaluación.
5. En el pase de asistencia es necesario introducir una fecha en formato válido para activar la columna correspondiente de pase de lista. Formato: DD-MM-AAA
Puedes darle doble click a la casilla de fecha y se desplegara una calendario para que realices la selección correspondiente.
5. En la columna de asistencia coloca un valor entre 0 y 1, donde cero es falta y 1 es asistencia completa. Puedes introducir valores intermedios dependiendo del retardo del alumno en la asistencia. (por ejemplo: 0.5)

### Pastaña "Recuperación"
En esta pestña se realiza el concentrado de las calificaciones finales de cada Tema evaluado (Unidad) y es en esta pestaña donde podra modificar las calificaciones obtenidas por parte del alumno en la etapa de recuperación de la materia.
1. En la pestaña de recuperación, se cargarán las calificaciones del curso normal, además, se mostrarán en color amarillo los temas que debe presentar el alumno. En esa pestaña debes colocar de forma manual la calificación obtenida en la recuperación, al momento de actualizar se borrará la formula.
2. Cuando cambies la calificación y esta sea aprobatoria la celda cambiará a color verde, indicando que el alumno ha aprobado la materia en modo de recuperación, si la calificación no es aprobatoria se celda se mostrará de color amarillo.

## Observaciones
Si encuentras algún error o detalle en el presente formato, nos ayudaría mucho que levantaras un ticket para seguir mejorando el formato.
