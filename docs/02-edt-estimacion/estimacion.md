# Estimación

> **Técnica principal:** Delphi · **Rondas realizadas:** 2 · **Estimadores:** Renzo (Líder / Gestión), Gabriel S. (Infraestructura), Lucía (Sistemas), Gabriel N. (Detección)
> **Unidad:** horas-persona del equipo integrador. No incluye horas de la cuadrilla externa ni horas de la Central de Monitoreo, que se supervisan pero no se estiman por Delphi.
> **Supuesto de dedicación:** 3 h/día hábil por integrante (15 h/semana, dentro del rango 10 a 15 h de la Tarea 2). 5 días hábiles por semana, fines de semana excluidos.

## Ronda 1 — Estimación individual anónima

Cada estimador estimó por su cuenta, sin ver las estimaciones de los demás, sobre la base del diccionario de la EDT. La tabla muestra el esfuerzo en horas-persona.

| ID | Paquete | Renzo (hs) | Gabriel S. (hs) | Lucía (hs) | Gabriel N. (hs) | Promedio R1 | Delta R1 |
|----|---------|-----------:|---------------:|----------:|--------------:|------------:|---------:|
| 6.1 | Planificación y línea base | 15 | 24 | 17 | 21 | 19.2 | 9 |
| 1.1 | Relevamiento planimétrico y planos de tendido | 23 | 38 | 27 | 34 | 30.5 | 15 |
| 1.2 | Diseño de red, cálculo UPS y dimensionamiento NVR | 31 | 48 | 35 | 43 | 39.2 | 17 |
| 1.3 | Cotizaciones, pliego de montaje y órdenes de compra | 20 | 41 | 28 | 37 | 31.5 | 21 |
| 1.4 | Coordinación previa protocolo con Central de Monitoreo | 9 | 15 | 11 | 13 | 12.0 | 6 |
| 2.1 | Zanjeo y canalizaciones (cuadrilla externa) | 8 | 17 | 11 | 15 | 12.8 | 9 |
| 2.2 | Tendido de cableado UV | 12 | 19 | 13 | 17 | 15.2 | 7 |
| 2.3 | Montaje de postes, cámaras y sensores | 15 | 24 | 17 | 22 | 19.5 | 9 |
| 2.4 | Instalación rack y UPS + prueba ping 100% | 14 | 23 | 16 | 21 | 18.5 | 9 |
| 3.1 | Configuración NVR/VMS y matriz usuarios app (Ley 25.326) | 26 | 42 | 30 | 38 | 34.0 | 16 |
| 3.2 | Calibración iterativa de sensores en terreno | 31 | 62 | 41 | 55 | 47.2 | 31 |
| 3.3 | Pruebas de disparo con Central + 7 días sin falsas alarmas | 14 | 29 | 19 | 26 | 22.0 | 15 |
| 4.1 | Planos conforme a obra | 15 | 23 | 17 | 21 | 19.0 | 8 |
| 4.2 | Manual de usuario y guía administrativa | 16 | 26 | 18 | 23 | 20.8 | 10 |
| 4.3 | Capacitación sereno y administración + actas | 13 | 20 | 15 | 18 | 16.5 | 7 |
| 5.1 | Simulacros diurno y nocturno de intrusión | 14 | 22 | 16 | 20 | 18.0 | 8 |
| 5.2 | Prueba de corte y autonomía real UPS 8h | 9 | 15 | 10 | 13 | 11.8 | 6 |
| 5.3 | Acta de Recepción Definitiva y garantía 12 meses | 8 | 12 | 9 | 11 | 10.0 | 4 |
| 6.2 | Seguimiento y control + gestión de riesgos | 24 | 38 | 28 | 34 | 31.0 | 14 |
| 6.3 | Cierre administrativo del proyecto | 5 | 8 | 6 | 7 | 6.5 | 3 |
| **TOTAL** | | | | | | **435.2** | |

> **Delta:** diferencia entre la estimación máxima y la mínima. Umbral definido por el equipo: si Delta > 10 h o > 30% del promedio, se discute y se hace otra ronda. En Ronda 1, 9 de 20 paquetes superaron el umbral, por eso fue necesaria la Ronda 2.

## Discusión entre rondas

La discusión fue facilitada por Renzo, sin atribuir estimaciones a personas, solo con argumentos y supuestos. Los 4 puntos que explicaron casi toda la dispersión fueron:

1. **3.2 Calibración iterativa (Delta R1 = 31 h, la mayor).** Gabriel N. había supuesto 2 iteraciones por sector. Lucía y Gabriel S. argumentaron que la rotación de maquinaria y las sombras cambiantes en el patio obligan a prever 3 a 4 iteraciones, más un registro por iteración. Se acordó estimar con 3 iteraciones + 1 de repaso por sector crítico.
2. **1.3 Cotizaciones y compras (Delta R1 = 21 h).** La dispersión venía de confundir esfuerzo con espera. Se aclaró: el esfuerzo es 30 h de trabajo (pedir, comparar, pliego, OC), la espera de 5 días de respuesta de proveedores está dentro de la duración de 10 días pero no suma esfuerzo. Sin ese acuerdo, unos estimaban solo trabajo y otros trabajo + espera.
3. **2.1 Zanjeo y canalizaciones (Delta R1 = 9 h en supervisión).** Unos estimaban supervisión continua y otros supervisión por hitos. Se acordó supervisión por hitos: inicio, 50% y cierre de cada tramo, más acta. El esfuerzo del equipo es supervisión, no el zanjeo en sí, que lo hace la cuadrilla a tiempo completo.
4. **1.2 Diseño red, UPS y NVR (Delta R1 = 17 h).** Se había duplicado parte del cálculo UPS con 1.1. Se acordó: 1.1 releva y define ubicación, 1.2 calcula y dimensiona. Sin duplicación, la estimación bajó y convergió.

Otros supuestos explicitados: la app se configura con la matriz de usuarios ya definida en 1.2, no se diseña desde cero en 3.1; la prueba de 7 días en 3.3 es observación, no 7 días de trabajo continuo; y la capacitación en 4.3 es 2 jornadas, no 4.

## Ronda 2 — Re-estimación con información del grupo

| ID | Paquete | Renzo (hs) | Gabriel S. (hs) | Lucía (hs) | Gabriel N. (hs) | Promedio R2 | Delta R2 | Estimación final |
|----|---------|-----------:|---------------:|----------:|--------------:|------------:|---------:|-----------------:|
| 6.1 | Planificación y línea base | 18 | 19 | 19 | 19 | 18.8 | 1 | **18** |
| 1.1 | Relevamiento planimétrico y planos de tendido | 30 | 32 | 31 | 32 | 31.2 | 2 | **30** |
| 1.2 | Diseño de red, cálculo UPS y dimensionamiento NVR | 35 | 37 | 36 | 36 | 36.0 | 2 | **36** |
| 1.3 | Cotizaciones, pliego de montaje y órdenes de compra | 28 | 32 | 29 | 31 | 30.0 | 4 | **30** |
| 1.4 | Coordinación previa protocolo con Central de Monitoreo | 11 | 12 | 12 | 12 | 11.8 | 1 | **12** |
| 2.1 | Zanjeo y canalizaciones (cuadrilla externa) | 11 | 13 | 12 | 12 | 12.0 | 2 | **12** |
| 2.2 | Tendido de cableado UV | 14 | 15 | 15 | 15 | 14.8 | 1 | **15** |
| 2.3 | Montaje de postes, cámaras y sensores | 17 | 19 | 18 | 18 | 18.0 | 2 | **18** |
| 2.4 | Instalación rack y UPS + prueba ping 100% | 18 | 19 | 18 | 19 | 18.5 | 1 | **18** |
| 3.1 | Configuración NVR/VMS y matriz usuarios app (Ley 25.326) | 33 | 35 | 34 | 35 | 34.2 | 2 | **33** |
| 3.2 | Calibración iterativa de sensores en terreno | 43 | 48 | 44 | 46 | 45.2 | 5 | **45** |
| 3.3 | Pruebas de disparo con Central + 7 días sin falsas alarmas | 20 | 22 | 21 | 22 | 21.2 | 2 | **21** |
| 4.1 | Planos conforme a obra | 18 | 19 | 19 | 19 | 18.8 | 1 | **18** |
| 4.2 | Manual de usuario y guía administrativa | 20 | 21 | 20 | 21 | 20.5 | 1 | **21** |
| 4.3 | Capacitación sereno y administración + actas | 14 | 15 | 15 | 15 | 14.8 | 1 | **15** |
| 5.1 | Simulacros diurno y nocturno de intrusión | 17 | 18 | 17 | 18 | 17.5 | 1 | **18** |
| 5.2 | Prueba de corte y autonomía real UPS 8h | 12 | 12 | 12 | 12 | 12.0 | 0 | **12** |
| 5.3 | Acta de Recepción Definitiva y garantía 12 meses | 9 | 9 | 9 | 9 | 9.0 | 0 | **9** |
| 6.2 | Seguimiento y control + gestión de riesgos | 29 | 32 | 30 | 31 | 30.5 | 3 | **30** |
| 6.3 | Cierre administrativo del proyecto | 6 | 6 | 6 | 6 | 6.0 | 0 | **6** |
| **TOTAL** | | | | | | **420.8** | | **417 hs** |

**Convergencia lograda.** En Ronda 2 ningún paquete supera el umbral de Delta > 10 h, salvo 3.2 que queda en 5 h y se acepta por su incertidumbre ambiental. El equipo adopta como estimación final el valor consensuado, que en todos los casos está dentro de 1 h del promedio de Ronda 2. No se necesitó una tercera ronda.

### Totales por entregable

| Entregable | Esfuerzo (hs) | % del total |
|------------|--------------:|-----------:|
| E1 | 108 | 25.9% |
| E2 | 63 | 15.1% |
| E3 | 99 | 23.7% |
| E4 | 54 | 12.9% |
| E5 | 39 | 9.4% |
| Gestión | 54 | 12.9% |
| **TOTAL** | **417** | **100%** |

## Conversión a duración

> **Fórmula:** Duración (días hábiles) = Esfuerzo (hs) / (Recursos × 3 h/día por persona)
> **Excepciones explicitadas, no errores de cálculo:**
>
> - **2.1, 2.2, 2.3:** la duración la manda la cuadrilla externa a tiempo completo (8, 6 y 7 días). El esfuerzo en la tabla es solo supervisión del equipo.
> - **1.3:** 10 días incluyen 5 días de espera de cotizaciones. El esfuerzo es 30 h de trabajo, la espera no suma esfuerzo.
> - **3.3:** 7 días son calendario de observación (7 días corridos sin falsas alarmas). El esfuerzo es 21 h de monitoreo y registro repartidas en esos 7 días.
> - **6.2:** 86 días son paralelos a todo el proyecto (seguimiento semanal). No suma duración al camino crítico.

| ID | Paquete | Esfuerzo (hs) | Recursos (personas) | Dedicación | Duración (días hábiles) | Tipo de duración |
|----|---------|-------------:|-------------------:|-----------:|-------------------------:|------------------|
| 6.1 | Planificación y línea base | 18 | 2 | 3 h/día | 3 | Esfuerzo |
| 1.1 | Relevamiento planimétrico y planos de tendido | 30 | 2 | 3 h/día | 5 | Esfuerzo |
| 1.2 | Diseño de red, cálculo UPS y dimensionamiento NVR | 36 | 2 | 3 h/día | 6 | Esfuerzo |
| 1.3 | Cotizaciones, pliego de montaje y órdenes de compra | 30 | 1 | 3 h/día | 10 | Esfuerzo + 5 d espera |
| 1.4 | Coordinación previa protocolo con Central de Monitoreo | 12 | 1 | 3 h/día | 4 | Esfuerzo |
| 2.1 | Zanjeo y canalizaciones (cuadrilla externa) | 12 (supervisión) | 1 | 3 h/día | 8 | Cuadrilla a tiempo completo |
| 2.2 | Tendido de cableado UV | 15 (supervisión) | 1 | 3 h/día | 6 | Cuadrilla a tiempo completo |
| 2.3 | Montaje de postes, cámaras y sensores | 18 (supervisión) | 1 | 3 h/día | 7 | Cuadrilla a tiempo completo |
| 2.4 | Instalación rack y UPS + prueba ping 100% | 18 | 2 | 3 h/día | 3 | Esfuerzo |
| 3.1 | Configuración NVR/VMS y matriz usuarios app (Ley 25.326) | 33 | 2 | 3 h/día | 6 | Esfuerzo |
| 3.2 | Calibración iterativa de sensores en terreno | 45 | 2 | 3 h/día | 8 | Esfuerzo |
| 3.3 | Pruebas de disparo con Central + 7 días sin falsas alarmas | 21 | 1 | 3 h/día | 7 | Calendario: 7 días observación |
| 4.1 | Planos conforme a obra | 18 | 1 | 3 h/día | 6 | Esfuerzo |
| 4.2 | Manual de usuario y guía administrativa | 21 | 1 | 3 h/día | 7 | Esfuerzo |
| 4.3 | Capacitación sereno y administración + actas | 15 | 1 | 3 h/día | 5 | Esfuerzo |
| 5.1 | Simulacros diurno y nocturno de intrusión | 18 | 2 | 3 h/día | 3 | Esfuerzo |
| 5.2 | Prueba de corte y autonomía real UPS 8h | 12 | 2 | 3 h/día | 2 | Esfuerzo |
| 5.3 | Acta de Recepción Definitiva y garantía 12 meses | 9 | 1 | 3 h/día | 3 | Esfuerzo |
| 6.2 | Seguimiento y control + gestión de riesgos | 30 | 1 | 3 h/día | 86 (paralelo) | Paralelo, no suma al CPM |
| 6.3 | Cierre administrativo del proyecto | 6 | 1 | 3 h/día | 2 | Esfuerzo |

**Verificación:** 417 h totales / (4 personas × 15 h/semana) = 6,95 semanas de capacidad pura. El proyecto dura 86 días hábiles (17,2 semanas) porque gran parte del trabajo es secuencial, hay esperas de proveedores y observación de 7 días, y no todos trabajan en todos los paquetes a la vez. La diferencia entre capacidad y duración es esperable y no es holgura desperdiciada.

## Otras técnicas (verificación con tres puntos)

Como verificación, se aplicó estimación por tres puntos a los 2 paquetes con mayor incertidumbre. No reemplaza a Delphi, solo confirma que el valor Delphi está dentro del rango razonable.

| Paquete | Optimista (O) | Más probable (M) | Pesimista (P) | Estimación (O + 4M + P) / 6 | Delphi final |
|---------|:-------------:|:----------------:|:-------------:|:---------------------------:|:------------:|
| 3.2 Calibración iterativa | 32 | 44 | 62 | 45,0 | 45 |
| 1.3 Cotizaciones y compras | 22 | 30 | 40 | 30,3 | 30 |

En ambos casos la estimación PERT coincide con Delphi dentro de 1 h, lo que refuerza la credibilidad del consenso.

## Estimación de costos (referencial, fuera de Delphi)

El costo de hardware, cuadrilla y licencias se define con cotizaciones firmes en 1.3. Acá se estima solo el costo interno de mano de obra del equipo integrador, a modo referencial.

| Concepto | Esfuerzo / cantidad | Costo unitario (referencial) | Costo total |
|----------|:-------------------:|:---------------------------:|------------:|
| Mano de obra equipo integrador | 417 hs | $ 18.000 / h | $ 7.506.000 |
| Materiales / hardware | Según cotización en 1.3 | A confirmar con OC | A confirmar |
| Servicios / licencias (VMS/app) | Según cotización en 1.3 | A confirmar con OC | A confirmar |
| Reserva de contingencia (10% sobre mano de obra) | 10% | | $ 750.600 |
| **TOTAL mano de obra + contingencia** | | | **$ 8.256.600** |

> Valor hora a confirmar por Gerencia. No incluye hardware, cuadrilla externa ni abono de monitoreo (exclusión del alcance). Si el valor hora cambia, el total se recalcula sin cambiar el esfuerzo ni la duración.

---

*Área de Posgrado · Gestión de Proyectos · Especializaciones FIUNER · 2026 · Equipo 4*
