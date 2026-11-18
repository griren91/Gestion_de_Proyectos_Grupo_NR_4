# 📦 Entregables Relevantes

> Los entregables son el punto de partida de la EDT (Tarea 3). Listar los productos de trabajo verificables más importantes del proyecto, no las actividades.
>
> Los cinco entregables tangibles se formalizaron para delimitar contractualmente el trabajo y preparar el terreno hacia la Tarea 3 (EDT / WBS). Son la entrega llave en mano al cliente, con validación incremental por hitos.

| ID | Entregable | Descripción | Criterio de aceptación | Fase en que se completa |
|----|-----------|-------------|------------------------|:-----------------------:|
| E1 | Documento de Ingeniería de Detalle y Plan de Montaje | Planos de tendido, diagramas de conexión, cálculo eléctrico de UPS y pliego para la cuadrilla. | Aprobación formal por escrito del Cliente y emisión de órdenes de compra confirmadas. | 1 |
| E2 | Infraestructura Física y Hardware Perimetral | Postes fijados, canalizaciones, cableado UV, cámaras IP y sensores montados y energizados. | Acta de conformidad física + 100% de dispositivos con comunicación de red comprobada. | 2 |
| E3 | Sistema Lógico, Calibración y App Móvil | NVR (grabador de video en red) y VMS (software de gestión de video) configurados, matriz de usuarios activa (Ley 25.326), sensores calibrados y enlace externo. | Informe de 7 días continuos en intemperie sin falsas alarmas + acuse de recibo de la central externa. | 3 |
| E4 | Paquete Documental y Capacitación Operativa | Planos conforme a obra, manual de usuario para el sereno y guía administrativa para gerencia. | Jornadas de capacitación concluidas con actas firmadas por los usuarios y manuales entregados. | 4 |
| E5 | Acta de Recepción Definitiva y Garantía | Documento formal de cierre contractual, transferencia de administración y póliza de garantía de 12 meses. | Firma del Acta de Recepción por la Gerencia de la Concesionaria tras simulacro exitoso. | 4 |

## Exclusiones

> Qué queda explícitamente fuera del alcance del proyecto. Para proteger a la empresa integradora de sobrecostos y reclamos fuera de alcance, el contrato establece cinco exclusiones:

- **Obra civil mayor y albañilería:** No incluye pavimentación de calles internas, reformas edilicias en galpones ni reparación de cercos perimetrales o alambrados preexistentes dañados.
- **Servicio y abono comercial de monitoreo:** La empresa integradora homologa el protocolo técnico de comunicación; la contratación y el pago del abono mensual de vigilancia es un contrato directo entre la concesionaria y la empresa de seguridad.
- **Seguridad física presencial:** El sistema tecnológico complementa y asiste, pero bajo ninguna circunstancia reemplaza al sereno ni contempla provisión de personal de guardia armada o custodia presencial.
- **Provisión de dispositivos móviles de usuario:** Se suministra y configura la aplicación cliente, pero no se proveen teléfonos celulares, tablets ni abonos de datos móviles para el personal de la concesionaria.
- **Ampliación de cobertura a depósitos no contemplados:** El alcance se restringe estrictamente al patio exterior y accesos críticos de galpones principales; cualquier extensión a nuevas zonas demandará una adenda contractual formal.

## Relación entre entregables y fases

| Fase | Entregables que la cierran |
|------|----------------------------|
| 1 · Inicio e Ingeniería [Predictiva] | E1 |
| 2 · Montaje Físico [Predictiva] | E2 |
| 3 · Integración y Calibración [Iterativa] | E3 |
| 4 · Cierre y Capacitación [Predictiva] | E4 + E5 |

> Verificar que el criterio de salida de cada fase (`ciclo-de-vida.md`) se pueda comprobar con estos entregables. La compuerta de Fase 1 se comprueba con E1, la de Fase 2 con E2, la de Fase 3 con E3, y la de Fase 4 con E4 + E5.

## Trazabilidad de requisitos técnicos

> En la Tarea 1 el equipo fijó ocho requisitos técnicos como objetivo del producto. Son metas preliminares, a confirmar con el cliente en la Fase 1. La tabla indica en qué entregable se define cada uno y dónde se verifica.

| Requisito técnico objetivo (Tarea 1) | Dónde se define | Dónde se verifica |
|--------------------------------------|-----------------|-------------------|
| Detección en perímetro y accesos | E1 (ingeniería de detalle) | E2 y E3: montaje y calibración (Fases 2 y 3) |
| Cobertura de cámaras con grabación | E1 | E2 y E3 (Fases 2 y 3) |
| Aviso en 30 s o menos | E1 y coordinación con la central (Fase 1) | Pruebas de disparo con la central (Fase 3) y simulacro (Fase 4) |
| Autonomía de 8 h o más | E1: cálculo eléctrico de UPS | Prueba de corte y autonomía real (Fase 4, E5) |
| Retención de video de 30 días | E1: dimensionamiento del grabador | E3: NVR configurado (Fase 3) |
| 100% de las zonas críticas cubiertas | E1: planos y relevamiento | E2 y simulacro de intrusión (Fases 2 y 4) |
| Monitoreo remoto seguro, con aviso que indica el sector | E1 | E3: app y matriz de usuarios (Fase 3) |
| Cumplimiento de la Ley 25.326 | E1 | E3 y E4: perfiles de usuario y documentación (Fases 3 y 4) |

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026*
