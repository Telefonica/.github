# Políticas y buenas prácticas de seguridad
   
## 1. Practicas de seguridad en el desarrollo de aplicaciones.
   Tener en cuenta buenas prácticas en el desarrollo de aplicaciones
    siguiendo el modelo SDLC (Ciclo de vida de Desarrollo de Software)
    en la definición, desarrollo, implementación y mantenimiento del
    código.

## 2. Practicas de seguridad en la codificación segura.
 Aplicar buenas prácticas en la codificación segura. 
 Entre otras:

 - Validando entradas.
 - Codificando salidas.
 - Estableciendo un adecuado estilo de programación.
 - Manejo del log de cambios.
 - Establecimiento de prácticas criptográficas cuando proceda utilizando algoritmos de encriptación robustos.
 - Manejar adecuadamente los archivos que forman parte del código.
 - Establecer procesos de estandarización y reutilización.
 - Aplicación de funciones de seguridad.
 - Cifrando la información sensible (como credenciales) en los repositorios, independientemente del entorno.
 - No incluir información que pueda resultar sensible en los comentarios del código fuente.
 - Para conocer un listado completo, contactar con tu área de Seguridad/CISO.

## 3. Estándares de desarrollo.

Seguir los estándares de desarrollo seguro establecidos en:
 - OWASP
 - NIST
 - ISO 21827 (System Security Engineering – Capability Madurity Model SSE-CMM)

## 4. Herramientas de análisis de código.
Utilizar herramientas de análisis de código verificadas por la organización y validando que el código contemple: 

 **- La inexistencia de incidencias criticas** 
 
 **- Una cobertura del 80%**

## 5 Prácticas de seguridad en el despliegue.

Asegurar que donde se despliega, el código no provoca defectos de bastionado.

-	No se usan contraseñas en claro.
-	No se modifican los permisos de los servidores de forma amplia (777)
-	Si el código necesita TLS, recordar que es a partir de la version 1.2.
-	Si se guardan datos de carácter personal, hazlo de forma segura. 

En cualquier caso se debe revisar el despliegue basándose en las guías CIS nivel 2 server.


En caso de dudas sobre las herramientas autorizadas sobre escaneo de código, consultar con tu área de Seguridad/CISO.

