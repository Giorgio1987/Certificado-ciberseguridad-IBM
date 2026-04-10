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

Concepto,Nivel de Operación,Ejemplo,Ventaja en IT
Cifrado,Caracteres individuales (símbolos).,Hola -> Krod (César +3),Muy fácil de automatizar con algoritmos computacionales.
Codificación,Unidades de significado (palabras/frases).,Misión cumplida -> El águila aterrizó,"Útil para comunicación humana encubierta, pero difícil de escalar técnicamente."

