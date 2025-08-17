# PowerShell-Ciberseguridad

Este repositorio contiene scripts en PowerShell para realizar auditorías básicas en Windows.

Contenido:

Script 1 (Principal.ps1, AuditoriaBasica.psm1, Manifesto.txt):

  Principal.ps1: consiste en un menu inteactivo en el cual, deperndiendo de la opcion seleccionada podras acceder al modulo, ya sea para mostrar los usuarios activos o    los servicios de terceros que se esten ejecutando.

  AuditoriaBasica.psm1: contiene el código del módulo, en las cuales se encuentran las funciones que componen la funcionalidad del módulo

  Manifesto.txt: contiene el comando para crear el manifesto del modulo, el cual describe el contenido del modulo
  
  Módulos personalizados:

  Obtener-UsuariosInactivos: detecta cuentas locales habilitadas sin logon.

  Obtener-ServiciosExternos: muestra servicios de terceros activos.
  
Script 2 (ejercicio_4.ps1):

  Usuarios activos: identifica qué cuentas nunca han iniciado sesión y cuáles sí.

Tareas que resuelven:

  Deteccion de cuentas activas, innecesarias o sospechosas.

  Identificar software de terceros corriendo en segundo plano.

  Generar reportes automáticos en .txt, .csv y .html.

Aprendizajes:

  Automatizar tareas de auditoría con PowerShell.

  Uso de pipes, filtros y módulos personalizados.

  Exportación de resultados en diferentes formatos.

Autor:
Abraham Puente
