# 📖 Proyecto y Propuesta de Valor

> El proyecto parte del diseño y desarrollo (D&D) de un **producto** trabajado en las asignaturas anteriores o en la práctica profesional. Aquí se resume lo ya conocido para poder planificarlo; no se rediseña el producto. Si el proyecto proviene de un contexto profesional, cuidar la confidencialidad de la información que se publica.

## Nombre del proyecto

> **Sistema de seguridad integral para galpones industriales**

## Origen del proyecto

- [ ] Proyecto de una asignatura anterior de la especialización
- [x] Proyecto profesional en curso o previsto
- [ ] Trabajo Final Integrador de la especialización (en preparación)

## Descripción del producto

> El proyecto es el diseño y la puesta en marcha de un sistema de seguridad para los galpones de una empresa (en adelante, la empresa), que combina alarma con sensores y videovigilancia de las zonas perimetrales y del patio exterior. El producto es un sistema integrado de detección, registro y aviso de intrusiones, compuesto por sensores de alarma, cámaras IP, una red dedicada, grabación de video y alimentación de respaldo.
>
> Está destinado a la empresa: su dirección, el personal de los galpones y los contactos responsables ante una alarma. Complementa a la vigilancia física existente (el sereno) y no la reemplaza. Se desarrolla dentro de las instalaciones de la empresa, que siguen operando durante la obra.

## Problema u oportunidad

> La vigilancia actual depende de presencia física que no cubre las 24 horas. El personal administrativo se retira a las 17 h, el sereno trabaja de 21 a 5 h y el personal administrativo vuelve a las 9 h. Quedan dos franjas diarias sin ninguna vigilancia: 17:00 a 21:00 (4 h) y 05:00 a 09:00 (4 h), un total de 8 h por día sin vigilancia.
>
> La situación se agrava por tres condiciones del predio:
>
> - Es una zona amplia y alejada de la zona urbana, sin vecinos ni tránsito que observen o den aviso, y con ayuda que tardaría más en llegar.
> - La mayor parte de los activos son tractores y maquinaria pesada, almacenados para la venta en el patio exterior, la zona que hoy no tiene protección.
> - Las cámaras existentes son interiores, por lo que el perímetro y el patio exterior no tienen detección ni registro. Incluso durante el turno del sereno, una sola persona no puede vigilar un predio de esta extensión.
>
> La empresa no ha sufrido robos hasta ahora. La oportunidad es actuar antes del primer incidente: pasar de una vigilancia limitada y reactiva a un sistema que detecte, avise y deje evidencia, con un diseño a medida de cada sector.

## Contexto

| Campo | Detalle |
|-------|---------|
| Organización | La empresa (nombre reservado por confidencialidad): fabricante y comercializadora de tractores y maquinaria pesada, con galpones y patio exterior de almacenamiento |
| Sector | Industria de maquinaria (tractores y maquinaria pesada) |
| Usuarios / clientes | Dirección de la empresa, personal de los galpones, sereno y responsables de seguridad y mantenimiento |
| Estado actual del proyecto | En planificación. Sin detección ni registro en el perímetro. Las cámaras interiores existentes siguen funcionando y quedan fuera del alcance del proyecto (la empresa las administra por su cuenta). Presupuesto aún no definido |

Etapas previstas en el documento de origen: Relevamiento (recorrido del predio, planos, zonas críticas, puntos de acceso, tomas de energía y estado de la conectividad); Diseño y cálculo de materiales (cantidad y tipo de cámaras y lentes según distancia a cubrir, metros de cable UTP, sensores, dimensionamiento de UPS y baterías, y requisitos de ancho de banda de internet); Definición de zonas a monitorear (mapa de cobertura por sector, con las zonas perimetrales priorizadas); Preparación por sectores (canalizaciones, tendido de cableado y puntos de energía, sector por sector para no frenar la operación); Despliegue y puesta en marcha (instalación de equipos, configuración, pruebas de detección y aviso, y entrega con documentación).

## Requerimientos principales

> Funcionalidades o requerimientos ya conocidos, tomados de las asignaturas anteriores o del relevamiento previo.

| ID | Requerimiento | Prioridad | Origen |
|----|--------------|:---------:|--------|
| REQ-01 | Detectar intrusiones en el perímetro mediante sensores (barreras infrarrojas, magnéticos en accesos, detectores de movimiento exterior) | Alta | Relevamiento y documento de proyecto |
| REQ-02 | Cubrir con cámaras las zonas perimetrales y el patio exterior, con capacidad de detección y registro a larga distancia | Alta | Relevamiento y documento de proyecto |
| REQ-03 | Avisar de forma local (sirena) y remota (notificación a responsables) en 30 segundos o menos desde la detección | Alta | Relevamiento y documento de proyecto |
| REQ-04 | Seguir funcionando ante cortes de energía, con autonomía de al menos 8 horas | Alta | Relevamiento y documento de proyecto |
| REQ-05 | Grabar el video y conservarlo durante un período mínimo de 30 días | Media | Relevamiento y documento de proyecto |
| REQ-06 | Permitir el monitoreo remoto seguro a través de una conexión a internet estable | Media | Relevamiento y documento de proyecto |
| REQ-07 | Notificar al sereno durante su turno e indicarle la zona del evento | Media | Relevamiento y documento de proyecto |

## Propuesta de valor

> Para una empresa que almacena tractores y maquinaria pesada en un predio industrial alejado de la zona urbana, con períodos diarios sin vigilancia física y sectores exteriores sin protección, se propone implementar un sistema integrado de seguridad perimetral y videovigilancia.
>
> La solución permitirá mejorar la capacidad de prevención, detección y respuesta ante posibles intrusiones, proporcionando información en tiempo real y registros audiovisuales de los eventos.
>
> De esta manera, la empresa podrá reducir su exposición al riesgo patrimonial, mejorar el control de sus instalaciones y complementar la vigilancia física existente, sin necesidad de reemplazar al personal de seguridad ni incrementar la dotación de guardias.
>
> La solución estará diseñada específicamente para las características del predio y podrá ampliarse a otros sectores o instalaciones en el futuro.

| Elemento | Respuesta |
|----------|-----------|
| ¿Quién es el usuario o cliente? | La empresa propietaria de los galpones: su dirección, el personal, el sereno y los responsables que atienden una alarma. |
| ¿Qué problema o necesidad tiene? | Hay 8 h diarias sin vigilancia (17 a 21 h y 5 a 9 h) en un predio amplio y alejado de la zona urbana. Los activos de mayor valor están en el patio exterior, donde no hay detección ni registro. Que hasta ahora no haya habido robos no indica que el riesgo sea bajo: las ventanas sin vigilancia son fijas y previsibles, y el lugar está aislado. |
| ¿Cómo lo resuelve el producto? | Con sensores perimetrales y cámaras IP en el exterior que detectan la intrusión, activan una sirena local, notifican a los responsables en 30 segundos y graban el evento. Fuera del horario del sereno (17 a 21 h y 5 a 9 h) cubre el vacío de vigilancia. Durante su turno (21 a 5 h) amplía su alcance indicándole dónde está el evento. Funciona con alimentación de respaldo y permite el monitoreo remoto. Las cámaras interiores existentes no se modifican. |
| ¿Qué lo diferencia de las alternativas actuales? | Su principal diferencial es la detección y el registro a larga distancia a través de las cámaras, que permite vigilar un predio amplio desde puntos fijos, algo que una persona recorriendo el lugar no puede hacer. Frente a la vigilancia física, no la reemplaza sino que la potencia. Frente a sumar más guardias, cubre las 8 horas sin agregar personal. Frente a un kit comercial, está diseñado a medida del predio y de las zonas críticas. Frente a no hacer nada, deja de depender de que alguien esté presente para enterarse. |
| ¿Qué beneficio se espera y cómo se podrá reconocer? (medible si es posible) | Evitar pérdidas potenciales y responder más rápido ante cualquier intento de intrusión. Se reconocerá con indicadores de cumplimiento técnico: tiempo entre detección y notificación ≤ 30 segundos; autonomía eléctrica ≥ 8 horas; retención de video ≥ 30 días; cobertura del 100% de las zonas definidas en el relevamiento; 100% de las pruebas de aceptación satisfactorias. Y con indicadores de impacto: porcentaje de activos críticos dentro de zonas monitoreadas; tiempo entre la notificación y la intervención del responsable; porcentaje de eventos detectados con registro audiovisual; disponibilidad del sistema de detección y notificación durante las 24 horas; cantidad de incidentes y pérdidas patrimoniales registradas. |
| ¿Quiénes se ven impactados positivamente? | Dirección (más control y menor exposición al riesgo), personal de los galpones (lugar de trabajo más seguro), sereno (mayor alcance y respaldo) y responsables de seguridad y mantenimiento (alarmas y registros accesibles en forma remota). |
| ¿Por qué conviene que se haga, desde la perspectiva de quien lo patrocina? | La conveniencia no está en recuperar pérdidas pasadas, sino en no esperar al primer incidente para actuar: el riesgo existe aunque no se haya concretado. El predio tiene 8 horas diarias sin vigilancia, está alejado de la zona urbana y concentra su activo más valioso a la intemperie. Los horarios sin cobertura son fijos y fáciles de observar desde afuera. Un solo incidente puede costar más que el sistema. Las unidades del patio son maquinaria con un valor de entre USD 20.000 y USD 100.000 cada una. El robo o daño de un solo tractor implica perder el ingreso de esa venta y tener que reponer la unidad, además del posible retraso en entregas ya comprometidas. Un tractor se puede sacar del predio conduciéndolo o cargándolo en un camión, y al estar a la intemperie y fuera de los galpones queda expuesto durante las 8 horas sin vigilancia. La inversión se justifica si su costo es menor al valor de una o pocas unidades. Prevenir cuesta menos que reaccionar. Con detección y registro, el intento de intrusión puede cortarse a tiempo, y si igualmente ocurre, queda evidencia para la denuncia policial. Complementa al guardia y cubre sus ausencias. Un sereno no alcanza a vigilar un predio amplio al mismo tiempo y fuera de su horario no hay nadie. El sistema cubre ambas debilidades sin eliminar el puesto. Es una inversión que se puede ampliar. Deja una infraestructura documentada que puede extenderse a otros sectores o sedes. |

## Restricciones y supuestos conocidos

| Tipo | Descripción |
|------|-------------|
| Tiempo | El plan debe completarse dentro del cursado (fecha concreta a definir con la cátedra) |
| Presupuesto | El presupuesto del cliente aún no está definido |
| Alcance | Seguridad perimetral y del patio exterior. Quedan fuera las cámaras interiores existentes y el control de accesos. El sistema complementa al sereno y no lo reemplaza |
| Recursos | Los galpones siguen operando, por lo que la obra se organiza por sectores |

**Supuestos:**

- La empresa facilita planos, acceso al predio y un interlocutor para el relevamiento.
- Existe infraestructura eléctrica en los puntos de instalación o puede extenderse.
- La conexión a internet actual alcanza o puede ampliarse.
- Un responsable de la empresa recibe las notificaciones en las franjas sin sereno (17 a 21 h y 5 a 9 h).

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
