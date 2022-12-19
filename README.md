# EjParcial

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.1.3.

Primer Parcial Programación Web ISTEA

En la empresa donde usted se encuentra prestando sus servicios como analista y desarrollador
de sistemas están actualmente realizando un sitio web de uno de los clientes Bancarios más
importantes y su líder técnico le encomendó realizar los siguientes componentes dentro del
sitio web:

1. Vista Menu-component:

Crear un componente el cual puede ser una barra Lateral Izquierda o un conjunto
agrupado de botones que re direccionen a los componentes del punto 2 (formulario) y
3 (tabla), este componente le permitirá al user navegar por las diferentes opciones
dentro de la aplicación

2) Al presionar la opción de “Tools” del menú deberá mostrarse un formulario que le
permitirá al usuario cargar sus datos (apellido , nombre , correo , operador , papel ) , todos
los campos son obligatorios y el botón de “cambiar contraseña solo debe aparecer si están
presente todos los input “ caso contrario debe estar oculto , al presionar el botón de
“cambiar contraseña” por la consola del navegador se debe mostrar una password que
debe ser generada de manera automática (lo muestran mediante un console.log() y usar
algún función como por ej Math.random())

3) Al presionar el botón “Dashboard”
Deberá ser visualizado una tabla como la siguiente:

Esta vista debe poseer un filtro que permita filtrar el listado de la tabla por país
Le brindaron el siguiente Json para que lo tome de ejemplo a la hora de generar los datos
para el servicio que proveerá la información con la cual se renderiza la tabla html
[
 {
    "country": "BRA",
    "client": "HCI",
    "Balance": 100033,
    "moneda": "reales", 
  },
  {
    "country": "CHL",
    "client": "I-Payout",
    "Balance": 100033,
    "moneda": "dolar", 
  },
  {
    "country": "ARG",
    "client": "Wester",
    "Balance": 1053413,
    "moneda": "pesos", 
  },
  {
    "country": "COL",
    "client": "thunes",
    "Balance": 1543033,
    "moneda": "dolar", 
  },
  {
    "country": "MEX",
    "client": "HCI",
    "Balance": 1123033,
    "moneda": "dolar", 
  },
  {
    "country": "URY",
    "client": "Nium",
    "Balance": 179033,
    "moneda": "dolar", 
  }

]

Importante:

Se deberán entregar el proyecto a más tardar el día lunes 11/10/2022 a las 22:00hs en la tarea
asignada al classRoom pasado ese horario no se recibirán más exámenes por ningún otro
medio
Subir el examen sin la carpeta “nodeModules”

 Toda Imagen es ilustrativa y no es necesario que el examen entregado sea
exactamente igual a las fotos
