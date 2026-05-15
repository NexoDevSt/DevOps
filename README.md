\# Innovatech Chile - Etapa 2: Despliegue Automatizado



Este repositorio contiene la solución de contenedorización y microservicios para la Evaluación Parcial N°2.



\## Estructura del Proyecto

\* \*\*back-Despachos\_SpringBoot\*\*: Microservicio de gestión de despachos.

\* \*\*back-Ventas\_SpringBoot\*\*: Microservicio de gestión de ventas.

\* \*\*front\_despacho\*\*: Interfaz de usuario.

\* \*\*db-mysql\*\*: Base de datos persistente.



\## Requisitos Técnicos Implementados

\* \*\*Contenedorización Multi-stage\*\*: Imágenes optimizadas usando Eclipse Temurin y Nginx.

\* \*\*Seguridad\*\*: Ejecución con usuario no root para mínimo privilegio\[cite: 91].

\* \*\*Persistencia\*\*: Uso de Named Volumes (`mysql\_data`) para asegurar la continuidad de datos.

\* \*\*Orquestación\*\*: Stack completo gestionado con Docker Compose.



\## Instrucciones de Ejecución Local

1\. Asegúrese de tener Docker Desktop iniciado.

2\. Ejecute el comando: `docker-compose up --build`

