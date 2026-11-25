# Tarea 3 — Estimación
## Sistema integrado de detección de intrusiones y videovigilancia perimetral · Equipo 4 · Gestión de Proyectos · FIUNER

> **Fuente:** Documento `Tarea3_EDT_y_estimaciones_G4_vf.docx`.
> **Técnica principal:** Delphi en 2 rondas · **Control:** PERT (tres puntos) · **Estimadores:** Gabriel S., Lucía y Gabriel N. · **Coordinador:** Renzo (no estima).
> **Estimación final:** **858 horas**. **Costos:** no se incluyen (punto opcional de la consigna, no realizado).

## 3.1 Técnicas consideradas

Antes de estimar comparamos cuatro técnicas y elegimos la que mejor se ajusta al proyecto:

| Técnica | Cómo funciona | ¿La usamos? |
| --- | --- | --- |
| Delphi | Varios expertos estiman en forma anónima; un coordinador comparte los resultados y se repiten las rondas hasta llegar a consenso. | Sí, como técnica principal: da horas absolutas, que necesitamos para presupuestar y para calcular duraciones. |
| PERT (tres puntos) | Se estiman un valor optimista, uno más probable y uno pesimista, y se combinan: (O + 4M + P) / 6. | Sí, como control en los paquetes más inciertos y para el plazo de entrega de los proveedores. |
| Planning poker | Versión ágil de Delphi: el equipo vota con cartas de una serie tipo Fibonacci, en puntos relativos, y discute las diferencias. | No: estima esfuerzo relativo por sprint, y nuestra obra física se planifica con horas y presupuesto cerrado. |
| T-shirt sizing | Se asignan tallas (S, M, L, XL) según el esfuerzo relativo; sirve para planificación rápida de alto nivel. | No como estimación final: no da horas. Solo sirvió para ordenar mentalmente los paquetes antes de la ronda 1. |

## 3.2 Procedimiento Delphi

- **Coordinador:** Renzo, líder del proyecto. Preparó la EDT y el formulario, recibió las estimaciones, calculó promedios y deltas y moderó la discusión. No estimó, para no influir en los demás.
- **Estimadores (3):** Gabriel S., Lucía y Gabriel N. Cada uno estimó todos los paquetes, no solo los propios. En las tablas aparecen como Est. 1, 2 y 3, sin nombre, para mantener el anonimato.
- **Unidad:** horas de esfuerzo de la persona o del grupo que ejecuta el paquete. En la obra de la cuadrilla, son horas-operario.
- **Criterio de convergencia:** cuando el delta (diferencia entre la estimación máxima y la mínima) supera el 25 % del promedio, los estimadores que presentan los valores extremos explican los supuestos utilizados. A partir de esa discusión se revisan las estimaciones y se realiza una segunda ronda. En la segunda ronda, todos los paquetes quedaron por debajo del umbral establecido.
- **Estimación final:** se adopta el promedio de los valores obtenidos en la segunda ronda.

## 3.3 Ronda 1

En el documento original, en rojo los paquetes que superaron el umbral del 25 %.

| ID | Paquete | Est. 1 (h) | Est. 2 (h) | Est. 3 (h) | Promedio R1 | Delta R1 | Delta / prom. |
| --- | --- | :---: | :---: | :---: | :---: | :---: | :---: |
| 1.1 | Relevamiento del predio y zonas críticas | 16 | 24 | 12 | 17,3 | 12 | 69 % |
| 1.2 | Diseño de detección y cobertura de cámaras | 20 | 32 | 24 | 25,3 | 12 | 47 % |
| 1.3 | Ingeniería de red, canalizaciones y energía | 32 | 16 | 24 | 24 | 16 | 67 % |
| 1.4 | Confirmación de versión y compra de licencias | 8 | 12 | 8 | 9,3 | 4 | 43 % |
| 1.5 | Coordinación técnica con la central de monitoreo | 8 | 16 | 12 | 12 | 8 | 67 % |
| 1.6 | Pliego de montaje y contratación de la cuadrilla | 16 | 12 | 24 | 17,3 | 12 | 69 % |
| 1.7 | Presupuesto final, aprobación y órdenes de compra | 16 | 16 | 12 | 14,7 | 4 | 27 % |
| 2.1 | Recepción de equipos y licencias | 16 | 24 | 12 | 17,3 | 12 | 69 % |
| 2.2 | Zanjeo y canalizaciones | 160 | 240 | 176 | 192 | 80 | 42 % |
| 2.3 | Tendido de cableado exterior | 128 | 112 | 144 | 128 | 32 | 25 % |
| 2.4 | Postes y montaje de cámaras y sensores | 128 | 192 | 160 | 160 | 64 | 40 % |
| 2.5 | Instalación de rack y UPS | 8 | 12 | 6 | 8,7 | 6 | 69 % |
| 2.6 | Conexionado y prueba de comunicación | 12 | 24 | 16 | 17,3 | 12 | 69 % |
| 3.1 | Instalación y activación del VMS | 16 | 24 | 16 | 18,7 | 8 | 43 % |
| 3.2 | Configuración de app y perfiles de usuario | 16 | 16 | 12 | 14,7 | 4 | 27 % |
| 3.3 | Calibración de sensores en sitio | 24 | 44 | 32 | 33,3 | 20 | 60 % |
| 3.4 | Integración y pruebas con la central | 16 | 16 | 24 | 18,7 | 8 | 43 % |
| 3.5 | Observación de 7 días corridos sin falsas alarmas | 8 | 14 | 10 | 10,7 | 6 | 56 % |
| 4.1 | Planos conforme a obra | 8 | 12 | 6 | 8,7 | 6 | 69 % |
| 4.2 | Manuales de usuario y guía administrativa | 16 | 24 | 16 | 18,7 | 8 | 43 % |
| 4.3 | Capacitación de usuarios | 16 | 16 | 12 | 14,7 | 4 | 27 % |
| 5.1 | Simulacro de intrusión y prueba de autonomía | 16 | 24 | 16 | 18,7 | 8 | 43 % |
| 5.2 | Acta de recepción, garantía y traspaso de soporte | 8 | 8 | 8 | 8 | 0 | 0 % |
| 6.1 | Planificación del proyecto | 12 | 24 | 16 | 17,3 | 12 | 69 % |
| 6.2 | Seguimiento y control | 32 | 64 | 48 | 48 | 32 | 67 % |
| 6.3 | Cierre del proyecto | 8 | 12 | 8 | 9,3 | 4 | 43 % |
| **Total** | | | | | **882,7** | | |

## 3.4 Discusión entre rondas

A partir de los resultados de la primera ronda, se identificaron diferencias en la interpretación del alcance y del esfuerzo requerido para determinados paquetes de trabajo. Los estimadores revisaron los supuestos considerados, teniendo en cuenta las características del predio, la solución tecnológica propuesta y las condiciones de ejecución del proyecto.

Los principales aspectos considerados para ajustar las estimaciones fueron:

- **1.1 Relevamiento:** las diferencias se relacionaron con el nivel de detalle considerado. Se acordó contemplar no solo el recorrido del predio, sino también la medición de distancias, identificación de puntos de energía y conectividad, registro fotográfico y validación de las zonas críticas con el cliente.
- **1.3 Ingeniería de red:** las diferencias se relacionaron con la posibilidad de rediseñar el trazado una vez terminado el relevamiento. Se acordó que el relevamiento ya fija las zonas críticas y los recorridos, por lo que la ingeniería parte de esa base sin rediseño, e incluye el cálculo de autonomía de la UPS.
- **1.5 y 1.6 Coordinación con la central y contratación de la cuadrilla:** se consideraron diferentes niveles de intervención en la coordinación técnica y administrativa. Se acordó incluir las reuniones de coordinación, validación de protocolos de comunicación, elaboración del pliego de montaje y gestión de la contratación de la cuadrilla externa.
- **1.7 y 2.1 Presupuesto, compras y recepción:** las diferencias estuvieron relacionadas con el alcance de las tareas de seguimiento y gestión de proveedores. Se distinguió el esfuerzo administrativo de realizar las compras y coordinar las entregas del plazo de provisión de los equipos y licencias, que depende de terceros.
- **2.2 y 2.4 Zanjeo y montaje:** las diferencias estuvieron relacionadas con el tipo de suelo, la longitud de las zanjas y la cantidad de postes considerados por cada estimador. Se acordó usar los metros medidos en el relevamiento y la cantidad de postes del plano de cobertura, y sumar un día de margen por lluvia dentro del zanjeo.
- **2.5 y 2.6 Rack, UPS y pruebas de comunicación:** las estimaciones variaban según el nivel de complejidad contemplado. Se acordó considerar el montaje físico del rack y la UPS, el conexionado de los equipos y las pruebas de comunicación de los dispositivos instalados.
- **3.2 y 3.4 Configuración de la aplicación e integración con la central:** se revisó el alcance de la configuración de perfiles de usuario y permisos, así como las pruebas de comunicación con la central. Se consideró que el uso de software comercial conocido por el equipo y la asistencia del proveedor reducen la necesidad de desarrollo y configuración desde cero.
- **3.3 Calibración:** las diferencias se relacionaron con la cantidad de ciclos de prueba y ajuste considerados por las condiciones climáticas y el movimiento de maquinaria. Se acordó planificar dos ciclos completos de ajuste, dado que el equipo ya conoce el software de calibración del proveedor; un ciclo adicional quedaría cubierto por la reserva de la fase iterativa.
- **3.5 Observación:** las diferencias se relacionaron con el esfuerzo de supervisión considerado durante el período de observación. Se acordó mantener los siete días corridos como condición de aceptación y estimar por separado las horas de seguimiento y control necesarias durante ese período.
- **4.1, 4.2 y 4.3 Documentación y capacitación:** se revisó el nivel de detalle esperado para los planos conforme a obra, los manuales de usuario y la guía administrativa. También se consideró la preparación y realización de las capacitaciones destinadas al personal de la empresa, incluyendo al sereno y a los responsables de administración y seguridad.
- **5.1 Simulacro y prueba de autonomía:** se contemplaron tanto las pruebas de detección y notificación de intrusiones como la verificación de la autonomía de la UPS mediante un corte controlado de alimentación eléctrica. Se acordó considerar la participación de los responsables técnicos necesarios para realizar y documentar las pruebas.
- **6.1 y 6.3 Planificación y cierre:** las diferencias respondieron al alcance de las actividades de gestión consideradas. Se acordó incluir en la planificación la organización inicial, coordinación de recursos y definición del cronograma, y en el cierre la documentación final, el cierre administrativo de contratos y la entrega de las lecciones aprendidas.
- **6.2 Seguimiento y control:** se acordó considerar aproximadamente una hora diaria de dedicación del líder del proyecto durante la ejecución, incluyendo la coordinación con proveedores, contratistas y demás participantes.

A partir de estas revisiones se realizó la segunda ronda, en la que se alcanzó una mayor convergencia. Todos los paquetes quedaron por debajo del umbral del 25 % establecido como criterio de convergencia. Se adoptó el promedio de la segunda ronda como estimación final de esfuerzo.

## 3.5 Ronda 2 y estimación final

| ID | Paquete | Est. 1 (h) | Est. 2 (h) | Est. 3 (h) | Promedio R2 | Delta R2 | Delta / prom. | Final (h) |
| --- | --- | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| 1.1 | Relevamiento del predio y zonas críticas | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 1.2 | Diseño de detección y cobertura de cámaras | 24 | 24 | 24 | 24 | 0 | 0 % | 24 |
| 1.3 | Ingeniería de red, canalizaciones y energía | 24 | 26 | 22 | 24 | 4 | 17 % | 24 |
| 1.4 | Confirmación de versión y compra de licencias | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| 1.5 | Coordinación técnica con la central de monitoreo | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| 1.6 | Pliego de montaje y contratación de la cuadrilla | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 1.7 | Presupuesto final, aprobación y órdenes de compra | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 2.1 | Recepción de equipos y licencias | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 2.2 | Zanjeo y canalizaciones | 192 | 200 | 184 | 192 | 16 | 8 % | 192 |
| 2.3 | Tendido de cableado exterior | 128 | 128 | 128 | 128 | 0 | 0 % | 128 |
| 2.4 | Postes y montaje de cámaras y sensores | 160 | 168 | 152 | 160 | 16 | 10 % | 160 |
| 2.5 | Instalación de rack y UPS | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| 2.6 | Conexionado y prueba de comunicación | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 3.1 | Instalación y activación del VMS | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 3.2 | Configuración de app y perfiles de usuario | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 3.3 | Calibración de sensores en sitio | 32 | 34 | 30 | 32 | 4 | 13 % | 32 |
| 3.4 | Integración y pruebas con la central | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 3.5 | Observación de 7 días corridos sin falsas alarmas | 10 | 10 | 10 | 10 | 0 | 0 % | 10 |
| 4.1 | Planos conforme a obra | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| 4.2 | Manuales de usuario y guía administrativa | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 4.3 | Capacitación de usuarios | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 5.1 | Simulacro de intrusión y prueba de autonomía | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 5.2 | Acta de recepción, garantía y traspaso de soporte | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| 6.1 | Planificación del proyecto | 16 | 16 | 16 | 16 | 0 | 0 % | 16 |
| 6.2 | Seguimiento y control | 48 | 48 | 48 | 48 | 0 | 0 % | 48 |
| 6.3 | Cierre del proyecto | 8 | 8 | 8 | 8 | 0 | 0 % | 8 |
| **Total** | | | | | | | | **858** |


### Totales por entregable

| Entregable | Esfuerzo (h) | % del total |
| --- | :---: | :---: |
| E1 Ingeniería | 112 | 13,1 % |
| E2 Infraestructura | 520 | 60,6 % |
| E3 Sistema lógico | 90 | 10,5 % |
| E4 Documentación | 40 | 4,7 % |
| E5 Recepción | 24 | 2,8 % |
| Gestión (6.1 a 6.3) | 72 | 8,4 % |
| **Total** | **858** | **100 %** |

> E2 concentra el 60,6 % porque incluye las 480 h-operario de la cuadrilla externa en 2.2 (192 h), 2.3 (128 h) y 2.4 (160 h). Sin la cuadrilla, el esfuerzo del equipo integrador es de 378 h.

## 3.6 Control con PERT


Usamos la estimación de tres puntos en los dos paquetes más inciertos y en el plazo de los proveedores, que no depende del esfuerzo del equipo:

| Paquete | Unidad | Optimista (O) | Más probable (M) | Pesimista (P) | (O + 4M + P) / 6 | Uso |
| --- | --- | :---: | :---: | :---: | :---: | --- |
| 2.1 Recepción de equipos y licencias | días hábiles | 10 | 15 | 26 | 16,0 | Duración adoptada: 16 días |
| 2.2 Zanjeo y canalizaciones | horas | 160 | 192 | 256 | 197,3 | Control: Delphi dio 192 h |
| 3.3 Calibración de sensores en sitio | horas | 24 | 32 | 44 | 32,7 | Control: Delphi dio 32 h |

En los dos paquetes de control, PERT da valores muy cercanos a los de Delphi (diferencias menores al 3 %), así que mantuvimos los de Delphi pero lo contrastamos con el PERT.

Ejemplo de cálculo, 2.1: (10 + 4×15 + 26) / 6 = 96 / 6 = 16 días.

## 3.7 Conversión a duración

**Fórmula:** Duración = Esfuerzo / (Recursos × Dedicación × 8 horas por día). Los recursos son los de la estructura del equipo definida en la Tarea 2, más la cuadrilla externa.

Tres paquetes no salen de la fórmula y se explican aparte:

- **2.1 Recepción de equipos y licencias:** el plazo lo fijan los proveedores; el esfuerzo de 16 h es solo el seguimiento.
- **3.5 Período de observación:** son 7 días corridos fijados por el criterio de aceptación de la Tarea 2.
- **6.2 Seguimiento y control:** dura toda la ejecución; con 48 h repartidas en 45 días, la dedicación del líder es de alrededor del 13 %.

| ID | Paquete | Esfuerzo (h) | Recursos | Cant. | Dedicación | Duración calculada (d) | Duración adoptada (d) |
| --- | --- | :---: | --- | :---: | :---: | --- | :---: |
| 1.1 | Relevamiento del predio y zonas críticas | 16 | Gabriel S. y Gabriel N. | 2 | 100 % | 1 | 1 |
| 1.2 | Diseño de detección y cobertura de cámaras | 24 | Gabriel N. | 1 | 100 % | 3 | 3 |
| 1.3 | Ingeniería de red, canalizaciones y energía | 24 | Gabriel S. | 1 | 100 % | 3 | 3 |
| 1.4 | Confirmación de versión y compra de licencias | 8 | Lucía | 1 | 100 % | 1 | 1 |
| 1.5 | Coordinación técnica con la central de monitoreo | 8 | Gabriel N. | 1 | 100 % | 1 | 1 |
| 1.6 | Pliego de montaje y contratación de la cuadrilla | 16 | Gabriel S. | 1 | 100 % | 2 | 2 |
| 1.7 | Presupuesto final, aprobación y órdenes de compra | 16 | Renzo | 1 | 100 % | 2 | 2 |
| 2.1 | Recepción de equipos y licencias | 16 | Renzo (seguimiento) | 1 | — | Plazo del proveedor (PERT) | 16 |
| 2.2 | Zanjeo y canalizaciones | 192 | Cuadrilla externa (4) | 4 | 100 % | 6 | 6 |
| 2.3 | Tendido de cableado exterior | 128 | Cuadrilla externa (4) | 4 | 100 % | 4 | 4 |
| 2.4 | Postes y montaje de cámaras y sensores | 160 | Cuadrilla externa (4) | 4 | 100 % | 5 | 5 |
| 2.5 | Instalación de rack y UPS | 8 | Gabriel S. | 1 | 100 % | 1 | 1 |
| 2.6 | Conexionado y prueba de comunicación | 16 | Gabriel S. | 1 | 100 % | 2 | 2 |
| 3.1 | Instalación y activación del VMS | 16 | Lucía (con soporte del proveedor) | 1 | 100 % | 2 | 2 |
| 3.2 | Configuración de app y perfiles de usuario | 16 | Lucía | 1 | 100 % | 2 | 2 |
| 3.3 | Calibración de sensores en sitio | 32 | Gabriel N. | 1 | 100 % | 4 | 4 |
| 3.4 | Integración y pruebas con la central | 16 | Gabriel N. | 1 | 100 % | 2 | 2 |
| 3.5 | Observación de 7 días corridos sin falsas alarmas | 10 | Gabriel N. (control diario) | 1 | 25 % | 7 días corridos = 5 hábiles | 5 |
| 4.1 | Planos conforme a obra | 8 | Gabriel S. | 1 | 100 % | 1 | 1 |
| 4.2 | Manuales de usuario y guía administrativa | 16 | Lucía | 1 | 100 % | 2 | 2 |
| 4.3 | Capacitación de usuarios | 16 | Lucía | 1 | 100 % | 2 | 2 |
| 5.1 | Simulacro de intrusión y prueba de autonomía | 16 | Gabriel N. y Gabriel S. | 2 | 100 % | 1 | 1 |
| 5.2 | Acta de recepción, garantía y traspaso de soporte | 8 | Renzo | 1 | 100 % | 1 | 1 |
| 6.1 | Planificación del proyecto | 16 | Renzo | 1 | 100 % | 2 | 2 |
| 6.2 | Seguimiento y control | 48 | Renzo | 1 | 13 % | Toda la ejecución (de 6.1 a 5.2) | 45 |
| 6.3 | Cierre del proyecto | 8 | Renzo | 1 | 100 % | 1 | 1 |

**Verificación:** 858 h totales. E2 (520 h) es el 60,6 % por la cuadrilla. El resto del equipo (378 h) se reparte en ingeniería (112 h), sistema lógico (90 h), gestión (72 h), documentación (40 h) y recepción (24 h). La duración de 48 días hábiles no sale de dividir 858 / 32, porque gran parte del trabajo es secuencial, hay 16 días de espera de proveedores y 5 días hábiles de observación, y no todos trabajan en todos los paquetes a la vez.

> **Estimación de costos:** no se incluye en esta entrega (punto opcional de la consigna).

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
