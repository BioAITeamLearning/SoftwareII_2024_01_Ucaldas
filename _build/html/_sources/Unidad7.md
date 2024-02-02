---
title: Unidad 7
---
# Unidad 7: Especificación y formatos para HU y CU

## Contenido de la unidad

<img src="_static/images/contenidoU7.png"/>

## Especificación de casos de uso

* Generalmente hay pocos actores asociados a los casos de uso.

* Se relaciona con las historias de usuario

<img src="_static/images/U7_1.png"/>

---

<img src="_static/images/U7_2.png"/>

---

## Formato de especificación de casos de uso

* Las precondiciones **NO** necesariamente son entradas. Ejemplo: El usuario debe estar autenticado.

* Las postcondiciones **NO** necesariamente son salidas. Ejemplo: Almacena la información en la base de datos.


<img src="_static/images/U7_3.png"/>

---

## Formato de especificación de casos de uso: Flujos básicos

Los flujos básicos describen las interacciones entre el actor y el sistema (numerados).

* Deben especificarse los datos de entrada y de salida 
* Los cálculos y validaciones que se deben realizar
* Debe ser entendido por el usuario.


<img src="_static/images/U7_4.png"/>

```<<include>>``` Cuando esta característica se menciona es porque un Caso de Uso llama de manera obligatoria a otro.

---

## Formato de especificación de casos de uso: Flujos alternativos


Los flujos alternativos son los que pueden pasar cuando se presentan errores (tanto del usuario como del sistema) 
o cuando el usuario toma alguna decisión que lleva a acciones alternas o complementarias al flujo normal básico.

Cuando se formule el flujo alternativo, se debe evidenciar el caso de uso que se está extendiendo. 

<img src="_static/images/U7_5.png"/>

```<<extend>>``` Cuando esta característica se menciona es porque un Caso de Uso puede llamar a otro.

---
## Ejemplo de especificación de casos de uso: Asignar una cita

<img src="_static/images/U7_6.png"/>


### Escenarios:

* Se asigna exitosamente
* Paciente  no registrado
* Error al ingresar el documento
* No hay citas disponibles

---

### Modelado del caso de uso

<img src="_static/images/U7_7.png"/>

```{warning}
OJO: El paciente no se modela ya que no es un actor directo del sistema a desarrollar. 
```

---

### Especificación de casos de uso: Asignar una cita

<img src="_static/images/U7_8.png"/>

---
###  Flujo normal básico de eventos

<img src="_static/images/U7_8_1.png"/>

---

### Flujo alternativo de eventos: Paciente no registrado

<img src="_static/images/U7_9.png"/>

---

### ¿Cómo queda el formato?

<img src="_static/images/U7_10.png"/>


::::{card-carousel} 1

:::{card}
:margin: 3
:class-body: text-center
:class-header: bg-light text-center
:link: https://github.com/BioAITeamLearning/SoftwareII_2023_03_Ucaldas/raw/main/Unidades/Unidad_7/Ejemplo_especificacionCasoUso.docx
**💬 Recurso extra!**
^^^
```{image} https://gcloud.devoteam.com/wp-content/uploads/sites/32/2021/08/Google_Docs_logo_2014-2020.svg.png
:height: 100
```

Recurso Extra: Diagramas y especificación de casos de uso
+++
Explore this book {fas}`arrow-right`
:::
::::

---

## Otro ejemplo de especificación de casos de uso:

<img src="_static/images/U7_11.png"/>

---

## Ejercicio

:::{admonition} Ejercicio

<img src="https://www.acentoespanol.com/wp-content/uploads/2019/11/2e1ax_nomad_entry_shutterstock_129399062.jpg"/>

Teniendo en cuenta los objetivos planteados, realice los diagramas de caso de uso y la especificación.

**Objetivo del proyecto:** Desarrollar un sistema de gestión de ventas en línea para mejorar la eficiencia y la experiencia del usuario.

**Objetivo de negocio:** Incrementar la cantidad de ventas en línea y mejorar la satisfacción del cliente mediante la implementación de un sistema de gestión de ventas en línea que permita una mayor eficiencia en el proceso de compra y una mejor experiencia de usuario en la plataforma.

:::

:::{dropdown} Solución

<img src="_static/images/U7_12.png"/>
:::