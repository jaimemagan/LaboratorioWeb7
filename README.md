¿Cuál es la diferencia entre autenticación y autorizacion?
la autenticacion puede verificar la identidad del usuario como ejemplo 
el usuario , contraseña. y la autorizacion es quien determina el permmiso que tinene un usuario 
dentro del sistema como editar , eliminar o solo leer los datos .

¿Cuál es la función del token JWT en la guía?
tenemos lo que es la autenticacion sin estado la que nos permite identificar al usuario sin guardar sesiones 
en el servidor . la seguridad se envia a la cabecera HTTP para validar el acceso a rutas protegidas .
el middleware verifytoken este verifica el token antes de permitir el acceso a recusros restringidos 
