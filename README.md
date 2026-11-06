El código que se encuentra libre dentro de la carpeta principal será considerado como el código con nueva dinámica,
parámetros DH modificados, interfaz modificada y movimiento con lazo cerrado por encoders; Posteriormente se encontrarán 3 carpetas
extras las cuales se ordenan por "gui_version_antigua", "gui_de_mov_C" y "gui alternativo", en gui_version_antigua será la
original previa a mi intervención, en gui alternativo encontraras una interfáz de control con los parámetros de DH originales,
dinámica original pero con la interfaz modificada y conservando el control de lazo cerrado, en gui_de_mov_C conserva los
parámetros de DH originales y la dinámica original pero con la interfaz modificada y la mosión es a ciegas (por eso la C)
sin usar los encoders siendo de lazo abierto (esta última fue la que se uso para la entrega de avance a anaya).


Para acceder a las diferentes interfaces de control se debe de descargar el .rar de nombre PROGRAMACIÓN

A LA FECHA DE SUBIDO/ACTUALIZADO ESTE REPOSITORIO, LA ESP32 DEL ROBOT SE ENCUENTRA FLASHEADA PARA USAR LA INTERFAZ DE CONTROL gui_de_mov_C
ANTES RE USAR UNA INTERFAZ DIFERENTE REVISAR SI ESTÁ LA ESP32 FLASHEADA CON EL FIRMWARE ADECUADO PARA DICHA INTERFAZ

REVISAR EL CABLEADO, POR FAVOR CAMBIAR LOS CABLES DE LOS ENCODER DEL M2 Y M3
