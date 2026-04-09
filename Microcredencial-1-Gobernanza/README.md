# 🛡️ Formación en Ciberseguridad - IBM 

Bienvenido a mi repositorio de aprendizaje en Ciberseguridad. Este espacio documenta mi progreso técnico y estratégico, enfocado en el rol de **Analista SOC / Ciberseguridad**.

## 📁 Estructura del Proyecto

### 🏛️ Módulo 1: GRC y Privacidad de Datos
*Fundamentos de Gobernanza, Riesgo, Cumplimiento y marcos legales.*
* [Conceptos de GRC](./modulo1/GRC_concepts.md)
* [Gestión de Riesgos y Activos](./modulo1/Risk_Management.md)
* [Privacidad y Protección de Datos](./modulo1/Privacy.md)


---

## 🛠️ Skills & Frameworks
* **Frameworks:** NIST CSF, ISO 27001 (Conceptos básicos).
* **Estándares:** STIX 2.1, TAXII.
* **Análisis:** CVSS v3.1 Scoring.

> "La ciberseguridad es un esfuerzo continuo de gestión de riesgos, no un destino final."

## DATOS Y PRIVACIDAD 

## La privacidad de los datos, como concepto y como práctica, es esencial en el campo de la ciberseguridad. Cada trabajo en ese campo gira en torno a mantener los datos de las personas u organizaciones fuera de las manos equivocadas. 

## Te damos la bienvenida al módulo Datos y privacidad. En este módulo, explorarás la ciberseguridad y verás cuáles son los elementos clave y las amenazas que aborda. Aprenderás sobre la privacidad de los datos, por ejemplo, cuáles son los diferentes tipos de datos confidenciales y qué consecuencias enfrentan las organizaciones cuando ocurren filtraciones de datos. Luego, descubrirás de qué manera las organizaciones evalúan la seguridad de los datos usando la tríada CIA, un modelo de seguridad de la información estándar de la industria. También aprenderás sobre los controles de seguridad de datos utilizados para combatir las amenazas de ciberseguridad. Explorarás en profundidad dos de estos controles, cifrado y copias de seguridad, e incluso practicarás cómo elaborar un plan para las copias de seguridad de los datos. 

## 1. Protección contra Amenazas CrecientesFrecuencia de ataques: Se estima que ocurre un ciberataque cada 39 segundos y se vulneran aproximadamente 30,000 sitios web al día.Objetivos comunes: Sectores como el gubernamental, tecnológico, salud y comercio minorista son blancos frecuentes debido al valor de los datos personales y financieros que almacenan.

## 2. Prevención de Daños Económicos y ReputacionalesCostos millonarios: Una sola filtración de datos puede devastar a una empresa, costando millones de dólares en esfuerzos de recuperación.Pérdida de confianza: Los clientes esperan que se proteja su información sensible (como números de seguridad social o tarjetas de crédito). Si estos datos se vulneran, los consumidores suelen llevar sus negocios a la competencia.Impacto en el consumidor: Para compensar las pérdidas por ataques, muchas organizaciones aumentan sus precios, trasladando el costo al cliente final.

## 3. Inversión Inteligente y ResponsablePresupuesto: Las organizaciones destinan, en promedio, el 10% de su presupuesto de TI exclusivamente a la seguridad.Definición de ciberseguridad: Se define como la práctica de proteger y recuperar datos, redes, dispositivos y programas frente a ataques maliciosos.Responsabilidad ética: Más allá del costo, es una elección responsable para evitar que la información confidencial de los clientes caiga en manos de delincuentes que podrían venderla o realizar fraudes.🛠️ Herramientas de Inteligencia (Contexto STIX)Para gestionar estas amenazas de forma profesional, se utilizan estándares como STIX, que organiza la información en objetos específicos para identificar quién ataca y cómo:Actores y Métodos: Se identifican los Threat Actors (quién), sus Attack Patterns (tácticas) y el Malware o Tools que utilizan.Respuesta: Se definen Courses of Action (planes de respuesta) para mitigar las Vulnerabilities detectadas.

* OPINION PERSONAL: 
## "La ciberseguridad es una inversión inteligente y una elección responsable. En un mundo donde gestionamos casi todo a través de Internet (desde salud hasta finanzas), las organizaciones deben garantizar que esa conexión no se convierta en una vulnerabilidad que devaste su reputación o su economía."

En resumen, las empresas tienen que invertir en ciberseguridad porque el costo potencial de una filtración supera el precio de una buena ciberseguridad. Cuando se produce una violación, el tiempo perdido y los esfuerzos de recuperación pueden costar cantidades extraordinarias de dinero. Y la reducción de la reputación de la empresa y de la confianza de los clientes puede ser igual de perjudicial. Un tercio de los consumidores llevarán su negocio a otra parte. Pero con una buena ciberseguridad, las organizaciones pueden evitar las violaciones de seguridad y limitar los daños si se producen.

## ----------------------Amenazas de ciberseguridad-------------------------------------------

* Una amenaza es todo aquello que pueda provocar que algo perjudicial ocurra en tu red, sistemas o datos 

🧱 Pilares de la Seguridad: Conceptos Fundamentales
Para gestionar el riesgo de forma efectiva, es necesario distinguir claramente entre estos cuatro elementos:

1. Amenaza (Threat)
Cualquier evento o acción que tiene el potencial de causar daño a la red, los sistemas o los datos de una organización.

2. Vulnerabilidad (Vulnerability)
Es una debilidad específica en el hardware, firmware o software que puede ser explotada por un atacante.

Ejemplo crítico: El uso de dispositivos obsoletos que ya no reciben soporte del fabricante, lo que genera fallas persistentes.

3. Atacantes y Hackers
Hacker: Individuo que intenta eludir la seguridad para acceder a datos.

Atacante (Ciberatacante): Un hacker que actúa sin autorización y con fines maliciosos, como el robo de dinero, la interrupción de procesos de negocio o la destrucción de información.

Método común: Ingeniería social, como el envío de correos falsos (phishing) para obtener contraseñas.

4. Malware (Software Malicioso)
Código diseñado para realizar acciones no autorizadas que afectan la seguridad del sistema.

Troyano: Un programa que parece legítimo (como un juego o fondo de pantalla) pero que oculta código malicioso para dar control remoto al atacante.

Tipos comunes: Virus, gusanos y ransomware.

### 🔑 Glosario Técnico de Seguridad

En el marco de la Gobernanza y el Riesgo, utilizo estas definiciones estándar para categorizar incidentes:

| Concepto | Definición |
| :--- | :--- |
| **Amenaza** | Todo evento potencial que pueda provocar un impacto perjudicial en los activos. |
| **Vulnerabilidad** | Debilidad técnica (Hardware/Software) que sirve como punto de entrada. |
| **Atacante** | Actor que explota vulnerabilidades con fines maliciosos (lucro, sabotaje). |
| **Malware** | Herramienta técnica (Software/Firmware) usada para comprometer sistemas. |

> **Caso de Estudio Interno:** El uso de software sin soporte (Legacy) incrementa la superficie de ataque al mantener vulnerabilidades que los atacantes pueden explotar mediante malware tipo Troyano o técnicas de Phishing.

## ------------------------------------Elementos clave de la ciberseguridad----------------------------

## La ciberseguridad implica múltiples capas de protección. Las organizaciones deben considerar tres elementos clave: personas, procesos y tecnología. 

## 🛡️ Las Tres Capas de la Ciberseguridad (PPT)
Un enfoque de seguridad robusto no depende solo de herramientas técnicas, sino de la interacción armoniosa entre tres elementos clave:

1. Personas (El factor más crítico)
Las personas son los responsables del diseño, mantenimiento y control de los sistemas de seguridad.

* El eslabón débil: Cualquier empleado, por falta de conocimiento o descuido, puede abrir una puerta a un atacante.

* Capacitación: Es vital que cada trabajador reciba formación específica según su rol y sector para tomar la seguridad con la seriedad necesaria.

2. Procesos (Las reglas del juego)
Son las actividades y pasos definidos que guían cómo se debe actuar de forma segura. Para ser efectivos, los procesos deben ser:

* Claros y fáciles: Evitan la frustración del usuario.

* Accesibles: Deben ser conocidos por todos, similar a la señalización de una salida de incendios.

* Coherentes: No deben contradecirse ni tener demasiadas excepciones que aumenten la complejidad.

3. Tecnología (Las herramientas)
Incluye la infraestructura y el software diseñado para proteger los activos.

* Ejemplos: Firewalls, seguridad de correo electrónico y software anti-malware.

* Implementación invisible: La buena tecnología debe ser no intrusiva. Si es molesta o difícil de usar, los usuarios intentarán deshabilitarla, creando nuevos riesgos.

### 📐 El Triángulo de la Ciberseguridad: Personas, Procesos y Tecnología

Para que la gobernanza sea efectiva, implemento una estrategia basada en tres pilares:

| Pilar | Rol en la Organización | Objetivo de Seguridad |
| :--- | :--- | :--- |
| **Personas** | Usuarios, administradores y analistas. | Concientización y reducción del error humano. |
| **Procesos** | Políticas y pasos estandarizados. | Operaciones claras, coherentes y accesibles. |
| **Tecnología** | Firewalls, EDR, SIEM y parches automáticos. | Protección no intrusiva y resolución de problemas. |

> **Nota de Analista:** La tecnología por sí sola no es suficiente. Un sistema técnico perfecto puede ser vulnerado si el factor humano (Personas) no está capacitado o si los protocolos (Procesos) son tan complejos que el usuario decide ignorarlos.

## 🚀 ¿Cómo se conecta esto con el SOC?
Como Analista SOC, vos sos la Persona que opera la Tecnología (el SIEM) siguiendo un Proceso (el Playbook de respuesta).

## Aplicar los elementos clave


## 🏠 La Ciberseguridad en el Hogar (Marco PPT)
La seguridad de tu red personal depende de cómo administrás estos tres componentes:

1. Personas: El factor de conocimiento
La seguridad empieza por quién configura y quién usa la red.

* Configuración: El nivel de conocimiento de quien instala el router determina si la red nace protegida (ej. con contraseñas seguras).

* Hábitos: Los miembros del hogar deben saber navegar de forma segura, detectar phishing y mantener sus dispositivos actualizados.

* Eliminación de datos: Es clave destruir de forma segura papeles o dispositivos que contengan contraseñas e información delicada.

2. Procesos: Las reglas de la casa
Son las normas y la facilidad con la que se gestiona la seguridad.

* Gestión de contraseñas: La complejidad de la clave del Wi-Fi y qué tan fácil (o inseguro) es compartirla con nuevos dispositivos.

* Manuales de usuario: La claridad de las instrucciones del enrutador para cambiar la clave de administrador por defecto y fortalecer la seguridad.

3. Tecnología: Las herramientas de defensa
Son las decisiones técnicas que tomás para proteger el tráfico y los dispositivos.

* Acceso y Cifrado: Decidir si la red requiere contraseña y si se utilizará una VPN para cifrar el tráfico.

* Superficie de ataque: A mayor cantidad de dispositivos conectados, más objetivos tiene un atacante para intentar entrar.

* Defensas individuales: El uso de firewalls y software contra malware en cada computadora o celular de la casa.

### 🏠 Aplicación del Marco PPT en Redes Domésticas

La seguridad no es exclusiva del entorno corporativo. En el hogar, la tríada de protección se manifiesta de la siguiente manera:

| Elemento | Aplicación Práctica en el Hogar |
| :--- | :--- |
| **Personas** | Educación de los convivientes en detección de phishing y gestión de contraseñas. |
| **Procesos** | Políticas de cambio de claves de administrador en el router y protocolos de actualización de firmware. |
| **Tecnología** | Implementación de WPA3, uso de VPNs y despliegue de firewalls en dispositivos finales. |

> **Reflexión de Analista:** La "Superficie de Ataque" en casa crece con cada dispositivo IoT (Smart TVs, cámaras, luces). Si las **Personas** no tienen el hábito de actualizar y la **Tecnología** no tiene un firewall activo, el **Proceso** de seguridad falla.

## Aspecto destacado de la gestión profesional: Trayectoria profesional en ciberseguridad.

📈 Panorama y Oportunidades en Ciberseguridad
El crecimiento exponencial de las amenazas ha generado una demanda de profesionales sin precedentes. Este campo ofrece no solo estabilidad, sino también una alta satisfacción laboral.

📊 Datos del Sector:
* Déficit de Talento: Actualmente trabajan unos 5.5 millones de profesionales en el mundo, pero aún existen 4 millones de vacantes sin cubrir.

* Reconocimiento: El puesto de Ingeniero de Ciberseguridad ocupa el n.º 7 en la lista de los 100 mejores empleos, basada en potencial de ingresos y satisfacción.

* Versatilidad: La demanda supera al sector tecnológico; instituciones financieras, de salud, manufactura y obras públicas requieren equipos de seguridad robustos.

🎓 Perfil del Profesional:
* Diversidad de Origen: No siempre se requiere un título tradicional de cuatro años; los profesionales provienen de diversos trasfondos y etapas de su carrera.

* Responsabilidad: El rol central es detectar, abordar y prevenir delitos cibernéticos mediante habilidades técnicas y características personales analíticas.

* Crecimiento: Existe una progresión clara que va desde técnicos principiantes hasta funcionarios de seguridad de alto nivel (CISO).

### 📈 Perspectivas de la Carrera en Ciberseguridad

Mi formación se alinea con una de las industrias más dinámicas y demandadas globalmente. La ciberseguridad representa una oportunidad estratégica debido a:

* **Alta Demanda Global:** Con un déficit de 4 millones de profesionales, el mercado valora la especialización técnica y la capacidad de respuesta ante incidentes.
* **Impacto Multisectorial:** Mi perfil como Analista es aplicable en finanzas, salud y manufactura, sectores críticos que priorizan la protección de sus activos digitales.
* **Compromiso Profesional:** Mi objetivo es contribuir a la prevención del cibercrimen, evolucionando desde roles técnicos operativos hacia posiciones de gestión de seguridad de alto nivel.

> **Dato Clave:** La ingeniería de seguridad de la información es considerada uno de los 10 mejores trabajos gracias a su equilibrio entre remuneración y propósito profesional.

🗺️ Hoja de Ruta Profesional en Ciberseguridad
La carrera en ciberseguridad ofrece una progresión estructurada basada en la experiencia y la especialización técnica:

1. Técnico de Seguridad de la Información (Nivel Inicial: 0—2 años)
Es el punto de partida donde se desarrollan las bases operativas:

* Funciones: Instalación y gestión de herramientas de seguridad, reporte de eventos detectados y soporte técnico a usuarios para identificar amenazas.

* Enfoque: Solución de problemas de software/hardware y asistencia directa en la higiene de seguridad de la organización.

2. Especialista en Ciberseguridad (Nivel Medio: 3—5 años)
En esta etapa, el rol se vuelve más analítico y preventivo:

* Funciones: Garantizar la integridad y disponibilidad de los datos y sistemas.

* Enfoque: Revisión de evaluaciones de riesgo y vulnerabilidad, proponiendo mejoras activas a la postura de seguridad.

3. Director de Ciberseguridad (Nivel Gerencial: +5 años)
Es un rol de liderazgo y visión global:

* Funciones: Liderar equipos de profesionales de seguridad y supervisar la respuesta ante incidentes.

* Enfoque: Monitoreo de la estrategia organizacional, arquitectura de sistemas y administración general de la seguridad.

### 🎯 Mi Roadmap Profesional

He definido mi trayectoria profesional siguiendo los estándares de la industria, aprovechando mi formación previa en Sistemas y mis estudios actuales en la UGR:

1. **Fase Actual (Entry Level):** Busco consolidarme como **Técnico de Seguridad**, enfocándome en la gestión de herramientas (SIEM, Firewalls) y la respuesta inicial ante eventos detectados.
2. **Meta a Mediano Plazo:** Evolucionar hacia el rol de **Especialista**, participando activamente en la gestión de riesgos y el análisis de vulnerabilidades para fortalecer la infraestructura.
3. **Visión a Largo Plazo:** Proyectarme hacia posiciones de **Dirección de Ciberseguridad**, donde pueda liderar equipos técnicos y definir arquitecturas de seguridad estratégicas para organizaciones de alta complejidad.

> **Habilidades en desarrollo:** Monitoreo de eventos, reporte de amenazas, resolución de problemas de hardware/software de seguridad y análisis de integridad de datos.

### 👤 Sobre mí y mi Visión en Ciberseguridad

Como profesional con formación en **Análisis de Sistemas**, mi transición hacia la ciberseguridad está motivada por el deseo de aplicar mi conocimiento técnico en la protección de activos críticos.

* **Objetivo:** Desarrollarme como **Hacker de Sombrero Blanco** para detectar y prevenir delitos cibernéticos mediante el análisis proactivo de fallos de seguridad.
* **Enfoque:** Combino el interés por el hardware y software con la resolución de desafíos técnicos de alta complejidad.
* **Compromiso:** Ayudar a reducir el déficit de talento global, aportando mi capacidad de análisis y mi compromiso con el aprendizaje continuo para enfrentar ataques que ocurren cada **39 segundos**.

> "Busco transformar mi curiosidad técnica en una herramienta de defensa que garantice la integridad y confidencialidad de la información en un mundo hiperconectado."

## Ampliar para ver más ideas
La gente entra en el campo de la ciberseguridad por varias razones. Repasemos algunas de las razones comunes que podrías incluir en tu respuesta: 

* Gran demanda. Como ya sabes, las cifras muestran que las organizaciones tendrán una necesidad enorme de profesionales de la ciberseguridad durante la próxima década. Además, los empleos de ciberseguridad suelen ir acompañados de excelentes salarios y beneficios. 

* Oportunidades de ascenso. También aprendiste que a medida que aumentan tus conocimientos y experiencia en ciberseguridad, también lo hacen tus posibilidades de ascender a puestos de mayor responsabilidad. Estos puestos suelen estar mejor remunerados y gozar de mayor prestigio. 

* Campo diverso. Si te interesa la tecnología, la ciberseguridad es un campo apasionante, y los conocimientos técnicos son esenciales para muchos puestos. Pero la diversidad de los puestos de ciberseguridad requiere una gran diversidad de aptitudes. Como la ciberseguridad es tan amplia, los empresarios buscan talentos en muchas áreas, como la gestión, la comunicación y las matemáticas. Ten en cuenta que hay mucha educación y capacitación disponible para cualquiera que quiera avanzar en este campo. 

* Aprendizaje continuo. A medida que evoluciona la tecnología, también lo hacen los métodos de los atacantes cibernéticos. Los profesionales de la ciberseguridad deben estar actualizados con respecto a ambas cosas. Si te gusta aprender sobre nuevas tecnologías y tendencias, la ciberseguridad te resultará atractiva e intelectualmente gratificante.

## --------------------------------------Datos-----------------------------------------------

## Manejas datos a diario: texto, números, medidas, estadísticas, hechos e imágenes son solo algunos ejemplos. Y provienen de muchas fuentes diferentes, como computadores, teléfonos inteligentes, redes, encuestas en línea y redes sociales, entre muchas otras. 

## 👤 ¿Qué es la PII y por qué es el "Tesoro" de los Atacantes?
La PII es cualquier dato que pueda usarse para distinguir o rastrear la identidad de un individuo. Como bien leíste, estos datos están repartidos en diferentes sectores:

* Datos de Gobierno: Identificadores únicos (DNI, CUIL/CUIT, Seguridad Social). Son la base del robo de identidad.

* Datos de Salud: Es información Sensible. Un diagnóstico médico filtrado puede causar discriminación o extorsión.

* Datos Financieros: El objetivo principal para el fraude bancario inmediato.

* Datos de Redes Sociales: Aquí los atacantes obtienen el "contexto" para ataques de Ingeniería Social. Saber dónde trabajaste o a qué le das "like" les permite armar correos de phishing muy creíbles.

## Las siglas *PII* significan Personally Identifiable Information  (en español, Información de Identificación Personal)

## Se puede  definir a *PII* como el "activo crítico" que las leyes de privacidad (como la Ley de Protección de Datos Personales en Argentina o la GDPR en Europa) obligan a las organizaciones a proteger mediante cifrado y controles de acceso estrictos.

