# segundaentregajs
Readme Segunda entrega final mejoras al simulador

-Reemplacé la estructura HTML (que había hecho con las cards de bootstrap) por un array de objetos que a través de un bucle y DOM
Se imprimen en pantalla 
-A través de una gran función (que contiene a su vez otras dos para sumar y multiplicar), que contiene un evento click, 
envío al local Storage los equipos seleccionados por el usuario, estos a su vez se consumen desde el local storage creando un array 
con la seleccion del usuario. 
- A través de un reduce recorro el array extrayendo el precio y luego los sumo. 
- a través del DOM voy imprimiendo la selección del usuario y el subtotal (se van sumando los equipos) 
-solicito al usuario (a través de un form) que indique la cantidad de jornadas que alquilará los equipos. Con otro evento click
calculo el total final(obtengo el valor ingresado en el form y lo multiplico, a través de una función, por la suma de los equipos elegidos) 
- finalmente imprimo el valor total del alquiler en pantalla por DOM.
- // UTILIZO UN CONDICIONAL PARA ESTABLECER EL FUNCIONAMIENTO CORRECTO DEL SIMULADOR TENIENDO EN CUENTA SI EL STORAGE TIENE INFO O NO
 (ESTO MODIFICARÁ LA FORMA DE FUNCIONAR DEL SIMULADOR.) DENTRO DE ESTE CONDICIONAL DECALRO LA FUNCIÓN MAESTRA Y TAMBIÉN UN COMPORTAMIENTO
 PARA QUE EN CASO DE TILDAR UN EQUIPO POR ERROR, TOCANDOLO DE NUEVO  SE BORRE DEL HTML Y DEL STORAGE.
-En el local Storage cargo los datos que el usuario me brinda, y también los consumo para hacer los calculos y devolverle el total. 
