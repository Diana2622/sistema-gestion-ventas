# Sistema de Gestión de Ventas

Repositorio utilizado para aplicar la Gestión de la Configuración del Software (GCS) y el Control de Cambios.

## Descripción

El proyecto corresponde a un Sistema de Gestión de Ventas que permite organizar información relacionada con clientes, proveedores, usuarios y ventas.

## Gestión de la Configuración del Software

La GCS permite controlar y mantener identificados los elementos importantes del proyecto, sus versiones y los cambios realizados.

### Elementos de configuración

- Documentos de requisitos.
- Modelos y diagramas UML.
- Código fuente.
- Pruebas.
- Configuración del proyecto.
- Bitácora de cambios.

## Baseline

Se establece una Baseline inicial identificada como:

**BL-01 – Versión inicial aprobada**

Esta Baseline representa el estado aprobado de los requisitos y modelos iniciales del sistema antes de realizar cambios.

## Solicitud de Cambio CR-001

El cliente solicita:

- Integración con una pasarela de pagos externa.
- Implementación de autenticación en dos factores (2FA).

El cambio afecta los requisitos, modelos, código fuente, pruebas, configuración y documentación.

## Trazabilidad

El cambio se relaciona mediante la siguiente cadena:

**Solicitud de cambio → Requisitos → Diseño → Código → Pruebas → Resultado**

Esto permite conocer el origen y el impacto de cada modificación.

## Control de versiones

El repositorio utiliza ramas para organizar el desarrollo y controlar los cambios.

- **principal:** versión estable del proyecto.
- **feature/pasarela-pagos:** desarrollo de la integración de pagos.
- **feature/autenticacion-2fa:** desarrollo de la autenticación 2FA.
- **release/v1.1:** preparación de la versión actualizada.

## Auditoría

Los cambios se registran en la bitácora ubicada en:

`auditorios/bitácora-cambios.md`

La bitácora permite registrar la fecha, versión, cambio realizado, responsable y estado.

## Organización del repositorio

- `documentos/` → requisitos y documentación.
- `modelado/` → diagramas y modelos UML.
- `codigo/` → código fuente.
- `pruebas/` → casos y resultados de pruebas.
- `configuracion/` → configuración del proyecto.
- `auditorios/` → registro y seguimiento de cambios.

## Proyecto académico

**Estudiante:** Diana Carolina Montilla Aguirre  - Eider Stiven Narvaez
**Programa:** Ingeniería de Sistemas  
**Institución:** Corporación Universitaria Remington  
**Asignatura:** Ingeniería de Software  
**Docente:** Ricardo Zambrano  
**Año:** 2026
