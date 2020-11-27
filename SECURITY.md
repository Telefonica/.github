# Políticas y buenas prácticas de seguridad

English version below
   
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
 
En caso de dudas sobre las herramientas autorizadas sobre escaneo de código, consultar con tu área de Seguridad/CISO.

## 5 Prácticas de seguridad en el despliegue.

Asegurar que donde se despliega, el código no provoca defectos de bastionado.

-	No se usan contraseñas en claro.
-	No se modifican los permisos de los servidores de forma amplia (777)
-	Si el código necesita TLS, recordar que es a partir de la version 1.2.
-	Si se guardan datos de carácter personal, hazlo de forma segura. 

En cualquier caso se debe revisar el despliegue basándose en las guías CIS nivel 2 server.

# Security policies and good practices 

## 1. Security practices in application development. 

You must consider good practices in the development of applications following the SDLC model (Software Development Life Cycle) in the definition, development, implementation, and maintenance of the code. 

 

## 2. Security practices in secure coding. 

- Apply these good practices in secure coding among others: 

- Validate entries. 

- Encrypt outputs. 

- Establish an adequate programming style. 

- Managing the changes log. 

- Establish cryptographic practices when appropriate using strong encryption algorithms. 

- Properly handling the files that are part of the code. 

- Establish standardization and reuse processes. 

- Apply security functions. 

- Encrypt sensitive information (such as credentials) in the repositories, regardless of the environment 

- Not include information that could be sensitive in the comments of the source code. 

- For a complete list, contact your Security/CISO area. 

 

## 3. Development standards. 

Follow the secure development standards established in: 

- OWASP 

- NIST 

- ISO 21827 (System Security Engineering - Capability Madurity Model SSE-CMM) 

 

## 4. Code analysis tools. 

Use code analysis tools verified by the organization and validate that the code contemplates: 

**- The inexistence of critical incidents 

**- 80% coverage 

In case of doubts about the authorized tools for code scanning, consult with your Security/CISO area. 

 

## 5. Security practices in the deployment. 

Ensure that where the code is deployed, it does not cause bastioning defects. 

- Do not use passwords in clear. 

- Do not modify the permissions of the servers in a broad way (777). 

- If the code needs TLS, remember to use it from version 1.2. 

- If you save personal data, do it safely. 

- In any case, the deployment should be reviewed based on the CIS level 2 server guidelines 

