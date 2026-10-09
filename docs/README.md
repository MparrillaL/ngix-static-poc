# Guadalquivir Cloud Tech — Landing

PoC de infraestructura: landing corporativa estática servida por Nginx en Docker con hardening HTTP básico.

**Módulo:** 0614 Despliegue de Aplicaciones Web — 2º DAW  
**Empresa ficticia:** Guadalquivir Cloud Tech (Sevilla)

## Descripción

Antes de migrar la plataforma de un cliente corporativo, se valida la infraestructura de contenedores en local. Esta PoC construye una landing estática mínima servida por Nginx en Docker, con hardening HTTP básico, bind mount de solo lectura y logs redirigidos a `stdout`/`stderr`.

Durante la fase de diseño se han definido dos artefactos previos al desarrollo:

- **Wireframe:** estructura de secciones, sin estilos.
- **Mockup:** representación visual de referencia, con paleta, tipografía y espaciados.

---

## Wireframe

Esquema de baja fidelidad con la estructura de secciones de la landing, sin estilos ni decisiones visuales.