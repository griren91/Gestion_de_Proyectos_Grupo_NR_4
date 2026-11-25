# Tarea 3 — EDT y estimaciones
## Sistema integrado de detección de intrusiones y videovigilancia perimetral · Equipo 4 · Gestión de Proyectos · FIUNER

> **Fuente:** Documento `Tarea3_EDT_y_estimaciones_G4_vf.docx` (versión final del grupo).
> **En resumen.** La EDT parte de los cinco entregables de la Tarea 2 y suma la gestión del proyecto: 26 paquetes de trabajo. El esfuerzo total estimado es de **858 horas**. Con el equipo a tiempo completo y una cuadrilla externa de cuatro operarios, el proyecto dura **48 días hábiles: empieza el 1 de marzo y termina el 10 de mayo de 2027**. El camino crítico pasa por la ingeniería de red, la entrega de los equipos por parte de los proveedores, el montaje y la calibración en el sitio.
> **Costos:** no se incluyen en esta entrega (punto opcional de la consigna, no realizado).

## 1. Quiénes somos y qué incluye el proyecto

Somos una empresa integradora. No somos parte de la concesionaria: la concesionaria nos contrata para diseñar, comprar, dirigir la instalación y poner en marcha el sistema. Integramos equipos y servicios de terceros (cámaras, sensores, UPS, cuadrilla de obra, central de monitoreo y software) en una solución que funcione en este predio.

El software es enlatado. La plataforma de gestión de video (VMS) y la app no las desarrollamos: compramos licencias a un proveedor y las configuramos para el cliente. Eso suma un actor externo más al proyecto, con su plazo de entrega, sus condiciones de licencia y su soporte técnico.

Trabajamos con un proveedor habitual. El equipo ya conoce su app y su software de calibración, por eso no hay que elegir proveedor y la configuración y la calibración llevan menos tiempo.

### Consecuencias del software enlatado en la planificación

- **Licencias (1.4):** no se elige proveedor; se confirma que la versión vigente sea compatible con las cámaras y el grabador, y se calcula y cotiza la cantidad de licencias.
- **Plazo de entrega (2.1):** las licencias entran en el mismo seguimiento que el hardware.
- **Activación (3.1):** la instalación se hace con asistencia remota del proveedor; si su soporte demora, se atrasa la Fase 3.
- **Manuales (4.2) y cierre (5.2):** el cliente recibe los datos de contacto del soporte y el contrato de licencias y soporte queda a su nombre. Después de la entrega, las consultas sobre el software las atiende el proveedor.
- **Seguimiento (6.2):** el proveedor del software se suma a la coordinación con los demás proveedores, la cuadrilla y la central.
- **Riesgo de proveedor único:** al no cotizar alternativas, el proyecto depende de un solo proveedor de software. Si cambia precios, discontinúa el producto o demora el soporte, no hay un reemplazo evaluado. Se registra en el registro de riesgos y se justifica ante el cliente en la ingeniería de detalle (E1): experiencia previa, menor riesgo técnico y menor plazo.

### Supuestos de planificación

- **Inicio del proyecto:** lunes 1 de marzo de 2027. Jornada de 8 horas, de lunes a viernes; se excluyen los feriados nacionales del período (24/3, 26/3, 2/4 y 25/5).
- El equipo de la empresa integradora trabaja a tiempo completo en el proyecto (dedicación del 100 %). Las excepciones son el seguimiento y control y el período de observación, con dedicación parcial.
- La obra pesada (zanjeo, cableado y postes) la ejecuta una cuadrilla externa de cuatro operarios a tiempo completo. Gabriel S. la supervisa en forma parcial, dentro de esos mismos paquetes.
- El plazo de entrega de equipos y licencias lo fijan los proveedores; se estimó con PERT (sección 3.6 de estimaciones).
- El software enlatado es del proveedor habitual de la empresa: el equipo ya conoce la app y el software de calibración.
- Las duraciones se redondean hacia arriba a días enteros.
- Los costos (punto opcional de la consigna) no se incluyen en esta entrega.

## 2. Estructura de desglose del trabajo (EDT)

La EDT se armó en tres pasos. Primero listamos todo el trabajo necesario para construir el sistema y gestionar el proyecto. Después lo agrupamos por los cinco entregables de la Tarea 2, que forman el primer nivel, más un sexto grupo de gestión del proyecto. Por último descompusimos cada entregable en paquetes de trabajo que tienen un responsable y un resultado verificable. El orden de los paquetes sigue las cuatro fases del ciclo de vida híbrido: los entregables E1, E2, E4 y E5 son predictivos y el E3, de calibración, es iterativo.

**Figura 1: EDT del proyecto. En rojo, los paquetes del camino crítico.**

Camino crítico (holgura 0): 6.1 → 1.1 → 1.3 → 1.6 → 1.7 → 2.1 → 2.4 → 2.6 → 3.3 → 3.4 → 3.5 → 4.3 → 5.2 → 6.3.

Estructura por entregable:

- **E1 Ingeniería (1.1 a 1.7):** Relevamiento, Diseño de detección, Ingeniería de red, Licencias, Central, Pliego y cuadrilla, Presupuesto y aprobación.
- **E2 Infraestructura (2.1 a 2.6):** Recepción, Zanjeo, Cableado, Postes y montaje, Rack y UPS, Conexionado.
- **E3 Sistema lógico (3.1 a 3.5):** VMS, App y perfiles, Calibración, Integración con central, Observación 7 días.
- **E4 Documentación (4.1 a 4.3):** Planos conforme a obra, Manuales, Capacitación.
- **E5 Recepción (5.1 a 5.2):** Simulacro y autonomía, Acta de recepción.
- **Gestión (6.1 a 6.3):** Planificación, Seguimiento y control, Cierre.

### Diccionario de la EDT

| ID | Paquete de trabajo | Entregable | Responsable | Descripción | Criterio de completitud |
| --- | --- | --- | --- | --- | --- |
| 1.1 | Relevamiento del predio y zonas críticas | E1 Ingeniería | Gabriel S. | Recorrido del patio, accesos y galpones; medición de distancias, puntos de energía y red; registro fotográfico y acuerdo de zonas críticas con el cliente. | Plano de relevamiento con zonas críticas validadas por el cliente. |
| 1.2 | Diseño de detección y cobertura de cámaras | E1 Ingeniería | Gabriel N. | Ubicación y tipo de sensores perimetrales y cámaras, ángulos de visión, análisis de puntos ciegos por movimiento de maquinaria. | Plano de cobertura con 100 % de zonas críticas cubiertas y listado de equipos. |
| 1.3 | Ingeniería de red, canalizaciones y energía | E1 Ingeniería | Gabriel S. | Trazado de canalizaciones, cálculo de enlaces y cableado exterior, dimensionamiento del rack y cálculo de autonomía de la UPS (≥ 8 h). | Planos de canalización y diagrama de red; memoria de cálculo de UPS revisada. |
| 1.4 | Confirmación de versión y compra de licencias | E1 Ingeniería | Lucía | Con el proveedor habitual de software: verificación de que la versión vigente del VMS y la app es compatible con las cámaras y el grabador elegidos, cálculo de licencias (retención de 30 días) y cotización con las condiciones de soporte. | Versión confirmada, cotización de licencias y condiciones de soporte vigentes. |
| 1.5 | Coordinación técnica con la central de monitoreo | E1 Ingeniería | Gabriel N. | Definición con la central del protocolo de comunicación, eventos a transmitir, identificación de sectores y prueba de enlace prevista. | Protocolo y lista de eventos acordados por escrito con la central. |
| 1.6 | Pliego de montaje y contratación de la cuadrilla | E1 Ingeniería | Gabriel S. | Pliego técnico de zanjeo, tendido y postes; pedido de cotización, comparación y contratación de la cuadrilla externa. | Cuadrilla contratada con pliego y fechas firmados. |
| 1.7 | Presupuesto final, aprobación y órdenes de compra | E1 Ingeniería | Renzo | Consolidación del documento de ingeniería, presupuesto final con contingencia, presentación al cliente y emisión de órdenes de compra de equipos y licencias. | Ingeniería aprobada por escrito y órdenes de compra emitidas (Hito 1). |
| 2.1 | Recepción de equipos y licencias | E2 Infraestructura | Renzo | Seguimiento de proveedores de hardware y del software enlatado hasta la entrega; control de cantidades y estado. La duración depende del plazo de entrega del proveedor. | Equipos y licencias recibidos y controlados contra las órdenes de compra. |
| 2.2 | Zanjeo y canalizaciones | E2 Infraestructura | Gabriel S. | Apertura de zanjas perimetrales, colocación de caños y cámaras de paso según pliego, bajo supervisión de Gabriel S. | Canalizaciones completas e inspeccionadas según planos. |
| 2.3 | Tendido de cableado exterior | E2 Infraestructura | Gabriel S. | Tendido de cable de red exterior con protección UV y de alimentación hasta cada punto. | Cableado tendido y rotulado; continuidad verificada en el 100 % de los tramos. |
| 2.4 | Postes y montaje de cámaras y sensores | E2 Infraestructura | Gabriel S. | Fijación de postes y soportes, montaje mecánico de cámaras IP y sensores perimetrales, conexión a la red. | Equipos montados y energizados en todas las posiciones del plano. |
| 2.5 | Instalación de rack y UPS | E2 Infraestructura | Gabriel S. | Armado del rack en el galpón, switches, grabador (NVR) y UPS; tablero eléctrico de alimentación. | Rack y UPS instalados y energizados. |
| 2.6 | Conexionado y prueba de comunicación | E2 Infraestructura | Gabriel S. | Conexionado final y prueba de comunicación de cada dispositivo con el rack. | Acta de montaje firmada y 100 % de equipos con comunicación de red comprobada (Hito 2). |
| 3.1 | Instalación y activación del VMS | E3 Sistema lógico | Lucía | Instalación del software enlatado de gestión de video, activación de licencias, alta de cámaras y grabación con retención de 30 días, con asistencia remota del proveedor. | Todas las cámaras grabando en el VMS con licencias activas. |
| 3.2 | Configuración de app y perfiles de usuario | E3 Sistema lógico | Lucía | Configuración de la app del proveedor, avisos con indicación de sector y perfiles y permisos de usuario según la Ley 25.326. | Matriz de usuarios cargada y avisos de prueba recibidos en la app. |
| 3.3 | Calibración de sensores en sitio | E3 Sistema lógico | Gabriel N. | Ciclos de prueba y ajuste de sensibilidad, filtros y zonas de detección con el software de calibración del proveedor, que el equipo ya conoce; tratamiento de sombras de maquinaria y condiciones climáticas. | Ensayos de cruce detectados en todas las zonas sin disparos por clima o maquinaria. |
| 3.4 | Integración y pruebas con la central | E3 Sistema lógico | Gabriel N. | Pruebas de disparo de punta a punta: sensor, alarma sonora, central de monitoreo y app, midiendo el tiempo de aviso (≤ 30 s). | Acuse de la central en todas las zonas y tiempos de aviso dentro de la meta. |
| 3.5 | Observación de 7 días corridos sin falsas alarmas | E3 Sistema lógico | Gabriel N. | Funcionamiento continuo durante 7 días corridos con registro diario de eventos. Si aparece una falsa alarma se ajusta y el período se reinicia. | Informe de 7 días seguidos sin falsas alarmas (Hito 3). |
| 4.1 | Planos conforme a obra | E4 Documentación | Gabriel S. | Actualización de planos de canalización, red y ubicación de equipos según lo efectivamente instalado. | Planos conforme a obra entregados al cliente. |
| 4.2 | Manuales de usuario y guía administrativa | E4 Documentación | Lucía | Adaptación de los manuales del proveedor: manual del sereno, guía para administración y gerencia, y datos de contacto del soporte del proveedor del software. | Manuales revisados y entregados. |
| 4.3 | Capacitación de usuarios | E4 Documentación | Lucía | Jornadas de capacitación al sereno, administración y gerencia sobre la app, el VMS y la respuesta a eventos. | Actas de capacitación firmadas por los asistentes. |
| 5.1 | Simulacro de intrusión y prueba de autonomía | E5 Recepción | Gabriel N. | Simulacro diurno y nocturno con el cliente y la central; corte de energía para verificar la autonomía real de la UPS. | Simulacro exitoso y autonomía ≥ 8 h verificada. |
| 5.2 | Acta de recepción, garantía y traspaso de soporte | E5 Recepción | Renzo | Firma del acta de recepción, entrega de la póliza de garantía y traspaso al cliente del contrato de soporte y licencias del software enlatado. | Acta de recepción definitiva firmada por la gerencia (Hito 4). |
| 6.1 | Planificación del proyecto | Gestión | Renzo | Acta de constitución, plan del proyecto, línea base de alcance, costo y cronograma, registro de riesgos y calendario de reuniones. | Plan y línea base aprobados por la gerencia del cliente. |
| 6.2 | Seguimiento y control | Gestión | Renzo | Reunión semanal, control de avance y costos, gestión de cambios (Nivel 3), riesgos y coordinación con proveedores, cuadrilla, central y proveedor del software. | Informes semanales emitidos y cambios registrados hasta la recepción. |
| 6.3 | Cierre del proyecto | Gestión | Renzo | Cierre administrativo de contratos con proveedores y cuadrilla, archivo del proyecto y lecciones aprendidas. | Contratos cerrados e informe de lecciones aprendidas emitido. |

> Fuente: Tarea 3 — EDT y estimaciones, Equipo 4, versión final del grupo (858 h, 48 días hábiles, 01/03/2027 a 10/05/2027).

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
