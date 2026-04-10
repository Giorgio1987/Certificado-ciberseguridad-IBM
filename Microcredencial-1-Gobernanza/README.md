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

## Tipos de datos

* Los expertos en seguridad clasifican los datos por su nivel de sensibilidad. 

### 🏷️ Clasificación de Datos y Niveles de Sensibilidad

Como parte de la estrategia de GRC, clasifico la información para determinar los controles de seguridad necesarios:

* **Datos Públicos:** Información de libre distribución.
* **Datos Confidenciales:** Información que requiere control de acceso (ej. Código Fuente).
* **Datos de Propiedad Exclusiva:** Activos que otorgan ventaja competitiva (ej. Secretos comerciales).
* **Datos Privados:** Información personal que se subdivide en:
    * **PII (Personally Identifiable Information):** Identificadores como DNI, domicilio o fotos.
    * **PHI (Protected Health Information):** Datos médicos sensibles (recetas, diagnósticos).

> **Regla de Oro:** Todo dato **PHI** es también **PII**, pero no toda la **PII** es **PHI**. La protección de estos datos privados es la máxima prioridad para evitar implicancias legales y daños a las personas.

🚀 ¿Viste la diferencia?
Imaginalo así:

El manual de usuario de un producto es Público.

El plan de ventas del año que viene es Propiedad Exclusiva.

El recibo de sueldo de un empleado es Privado (PII).

El resultado de un análisis de sangre de un cliente es Privado (PHI).

## 🗄️ La "Mamushka" de la Clasificación de Datos
Para que te sea fácil de recordar imaginalo como un sistema de carpetas una dentro de otra:

* Datos Confidenciales (La carpeta más grande): Es el término paraguas. Todo lo que la empresa no quiere que se filtre es confidencial. Aquí dentro guardamos tanto los secretos de la empresa (Propiedad Exclusiva) como la información de la gente (Privados).

* Datos Privados (La subcarpeta): Dentro de lo confidencial, están los datos de las personas. Solo se pueden tocar con autorización.

* PII y PHI (El contenido específico): Dentro de lo privado, clasificamos si el dato sirve para identificar a alguien (PII) o si además es un dato de salud (PHI).


* Dato: Dirección Postal,¿Por qué encaja?
Es PII,Porque permite localizar e identificar a un individuo específico.
Es Privada,Porque pertenece a la vida íntima y su divulgación requiere consentimiento legal.
Es Confidencial,Porque la organización tiene la obligación de protegerla contra el acceso no autorizado.

## 🔑 Regla Nemotécnica para el Analista:
"Todo dato PII es Privado, y todo dato Privado es Confidencial. Pero no todo lo Confidencial es PII (por ejemplo, el código fuente de un software es confidencial pero no es PII)."

🚀 ¿Por qué te sirve saber esto en el SOC?
Cuando recibas una alerta de seguridad que diga: "Se ha filtrado una base de datos con direcciones de clientes", ya sabés que tenés un triple problema:

Violación de Confidencialidad (falla técnica).

Violación de Privacidad (falla legal).

Exposición de PII (riesgo directo para la persona).

## --------------------------------Protección de datos--------------------------------------
### ⚖️ Seguridad de Datos vs. Privacidad de Datos

Para una gobernanza efectiva, distingo entre los mecanismos de defensa y los derechos de los individuos:

1. **Seguridad de Datos:** El conjunto de medidas técnicas para prevenir el acceso, divulgación o destrucción no autorizada de **cualquier activo de información** de la empresa (incluyendo propiedad exclusiva y secretos comerciales).
2. **Privacidad de Datos:** Una disciplina específica de la seguridad enfocada en garantizar que los **datos privados de personas** (clientes y empleados) se recolecten y utilicen únicamente bajo autorización y para los fines permitidos.

> **Reflexión de Analista:** Podés tener seguridad sin privacidad (por ejemplo, los datos están bien guardados pero la empresa los vende sin permiso), pero **no podés tener privacidad sin seguridad** (si no protegés los datos, cualquiera puede violar la privacidad de los usuarios).

## 🚀 ¿Viste la relación?
Como hacker de sombrero blanco, tu trabajo técnico suele estar más del lado de la Seguridad (cerrar brechas), pero las leyes te obligan a trabajar para la Privacidad (que esos datos de personas no queden expuestos).

## Por qué es importante la privacidad de los datos

### 🚨 El Costo de Ignorar la Privacidad

La privacidad de los datos es un pilar estratégico. Una violación en este ámbito no es solo un problema técnico, sino una crisis multiforme:

* **Impacto Financiero:** Sanciones regulatorias masivas y costos de remediación inesperados.
* **Impacto Operativo:** Parálisis de los procesos de negocio y desvío de recursos críticos para la recuperación de sistemas.
* **Impacto Reputacional:** Pérdida definitiva de la confianza del consumidor, el activo más difícil de reconstruir.

> **Caso de Estudio:** Mientras que la *Seguridad* evita que el hacker entre, la *Privacidad* garantiza que, si los datos se usan, se haga bajo el marco legal. Fallar en cualquiera de las dos puede resultar en la quiebra de la organización.

![EQUIFAX](/img/equifax.png)

### 🔎 Caso de Estudio: La Filtración de Equifax , agencia de calificación crediticia de EE. UU.(2017)

Este caso demuestra que la ciberseguridad es una inversión inteligente frente al costo devastador de una filtración.

* **La Falla:** No se aplicó un parche de seguridad conocido y se almacenaron credenciales administrativas sin cifrado.
* **Datos Comprometidos (PII):** * 147 millones de nombres y fechas de nacimiento.
    * 145.5 millones de números de seguridad social.
    * 209,000 números de tarjetas de pago.
* **Consecuencia Principal:** Multas de hasta $700 millones y pérdida total de la confianza del consumidor.

> **Lección para el Analista:** Una sola filtración puede devastar una organización. La ciberseguridad no es un gasto, es una elección responsable para evitar que los datos caigan en manos equivocadas.

### ⚠️ Lección de GRC: El Caso Equifax (Análisis de Consecuencias)

Este caso demuestra que la falta de un parche de seguridad y el almacenamiento de credenciales sin cifrado generan un efecto dominó:

1. **Financiero:** Multas y acuerdos que superan los 425M USD.
2. **Operativo:** Parálisis de la innovación para enfocarse en la remediación y auditoría de políticas.
3. **Reputacional:** Daño permanente a la marca por falta de transparencia y soporte deficiente.

> **Conclusión del Analista:** La ciberseguridad es una inversión inteligente. El 10% del presupuesto de TI en seguridad es mínimo comparado con el costo de una filtración que puede devastar la reputación y las finanzas de una organización.

GRC significa Governance, Risk, and Compliance (en español: Gobernanza, Riesgo y Cumplimiento).

Es el marco de trabajo que asegura que una organización actúe con integridad y alcance sus objetivos de seguridad de manera ordenada. Imaginalo como el "cerebro" estratégico que decide qué tecnologías y procesos se deben usar.

Aquí detallo qué significa cada letra:

🏛️ G - Gobernanza (Governance)
Es el conjunto de reglas y políticas que dirigen a la organización.

Define quién toma las decisiones y quién es responsable de la seguridad.

Asegura que los esfuerzos de ciberseguridad ayuden a los objetivos del negocio y no sean solo "instalar programas".

📉 R - Riesgo (Risk Management)
Es el proceso de identificar y manejar las posibles amenazas antes de que se conviertan en desastres.

Se analizan las vulnerabilidades (como el parche que no aplicó Equifax) y el impacto que tendrían si alguien las explota.

Ayuda a decidir dónde invertir el presupuesto de seguridad (ese 10% del que hablamos) de forma inteligente.

⚖️ C - Cumplimiento (Compliance)
Se encarga de que la empresa siga todas las leyes y regulaciones externas.

Por ejemplo, asegurar que se cumplan las leyes de Privacidad de Datos para proteger la PII de los clientes.

Evita las consecuencias financieras (multas de millones de dólares) y legales que vimos en el caso de Equifax.

## 📜 Los 10 Principios de Privacidad (GAPP)
Estos principios aseguran que la privacidad esté presente en todo el ciclo de vida del dato:

* Gestión: La organización debe tener políticas claras y personas responsables de la privacidad.

* Notificación: Se debe informar al usuario sobre qué datos se recopilan y para qué se usan.

* Elección y consentimiento: El usuario debe poder elegir si quiere compartir sus datos y dar su autorización explícita.

* Recopilación: Solo se deben recolectar los datos necesarios para los fines informados.

* Uso, retención y eliminación: Los datos solo se usan para lo acordado, se guardan el tiempo necesario y luego se destruyen de forma segura.

* Acceso: Los usuarios tienen derecho a ver, revisar y corregir su información personal.

* Divulgación a terceros: Los datos solo se comparten con terceros si el usuario lo autorizó o si la ley lo exige.

* Seguridad para la privacidad: Se deben usar medidas técnicas (como cifrado y firewalls) para proteger los datos de accesos no autorizados.

* Calidad: La organización debe asegurar que la información personal sea exacta y completa.

* Supervisión y cumplimiento: Se deben realizar auditorías internas y tener mecanismos para resolver quejas de los usuarios.

### ⚖️ Principios GAPP: El Estándar de Privacidad Organizacional

Para garantizar que una organización cumple con la ética y la ley, sigo los 10 principios del estándar **GAPP** (Generally Accepted Privacy Principles):

* **Transparencia:** Notificación clara y obtención de consentimiento antes de la recopilación.
* **Limitación:** Recopilar y usar solo lo necesario (Minimización de datos).
* **Protección:** Aplicar controles de seguridad técnica para salvaguardar la PII/PHI.
* **Derechos del Usuario:** Facilitar el acceso, corrección y eliminación de los datos por parte de sus dueños.

> **Importancia para el Analista:** Aplicar GAPP reduce drásticamente el riesgo de **consecuencias financieras y reputacionales** como las ocurridas en el caso Equifax, donde fallaron principios básicos de seguridad y notificación oportuna.

### 💼 Perfiles Profesionales en el área de Privacidad

Dentro de mi formación, identifico tres rutas de especialización según el enfoque de la organización:

| Rol | Enfoque Principal | Responsabilidad Clave |
| :--- | :--- | :--- |
| **Especialista** | Normativo y Auditoría. | Garantizar el cumplimiento de leyes y regulaciones. |
| **Analista** | Técnico y Operativo. | Desarrollar controles automatizados y supervisar la infraestructura. |
| **Administrador** | Estratégico y Humano. | Mapear flujos de datos y liderar la concientización organizacional. |

> **Mi Perfil:** Gracias a mi base en Análisis de Sistemas, tengo una afinidad natural hacia el rol de **Analista de Privacidad**, donde puedo aplicar controles técnicos para evitar accesos no autorizados y participar en la respuesta ante incidentes.

### 🛠️ Habilidades Profesionales (Soft Skills)

Para complementar mi formación técnica, he desarrollado competencias clave que aseguran una gestión de privacidad eficiente:

* **Gestión del Tiempo:** Capacidad para planificar y ejecutar auditorías y controles en tiempo y forma.
* **Colaboración:** Orientado al trabajo en equipo y a la articulación entre áreas técnicas y administrativas.
* **Comunicación y Auditoría:** Experiencia en la elaboración de informes técnicos y disposición para asumir roles de auditoría y control de cumplimiento.

> **Perfil del Analista:** Mi enfoque organizado y mi disposición para la auditoría me permiten asegurar que los marcos de privacidad (como GAPP) se mantengan vigentes y operativos dentro de la organización.

## Ampliar para ver más ideas
## Tu respuesta podría incluir algunas de las siguientes habilidades: 

Atención al detalle: Los profesionales de la ciberseguridad deben ser meticulosos y prestar mucha atención a los detalles. Hasta el más mínimo descuido puede dejar un sistema vulnerable a un ataque. Las personas que son detallistas en su vida personal, como las que disfrutan organizando o planificando eventos, podrían encontrar que sus habilidades se trasladan bien a una carrera en ciberseguridad. 

Resolución de problemas: La ciberseguridad requiere una gran capacidad para resolver problemas. Los profesionales deben estar constantemente atentos a las nuevas amenazas e idear soluciones innovadoras para evitar los ataques. Las personas a las que les gustan los rompecabezas o tienen experiencia en otros campos de resolución de problemas, como la ingeniería o las matemáticas, podrían encontrar que sus habilidades son valiosas para la ciberseguridad. 

Comunicación: Una buena capacidad de comunicación es esencial en ciberseguridad, porque los profesionales a menudo deben explicar conceptos técnicos complejos a partes interesadas sin conocimientos técnicos. Las personas que son buenas para explicar, como los docentes o los presentadores públicos, podrían encontrar que sus habilidades son muy valiosas para desarrollarse profesionalmente en el campo de la ciberseguridad. Además, las personas capaces de comunicar eficazmente, más allá de las barreras culturales y lingüísticas, pueden resultar especialmente valiosas en el panorama mundial de la ciberseguridad. 

## CIA 
### 🛡️ La Tríada CIA: Marco de Evaluación de Riesgos

En mi práctica como analista, utilizo la Tríada CIA como la piedra angular para identificar vulnerabilidades y proponer soluciones:

| Pilar | Definición | Aplicación de Sombrero Blanco |
| :--- | :--- | :--- |
| **Confidencialidad** | Solo personal autorizado accede al dato. | Implementación de cifrado para proteger PII/PHI. |
| **Integridad** | El dato es veraz y no ha sido alterado. | Uso de Hashes para verificar que el software no fue modificado. |
| **Disponibilidad** | El sistema funciona cuando se requiere. | Planes de recuperación ante desastres y mantenimiento preventivo. |

> **Reflexión:** Un programa de seguridad exitoso es aquel que logra el equilibrio entre estos tres objetivos. Si priorizo demasiado la confidencialidad (poniendo 10 contraseñas), puedo terminar afectando la disponibilidad.

## Nota: El origen del término tríada CIA es difícil de determinar. Pero sus conceptos guiaron a generales militares durante siglos, incluso a Julio César durante las guerras de las Galias.

### 📋 Parámetros de Auditoría para Datos Confidenciales

Como Analista, evalúo la postura de seguridad basándome en el ciclo de vida de la información:

| Parámetro | Pregunta Clave de Auditoría | Objetivo CIA |
| :--- | :--- | :--- |
| **Identificación** | ¿Qué datos específicos son confidenciales (PII/PHI)? | Confidencialidad |
| **Almacenamiento** | ¿El repositorio cuenta con cifrado en reposo (at rest)? | Confidencialidad / Integridad |
| **Acceso** | ¿Se aplica el control de acceso basado en roles (RBAC)? | Confidencialidad |
| **Flujo** | ¿Los datos están protegidos durante el tránsito (in transit)? | Confidencialidad / Integridad |
| **Monitoreo** | ¿Existe trazabilidad (logs) de quién accedió al dato? | Disponibilidad / Integridad |

> **Enfoque Práctico:** En mi laboratorio virtual con Windows Server y Linux, aplico estos parámetros al configurar **Dominios** y **Permisos de Archivos**, asegurando que el flujo de datos sea siempre visible y controlado.

![controles](/img/controles.png)

### 🛠️ Implementación de Controles de Seguridad

Para mitigar riesgos, diseño defensas en profundidad utilizando tres tipos de controles:

| Tipo de Control | Aplicación Práctica | Ejemplo en mi Laboratorio |
| :--- | :--- | :--- |
| **Administrativo** | Políticas de uso aceptable y gestión de claves. | Configuración de directivas de grupo (GPO) en Active Directory. |
| **Físico** | Seguridad perimetral y control de acceso. | Gestión de acceso físico a dispositivos de red. |
| **Técnico** | Herramientas de protección lógica. | Uso de Wireshark para monitoreo y Cifrado BitLocker. |

#### 🔑 Diferencia Crítica: Borrado vs. Eliminación Permanente
En el manejo de **PII**, es fundamental aplicar software de **borrado de datos** (sobreescritura) en lugar de solo eliminar archivos, garantizando que la información sensible sea irrecuperable según los estándares de cumplimiento.

## Prevención de pérdida de datos
## 🎯 Conclusión: Prevención de Pérdida de Datos (DLP)

La **Pérdida de Datos** (Data Loss) ocurre cuando la información confidencial es expuesta a personas no autorizadas, comprometiendo la tríada CIA. Una estrategia **DLP** efectiva es la capacidad organizacional de combinar:

1. **Personas:** Capacitadas para manejar PII/PHI con ética y responsabilidad.
2. **Procesos:** Marcos de trabajo (como GAPP y GRC) que definen el flujo seguro de la información.
3. **Tecnología:** Herramientas que protegen los datos en sus tres estados: **en reposo, en movimiento y en uso**.

> **Misión del Analista:** Implementar controles administrativos, físicos y técnicos para asegurar que el "negocio" sea resiliente ante las amenazas y cumpla con las leyes de privacidad vigentes.

### 🛡️ DLP: Protección en los Tres Estados del Dato

Como Analista, mi objetivo es implementar controles que garanticen la seguridad del dato en todo su ciclo de vida:

| Estado del Dato | Descripción | Control Técnico Sugerido |
| :--- | :--- | :--- |
| **En Reposo** | Almacenado en discos o servidores. | Cifrado de archivos y bases de datos. |
| **En Movimiento** | Viajando a través de redes o internet. | Uso de protocolos seguros (VPN, SSL/TLS). |
| **En Uso** | Procesado activamente en la memoria (RAM). | Gestión segura de identidad y acceso (IAM). |

> **Nota Técnica:** Una filtración como la de **Equifax** ocurrió porque los datos **en reposo** (credenciales) no estaban cifrados y el monitoreo de los datos **en movimiento** falló durante meses.


## 🛡️ Tipos de Sistemas DLP y su Aplicación
Herramientas según el área que protegen:

1. DLP a Nivel de Archivo (Basado en Metadatos)
Este sistema "etiqueta" los archivos. Utiliza los metadatos (información oculta sobre el archivo) para ponerle reglas.

Ejemplo: Un archivo de Excel con salarios tiene un metadato que dice "Prohibido enviar por Email". Si alguien intenta adjuntarlo, el sistema lo bloquea automáticamente.

2. DLP de Red (Network DLP)
Es el "vigilante" del tráfico. Monitorea todo lo que entra y sale de la organización.

Capacidad: Protege datos en reposo, movimiento y uso dentro de la red.

Ejemplo: Si un empleado intenta subir los planos de un nuevo producto (Propiedad Exclusiva) a un sitio de transferencias externo, la DLP de red lo registra y bloquea.

3. DLP en la Nube (Cloud DLP)
Es vital hoy en día, ya que muchas empresas usan Google Drive, OneDrive o AWS.

Función: Detecta datos sensibles y los cifra antes de que lleguen a la nube, asegurando que, aunque la nube sea vulnerada, los datos sigan siendo ilegibles.

4. DLP de Puntos de Conexión (Endpoint DLP)
Se instala directamente en los dispositivos finales (laptops, servidores, PC de escritorio).

Función: Monitorea lo que el usuario hace en su máquina. Por ejemplo, puede bloquear que alguien copie PII a un pendrive USB o que haga una captura de pantalla de información médica protegida (PHI).

### 🛡️ Implementación de Sistemas DLP (Data Loss Prevention)

Para una protección integral de los activos, clasifico y utilizo diferentes soluciones DLP según el entorno:

| Tipo de DLP | Alcance de Protección | Mecanismo de Control |
| :--- | :--- | :--- |
| **A nivel de Archivo** | Documentos específicos. | Uso de **Metadatos** para aplicar reglas de seguridad al archivo. |
| **De Red** | Tráfico de red (Email, Web). | Monitoreo activo de transferencias para evitar filtraciones. |
| **En la Nube** | Repositorios externos (Cloud). | Cifrado preventivo antes del almacenamiento en la nube. |
| **De Endpoints** | Dispositivos finales (Laptops, PC). | Control de puertos USB y actividades locales del usuario. |

> **Rol del Analista:** Mi objetivo es asegurar que las políticas de seguridad se traduzcan en reglas técnicas dentro de estos sistemas, garantizando que el flujo de datos sea siempre legítimo y monitoreado.

### 🎯 Competencias Fundamentales del Analista según mi opinión 

Para garantizar una defensa efectiva de la información, aplico tres habilidades transversales:

1. **Evaluación basada en la Tríada CIA:** Utilizo Confidencialidad, Integridad y Disponibilidad como métricas para auditar cualquier sistema.
2. **Vigilancia Operativa (Alerta Continua):** Monitoreo constante de los cinco parámetros (Acceso, Almacenamiento, Flujo, Monitoreo e Identificación) para detectar anomalías.
3. **Clasificación Estratégica de Datos:** Capacidad para identificar y categorizar PII, PHI y Propiedad Exclusiva, asegurando que los controles de seguridad (DLP) se apliquen de forma eficiente.

> **Mi Enfoque:** Mi formación técnica me permite no solo identificar el riesgo, sino también proponer el control (Administrativo, Físico o Técnico) más adecuado para mitigarlo.

## Ampliar para ver más ideas
Tu respuesta podría incluir algunas de las siguientes habilidades: 

Pensamiento analítico: Los analistas de seguridad de datos deben emplear el pensamiento analítico para detectar posibles amenazas a la seguridad. Por ejemplo, podrían analizar redes informáticas para evaluar los riesgos y luego determinar las mejoras necesarias en las políticas de seguridad para hacerles frente. 

Comunicación escrita: Los analistas de seguridad de datos deben ser expertos en la redacción de estrategias para mejorar la seguridad. Por ejemplo, crean informes que documentan las actualizaciones necesarias del programa de seguridad. También podrían simplificar directrices y prácticas de seguridad complejas en un correo electrónico que envían a los empleados de todos los niveles de una organización. 

Atención al detalle: Los analistas de seguridad de datos deben prestar atención a los detalles cuando auditan el programa de seguridad de una organización. Deben identificar todas las formas sutiles que podría usar un atacante para poner en peligro los datos de una organización, por ejemplo explotando vulnerabilidades en la configuración de seguridad de la red. 

## ----------------------------Cifrado------------------------------------------------------

### 🔑 Cifrado: La última línea de defensa de la Confidencialidad

El cifrado es el proceso de convertir texto en claro en un formato ilegible (texto cifrado) mediante una clave. Es el control técnico por excelencia para mitigar el impacto de una filtración:

* **Protección de PII:** Si los 145 millones de números de seguridad social de Equifax hubieran estado cifrados, los atacantes habrían obtenido datos inútiles.
* **Preservación de la Tríada:** El cifrado garantiza la **Confidencialidad** incluso si el atacante logra romper el parámetro de **Almacenamiento** o **Acceso**.

> **Concepto Clave:** En mi rol de analista, priorizo el cifrado tanto para datos **en tránsito** (vía protocolos como TLS/SSL) como para datos **en reposo** (usando cifrado de disco o base de datos).

![CIFRADO ](/img/cifrado1.png)
![CIFRADO CESAR](/img/cifrado_cesar.png)
![CIFRADO MONOALFABETICO](/img/cifrado_mono.png)
Nota: A menudo se utilizan de manera indistinta los términos cifrar y codificar, pero en ciberseguridad sus significados difieren. El cifrado convierte cada símbolo o carácter en otro símbolo o carácter. En cambio, la codificación convierte unidades de significado mayores, como palabras o frases enteras, en otras palabras o frases. 

Por ejemplo, veamos la siguiente frase Esta información está clasificada. El cifrado César podría convertir cada letra en la letra que se ubica tres lugares después en el alfabeto. El texto cifrado resultante es Hvwd lairqdflrq hvwd fodvlilfdgd. En contraste, en el caso de la codificación se convertiría cada palabra en otra palabra, como Un por Esta, elefante por información, corre por está y libre por clasificada. En este caso, la frase codificada es Un elefante corre libre.

Como el cifrado utiliza algoritmos que actúan sobre caracteres individuales, se puede automatizar con mayor facilidad el cifrado y el descifrado con computadores.  

![DESCIFRADO](/img/desifrado.png)

### 🔑 Fundamentos de Criptografía: Cifrado vs. Codificación

Para entender la protección de datos actual, es vital diferenciar cómo se transforma la información:

* **Cifrado (Encryption):** Actúa sobre símbolos individuales. Es la base de la seguridad informática actual debido a su facilidad para ser automatizado mediante algoritmos.
    * *Ejemplos clásicos:* César, A1Z26, Monoalfabético.
* **Codificación (Coding):** Actúa sobre el significado de palabras o frases completas (lenguaje en clave).

#### 🧪 Ejercicio de Aplicación:
Frase: `Esta información está clasificada`

1. **Cifrado César (+3):** `Hvwd lairqdflrq hvwd fodvlilfdgd`
   * *Uso:* Protección lógica de datos mediante software.
2. **Codificación:** `Un elefante corre libre`
   * *Uso:* Comunicación táctica basada en semántica.

> **Lección de Seguridad:** El cifrado es la herramienta técnica que preserva la **Confidencialidad** en la tríada CIA, permitiendo que solo el poseedor de la clave pueda revertir la transformación.

## 🔨 El Ataque de Fuerza Bruta (Brute Force)
Como bien describe la imagen, este ataque es el método más simple pero más persistente: el ensayo y error.

Cómo funciona: El atacante utiliza scripts automatizados para probar miles (o millones) de combinaciones de contraseñas por segundo hasta que una coincide.

Por qué el cifrado ayuda: Si un atacante intercepta una base de datos cifrada, no solo necesita la contraseña del sistema, sino que tendría que aplicar fuerza bruta para adivinar la clave de descifrado. Esto puede tomar años o incluso siglos con la tecnología actual.

El factor "objetivo poco atractivo": En ciberseguridad hablamos de "elevar el costo del ataque". Si un hacker ve que tus datos están bien cifrados, probablemente busque una víctima más fácil (como ocurrió con Equifax, que tenía credenciales sin cifrar).

🛡️ Beneficios Estratégicos del Cifrado
Más allá de la técnica, el cifrado es una herramienta de gestión de reputación:

Protección contra Intercepción: Si los datos en movimiento (red) son interceptados, el atacante solo ve "galimatías".

Seguridad de los Clientes: Almacenar datos en formato cifrado garantiza que, incluso ante una intrusión física o lógica, la Confidencialidad se mantenga intacta.

Cumplimiento Legal: Muchas normativas exigen el cifrado como estándar mínimo para manejar PII (como esos 145 millones de números de seguridad social de la imagen).

### ⚔️ Amenaza: Ataques de Fuerza Bruta vs. Cifrado

Un **Ataque de Fuerza Bruta** es un método de ensayo y error para adivinar credenciales. Mi estrategia como Analista para mitigar esto incluye:

* **Cifrado Robusto:** Utilizar algoritmos que conviertan los datos en "galimatías" inútiles para el atacante.
* **Políticas de Complejidad:** Implementar requisitos de contraseñas largas y variadas (Control Administrativo) para que el tiempo necesario para un ataque de fuerza bruta sea matemáticamente inviable.
* **Bloqueo de Intentos:** Configurar controles técnicos que bloqueen una cuenta tras X intentos fallidos.

> **Lección del caso Equifax:** La falta de cifrado en las credenciales administrativas permitió que los atacantes tomaran el control total. El cifrado no solo protege el dato, protege la continuidad del negocio y la reputación de la marca.

## 🚀 Reflexión para un "White Hat"
Como sos estudiante de la Universidad del Gran Rosario, recordá que en tus laboratorios de Kali Linux, herramientas como John the Ripper o Hydra se usan justamente para probar la resistencia de las contraseñas mediante fuerza bruta.

¿Viste lo importante que es balancear la técnica con la estrategia? El cifrado es la herramienta, pero la política de seguridad (Gobernanza) es la que decide dónde y cómo usarla.

## 🔑 ¿Cómo funciona el Cifrado de Clave Pública?
A diferencia de los métodos clásicos que vimos (como el César), donde se usa la misma clave para cifrar y descifrar, aquí cada usuario tiene un par de claves matemáticas vinculadas:

## Clave Pública: Es como tu dirección de correo o tu CBU; se puede compartir con todo el mundo. Se utiliza para cifrar el mensaje.

## Clave Privada: Es como la contraseña de tu cuenta; solo vos la tenés y nadie más debe conocerla. Se utiliza para descifrar el mensaje.

El flujo lógico es:

Si yo quiero enviarte un mail, busco tu clave pública y cifro el mensaje con ella.

Una vez cifrado, ese mail es un "galimatías" que viaja por internet.

Solo vos, con tu clave privada, podés abrirlo y leerlo.

### 📧 Cifrado de Clave Pública (Asimétrico)

Para proteger los **datos en movimiento** (especialmente correos electrónicos), implementamos el cifrado asimétrico. Este método es fundamental para garantizar que el mensaje solo sea leído por el destinatario legítimo.

* **Dato en Tránsito:** El correo electrónico mientras viaja del remitente al destinatario.
* **Mecanismo:** * Se utiliza la **Clave Pública** del destinatario para cerrar el candado (cifrar).
    * Se utiliza la **Clave Privada** del destinatario para abrir el candado (descifrar).

> **Importancia técnica:** Este método resuelve el problema de cómo compartir claves de forma segura a través de internet, algo que el cifrado simétrico tradicional no puede hacer fácilmente.

## ✉️ El paso a paso del envío seguro:
Tu amigo te da su "candado": Tu amigo tiene dos claves. Él publica su Clave Pública (imaginala como un candado abierto que cualquiera puede usar).

Vos cerrás el mensaje: Cuando le escribís, vos usás la Clave Pública de tu amigo para cifrar el correo. Una vez que hacés esto, el mensaje se transforma en "galimatías".

El viaje: El correo viaja por internet cifrado. Si un hacker lo intercepta, no puede hacer nada porque no tiene la llave.

Tu amigo abre el mensaje: Solo tu amigo tiene la Clave Privada (la única llave que abre ese candado específico). Él la usa para descifrar el mensaje y leerlo.

## 💡 La analogía del Buzón:
Para que no te olvides nunca, pensalo así:

Clave Pública: Es como la ranura del buzón de tu amigo. Cualquiera puede pasar por la calle y meter una carta (cifrar), pero una vez que la carta cae adentro, ya nadie puede sacarla.

Clave Privada: Es la llave de la puertita trasera del buzón. Solo tu amigo tiene esa llave para sacar las cartas y leerlas (descifrar).

📝 Resumen:
"En el cifrado asimétrico, el emisor cifra el mensaje utilizando la clave pública del receptor. De esta manera, se garantiza que solo el poseedor de la clave privada correspondiente (el receptor legítimo) pueda acceder a la información original."

## 🛡️ Las 3 Funciones del Cifrado de Red Moderno
Cuando los datos viajan (en movimiento) entre un servidor y un cliente (como tu PC), estos algoritmos garantizan lo siguiente:

1. Autenticación (¿Sos quién decís ser?)
Asegura que el origen del mensaje es legítimo.

* Cómo funciona: El sistema verifica certificados digitales (como el candadito de las webs), contraseñas o biometría antes de permitir el acceso.

* Para el Analista: Evita que un atacante suplante la identidad de un servidor bancario o de una base de datos corporativa.

2. Integridad (¿Alguien cambió el mensaje?)
Verifica que los datos no hayan sido alterados durante el viaje.

* Cómo funciona: Los algoritmos generan firmas digitales o códigos MAC. Si un solo bit cambia en el camino, la firma ya no coincide y el sistema descarta los datos.

* Para el Analista: Es vital para transacciones financieras o actualizaciones de software; asegura que el archivo que descargaste es exactamente el que envió el autor.

3. No Rechazo o No Repudio (Yo no fui...)
Garantiza que ninguna de las partes pueda negar que participó en la transmisión.

* Cómo funciona: El remitente tiene una prueba de que el mensaje se entregó y el receptor tiene una prueba de quién lo envió.

* Para el Analista: Esto es esencial para temas legales y contratos digitales. Si enviás una orden de compra cifrada, no podés decir después "yo no la envié".

### 🌐 Cifrado de Red y Garantías de Seguridad

El cifrado moderno ha evolucionado más allá del estándar **DES** (hoy considerado inseguro/obsoleto) para ofrecer una arquitectura de confianza completa:

* **Autenticación:** Validación de identidad mediante certificados digitales y biometría.
* **Integridad:** Uso de firmas digitales y códigos MAC para asegurar que el dato no fue modificado en tránsito.
* **No Rechazo:** Garantía técnica de que ni el emisor ni el receptor pueden negar la transacción (evidencia digital).

> **Contexto Técnico:** Estos pilares son los que permiten que iniciativas de seguridad modernas sean confiables, protegiendo no solo la privacidad del dato, sino la validez de la operación completa.

### ⚖️ Comparativa: Algoritmos Simétricos y Asimétricos

En la implementación de controles técnicos, distingo entre dos arquitecturas de cifrado:

#### 1. Cifrado Simétrico (Clave Única)
* **Algoritmo:** **AES** (Advanced Encryption Standard).
* **Ventaja:** Alta velocidad de procesamiento.
* **Desafío:** La distribución segura de la clave; si el atacante intercepta la clave privada compartida, la confidencialidad se rompe.

#### 2. Cifrado Asimétrico (Par de Claves)
* **Algoritmo:** **RSA** (Rivest-Shamir-Adleman).
* **Ventaja:** Máxima seguridad, ya que la clave privada permanece local y secreta. Facilita la autenticación y firmas digitales.
* **Desafío:** Mayor consumo de recursos computacionales (más lento).

> **Aplicación Práctica:** El cifrado asimétrico se utiliza para la **identificación** y el intercambio seguro de claves, mientras que el simétrico se prefiere para el **cifrado de archivos masivos** y datos en reposo.

## 🏛️ 1. ¿Cuál es más segura?
En términos estrictos de protección de la clave, la Asimétrica es más segura.

* ¿Por qué? Porque en el cifrado Asimétrico, vos nunca tenés que enviarle tu "llave maestra" (clave privada) a nadie. En cambio, en el Simétrico, si querés que alguien lea tu mensaje, tenés que compartir la clave. Si un hacker intercepta la clave mientras se la pasás a tu amigo, la seguridad se rompe totalmente.

## 🛠️ 2. ¿En qué casos se usa cada una?
Cifrado Simétrico (AES): Se usa para "Volumen"
Se utiliza cuando necesitás velocidad y tenés que cifrar mucha información.

* Archivos en tu PC: Si usás BitLocker o cifrás una carpeta en tu Windows Server.

* Bases de datos: Para proteger los registros de millones de clientes.

* WhatsApp: Una vez que la charla empezó, los mensajes fluyen rápido gracias al cifrado simétrico.

* Cifrado Asimétrico (RSA): Se usa para "Identidad"
Se utiliza para situaciones donde dos personas (o máquinas) no se conocen y necesitan hablar de forma segura por primera vez.

* Firmas Digitales: Para demostrar que un PDF realmente lo firmaste vos.

* Certificados de sitios web (HTTPS): Para que tu navegador sepa que está hablando con el servidor real de tu banco y no con un impostor.

## 🤝 3. El "Truco Final": El Cifrado Híbrido
En la vida real (como cuando entrás a Google o Facebook), se hace un proceso híbrido que combina lo mejor de los dos mundos:

* El Saludo (Asimétrico): Tu PC y el servidor usan cifrado asimétrico para presentarse y verificar que son quienes dicen ser. Es lento, pero muy seguro.

* El Intercambio: Por ese canal seguro "asimétrico", tu PC le envía al servidor una clave simétrica temporal.

* La Navegación (Simétrico): A partir de ahí, toda la charla (fotos, textos, videos) se cifra con esa clave simétrica porque es mucho más rápido y no sobrecarga tu procesador.

### ⚖️ Aplicación Práctica de Cifrados

En la arquitectura de sistemas, selecciono el algoritmo según el caso de uso:

* **Cifrado Simétrico (AES):** Lo aplico para **Datos en Reposo** (discos duros, bases de datos) por su alta velocidad de procesamiento.
* **Cifrado Asimétrico (RSA):** Lo aplico para **Autenticación** y el intercambio inicial de claves, garantizando que la clave privada nunca viaje por la red.

> **Dato Pro:** La seguridad moderna (HTTPS, VPN, SSH) utiliza un sistema **híbrido**: asimétrico para la conexión inicial y simétrico para el intercambio masivo de datos.

## ----------------------------------Cifrado de archivos-------------------------------------------

## 📂 Cifrado de Archivos: Protegiendo la "Caja", no solo el "Túnel"
A diferencia del cifrado de red (que protege el viaje), el cifrado de archivos protege el dato en sí mismo.

1. Datos en Reposo (At Rest)
Es el uso más común. Aplicás el cifrado directamente sobre el disco duro o carpetas específicas.

Soporte Nativo: Sistemas operativos como Windows (con BitLocker o EFS) y Linux (con LUKS) permiten que el sistema de archivos sea ilegible sin la clave de usuario.

Dispositivos Extraíbles: Podés cifrar un pendrive USB completo. Si se te cae en la calle, quien lo encuentre solo verá "galimatías".

2. Datos en Movimiento (In Transit)
El cifrado de archivos ofrece una capa extra de seguridad (Defense in Depth).

El escenario: Si enviás un Excel con PII por mail, el mail viaja por un túnel seguro (HTTPS/TLS). Pero si el servidor de correo del receptor es hackeado, el archivo queda expuesto.

La solución: Si cifrás el archivo antes de enviarlo, el atacante puede interceptar el mail, pero no podrá abrir el Excel adjunto sin la clave que vos le diste a tu amigo por un canal seguro.

### 🔒 Cifrado de Archivos y Sistemas de Archivos

Como Analista, implemento el cifrado de archivos para garantizar la Confidencialidad de la PII y PHI, tanto en almacenamiento local como en tránsito:

| Escenario | Aplicación Técnica | Resultado de Seguridad |
| :--- | :--- | :--- |
| **Disco Local / Servidor** | Cifrado de volumen completo (BitLocker/LUKS). | Protección contra robo físico del hardware. |
| **Almacenamiento Externo** | Cifrado de unidades USB / Discos extraíbles. | Datos ilegibles en caso de pérdida del dispositivo. |
| **Envío de Documentos** | Cifrado a nivel de archivo (File-level encryption). | Seguridad persistente del dato, incluso si el canal de envío falla. |

> **Principio de Seguridad:** El cifrado de archivos asegura que el control de acceso acompañe al dato, sin importar dónde resida o por dónde viaje.

### 📈 Camino de Especialización (Roadmap)

Como parte de mi compromiso con la formación continua en ciberseguridad, tengo como objetivo la certificación:

* **EC-Council Certified Encryption Specialist (ECES):**
    * **Enfoque:** Profundizar en algoritmos simétricos, asimétricos y protocolos de hashing.
    * **Propósito:** Desarrollar la capacidad técnica para seleccionar e implementar estándares de cifrado robustos que aseguren la confidencialidad e integridad en infraestructuras críticas.
    * **Mentalidad:** Evolucionar del análisis de sistemas hacia la arquitectura de seguridad defensiva.

### 🎯 Próximos Pasos y Certificaciones (Roadmap)

Como parte de mi especialización en seguridad de datos y criptografía, tengo proyectado cursar la siguiente certificación:

* **ECES (EC-Council Certified Encryption Specialist):** * **Enfoque:** Algoritmos simétricos/asimétricos, hashing, teoría numérica y criptoanálisis.
    * **Enlace oficial:** [EC-Council Certified Encryption Specialist (ECES)](https://www.eccouncil.org/train-certify/ec-council-certified-encryption-specialist-eces/)


