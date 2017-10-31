# OpenId-Connect

> OpenID Connect te dará un token de acceso más un token de identificación . El token de identificación es un JWT y contiene información sobre el usuario autenticado. Está firmado por el proveedor de identidad y se puede leer y verificar sin acceder al proveedor de identidad.

> Además, OpenID connect estandariza un par de cosas que oauth2 deja a la elección. por ejemplo, ámbitos, descubrimiento de punto final y registro dinámico de clientes.

> Esto hace que sea más fácil escribir código que le permita al usuario elegir entre múltiples proveedores de identidad

## Un patrón común para la API de OpenID Connect es tres pasos: 
+ Obtener un código 
+ Obtener fichas como el access_token, refresh_tokeny id_token
+ Obtener información del usuario que contiene afirmaciones como nombre de usuario, correo electrónico, etc. 
