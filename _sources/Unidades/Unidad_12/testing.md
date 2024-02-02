---
 file: testing.py
---

# Testing de Software

Las pruebas de software en sistemas grandes y que requieren programación y desarrollo en equipo se realizan a través de varios pasos y técnicas clave. Aquí hay una descripción general del proceso:

## Planificación de pruebas

* Definir los objetivos de las pruebas.
* Identificar los requisitos y criterios para la prueba.
* Establecer métricas para evaluar la efectividad de las pruebas.

## Diseño de casos de prueba

* Desarrollar casos de prueba que cubran todas las funciones del software.
* Incluir pruebas para casos de uso normales y anormales.
* Priorizar los casos de prueba basados en factores como el riesgo y la importancia.

## Entorno de pruebas

* Configurar un entorno de pruebas que simule condiciones de producción.
* Asegurar que todas las herramientas y recursos necesarios estén disponibles.

## Automatización de pruebas

* Utilizar herramientas de automatización para pruebas repetitivas y de regresión.
* Desarrollar scripts que permitan la ejecución de pruebas de manera eficiente.

## Pruebas Unitarias

* Realizar pruebas a nivel de componente o unidad para validar que cada parte del código funcione correctamente.
* A menudo realizadas por los desarrolladores.

## Pruebas de integración

* Probar la interacción entre diferentes módulos o servicios.
* Detectar problemas en las interfaces y en la integración de componentes.

## Pruebas de sistema

* Evaluar el sistema completo para asegurar que cumple con los requisitos especificados.
* Incluir pruebas de funcionalidad, rendimiento y seguridad.

## Pruebas de aceptación

* Realizar pruebas que reflejen el uso real del sistema por parte de los usuarios finales.
* A menudo involucra a clientes o usuarios finales en el proceso.

## Gestión de defectos

* Registrar y hacer seguimiento de los defectos encontrados.
* Priorizar la corrección de defectos basándose en su severidad e impacto.

## Revisiones y retrospectivas

* Analizar los resultados de las pruebas y discutir formas de mejorar el proceso de pruebas.
* Ajustar las estrategias y planes de prueba según sea necesario.

## Colaboración y comunicicación

* Mantener una comunicación efectiva entre los miembros del equipo y otros stakeholders.
* Utilizar herramientas de gestión de proyectos y seguimiento de defectos para coordinar el trabajo.

## Pruebas continuas y entrega continua

* Integrar las pruebas en el proceso de desarrollo y despliegue continuo.
* Permitir una retroalimentación rápida y la detección temprana de problemas.

# Ejemplo de procesos de pruebas


Para ilustrar cómo se aplican las pruebas de software en un proyecto grande, usaremos un ejemplo hipotético: el desarrollo de una aplicación móvil de comercio electrónico. Este ejemplo nos permitirá explorar diferentes tipos de pruebas a lo largo del proceso de desarrollo.

**Proyecto: Aplicación Móvil de Comercio Electrónico**

1. **Planificación de Pruebas**

* **Objetivos**: Asegurar la funcionalidad, rendimiento, seguridad y usabilidad de la aplicación.
* **Requisitos**: Funciones de búsqueda de productos, carrito de compras, pagos seguros, gestión de cuentas de usuario.
* **Métricas**: Tasa de defectos, cobertura de código, tiempo de respuesta, tasa de satisfacción del usuario.

2. **Diseño de Casos de Prueba**


* **Casos para cada función:** búsqueda de productos, agregar al carrito, realizar pagos, etc.
* Pruebas para situaciones anormales como pérdida de conexión a Internet, pagos fallidos.

3. **Entorno de Pruebas**
   
* Configuración de servidores de prueba que simulan el entorno de producción.
* Disponibilidad de distintos dispositivos móviles para pruebas.

4. **Automatización de Pruebas**

* Herramientas como Selenium o Appium para pruebas automatizadas en diferentes dispositivos y sistemas operativos.

5. **Pruebas Unitarias**

* Pruebas a nivel de función o método, por ejemplo, verificar la correcta adición de un producto al carrito.

6. **Pruebas de Integración**
    
* Verificar la correcta interacción entre el sistema de carrito de compras y el sistema de pagos.

7. **Pruebas de Sistema**

* Evaluar la aplicación completa en un entorno que simule el de producción.

8. **Pruebas de Aceptación**

* Invitar a un grupo de usuarios beta para que prueben la aplicación y recolectar su feedback.

9. **Gestión de Defectos (BUGS)🐞**

* Uso de herramientas como JIRA para registrar y gestionar los defectos encontrados.

10. **Revisiones y Retrospectivas**

* Análisis de los resultados de las pruebas después de cada sprint (si se usa metodología ágil).
  
11. **Colaboración y Comunicación**

* Reuniones regulares del equipo, uso de herramientas de comunicación y gestión de proyectos.

12. **Pruebas Continuas y Entrega Continua**

* Integración continua de código y pruebas automáticas en cada fase del desarrollo.

---

## Sesión práctica de Testing (unitarias, integración)

::::{card-carousel} 1

:::{card}
:margin: 3
:class-body: text-center
:class-header: bg-light text-center
:link: https://github.com/johanpina/testing_class/tree/main
**💬 Repositorio de testing**
^^^
```{image} https://banner2.cleanpng.com/20180331/udw/kisspng-social-media-github-computer-icons-logo-github-5ac0188083c4f5.8572681115225386245397.jpg
:height: 100
```

Repositorio con práctica de testing
+++
Explore this repo {fas}`arrow-right`
:::
::::