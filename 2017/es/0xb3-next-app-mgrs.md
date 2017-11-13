# +A: ¿Que sigue para los Administradores de Aplicaciones?

## Administre el Completo Ciclo de Vida de la Aplicación

Las aplicaciones son algunos de los sistemas más complejos que los humanos crean y mantienen regularmente. La administración TI (Tecnología de la Información) para una aplicación debería ser ejecutada por especialistas en TI que sean responsables por el completo ciclo de vida de la misma.

Sugerimos la designación de propietarios y administradores para cada aplicación a los efectos de proveer (accountability, responsibility, consulted and informed (RACI)). El administrador de la aplicación es la contraparte técnica del propietario de la aplicación desde la perspectiva del negocio y administra el completo ciclo de vida de la aplicación, incluyendo la seguridad de una aplicación, activos de datos asociados, y documentación. Esto puede ayudar a entender quién puede aceptar los riesgos, y quién es responsable de incluir la seguridad.

## Administración de Requerimientos y Recursos

* Recolectar y negociar los requerimientos de negocios para una aplicación, incluyendo la recepción de los requerimientos de protección en vista a la confidencialidad, integridad y disponibilidad de todos los activos de datos.
* Compilar los requerimientos técnicos incluyendo requerimientos de seguridad funcionales y no funcionales.
* Planear y negociar el presupuesto que cubre todos los aspectos de diseño, construcción, testeo y operación, incluyendo actividades de seguridad.

## Solicitud de Propuestas (RFP por sus siglas en inglés) y su Adopción

* Negociar los requerimientos con desarrolladores internos y externos, incluyendo lineamientos y requerimientos de seguridad con respecto a su programa de seguridad, p.ej. SDLC, mejores prácticas.
* Evaluar el cumplimiento de todos los requerimientos técnicos incluyendo un borrador de planeamiento y diseño.
* Negociar todos los requerimientos técnicos incluyendo diseño, seguridad y acuerdos de nivel de servicio (SLA por sus siglas en inglés).
* Considere usar plantillas y listas de comprobación, tal como [Anexo de Contrato de Software Seguro de OWASP](https://www.owasp.org/index.php/OWASP_Secure_Software_Contract_Annex) **NB**: El Anexo es un ejemplo específico a las leyes de contrato de EUA, y probablemente necesitará de revisión legale en su jurisdicción. Por favor obtenga consejo legal calificado antes de usar el Anexo.

## Planeamiento y Diseño

* Negociar el planeamiento y diseño con los desarrolladores e interesados internos, p. ej. especialistas de securidad.
* Definir una arquitectura de seguridad, controles, y contramedidas de acuerdo a las necesidades de protección y el nivel planeado de seguridad ambiental. Esto debería contar con el soporte de especialistas en seguridad.
* Haga que el propietario de la aplicación asuma los riesgos remanentes o bien que provea recursos adicionales.
* En cada etapa, asegúrese de que se crean historiales de seguridad para requerimientos funcionales, y se agreguen restricciones para requerimientos no funcionales.

## Desarrollo

* Por favor revise +D "¿Qué sigue para desarrolladores" para guía.

## Deployment, Testing and Rollout

* It's critical that security tasks automated the secure setup of the application, interfaces and of all further components needed, including required authorizations
* Test the technical functions and integration to the IT architecture, and coordinate business tests. Consider to test use and abuse cases from technical and business perspectives.
* Manage security tests according to internal processes, the protection needs and the level of security where the application is going to be deployed
* Put the application in operation and migrate from previously used applications
* Finalize all documentation, including the CMDB and security architecture

## Operating and Changes

* Operating including the security management for the application (e.g. patch management)
* Regularly report all users and authorizations to the application owner and get them acknowledged
* Raise the security awareness of users and manage conflicts about usability vs security
* Plan and manage changes, e.g. migrate to new versions of the application or other components like OS, middleware and libraries
* Update all documentation, including in CMDB and the security architecture, controls, and countermeasures, including any runbooks or project documentation

## Retiring Systems

* Implement business requirements for data retention (deletion) policies and securely archiving data
* Securely close down the application, including deleting unused accounts and roles and permissions
* Set your application’s state to retired in the CMDB
