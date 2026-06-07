## Módulo 11: Respuesta a Incidentes

### Acerca de este módulo

Nadie puede prevenir todos los ataques cibernéticos. La seguridad de un sistema realmente radica en **qué tan bien la organización puede responder a un ataque cuando ocurre**.

Esta respuesta incluye:

- **Detener** un ataque en curso
- **Reparar y restaurar** el sistema
- **Analizar ataques** para aprender de ellos y mejorar el sistema antes de que llegue el próximo ataque

Te damos la bienvenida al módulo de **Respuesta a Incidentes**.

#### En este módulo aprenderás:

- Las **fases de respuesta a incidentes**
- Las **responsabilidades del equipo de respuesta a incidentes**
- Los **planes de respuesta a incidentes** y cómo crear uno sólido
- El **análisis de intrusiones** y cómo un marco de análisis de intrusiones te ayuda a planificar la respuesta al enseñarte a **pensar como un atacante**

### Objetivos de aprendizaje

Luego de completar este módulo, deberías ser capaz de:

- **Aplicar un marco de respuesta a incidentes adecuado** en función de las necesidades de una organización
- **Identificar las funciones del equipo de respuesta a incidentes**
- **Aplicar el marco MITRE ATT&CK**
- **Aplicar el marco Cyber Kill Chain**
- **Responder a un ataque de red**

### Acerca de esta lección: Descripción general de la respuesta a incidentes

Los ciberataques siguen ocurriendo. Independientemente de cuántas precauciones y protecciones contengan las redes, **algunos ataques inevitablemente pasan por sus defensas**.

> Los administradores de TI deben entender que un **ataque ocurrirá en algún momento** y considerar qué hacer cuando eso suceda.

#### En esta lección aprenderás:

- **Qué tipo de ataques** pueden ocurrir
- **Qué pasos** pueden tomar los administradores para **detener un ataque** y **mitigar sus efectos**
- Cómo las organizaciones pueden **recuperarse** de un ataque
- **Qué pueden aprender** de un ataque

### Visión general: Respuesta a incidentes

#### El escenario

Es una mañana tranquila, hasta que empiezan a llegar alertas sobre **accesos no autorizados** y **descargas no autorizadas**. ¡Los atacantes obtuvieron acceso a tu red! Es una emergencia que nadie quiere ver: una **filtración de datos**.

---

#### ¿Qué es un plan de respuesta a incidentes?

Un **plan de respuesta a incidentes** es un conjunto de **acciones y responsabilidades** para aplicar en caso de un incidente de ciberseguridad.

> Los analistas y otros miembros del equipo elaboran el plan **antes** de que se necesite, para que esté listo para una respuesta rápida.

---

#### Pasos de la respuesta a incidentes (según el video)

| Paso | Acción | Propósito |
|------|--------|-----------|
| **1** | Activar el equipo de respuesta a incidentes | Enviar mensaje de emergencia a todos los miembros |
| **2** | Revisar el plan | Cada miembro encuentra sus tareas asignadas |
| **3** | **Aislar** los sistemas afectados | Desconectarlos de la red para evitar más daños |
| **4** | **Deshabilitar** cuentas comprometidas | Forzar cambios de contraseña |
| **5** | **Analizar** sistemas afectados | Determinar el alcance de la violación |
| **6** | **Recopilar evidencia** | Archivos de registro para entender el alcance e identificar atacantes |
| **7** | **Erradicar** el malware | Eliminar software malicioso de sistemas afectados |
| **8** | **Restaurar** sistemas | Usar copias de seguridad para reparar datos dañados |
| **9** | **Actualizar defensas** | Firewalls, sistemas de detección de intrusiones |
| **10** | **Comunicar** a empleados | Actualizar sobre el estado y orientar sobre cómo evitar incidentes futuros |
| **11** | **Evaluar** procesos existentes | Identificar áreas de mejora |

---

#### Causa del incidente

> *"Descubres que la violación ocurrió por una **vulnerabilidad en un sistema** causada por un **malware que descargó un usuario desprevenido**."*

---

#### Beneficio de tener un plan

> *"Los ataques son estresantes, pero la **respuesta inteligente y organizada** ante incidentes reduce la preocupación y la posibilidad de **errores en la toma de decisiones** en el momento en que ocurren los ataques."*

---

#### En general

Todos están muy agradecidos de tener un plan listo cuando fue necesario. El equipo sigue el plan paso a paso:

1. **Aislar** sistemas afectados
2. **Erradicar** el malware
3. **Restaurar** sistemas (usando copias de seguridad)
4. **Actualizar** defensas
5. **Evaluar** procesos para mejorar

### ¿Qué es la respuesta a incidentes?

Los incidentes de ciberseguridad pueden ocurrir en **cualquier organización**, incluso con medidas preventivas estrictas. El riesgo hace que la **respuesta a incidentes (IR)** sea esencial para el programa de tecnologías de la información (TI) de cualquier organización.

#### Definición

La **respuesta a incidentes (IR)** comprende el **conjunto de acciones** que realiza una organización para:

| Acción | Propósito |
|--------|-----------|
| **Preparar** | Estar listos antes de que ocurra un ataque |
| **Detectar** | Identificar cuándo ocurre un ataque |
| **Detener** | Contener y erradicar la amenaza |
| **Reparar** | Arreglar cualquier daño causado por el ataque |
| **Recopilar datos** | Aprender para prevenir ataques similares en el futuro |

#### Beneficios de la respuesta a incidentes

- **Reduce el daño** que causan los incidentes
- **Produce información** que puedes emplear para prevenir o manejar incidentes similares en el futuro

#### Naturaleza continua

> La IR puede responder a un **solo evento**, pero a nivel global es un **proceso continuo** que presenta:
> - **Aprendizaje continuo** para descubrir cómo proteger mejor a la organización
> - **Avances** para poner ese conocimiento a trabajar

### Marcos de respuesta a incidentes

¿Cómo comienzan las organizaciones a recopilar toda la información necesaria para un plan integral de respuesta a incidentes? Afortunadamente, comienzan con un **marco de respuesta a incidentes establecido**.

#### ¿Qué es un marco de respuesta a incidentes?

Un **marco de respuesta a incidentes** proporciona una **estructura** para respaldar las operaciones de respuesta a incidentes.

| Característica | Descripción |
|----------------|-------------|
| **Proporciona orientación** | Sobre **qué** se debe hacer (no sobre **cómo** se hace) |
| **Flexible** | Permite agregar o eliminar elementos según sea necesario para satisfacer las necesidades de cada organización |

---

#### ¿Por qué es importante elegir el marco adecuado?

> Identificar el **mejor marco** garantiza que una organización esté preparada para el éxito.

El mejor marco:
- Aborda las **necesidades** de una organización
- Se puede aplicar **fácilmente** en todas las operaciones

---

#### El marco NIST

**¿Qué es el NIST?**  
El **National Institute of Standards and Technology (NIST)** es una agencia operada por el **Departamento de Comercio de Estados Unidos** que proporciona estándares y recomendaciones para muchos sectores tecnológicos.

**¿Qué desarrolló?**  
El NIST desarrolló la **Guía de manejo de incidentes de seguridad informática** como marco de respuesta a incidentes.

> Aunque el marco NIST es **popular** y se considera el **estándar líder**, los equipos pueden elegir otro marco y adaptarlo a las necesidades de su organización.

---

#### Beneficio de un marco común

Un marco de respuesta a incidentes **armoniza** el plan de respuesta en una red más amplia de personas.

**Ejemplo:** Una gran corporación multinacional podría tener centros distribuidos en todo el mundo. Adoptar un **marco común** permite a los empleados trabajar junto con colegas de todo el mundo.

---

### Resumen

| Concepto | Explicación |
|----------|-------------|
| **Marco IR** | Estructura que guía **qué** hacer en respuesta a incidentes |
| **NIST** | Agencia de EE.UU. que creó el marco IR más popular |
| **Flexibilidad** | Los marcos se pueden adaptar a cada organización |
| **Beneficio clave** | Armoniza la respuesta entre equipos globales |

1. ¿El marco es lo mismo que "respuesta a incidentes (IR)"?
NO exactamente. Son conceptos relacionados pero diferentes:

## Concepto	Explicación
Respuesta a incidentes (IR)	Es el conjunto de acciones que hacés cuando ocurre un ataque (detectar, contener, erradicar, recuperar). Es lo que hacés.
Marco de respuesta a incidentes	Es la estructura o guía que te dice cómo organizar esas acciones. Es cómo lo hacés (el método, los pasos, las fases).
Analogía fácil:

## Concepto	Analogía
Respuesta a incidentes (IR)	Apagar un incendio (las acciones: agarrar el matafuegos, llamar a los bomberos, evacuar)
Marco de IR	El protocolo del cuartel de bomberos (qué hace cada uno, en qué orden, quién manda, cómo se comunica)
Resumen: La IR son las acciones. El marco es la estructura que organiza esas acciones.

2. ¿El marco más popular/líder es el NIST?
✅ SÍ. El marco del NIST (National Institute of Standards and Technology, EE.UU.) es el más popular y considerado el estándar líder para respuesta a incidentes.

El NIST divide la respuesta a incidentes en 4 fases:

Fase	Acciones
1. Preparación	Tener el plan, el equipo, las herramientas
2. Detección y análisis	Identificar que ocurrió un incidente
3. Contención, erradicación y recuperación	Detener el ataque, eliminar la amenaza, restaurar sistemas
4. Actividad posterior	Aprender y mejorar para el futuro
3. ¿El marco es como la ISO 27001?
✅ Excelente analogía. Sí, es una idea similar, pero con un enfoque diferente:

## Concepto	Enfoque	¿Para qué sirve?
ISO 27001	Sistema de Gestión de Seguridad de la Información (SGSI)	Es un marco general para implementar, mantener y mejorar la seguridad de la información en toda la organización (preventivo + correctivo).
NIST (para IR)	Respuesta a incidentes	Es un marco específico para saber qué hacer cuando ya ocurrió un ataque (reactivo).
Analogía final:

## Concepto	Analogía
ISO 27001	El manual de construcción de una casa (cimientos, paredes, techos, instalaciones eléctricas) → todo el edificio
NIST (IR)	El protocolo de evacuación en caso de incendio → situación de emergencia específica
En resumen:

* ISO 27001 → marco general de seguridad (previene, gestiona, mejora)

* NIST (IR) → marco específico para respuesta a incidentes (qué hacer cuando falla la prevención).

### Fases de respuesta a incidentes

#### Punto de partida: Identificar la superficie de ataque

El proceso de IR comienza con la **identificación de una superficie de ataque**. Este análisis ayuda a **priorizar las áreas más vulnerables y críticas** que requieren una supervisión y protección sólidas.

##### ¿Qué es una superficie de ataque?

Una **superficie de ataque** abarca **todos los puntos** de los componentes de un sistema, los puntos de acceso y otros lugares donde un atacante puede intentar:

- **Extraer datos** del sistema
- **Ingresar** al sistema
- **Afectar** el sistema

> Comprender y mapear exhaustivamente la superficie de ataque permite priorizar las defensas.

---

#### El flujo de la respuesta a incidentes

A continuación, el equipo:

1. **Evalúa la gravedad** de un ataque
2. **Desarrolla una estrategia de priorización** de amenazas
3. **Investiga y mitiga** el ataque
4. **Restaura las operaciones**
5. **Toma medidas preventivas** para reducir la posibilidad de que se repita

---

#### Las 4 fases principales de respuesta a incidentes

Los equipos suelen realizar las tareas de respuesta a incidentes en **cuatro fases principales**:

| Fase | Descripción |
|------|-------------|
| **1. Preparación** | Establecer el plan, el equipo, las herramientas y los procedimientos antes de que ocurra un incidente |
| **2. Detección y análisis** | Identificar que ha ocurrido un incidente, analizar alertas y determinar el alcance |
| **3. Contención y erradicación** | Detener la propagación del ataque y eliminar la amenaza de los sistemas afectados |
| **4. Recuperación** | Restaurar los sistemas a su estado normal y asegurar que la amenaza haya sido completamente eliminada |

---

### Diagrama del proceso de IR
┌─────────────────────────────────────────────────────────────────────────────┐
│ FASES DE RESPUESTA A INCIDENTES │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌───────────┐ │
│ │ 1. │ │ 2. │ │ 3. │ │ 4. │ │
│ │ Preparación │───▶│ Detección │───▶│ Contención │───▶│Recuperación│ │
│ │ │ │ y análisis │ │ y erradicación│ │ │ │
│ └──────────────┘ └──────────────┘ └──────────────┘ └───────────┘ │
│ │
│ Antes del ataque Durante el ataque Después del ataque │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

---

### Resumen de cada fase

| Fase | Actividades clave |
|------|-------------------|
| **Preparación** | - Crear plan de respuesta a incidentes<br>- Formar equipo IR<br>- Implementar herramientas de monitoreo<br>- Realizar capacitaciones y simulacros |
| **Detección y análisis** | - Monitorear alertas (SIEM, EDR, etc.)<br>- Analizar indicadores de compromiso (IOCs)<br>- Determinar alcance y gravedad<br>- Priorizar incidentes |
| **Contención y erradicación** | - Aislar sistemas afectados<br>- Deshabilitar cuentas comprometidas<br>- Eliminar malware y amenazas<br>- Parchear vulnerabilidades |
| **Recuperación** | - Restaurar sistemas desde backups<br>- Verificar que la amenaza fue erradicada<br>- Reincorporar sistemas a la red<br>- Monitorear para detectar reinfección |

---

> **Nota:** El marco más popular para estas 4 fases es el del **NIST** (National Institute of Standards and Technology).

### Actividad: Fase 1 - Preparación (HealthGuard Medical Services)

#### Antecedentes

HealthGuard Medical Services es un proveedor líder de servicios médicos (telesalud y citas en línea). El equipo de TI implementó múltiples medidas de preparación:

| Medida de preparación | Propósito |
|----------------------|-----------|
| Programa regular de parches | Abordar vulnerabilidades conocidas con prontitud |
| Autenticación multifactor (MFA) | Evitar el acceso no autorizado |
| Sistema de detección de intrusiones (IDS) | Monitorear tráfico y detectar posibles amenazas |
| Pruebas de simulación de phishing | Capacitar a empleados para identificar y evitar emails de phishing |
| Plan de copia de seguridad y recuperación ante desastres | Restaurar datos críticos de forma rápida y segura |

#### Elementos clave de la Fase de Preparación

Según el módulo, la preparación incluye:

- **Evaluación de riesgos** (monitoreo de la superficie de ataque)
- **Seguridad del host** (configuración de dispositivos, listas de control de acceso)
- **Seguridad de la red** (perímetro configurado para rechazar actividad no permitida)
- **Prevención de malware** (software antimalware, limpieza de sistemas)
- **Concientización y capacitación de usuarios** (prácticas seguras, políticas actualizadas)

#### Política de respuesta a incidentes

La política debe incluir:

1. Estructura del equipo de respuesta a incidentes
2. Funciones y responsabilidades de los miembros
3. Medios, herramientas y recursos para identificar y recuperar datos
4. Pruebas de políticas (quiénes son responsables)
5. Plan de acción para ejecutar la respuesta de principio a fin

### Fase 1: Preparación - Prevención vs. Respuesta

#### La distinción clave

| Concepto | Acciones | Cuándo |
|----------|----------|--------|
| **Prevención** | Parches, MFA, firewalls, capacitación | **Antes** del ataque |
| **Respuesta a incidentes (IR)** | Detener, contener, erradicar, recuperar | **Durante/después** del ataque |

#### ¿Por qué la Fase 1 de IR incluye prevención?

Porque el **marco NIST** define la **Preparación** como la primera fase de la respuesta a incidentes. Esta fase incluye:

1. **Medidas de prevención** (para reducir la cantidad de incidentes)
2. **Medidas de preparación** (para estar listos cuando ocurran)

El equipo de IR **no es dueño de toda la prevención**, pero **tiene interés en reducir incidentes** y en **estar listo** para cuando ocurran.

#### Ejemplo: HealthGuard Medical Services

| Acción | Tipo | ¿Por qué está en Fase 1? |
|--------|------|-------------------------|
| Parches regulares | Prevención | Reduce vulnerabilidades (menos incidentes) |
| Autenticación multifactor | Prevención | Evita accesos no autorizados |
| Plan de backups y recuperación | **Preparación IR** | Permite recuperar datos durante un incidente |
| Capacitación anti-phishing | Prevención | Empleados más alerta |

> **Conclusión:** La Fase 1 mezcla prevención y preparación. La prevención NO es respuesta a incidentes, pero es una actividad preparatoria que el equipo de IR promueve para reducir la carga de trabajo.

### El rol del equipo de IR en la preparación

El equipo de **Respuesta a Incidentes (IR)** no ejecuta toda la seguridad, pero cumple un rol clave:

| Función | Descripción |
|---------|-------------|
| **Guían** | Establecen las políticas y procedimientos de seguridad |
| **Asesoran** | Recomiendan medidas de prevención a TI y otros equipos |
| **Coordinan** | Trabajan con TI para implementar controles |
| **Responden** | Activan el plan cuando ocurre un incidente real |

#### En el caso de HealthGuard:

| Acción | ¿Quién la ejecuta? | ¿Quién la guía/asesora? |
|--------|-------------------|------------------------|
| Parches regulares | Equipo de TI | Equipo de IR |
| Autenticación multifactor | Equipo de TI | Equipo de IR |
| Detección de intrusiones (IDS) | Equipo de TI | Equipo de IR |
| Pruebas de phishing | Equipo de TI | Equipo de IR |
| Plan de backup y recuperación | **Equipo de IR** | Equipo de IR |

> **Conclusión:** El equipo de IR **guía y asesora** sobre prevención, pero **ejecuta y coordina** la respuesta activa durante un incidente.

## Fase 2: Detección y Análisis

En esta fase se reconoce que, independientemente de las medidas preventivas implementadas, los incidentes de seguridad pueden ocurrir. Por ello, es fundamental detectarlos y analizarlos rápidamente para minimizar su impacto en los sistemas y usuarios.

Actualmente, el uso de herramientas de detección de amenazas es común en los entornos tecnológicos. Sin embargo, si estas soluciones no están correctamente adaptadas a la organización, pueden no identificar amenazas emergentes. Por esta razón, contar con un plan detallado de detección y análisis mejora significativamente la capacidad de respuesta.

### Precursores e Indicadores

La detección de incidentes se basa en la identificación de señales que se clasifican en dos tipos:

* **Precursores:** Son señales que indican que un incidente podría ocurrir en el futuro.
  *Ejemplo:* registros de un servidor web que muestran el uso de herramientas de escaneo de puertos.
  Estos permiten actuar de forma preventiva reforzando la seguridad antes de un ataque.

* **Indicadores:** Son señales de que un incidente está ocurriendo o ya ocurrió.
  *Ejemplo:* alertas de antivirus detectando un troyano en un dispositivo.
  Son de naturaleza reactiva y suelen ser más frecuentes que los precursores.

#### Fuentes de detección

Los precursores e indicadores pueden provenir de:

* Sistemas de seguridad (IDS/IPS, SIEM, antivirus)
* Registros de red, sistemas y aplicaciones
* Información pública (como la NVD o noticias)
* Reportes de usuarios o personal interno/externo

---

### Documentación de Incidentes

Una vez detectado un posible incidente, el equipo de respuesta debe documentarlo de inmediato. Esto permite una mejor gestión del evento actual y sirve como referencia para incidentes futuros.

#### Información básica a registrar:

* ¿Dónde ocurrió el incidente?
* ¿Quién lo detectó o reportó?
* ¿Cómo fue detectado?
* ¿Qué otras áreas fueron afectadas y cuándo?
* ¿Se identificó la fuente del incidente? ¿Dónde y cuándo?

---

### Priorización de Incidentes

Los incidentes deben priorizarse según su impacto, no por el orden en que ocurren. Se consideran tres tipos de impacto:

* Impacto funcional
* Impacto informativo
* Impacto de recuperabilidad

#### Impacto de la Recuperabilidad

Evalúa el nivel de daño y el tiempo necesario para restaurar el sistema:

* **Regular:** Recuperación predecible con recursos actuales.
* **Complementado:** Requiere recursos adicionales, pero es predecible.
* **Ampliado:** No se puede estimar el tiempo de recuperación; requiere ayuda externa.
* **No recuperable:** No es posible recuperar (por ejemplo, filtración de datos sensibles).

---

### Notificación de Incidentes

Una vez documentado y evaluado el incidente, se debe notificar a las partes relevantes dentro de la organización para iniciar la respuesta adecuada.

#### Personal que debe ser notificado:

* Director de Información (CIO)
* Gerentes y responsables de seguridad
* Equipos internos de respuesta a incidentes
* Equipos externos (si aplica)

#### Otras áreas que pueden intervenir:

* Propietarios del sistema afectado
* Recursos Humanos (si hay implicación de usuarios)
* Asuntos públicos (si puede haber impacto mediático)
* Área legal o fuerzas de seguridad (si corresponde)

---

Esta fase es clave para una respuesta efectiva ante incidentes, ya que una detección temprana y un análisis adecuado permiten reducir daños, optimizar recursos y mejorar la seguridad organizacional.


### Actividad: Fase 2 - Detección y análisis (HealthGuard Medical Services)
#### Antecedentes

El equipo de TI de HealthGuard detectó actividad sospechosa en su red:

| Herramienta | Función |
|-------------|---------|
| **IDS/IPS** | Detectan anomalías y posibles violaciones de seguridad |
| **SIEM** | Analizó el tráfico y detectó intentos fallidos de inicio de sesión desde IP desconocida |

### ¿Qué son IDS e IPS?

| Herramienta | Nombre | ¿Qué hace? | ¿Actúa solo? |
|-------------|--------|------------|--------------|
| **IDS** | Sistema de Detección de Intrusiones | Detecta y alerta | ❌ No (solo avisa) |
| **IPS** | Sistema de Prevención de Intrusiones | Detecta, alerta y **bloquea** | ✅ Sí (actúa automáticamente) |

**Analogía:**
- **IDS** = Cámara de seguridad (te avisa, pero no detiene al ladrón)
- **IPS** = Guardia de seguridad (te avisa Y detiene al ladrón)

**En el caso de HealthGuard:**
- Usaron **IDS** para detectar actividad sospechosa
- Usaron **IPS** para detectar Y PREVENIR la intrusión

### ¿IDS e IPS se usan juntos o separados?

**Las 3 opciones son válidas:**

| Opción | Ventaja | Desventaja |
|--------|---------|------------|
| **Solo IDS** | Más económico, no interrumpe el tráfico | No bloquea automáticamente |
| **Solo IPS** | Bloquea automáticamente | Puede bloquear tráfico legítimo (falso positivo) |
| **IDS + IPS** | Lo mejor de ambos mundos | Más caro, más complejo de configurar |

**En la práctica:** Hoy en día, los **firewalls de nueva generación (NGFW)** suelen incluir **ambas funciones** en un solo dispositivo.

**En HealthGuard:** Usaron tanto IDS como IPS, probablemente como parte de su estrategia de seguridad en capas.

#### Acciones tomadas

| Paso | Acción |
|------|--------|
| 1 | Detección de actividad sospechosa (IDS/IPS) |
| 2 | Análisis de tráfico (SIEM) |
| 3 | Activación del plan de respuesta a incidentes |
| 4 | Documentación de la información del ataque |
| 5 | Notificación a la gerencia |
| 6 | Investigación de la fuente y alcance del ataque |

#### Conceptos clave de la Fase 2

| Concepto | Definición | Ejemplo del caso |
|----------|-----------|------------------|
| **Precursor** | Señal de que un incidente **podría ocurrir** | Intentos fallidos de inicio de sesión |
| **Indicador** | Señal de que un incidente **está ocurriendo** | Alerta de IDS/IPS por tráfico anómalo |

#### Evaluación de impactos

| Tipo de impacto | Pregunta que responde |
|----------------|----------------------|
| **Funcional** | ¿Cómo afecta el ataque a la eficacia del sistema? |
| **Informativo** | ¿Qué información fue robada o destruida? |
| **Recuperabilidad** | ¿Cuánto tiempo tomará restaurar el sistema? |

#### Notificaciones

El equipo de IR notificó a la gerencia según el componente de comunicación del plan de respuesta a incidentes.
Posibles preguntas de la actividad
Pregunta 1: ¿Qué herramienta utilizó HealthGuard para detectar actividad sospechosa en su red?

✅ Sistemas de detección de intrusiones (IDS) y sistemas de prevención de intrusiones (IPS)

Pregunta 2: ¿Qué herramienta utilizó HealthGuard para analizar el tráfico y descubrir el acceso no autorizado?

✅ Sistema de gestión de eventos e información de seguridad (SIEM)

Pregunta 3: Los intentos fallidos de inicio de sesión desde una IP desconocida son un ejemplo de:

✅ Precursor (señal de que un incidente podría ocurrir en el futuro)

Pregunta 4: ¿Qué acciones tomó el equipo de IR inmediatamente después de detectar el ataque?

✅ Documentar la información del ataque y notificar a la gerencia

Análisis de la Fase 2: Detección y análisis
Acciones que tomó HealthGuard en esta fase:
Acción	Herramienta/Método	Tipo
Detectó actividad sospechosa	IDS/IPS (detección/prevención de intrusiones)	Indicador (señal de que el incidente está ocurriendo ahora)
Analizó el tráfico	SIEM (gestión de eventos e información de seguridad)	Análisis
Detectó intentos fallidos de inicio de sesión desde IP desconocida	SIEM	Precursor (señal de que un incidente podría ocurrir)
Activó el plan de respuesta a incidentes	Plan establecido	Respuesta
Documentó información del ataque	Registro de incidentes	Documentación
Notificó a la gerencia	Plan de comunicación	Notificación
Investigó fuente y alcance	Análisis	Investigación
Conceptos clave de esta fase
Precursores vs. Indicadores
Concepto	Definición	Ejemplo
Precursor	Señal de que un incidente podría ocurrir en el futuro	Escáner de puertos, intentos fallidos de inicio de sesión
Indicador	Señal de que un incidente está ocurriendo ahora	Alerta de antivirus, tráfico anómalo detectado por IDS
Fuentes de precursores e indicadores
Fuente	Ejemplo
Alertas (IDS/IPS, SIEM, antivirus)	✅ HealthGuard usó IDS/IPS y SIEM
Registros (logs)	Registros de red, dispositivos, aplicaciones
Información pública	NVD, noticias
Personas	Reportes internos o externos
Categorías para evaluar el impacto
Tipo de impacto	Describe	Niveles
Impacto funcional	Cómo afecta el ataque a la eficacia del sistema	Ninguno, Bajo, Medio, Alto
Impacto informativo	Cómo afecta a la información (robo, destrucción)	Ninguno, Violación de privacidad, Violación de propiedad, Pérdida de integridad
Impacto de recuperabilidad	Cuánto tiempo tomará restaurar el sistema	Regular, Complementado, Ampliado, No recuperable
Documentación de incidentes
La documentación debe incluir:

Pregunta	Propósito
¿Dónde ocurrió?	Localizar el incidente
¿Quién lo descubrió?	Rastrear la fuente del reporte
¿Cómo se descubrió?	Entender el método de detección
¿Qué otras áreas se vieron comprometidas?	Determinar el alcance
¿Se localizó la fuente?	Identificar al atacante (si es posible)
Notificaciones
Personas a notificar:

Director de información (CIO)

Gerentes locales y jefes de seguridad

Otros equipos IR (si aplica)

Equipos externos (si aplica)

Propietario del sistema

Recursos humanos (si hay implicación de usuarios)

Asuntos públicos (si puede llegar a medios)

Departamento legal y aplicación de la ley (si corresponde)

## Fase 3: Contención y Erradicación

Una vez detectado y analizado un incidente de seguridad, el equipo de respuesta a incidentes (IR) debe actuar rápidamente para contener el daño y eliminar la amenaza. Esta fase es crítica, ya que busca evitar que el ataque continúe propagándose y afecte más recursos.

Se puede entender esta etapa con una analogía: el sistema es como un barco bajo ataque. Primero se deben tapar los daños más graves que podrían hundirlo, controlar situaciones críticas como incendios y proteger a las personas, antes de atender problemas menores. Del mismo modo, el equipo debe priorizar las acciones que reduzcan el impacto inmediato.

---

### Contención

La contención es el proceso de evitar que un ataque continúe y cause más daños o inutilice el sistema.

El objetivo principal es aislar el incidente y limitar su propagación. Para ello, el equipo puede tomar distintas decisiones, como:

* Desconectar dispositivos afectados de la red
* Apagar sistemas comprometidos
* Deshabilitar servicios o funcionalidades vulnerables
* Segmentar partes de la red

Estas decisiones dependen del tipo de ataque y de las políticas de seguridad de la organización. Un buen plan de respuesta a incidentes ya debería definir cómo actuar en estos casos y quién es responsable de cada acción.

---

### Estrategia de Contención

La estrategia de contención busca evitar que el incidente consuma más recursos o incremente el daño.

Algunas preguntas clave que debe responder el equipo son:

* ¿Se puede aislar el problema?
* ¿Qué sistemas o redes deben desconectarse?
* ¿Qué impacto tendrá la contención en la operación del negocio?

El objetivo es encontrar un equilibrio entre detener el ataque y mantener la continuidad operativa.

---

### Análisis Forense

Durante la contención, es fundamental preservar evidencia del incidente, especialmente si puede derivar en acciones legales.

Para ello, se deben seguir buenas prácticas de análisis forense digital:

* Realizar una copia o imagen del sistema afectado antes de modificarlo
* Trabajar siempre sobre la copia, no sobre el sistema original
* Recopilar evidencia en un entorno controlado
* Mantener la cadena de custodia, documentando cada paso realizado

Esto garantiza que la evidencia sea válida y utilizable en investigaciones legales.

---

### Erradicación

La erradicación consiste en eliminar completamente la amenaza de todos los sistemas afectados.

Algunas acciones comunes incluyen:

* Eliminación de malware
* Desactivación de cuentas comprometidas
* Aplicación de parches de seguridad
* Reinstalación o reimaginado de sistemas
* Actualización de software vulnerable

Durante este proceso, es fundamental identificar todos los equipos comprometidos para evitar reinfecciones.

---

### Consideraciones Clave

Para asegurar una erradicación efectiva, el equipo debe evaluar:

* ¿Es posible eliminar completamente la amenaza?
* ¿Se eliminaron todos los rastros del ataque?
* ¿Se pueden reforzar los sistemas para prevenir futuros incidentes?

En algunos casos, la erradicación puede combinarse con la fase de recuperación, priorizando los sistemas más críticos para la organización.

Además, es importante tener en cuenta que, si un atacante logró comprometer un sistema, es probable que intente hacerlo nuevamente. Por ello, fortalecer la seguridad tras el incidente es esencial.

---

Esta fase permite estabilizar el entorno afectado, eliminar la amenaza y sentar las bases para una recuperación segura y controlada del sistema.

## Actividad: Aplicación de la Fase 3 (Contención y Erradicación)

### Antecedentes

El equipo de respuesta a incidentes de HealthGuard Medical Services puso en marcha su plan de respuesta y comenzó a aislar los sistemas afectados para evitar la propagación del ataque. En primer lugar, desconectó de la red los sistemas comprometidos. Luego, se aseguró de que ningún otro sistema pudiera comunicarse con ellos, evitando así una posible expansión del incidente.

Posteriormente, el equipo investigó la amenaza y descubrió la existencia de un parche de seguridad. A continuación, procedió a eliminar el código malicioso de los sistemas afectados, actualizar los sistemas vulnerables y aplicar medidas de seguridad adicionales para prevenir futuros ataques.

---

### Análisis y Opinión

En mi opinión, el equipo de respuesta a incidentes actuó de manera correcta y alineada con las buenas prácticas de la fase 3 del manejo de incidentes.

En primer lugar, la acción de aislar los sistemas afectados fue clave para contener el ataque. La desconexión de la red y la restricción de comunicaciones evitaron la propagación lateral, lo cual es fundamental en este tipo de situaciones.

Además, el análisis de la amenaza permitió identificar una vulnerabilidad existente y su correspondiente parche, lo que demuestra una correcta investigación técnica. La eliminación del malware y la actualización de los sistemas reflejan una adecuada ejecución de la fase de erradicación.

Otro aspecto positivo es la implementación de medidas de seguridad adicionales, lo que indica un enfoque preventivo para reducir la probabilidad de futuros incidentes.

Como punto de mejora, no se menciona explícitamente la realización de un análisis forense ni la preservación de evidencia, lo cual sería importante en caso de una investigación legal o para un análisis más profundo del incidente.

---

### Conclusión

El equipo aplicó correctamente las etapas de contención y erradicación, logrando mitigar el incidente de forma efectiva. Además, no solo resolvió el problema actual, sino que también fortaleció la seguridad del entorno, lo cual es fundamental para la resiliencia de la organización frente a futuras amenazas.

## Fase 4: Recuperación y Actividades Posteriores al Incidente

Una vez que el equipo ha contenido el ataque y eliminado la amenaza, comienza la fase de recuperación. En esta etapa, el objetivo principal es restaurar los sistemas afectados a su funcionamiento normal, asegurando que sean seguros y estén libres de vulnerabilidades.

La recuperación no solo implica volver a poner en marcha los sistemas, sino también garantizar que el incidente no vuelva a ocurrir.

---

### Recuperación

Durante esta fase, los administradores trabajan para restaurar completamente la operación de los sistemas y verificar su correcto funcionamiento.

Algunas de las acciones más comunes incluyen:

* Restaurar sistemas a partir de copias de seguridad limpias
* Reconstruir sistemas comprometidos desde cero
* Reemplazar archivos afectados por versiones seguras
* Aplicar parches de seguridad
* Cambiar credenciales (contraseñas)
* Reforzar la seguridad de la red (firewalls, ACLs, etc.)

Además, es habitual implementar niveles más altos de monitoreo y registro (logging) para detectar posibles ataques futuros de manera más rápida.

El proceso de recuperación puede requerir pruebas exhaustivas y monitoreo continuo durante semanas o incluso meses, dependiendo de la gravedad del incidente. En algunos casos, puede ser necesario restaurar el sistema a un punto anterior al ataque, lo que podría generar impacto operativo en la organización.

---

### Actividades Posteriores al Incidente

Una vez finalizada la recuperación, es fundamental realizar actividades de mejora continua. Estas acciones permiten fortalecer la seguridad y optimizar la respuesta ante futuros incidentes.

---

#### Lecciones Aprendidas

Se debe organizar una reunión con todas las partes involucradas para analizar lo ocurrido y detectar oportunidades de mejora.

Algunas preguntas clave son:

* ¿Se siguieron los procedimientos establecidos?
* ¿Funcionaron correctamente o deben mejorarse?
* ¿Qué información faltó durante el incidente?
* ¿Qué acciones dificultaron la recuperación?
* ¿Qué se haría diferente en un caso similar?
* ¿Qué recursos adicionales se necesitan?

---

#### Informe de Respuesta a Incidentes

Es fundamental elaborar un informe completo que incluya:

* Línea de tiempo del incidente
* Impacto técnico y financiero
* Sistemas afectados
* Acciones realizadas
* Vulnerabilidades detectadas
* Recomendaciones de mejora

Este documento sirve como referencia futura y puede ser clave en procesos legales.

---

#### Retención de Evidencia

La organización debe contar con políticas claras para la conservación de evidencia, ya que el incidente podría derivar en acciones legales.

Es importante:

* Almacenar correctamente la evidencia digital
* Mantener la cadena de custodia
* Garantizar la integridad de los datos a lo largo del tiempo

---

#### Mejora Continua

Los datos recopilados durante el incidente (tiempos de respuesta, impacto, recuperación, etc.) deben analizarse para identificar patrones y mejorar los procesos.

Esto permite:

* Optimizar la detección de incidentes
* Reducir tiempos de respuesta
* Fortalecer la seguridad general
* Anticiparse a futuras amenazas

---

### Conclusión

La fase de recuperación no solo busca restablecer los sistemas, sino también aprender del incidente. A través del análisis, la documentación y la mejora continua, la organización puede volverse más resiliente y estar mejor preparada para enfrentar futuros ataques.

## Actividad: Aplicación de la Fase 4 (Recuperación)

### Antecedentes

En la fase de recuperación, el equipo de TI de HealthGuard Medical Services trabajó para restaurar los sistemas afectados y verificó que el parche se aplicara correctamente en todos los sistemas necesarios. Además, realizó un análisis del incidente con el objetivo de identificar otras posibles vulnerabilidades y aplicó medidas de seguridad adicionales para prevenir futuros ataques.

Por otro lado, la organización comunicó el incidente a todos los pacientes afectados y les ofreció servicios de protección de identidad como medida preventiva. Asimismo, revisó su plan de respuesta a incidentes y realizó mejoras para fortalecer su preparación ante futuros incidentes de ciberseguridad.

---

### Análisis y Opinión

En mi opinión, el equipo de TI actuó de manera muy adecuada y alineada con las mejores prácticas de la fase de recuperación dentro de un marco de respuesta a incidentes.

En primer lugar, la restauración de los sistemas y la verificación de la correcta aplicación del parche demuestran que el equipo priorizó asegurar que la vulnerabilidad explotada quedara completamente mitigada. Esto es fundamental para evitar una reinfección o un nuevo ataque similar.

Además, el análisis posterior del incidente para identificar otras posibles debilidades evidencia un enfoque proactivo orientado a la mejora continua de la seguridad.

Otro punto muy importante es la comunicación con los pacientes afectados. Esto refleja transparencia y responsabilidad por parte de la organización, además de ayudar a reducir el impacto en los usuarios. La oferta de servicios de protección de identidad también es una medida adecuada para mitigar posibles consecuencias del incidente.

Por último, la revisión y mejora del plan de respuesta a incidentes demuestra madurez organizacional, ya que permite aprender del incidente y optimizar los procesos para el futuro.

Como posible mejora, se podría reforzar aún más el monitoreo continuo posterior a la recuperación para detectar comportamientos anómalos en etapas tempranas.

---

### Conclusión

El equipo de HealthGuard Medical Services ejecutó correctamente la fase de recuperación, no solo restaurando los sistemas, sino también fortaleciendo la seguridad, mejorando sus procesos internos y protegiendo a los usuarios afectados. Esto demuestra una respuesta integral y madura frente a incidentes de ciberseguridad.

* Análisis del caso HealthGuard Medical Services con respecto a los avisos a los clientes.

En la fase de recuperación, el equipo de TI de HealthGuard Medical Services llevó a cabo acciones fundamentales para restablecer el funcionamiento normal de los sistemas afectados tras el incidente de ciberseguridad. En primer lugar, se encargaron de restaurar los sistemas comprometidos, asegurándose de que el parche de seguridad correspondiente fuera aplicado correctamente en todos los dispositivos vulnerables. Esta acción es clave para evitar que la misma vulnerabilidad pueda ser explotada nuevamente.

Además, el equipo realizó un análisis exhaustivo del incidente con el objetivo de identificar posibles debilidades adicionales en la infraestructura tecnológica. A partir de este análisis, se implementaron medidas de seguridad complementarias para fortalecer la protección de los sistemas y reducir el riesgo de futuros ataques.

* Un aspecto destacable de esta fase fue la decisión de la organización de comunicar el incidente a los pacientes afectados. Si bien esta acción puede generar un impacto negativo en la reputación a corto plazo, resulta fundamental desde el punto de vista legal, ético y de confianza. Informar a los usuarios permite que tomen medidas preventivas, como el monitoreo de su identidad o el cambio de credenciales, reduciendo así el posible impacto del incidente. Asimismo, la empresa ofreció servicios de protección de identidad como medida adicional de mitigación.

Por otro lado, HealthGuard revisó su plan de respuesta a incidentes e introdujo mejoras basadas en lo ocurrido. Este proceso de retroalimentación es esencial, ya que permite a la organización aprender del incidente y estar mejor preparada ante futuros eventos de ciberseguridad.

En conclusión, la fase de recuperación no solo implica restaurar sistemas, sino también fortalecer la seguridad, proteger a los usuarios afectados y mejorar continuamente los procesos internos. La transparencia en la comunicación y la implementación de medidas correctivas adecuadas son factores clave para mantener la confianza y garantizar la resiliencia de la organización frente a futuros incidentes.

**Estudio de caso: SilverHedge Financial – Identificación de las fases de respuesta a incidentes**

En el caso de SilverHedge Financial, se pueden identificar claramente las cuatro fases del proceso de respuesta a incidentes: preparación, detección y análisis, contención y erradicación, y recuperación.

**1. Fase de Preparación**
SilverHedge Financial demostró estar preparada para enfrentar incidentes de seguridad al implementar diversas medidas preventivas. Entre ellas, se destacan el uso de firewalls, sistemas de detección de intrusiones (IDS) y controles de acceso. Estas herramientas permiten reducir la probabilidad de ataques y facilitan la detección temprana de actividades sospechosas.
Además, la empresa contaba con un plan de respuesta a incidentes previamente definido, lo que permitió actuar de manera rápida y organizada ante la detección del problema.

**2. Fase de Detección y Análisis**
El equipo de seguridad detectó actividad inusual en la red, como múltiples intentos fallidos de inicio de sesión, bajo rendimiento del sistema, comportamiento extraño de archivos y tráfico de red sospechoso.
A partir de estas señales, se activó el plan de respuesta a incidentes y se inició una investigación. El análisis permitió identificar que el origen del incidente fue un correo electrónico de phishing que engañó a un empleado, quien descargó malware en su equipo. Este malware se propagó por la red y permitió el acceso no autorizado a datos confidenciales.

**3. Fase de Contención y Erradicación**
Una vez identificado el incidente, el equipo actuó rápidamente para contener la amenaza. Se aislaron y desconectaron de la red las máquinas infectadas, evitando así una mayor propagación del malware.
Posteriormente, se procedió a la eliminación completa del software malicioso de los sistemas afectados. Estas acciones fueron clave para detener el ataque y evitar daños adicionales a la infraestructura y a los datos de la organización.

**4. Fase de Recuperación**
En esta etapa, SilverHedge Financial trabajó para restaurar el funcionamiento normal de sus sistemas. Se recuperaron los datos alterados utilizando copias de seguridad y se verificó la instalación de actualizaciones y parches de seguridad en todos los sistemas.
Asimismo, se realizó una revisión exhaustiva del incidente para identificar posibles mejoras en los procesos y controles de seguridad.
Dado que los datos de los clientes fueron comprometidos, la empresa tomó la decisión de informar a los afectados, cumpliendo con sus responsabilidades legales y éticas. También brindó garantías de que se implementaron medidas adecuadas para proteger la información en el futuro.

**Conclusión**
El caso de SilverHedge Financial demuestra la importancia de contar con un plan de respuesta a incidentes bien definido y de aplicar correctamente cada una de sus fases. La rápida detección, la efectiva contención del ataque y la adecuada recuperación permitieron minimizar el impacto del incidente y fortalecer la seguridad de la organización frente a futuras amenazas.

## Resumen y perspectivas

### Resumen de la lección

En esta lección, aprendiste sobre el **proceso de respuesta a incidentes**.

#### Puntos clave aprendidos

- Las **cuatro fases** de la respuesta a incidentes y los pasos dentro de cada una:
  - **Fase 1: Preparación**
  - **Fase 2: Detección y análisis**
  - **Fase 3: Contención y erradicación**
  - **Fase 4: Recuperación**

- Seguiste un **ejemplo** en cada fase del proceso de IR (HealthGuard Medical Services)
- Aplicaste tus conocimientos a un **estudio de caso**

---

### Resumen de las 4 fases

| Fase | Descripción |
|------|-------------|
| **1. Preparación** | Establecer el plan, el equipo, las herramientas y los procedimientos antes de que ocurra un incidente |
| **2. Detección y análisis** | Identificar que ha ocurrido un incidente, analizar alertas y determinar el alcance |
| **3. Contención y erradicación** | Detener la propagación del ataque y eliminar la amenaza de los sistemas afectados |
| **4. Recuperación** | Restaurar los sistemas a su estado normal y asegurar que la amenaza haya sido completamente eliminada |

---

### Perspectivas

**En la siguiente lección**, aprenderás a **formular un plan de respuesta a incidentes**.

Explorarás:
- Qué información necesita **recopilar** un equipo de IR
- Cómo puede usarla para **planear** qué hacer cuando ocurre un ataque

### Acerca de esta lección: Planeación de la respuesta a incidentes

Los profesionales de la ciberseguridad a menudo dicen que no se trata de **"si"** sino de **"cuándo"** ocurrirá un ataque.

Invariablemente, un ataque cibernético ocurre **cuando menos lo esperas**:
- Cerca del final de una semana laboral ocupada
- En medio de un evento planeado de migración del sistema
- A altas horas de la noche después de que todos se fueron a casa

> Una organización debe contar con un **plan de respuesta a incidentes (IR)** para que, cuando se produzca el ataque, el equipo de IR pueda **detenerlo y mitigarlo rápidamente**.

#### En esta lección aprenderás

- Cómo los administradores crean un **plan de IR** que funcione para su organización
- **Quién trabaja** en el equipo de IR y qué otros equipos pueden ayudar con la respuesta a incidentes
- **Inquietudes** que debes abordar relacionadas con cada fase de IR
- **Planes básicos** que deben incluirse sobre cómo **mantener el plan** en sí

### El plan de respuesta a incidentes

#### ¿Por qué es necesario un plan?

Los primeros momentos frenéticos de la identificación de un incidente pueden causar **pánico**, especialmente sin una guía clara.

> Tomar buenas decisiones y recordar todo lo que debe abarcar la respuesta puede ser un reto incluso para el mejor equipo de respuesta a incidentes mientras se produce un ataque.

Un **plan de respuesta a incidentes (IRP)** actúa como una **hoja de ruta** a seguir, ahorrando tiempo valioso y garantizando que el equipo centre sus esfuerzos adecuadamente.

#### ¿Qué es un plan de respuesta a incidentes (IRP)?

Un **IRP** detalla:
- Las **acciones necesarias** en caso de un ciberataque
- El **orden** en que deben llevarse a cabo
- Los **miembros del equipo** que deben realizarlas

---

### Pautas para crear un IRP efectivo

#### 1. Observar el panorama general

| Aspecto | Descripción |
|---------|-------------|
| **Considerar las 4 fases** | Preparación, detección y análisis, contención y erradicación, recuperación |
| **Nivel superior primero** | Mantener el desarrollo del IRP a un nivel alto al principio, agregar detalles a medida que se refina |
| **Adaptar a la organización** | Ningún IRP se adapta a todas las organizaciones; cada equipo debe adaptarlo a sus operaciones únicas |

---

#### 2. Planear el plan (estructura del IRP)

Todo IRP debe tener una **política** que establezca las partes importantes de forma general:

| Elemento | Descripción |
|----------|-------------|
| **Estructura del equipo de IR** | Cómo está organizado el equipo |
| **Funciones y responsabilidades** | Qué hace cada miembro |
| **Medios, herramientas y recursos** | Qué se usará para identificar y recuperar datos |
| **Pruebas del plan** | Cómo debe probarse el plan y quién es responsable |
| **Plan de acción** | Cómo llevar a cabo el IRP de principio a fin |

---

#### 3. Mantener un manual físico del IRP

| Problema | Solución |
|----------|----------|
| Un ataque puede **interrumpir el acceso** a sistemas clave | Mantener **versiones físicas y digitales** del IRP |
| El IRP en línea podría ser **inaccesible** cuando más se necesita | Tener una copia física disponible |

> Mantener el IRP **solo en línea** es un riesgo. Un ataque podría dejar el sistema inaccesible justo cuando más se necesita el plan.

---

#### 4. Eliminar las dependencias de miembros clave

| Problema | Solución |
|----------|----------|
| ¿Qué pasa si un miembro clave **no está disponible** cuando ocurre un ataque? | Crear el IRP para que **cualquier persona** de la organización pueda usarlo |
| La jerga técnica puede ser confusa | Escribir los pasos básicos en **lenguaje claro** con jerga técnica limitada |
| Se necesita expertise técnica | El IRP puede contener contactos adecuados para gestionar aspectos técnicos |

---

#### 5. Documentar el mantenimiento del IRP

El IRP solo es efectivo si se **mantiene actualizado**.

| Acción | Responsabilidad |
|--------|----------------|
| Documentar cambios futuros | ¿Quién lo hará? |
| Copiar cambios a diferentes versiones | ¿Quién lo hará? |
| Notificar a personas afectadas | ¿Quién lo hará? |
| Indicar dónde encontrar el IRP en emergencias | Documentar la ubicación |

---

### Resumen de pautas para un IRP efectivo

| Pauta | Clave |
|-------|-------|
| **Observar el panorama general** | Considerar las 4 fases, adaptar a la organización |
| **Planear el plan** | Definir política, estructura, roles, recursos |
| **Manual físico** | Tener copia física disponible (no solo digital) |
| **Sin dependencias críticas** | Cualquiera puede usar el plan, lenguaje claro |
| **Mantenimiento documentado** | Actualizar, notificar, documentar ubicación |

### El equipo de respuesta a incidentes

#### ¿Por qué es importante el equipo?

Los primeros momentos frenéticos de la identificación de un incidente pueden causar **pánico**. Tomar buenas decisiones y recordar todo lo que debe abarcar la respuesta puede ser un reto incluso para el mejor equipo.

> Un **plan de respuesta a incidentes (IRP)** actúa como una hoja de ruta, pero el **equipo** es quien lo ejecuta.

---

### Elementos clave del equipo de respuesta a incidentes

#### 1. Jefe de equipo

| Responsabilidad | Descripción |
|-----------------|-------------|
| **Responsable único** | Una sola persona es responsable de llevar a cabo el IRP |
| **Punto de contacto** | Actúa como enlace con otros equipos y organizaciones |
| **Recursos y personal** | Garantiza que el equipo tenga el personal, recursos y habilidades necesarios |
| **Líderes alternativos** | El plan debe designar alternativas si el jefe habitual no está disponible |

**Habilidades necesarias:**
- Sólidos conocimientos técnicos
- Excelentes habilidades de comunicación (con diferentes audiencias)
- Responsabilidad final de que el equipo realice correctamente las actividades de IR

---

#### 2. Líderes técnicos y de incidentes

| Rol | Descripción |
|-----|-------------|
| **Líder técnico** | Persona con sólidas habilidades técnicas y experiencia en IR que **dirige el trabajo técnico** del equipo y asume la responsabilidad final del mismo |
| **Líder de incidentes** (equipos grandes) | Punto de contacto principal para un incidente específico. **Coordina** actividades, recopila información, proporciona actualizaciones a otros grupos y garantiza que se satisfagan las necesidades del equipo |

> En equipos grandes, el líder de incidentes puede **no manejar incidentes directamente**, sino coordinar al equipo.

---

#### 3. Habilidades de los miembros del equipo

| Habilidad | ¿Quién la necesita? |
|-----------|---------------------|
| **Buenas habilidades técnicas** | Todos los miembros |
| **Habilidades de resolución de problemas** | Todos los miembros |
| **Habilidades de pensamiento crítico** | Todos los miembros |
| **Competencias técnicas específicas** | Al menos un miembro por cada área clave |

**Áreas de especialización necesarias:**

| Especialidad | Descripción |
|--------------|-------------|
| **Administración de sistemas** | SO y aplicaciones comúnmente atacadas |
| **Administración de redes** | Infraestructura de red |
| **Programación** | Análisis de código, automatización |
| **Soporte técnico** | Asistencia a usuarios y sistemas |
| **Detección de intrusiones** | IDS/IPS, monitoreo |
| **Análisis de malware** | Estudio de software malicioso |
| **Análisis forense** | Investigación de evidencia digital |

---

#### 4. Modelos de dotación de personal

| Modelo | Descripción | Cuándo se usa |
|--------|-------------|---------------|
| **Interno** | Solo empleados de la organización | Empresas grandes con presupuesto y personal calificado |
| **Subcontratado** | Equipo externo especializado en IR | Empresas sin personal interno de seguridad |
| **Híbrido** | Equipo interno + especialistas externos | Empresas que tienen algo de personal pero necesitan expertise adicional |

**Factores para elegir un modelo:**
- **Tamaño de la empresa**
- **Presupuesto disponible**
- **Habilidades técnicas** de los empleados actuales

---

### Resumen del equipo de IR
┌─────────────────────────────────────────────────────────────────────────────┐
│ EQUIPO DE RESPUESTA A INCIDENTES │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌─────────────────┐ │
│ │ JEFE DE │ │
│ │ EQUIPO │ │
│ └────────┬────────┘ │
│ │ │
│ ┌───────────────────┼───────────────────┐ │
│ │ │ │ │
│ ▼ ▼ ▼ │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ │
│ │ LÍDER TÉCNICO │ │ LÍDER TÉCNICO │ │ LÍDER TÉCNICO │ │
│ │ (Redes) │ │ (Sistemas) │ │ (Malware) │ │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘ │
│ │
│ Modelos: │
│ • Interno (solo empleados) │
│ • Subcontratado (solo externos) │
│ • Híbrido (internos + externos) │
│ │
└─────────────────────────────────────────────────────────────────────────────┘


---

### Habilidades clave del equipo de IR

| Habilidad | ¿Por qué es importante? |
|-----------|------------------------|
| **Conocimiento técnico** | Para entender y combatir las amenazas |
| **Resolución de problemas** | Para encontrar soluciones bajo presión |
| **Pensamiento crítico** | Para evaluar situaciones y tomar decisiones |
| **Comunicación** | Para coordinar con otros equipos y explicar situaciones |

### Actividad: Identificar los roles del equipo de respuesta a incidentes

#### Preguntas y respuestas

| Pregunta | Respuesta |
|----------|-----------|
| ¿Quién lleva a cabo el plan de respuesta a incidentes? | **Equipo de respuesta a incidentes** |
| ¿Quién sirve como punto de contacto para el plan de respuesta a incidentes? | **Jefe de equipo** |
| ¿Quién actúa como enlace con otros equipos y organizaciones y se asegura de que el equipo tenga el personal, los recursos y las habilidades necesarios? | **Jefe de equipo** |
| ¿Quién dirige el trabajo técnico del equipo de respuesta a incidentes y asume la responsabilidad final por ello? | **Líder técnico** |

---

### Resumen de roles

| Rol | Responsabilidades clave |
|-----|------------------------|
| **Equipo de respuesta a incidentes** | Ejecuta el plan de respuesta a incidentes |
| **Jefe de equipo** | - Punto de contacto principal<br>- Enlace con otros equipos y organizaciones<br>- Garantiza personal, recursos y habilidades necesarias |
| **Líder técnico** | - Dirige el trabajo técnico<br>- Asume la responsabilidad final del trabajo técnico |

---

### Estructura del equipo de IR
┌─────────────────────────────────────────────────────────────────────────────┐
│ EQUIPO DE RESPUESTA A INCIDENTES │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌─────────────────┐ │
│ │ JEFE DE │ │
│ │ EQUIPO │ │
│ │ │ │
│ │ • Punto de │ │
│ │ contacto │ │
│ │ • Enlace con │ │
│ │ otros equipos │ │
│ └────────┬────────┘ │
│ │ │
│ ▼ │
│ ┌─────────────────┐ │
│ │ LÍDER TÉCNICO │ │
│ │ │ │
│ │ • Dirige el │ │
│ │ trabajo │ │
│ │ técnico │ │
│ └────────┬────────┘ │
│ │ │
│ ┌───────────────────┼───────────────────┐ │
│ │ │ │ │
│ ▼ ▼ ▼ │
│ ┌─────────────────┐ ┌─────────────────┐ ┌─────────────────┐ │
│ │ MIEMBRO │ │ MIEMBRO │ │ MIEMBRO │ │
│ │ TÉCNICO │ │ TÉCNICO │ │ TÉCNICO │ │
│ │ (Redes) │ │ (Sistemas) │ │ (Malware) │ │
│ └─────────────────┘ └─────────────────┘ └─────────────────┘ │
│ │
│ Todo el EQUIPO DE RESPUESTA A INCIDENTES ejecuta el plan │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

### Otros participantes en la respuesta a incidentes

Cada equipo de respuesta a incidentes depende de la **experiencia, el juicio y las habilidades de otros**. El IRP debe asociarse con otros grupos relevantes de la organización para que:

- Los miembros del equipo puedan entender cómo pueden ayudar
- Los otros grupos sepan cuándo contactarlos

> El equipo de IR deberá **analizar el plan con cada uno de estos grupos** antes de que ocurra un incidente.

---

### Participantes clave y sus responsabilidades

| Participante | Responsabilidades |
|--------------|-------------------|
| **Gestión** | - Promulga la política de respuesta a incidentes<br>- Establece estándares para personal y presupuesto<br>- Coordina la respuesta a incidentes<br>- Minimiza daños<br>- Notifica a agencias reguladoras<br>- Planifica la continuidad del negocio |
| **Soporte de TI** | - Expertos técnicos (administradores de sistemas y redes)<br>- Mejor entendimiento de la tecnología diaria<br>- Asistencia a usuarios confundidos y preocupados<br>- Mantiene a los usuarios informados y tranquilos |
| **Departamento jurídico** | - Revisa planes, políticas y procedimientos de IR<br>- Garantiza cumplimiento de leyes y regulaciones<br>- Asesora sobre consecuencias legales<br>- Ayuda con mediaciones o enjuiciamiento de sospechosos |
| **Asuntos públicos** | - Gestiona la comunicación con el público y medios<br>- Trabaja eficazmente si se mantiene en estrecho contacto con el equipo de IR |
| **Recursos humanos** | - Ayuda con procedimientos disciplinarios si un empleado causó el incidente<br>- Asiste en etapas posteriores de recuperación |
| **Gestión de instalaciones** | - Investiga violaciones de seguridad física<br>- Investiga ataques lógicos y físicos coordinados<br>- Proporciona acceso a instalaciones (ej. adquirir una workstation comprometida) |

---

### ¿Por qué es importante involucrar a estos grupos?

| Razón | Explicación |
|-------|-------------|
| **Preparación** | Todos deben saber su rol antes de que ocurra un incidente |
| **Respuesta rápida** | No se pierde tiempo decidiendo quién debe hacer qué |
| **Cumplimiento** | Aspectos legales y regulatorios deben ser manejados correctamente |
| **Comunicación** | Los afectados (usuarios, público, medios) reciben información adecuada |
| **Continuidad** | El negocio puede seguir operando durante y después del incidente |

---

### Resumen visual
┌─────────────────────────────────────────────────────────────────────────────┐
│ OTROS PARTICIPANTES EN IR │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ │
│ │ GESTIÓN │ │ SOPORTE │ │ JURÍDICO │ │
│ │ │ │ DE TI │ │ │ │
│ │ • Política │ │ • Expertos │ │ • Legal │ │
│ │ • Presupuesto│ │ técnicos │ │ • Regulaciones│ │
│ │ • Continuidad│ │ • Asistencia │ │ │ │
│ └──────────────┘ └──────────────┘ └──────────────┘ │
│ │
│ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ │
│ │ ASUNTOS │ │ RR.HH. │ │ INSTALACIONES│ │
│ │ PÚBLICOS │ │ │ │ │ │
│ │ │ │ │ │ │ │
│ │ • Medios │ │ • Disciplina │ │ • Seguridad │ │
│ │ • Comunicación│ │ empleados │ │ física │ │
│ │ externa │ │ • Recuperación│ │ • Acceso │ │
│ └──────────────┘ └──────────────┘ └──────────────┘ │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

> **Importante:** Todos estos grupos deben ser **consultados y entrenados** antes de que ocurra un incidente, para que cuando ocurra, sepan exactamente qué hacer y cómo coordinar con el equipo de IR.

### Planeación de las fases de respuesta a incidentes

El **IRP** debe contener instrucciones para **cada fase** de la respuesta a un incidente:

| Fase | Nombre |
|------|--------|
| 1 | Preparación |
| 2 | Detección y análisis |
| 3 | Contención y erradicación |
| 4 | Recuperación |

#### Elementos que debe incluir el IRP para cada fase

| Elemento | Descripción |
|----------|-------------|
| **Indicadores** | Qué señales buscar |
| **Acciones** | Qué acciones tomar |
| **Responsables** | Qué miembros del equipo realizan cada acción |
| **Resultado medible** | Cómo saber cuándo se completaron todas las tareas |

> Cada fase tiene preocupaciones y requisitos particulares. Las siguientes pautas se aplican a la mayoría de las organizaciones.

---

### Fase 1: Preparación

#### Planificación

| Actividad | Descripción |
|-----------|-------------|
| **Evaluación general de seguridad** | Analizar toda la organización |
| **Identificar preocupaciones exclusivas** | Cada sector tiene riesgos particulares (ej. bancos → información financiera y personal) |
| **Revisión de superficies de ataque** | Identificar todos los puntos donde un atacante puede obtener acceso (vulnerabilidades de software, conexiones de red abiertas) |
| **Riesgos de geolocalización** | Ej. centros de datos en zonas de huracanes o terremotos |

#### Analogía: Sala de emergencias de un hospital

> *Antes de que cualquier paciente llegue, el personal debe considerar qué problemas podrían presentarse y hacer un plan. Se aseguran de tener el equipo necesario para admitir, diagnosticar, estabilizar y tratar. El liderazgo garantiza que el personal esté capacitado y listo.*

---

### Fase 2: Detección y análisis

#### Planificación

| Actividad | Descripción |
|-----------|-------------|
| **Adquirir herramientas de detección** | IDS, IPS, SIEM, etc. (no hay solución única, se personaliza según necesidades) |
| **Implementar herramientas de registro** | Registrar continuamente la actividad del sistema para revisión manual y análisis |
| **Analizar registros** | Descubrir qué pudo haber visto, modificado o extraído el atacante |

#### Analogía: Sala de emergencias de un hospital

> *Cuando los pacientes llegan, el personal tiene un plan para clasificarlos y descubrir sus lesiones. Piden información sobre síntomas, emplean equipos especiales para recopilar más información y determinar la naturaleza de la crisis.*

---

### Fase 3: Contención y erradicación

#### Planificación

| Actividad | Descripción |
|-----------|-------------|
| **Contener la amenaza** | Detener la propagación, neutralizar el ataque |
| **Evaluar el daño** | Acceso no autorizado, malware, destrucción de recursos, extracción de datos, manipulación de cuentas |
| **Erradicar** | Eliminar malware, restaurar información dañada, restablecer cuentas comprometidas |
| **Probar** | Verificar que todo vuelva a funcionar correctamente |

#### Analogía: Sala de emergencias de un hospital

> *El equipo estabiliza la lesión para que no empeore. Luego repara cualquier daño inmediato y prepara la lesión para que comience el proceso de curación (ej. limpiar, coser y aplicar yeso a una pierna fracturada).*

---

### Fase 4: Recuperación

#### Planificación

| Acción | Descripción |
|--------|-------------|
| **Restaurar particiones** | A partir de copias de seguridad |
| **Intercambiar archivos** | Reemplazar archivos afectados por archivos limpios |
| **Actualizar contraseñas** | Restablecer cuentas comprometidas |
| **Parchear y endurecer sistemas** | Corregir vulnerabilidades explotadas |

#### Otras consideraciones en la recuperación

| Consideración | Descripción |
|---------------|-------------|
| **Preservar conocimiento** | Aprender cómo ocurrió el ataque para mejorar preparativos futuros |
| **Informar partes interesadas** | Con ayuda de relaciones públicas |
| **Notificar afectados** | Proveer instrucciones para corrección |
| **Aspectos legales** | Recopilar y almacenar evidencia adecuadamente (con ayuda legal) |

#### Analogía: Sala de emergencias de un hospital

> *Cuando el paciente es dado de alta, el equipo tiene políticas para proporcionar recursos que ayuden a curar y restaurar su salud: medicamentos, cita de seguimiento, derivación a fisioterapeuta.*

---

### Resumen: Las 4 fases con analogía del hospital

| Fase | Acción en IR | Analogía en el hospital |
|------|--------------|------------------------|
| **1. Preparación** | Evaluar riesgos, planificar, tener herramientas | Equipo listo, materiales preparados |
| **2. Detección y análisis** | Monitorear, detectar, analizar | Clasificar, diagnosticar, preguntar síntomas |
| **3. Contención y erradicación** | Contener, eliminar amenaza | Estabilizar, tratar, aplicar yeso |
| **4. Recuperación** | Restaurar, comunicar, aprender | Medicación, seguimiento, rehabilitación |

---

### Diagrama de las 4 fases
┌─────────────────────────────────────────────────────────────────────────────┐
│ LAS 4 FASES DE RESPUESTA A INCIDENTES │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌──────────────┐ ┌──────────────┐ ┌──────────────┐ ┌───────────┐ │
│ │ 1. │ │ 2. │ │ 3. │ │ 4. │ │
│ │ Preparación │───▶│ Detección │───▶│ Contención │───▶│Recuperación│ │
│ │ │ │ y análisis │ │ y erradicación│ │ │ │
│ └──────────────┘ └──────────────┘ └──────────────┘ └───────────┘ │
│ │
│ Hospital: Hospital: Hospital: Hospital: │
│ Equipo listo Clasificar Estabilizar Rehabilitación │
│ Material listo Diagnosticar Tratar Seguimiento │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

Ejemplos de trabajos reales en Respuesta a Incidentes
Puesto y Empresa	Funciones Principales (¿Qué hacen?)	Requisitos Clave (¿Qué piden?)
Tech_Analista de Ciberseguridad DFIR (Telefónica, México) 	Investigar incidentes, hacer análisis forense en endpoints, determinar causa raíz, elaborar informes técnicos.	2.5-5 años de exp. en DFIR, manejo de SIEM/EDR (Splunk, QRadar, CrowdStrike), herramientas forenses (FTK, Autopsy), inglés valorable.
Tech_Analista forense y respuesta a incidentes DFIR N3 (Telefónica, España) 	Conducir investigaciones forenses, coordinar equipos, analizar malware (en sandbox), preparar informes detallados.	+3 años en ciberseguridad (+1 en IR/forense), conocimiento de TTPs de atacantes, experiencia en cloud (AWS, Azure), inglés B2 obligatorio.
Cybersecurity Incident Response Analyst (Endava, remoto) 	Responder a incidentes, analizar alertas con EDR/SIEM, hacer análisis de malware básico, participar en revisiones post-incidente.	+3 años en ciberseguridad (+2 en SOC/IR), experiencia práctica con SIEM y EDR, conocimiento de MITRE ATT&CK, capacidad para trabajar bajo presión.
Tech_Analista N3 CSIRT (Telefónica, España) 	Diseñar planes de respuesta, gestionar incidentes complejos, crear "playbooks" y casos de uso para SIEM, generar informes forenses.	+5 años en roles de seguridad, experiencia en banca, conocimiento de marcos (NIST, ISO 27001), manejo de SIEM/EDR/XDR, scripting (Python, PowerShell), inglés B2.
Análisis y conclusiones (Para tu actividad)
Después de revisar estas ofertas, noté varios patrones muy claros.

1. Patrones en los requisitos (¿Qué se repite en todos lados?)
Experiencia base: La mayoría pide entre 2 y 5 años de experiencia en roles de seguridad. Para los perfiles senior, puede subir a 5-10 años. La entrada al campo IR no es de nivel inicial; suele ser un rol avanzado al que se llega tras pasar por el SOC (analista de seguridad) .

Herramientas SIEM y EDR: Es fundamental saber manejar herramientas de monitoreo (SIEM) y de protección de endpoints (EDR). Ejemplos que se repiten: Splunk, QRadar, CrowdStrike, SentinelOne, Elastic .

Conocimiento de frameworks: Casi todos piden conocer marcos como MITRE ATT&CK, NIST o ISO 27001. Esto es el "idioma común" para hablar de tácticas de atacantes .

Análisis forense: La mayoría requiere habilidades en forensia digital (análisis de discos, memoria, logs) y uso de herramientas como Autopsy, FTK, Volatility, Wireshark .

Habilidades blandas: Se valora mucho la capacidad de trabajar bajo presión, el pensamiento crítico y la comunicación efectiva (saber explicar un ataque a un gerente no técnico) .

Inglés: En roles más especializados, el inglés B2 o superior es excluyente .

2. Habilidades que podrías necesitar desarrollar más
Basado en lo que piden estas ofertas, estas son las áreas donde deberías enfocarte para ser competitivo para puestos de Analista de Incidentes:

Forense Digital: Aprender a usar herramientas como Autopsy, FTK Imager, o KAPE. Es una habilidad muy demandada y específica.

Respuesta a Incidentes (IR): Practicar el proceso completo (detección, contención, erradicación, recuperación). Te sugiero realizar simulaciones en laboratorios controlados o buscar ejemplos de "tabletop exercises" (ejercicios de mesa).

Análisis de malware: No necesitas ser un experto reversero de entrada, pero entender cómo analizar malware en una "sandbox" (como Any.Run o Joe Sandbox) es un gran plus .

Scripting (Python/PowerShell): Aprender a programar para automatizar tareas es un requisito que aparece en roles de mayor seniority .

## Resumen y perspectivas

### Resumen de la lección

En esta lección, aprendiste las **consideraciones básicas para elaborar un plan de respuesta a incidentes**.

#### Puntos clave aprendidos

- Los **miembros clave** del equipo de respuesta a incidentes:
  - Jefe de equipo
  - Líder técnico
  - Líder de incidentes (en equipos grandes)
  - Miembros técnicos especializados

- **Otros grupos** de la organización que podrían ayudar con la respuesta:
  - Gestión
  - Soporte de TI
  - Departamento jurídico
  - Asuntos públicos
  - Recursos humanos
  - Gestión de instalaciones

- **Preocupaciones específicas** relacionadas con las fases de respuesta a incidentes:
  - Fase 1: Preparación (evaluación de riesgos, superficies de ataque)
  - Fase 2: Detección y análisis (herramientas, registros, clasificación)
  - Fase 3: Contención y erradicación (contener, evaluar daño, eliminar)
  - Fase 4: Recuperación (restaurar, comunicar, aprender)

---

### Perspectivas

**En la siguiente lección**, aprenderás:

- Cómo **encaja el análisis de incidentes** en la respuesta a incidentes
- **Mejores prácticas** para recopilar y analizar información relacionada con un ataque

### Acerca de esta lección: Análisis de intrusiones

Cuando un sistema alerta a un equipo de respuesta a incidentes sobre un ciberataque, es fácil **entrar en pánico**.

> El plan de respuesta a incidentes tiene muchas instrucciones, pero ¿cómo decide el equipo cuáles seguir?

#### En esta lección aprenderás

- **Qué es el análisis de intrusiones**
- El proceso de **recopilación e interpretación** de información sobre un ataque
- Cómo el equipo de respuesta a incidentes puede **formular una respuesta eficaz** basada en ese análisis

### ¿Qué es el análisis de intrusiones?

Cuando las herramientas de monitoreo detectan un incidente de ciberseguridad, el equipo de respuesta a incidentes (IR) recopila cualquier información disponible de:

- Registros del sistema
- Usuarios
- Otras fuentes

> Luego, el equipo realiza un **análisis de intrusiones** como uno de sus **primeros pasos**.

#### Definición

El **análisis de intrusiones** es el proceso de emplear información sobre un ataque para determinar:

| Aspecto | Pregunta que responde |
|---------|----------------------|
| **Alcance del ataque** | ¿Qué tan grande es el ataque? |
| **Método de acceso** | ¿Cómo entró el atacante? |
| **Daño causado** | ¿Qué afectó y cuánto daño hizo? |

---

### Áreas clave del análisis de intrusiones

A grandes rasgos, el análisis de intrusiones incluye **cuatro áreas clave**. Los equipos de IR deben investigar cada una para desarrollar una **imagen completa del ataque**.

| Área | Preguntas clave |
|------|-----------------|
| **Adversario** | ¿Quiénes son los atacantes? ¿Tienen un patrocinador? ¿Desde dónde atacaron? ¿Por qué atacaron? ¿Cómo planearon el ataque? |
| **Infraestructura** | ¿Hay equipos infectados, nombres de dominio comprometidos, servidores no autorizados? ¿Hay credenciales comprometidas? ¿Hubo violación física? |
| **Capacidad** | ¿Qué habilidades tienen los atacantes? ¿Pueden explotar vulnerabilidades, desplegar malware, hacer reconocimiento? ¿Pueden recuperar acceso? |
| **Objetivo** | ¿Qué datos atacaron y por qué? ¿El ataque apunta a una persona específica? ¿Apunta a un sector industrial, competidor o país? |

---

### Resumen de las 4 áreas
┌─────────────────────────────────────────────────────────────────────────────┐
│ ANÁLISIS DE INTRUSIONES - 4 ÁREAS CLAVE │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ┌─────────────────────────────────────────────────────────────────────┐ │
│ │ ADVERSARIO │ INFRAESTRUCTURA │ │
│ │ ¿Quiénes son? │ ¿Qué sistemas están comprometidos? │ │
│ │ ¿Desde dónde? │ ¿Hay credenciales robadas? │ │
│ │ ¿Por qué atacaron? │ ¿Hubo violación física? │ │
│ └─────────────────────────────────────────────────────────────────────┘ │
│ │
│ ┌─────────────────────────────────────────────────────────────────────┐ │
│ │ CAPACIDAD │ OBJETIVO │ │
│ │ ¿Qué saben hacer? │ ¿Qué datos querían? │ │
│ │ ¿Pueden volver a │ ¿Apuntan a alguien específico? │ │
│ │ entrar? │ ¿Es político, económico o industrial? │ │
│ └─────────────────────────────────────────────────────────────────────┘ │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

---

### Importancia del análisis de intrusiones

| Beneficio | Descripción |
|-----------|-------------|
| **Entender al atacante** | Saber quién es y por qué atacó ayuda a prepararse para futuros ataques |
| **Determinar el alcance** | Saber qué sistemas están comprometidos permite priorizar la respuesta |
| **Planear la erradicación** | Saber cómo entraron ayuda a cerrar la puerta |
| **Mejorar defensas** | Aprender del ataque para prevenir incidentes similares |

### Marcos de análisis de intrusiones

El análisis eficaz de intrusiones se deriva de aprender a **"pensar como un atacante"**.

#### ¿Qué es un marco de análisis de intrusiones?

Un **marco de análisis de intrusiones** es una herramienta de planificación esencial porque **describe las tácticas, estrategias y objetivos típicos de los atacantes**.

| Beneficio | Descripción |
|-----------|-------------|
| **Punto de partida sólido** | Proporciona al equipo de IR una base para comprender lo que se pretende lograr con los ataques |
| **Mejor respuesta** | Al comprender los métodos y objetivos de los atacantes, el equipo puede planear la mejor respuesta para bloquear los ataques |

> Ningún marco único se adaptará a las necesidades de **todas** las organizaciones. Cada equipo debe adaptar el marco a su organización.

---

#### Dos marcos populares y efectivos

| Marco | Descripción |
|-------|-------------|
| **MITRE ATT&CK** | Matriz de tácticas, técnicas y procedimientos (TTPs) de atacantes |
| **Cyber Kill Chain** | Modelo de las fases que sigue un atacante para completar un ataque |

---

#### ¿Por qué usar estos marcos?

| Razón | Explicación |
|-------|-------------|
| **Pensar como atacante** | Ayudan a entender cómo piensan y operan los atacantes |
| **Estandarización** | Proporcionan un lenguaje común para describir ataques |
| **Mejora continua** | Se actualizan constantemente con nuevas tácticas y técnicas |

En las siguientes secciones, exploraremos cada uno de estos marcos en detalle.

## Marco MITRE ATT&CK - Explicación fácil
¿Qué es MITRE ATT&CK?
Es una matriz (una tabla) que describe todas las tácticas y técnicas que usan los atacantes para realizar un ciberataque.

ATT&CK significa Adversarial Tactics, Techniques & Common Knowledge (Tácticas, Técnicas y Conocimiento Común del Adversario).

Analogía: Es como un manual de jugadas de los atacantes. Si sabes qué jugadas pueden hacer, podés preparar tu defensa.

Las 14 tácticas del marco MITRE ATT&CK
El marco se divide en 14 tácticas (pasos o fases) que sigue un atacante, desde que empieza a investigar hasta que logra su objetivo final.

┌─────────────────────────────────────────────────────────────────────────────────────┐
│                         MARCO MITRE ATT&CK - 14 TÁCTICAS                            │
├─────────────────────────────────────────────────────────────────────────────────────┤
│                                                                                      │
│  Reconocimiento ──▶ Desarrollo ──▶ Acceso ──▶ Ejecución ──▶ Persistencia            │
│                   de recursos      inicial                                          │
│                                                                                      │
│  Escalada ──▶ Evasión ──▶ Acceso a ──▶ Descubrimiento ──▶ Movimiento               │
│  de privilegios    de defensa   credenciales                    lateral            │
│                                                                                      │
│  Recopilación ──▶ Mando y ──▶ Exfiltración ──▶ Impacto                              │
│                   control                                                           │
│                                                                                      │
└─────────────────────────────────────────────────────────────────────────────────────┘

¿Cómo se usa MITRE ATT&CK?
Uso	Descripción
Análisis de intrusiones	Identificar en qué etapa del ataque están los atacantes
Planificación de defensa	Implementar controles para cada táctica (ej. MFA para acceso inicial)
Detección	Crear reglas en SIEM para detectar técnicas específicas
Respuesta a incidentes	Entender qué pasó y cómo responder según la etapa del ataque
Comunicación	Lenguaje común entre profesionales de seguridad
Ejemplo práctico: Ataque de phishing
Táctica	Lo que hace el atacante	Cómo se detecta/defiende
Reconocimiento	Investiga empleados de la empresa	Monitorear escaneos
Acceso inicial	Envía email con link malicioso	Filtro anti-phishing
Ejecución	Usuario hace clic y descarga malware	Antivirus, EDR
Persistencia	Se instala en el sistema	Monitoreo de cambios en el sistema
Exfiltración	Sube datos a servidor externo	Monitoreo de tráfico saliente

### Marco MITRE ATT&CK - Explicación fácil

#### ¿Qué es?

MITRE ATT&CK es una **matriz** que describe las **tácticas y técnicas** que usan los atacantes. Es como un "manual de jugadas" que ayuda a los profesionales de seguridad a entender y defenderse de los ataques.

#### Las 14 tácticas (pasos del atacante)

| Táctica | ¿Qué hace? |
|---------|-----------|
| 1. Reconocimiento | Investiga a la víctima (escaneos, búsquedas) |
| 2. Desarrollo de recursos | Prepara herramientas y dominios falsos |
| 3. Acceso inicial | Logra entrar por primera vez (phishing, vulnerabilidad) |
| 4. Ejecución | Corre código malicioso |
| 5. Persistencia | Se asegura de no perder el acceso |
| 6. Escalada de privilegios | Obtiene permisos de administrador |
| 7. Evasión de defensa | Evita ser detectado (ofusca código, desactiva antivirus) |
| 8. Acceso a credenciales | Roba contraseñas |
| 9. Descubrimiento | Explora el sistema buscando datos valiosos |
| 10. Movimiento lateral | Se mueve a otros sistemas |
| 11. Recopilación | Junta la información que quiere robar |
| 12. Mando y control (C2) | Se comunica con su servidor externo |
| 13. Exfiltración | Saca los datos robados de la red |
| 14. Impacto | Causa daño final (ransomware, destrucción) |

#### ¿Para qué sirve?

- **Análisis de intrusiones**: identificar en qué etapa está el ataque
- **Planificación de defensa**: implementar controles para cada táctica
- **Detección**: crear reglas en SIEM
- **Respuesta a incidentes**: entender y responder según la etapa
- **Comunicación**: lenguaje común entre profesionales


### Marco Cyber Kill Chain

El **marco Cyber Kill Chain** es otra herramienta valiosa para el análisis de intrusiones. Al igual que MITRE ATT&CK, proporciona una **estructura** para:

- **Identificar** comportamiento malicioso
- **Comprender** el ataque
- **Aislar** al atacante
- **Responder** al incidente

---

#### Diferencia clave entre MITRE ATT&CK y Cyber Kill Chain

| Aspecto | MITRE ATT&CK | Cyber Kill Chain |
|---------|--------------|------------------|
| **Enfoque** | Contrarrestar **técnicas** específicas | Contrarrestar **objetivos** del atacante |
| **Orden** | Flexible (los pasos pueden variar) | **Estricto** (deben seguir el orden para tener éxito) |
| **Número de pasos** | 14 tácticas | 8 fases |

> **Idea principal del marco Cyber Kill Chain:** Los atacantes deben seguir el orden establecido de pasos para tener éxito. Si se rompe un eslabón de la cadena, el ataque falla.

---

#### Las 8 fases de la Cyber Kill Chain

| Fase | Nombre | ¿Qué hace el atacante? | Cómo detenerlo |
|------|--------|------------------------|----------------|
| 1 | **Reconocimiento** | Investiga a la víctima (recopila información) | Monitorear escaneos, educar empleados |
| 2 | **Armamentización** | Crea o adquiere herramientas de ataque (malware, exploits) | Usar antimalware, mantener sistemas actualizados |
| 3 | **Entrega** | Envía el ataque a la víctima (email, USB, web) | Filtros de correo, controles de USB |
| 4 | **Explotación** | Ejecuta el código malicioso en el sistema | Parches de seguridad, EDR, antivirus |
| 5 | **Instalación** | Instala malware o puerta trasera en el sistema | Monitoreo de cambios, whitelisting de aplicaciones |
| 6 | **Mando y control (C2)** | Establece comunicación con el sistema comprometido | Monitoreo de tráfico saliente, firewalls |
| 7 | **Acción sobre el objetivo** | Logra su objetivo final (robar datos, ransomware) | Backup, segmentación de red, controles de acceso |

---

#### Diagrama de la Cyber Kill Chain
┌─────────────────────────────────────────────────────────────────────────────────────┐
│ CYBER KILL CHAIN - LAS 7 FASES │
├─────────────────────────────────────────────────────────────────────────────────────┤
│ │
│ Reconocimiento ──▶ Armamentización ──▶ Entrega ──▶ Explotación │
│ │
│ Instalación ──▶ Mando y control ──▶ Acción sobre el objetivo │
│ (C2) │
│ │
└─────────────────────────────────────────────────────────────────────────────────────┘

> **Si rompes un eslabón de la cadena, el ataque falla.**

---

#### Comparación: MITRE ATT&CK vs. Cyber Kill Chain

| Característica | MITRE ATT&CK | Cyber Kill Chain |
|----------------|--------------|------------------|
| **Enfoque** | Técnicas y tácticas | Objetivos y fases |
| **Orden** | Flexible (puede variar) | Estricto (debe seguir el orden) |
| **Cantidad** | 14 tácticas | 7-8 fases |
| **Nivel de detalle** | Muy detallado (muchas técnicas por táctica) | Alto nivel (fases generales) |
| **Mejor para** | Análisis profundo, detección específica | Visión estratégica, planificación de defensa |

---

#### ¿Cuándo usar cada uno?

| Situación | Marco recomendado |
|-----------|-------------------|
| **Análisis detallado de un ataque** (¿qué técnica usó?) | MITRE ATT&CK |
| **Planificación estratégica de defensa** (¿en qué fase detener al atacante?) | Cyber Kill Chain |
| **Respuesta a incidentes** (¿dónde estamos en el ataque?) | Ambos (se complementan) |
| **Creación de reglas de detección** (SIEM, EDR) | MITRE ATT&CK |

---

### Analogía fácil

| Concepto | Analogía |
|----------|----------|
| **Cyber Kill Chain** | El **mapa del viaje** (las ciudades que visita el atacante en orden) |
| **MITRE ATT&CK** | El **manual de técnicas** (qué hace en cada ciudad: cómo entra, cómo se esconde, qué roba) |

> **Cyber Kill Chain** te dice **dónde** está el atacante en su viaje.
> **MITRE ATT&CK** te dice **cómo** está operando en ese lugar.

### Cyber Kill Chain - Versión de 8 fases

#### Las 8 fases del ataque

| Fase | Nombre | Explicación |
|------|--------|-------------|
| 1 | **Reconocimiento** | El atacante investiga a la víctima: busca empleados, tecnologías que usan, direcciones de email, etc. |
| 2 | **Armamento y entrega** | Prepara el malware (arma) y lo envía por email, USB, o sitio web malicioso |
| 3 | **Explotación** | El malware se ejecuta aprovechando una vulnerabilidad del sistema |
| 4 | **Escalada de privilegios** | El atacante obtiene permisos de administrador para tener control total |
| 5 | **Movimiento lateral** | Se mueve de un sistema a otro dentro de la red para expandir el control |
| 6 | **Ofuscación y antiforense** | Oculta sus rastros: borra logs, ofusca código, desactiva herramientas de monitoreo |
| 7 | **Denegación de servicio** | Interrumpe servicios (puede ser el objetivo final o una distracción) |
| 8 | **Exfiltración** | Saca los datos robados de la red (los envía a su servidor) |

#### Cómo detener al atacante en cada fase

| Fase | Estrategia de defensa |
|------|----------------------|
| Reconocimiento | Monitorear escaneos, educar empleados, limitar información pública |
| Armamento y entrega | Filtros de correo, controles de USB, antivirus |
| Explotación | Parches de seguridad, EDR, hardening de sistemas |
| Escalada de privilegios | Principio de mínimo privilegio (POLP), MFA |
| Movimiento lateral | Segmentación de red, monitoreo de conexiones anómalas |
| Ofuscación y antiforense | Logs centralizados (SIEM), integridad de logs |
| Denegación de servicio | Protección DDoS, balanceadores de carga |
| Exfiltración | Monitoreo de tráfico saliente, DLP (Data Loss Prevention) |

1. ¿Cuándo usar MITRE ATT&CK y cuándo usar Cyber Kill Chain?
Situación	Marco recomendado	¿Por qué?
Análisis detallado de un ataque (¿qué técnica usó el atacante?)	MITRE ATT&CK	Tiene muchísimo detalle (más de 200 técnicas)
Respuesta a incidentes (¿en qué etapa del ataque estamos?)	Ambos	ATT&CK da detalle, Kill Chain da visión general
Planificación de defensa (¿en qué fase debemos bloquear?)	Cyber Kill Chain	Te muestra los puntos críticos donde detener al atacante
Creación de reglas de detección (para SIEM, EDR)	MITRE ATT&CK	Te dice exactamente qué comportamientos buscar
Presentación a gerencia (explicar un ataque de forma simple)	Cyber Kill Chain	Tiene pocas fases, es más fácil de entender
Análisis forense profundo	MITRE ATT&CK	Tiene el nivel de detalle que necesitas
Regla práctica
Si querés...	Usá...
El "mapa" del ataque (visión general)	Cyber Kill Chain
El "manual técnico" (detalle de cada paso)	MITRE ATT&CK
2. ¿Se pueden usar los dos juntos?
✅ SÍ, absolutamente. De hecho, es lo mejor que podés hacer.

Analogía: Son dos herramientas que se complementan:

Herramienta	Analogía
Cyber Kill Chain	El mapa de ruta del viaje (las ciudades que visita el atacante en orden)
MITRE ATT&CK	La guía detallada de qué hace el atacante en cada ciudad
Usarlos juntos:
┌─────────────────────────────────────────────────────────────────────────────┐
│                    CÓMO USAR AMBOS MARCOS JUNTOS                            │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│   Cyber Kill Chain:       Reconocimiento ──▶ Entrega ──▶ Explotación        │
│   (el "cuándo" y "dónde")                                                    │
│                                                                              │
│   MITRE ATT&CK:           Técnica 1    Técnica 2    Técnica 3               │
│   (el "cómo" y "qué")     Técnica 4                 Técnica 5               │
│                                                                              │
│   Ejemplo:                                                                   │
│   1. Kill Chain dice: "El atacante está en la fase ENTREGA"                 │
│   2. ATT&CK dice: "La técnica específica fue phishing con adjunto malicioso"│
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘

En la práctica: Los profesionales de seguridad usan primero Cyber Kill Chain para entender en qué fase están, y luego MITRE ATT&CK para obtener el detalle técnico de esa fase.

3. ¿Tienen costo?
Marco	¿Es gratuito?	¿Quién lo creó?
MITRE ATT&CK	✅ 100% gratuito (código abierto)	MITRE (organización sin fines de lucro de EE.UU.)
Cyber Kill Chain	✅ 100% gratuito	Lockheed Martin (compañía privada, pero el marco es público)
¿Dónde acceder?
Marco	Acceso
MITRE ATT&CK	https://attack.mitre.org (sitio web gratuito con toda la matriz)
Cyber Kill Chain	Documentación pública, se encuentra en artículos y libros de ciberseguridad
Importante: No hay que pagar nada. Son marcos de conocimiento (frameworks), no software. No se "instalan", se "estudian" y "aplican".

### ¿Cuándo usar MITRE ATT&CK vs. Cyber Kill Chain?

#### Respuestas rápidas

| Pregunta | Respuesta |
|----------|-----------|
| **¿Cuándo usar MITRE ATT&CK?** | Cuando necesitás **detalle técnico** (qué técnica usó el atacante) |
| **¿Cuándo usar Cyber Kill Chain?** | Cuando necesitás **visión general** (en qué fase está el atacante) |
| **¿Se pueden usar juntos?** | ✅ **Sí**, se complementan perfectamente |
| **¿Tienen costo?** | ❌ **No**, ambos son gratuitos |

#### Tabla comparativa

| Característica | MITRE ATT&CK | Cyber Kill Chain |
|----------------|--------------|------------------|
| **Enfoque** | Técnicas y tácticas | Fases del ataque |
| **Cantidad** | 14 tácticas, +200 técnicas | 7-8 fases |
| **Detalle** | Muy detallado | Alto nivel |
| **Orden** | Flexible (puede variar) | Estricto (debe seguir el orden) |
| **Costo** | Gratuito | Gratuito |
| **Acceso** | attack.mitre.org | Documentación pública |

#### Mejor práctica

Usar **ambos**:
1. **Cyber Kill Chain** para el contexto general (¿dónde estamos?)
2. **MITRE ATT&CK** para el detalle técnico (¿cómo opera?)

#### Ejercicio: Determinar el alcance de un ataque de fuerza bruta

**Escenario:**  
Eres un analista de seguridad revisando un informe de Splunk para BetterBytes Games. Identificaste un ataque de fuerza bruta desde la IP `64.66.0.20`.

**Pregunta:** ¿Qué debes hacer primero para determinar el alcance de la amenaza?

- [x] **Analiza el informe en busca de intentos de inicio de sesión fallidos desde la dirección IP 64.66.0.20**
- [ ] Comprueba si hay actualizaciones de software en todos los sistemas de la empresa
- [ ] Ponte en contacto con el administrador del sistema para restablecer todas las contraseñas de los usuarios
- [ ] Notifica a todos los usuarios de una posible filtración de datos de inmediato

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Analizar el informe en busca de intentos fallidos desde la IP**. El primer paso ante una alerta es **investigar y analizar** la evidencia disponible para entender el alcance de la amenaza (cuántos intentos, qué usuarios, qué sistemas). Actuar sin analizar (restablecer contraseñas, notificar usuarios) puede ser prematuro e ineficaz.

</details>

#### Ejercicio: Información adicional para entender un ataque de fuerza bruta

**Escenario:**  
Descubriste repetidos intentos fallidos de inicio de sesión desde una IP en un informe de Splunk.

**Pregunta:** ¿Qué información adicional deberías buscar para entender mejor la amenaza?

- [x] **Inicios de sesión exitosos desde la misma dirección IP**
- [ ] Registros de correo electrónico para intentos de phishing
- [ ] Errores del sistema no relacionados durante el mismo tiempo
- [ ] Patrones de tráfico del sitio web durante el último mes

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Inicios de sesión exitosos desde la misma IP**. Al analizar un ataque de fuerza bruta, lo más crítico es determinar si el atacante logró acceder exitosamente. Si hubo algún inicio de sesión exitoso, significa que una cuenta fue comprometida y se debe actuar de inmediato (restablecer contraseña, revisar actividades posteriores).

</details>

#### Ejercicio: Información para entender el alcance de intentos de fuerza bruta

**Escenario:**  
Al analizar el reporte, encuentras que se intentan varios nombres de usuario. Un atacante podría estar probando sistemáticamente diferentes nombres de usuario para obtener acceso no autorizado.

**Pregunta:** ¿Qué información específica debes buscar para comprender el alcance de estos intentos?

- [x] **Nombres de usuario y frecuencia de cada intento desde la dirección IP**
- [ ] Sistema operativo de las máquinas a las que se dirige
- [ ] Hora del día en que se realizaron los intentos
- [ ] Patrones de otro tráfico de red

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Nombres de usuario y frecuencia de cada intento desde la IP**. Para entender el alcance de un ataque de fuerza bruta, es fundamental saber:
- **Qué usuarios** están siendo atacados (¿son reales? ¿son genéricos?)
- **Con qué frecuencia** (¿hay un usuario específico siendo atacado más que otros?)

Esta información ayuda a determinar si el ataque es dirigido o masivo, y qué cuentas están en mayor riesgo.

</details>

#### Ejercicio: Acciones inmediatas para mitigar un ataque de fuerza bruta

**Escenario:**  
BetterBytes Games está sufriendo un ataque de fuerza bruta en curso desde la IP `64.66.0.20`.

**Pregunta:** ¿Cuál es tu acción inmediata para mitigar la amenaza?

- [ ] Informar a los usuarios y pedirles que cambien sus contraseñas
- [x] **Emplear la configuración del firewall para bloquear la dirección IP 64.66.0.20**
- [ ] Resetear el servidor principal para interrumpir el ataque de inmediato
- [ ] Desactivar temporalmente la funcionalidad de inicio de sesión para todos los usuarios

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Bloquear la IP en el firewall**. Es la acción más rápida y efectiva para detener un ataque de fuerza bruta en curso sin afectar a los usuarios legítimos.

- **Resetear el servidor** es extremo y no resuelve el problema
- **Desactivar el login** afecta a todos los usuarios
- **Cambiar contraseñas** es útil después, pero no detiene el ataque actual

</details>

#### Ejercicio: Paso adicional para fortalecer defensas después de un ataque

**Escenario:**  
Después de bloquear la IP maliciosa que estaba realizando un ataque de fuerza bruta.

**Pregunta:** ¿Qué paso adicional debes tomar para fortalecer las defensas del sistema?

- [ ] Apagar toda la red para una auditoría de seguridad completa
- [x] **Revise y actualice la política de contraseñas para aplicar contraseñas más seguras**
- [ ] Eliminar todos los registros con más de un mes de antigüedad para ahorrar espacio
- [ ] Enviar un correo a toda la empresa sobre la mitigación exitosa

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Revisar y actualizar la política de contraseñas**.

- **Apagar la red** es extremo e innecesario
- **Eliminar registros** es contraproducente (se pierde evidencia)
- **Enviar un correo** es informativo, pero no fortalece las defensas

Actualizar la política de contraseñas (exigir contraseñas más seguras, implementar MFA) es una medida preventiva clave para evitar que futuros ataques de fuerza bruta tengan éxito.

</details>

### Actualización de la política de contraseñas después de un ataque de fuerza bruta

#### Política de contraseñas ANTES del ataque

| Requisito | Estado |
|-----------|--------|
| Longitud mínima | 8 caracteres |
| Complejidad | Al menos un número y un carácter especial |
| Caducidad | Cada 90 días |
| Reutilización | Sin restricciones |
| Contraseñas comunes | No prohibidas |

---

#### Política de contraseñas ACTUALIZADA (después del ataque)

| Requisito | Nueva regla | Por qué |
|-----------|-------------|---------|
| **Longitud mínima** | **12 caracteres** | Más caracteres = más difícil de adivinar por fuerza bruta |
| **Complejidad** | Mayúsculas + minúsculas + números + caracteres especiales | Más combinaciones posibles |
| **Caducidad** | 90 días (se mantiene) | Renovación periódica |
| **Reutilización** | **Impedir las últimas 5 contraseñas** | Evita que los usuarios reciclen contraseñas viejas (posiblemente comprometidas) |
| **Contraseñas comunes** | **Prohibidas** (lista de contraseñas restringidas) | Evita "123456", "password", "admin123", etc. |

---

#### Acciones adicionales tomadas

| Acción | Propósito |
|--------|-----------|
| **Actualizar configuración de seguridad** | Implementar técnicamente los nuevos requisitos |
| **Enviar correo a todos los usuarios** | Comunicar el cambio |
| **Proporcionar enlace con instrucciones** | Ayudar a los usuarios a crear contraseñas seguras |

---

#### ¿Por qué estas actualizaciones ayudan a prevenir futuros ataques?

| Medida | Cómo previene ataques de fuerza bruta |
|--------|--------------------------------------|
| **12 caracteres mínimo** | Un atacante necesitaría muchísimo más tiempo para adivinar (por prueba y error) |
| **Complejidad (4 tipos)** | Multiplica las combinaciones posibles exponencialmente |
| **Prohibir contraseñas comunes** | Evita que los usuarios usen contraseñas que están en listas de atacantes |
| **No reutilizar últimas 5** | Evita que, si una contraseña se filtra, se vuelva a usar |

---

### Resumen visual
┌─────────────────────────────────────────────────────────────────────────────┐
│ ACTUALIZACIÓN DE POLÍTICA DE CONTRASEÑAS │
├─────────────────────────────────────────────────────────────────────────────┤
│ │
│ ANTES DESPUÉS │
│ ┌─────────────────────┐ ┌─────────────────────┐ │
│ │ Mínimo: 8 caracteres│ │ Mínimo: 12 caracteres│ ✅ │
│ │ Un número y especial│────────────▶│ 4 tipos (Mayúsc, │ ✅ │
│ │ Sin restricción │ │ minúsc, número, esp) │ │
│ │ comunes │ │ Prohibir comunes │ ✅ │
│ │ Reutilización libre │ │ No repetir últimas 5 │ ✅ │
│ └─────────────────────┘ └─────────────────────┘ │
│ │
│ Vulnerable a fuerza bruta Mucho más resistente │
│ │
└─────────────────────────────────────────────────────────────────────────────┘

#### Ejercicio: Acción después de bloquear una IP maliciosa

**Escenario:**  
Bloqueaste la IP `64.66.0.20` que estaba realizando un ataque de fuerza bruta.

**Pregunta:** ¿Qué debes hacer después para asegurar la efectividad de tus acciones?

- [x] **Supervisar si hay más intentos desde diferentes direcciones IP**
- [ ] Revisar todos los correos enviados a los usuarios durante el ataque
- [ ] Comprobar si hay nuevas actualizaciones de software disponibles
- [ ] Contar el número de usuarios afectados por el ataque

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Supervisar si hay más intentos desde diferentes direcciones IP**. Los atacantes suelen tener múltiples IPs (botnets, VPNs) y pueden cambiar de origen después de ser bloqueados. La supervisión continua permite detectar si el ataque persiste desde nuevas direcciones.

- **Revisar correos** no es relevante para un ataque de fuerza bruta
- **Actualizar software** es una buena práctica general, pero no es la acción inmediata posterior al bloqueo
- **Contar usuarios afectados** ya se determinó que los usuarios probados eran inválidos

</details>

#### Actividad: Pros y Contras de la Autenticación Multifactor (MFA)

##### Beneficios de MFA (Pros)

- [x] **MFA aumenta significativamente la seguridad de las cuentas de usuario**
- [x] **MFA ayuda a proteger los datos confidenciales de los usuarios**
- [ ] MFA reduce el costo de las medidas de seguridad necesarias (Falso)
- [ ] MFA simplifica el proceso de inicio de sesión (Falso)

##### Inconvenientes de MFA (Contras)

- [x] **MFA agrega un paso al proceso, lo que posiblemente frustre a algunos usuarios**
- [x] **Es posible que MFA requiera más recursos para implementar y gestionar**
- [ ] MFA garantiza que no se producirán violaciones de seguridad (Falso)
- [ ] MFA hace imposible recuperar cuentas perdidas (Falso)

#### Resumen

| Pros | Contras |
|------|---------|
| Mayor seguridad | Más pasos (frustración) |
| Protege datos confidenciales | Requiere más recursos |
| Previene accesos no autorizados | Posible costo adicional |
| Defensa contra fuerza bruta | Curva de aprendizaje para usuarios |

### Estrategias para implementar MFA (Autenticación Multifactor)

Después del ataque de fuerza bruta, el equipo de seguridad debate cómo implementar MFA. Tres opciones presentadas:

---

#### Opción 1: Implementar MFA de inmediato (Angella Pauling)

| Aspecto | Descripción |
|---------|-------------|
| **Qué propone** | Activar MFA en **todas las cuentas de usuario de inmediato** |
| **Ventaja** | Mejora significativamente la seguridad **desde el principio** |
| **Desventaja** | Inconvenientes inmediatos para usuarios no familiarizados con MFA |

> **Ideal para:** Organizaciones que priorizan la **seguridad máxima** por sobre la experiencia de usuario

---

#### Opción 2: Implementación gradual de MFA (Dennis Bowen)

| Aspecto | Descripción |
|---------|-------------|
| **Qué propone** | Introducir MFA **progresivamente**: comenzar con actividades de alto riesgo, aumentar gradualmente hasta cubrir todos los inicios de sesión |
| **Ventaja** | Da tiempo a los usuarios para **adaptarse**, minimiza interrupciones abruptas |
| **Desventaja** | Lleva **más tiempo** obtener protección completa |

> **Ideal para:** Organizaciones que priorizan la **experiencia de usuario** y quieren una transición suave

---

#### Opción 3: MFA solo para dispositivos nuevos (Rosa de La Cruz)

| Aspecto | Descripción |
|---------|-------------|
| **Qué propone** | Requerir MFA **solo cuando el usuario inicia sesión desde un dispositivo nuevo o no reconocido** |
| **Ventaja** | **Equilibrio** entre seguridad y conveniencia: verificación solo cuando es necesario |
| **Desventaja** | Dispositivos familiares siguen siendo un punto débil (si se comprometen) |

> **Ideal para:** Organizaciones que buscan un **balance** entre seguridad y experiencia de usuario

---

### Comparativa de las 3 opciones

| Criterio | Opción 1 (Inmediata) | Opción 2 (Gradual) | Opción 3 (Dispositivos nuevos) |
|----------|---------------------|-------------------|-------------------------------|
| **Velocidad de implementación** | ✅ Muy rápida | ❌ Lenta | ⚠️ Media |
| **Seguridad inmediata** | ✅ Alta | ❌ Baja al principio | ⚠️ Media |
| **Experiencia de usuario** | ❌ Puede frustrar | ✅ Buena (adaptación) | ✅ Buena (solo cuando es necesario) |
| **Complejidad** | Baja | Media | Media |
| **Protección contra fuerza bruta** | ✅ Alta | ⚠️ Gradual | ✅ Buena |

---

### Resumen de las posiciones del equipo

| Miembro | Opción preferida | Razón principal |
|---------|-----------------|-----------------|
| **Angella Pauling** | Implementación inmediata | Seguridad máxima desde el principio |
| **Dennis Bowen** | Implementación gradual | Menos interrupciones para usuarios |
| **Rosa de La Cruz** | MFA solo para dispositivos nuevos | Equilibrio entre seguridad y conveniencia |

---

### Conclusión del equipo

> *"La mejor opción depende de las **necesidades de seguridad** y las **prioridades de experiencia del usuario** de la organización."*

| Si priorizas... | Elegí... |
|-----------------|----------|
| **Seguridad máxima** (ej. banca, salud) | Opción 1 (Inmediata) |
| **Experiencia de usuario** (ej. juegos, retail) | Opción 2 (Gradual) o Opción 3 (Dispositivos nuevos) |
| **Balance** entre ambos | Opción 3 (Dispositivos nuevos) |

✅ Actividad: Certificación EC-Council Certified Incident Handler (CIH)
Habilidades de gestión profesional: EC-Council ofrece la certificación Certified Incident Handler (CIH) para ayudar a los profesionales a prepararse y responder ante incidentes de ciberseguridad .

📋 Las 9 Etapas del Manejo de Incidentes (ECIH v3)
El corazón de esta certificación es un proceso estructurado de 9 pasos para manejar cualquier incidente :

Preparación para el Manejo y Respuesta a Incidentes: Establecer políticas, herramientas y un equipo antes de que ocurra un incidente.

Registro y Asignación del Incidente: Documentar formalmente el incidente y designar a los responsables.

Clasificación del Incidente (Triage): Evaluar la urgencia, el impacto y la prioridad del incidente .

Notificación: Alertar a las partes interesadas internas (directivos, legal) y externas (clientes, reguladores) según el plan.

Contención: Aislar los sistemas afectados para detener la propagación y minimizar el daño .

Recolección de Evidencia y Análisis Forense: Recopilar y preservar pruebas digitales (logs, discos) de forma segura para su análisis .

Erradicación: Eliminar completamente la amenaza del sistema (malware, cuentas comprometidas, puertas traseras) .

Recuperación: Restaurar los sistemas y datos afectados a su estado operativo normal (ej. usando copias de seguridad seguras) .

Actividades Posteriores al Incidente: Realizar una revisión para identificar lecciones aprendidas, mejorar las defensas y actualizar el plan de respuesta .

Áreas que Cubre la Certificación CIH (y mi análisis)
He investigado el temario y aquí te explico los 6 tipos de incidentes críticos que se abordan, incluyendo tu consulta sobre amenazas internas .

1. Incidentes de Malware
Se estudia cómo detectar, contener y analizar software malicioso, así como eliminarlo y recuperar los sistemas infectados .

2. Incidentes de Seguridad en la Nube
Aprenderás a manejar incidentes específicos en entornos como AWS, Azure y Google Cloud . Esto incluye desde configuraciones erróneas hasta accesos no autorizados.

3. Incidentes de Seguridad del Correo Electrónico
Te enseñan a responder a amenazas como el phishing, el business email compromise (BEC) y la propagación de malware a través del correo, incluyendo cómo analizar cabeceras y archivos adjuntos maliciosos .

4. Incidentes de Seguridad de Aplicaciones Web
Se enfoca en ataques como inyección SQL, cross-site scripting (XSS) y cómo investigar y contener una violación en una aplicación web .

5. Incidentes de Seguridad de la Red
Aquí se cubren los ataques a la infraestructura de red (DoS/DDoS, accesos no autorizados, etc.), aprendiendo a detectarlos, contenerlos y erradicarlos .

6. Amenazas Internas
Explicación: Aunque ya viste este tema en el Módulo 8, la certificación ECIH lo profundiza desde la perspectiva de la respuesta a incidentes .

Se centra en cómo detectar actividades anómalas que indiquen un abuso de privilegios.

Detalla cómo contener el acceso de un empleado malicioso o negligente.

Incluye el análisis forense específico para este tipo de amenazas, y las estrategias de erradicación y recuperación.

💡 Reflexión y Notas Personales (para tu actividad)
Aquí te comparto algunas notas sobre conceptos que pueden generar dudas y que me parecen clave para profundizar. Siéntete libre de usarlas o agregar las tuyas:

Diferencia entre Triage, Contención y Erradicación: Es fácil confundirlas.

Triage (Paso 3): Es evaluar el incidente para priorizar ("¿Esto es un incendio forestal o una vela encendida?").

Contención (Paso 5): Es la primera acción para detener el daño ("Poner la vela dentro de un frasco de cristal para que no queme la mesa").

Erradicación (Paso 7): Es eliminar limpiamente la raíz del problema ("Apagar la vela y tirarla a la basura"). El curso de ECIH ayuda a trazar estas líneas con claridad.

Complementariedad con Módulos Anteriores: Me interesa mucho cómo la certificación CIH conecta directamente con lo que vimos en el Módulo 11 (Respuesta a Incidentes) y Módulo 8 (Seguridad en la Nube) . Es una forma de validar oficialmente esos conocimientos.

Relación con Marcos de Análisis: Sería interesante explorar a fondo cómo las 9 etapas de ECIH se integran con marcos como MITRE ATT&CK y Cyber Kill Chain, los cuales vimos en el curso .

📚 Para más información
Te sugiero visitar el sitio oficial de EC-Council o las plataformas de formación como Coursera o Learning Tree para ver los requisitos y el temario actualizado .

#### Ejercicio: Identificar la fase de ocultamiento en Cyber Kill Chain

**Escenario:**  
SilverHedge Financial sufrió un ataque. Los atacantes **eliminaron registros y crearon pistas falsas** para confundir al equipo de respuesta a incidentes.

**Pregunta:** ¿En qué etapa de la Cyber Kill Chain ocultarían sus acciones?

- [ ] Armamento y entrega
- [ ] Reconocimiento
- [ ] Exfiltración
- [x] **Ofuscación y antiforense**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Ofuscación y antiforense**. Esta fase se caracteriza por acciones como:
- Borrar registros (logs) para eliminar evidencia
- Crear pistas falsas para desviar la investigación
- Ofuscar código para dificultar el análisis
- Deshabilitar herramientas de monitoreo

Las otras fases tienen otros propósitos:
- **Armamento y entrega** → preparar y enviar el ataque
- **Reconocimiento** → investigar a la víctima
- **Exfiltración** → sacar los datos robados

</details>

┌─────────────────────────────────────────────────────────────────────────────┐
│                    MITRE ATT&CK - MANDO Y CONTROL (C2)                      │
├─────────────────────────────────────────────────────────────────────────────┤
│                                                                              │
│   Reconocimiento ──▶ Acceso inicial ──▶ Ejecución ──▶ Persistencia          │
│                                                                              │
│   Escalada de privilegios ──▶ Evasión de defensa ──▶ Acceso a credenciales   │
│                                                                              │
│   Descubrimiento ──▶ Movimiento lateral ──▶ Recopilación                     │
│                                                                              │
│   ▶ **MANDO Y CONTROL (C2)** ◀─── ¡ESTAMOS ACÁ!                             │
│                                                                              │
│   Exfiltración ──▶ Impacto                                                  │
│                                                                              │
└─────────────────────────────────────────────────────────────────────────────┘

#### Ejercicio: Identificar la fase de Mando y control en MITRE ATT&CK

**Escenario:**  
HealthGuard Medical Services sufrió un ataque. Los atacantes **establecieron una conexión con los sistemas comprometidos para controlarlos y manipularlos de forma remota**.

**Pregunta:** ¿Qué paso del marco MITRE ATT&CK implica esta acción?

- [ ] Reconocimiento
- [x] **Mando y control**
- [ ] Exfiltración
- [ ] Escalada de privilegios

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Mando y control (C2)**. Esta fase se caracteriza por:
- Establecer una conexión remota con sistemas comprometidos
- Recibir órdenes del atacante
- Enviar información al atacante
- Mantener un canal de comunicación persistente

Las otras fases tienen otros propósitos:
- **Reconocimiento** → investigar a la víctima
- **Exfiltración** → sacar datos robados
- **Escalada de privilegios** → obtener permisos de administrador

</details>

#### Ejercicio: Identificar la fase de Acceso inicial en MITRE ATT&CK

**Escenario:**  
Healthy U sufrió un ataque. Los atacantes **aprovecharon una vulnerabilidad en la aplicación web** para obtener acceso no autorizado a la red interna.

**Pregunta:** ¿Qué paso del marco MITRE ATT&CK incluye los esfuerzos del atacante para obtener acceso no autorizado mediante la explotación de un error de software?

- [ ] Persistencia
- [x] **Acceso inicial**
- [ ] Recopilación
- [ ] Descubrimiento

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Acceso inicial**. Esta fase incluye técnicas como la explotación de vulnerabilidades (aprovechar errores de software), phishing, fuerza bruta, etc. Es el momento en que el atacante logra entrar al sistema por primera vez.

</details>

#### Ejercicio: Identificar la táctica de Ejecución en MITRE ATT&CK

**Escenario:**  
TechSecure Inc. sufre un ataque. Los atacantes desplegaron ransomware para cifrar archivos confidenciales.

**Pregunta:** ¿Cuál de las siguientes acciones se clasificaría bajo la **táctica de ejecución**?

- [ ] Obtener permisos de nivel superior, como usar una vulnerabilidad
- [x] **Ejecutar código malicioso, como desplegar un virus**
- [ ] Intentar evitar la detección, como usar procesos confiables para ocultar malware
- [ ] Recopilar datos de interés, como acceder a los datos almacenados

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Ejecutar código malicioso, como desplegar un virus**. En MITRE ATT&CK, la táctica de **Ejecución** se refiere a técnicas que permiten al atacante correr código malicioso en el sistema (ej. malware, scripts, ransomware).

- **Escalada de privilegios** → obtener permisos
- **Evasión de defensa** → evitar detección
- **Recopilación** → juntar datos

</details>

#### Ejercicio: Identificar la fase de Armamento y entrega en Cyber Kill Chain

**Escenario:**  
YouSave Bank sufre un ataque. Los atacantes **enviaron un correo de phishing con un enlace malicioso** que instalaba malware al hacer clic.

**Pregunta:** ¿Cuál de las siguientes acciones se clasificaría como **"Armamento y entrega"** ?

- [ ] Desarrollar herramientas y crear infraestructura para el ataque
- [x] **Entregar la carga maliciosa a través de correos electrónicos de phishing**
- [ ] Evaluar la situación para identificar objetivos y tácticas para el ataque
- [ ] Entrar en el sistema de destino mediante malware o vulnerabilidades de seguridad

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Entregar la carga maliciosa a través de correos electrónicos de phishing**. En la Cyber Kill Chain, la fase de **Armamento y entrega** comprende:
- **Armamentización**: crear/desarrollar el arma (malware)
- **Entrega**: enviar el arma a la víctima (email, USB, sitio web)

El envío del correo de phishing es el acto de **entrega** de la carga maliciosa.

- **Reconocimiento** → investigar a la víctima
- **Explotación** → ejecutar el malware

</details>

## Puntos para recordar - Conceptos clave

### Respuesta a incidentes

| # | Concepto |
|---|----------|
| 1 | Una **respuesta eficaz a los incidentes** es crucial para una buena seguridad del sistema |
| 2 | La respuesta a incidentes tiene **cuatro fases**: Preparación → Detección y análisis → Contención y erradicación → Recuperación |
| 3 | Una buena respuesta a incidentes se basa en un **plan sólido de respuesta a incidentes (IRP)** |
| 4 | Un IRP debe abordar las fases de IR, incluidas las **tareas** en cada fase y las **personas responsables** |
| 5 | Los equipos de IR tienen **miembros clave**, y cada uno debe tener las habilidades pertinentes (jefe, líder técnico, etc.) |
| 6 | **Otras partes** de la organización pueden desempeñar papeles importantes (gestión, TI, legal, RR.HH., etc.) |

### Análisis de intrusiones y marcos

| # | Concepto |
|---|----------|
| 7 | El **análisis de intrusiones** es el proceso de emplear información sobre un ataque para determinar y aprender de sus características clave |
| 8 | Existen **marcos de análisis de intrusiones** que los equipos pueden emplear para aprender cómo piensan y crean los atacantes los ataques |
| 9 | Dos marcos populares son **MITRE ATT&CK** (14 tácticas, enfoque en técnicas) y **Cyber Kill Chain** (7-8 fases, enfoque en objetivos) |

---

## Grandes ideas - Habilidades practicadas

| Habilidad | Aplicación en el módulo |
|-----------|-------------------------|
| **Pensamiento crítico** | Enumerar elementos críticos de un plan de IR, identificar las 4 fases |
| **Comunicación escrita** | Aplicar marco de IR adecuado a las necesidades de una organización |
| **Atención al detalle** | Identificar funciones en el equipo de IR y participantes externos |
| **Pensamiento analítico** | Distinguir entre áreas clave de análisis de intrusiones (Adversario, Infraestructura, Capacidad, Objetivo) |
| **Resolución de problemas** | Responder a un ataque de red |
| **Agilidad de aprendizaje** | Aplicar marcos MITRE ATT&CK y Cyber Kill Chain |
| **Mentalidad de crecimiento** | Explorar certificaciones (EC-Council CIH, etc.) |
| **Investigación** | Enumerar requisitos para puestos de IR y las 9 etapas de manejo de incidentes de EC-Council |

### Habilidades de gestión profesional

- Recordar las **tareas típicas** que realiza un analista de incidentes
- Resumir las **habilidades necesarias** para ser un analista de incidentes certificado

---

## Objetivos de aprendizaje - Módulo 11 completado

Ahora que has completado este módulo, deberías ser capaz de:

- ✅ **Aplicar un marco de respuesta a incidentes adecuado** dadas las necesidades de una organización
- ✅ **Identificar las funciones del equipo de respuesta a incidentes**
- ✅ **Aplicar el marco MITRE ATT&CK**
- ✅ **Aplicar el marco Cyber Kill Chain**
- ✅ **Responder a un ataque de red**

---

## Resumen de los dos marcos principales

| Característica | MITRE ATT&CK | Cyber Kill Chain |
|----------------|--------------|------------------|
| **Enfoque** | Técnicas y tácticas | Fases del ataque |
| **Cantidad** | 14 tácticas, +200 técnicas | 7-8 fases |
| **Orden** | Flexible (puede variar) | Estricto (debe seguir el orden) |
| **Mejor para** | Análisis detallado, detección | Visión estratégica, planificación |
| **Costo** | Gratuito | Gratuito |

---

## ¡Módulo 11 completado! 🎉

### Resumen de las 4 fases de respuesta a incidentes

| Fase | Acción |
|------|--------|
| **1. Preparación** | Planificar, capacitar, tener herramientas listas |
| **2. Detección y análisis** | Monitorear, detectar, analizar el incidente |
| **3. Contención y erradicación** | Detener la propagación, eliminar la amenaza |
| **4. Recuperación** | Restaurar sistemas, comunicar, aprender |

#### Ejercicio: Identificar la fase de respuesta a incidentes

**Escenario:**  
Cybertech Corporation identificó un **aumento inesperado en el tráfico de red**.

**Pregunta:** ¿En qué fase de respuesta a incidentes se encuadra?

- [ ] Recuperación
- [ ] Contención y erradicación
- [ ] Preparación
- [x] **Detección y análisis**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Detección y análisis**. Esta fase consiste en identificar y analizar posibles incidentes de seguridad (como un aumento anómalo de tráfico). Las otras fases tienen otros propósitos:
- **Preparación** → antes del incidente
- **Contención y erradicación** → detener la amenaza
- **Recuperación** → restaurar después del incidente

</details>

