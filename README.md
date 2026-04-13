# Mateo Legal Guatemala

**Mateo Legal Guatemala** es un agente de inteligencia artificial diseñado para brindar **orientación jurídica preliminar** dentro de un entorno web publicado, con acceso controlado y enfoque profesional.

El proyecto fue desarrollado como una solución funcional que integra interfaz web, backend, automatización, base de datos y lógica de respuesta estructurada para consultas jurídicas dentro de un alcance definido.

## Problema que resuelve

En el contexto jurídico, muchas consultas iniciales requieren una primera orientación clara y ordenada antes de pasar a un análisis profesional más profundo. Atender esa etapa de forma manual consume tiempo, y hacerlo con herramientas generalistas de IA puede producir respuestas variables o poco útiles para un entorno profesional.

Mateo Legal Guatemala busca mejorar esa primera interacción mediante una orientación preliminar más estructurada, consistente y delimitada.

## Propuesta de valor

La propuesta de valor del proyecto consiste en ofrecer una experiencia de consulta jurídica preliminar más ordenada que la de un chatbot generalista, integrando:

- clasificación inicial de la consulta
- recuperación de apoyo contextual
- respuesta estructurada
- acceso controlado
- entorno web funcional

## Materias cubiertas

El agente está delimitado a cuatro materias jurídicas del derecho guatemalteco:

- Derecho civil
- Derecho mercantil
- Derecho laboral
- Derecho notarial

## Alcance y límites

Mateo Legal Guatemala fue diseñado como una herramienta de **orientación jurídica preliminar**. No sustituye la asesoría ni el criterio profesional de un abogado.

Las consultas fuera de las materias cubiertas o aquellas que no contengan suficiente información pueden ser tratadas como fuera de alcance o ambiguas.

## Stack tecnológico

El proyecto integra los siguientes componentes a nivel general:

1. **WordPress** como entorno web de publicación  
2. **Widget frontend en HTML, CSS y JavaScript** para la interacción conversacional  
3. **FastAPI** como backend para autenticación, sesiones y comunicación con el flujo interno  
4. **n8n** como motor de automatización y orquestación  
5. **PostgreSQL** como base de datos de apoyo  
6. **OpenAI API** para clasificación y generación de respuestas  
7. **Nginx** como capa de infraestructura y protección adicional  
8. **VPS** como entorno de despliegue del backend del proyecto  

## Arquitectura general

A nivel general, el flujo del sistema opera así:

**Usuario → sitio web → backend/API → automatización → lógica de IA y apoyo contextual → respuesta estructurada → frontend**

## Cómo funciona

De forma resumida, el agente sigue esta secuencia:

1. El usuario ingresa al entorno web.  
2. Accede al chat dentro del entorno de prueba.  
3. Envía una consulta jurídica.  
4. El sistema clasifica la consulta.  
5. Recupera apoyo contextual.  
6. Genera una respuesta estructurada.  
7. Devuelve la respuesta al sitio para su visualización.  

## Capturas del proyecto

Aquí puedes incluir capturas como estas:

- Página principal del sitio
- Acceso al entorno de prueba
- Chat en funcionamiento
- Ejemplo de consulta dentro de alcance
- Ejemplo de respuesta estructurada

## Estado actual del proyecto

Proyecto funcional y publicado en entorno web de validación.

## Acceso al sitio

El proyecto se encuentra publicado en un entorno funcional.

Por tratarse de una fase de validación controlada, el acceso de prueba no se publica en este repositorio abierto.

## Documentación

Este repositorio presenta la descripción general del proyecto, su enfoque, stack tecnológico, arquitectura a alto nivel y evidencias visuales seleccionadas.

Determinados componentes internos de implementación no se publican por razones de seguridad y protección de la solución.

## Mejoras futuras

Entre las principales líneas de mejora futura se encuentran:

- ampliación progresiva de cobertura temática
- mejoras de experiencia de usuario
- mayor trazabilidad y analítica de uso
- evolución hacia una versión más robusta a nivel operativo

## Autor

**Jaime Eduardo Blanco**
