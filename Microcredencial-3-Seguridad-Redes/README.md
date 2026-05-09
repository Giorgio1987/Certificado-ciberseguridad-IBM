## 🔐 Seguridad del sistema

La seguridad informática sigue el mismo principio que proteger una casa antes de irnos de vacaciones: se trata de **reducir la superficie de ataque** para que un intruso lo tenga mucho más difícil a la hora de robar o destruir datos valiosos.

### 🏠 Analogía casa ↔ sistema

| Protección física (casa)        | Protección digital (sistema)                         |
|---------------------------------|------------------------------------------------------|
| Cerrar puertas con llave        | Autenticación segura (contraseñas robustas, MFA)     |
| Cerrar ventanas                 | Cerrar puertos innecesarios                          |
| Instalar un sistema de alarma   | Antivirus, protección del correo, navegadores y archivos |
| Pedir a los vecinos que vigilen | Registro del sistema (logging) para rastrear actividad |

Cada capa refuerza a las demás, de modo que si una falla, todavía hay otras funcionando.

### 💡 ¿Por qué es igual de importante que la seguridad física?

En un equipo personal se almacena mucha información confidencial:
- Credenciales guardadas en navegadores.
- Números de tarjeta de crédito.
- Documentos sensibles, datos financieros y personales.

Además, un solo equipo comprometido puede servir como puerta de entrada a toda la red interna de una organización, amplificando el daño.

### 🛡️ Medidas básicas de protección

- Usar **contraseñas seguras** y **autenticación multifactor**.
- Cerrar **puertos innecesarios** (ventanas digitales).
- Instalar **software antivirus** y otras herramientas de protección para correo, navegadores y sistema de archivos.
- Activar el **registro del sistema** para analizar cualquier incidente y entender cómo entró un atacante y qué hizo.

### 💬 Opinión personal

> Considero que la comparación con el cuidado de un hogar es muy acertada, ya que personalmente almacenamos mucha información sensible en la PC (datos personales, financieros) que puede comprometer nuestra vida. Los ciberdelincuentes pueden aprovecharse para estafarnos, robar y mucho más a nuestro nombre. A nivel organizacional también hay que tomar todos los recaudos porque, de lo contrario, quedamos expuestos con datos confidenciales y sensibles. Algunas formas de protegerse a nivel personal son usar antivirus, navegar correctamente, prestar atención a los correos electrónicos, utilizar contraseñas fuertes y no divulgar credenciales. A nivel organizacional, es clave contratar un equipo de profesionales en ciberseguridad.

> *“Así como desarrollas buenos hábitos para proteger tus objetos de valor físicos, practicar una buena seguridad del sistema es esencial para mantener seguros tus activos digitales.”*

## 🔧 Firmware

El firmware es un programa informático crítico integrado en un dispositivo de hardware que proporciona control para sus funciones específicas. Está presente en la mayoría de los dispositivos que usamos a diario: routers, teléfonos móviles, impresoras, cámaras, escáneres, tarjetas de red (NIC), unidades ópticas e incluso mandos a distancia.

Se almacena en **memoria no volátil (NVM)**, lo que permite conservar la información incluso cuando el dispositivo está apagado. Puede actualizarse para mejorar la seguridad y el rendimiento, de forma similar al software.

### 🆚 Diferencia entre firmware y software

| Firmware | Software |
|----------|----------|
| Integrado directamente en el hardware | Instalado en el dispositivo |
| Controla el comportamiento del hardware | Son programas y aplicaciones que se ejecutan sobre el sistema operativo |
| Almacenado permanentemente en memoria no volátil (ROM, flash) | Se carga en memoria volátil (RAM) para su ejecución |
| Proporciona las funciones básicas y el arranque del dispositivo | Permite interacciones del usuario: navegar, procesar textos, multimedia, etc. |

### 📁 Tipos de firmware

1. **Firmware de bajo nivel**
   - Almacenado en chips de memoria no volátil como la ROM.
   - No se puede reescribir ni actualizar; es una parte inherente del dispositivo.
   - Proporciona el control más básico, normalmente gestionando los procesos de inicio inicial del hardware.

2. **Firmware de alto nivel**
   - Utiliza chips de memoria flash, lo que permite actualizaciones.
   - Instrucciones más complejas que el de bajo nivel.
   - Ofrece mayor funcionalidad y control, a menudo con una interfaz para el usuario (ej. firmware de una impresora que gestiona trabajos de impresión y configuración).

3. **Firmware de subsistema (o de dispositivo)**
   - Funciona de forma independiente al firmware del sistema principal.
   - Especializado en una parte concreta del hardware.
   - Ejemplo: el chip del cartucho de tinta de una impresora tiene su propio firmware para comunicar los niveles de tinta.


   ## 📋 Plan de firmware de seguridad

Además de conocer qué es el firmware, es fundamental tener un plan para protegerlo en los dispositivos que usamos a diario. Este plan se basa en tres pasos sencillos pero muy efectivos.

### 🔍 Paso 1: Identificar dispositivos con firmware en tu red

Muchos aparatos cotidianos llevan firmware integrado, por ejemplo:
- **Computadoras**: BIOS / UEFI
- **Dispositivos móviles**: cargador de arranque, firmware de banda base
- **Dispositivos médicos**: desfibriladores cardíacos
- **Hogar inteligente (IoT)**: lavavajillas, termostatos inteligentes
- **Electrónica de consumo**: televisores, reproductores Blu-ray, cámaras digitales
- **Periféricos**: impresoras, routers, teclados, ratones

### 🛡️ Paso 2: Detectar vulnerabilidades y cómo prevenirlas

Una vez identificado el firmware de tus dispositivos, el objetivo es listar **dos o tres vulnerabilidades** posibles y sus medidas de prevención. Algunos ejemplos comunes:
- **Firmware desactualizado** → mantener actualizaciones automáticas o verificarlas periódicamente.
- **Contraseñas por defecto** → cambiar siempre las credenciales de fábrica.
- **Acceso remoto innecesario** → desactivar servicios o puertos que no se utilicen.

### ⏱️ Paso 3: Revisar la última actualización de firmware

Elige **dos o tres dispositivos** de tu red wifi e investiga cuándo fue la última vez que se actualizó su firmware. Esta revisión te da una idea del nivel de mantenimiento que reciben y de posibles riesgos acumulados.

### 🔧 Paso 4: Definir acciones concretas de protección

Finalmente, establece los pasos que tomarás para proteger tu hardware y firmware, explicando el razonamiento detrás de cada uno. Por ejemplo:
- Programar revisiones mensuales de actualizaciones.
- Activar funciones de seguridad integradas (arranque seguro, actualizaciones automáticas).
- Reemplazar dispositivos que ya no reciben soporte del fabricante.

> Este plan convierte la seguridad del firmware en un hábito práctico y periódico, reduciendo la superficie de ataque de los dispositivos que usamos todos los días.

### 🧪 Ejemplo práctico: Aplicando el plan de firmware de seguridad

#### Paso 1: Dispositivos que uso a diario con firmware

| Dispositivo | ¿Contiene firmware? | ¿Cómo ayuda a mantener el dispositivo seguro? |
|-------------|---------------------|-----------------------------------------------|
| Router WiFi (modelo genérico) | Sí, todo router tiene firmware. | Controla el firewall integrado, la encriptación de la red (WPA2/WPA3), las reglas de filtrado y el panel de administración. Un firmware actualizado corrige vulnerabilidades que podrían permitir accesos no autorizados a la red. |
| Impresora multifunción | Sí, las impresoras tienen firmware de alto nivel y también firmware de subsistema en los cartuchos. | Gestiona la cola de impresión, protege los documentos almacenados temporalmente y controla el acceso a la configuración de red (Wi-Fi, Ethernet). Las actualizaciones suelen parchear fallos que exponen datos. |
| Smart TV | Sí, contiene firmware (sistema operativo embebido). | Controla las apps, la conexión a internet y los permisos de cámara/micrófono si los tiene. Un firmware actualizado evita exploits que podrían espiar al usuario o usar el televisor como puerta de entrada a la red doméstica. |

**Respuestas a las preguntas:**
- **¿Tiene firmware un enrutador?** Sí, es uno de los dispositivos con firmware más crítico.
- **¿Cómo confirmar la información del firmware en un dispositivo inteligente?** Generalmente desde el menú de configuración del propio dispositivo (sección "Acerca de", "Información del sistema" o "Actualización") o mediante la app móvil del fabricante.
- **¿Qué periféricos de computadora tienen firmware?** Impresoras, routers, teclados, ratones, cámaras web, unidades SSD/HDD externas y docks USB, entre otros.

---

#### Paso 2: Vulnerabilidades y formas de prevención

| Dispositivo | Vulnerabilidad | Prevención |
|-------------|----------------|------------|
| Router WiFi | Firmware desactualizado con fallos de seguridad conocidos (ej. ejecución remota de código). | Activar las actualizaciones automáticas desde el panel de administración. Revisar manualmente cada 2-3 meses en la web del fabricante. |
| Impresora multifunción | Contraseña de administrador por defecto ("admin/admin"). | Cambiar la contraseña nada más instalar el dispositivo y usar credenciales robustas. Desactivar servicios innecesarios (Wi-Fi Direct, impresión remota) si no se usan. |
| Smart TV | Recopilación excesiva de datos mediante ACR (reconocimiento automático de contenido) sin consentimiento claro. | Revisar los ajustes de privacidad al configurar el televisor y desactivar las opciones de seguimiento. Mantener el firmware actualizado para corregir vulnerabilidades de privacidad. |

---

#### Paso 3: Última actualización de firmware en dispositivos de mi red

| Dispositivo | Última actualización de firmware | ¿Está al día? |
|-------------|----------------------------------|---------------|
| Router WiFi | 15 de mayo de 2025 (versión 2.4.1) | Sí, se lanzó hace menos de un mes. |
| Impresora multifunción | 20 de diciembre de 2024 (actualización crítica de seguridad) | No, el fabricante ya publicó una nueva versión en marzo de 2026. Requiere descarga manual desde el sitio web. |
| Smart TV | El televisor muestra "comprobación automática" activada; última comprobación exitosa: hace 2 días. | Sí, se actualiza automáticamente. |

**Reflexión personal sobre el plan de firmware:**
> "Descubrí que la impresora llevaba meses sin actualizar porque no tiene activada la opción automática. Ahora sé que tengo que revisar manualmente el sitio del fabricante cada trimestre. También cambié la contraseña por defecto del router y desactivé ACR en la Smart TV para proteger mi privacidad. Son pasos sencillos pero reducen mucho la superficie de ataque en casa."

### Paso 1: Identificar dispositivos con firmware que uso a diario

| Dispositivo | ¿Contiene firmware? | ¿Cómo ayuda ese firmware a mantener seguro el dispositivo? |
|-------------|---------------------|------------------------------------------------------------|
| **Router WiFi de casa** | Sí, todo router tiene firmware. | El firmware controla el firewall integrado, la encriptación de la red (WPA2) y el panel de administración. Si está actualizado, corrige agujeros de seguridad que podrían dejar entrar a intrusos en mi red. |
| **Impresora** | Sí, las impresoras tienen firmware. | El firmware gestiona quién puede imprimir, protege los documentos que quedan en cola y controla la conexión a la red. Las actualizaciones arreglan fallos que podrían exponer datos. |
| **Mouse inalámbrico** | Sí, los periféricos también llevan firmware. | El firmware controla la conexión Bluetooth/USB y evita interferencias. Si tiene vulnerabilidades, un atacante cercano podría interceptar la señal y tomar control del cursor. Mantenerlo actualizado cierra esa puerta. |

### Respuestas a las preguntas

- **¿Tiene firmware un router?**
  Sí, absolutamente. El firmware del router es clave para mantener la red doméstica segura, ya que gestiona el cortafuegos, las reglas de filtrado y las actualizaciones de seguridad.

- **¿Tengo algún dispositivo inteligente? ¿Cómo confirmar la información de su firmware?**
  Sí, por ejemplo un lavavajillas inteligente o un termostato inteligente. Para confirmar la información del firmware puedo:
  - Entrar en el menú de configuración del propio dispositivo (pantalla táctil o botones) y buscar "Información del sistema" o "Acerca de".
  - Usar la aplicación móvil del fabricante, donde suele aparecer la versión de firmware y si hay actualizaciones disponibles.
  - El firmware de estos dispositivos garantiza que funcionen correctamente y avisa cuando hay una actualización disponible para mantenerlos protegidos.

- **¿Qué periféricos informáticos tienen firmware?**
  Muchos periféricos cotidianos tienen firmware, por ejemplo:
  - Impresoras
  - Teclados (especialmente los inalámbricos y gaming)
  - Ratones (mouse)
  - Cámaras web
  - Discos duros externos (SSD/HDD)
  - Docks USB

> **Conclusión del paso 1:** Los tres dispositivos que uso a diario con firmware son el router, la impresora y el mouse inalámbrico. El firmware ayuda a mantenerlos seguros controlando accesos, corrigiendo vulnerabilidades y asegurando que funcionen correctamente.

## ⚠️ Vulnerabilidades de firmware

Al igual que el software, el firmware puede tener debilidades que los ciberatacantes explotan para comprometer la seguridad y el funcionamiento de los dispositivos. Estas amenazas pueden aparecer en cualquier aparato con sistema operativo y firmware (routers, impresoras, smart TVs, cámaras, etc.).

### 📋 Vulnerabilidades más comunes según CWE (Common Weakness Enumeration)

La comunidad de seguridad mantiene una lista de debilidades comunes que afectan al software y al firmware. Estas son las más frecuentes:

| Vulnerabilidad | ¿En qué consiste? | Ejemplo sencillo |
|----------------|-------------------|------------------|
| **Falta de cifrado de datos** | Los datos viajan o se almacenan sin protección. | Un router que transmite la contraseña WiFi en texto plano. |
| **Inyección de comandos del SO** | Un atacante introduce comandos del sistema operativo y los ejecuta. | Enviar un comando malicioso desde la app de un dispositivo inteligente. |
| **Inyección SQL** | Se inserta código malicioso en bases de datos mal protegidas. | Manipular el panel de administración de una cámara IP para robar datos. |
| **Desbordamiento del búfer** | Se introducen más datos de los que el dispositivo puede manejar, sobrescribiendo memoria. | Colapsar el firmware de una impresora para tomar su control. |
| **Falta de autenticación** | Una función crítica no pide contraseña ni verificación. | Acceder a la configuración de un router sin necesidad de iniciar sesión. |
| **Falta de autorización** | Un usuario con pocos permisos accede a funciones que no le corresponden. | Un invitado de la red que puede cambiar la contraseña del WiFi. |
| **Carga de archivos peligrosos sin restricción** | El dispositivo acepta cualquier tipo de archivo sin comprobar si es malicioso. | Subir un virus al actualizar el firmware de una Smart TV. |
| **Entradas no fiables en decisiones de seguridad** | El sistema confía ciegamente en datos que vienen de fuera. | Un termostato inteligente que ejecuta órdenes sin verificar su origen. |
| **Falsificación y secuencias de comandos en sitios cruzados (XSS)** | Se inyecta código malicioso en páginas web del dispositivo. | Manipular la interfaz web del router para robar credenciales. |
| **Descarga de código sin comprobación de integridad** | El dispositivo instala actualizaciones sin verificar que sean legítimas. | Aceptar una actualización falsa que introduce malware. |
| **Uso de algoritmos rotos** | Se utilizan métodos de cifrado débiles u obsoletos. | Un router que usa encriptación WEP en lugar de WPA3. |
| **Redirección de URL a sitios no fiables** | El dispositivo redirige a páginas maliciosas sin advertirlo. | Una impresora que te envía a un sitio falso para descargar drivers. |

### 🛡️ ¿Por qué es importante conocerlas?

Conocer estas vulnerabilidades permite:
- **Identificar riesgos** en los dispositivos que usamos a diario.
- **Aplicar medidas preventivas** como mantener el firmware actualizado, cambiar contraseñas por defecto y desactivar funciones innecesarias.
- **Reducir la superficie de ataque** siguiendo el plan de firmware de seguridad.

> *"Estas amenazas pueden ocurrir en cualquier dispositivo con sistema operativo y firmware. La prevención empieza por conocer las debilidades."*
## 🔧 Firmware

### ¿Qué es el firmware?

El firmware es un programa informático crítico integrado directamente en el hardware de un dispositivo. Le dice al aparato cómo funcionar a nivel básico: es lo primero que se ejecuta al encenderlo, antes incluso que el sistema operativo o las aplicaciones.

Está presente en casi todos los dispositivos electrónicos: routers, teléfonos, impresoras, smart TVs, cámaras, microondas, teclados, ratones e incluso mandos a distancia.

Se almacena en **memoria no volátil (ROM o flash)**, lo que significa que conserva la información incluso con el dispositivo apagado.

### 🧠 ¿Para qué sirve el firmware si ya tenemos software?

Imaginemos un teatro:

| Capa | ¿Qué es? | Ejemplo |
|------|----------|---------|
| **Hardware** | El edificio, las butacas, los focos. | El chip físico, los circuitos. |
| **Firmware** | El manual de instrucciones que le dice al edificio cómo encender las luces y bajar el telón. **Sin esto, el edificio no funciona.** | BIOS/UEFI, sistema interno del router, chip de la impresora. |
| **Sistema operativo** | El director de la obra, que coordina a los actores y la escenografía. | Windows, Linux, Android. |
| **Software / Apps** | La obra de teatro que ve el público. | Word, Chrome, Spotify. |

- El **firmware** es lo primero que se ejecuta. Le enseña al hardware cómo arrancar y responder.
- El **software** (SO y aplicaciones) se carga después, usando las funciones que el firmware ya dejó listas.
- Sin firmware, el software no tiene con qué hablarle al hardware. Sería como manejar un auto sin que nadie le haya enseñado al motor a responder al acelerador.

> **Entonces no, el firmware no se usa solo para chips pequeños como la BIOS. La BIOS es un tipo de firmware, pero también lo es todo el sistema operativo interno de un router, una Smart TV, una cámara IP o una impresora.**

### ⚠️ ¿Estamos vulnerables porque nadie revisa el firmware?

**Sí. Es un riesgo real y bastante silencioso.** Nadie se acuerda del firmware, y los atacantes lo saben. Los motivos más comunes:
- La gente no sabe que existe.
- No sabe cómo actualizarlo.
- Piensa "si funciona, para qué tocarlo".
- No hay alertas visibles como en Windows o en el celular.

**El peligro:** un atacante que explota una vulnerabilidad en el firmware de tu router puede robar contraseñas, desviarte a páginas falsas o usar tu red para actividades ilegales. Y como el firmware está por debajo del sistema operativo, un antivirus común no lo detecta fácilmente.

**Consejos prácticos para protegerse:**
- **Router:** entrar al panel de administración cada 2 o 3 meses y buscar "Actualizar firmware". Activar actualizaciones automáticas si las tiene.
- **Dispositivos inteligentes:** abrir la app del fabricante y buscar "Información del sistema". Ahí suele avisar si hay actualización disponible.
- **Regla de oro:** si un dispositivo conectado a internet no recibe actualizaciones del fabricante desde hace años, hay que considerar reemplazarlo.

### 🆚 Diferencia entre firmware y software

| Firmware | Software |
|----------|----------|
| Integrado directamente en el hardware | Instalado en el dispositivo |
| Controla el comportamiento del hardware | Son programas y aplicaciones que se ejecutan sobre el SO |
| Almacenado en memoria no volátil (ROM, flash) | Se carga en memoria volátil (RAM) para su ejecución |
| Proporciona las funciones básicas y el arranque | Permite interacciones del usuario: navegar, procesar textos, multimedia |

### 📁 Tipos de firmware

1. **Firmware de bajo nivel**
   - Almacenado en chips ROM.
   - No se puede reescribir ni actualizar.
   - Gestiona los procesos de inicio del hardware (ej. BIOS).

2. **Firmware de alto nivel**
   - Utiliza memoria flash, permite actualizaciones.
   - Instrucciones más complejas.
   - Ofrece interfaz para el usuario (ej. firmware de una impresora o router).

3. **Firmware de subsistema (o de dispositivo)**
   - Funciona de forma independiente al firmware principal.
   - Especializado en una parte concreta del hardware (ej. chip del cartucho de tinta que comunica niveles de tinta).

### 📋 Plan de firmware de seguridad

#### Paso 1: Identificar dispositivos con firmware

| Dispositivo | ¿Tiene firmware? | ¿Cómo ayuda a mantenerlo seguro? |
|-------------|------------------|-----------------------------------|
| Router WiFi | Sí, todo router tiene firmware. | Controla firewall, encriptación WPA2/WPA3 y panel de administración. Las actualizaciones corrigen vulnerabilidades. |
| Impresora | Sí. | Gestiona acceso a documentos, cola de impresión y conexión de red. |
| Mouse inalámbrico | Sí. | Controla la conexión Bluetooth/USB. Actualizaciones evitan interceptación de señal. |

**Preguntas clave:**
- **¿Tiene firmware un router?** Sí, es uno de los dispositivos con firmware más crítico.
- **¿Cómo confirmar el firmware de un dispositivo inteligente?** Desde el menú "Acerca de" o "Información del sistema" en el propio aparato, o mediante la app del fabricante.
- **¿Qué periféricos tienen firmware?** Impresoras, teclados, ratones, cámaras web, discos externos, docks USB.

#### Paso 2: Vulnerabilidades y prevención

| Dispositivo | Vulnerabilidad | Prevención |
|-------------|----------------|------------|
| Router WiFi | Firmware desactualizado | Activar actualizaciones automáticas. Revisar manualmente cada 2-3 meses. |
| Impresora | Contraseña de administrador por defecto | Cambiarla apenas se instala. Desactivar servicios que no se usen. |
| Smart TV | Recopilación excesiva de datos (ACR) | Revisar ajustes de privacidad y desactivar seguimiento. Mantener firmware actualizado. |

#### Paso 3: Revisar última actualización

| Dispositivo | Última actualización | ¿Al día? |
|-------------|----------------------|----------|
| Router WiFi | 15/05/2025 | Sí |
| Impresora | 20/12/2024 | No (hay nueva versión disponible) |
| Smart TV | Automática (hace 2 días) | Sí |

### ⚠️ Vulnerabilidades de firmware más comunes (según CWE)

| Vulnerabilidad | ¿En qué consiste? | Ejemplo sencillo |
|----------------|-------------------|------------------|
| Falta de cifrado de datos | Los datos viajan o se almacenan sin protección. | Router que transmite la contraseña WiFi en texto plano. |
| Inyección de comandos | Un atacante introduce comandos del SO y los ejecuta. | Enviar un comando malicioso desde la app de un dispositivo inteligente. |
| Inyección SQL | Se inserta código en bases de datos mal protegidas. | Manipular el panel de administración de una cámara IP. |
| Desbordamiento del búfer | Se introducen más datos de los que el dispositivo puede manejar. | Colapsar el firmware de una impresora para tomar su control. |
| Falta de autenticación | Una función crítica no pide contraseña. | Acceder a la configuración del router sin iniciar sesión. |
| Falta de autorización | Un usuario con pocos permisos accede a funciones avanzadas. | Un invitado de la red que puede cambiar la contraseña WiFi. |
| Carga de archivos peligrosos sin restricción | El dispositivo acepta cualquier archivo sin comprobar. | Subir un virus al "actualizar firmware" de una Smart TV. |
| Dependencia de entradas no fiables | El sistema confía ciegamente en datos externos. | Termostato inteligente que ejecuta órdenes sin verificar su origen. |
| Falsificación y XSS | Se inyecta código malicioso en páginas web del dispositivo. | Manipular la interfaz web del router para robar credenciales. |
| Descarga sin comprobación de integridad | Instala actualizaciones sin verificar que sean legítimas. | Aceptar una actualización falsa que introduce malware. |
| Uso de algoritmos rotos | Métodos de cifrado débiles u obsoletos. | Router que todavía usa encriptación WEP. |
| Redirección de URL a sitios no fiables | El dispositivo redirige a páginas maliciosas. | Impresora que te envía a un sitio falso para descargar drivers. |

### ❓ Preguntas frecuentes sobre firmware

**¿Todos los dispositivos usan firmware?**
Sí, prácticamente todos los dispositivos electrónicos tienen firmware. La diferencia está en si se actualiza a menudo (router, Smart TV) o casi nunca (microondas, mouse).

**¿Por qué se menciona el phishing si es por correo electrónico?**
El phishing no ataca directamente al firmware, pero es la puerta de entrada. Si un usuario cae en un phishing, puede instalar malware que luego explote vulnerabilidades del firmware o del sistema operativo. Por eso el curso lo menciona como amenaza relacionada.

**¿El firmware se usa solo para chips pequeños como la BIOS?**
No. La BIOS es un tipo de firmware (de bajo nivel), pero los dispositivos modernos como routers, Smart TVs y cámaras IP tienen sistemas operativos completos que también se consideran firmware. Todo lo que va "incrustado" en el aparato y se carga directamente sobre el hardware es firmware.

> *"Conocer el firmware, mantenerlo actualizado y seguir un plan de seguridad reduce drásticamente la superficie de ataque de cualquier red doméstica o corporativa."*

### Paso 2: Vulnerabilidades y formas de prevención

| Dispositivo | Vulnerabilidad | ¿Cómo la prevengo? | Concepto de seguridad |
|-------------|----------------|---------------------|------------------------|
| **Router WiFi** | **Falta de cifrado:** el panel de administración usa HTTP en lugar de HTTPS, por lo que los datos viajan en texto plano. | Accedo al panel del router desde un navegador y reviso que la dirección empiece con `https://`. Si solo tiene HTTP, habilito la opción "Acceso HTTPS" o "Cifrado SSL" desde los ajustes avanzados. **También me aseguro de que la red WiFi use WPA2 o WPA3** y no WEP. | **Cifrado** |
| **Impresora multifunción** | **Falta de autenticación:** la impresora viene con usuario y contraseña por defecto (`admin/admin`) y cualquiera en la red puede entrar a su configuración. | Al instalar la impresora, lo primero que hago es cambiar la contraseña de administrador. También desactivo funciones que no uso (Wi-Fi Direct, impresión remota) y creo un usuario con permisos limitados para las tareas diarias. | **Autenticación / Autorización** |
| **Smart TV** | **Redireccionamiento de URL a sitios no fiables:** el navegador integrado o las apps del televisor podrían redirigir a páginas falsas sin advertirlo, por ejemplo al buscar actualizaciones de firmware. | **Nunca descargo firmware desde enlaces en pantalla.** Siempre verifico las actualizaciones desde el menú oficial de la TV: Ajustes > Soporte > Actualización de software. Si tengo dudas, entro directamente a la web del fabricante desde mi computadora. También mantengo activada la verificación automática para que solo descargue de fuentes legítimas. | **Redireccionamiento de URL a sitios no fiables** |

### 📝 Explicación del razonamiento

- **Cifrado:** Me aseguro de que el router use conexiones cifradas (HTTPS para el panel, WPA2/WPA3 para el WiFi). Si los datos viajan en texto plano, un atacante en la misma red puede interceptarlos con mucha facilidad.

- **Autenticación / Autorización:** Cambiar las contraseñas por defecto de fábrica y limitar los permisos evita que usuarios no autorizados modifiquen la configuración del dispositivo. Es una barrera básica pero muy efectiva.

- **Redireccionamiento de URL:** Nunca permito que un dispositivo me redirija a sitios no fiables. Verifico que las actualizaciones y descargas se hagan únicamente desde los canales oficiales del fabricante. Esto previene la instalación de firmware falso con malware.

> **Conclusión:** Con estas tres medidas aplicadas a mi router, impresora y Smart TV, reduzco significativamente la superficie de ataque y protejo tanto los dispositivos como la información que pasa por mi red doméstica.


## 🦠 Hackeo de firmware

Las vulnerabilidades de firmware permiten a los atacantes acceder a los sistemas sin ser detectados hasta que ya es demasiado tarde. Tanto la BIOS tradicional como los sistemas UEFI modernos son objetivos habituales.

### 🧨 ¿Cómo funciona un ataque de firmware?

El proceso suele seguir dos pasos:

1. **Inyección de código**
   El atacante introduce malware en el código de bajo nivel que controla el dispositivo, tanto antes como después del arranque del sistema.

2. **Acciones destructivas**
   Una vez infiltrado, el malware puede:
   - Alterar o deshabilitar el firmware.
   - Atacar secciones específicas del sistema operativo.
   - Infiltrarse en el software instalado.

### 📦 Formas de hackeo de firmware

| Tipo de ataque | ¿En qué consiste? |
|----------------|-------------------|
| **Malware genérico** | Software malicioso que infecta el firmware para tomar control del dispositivo. |
| **Bootkit** | Malware que infecta el cargador de arranque o el registro de arranque maestro (MBR). Se ejecuta **antes** del sistema operativo, eludiendo medidas de seguridad. |
| **Rootkit** | Malware diseñado para **ocultar su presencia** al usuario y a los mecanismos de seguridad. Modifica componentes del sistema operativo para pasar desapercibido. |
| **USB infectadas** | Dispositivos flash que contienen firmware malicioso y lo ejecutan al conectarse. |
| **Corrupción de discos duros** | Ataque directo al firmware del disco para dañarlo o tomar su control. |
| **Firmware defectuoso o falso** | Productos que vienen con firmware vulnerable de fábrica o actualizaciones falsas que introducen malware. |

### 🌐 ¿Necesitan acceso físico al dispositivo?

**No.** Los atacantes pueden enviar malware de forma remota a través de:
- WiFi
- Bluetooth
- Otras conexiones de red

### 💥 ¿Por qué un ataque de firmware es tan grave?

El firmware es la **base de la seguridad del sistema** en cualquier dispositivo integrado: desde electrodomésticos inteligentes (heladeras, microondas) hasta sistemas de control industrial. Por eso un ataque exitoso no es un incidente menor.

**Consecuencias graves:**
- Los dispositivos electrónicos están cargados de firmware, incluso componentes como cámaras web, tarjetas de sonido y baterías. Todos pueden ser atacados.
- El malware de firmware **carece de firmas criptográficas** que permitan detectarlo fácilmente. Esto hace que los equipos de seguridad de TI tarden mucho en encontrarlo.
- Puede permanecer **oculto durante largos períodos** causando daño continuo.
- Puede infectar **actualizaciones legítimas de firmware**, incrustándose aún más profundo.
- Persiste incluso después de **limpiar completamente el disco duro o reinstalar el sistema operativo**, porque vive en un nivel inferior al SO.

### 🧠 En resumen

| Característica del ataque de firmware | Peligro |
|----------------------------------------|---------|
| Se ejecuta antes del SO | Elude antivirus y medidas de seguridad tradicionales |
| Se oculta (rootkit) | Difícil de detectar |
| Persiste tras formateo | Vive en el firmware, no en el disco duro |
| Puede llegar remotamente | No necesita acceso físico |
| Infecta actualizaciones legítimas | El usuario cree que está protegiéndose y en realidad abre la puerta |

> *"El firmware es la base de la seguridad del sistema. Si la base se quiebra, todo lo que se construye encima queda comprometido."*


**Analogía:** Es como un ladrón que se **disfraza de mueble**. Vos entrás a tu casa, ves la mesa, las sillas, el sofá... todo normal. Pero uno de esos muebles es el ladrón.

**Peligros:**
- Invisibilidad total durante meses.
- Sirve de "base" para otros malware (keyloggers, troyanos, ransomware).
- Muy difícil de eliminar. A veces la única solución es reinstalar todo desde cero.

---

#### 🆚 Diferencia clave

| Característica | 🥾 Bootkit | 🕶️ Rootkit |
|----------------|-----------|-----------|
| **¿Cuándo se activa?** | Durante el arranque, **antes** del SO. | Con el SO ya cargado. |
| **¿Dónde se aloja?** | MBR o cargador de arranque. | Kernel, drivers o librerías del SO. |
| **Objetivo principal** | Tomar control desde el inicio. | Ocultarse y ocultar otros malware. |
| **¿Sobrevive a reinstalar el SO?** | Sí (vive en el MBR). | Generalmente no, salvo que infecte el firmware. |
| **Analogía** | Sobornar al guardia antes de que abra. | Ladrón disfrazado de mueble. |

---

#### 💭 Dato personal

> Recuerdo que en la época de Windows XP, un compañero mostró en vivo un rootkit que tenía infectada su máquina. Era completamente invisible: no aparecía en el administrador de tareas, el antivirus no lo detectaba y el sistema parecía funcionar con normalidad. Solo se podía encontrar con herramientas especializadas. Esa demostración en vivo me dejó claro lo peligroso que es un malware que se oculta a nivel del sistema operativo.

### 🛡️ ¿Siguen funcionando los bootkits y rootkits en la actualidad?

**En los sistemas operativos modernos es mucho más difícil que funcionen como antes.** Windows, Linux y macOS incorporan múltiples capas de protección que no existían en la época de Windows XP.

#### 🧱 Mecanismos de protección actuales

| Mecanismo | ¿Qué hace? | ¿A quién frena? |
|-----------|------------|-----------------|
| **Secure Boot (UEFI)** | Solo permite que se ejecute software firmado digitalmente durante el arranque. Si el bootkit no tiene firma válida, directamente no arranca. | 🥾 Bootkit |
| **TPM (Trusted Platform Module)** | Chip que almacena claves de cifrado y verifica que el sistema no fue alterado durante el arranque. | 🥾 Bootkit |
| **Kernel Patch Protection (PatchGuard)** | En Windows, detecta si alguien intenta modificar el kernel y provoca una pantalla azul a propósito para frenar el ataque. | 🕶️ Rootkit |
| **Antivirus modernos** | Ya no solo buscan firmas de virus. Usan detección por comportamiento, heurística y análisis de memoria para encontrar amenazas ocultas. | 🕶️ Rootkit |
| **Actualizaciones automáticas** | Los parches de seguridad llegan rápido y cierran vulnerabilidades sin que el usuario tenga que hacer nada. | Ambos |
| **Control de cuentas de usuario (UAC)** | Pide confirmación antes de realizar cambios profundos en el sistema. El malware no puede modificar el kernel sin que el usuario lo sepa. | Ambos |

#### ⚠️ Pero ojo: no desaparecieron, evolucionaron

Aunque es mucho más difícil, los atacantes se adaptaron y ahora apuntan a capas más profundas:

| Vieja escuela (Windows XP) | Nueva escuela (actualidad) |
|----------------------------|----------------------------|
| Rootkit que modificaba el kernel sin resistencia. | Rootkit que aprovecha vulnerabilidades **zero-day** (fallos que todavía no tienen parche). |
| Bootkit alojado en el MBR sin protección. | Bootkit que ataca directamente el **firmware UEFI**, más profundo que el MBR y más difícil de detectar. |
| Infección por USB o descarga ingenua. | Ataques a la **cadena de suministro**: infectan el firmware de fábrica o una actualización oficial que el usuario instala confiado. |

#### 🎯 Conclusión

> Los rootkits clásicos de Windows XP no funcionarían hoy en un Windows 11 actualizado. Pero los atacantes ahora apuntan más abajo: al firmware UEFI, al TPM o a vulnerabilidades zero-day. La lucha sigue, solo cambió el campo de batalla.

#### 💭 Experiencia personal

> Recuerdo que en la época de Windows XP, un compañero mostró en vivo un rootkit que tenía infectada su máquina. Era completamente invisible: no aparecía en el administrador de tareas, el antivirus no lo detectaba y el sistema parecía funcionar con normalidad. Solo se podía encontrar con herramientas especializadas. Esa demostración me dejó claro lo peligroso que es un malware que se oculta a nivel del sistema operativo. Hoy, gracias a mecanismos como Secure Boot, TPM y los antivirus modernos, ese mismo ataque sería mucho más difícil de ejecutar... pero no imposible si el atacante logra bajar una capa más, directamente al firmware.


## 🔄 Actualizaciones de firmware

Las actualizaciones de firmware son esenciales para mantener los dispositivos funcionando de forma eficiente y segura. Consisten en agregar o reescribir el software existente en un dispositivo para corregir errores, parchear vulnerabilidades o añadir nuevas funciones.

### 📊 Frecuencia de actualización

La frecuencia depende del tipo de dispositivo:

| Tipo de dispositivo | Frecuencia de actualización |
|---------------------|-----------------------------|
| **Router WiFi** | Varias veces al año (por parches de seguridad). |
| **Smart TV** | Cada pocos meses. |
| **Impresora** | Ocasionalmente (muchos usuarios lo olvidan). |
| **Dispositivos IoT (termostatos, lavavajillas inteligentes)** | Cuando el fabricante lanza mejoras. |
| **Electrodomésticos simples (microondas)** | Rara vez o nunca (firmware de bajo nivel). |

**Regla general:** los dispositivos conectados a internet con frecuencia requieren actualizaciones más regulares para mantener las funciones de seguridad al día.

### 🛡️ ¿Por qué son importantes para la seguridad?

Las actualizaciones de firmware se vuelven necesarias cuando:
- Se descubren **fallos o errores** que necesitan corrección.
- Aparecen **nuevas vulnerabilidades de seguridad** que requieren parches.
- Se introducen **nuevas funciones** que mejoran la experiencia del usuario.

Una actualización de firmware ayuda a:
- Solucionar problemas de funcionamiento.
- Cerrar puertas de entrada a posibles ataques.
- Mejorar la estabilidad y compatibilidad del dispositivo.

### 📡 Actualizaciones inalámbricas (OTA)

Las actualizaciones **Over-The-Air (OTA)** son software, firmware u otros datos nuevos que se transmiten de forma inalámbrica a los dispositivos. No hace falta conectar el dispositivo a una computadora.

**¿Quiénes las usan?**
- Operadores inalámbricos.
- Fabricantes de equipos originales (OEM).

**¿Para qué sirven?**
- Configurar teléfonos nuevos para usarlos en sus redes (WiFi o banda ancha móvil).
- Implementar nuevos sistemas operativos en smartphones, tabletas y dispositivos IoT.

**Ejemplo cotidiano:**
> Cuando comprás un teléfono nuevo, es probable que necesite una actualización inalámbrica apenas lo encendés para inicializarse correctamente.

**Dispositivos que usan OTA:**
- Smartphones y tabletas.
- Dispositivos IoT (cámaras, termostatos, enchufes inteligentes).
- Smart TVs.
- Routers y repetidores WiFi.

### ✅ Buenas prácticas

- **Activar actualizaciones automáticas** siempre que el dispositivo lo permita.
- **Revisar manualmente** cada 2 o 3 meses los dispositivos que no se actualizan solos.
- **Descargar actualizaciones solo de fuentes oficiales** (web del fabricante, app oficial o menú del propio dispositivo).
- **No ignorar las notificaciones de actualización**, especialmente las que mencionan "parche de seguridad".

> *"Una actualización de firmware a tiempo puede ser la diferencia entre un dispositivo seguro y una puerta abierta a los atacantes."*

### Paso 3: Revisar la última actualización de firmware

#### 📋 Dispositivos en mi red WiFi

| Dispositivo | ¿Cómo encuentro la información? | Versión actual del firmware | Última actualización |
|-------------|---------------------------------|-----------------------------|----------------------|
| **Router WiFi** | Entré al panel de administración desde el navegador (192.168.1.1), inicié sesión y busqué en "Administración > Actualización de firmware" o "Información del sistema". | v2.4.1 | 15 de mayo de 2025 |
| **Impresora multifunción** | En la pantalla táctil de la impresora fui a "Configuración > Información del dispositivo > Versión de firmware". También revisé desde la app del fabricante en el celular. | v3.8.0 | 20 de diciembre de 2024 |
| **Smart TV** | Desde el control remoto entré a "Ajustes > Soporte > Actualización de software". La TV tiene activada la opción de actualización automática. | v6.2.0 | Hace 2 días (comprobación automática exitosa) |

#### 🔍 ¿Están al día?

| Dispositivo | ¿Está actualizado? | Acción necesaria |
|-------------|-------------------|------------------|
| **Router WiFi** | ✅ Sí | Ninguna. La actualización es reciente y tiene las correcciones de seguridad más nuevas. |
| **Impresora multifunción** | ❌ No | El fabricante publicó una nueva versión en marzo de 2026 que incluye un parche de seguridad importante. Debo descargarla manualmente desde la web oficial e instalarla. |
| **Smart TV** | ✅ Sí | Se actualiza automáticamente. La última comprobación fue exitosa. |

#### 📝 Explicación del razonamiento

- **Versión actual del firmware:** esta información la encontré en la configuración de cada dispositivo, generalmente en secciones como "Información del sistema", "Acerca de" o "Actualización de firmware". 
- **Última actualización:** revisé la fecha de la última actualización instalada y la comparé con las versiones disponibles en la web del fabricante para saber si estaban al día.
- **Acción tomada:** para la impresora, que estaba desactualizada, agendé la descarga e instalación manual como tarea prioritaria. También activé las actualizaciones automáticas en los dispositivos que lo permitían para no depender de revisiones manuales en el futuro.

#### 💭 Reflexión personal

> Revisar el firmware de mis dispositivos me llevó menos de 15 minutos y descubrí que la impresora llevaba meses sin actualizar, con una vulnerabilidad conocida sin parche. Es un recordatorio de que las actualizaciones automáticas no siempre están activadas por defecto y que vale la pena revisar manualmente cada cierto tiempo. A partir de ahora voy a programar un recordatorio cada 3 meses para repetir este chequeo.

### 🖨️ Guía práctica: Cómo revisar el firmware de una impresora

Esta guía explica, paso a paso, cómo encontrar la versión actual del firmware de una impresora doméstica o de oficina. Dependiendo de la marca y el modelo, la información puede estar en distintos lugares, pero el principio es siempre el mismo: **conectarse a la impresora y buscar la sección de información o actualización**.

---

#### Método 1: Desde la pantalla de la impresora (el más fácil)

Si la impresora tiene pantalla (táctil o con botones):

1. Encender la impresora.
2. Navegar por los menús buscando opciones como:
   - **Configuración / Ajustes**
   - **Herramientas**
   - **Información del dispositivo**
   - **Acerca de**
3. Dentro de alguna de esas secciones buscar **"Versión de firmware"** o **"Actualización de firmware"**.
4. La pantalla mostrará la versión actual y, en algunos modelos, la fecha de instalación.

---

#### Método 2: Desde la computadora (herramienta del fabricante)

Muchas marcas incluyen un programa para gestionar la impresora.

**Para impresoras Epson:**
- Buscar en la computadora el programa **"Epson Software Updater"**.
- Abrirlo, seleccionar la impresora y mostrará si hay actualizaciones disponibles, además de la versión instalada.
- En Mac suele estar en `Aplicaciones > Epson Software`.

**Para impresoras Brother:**
- Descargar la **"Herramienta de actualización de firmware"** desde la página web oficial de Brother.
- Al ejecutarla, detecta automáticamente la impresora y muestra la versión actual y si necesita actualización.

**Para otras marcas (HP, Canon, Samsung, etc.):**
- Visitar la web oficial del fabricante y buscar el modelo de la impresora.
- Generalmente hay una sección de "Soporte", "Descargas" o "Drivers y firmware".

---

#### Método 3: Desde el navegador web (Embedded Web Server)

Si la impresora está conectada a la red WiFi (no solo por USB):

1. Buscar la **dirección IP** de la impresora:
   - Desde la pantalla de la impresora (menú de red o configuración WiFi).
   - O desde la configuración del router, en la lista de dispositivos conectados.
2. Abrir un navegador (Chrome, Edge, Firefox) y escribir la dirección IP en la barra de direcciones.
3. Se abrirá el **servidor web interno** de la impresora.
4. Buscar opciones como **"Dispositivo"**, **"Estado"** o **"Información del dispositivo"**.
5. Ahí se mostrará la versión del firmware instalada.

---

#### ⚠️ Regla de oro al actualizar

> **Nunca apagar ni desconectar la impresora mientras se instala una actualización de firmware.** Si el proceso se interrumpe, el dispositivo puede quedar inutilizable.

---

#### 📝 ¿No encuentro mi modelo exacto?

Buscar en internet: `"actualizar firmware [marca de la impresora] [modelo]"`. La página oficial del fabricante siempre tiene las instrucciones paso a paso para cada modelo concreto.


### Paso 4: Plan de acción para proteger mi firmware

Después de completar los pasos 1, 2 y 3, este es el plan concreto que voy a seguir para mantener protegido el firmware de mis dispositivos.

---

#### 🛡️ 1. Abordar cada vulnerabilidad identificada

| Dispositivo | Vulnerabilidad encontrada | Acción concreta que voy a tomar | ¿Cuándo? |
|-------------|---------------------------|--------------------------------|----------|
| **Router WiFi** | Falta de cifrado en el panel de administración (usaba HTTP en lugar de HTTPS). | Ingresar al panel del router y activar la opción "Acceso HTTPS" o "Cifrado SSL" desde los ajustes avanzados. También verificar que la red WiFi use WPA2 o WPA3. | Hoy mismo |
| **Impresora multifunción** | Falta de autenticación (contraseña por defecto `admin/admin`). Firmware desactualizado desde diciembre 2024. | Cambiar la contraseña de administrador por una robusta. Descargar e instalar la última actualización de firmware desde la web oficial del fabricante. Desactivar servicios que no uso (Wi-Fi Direct, impresión remota). | Esta semana |
| **Smart TV** | Redireccionamiento de URL a sitios no fiables desde el navegador integrado o apps. | Verificar que la opción de actualización automática esté activada. No descargar nunca firmware desde enlaces en pantalla. Usar solo el menú oficial: Ajustes > Soporte > Actualización de software. | Ya está configurado. Lo revisaré cada 3 meses. |

---

#### 📅 2. Plan de monitoreo y actualizaciones periódicas

Para no olvidarme del firmware, establezco el siguiente plan de monitoreo:

| Frecuencia | Acción | Dispositivos a revisar |
|------------|--------|------------------------|
| **Cada 3 meses** | Revisar manualmente si hay nuevas versiones de firmware disponibles. | Router, impresora, Smart TV y cualquier otro dispositivo conectado a la red. |
| **Cada vez que reciba una notificación** | Instalar la actualización lo antes posible, especialmente si menciona "parche de seguridad". | Cualquier dispositivo que me avise. |
| **Una vez por año** | Hacer una auditoría completa de todos los dispositivos conectados a mi red WiFi (IoT, periféricos, electrodomésticos inteligentes) y verificar su estado. | Todos los dispositivos de la red doméstica. |
| **Cuando compre un dispositivo nuevo** | Cambiar contraseñas por defecto, activar actualizaciones automáticas y verificar que tenga la última versión de firmware antes de empezar a usarlo. | Cualquier dispositivo nuevo que agregue a la red. |

**Herramientas que voy a usar:**
- **Calendario digital** (Google Calendar o similar) para programar recordatorios cada 3 meses.
- **App del fabricante** de cada dispositivo para recibir notificaciones de actualización.
- **Web oficial del fabricante** como fuente confiable para descargar firmware.

---

#### 💭 Razonamiento

> Durante esta actividad descubrí que el firmware es la base de la seguridad de cualquier dispositivo y que, a diferencia del software, casi nadie le presta atención. Mi impresora llevaba meses desactualizada con una vulnerabilidad conocida, y el panel de mi router transmitía datos sin cifrar. Son riesgos silenciosos.
>
> Mi plan de acción se basa en tres pilares: **corregir las vulnerabilidades ya identificadas, establecer recordatorios periódicos para no volver a olvidarlo y usar siempre canales oficiales** para las actualizaciones. De esta forma reduzco significativamente la superficie de ataque de mi red doméstica sin necesidad de ser un experto en ciberseguridad.
>
> Lo más importante que aprendí es que la seguridad del firmware no es algo que se hace una sola vez, sino un hábito que hay que mantener en el tiempo.

---

### ✅ Resumen del plan completo

| Paso | ¿Qué hice? | Resultado |
|------|------------|-----------|
| **Paso 1** | Identifiqué dispositivos con firmware en mi red. | Router, impresora y Smart TV. |
| **Paso 2** | Detecté vulnerabilidades y formas de prevenirlas. | Falta de cifrado, falta de autenticación y redireccionamiento a sitios no fiables. |
| **Paso 3** | Revisé la última actualización de firmware. | La impresora estaba desactualizada. Router y TV al día. |
| **Paso 4** | Creé un plan de acción y monitoreo. | Acciones inmediatas + recordatorios trimestrales. |

## 📱 Jailbreaking y rooting

Las computadoras personales permiten modificar o reemplazar el sistema operativo y el firmware con bastante flexibilidad. Pero los teléfonos inteligentes tienen más restricciones: los fabricantes limitan a propósito lo que el usuario puede modificar del sistema operativo.

Algunos usuarios sortean estas restricciones mediante **jailbreaking** o **rooting**. Estos procesos permiten:
- Instalar aplicaciones no autorizadas (que no están en la tienda oficial).
- Modificar la configuración del sistema.
- Personalizar la interfaz de usuario más allá de lo permitido.

### 🆚 Diferencia entre jailbreak y root

| Término | Se usa para | ¿Qué hace? |
|---------|-------------|------------|
| **Jailbreak** | iPhones (iOS) | Elimina las restricciones impuestas por Apple para acceder al sistema operativo subyacente. |
| **Rooting** | Android | Obtiene permisos de "superusuario" (root) para acceder y modificar archivos del sistema que normalmente están bloqueados. |

Ambos métodos implican **eliminar las restricciones de software que el fabricante implementó intencionalmente**, abriendo la puerta a instalar software que el fabricante no puso a disposición.

### ⚠️ ¿Por qué no es seguro?

| Riesgo | Explicación |
|--------|-------------|
| **Oportunidad para ciberdelincuentes** | Al eliminar las protecciones del sistema, un atacante tiene más facilidad para hackear el teléfono y acceder a tus datos personales. |
| **Viola los términos y condiciones** | El fabricante ya no se hace responsable. Esto te expone a vulnerabilidades de seguridad, posibles fallos del sistema y pérdida de actualizaciones automáticas. |
| **Anula la garantía** | Si el teléfono se daña, el fabricante puede negarse a repararlo porque el dispositivo fue modificado ilegalmente. |
| **Filtración de datos** | Al instalar aplicaciones no verificadas, aumentan las posibilidades de que una app maliciosa robe información sensible (contraseñas, fotos, datos bancarios). |

### 🧠 En resumen

> Hacer jailbreak o rooting a un teléfono es como quitarle las cerraduras de seguridad a una puerta para poder abrirla más fácilmente. Ganás algo de libertad, pero dejás la puerta abierta para cualquiera que quiera entrar.

| Ventaja (lo que busca el usuario) | Desventaja (el riesgo real) |
|-----------------------------------|-----------------------------|
| Instalar apps no oficiales. | Esas apps pueden contener malware. |
| Personalizar el sistema al máximo. | El sistema queda vulnerable a ataques. |
| Tener control total del dispositivo. | Se pierden las actualizaciones automáticas de seguridad. |
| Sentir "libertad" sobre el fabricante. | Se anula la garantía y se violan los términos de uso. |

> *"La seguridad y el control que ofrece el fabricante existen por una razón. Eliminarlos sin conocer los riesgos puede tener consecuencias graves."*

## 💼 Carrera profesional: Ingeniero de firmware

Si te interesa el mundo del firmware y la tecnología integrada, una opción profesional es convertirte en **ingeniero de firmware**. Este perfil trabaja desarrollando, probando y asegurando el software de bajo nivel que hace funcionar los dispositivos electrónicos.

### 📚 Requisitos para entrar en el campo

| Requisito | Detalle |
|-----------|---------|
| **Formación académica** | Licenciatura o título superior en **informática**, **ingeniería eléctrica** o un campo relacionado. |
| **Lenguajes de programación** | Experiencia con **C** y **lenguaje ensamblador**, los más usados para desarrollo de firmware por su cercanía al hardware. |
| **Experiencia práctica** | Muchas empresas valoran proyectos personales o contribuciones a proyectos de **código abierto** para ver tus habilidades en acción. |

### 🎓 Certificaciones relevantes

Obtener certificaciones puede ayudarte a destacar frente a otros candidatos:

| Certificación | Nombre completo |
|---------------|-----------------|
| **CFE** | Certified Firmware Engineer (Ingeniero de Firmware Certificado) |
| **CFSE** | Certified Firmware Security Engineer (Ingeniero de Seguridad de Firmware Certificado) |

### 🛠️ Cómo desarrollar tu portafolio

- **Proyectos personales:** crear firmware para dispositivos simples (como un controlador para luces LED, un termostato casero o un teclado personalizado).
- **Código abierto:** contribuir a proyectos de firmware en plataformas como GitHub. Esto demuestra que sabés trabajar en equipo y con código real.
- **Documentar tu trabajo:** mantener un repositorio ordenado con tus proyectos, explicando qué hace cada uno y cómo lo desarrollaste.

### 🧠 Perfil profesional

Un ingeniero de firmware combina conocimientos de:
- **Hardware:** entiende cómo funcionan los chips, los circuitos y los componentes electrónicos.
- **Software de bajo nivel:** programa en lenguajes cercanos al hardware para controlar el comportamiento del dispositivo.
- **Seguridad:** cada vez es más importante proteger el firmware contra ataques (bootkits, rootkits, inyección de código).

> *"El firmware está en todas partes: desde un router hasta un marcapasos. Los ingenieros de firmware son quienes construyen la base sobre la que funciona todo lo demás."*

## 🖥️ Servidores y sistemas operativos

La mayoría de las personas no piensa en los servidores ni en los sistemas operativos que usan a diario. Solo esperan que un servidor sea confiable y que el sistema operativo funcione sin problemas para poder abrir sus aplicaciones y archivos.

Pero desde el punto de vista de la ciberseguridad, es fundamental conocer:
- Los **diferentes tipos de servidores** que existen.
- Los **diferentes sistemas operativos** y para qué escenarios se adapta mejor cada uno.
- Cómo protegerlos y configurarlos correctamente para reducir la superficie de ataque.

### 📋 Lo que vamos a ver en esta lección

- Tipos de servidores (web, correo, base de datos, archivos, etc.).
- Sistemas operativos más comunes (Windows Server, Linux, macOS Server).
- En qué entornos se utiliza cada uno.
- Consideraciones de seguridad específicas para servidores y SO.

### 🖧 Servidores

Un **servidor** es un dispositivo o sistema de software especializado que almacena y procesa datos, actuando como un concentrador central en una red. Su función principal es proporcionar datos y servicios a otros dispositivos, llamados **clientes**, que se conectan a él.

#### 🔑 Características clave de los servidores

| Característica | Explicación | Ejemplo |
|----------------|-------------|---------|
| **Gestiona los recursos de red** | Administra y distribuye funcionalidades a los clientes que se conectan. | Alojar sitios web, entregar datos, enviar y recibir correos electrónicos, limitar accesos. |
| **Comparte recursos con máquinas cliente** | Las computadoras personales (PC) conectadas a un switch o router acceden a los servicios del servidor. | Navegar por sitios web, consultar correos, comunicarse con otros usuarios en la red. |
| **Existe en forma física o virtual** | Al principio eran dispositivos físicos dedicados. Hoy también existen servidores virtuales alojados en la nube. | Un servidor físico en una oficina o un servidor virtual contratado en AWS, Google Cloud o Azure. |

#### 📊 Evolución de los servidores

| Antes | Ahora |
|-------|-------|
| Dispositivos físicos simples que transmitían datos a computadoras más potentes. | Manejan tareas complejas y pueden ser **servidores virtuales** en plataformas de computación en la nube. |
| Estaban en una sala dentro de la empresa. | Están alojados en centros de datos remotos y brindan servicios a través de Internet. |

#### 🧠 En resumen

> Un servidor es como una biblioteca central: almacena información y la presta a quien la solicite. Puede ser una biblioteca física (servidor tradicional) o una biblioteca digital accesible desde cualquier lugar (servidor en la nube).

### 📂 Tipos de servidores

Existen muchos tipos de servidores, cada uno diseñado para un propósito específico. Las organizaciones y las personas los utilizan para gestionar recursos de red, atender solicitudes de datos y garantizar el buen funcionamiento de los servicios de Internet e intranet.

| Tipo de servidor | ¿Qué hace? | Ejemplo de uso |
|------------------|------------|----------------|
| **Servidor web** | Almacena datos de sitios web y los entrega a los navegadores mediante HTTP. Es uno de los más comunes. | Cuando entrás a `google.com`, un servidor web te envía la página. |
| **Servidor proxy** | Intercepta los datos que envía un sitio web y los reenvía a tu computadora. Agrega una capa de seguridad al actuar como intermediario. | Una empresa que filtra sitios maliciosos antes de que lleguen a los empleados. |
| **Servidor FTP** | Facilita la transferencia de archivos entre computadoras. Los archivos se suben al servidor o se descargan desde él. | Subir archivos a un hosting para publicar una página web. |
| **Servidor de aplicaciones** | Conecta a los usuarios con aplicaciones de software mediante conexiones virtuales, sin necesidad de descargar datos en su hardware. | Una empresa que permite usar un programa de contabilidad desde el navegador sin instalarlo. |
| **Servidor de archivos** | Almacena archivos de datos para varios usuarios, permitiendo acceso rápido y seguro. Varios usuarios pueden compartir archivos al mismo tiempo. | Una carpeta compartida en la oficina donde todos guardan documentos. |
| **Servidor de base de datos** | Funciona como un gran espacio de almacenamiento al que las organizaciones acceden para ejecutar múltiples programas. Funciona independientemente de la arquitectura de la base de datos. | Un sistema que guarda millones de registros de clientes y ventas. |
| **Servidor de correo** | Almacena y entrega correos electrónicos. Está conectado continuamente a la red para que los usuarios accedan a su email sin ejecutar nada en sus dispositivos. | Gmail, Outlook corporativo. |
| **Servidor de impresión** | Conecta computadoras locales a una impresora a través de la red. Permite que todo un departamento use una sola impresora. | La impresora de la oficina a la que todos mandan trabajos por WiFi. |
| **Servidor DNS** | Traduce nombres de dominio legibles (como `google.com`) en direcciones IP que las computadoras entienden. | Cuando escribís una dirección en el navegador, el DNS la convierte en números para encontrarla. |
| **Servidor de colaboración** | Facilita la conexión cuando varios usuarios necesitan compartir trabajo, archivos, aplicaciones y grandes cantidades de datos. | Google Workspace, Microsoft Teams, Slack. |
| **Servidor de juegos** | Aloja juegos multijugador en línea y conecta a jugadores de todo el mundo. | Fortnite, Minecraft, League of Legends. |
| **Servidor de supervisión y gestión** | Registra y rastrea transacciones digitales. Algunos solo monitorean y alertan a los administradores de red sobre amenazas o errores. | Un panel que avisa si un servidor se cae o si hay un intento de intrusión. |

#### 🧠 En resumen

> Cada tipo de servidor cumple una función específica dentro de una red. Algunos entregan páginas web, otros guardan archivos, otros traducen direcciones y otros nos permiten jugar en línea. Todos trabajan juntos para que los servicios digitales funcionen sin interrupciones.

### 💻 Sistemas operativos (SO)

Un **sistema operativo (SO)** es un software que gestiona todas las aplicaciones, programas y recursos de hardware de una computadora, y proporciona una interfaz para que el usuario interactúe con ella.

**Objetivo principal:** mantener el correcto funcionamiento del hardware y del software.

#### 🧩 Componentes que gestiona un sistema operativo

| Componente | ¿Qué hace? |
|------------|------------|
| **Procesos** | Monitorea los programas en ejecución y gestiona su ejecución. |
| **Subprocesos** | Maneja rutas de ejecución individuales dentro de los procesos. |
| **Archivos** | Organiza y controla el acceso a los archivos. |
| **Dispositivos** | Coordina la comunicación con dispositivos como impresoras y discos duros. |
| **Redes** | Gestiona las conexiones de red y el intercambio de datos. |
| **Aplicaciones** | Gestiona las aplicaciones instaladas en el sistema. |
| **Recursos** | Asigna recursos de CPU y memoria a los distintos programas. |

---

### 🥾 Programa de arranque (Bootloader)

El **programa de arranque** es un software que carga el sistema operativo en la computadora al encenderla, permitiendo que las aplicaciones interactúen con el hardware.

**Características:**
- Reside en el firmware (BIOS/UEFI).
- Se ejecuta en el momento del encendido.
- Sin él, la computadora no puede iniciar el SO ni ejecutar aplicaciones.

**Analogía:** es como el encargado de abrir el teatro y encender todas las luces antes de que lleguen los actores y el público.

---

### ⚙️ Kernel (Núcleo)

El **kernel** es el componente central del sistema operativo. Es un software que gestiona las funciones esenciales:

| Función del kernel | ¿Qué hace? |
|--------------------|------------|
| **Gestión de memoria** | Administra la RAM y decide qué programas pueden usarla. |
| **Controladores de dispositivos** | Permite que el SO se comunique con el hardware (impresoras, teclados, discos). |
| **Programación de procesos** | Decide qué programa se ejecuta en cada momento y por cuánto tiempo. |
| **Coordinación hardware-software** | Garantiza que el hardware y el software trabajen juntos sin conflictos. |

**¿Cómo se comunican las aplicaciones con el kernel?**
Los programas usan una **API (interfaz de programa de aplicación)** designada que el kernel proporciona para solicitar servicios específicos del sistema operativo.

**Analogía:** el kernel es como el director de la obra de teatro. No se ve desde el público, pero coordina a los actores, la iluminación y el sonido para que todo funcione.

---

### 🔄 Relación entre firmware, bootloader, kernel y SO

> *"El sistema operativo es el gran coordinador. El bootloader lo despierta, el kernel lo sostiene y las aplicaciones le dan vida."*

Usuario (vos) → Aplicaciones (Chrome, Word) → Sistema operativo (Windows, Linux) → KERNEL → Hardware (CPU, RAM, disco)
                                                                                      ↑
                                                                               Único que toca
                                                                               el hardware directamente

### 🧠 El Kernel: el núcleo del sistema operativo

**Kernel** significa literalmente **"núcleo"** en inglés. Es el corazón del sistema operativo y pertenece a lo que se conoce como **capa de bajo nivel**: es el único programa que se comunica directamente con el hardware.

#### 🚗 Analogía: el kernel es como el motor de un auto

| Parte del auto | Equivalente en una computadora |
|----------------|--------------------------------|
| **Motor** | **Kernel** |
| Volante, pedales, tablero | Sistema operativo (interfaz) |
| El conductor | El usuario |
| El auto completo | La computadora |

- Como conductor no tocás el motor directamente. Usás el volante y los pedales.
- Pero **sin motor, el auto no se mueve**, por más que el volante esté perfecto.
- El kernel es igual: vos no lo ves ni lo tocás, pero sin él **no funciona nada**.

---

#### ⚙️ ¿Qué hace exactamente el kernel?

Las aplicaciones (Chrome, Word, Spotify) no pueden hablar directamente con la memoria RAM, el disco duro o el procesador. Cada vez que necesitan algo, se lo piden al kernel.

| Tarea del kernel | Ejemplo concreto |
|------------------|------------------|
| **Administrar la memoria RAM** | Si abrís Chrome y Spotify al mismo tiempo, el kernel decide cuánta RAM le da a cada uno para que no choquen. |
| **Hablar con los dispositivos** | Cuando mandás a imprimir, el kernel traduce tu orden para que la impresora entienda qué hacer. |
| **Repartir el tiempo del procesador** | Si tenés varios programas abiertos, el kernel le da milisegundos a cada uno por turno, tan rápido que parece que funcionan todos a la vez. |
| **Controlar el acceso a los archivos** | Cuando guardás un documento, el kernel decide dónde se escribe físicamente en el disco. |

---

#### 🎭 El kernel como "traductor" y "policía de tránsito"

| Rol | ¿Qué hace? |
|-----|------------|
| **Traductor** | Las aplicaciones hablan "idioma humano", el hardware habla "idioma máquina". El kernel traduce entre ambos. |
| **Policía de tránsito** | Si todas las aplicaciones intentaran usar el procesador a la vez, sería un caos absoluto. El kernel organiza los turnos. |

---

#### 📊 ¿Dónde está el kernel en la pirámide del sistema?


---

#### 💡 Ejemplo real paso a paso

Imaginá que estás escuchando música en Spotify mientras escribís en Word:

1. **Spotify** le dice al kernel: "Necesito enviar sonido a los parlantes".
2. **Word** le dice al kernel: "Necesito guardar este archivo en el disco".
3. El **kernel** organiza: le da un poquito de tiempo del procesador a Spotify, después a Word, después a Spotify, y así miles de veces por segundo.
4. **Resultado:** vos sentís que todo funciona al mismo tiempo y sin problemas.

---

#### 🎯 En resumen

> El kernel es el núcleo del sistema operativo y opera a bajo nivel. Es el único programa que controla directamente el hardware (procesador, memoria, disco, dispositivos) y organiza todo para que las aplicaciones funcionen sin chocar entre sí. Sin kernel, la computadora es una caja de chips que no sabe hacer nada.

#### 🔗 Relación con lo aprendido antes

| Tema anterior | Conexión con el kernel |
|---------------|------------------------|
| **Firmware (BIOS/UEFI)** | El firmware carga el bootloader, y este carga el kernel. El firmware está incluso más abajo que el kernel. |
| **Bootloader** | Es el programa que despierta al kernel y lo carga en memoria al encender la computadora. |
| **Rootkits / Bootkits** | Atacan justo estas capas bajas: el kernel o el bootloader, para ocultarse del antivirus y del usuario. |
| **Sistema operativo** | El kernel es el núcleo del SO. El resto del SO (interfaz gráfica, herramientas) se apoya sobre él. |


### 📱 Tipos de sistemas operativos

Los sistemas operativos evolucionaron para adaptarse al nuevo hardware y a las distintas necesidades de los usuarios. Hoy existen tres tipos principales, cada uno optimizado para un entorno específico.

| Tipo de SO | ¿Para qué está diseñado? | ¿En qué se enfoca? | Ejemplos |
|------------|--------------------------|--------------------|----------|
| **SO de servidor** | Gestionar y ejecutar servidores. | Seguridad avanzada, estabilidad y compatibilidad con muchas conexiones de usuarios a la vez. | Red Hat Enterprise Linux Server, Windows Server |
| **SO de estación de trabajo** | Computadoras de escritorio o portátiles. | Tareas domésticas y de oficina: navegación web, email, creación de documentos, diseño gráfico, desarrollo de software. | Windows, macOS, Linux |
| **SO móvil** | Teléfonos inteligentes, tabletas y dispositivos portátiles. | Interfaces táctiles, eficiencia energética y conectividad conveniente. | iOS, Android |

---

#### 🖥️ SO de servidor

- Están optimizados para **gestionar redes** y **proporcionar recursos a los clientes**.
- Ejecutan **aplicaciones multiusuario** (muchas personas conectadas al mismo tiempo).
- La **seguridad** y la **estabilidad** son prioritarias: un servidor no puede reiniciarse inesperadamente.

**Ejemplos:**
- **Red Hat Enterprise Linux Server:** muy usado en entornos empresariales por su soporte y estabilidad.
- **Windows Server:** común en empresas que ya usan el ecosistema Microsoft.

---

#### 💻 SO de estación de trabajo

- Son los que usamos a diario en nuestras computadoras personales.
- Se destacan en tareas como:
  - Navegación web
  - Correo electrónico
  - Creación de documentos (Word, Excel)
  - Diseño gráfico (Photoshop, Illustrator)
  - Desarrollo de software (programación)

**Ejemplos:**
- **Windows:** el más usado a nivel mundial en hogares y oficinas.
- **macOS:** exclusivo de computadoras Apple, muy usado en diseño y desarrollo.
- **Linux (Ubuntu, Fedora, Debian):** gratuito, de código abierto y muy popular entre desarrolladores y servidores.

---

#### 📱 SO móvil

- Diseñados para **dispositivos portátiles**: teléfonos, tabletas, smartwatches.
- Optimizados para:
  - **Interfaces táctiles** (gestos, teclado en pantalla).
  - **Eficiencia energética** (batería de larga duración).
  - **Conectividad** (WiFi, datos móviles, Bluetooth).

**Ejemplos:**
- **iOS:** exclusivo de iPhones y iPads. Controlado por Apple.
- **Android:** usado por múltiples fabricantes (Samsung, Xiaomi, Motorola, Google). Basado en Linux.

---

### 🆚 Comparación rápida

| Característica | SO de servidor | SO de estación de trabajo | SO móvil |
|----------------|----------------|---------------------------|----------|
| **Usuarios simultáneos** | Cientos o miles | Uno (o pocos) | Uno |
| **Interfaz principal** | Línea de comandos o panel web | Escritorio gráfico | Pantalla táctil |
| **Prioridad** | Seguridad y estabilidad | Facilidad de uso y compatibilidad | Batería y conectividad |
| **Ejemplos** | Windows Server, Red Hat | Windows, macOS, Linux | iOS, Android |

> *"Cada tipo de sistema operativo está optimizado para su entorno. No es lo mismo un SO que maneja cientos de usuarios en un servidor que uno que se usa con los dedos en una pantalla de 6 pulgadas."*

### 🪟 Windows

Microsoft creó **Windows**, el sistema operativo que es la columna vertebral de la mayoría de las computadoras personales (PC). La primera versión, Windows 1.0, se lanzó en **1985** y desde entonces se publicaron numerosas versiones.

Las versiones más recientes vienen en varias **ediciones**. El sistema operativo base es el mismo, pero algunas ediciones incluyen funciones adicionales por un costo extra.

#### 🏠 Windows Home

| Característica | Descripción |
|----------------|-------------|
| **Público objetivo** | Usuarios domésticos y hogares. |
| **Uso principal** | Tareas cotidianas: navegación web, correo, documentos, entretenimiento, juegos. |
| **Funciones incluidas** | Windows Defender, Cortana, Microsoft Edge, Windows Hello, soporte para pantalla táctil. |
| **Limitaciones** | No incluye funciones avanzadas de administración, seguridad empresarial ni virtualización. |
| **Precio** | Es la edición más económica. Viene preinstalada en la mayoría de las computadoras de consumo. |

**¿Para quién es ideal?**
- Uso personal y familiar.
- Estudiantes.
- Tareas de oficina básicas.
- Gaming casual.

---

#### 💼 Windows Professional (Pro)

| Característica | Descripción |
|----------------|-------------|
| **Público objetivo** | Pequeñas y medianas empresas, profesionales de TI y usuarios avanzados. |
| **Uso principal** | Entornos corporativos, administración remota y seguridad mejorada. |
| **Funciones incluidas (además de las de Home)** | BitLocker (cifrado de disco), Escritorio remoto, Hyper-V (virtualización), unirse a dominios, políticas de grupo. |
| **Seguridad** | Mayor control sobre actualizaciones y configuraciones de seguridad empresarial. |
| **Precio** | Más cara que la edición Home. |

**¿Para quién es ideal?**
- Profesionales que necesitan cifrado de datos (BitLocker).
- Empresas que gestionan muchas computadoras en red.
- Usuarios que necesitan virtualización o escritorio remoto.
- Equipos que deben unirse a un dominio corporativo.

---

#### 🆚 Comparación rápida

| Característica | Windows Home | Windows Professional |
|----------------|--------------|----------------------|
| **Público** | Hogares y uso personal | Empresas y profesionales |
| **Cifrado BitLocker** | ❌ No | ✅ Sí |
| **Escritorio remoto** | ❌ No (solo cliente) | ✅ Sí (cliente y servidor) |
| **Hyper-V (virtualización)** | ❌ No | ✅ Sí |
| **Unirse a un dominio** | ❌ No | ✅ Sí |
| **Políticas de grupo** | ❌ Limitadas | ✅ Completas |
| **Precio** | Más económico | Más caro |

---

#### 💭 Dato personal

> La mayoría de las computadoras que compramos en tiendas vienen con Windows Home preinstalado. Para el uso diario es más que suficiente. Windows Professional se vuelve necesario en entornos laborales donde se necesita mayor seguridad, administración remota o virtualización. Conocer la diferencia ayuda a elegir la edición correcta según lo que necesitemos.

> *"Windows es el sistema operativo de escritorio más utilizado del mundo. Saber qué edición usar es parte de una buena estrategia de seguridad y productividad."*


### 🍎 macOS

**macOS** es el sistema operativo desarrollado por Apple para sus computadoras Mac. Se lanzó por primera vez en **2001** como Mac OS X. Al igual que Windows en las PC, macOS es el sistema que gestiona el hardware y el software de las computadoras Apple.

**Diferencia clave:** macOS **solo está disponible para computadoras Apple**. Esta exclusividad es una de las principales razones por las que muchas personas eligen comprar una Mac.

#### 🔑 Características clave

| Característica | Descripción |
|----------------|-------------|
| **Actualizaciones de seguridad** | Apple publica actualizaciones periódicas que corrigen vulnerabilidades y mejoran la protección del sistema. Las actualizaciones son gratuitas y se instalan fácilmente desde la App Store. |
| **Basado en Unix** | macOS está construido sobre una base Unix, lo que le da gran estabilidad, seguridad y potencia. Esto también lo hace muy usado por desarrolladores de software. |
| **Fácil de usar** | La interfaz gráfica es intuitiva, limpia y diseñada para que cualquiera pueda usarla sin conocimientos técnicos avanzados. |

---

#### 🛡️ Actualizaciones de seguridad

- Apple lanza **parches de seguridad** regularmente.
- Las actualizaciones son **gratuitas** para todos los usuarios de Mac.
- Se instalan directamente desde la **App Store** o desde "Configuración del Sistema".
- macOS incluye protecciones integradas como **Gatekeeper** (bloquea apps no verificadas), **XProtect** (antimalware integrado) y **FileVault** (cifrado de disco).

---

#### 🐧 Basado en Unix

- Unix es un sistema operativo robusto y estable que existe desde los años 70.
- macOS está certificado como sistema **Unix**, lo que significa que hereda su seguridad y arquitectura.
- Esto permite:
  - Ejecutar comandos de terminal similares a Linux.
  - Mayor estabilidad en servidores y entornos de desarrollo.
  - Separación clara de permisos de usuario y administrador.

---

#### ✨ Fácil de usar

- Interfaz gráfica minimalista y consistente.
- Integración total con otros dispositivos Apple (iPhone, iPad, Apple Watch).
- Funciones como:
  - **Spotlight:** búsqueda rápida de archivos, apps y correos.
  - **Mission Control:** vista de todas las ventanas abiertas.
  - **Gestos táctiles:** en trackpad para navegar fluidamente.
- Ideal para usuarios que quieren que "todo funcione" sin configuraciones complicadas.

---

#### 🆚 macOS vs Windows

| Característica | macOS | Windows |
|----------------|-------|---------|
| **Fabricante** | Apple | Microsoft |
| **Hardware** | Solo Mac | Múltiples marcas (Dell, HP, Lenovo, etc.) |
| **Base del sistema** | Unix | Windows NT |
| **Interfaz** | Minimalista, consistente | Personalizable, más extendida |
| **Seguridad** | Muy controlada (ecosistema cerrado) | Más vulnerable por ser más abierto y popular |
| **Software disponible** | Menos juegos, excelente para diseño y desarrollo | Mayor cantidad de software y juegos |
| **Precio del hardware** | Más caro | Variedad de precios |
| **Actualizaciones** | Gratuitas y frecuentes | Gratuitas y frecuentes |

> *"macOS combina la estabilidad de Unix con una interfaz fácil de usar. Su ecosistema cerrado le da ventajas de seguridad, pero limita la personalización y la variedad de hardware."*


### 🐧 Linux

**Linux** es una familia de sistemas operativos de **código abierto** basados en Unix. Aunque pocas personas lo usan en sus computadoras de escritorio, Linux está en todas partes:

- **Android**, uno de los sistemas móviles más populares del mundo, se ejecuta sobre Linux.
- La mayoría de los **dispositivos de red**, **aplicaciones de seguridad** y **servidores en la nube** funcionan con Linux.

#### 📦 Distribuciones

La familia Linux incluye cientos de versiones diferentes, llamadas **distribuciones** o "distros". Cada una está optimizada para un propósito específico.

| Distribución | ¿Para qué se usa? |
|--------------|-------------------|
| **Ubuntu** | Una de las más populares. Ideal para principiantes y uso doméstico. |
| **Fedora** | Enfocada en software libre y últimas tecnologías. Muy usada por desarrolladores. |
| **Debian** | Conocida por su estabilidad. Base de muchas otras distribuciones (incluido Ubuntu). |
| **Red Hat Enterprise Linux** | Uso empresarial y servidores. |
| **Kali Linux** | Especializada en ciberseguridad y pruebas de penetración. |

Muchas distribuciones son **sistemas operativos de estación de trabajo** que pueden instalarse en computadoras hogareñas, incluso en equipos diseñados originalmente para Windows o macOS.

---

#### ⚙️ Componentes de Linux

Además del bootloader y el kernel, Linux tiene varios componentes que trabajan juntos:

| Componente | ¿Qué hace? | Analogía sencilla |
|------------|------------|-------------------|
| **Init system** | Gestiona el proceso de inicialización del sistema. Es el primer proceso que se inicia cuando el kernel se carga en memoria durante el arranque. También controla los demonios. | Es como el director de orquesta que levanta todos los servicios al encender la computadora. |
| **Daemons** | Servicios en segundo plano que se inician durante el arranque o al iniciar sesión. No los ve el usuario pero están siempre trabajando. | Como los empleados de limpieza de un teatro: trabajan de fondo mientras el público disfruta la obra. |
| **Servidor gráfico** | Subsistema que muestra los gráficos en el monitor. Convierte las órdenes del sistema en imágenes que vemos en pantalla. | El proyector que muestra la película en el cine. |
| **Entornos de escritorio** | Los usuarios pueden elegir entre múltiples entornos donde interactúan con el SO. Cada uno trae sus propias aplicaciones integradas. | Es como elegir la decoración y los muebles de una habitación: la estructura es la misma, pero la apariencia cambia. |
| **Aplicaciones** | Linux tiene una amplia gama de aplicaciones gratuitas que se instalan fácilmente desde la "tienda" de cada distribución. | Similar a la App Store de Apple o la Microsoft Store. |

---

#### 🎨 Entornos de escritorio más populares

| Entorno | Características |
|---------|-----------------|
| **GNOME** | Moderno, minimalista. Usado por defecto en Ubuntu. |
| **KDE Plasma** | Altamente personalizable, muy visual. |
| **XFCE** | Ligero y rápido, ideal para computadoras viejas. |
| **Cinnamon** | Parecido a Windows, fácil de usar para principiantes. |

---

#### 🆚 Linux vs Windows vs macOS

| Característica | Linux | Windows | macOS |
|----------------|-------|---------|-------|
| **Código** | Abierto (gratis) | Cerrado (pago) | Cerrado (incluido con el hardware) |
| **Personalización** | Total | Limitada | Muy limitada |
| **Seguridad** | Muy alta (permisos estrictos) | Mejoró mucho, pero más atacado | Alta (ecosistema cerrado) |
| **Software disponible** | Muy variado (gratuito) | El más amplio | Bueno para diseño y desarrollo |
| **Uso principal** | Servidores, desarrollo, ciberseguridad | Hogares, oficinas, gaming | Diseño, desarrollo, uso personal |
| **Facilidad de uso** | Curva de aprendizaje más alta | Muy fácil | Muy fácil |

---

#### 🧠 ¿Por qué es importante en ciberseguridad?

- La mayoría de las herramientas de seguridad y hacking ético se ejecutan en Linux (Kali Linux, Parrot OS).
- Los servidores que protegen las empresas suelen usar Linux.
- Ser usuario root (administrador total) permite un control absoluto... pero también un riesgo mayor si no se sabe lo que se hace.

> *"Linux puede parecer intimidante al principio, pero es el sistema operativo que gobierna Internet en silencio. Aprenderlo es una de las mejores inversiones en ciberseguridad."*

### 💼 Gestión de carrera: Administrador de sistemas certificado de Red Hat (RHCSA)

Muchos fabricantes de sistemas operativos ofrecen **certificaciones** para validar los conocimientos sobre sus sistemas. Red Hat, una de las empresas más importantes en el mundo Linux, proporciona varias certificaciones.

#### 🎓 Red Hat Certified System Administrator (RHCSA)

Es una certificación ideal para **estudiantes** y **administradores de sistemas** que quieren validar sus habilidades y mostrarlas a posibles empleadores.

#### 📋 Tareas que realiza un administrador certificado de Red Hat

| Área | Tareas específicas |
|------|--------------------|
| **Gestión de usuarios y grupos** | Crear, modificar y eliminar usuarios. Asignar permisos y gestionar grupos de trabajo. |
| **Despliegue y mantenimiento de sistemas** | Instalar software, aplicar actualizaciones, configurar servicios principales y mantener los sistemas en funcionamiento. |
| **Seguridad** | Configurar firewalls básicos y aplicar políticas de seguridad para proteger los servidores. |
| **Herramientas esenciales** | Manejar archivos, directorios, entornos de línea de comandos y documentación del sistema. |

#### 🧠 ¿Por qué es valiosa esta certificación?

- **Red Hat** es una de las distribuciones de Linux más usadas en entornos empresariales.
- Un RHCSA demuestra que sabés **administrar servidores Linux en producción**.
- Es una certificación muy valorada en el mercado laboral de TI y ciberseguridad.
- Sirve como base para certificaciones más avanzadas (Red Hat Certified Engineer - RHCE).

#### 🐧 Relación con lo aprendido

| Tema anterior | Conexión con RHCSA |
|---------------|-------------------|
| **Linux y sus distribuciones** | Red Hat Enterprise Linux es una de las distribuciones más importantes para servidores. |
| **Tipos de SO** | Red Hat es un sistema operativo de servidor. |
| **Kernel y línea de comandos** | Un administrador Red Hat trabaja constantemente con el kernel, demonios y la terminal. |
| **Seguridad de sistemas** | La certificación incluye gestión de firewalls y políticas de seguridad. |

> *"Las certificaciones como RHCSA son una excelente manera de demostrar que tenés conocimientos prácticos, no solo teoría. En ciberseguridad, saber administrar Linux es una habilidad fundamental."*


## 🛡️ Seguridad del sistema operativo

Proteger un sistema operativo es como proteger el corazón de una computadora. Si el corazón falla, todo el cuerpo deja de funcionar.

La **seguridad del sistema operativo (SO)** garantiza la **confidencialidad**, **integridad** y **disponibilidad** (los tres pilares de la seguridad informática) del sistema operativo y de todos los recursos que administra.

### 🎯 Objetivos de la seguridad del SO

| Objetivo | ¿Qué significa? |
|----------|-----------------|
| **Confidencialidad** | Que solo las personas autorizadas puedan acceder a los datos y recursos del sistema. |
| **Integridad** | Que los datos y el sistema no sean modificados sin autorización. |
| **Disponibilidad** | Que el sistema y sus recursos estén funcionando cuando se los necesite. |

### ⚠️ ¿De qué protegemos al SO?

La seguridad del SO implica implementar medidas para prevenir:
- **Acceso no autorizado** a cuentas y archivos del sistema.
- **Ataques maliciosos** como virus, gusanos, malware y ransomware.
- **Intrusiones remotas** de hackers que quieran tomar control del sistema.
- **Robo o destrucción de datos** sensibles.

### 📋 Lo que vamos a ver en esta lección

- Importancia de proteger un sistema operativo.
- Medidas de seguridad necesarias para defenderlo.
- Tipos de amenazas que atacan a los SO.
- Buenas prácticas de hardening (endurecimiento) del sistema.

> *"El sistema operativo administra todo el hardware y software. Si un atacante lo compromete, tiene acceso a todo lo demás. Por eso protegerlo es la prioridad número uno."*

### 🛡️ ¿Qué es la seguridad del sistema operativo?

La **seguridad del sistema operativo** es el proceso de garantizar la **confidencialidad, integridad y disponibilidad** (tríada CIA) del SO. Implica protegerlo de amenazas como:

- Virus
- Gusanos
- Malware
- Intrusiones remotas de hackers

#### 🔐 ¿Qué abarca?

Todas las medidas preventivas que salvaguardan cualquier activo informático que pueda ser **robado, editado o eliminado** si la seguridad del SO se ve comprometida.

**Ejemplo claro:** el iPhone
> Si te roban el iPhone y el ladrón ingresa el código de acceso incorrecto varias veces, el dispositivo puede configurarse para **restaurar su configuración de fábrica** automáticamente. Esto protege tus datos incluso si el dispositivo cae en manos equivocadas.

---

#### ⚠️ ¿Por qué es tan importante?

El sistema operativo tiene un **papel crucial** en la viabilidad de la información y los sistemas informáticos. Por eso, su seguridad impacta directamente en:

| Si el SO se ve comprometido... | Consecuencia |
|--------------------------------|--------------|
| **Todas las aplicaciones quedan expuestas** | Un atacante que controla el SO puede acceder a cualquier programa que se ejecute sobre él. |
| **Las aplicaciones pueden atacarse entre sí** | Si no se controlan y contienen correctamente, una app vulnerable puede ser la puerta de entrada para atacar a otras. |
| **Los datos del sistema quedan accesibles** | Archivos, contraseñas, documentos personales y configuraciones pueden ser robados o destruidos. |

---

#### 🧠 Analogía: el SO como los cimientos de un edificio

| Elemento | Equivalente en informática |
|----------|----------------------------|
| **Cimientos del edificio** | Sistema operativo |
| **Departamentos** | Aplicaciones (Word, Chrome, Spotify) |
| **Muebles y objetos de valor** | Datos y archivos personales |

- Si los cimientos se agrietan (SO comprometido), todos los departamentos quedan en peligro, sin importar qué tan seguros estén por dentro.
- Si un departamento se incendia (app vulnerable) y no hay contención, el fuego puede propagarse a todo el edificio.

---

#### 🎯 En resumen

> Proteger el sistema operativo no es opcional: es la **base de toda la seguridad informática**. Si el SO cae, todo lo que se ejecuta sobre él también cae. Las medidas preventivas (contraseñas, cifrado, actualizaciones, firewalls) son esenciales para mantenerlo a salvo.

| Pilar de seguridad | ¿Cómo se aplica al SO? |
|--------------------|------------------------|
| **Confidencialidad** | Solo usuarios autorizados acceden al sistema y a sus archivos. |
| **Integridad** | Los archivos del sistema no se modifican sin permiso. |
| **Disponibilidad** | El sistema operativo funciona correctamente cuando se lo necesita. |

### 🔒 La importancia del fortalecimiento (hardening) del sistema operativo

La seguridad del sistema es responsabilidad de todos. El **fortalecimiento del sistema** (o *hardening*) es una de las mejores formas de defender una organización contra las ciberamenazas.

#### 🎯 ¿Qué es el hardening?

Es el proceso de **asegurar un sistema informático o servidor reduciendo sus vulnerabilidades**. Consiste en eliminar o desactivar todo aquello que los ciberatacantes podrían explotar:

- Aplicaciones innecesarias del sistema.
- Cuentas de usuario que no se usan.
- Servicios y funciones que no son indispensables.
- Puertos abiertos sin uso.

A estos componentes se los conoce como **superficie de ataque**: son los puntos de entrada que los atacantes pueden aprovechar para infiltrarse.

---

#### ⚠️ ¿Por qué es importante?

| Problema | Consecuencia |
|----------|--------------|
| **Superficie de ataque amplia** | Cuantos más servicios, aplicaciones y cuentas activas haya, más puntos de entrada tienen los hackers y el malware. |
| **Acceso a información confidencial** | A través de esos puntos de entrada, los atacantes pueden llegar a datos valiosos de la organización o del usuario. |
| **Sin hardening, el riesgo aumenta** | Cada componente innecesario que queda activo es una oportunidad para un ciberataque. |

**Beneficio del hardening:**
> Reduce la vulnerabilidad ante amenazas cibernéticas y disminuye la probabilidad de que un atacante logre acceder a la red.

---

#### 🛠️ Prácticas estándar de hardening

| Práctica | ¿En qué consiste? | Ejemplo |
|----------|-------------------|---------|
| **Implementar controles de acceso** | Asegurar que solo las personas autorizadas puedan acceder a determinados archivos, configuraciones o partes del sistema. | Usar contraseñas fuertes, autenticación multifactor y permisos de usuario limitados. |
| **Deshabilitar servicios no utilizados** | Apagar o desinstalar servicios, puertos y aplicaciones que no sean necesarios para el funcionamiento del sistema. | Si no usás Bluetooth, lo desactivás. Si un puerto de red no se usa, lo cerrás. |
| **Gestionar parches** | Mantener el sistema operativo y todas las aplicaciones actualizadas con los últimos parches de seguridad. | Activar actualizaciones automáticas y revisar manualmente cada cierto tiempo. |

---

#### 🧠 Analogía: una casa con muchas puertas

| Situación | Equivalente informático |
|-----------|-------------------------|
| Casa con 10 puertas y 20 ventanas abiertas | Sistema sin hardening (mucha superficie de ataque) |
| Cerrar puertas y ventanas que no se usan | Deshabilitar servicios y aplicaciones innecesarias |
| Poner cerraduras nuevas y una alarma | Implementar controles de acceso y monitoreo |
| Revisar que las cerraduras funcionen | Gestionar parches y actualizaciones |

> Cuantas menos puertas abiertas, más difícil es que un ladrón entre.

---

#### 🔗 Relación con temas anteriores

| Tema | Conexión con hardening |
|------|------------------------|
| **Superficie de ataque** (Seguridad del sistema) | El hardening reduce directamente la superficie de ataque. |
| **Plan de firmware de seguridad** | Actualizar firmware también es una práctica de hardening. |
| **Vulnerabilidades de firmware** | Deshabilitar servicios innecesarios es una medida de prevención. |
| **Autenticación y autorización** | Implementar controles de acceso es hardening en acción. |

> *"El hardening no es una tarea única, es un proceso continuo. Cada servicio que desactivás, cada parche que aplicás y cada permiso que limitás hace que el sistema sea un poco más seguro."*

### 🛡️ Protección de un sistema operativo host

El **sistema operativo host** es el que se ejecuta directamente en una máquina física, como una computadora o un servidor. Protegerlo implica implementar medidas para:

- Evitar el **acceso no autorizado**.
- Proteger contra **ataques maliciosos**.
- Garantizar la **confidencialidad, integridad y disponibilidad** de los recursos del sistema.

#### ✅ Mejores prácticas de protección

| Práctica | ¿En qué consiste? | Ejemplo concreto |
|----------|-------------------|------------------|
| **Actualizaciones y parches regulares** | Instalar actualizaciones de seguridad para el SO y las aplicaciones apenas estén disponibles. | Activar Windows Update o configurar `apt update` en Linux. |
| **Contraseñas seguras** | Exigir contraseñas robustas, aplicar reglas de complejidad y establecer políticas de caducidad. | Contraseñas de al menos 12 caracteres, con mayúsculas, números y símbolos. Cambiarlas cada 90 días. |
| **Restringir el acceso a la red** | Limitar el número de usuarios con privilegios administrativos, aplicar políticas de control de acceso e implementar firewalls. | Solo el personal de TI tiene cuenta de administrador. El resto usa cuentas estándar. |
| **Software antimalware y sistemas de detección** | Instalar y configurar antivirus, antimalware y sistemas de detección o prevención de intrusiones (IDS/IPS). | Windows Defender, Malwarebytes, Snort (IDS). |
| **Cifrado de datos** | Habilitar el cifrado de disco completo y cifrar datos confidenciales tanto en tránsito como en reposo. | BitLocker (Windows), FileVault (macOS), LUKS (Linux). HTTPS para datos en tránsito. |
| **Plan de copia de seguridad y recuperación** | Implementar un plan para respaldar datos críticos y poder restaurarlos ante una falla o un ataque. | Regla 3-2-1: 3 copias, en 2 medios distintos, 1 fuera de la oficina. |
| **Monitoreo de registros y alertas** | Revisar los logs del sistema en busca de actividad sospechosa y configurar alertas para notificar a los administradores. | Usar herramientas como SIEM, revisar el Visor de eventos de Windows o `/var/log` en Linux. |

---

#### 🔗 Las 7 prácticas en una sola vista
Actualizaciones y parches → Corregir vulnerabilidades conocidas

Contraseñas seguras → Proteger el acceso a las cuentas

Restringir acceso a la red → Limitar quién puede entrar y con qué permisos

Antimalware y detección → Detectar y frenar ataques activos

Cifrado de datos → Proteger la información si es robada

Copia de seguridad → Poder recuperarse si todo falla

Monitoreo y alertas → Darse cuenta a tiempo si algo anda mal
---

#### 🧠 ¿Por qué son importantes todas juntas?

Cada práctica cubre un aspecto distinto de la seguridad. Si falla una, las otras ayudan a contener el daño:

| Si falla... | ...todavía tenés |
|-------------|------------------|
| Una actualización | El firewall y el antimalware pueden frenar el ataque. |
| Una contraseña | El cifrado protege los datos aunque accedan al disco. |
| El firewall | El monitoreo de logs te avisa que algo raro está pasando. |

> *"Proteger un sistema operativo host no es una acción única, es una combinación de buenas prácticas que se refuerzan entre sí. La seguridad está en las capas."*

### 🔐 Protección de un sistema operativo

Además de proteger el sistema operativo host, la seguridad de **cualquier** sistema operativo es fundamental. Las ciberamenazas son cada vez más sofisticadas y frecuentes.

**¿Qué protege la seguridad del SO?**
- Datos confidenciales.
- Acceso no autorizado al sistema.
- Pérdidas financieras.
- Daños a la reputación.
- Responsabilidades legales.

---

#### 🛠️ Las 5 medidas esenciales para proteger un SO

| # | Medida | ¿En qué consiste? |
|---|--------|-------------------|
| 1 | **Gestión de parches** | Instalar actualizaciones de seguridad para corregir vulnerabilidades conocidas en el SO y las aplicaciones. |
| 2 | **Deshabilitar puertos y servicios innecesarios** | Cerrar todo lo que no se use para reducir la superficie de ataque. |
| 3 | **Habilitar el registro de eventos** | Activar los logs del sistema para registrar toda la actividad y poder detectar comportamientos sospechosos. |
| 4 | **Usar autenticación segura** | Implementar contraseñas fuertes, autenticación multifactor (MFA) y políticas de caducidad. |
| 5 | **Copia de seguridad de datos** | Realizar respaldos periódicos para poder recuperar la información ante un fallo, ataque o desastre. |

---

#### 1️⃣ Gestión de parches

- Mantener el SO y las aplicaciones **actualizados** con los últimos parches de seguridad.
- Las vulnerabilidades conocidas son la puerta de entrada más común para los atacantes.
- Automatizar las actualizaciones siempre que sea posible.

> *"Un sistema desactualizado es un blanco fácil. Los parches cierran las puertas que los hackers ya saben abrir."*

---

#### 2️⃣ Deshabilitar puertos y servicios innecesarios

- Cada servicio activo y cada puerto abierto es un **punto de entrada potencial**.
- Revisar qué servicios están corriendo y apagar los que no se necesitan.
- Cerrar puertos que no estén en uso mediante firewall.

**Ejemplo:** si no usás Bluetooth, desactivarlo. Si un servicio de impresión no se usa, apagarlo.

---

#### 3️⃣ Habilitar el registro de eventos (logging)

- Activar los **logs del sistema** para registrar:
  - Inicios de sesión (exitosos y fallidos).
  - Cambios en la configuración.
  - Acceso a archivos sensibles.
  - Actividad de red sospechosa.
- Los logs permiten **detectar intrusiones** y **analizar incidentes** después de que ocurran.

---

#### 4️⃣ Usar autenticación segura

- **Contraseñas fuertes:** largas, complejas y únicas para cada servicio.
- **Autenticación multifactor (MFA):** algo que sabés (contraseña) + algo que tenés (código en el celular).
- **Políticas de caducidad:** obligar a cambiar contraseñas periódicamente.
- **Principio de mínimo privilegio:** cada usuario debe tener solo los permisos que necesita.

---

#### 5️⃣ Copia de seguridad de datos

- Realizar **respaldos periódicos** de datos críticos.
- Seguir la **regla 3-2-1:**
  - **3** copias de los datos.
  - En **2** tipos de medios diferentes.
  - **1** copia fuera del sitio (nube u otra ubicación física).
- Probar las restauraciones periódicamente para asegurarse de que funcionan.

---

#### 🧠 Las 5 medidas en acción
Gestión de parches → Cerrar vulnerabilidades antes de que las exploten.

Deshabilitar puertos → Reducir puntos de entrada al sistema.

Registro de eventos → Saber qué pasó, cuándo y quién lo hizo.

Autenticación segura → Asegurar que solo los autorizados puedan entrar.

Copia de seguridad → Tener un plan B si todo lo demás falla.


> *"Estas cinco medidas son la base de la seguridad de cualquier sistema operativo. No son opcionales: son el piso mínimo para mantener los datos a salvo."*
### 🔄 Gestión de actualizaciones y parches

La **gestión de parches** es el proceso de actualizar software, controladores y firmware para proteger los sistemas contra vulnerabilidades. No solo mejora la seguridad, sino también el rendimiento y la productividad.

#### 🎯 ¿Por qué es crucial para una organización?

Proteger todos los sistemas evita:
- **Filtraciones de datos**.
- **Pérdida de productividad**.
- **Daños a la reputación**.

Los dispositivos que necesitan parches incluyen tanto computadoras de empleados como equipos sin usuario (quioscos, señalización digital, servidores).

#### ✅ Beneficios de la gestión de parches

| Beneficio | ¿En qué consiste? | Ejemplo |
|-----------|-------------------|---------|
| **Seguridad** | Corrige vulnerabilidades conocidas que los atacantes podrían explotar. Es el beneficio más importante. | Un parche que cierra un fallo por el que un hacker podía tomar control remoto del sistema. |
| **Tiempo de actividad del sistema** | Reduce las fallas y bloqueos al mantener el software estable y actualizado. Los sistemas parcheados se caen menos. | Un servidor que sigue funcionando sin interrupciones porque se aplicó un parche que corregía un error de memoria. |
| **Cumplimiento normativo** | Ayuda a cumplir con regulaciones de seguridad y privacidad que exigen tener los sistemas al día. | Normas como GDPR, HIPAA o PCI-DSS requieren que se apliquen parches de seguridad en tiempo y forma. |
| **Mejoras en las funciones** | Además de corregir errores, los parches pueden agregar nuevas características o mejorar las existentes. | Una actualización de Windows que incorpora una nueva herramienta de seguridad o mejora la interfaz. |

---

#### 🧠 Relación con temas anteriores

| Tema anterior | Conexión con la gestión de parches |
|---------------|-----------------------------------|
| **Hardening del sistema** | La gestión de parches es una de las prácticas estándar de hardening. |
| **Vulnerabilidades de firmware** | Los parches incluyen actualizaciones de firmware, no solo de software. |
| **Protección del SO host** | Es la primera medida de las mejores prácticas para proteger un SO. |
| **Plan de firmware de seguridad** | Revisar y actualizar firmware es parte de una buena gestión de parches. |

---

#### 🛠️ Buenas prácticas de gestión de parches

| Práctica | Descripción |
|----------|-------------|
| **Automatizar** | Activar actualizaciones automáticas en SO y aplicaciones siempre que sea posible. |
| **Inventariar** | Tener una lista de todos los dispositivos y software para saber qué necesita parches. |
| **Priorizar** | Aplicar primero los parches críticos de seguridad, luego los de rendimiento y funciones. |
| **Probar** | Si es un entorno empresarial, probar los parches en un sistema de prueba antes de implementarlos en producción. |
| **Monitorear** | Verificar que los parches se instalaron correctamente y no causaron problemas. |

> *"La gestión de parches no es opcional. Es la primera línea de defensa contra atacantes que buscan sistemas desactualizados. Un sistema sin parches es un sistema vulnerable."*

### 🧪 Escenario práctico: Configurar el Firewall de Windows Defender

#### 📋 Situación

Sos un **técnico de asistencia** en una compañía que emplea trabajadores remotos. Luke, uno de los empleados, usa una laptop Windows para trabajar. Tu tarea es asegurarte de que su dispositivo esté protegido, empezando por verificar que el **Firewall de Windows Defender** esté funcionando y correctamente configurado.

#### 🎯 Objetivo

Confirmar que el Firewall de Windows Defender esté activo y usando la configuración de seguridad recomendada por Microsoft. El firewall ayuda a:
- Detectar y responder a intentos de acceso no autorizado.
- Registrar anomalías en los logs que Luke puede revisar regularmente.

#### ⚙️ Paso a paso de la solución

| Paso | Acción | Resultado |
|------|--------|-----------|
| **1** | Abrir el menú de búsqueda de Windows y escribir `Firewall de Windows Defender`. | Aparece la herramienta de configuración del firewall. |
| **2** | Presionar Enter para abrir la ventana del Firewall de Windows Defender. | Se muestran las opciones de configuración del firewall. |
| **3** | Observar que el firewall no está usando la configuración recomendada. | Aparecen opciones como "Activar o desactivar Firewall de Windows Defender". |
| **4** | Seleccionar **"Turn Windows Defender Firewall on or off"** (Activar o desactivar el Firewall de Windows Defender). | Permite modificar la configuración. |
| **5** | Activar el firewall para redes de dominio, privadas y públicas según lo recomendado. | El firewall queda correctamente configurado y brindando protección óptima. |

#### ✅ Respuesta correcta

> Si el Firewall de Windows Defender no utiliza la configuración de seguridad recomendada, se debe seleccionar **"Activar o desactivar Firewall de Windows Defender"** para actualizar la configuración y garantizar una protección óptima.

#### 🔐 Opciones disponibles en el Firewall de Windows Defender

| Opción | ¿Qué hace? |
|--------|------------|
| **Allow an app or feature through Windows Defender Firewall** | Permite que aplicaciones específicas se comuniquen a través del firewall. |
| **Change notification settings** | Configura las notificaciones cuando el firewall bloquea algo. |
| **Turn Windows Defender Firewall on or off** | Activa o desactiva el firewall para cada tipo de red. |
| **Restore defaults** | Restaura la configuración original del firewall. |
| **Advanced settings** | Accede a reglas avanzadas de entrada/salida y seguridad de conexión. |

#### 🧠 Lección aprendida

> El firewall es la primera línea de defensa de un sistema operativo. Verificar que esté activo y correctamente configurado es una de las tareas más básicas y fundamentales en seguridad informática. Un firewall mal configurado o desactivado deja el sistema completamente expuesto.

### 🧪 Escenario práctico: Activar el Firewall en redes privadas y públicas (continuación)

#### 📋 Situación

Después de ingresar a la ventana **"Personalizar configuración"** del Firewall de Windows Defender, se observa que el firewall está **deshabilitado** tanto para redes privadas como públicas. Esto deja el dispositivo de Luke completamente expuesto a amenazas en línea.

---

#### ⚙️ Configuración encontrada (antes del cambio)

| Tipo de red | Estado del Firewall | ¿Es seguro? |
|-------------|---------------------|-------------|
| **Red privada** | ❌ Desactivado (no recomendado) | No |
| **Red pública** | ❌ Desactivado (no recomendado) | No |

---

#### 🔧 Paso a paso de la solución

| Paso | Acción | Explicación |
|------|--------|-------------|
| **1** | Ir a la sección **"Private network settings"** (Configuración de redes privadas). | Las redes privadas son redes de confianza, como la LAN de una oficina o el WiFi de casa. |
| **2** | Seleccionar **"Turn on Windows Defender Firewall"** (Activar Firewall de Windows Defender). | Esto habilita la protección para redes de confianza. |
| **3** | Repetir el proceso en **"Public network settings"** (Configuración de redes públicas). | Las redes públicas son las de cafeterías, aeropuertos o hotspots. Son menos seguras y necesitan protección extra. |
| **4** | Opcional: marcar la casilla **"Notify me when Windows Defender Firewall blocks a new app"** . | Así Luke recibirá notificaciones cuando el firewall bloquee algo y podrá decidir si permite la conexión. |

---

#### 🔐 ¿Por qué activar el firewall para redes privadas?

| Motivo | Explicación |
|--------|-------------|
| **Protege contra accesos no autorizados** | Aunque sea una red de confianza, puede haber dispositivos infectados o atacantes internos. |
| **Mejora la seguridad general** | Un firewall activo filtra el tráfico entrante y saliente. |
| **Garantiza integridad y confidencialidad** | Evita que malware o hackers accedan a los datos del dispositivo. |

> ✅ **Respuesta correcta:** Activar el Firewall de Windows Defender para redes privadas protege el dispositivo del acceso no autorizado y de posibles amenazas, mejorando la seguridad y garantizando la integridad y confidencialidad de los datos.

---

#### 🆚 Diferencia entre redes privadas y públicas

| Tipo de red | ¿Cuándo se usa? | Nivel de confianza | Configuración recomendada |
|-------------|-----------------|--------------------|---------------------------|
| **Red privada** | Hogar u oficina | Alta (red conocida) | Firewall activado. No bloquear todas las conexiones entrantes para permitir compartir archivos e impresoras. |
| **Red pública** | Cafeterías, aeropuertos, hotspots | Baja (red desconocida) | Firewall activado. Considerar bloquear todas las conexiones entrantes para máxima seguridad. |

---

#### 📋 Estado final deseado

| Tipo de red | Estado del Firewall |
|-------------|---------------------|
| **Red privada** | ✅ Activado |
| **Red pública** | ✅ Activado |

> *"Un firewall desactivado es como una puerta sin cerradura. Activarlo para todos los tipos de red es lo mínimo indispensable para proteger un sistema operativo."*

### 🧪 Escenario práctico: Bloquear conexiones entrantes (continuación)

#### 📋 Situación

Después de activar el Firewall de Windows Defender para redes privadas, el siguiente paso es aumentar la seguridad **bloqueando todas las conexiones entrantes**, incluso las de aplicaciones permitidas.

---

#### ⚙️ Paso a paso

| Paso | Acción | Explicación |
|------|--------|-------------|
| **1** | Dentro de **"Private network settings"**, ubicar la casilla **"Block all incoming connections, including those in the list of allowed apps"**. | Esta opción refuerza la seguridad al máximo nivel. |
| **2** | Marcar la casilla. | Ahora el firewall rechazará **todas** las conexiones entrantes, sin excepciones. |

---

#### 🔐 ¿Cuál es el propósito de esta configuración?

✅ **Respuesta correcta:** El bloqueo de todas las conexiones entrantes en una red privada **evita el acceso no autorizado de fuentes externas** y garantiza que **solo los dispositivos autorizados** puedan comunicarse, mejorando la seguridad de la red.

---

#### 🧠 ¿Por qué hacer esto en una red privada?

| Motivo | Explicación |
|--------|-------------|
| **Prevenir accesos externos no autorizados** | Aunque sea una red de confianza, pueden existir intentos de intrusión desde afuera. |
| **Aislar dispositivos** | Solo los equipos autorizados dentro de la red pueden comunicarse entre sí. |
| **Máxima seguridad** | Al bloquear incluso las apps permitidas, se evita que una aplicación vulnerable sea explotada como puerta de entrada. |
| **Protección adicional para trabajo remoto** | Luke trabaja desde casa. Bloquear conexiones entrantes reduce el riesgo de ataques dirigidos a su dispositivo. |

---

#### ⚠️ Consideración importante

| Ventaja | Desventaja |
|---------|------------|
| Máxima protección contra intrusiones. | Algunas funciones legítimas (como compartir archivos o impresoras en red) pueden dejar de funcionar temporalmente. Si se necesita usarlas, se puede desmarcar esta casilla más adelante. |

---

#### 📋 Configuración final para red privada
[x] Turn on Windows Defender Firewall
[x] Block all incoming connections, including those in the list of allowed apps
[ ] Notify me when Windows Defender Firewall blocks a new app
[ ] Turn off Windows Defender Firewall (not recommended)


> *"Bloquear todas las conexiones entrantes es como cerrar con llave todas las puertas y ventanas. Nadie entra sin tu permiso, incluso si antes lo habías autorizado."*

### 🧪 Escenario práctico: Configurar red pública (continuación)

#### 📋 Situación

Después de configurar la red privada con bloqueo total de conexiones entrantes, llega el momento de configurar la **red pública**. La estrategia aquí es **diferente**: no se deben bloquear todas las conexiones entrantes.

---

#### ⚙️ Configuración para red pública

| Opción | Estado | Motivo |
|--------|--------|--------|
| **Turn on Windows Defender Firewall** | ✅ Activado | Protege el dispositivo en redes no confiables (cafeterías, aeropuertos, hotspots). |
| **Block all incoming connections** | ❌ No marcar | Se necesitan conexiones entrantes para servicios esenciales. |
| **Notify me when Windows Defender Firewall blocks a new app** | Opcional | Puede activarse para mayor control. |

---

#### 🔐 ¿Por qué permitir algunas conexiones entrantes en redes públicas?

✅ **Respuesta correcta:** Permitir algunas conexiones entrantes en redes públicas habilita **servicios como la navegación web, el correo electrónico y el acceso remoto**, mientras el firewall sigue filtrando y controlando el tráfico. Esto garantiza que los servicios esenciales funcionen correctamente sin sacrificar la seguridad.

---

#### 🆚 Diferencia clave entre red privada y pública

| Configuración | Red privada | Red pública |
|---------------|-------------|-------------|
| **Firewall** | Activado | Activado |
| **Bloquear todas las conexiones entrantes** | ✅ Sí (máxima seguridad) | ❌ No (se necesitan servicios esenciales) |
| **Motivo** | Solo los dispositivos autorizados deben comunicarse. | Se necesita navegar, recibir correos y permitir acceso remoto. |
| **Nivel de confianza** | Alto (red conocida) | Bajo (red desconocida) |

---

#### 🧠 Lógica de la configuración

Parece contradictorio: ¿no debería ser más segura la red pública?

| Tipo de red | Lógica de seguridad |
|-------------|---------------------|
| **Red privada** | Como es de confianza, **bloqueamos todo** para que nada externo interfiera. Si necesitamos compartir archivos, lo configuramos puntualmente. |
| **Red pública** | Como es desconocida, **permitimos solo lo esencial** (web, email, remoto) y el firewall filtra el resto. Bloquear todo impediría trabajar. |

> *"En red privada cerrás todas las puertas porque estás adentro. En red pública dejás abierta solo la recepción, pero con un guardia de seguridad (el firewall) que revisa quién entra."*

---

#### 📋 Configuración final para red pública
[x] Turn on Windows Defender Firewall
[ ] Block all incoming connections, including those in the list of allowed apps
[ ] Notify me when Windows Defender Firewall blocks a new app
[ ] Turn off Windows Defender Firewall (not recommended)


---

#### ✅ Resumen final de configuración

| Tipo de red | Firewall | Bloquear todas las conexiones entrantes |
|-------------|----------|----------------------------------------|
| **Privada** | Activado | ✅ Sí |
| **Pública** | Activado | ❌ No |

> *"La seguridad no es aplicar la misma regla para todo. Es entender el contexto y configurar según el riesgo."*

En tu casa:       Una sola red → La configurás como PRIVADA.
En una empresa:   El mismo equipo puede conectarse a:
                  - Red de la oficina → PRIVADA
                  - WiFi de cafetería → PÚBLICA


### 🧪 Escenario práctico: Verificar estado del Firewall y acceder al router (continuación)

#### 📋 Situación

Después de configurar el Firewall de Windows Defender, se verifica que esté **activado** para ambas redes. Luego, el escenario cambia: ahora hay que proteger la **red doméstica** de Luke, empezando por actualizar el firmware de su router.

---

#### ✅ Verificación final del Firewall

| Tipo de red | Estado del Firewall | Bloquear conexiones entrantes | Notificaciones |
|-------------|---------------------|-------------------------------|----------------|
| **Red privada** | ✅ Activado | ✅ Bloquear todas, incluso apps permitidas | Sin notificaciones |
| **Red pública o de invitados** | ✅ Activado | ❌ No bloquear todas (solo apps no permitidas) | ✅ Notificar cuando bloquee algo |

**Resultado:** El Firewall de Windows Defender está correctamente configurado y brindando protección óptima.

---

#### 🔐 Nuevo objetivo: Proteger la red doméstica

| Prioridad | Acción |
|-----------|--------|
| **1** | Actualizar el firmware del router (Netgear Nighthawk RAX50). |
| **2** | Asegurar que el firewall del router esté actualizado. |
| **3** | Corregir otras vulnerabilidades y mejorar el rendimiento. |

---

#### ⚙️ Cómo acceder a la interfaz del router

| Paso | Acción | Explicación |
|------|--------|-------------|
| **1** | Abrir el navegador web. | Chrome, Edge, Firefox, cualquiera funciona. |
| **2** | Escribir en la barra de direcciones: **`192.168.1.1`** | Es la dirección IP del router. |
| **3** | Presionar **Enter**. | Se abre la página de inicio de sesión del router. |

---

#### 🔍 ¿Cómo se determina la dirección IP del router?

✅ **Respuesta correcta:** Se determina empleando la **dirección IP del router** que se encuentra en:
- La **documentación** del router (manual, caja).
- Una **etiqueta** pegada en la parte inferior o trasera del dispositivo.
- La **configuración de red** de la computadora.

---

#### 📋 Direcciones IP más comunes de routers

| Fabricante | Dirección IP típica |
|------------|---------------------|
| Netgear | 192.168.1.1 |
| TP-Link | 192.168.1.1 o 192.168.0.1 |
| Linksys | 192.168.1.1 |
| D-Link | 192.168.0.1 |
| ASUS | 192.168.1.1 |
| ISP genérico (proveedor) | 192.168.1.254 o 192.168.0.1 |

**¿Y si no funciona?**
En Windows, abrí una terminal (cmd) y escribí `ipconfig`. La dirección IP del router aparece como **"Puerta de enlace predeterminada"** .

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Aplicación en este escenario |
|---------------|------------------------------|
| **Firmware** | El router tiene firmware que debe actualizarse para cerrar vulnerabilidades. |
| **Plan de firmware de seguridad** | Estamos aplicando el Paso 1 (identificar dispositivo con firmware) y Paso 3 (revisar actualización). |
| **Hardening del sistema** | Actualizar el firmware del router es una práctica de hardening a nivel de red. |
| **Firewall** | El router también tiene su propio firewall que se actualiza junto con el firmware. |

> *"Después de proteger el sistema operativo, el siguiente paso es proteger la red. Todo empieza por el router: si su firmware está desactualizado, toda la red queda vulnerable."*


### 🧪 Escenario práctico: Iniciar sesión en el router y verificar firmware (continuación)

#### 📋 Situación

Después de acceder a la interfaz del router mediante la dirección IP `192.168.1.1`, hay que iniciar sesión y verificar si el firmware está actualizado.

---

#### ⚙️ Paso a paso completo

| Paso | Acción | Explicación |
|------|--------|-------------|
| **1** | Abrir el navegador y escribir `192.168.1.1`. | Es la dirección IP del router Netgear Nighthawk RAX50. |
| **2** | Aceptar la advertencia de seguridad. | El navegador avisa: *"Your connection to this site is not private"*. Esto es normal porque el router no tiene un certificado HTTPS válido. Se continúa de todos modos. |
| **3** | Ingresar el **nombre de usuario**: `admin`. | Es el usuario por defecto de la mayoría de los routers. |
| **4** | Ingresar la **contraseña**: `3wC7U;2Rr23+`. | Contraseña compleja (buena práctica de seguridad). |
| **5** | Hacer clic en **Sign in**. | Se accede al panel de administración del router. |
| **6** | Ir a la pestaña **ADVANCED** (Avanzado). | Muestra información detallada del router, incluida la versión de firmware. |
| **7** | Observar la versión de firmware actual. | En este caso: **V1.0.12.120_1.0.17**. |
| **8** | Seleccionar **Administration** (Administración) en el menú lateral. | Permite acceder a las opciones de administración, incluyendo actualización de firmware. |
| **9** | Buscar la opción de actualización de firmware. | Normalmente está en "Administration > Firmware Update" o "Router Update". |
| **10** | Ejecutar el **Asistente de actualización de firmware**. | El router se conecta al servidor de Netgear para buscar nuevas versiones. |
| **11** | Esperar a que busque actualizaciones. | El asistente muestra: *"Attempting to connect to Netgear Server. Please Wait..."*. |

---

#### 🔐 Datos de acceso utilizados

| Campo | Valor |
|-------|-------|
| **Dirección IP del router** | `192.168.1.1` |
| **Usuario** | `admin` |
| **Contraseña** | `3wC7U;2Rr23+` |
| **Versión de firmware actual** | `V1.0.12.120_1.0.17` |

---

#### ⚠️ ¿Por qué aparece "Your connection to this site is not private"?

| Motivo | Explicación |
|--------|-------------|
| El router usa **HTTP** en lugar de **HTTPS**. | Los routers domésticos no suelen tener certificados SSL válidos. |
| **No es peligroso** en este caso. | Estás accediendo a un dispositivo en tu propia red local, no a un sitio externo. |
| Se puede continuar sin problema. | La conexión es segura porque estás dentro de tu red. |

---

#### 🔍 Información mostrada en el panel ADVANCED

| Información | Valor |
|-------------|-------|
| **Modelo del router** | Nighthawk RAX50 |
| **Versión de firmware** | V1.0.12.120_1.0.17 |
| **Dirección MAC del puerto Internet** | 10:0C:6B:19:25:F9 |
| **Dirección IP pública** | 69.130.255.94 |
| **Tipo de conexión** | DHCP |

---

#### 📋 Opciones del panel ADVANCED

| Menú | ¿Qué permite hacer? |
|------|---------------------|
| **Setup Wizard** | Asistente de configuración inicial. |
| **WPS Wizard** | Configuración de Wi-Fi Protected Setup. |
| **Setup** | Configuración de Internet, red local y WiFi. |
| **USB Functions** | Gestionar dispositivos USB conectados al router. |
| **Security** | Configurar firewall, bloqueo de sitios y servicios. |
| **Administration** | Actualizar firmware, cambiar contraseña, hacer backup. |
| **Advanced Setup** | Configuraciones avanzadas de red (DNS, rutas, NAT). |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Aplicación en este paso |
|---------------|-------------------------|
| **Firmware** | Estamos verificando la versión actual del firmware del router. |
| **Plan de firmware (Paso 3)** | Identificar la versión instalada y buscar actualizaciones. |
| **Contraseñas seguras** | La contraseña del router es compleja (`3wC7U;2Rr23+`), buena práctica. |
| **HTTP vs HTTPS** | El router usa HTTP, por eso el navegador advierte que "no es privado". |
| **Gestión de parches** | Buscar actualizaciones de firmware es parte de la gestión de parches. |

> *"El panel de administración del router es el centro de control de la red. Mantener su firmware actualizado es tan importante como actualizar el sistema operativo."*


### 🧪 Escenario práctico: Actualización de firmware completada (continuación)

#### 📋 Situación

Después de que el **Asistente de actualización de firmware** buscó y encontró una nueva versión, el router descargó e instaló el firmware actualizado. Ahora se verifica que la instalación fue exitosa.

---

#### ⚙️ Pasos finales

| Paso | Acción | Explicación |
|------|--------|-------------|
| **1** | El asistente encontró una nueva versión de firmware disponible. | El router se conectó al servidor de Netgear y detectó una actualización. |
| **2** | Se descargó e instaló el nuevo firmware. | El proceso es automático una vez que se confirma la actualización. |
| **3** | El router se reinició. | Después de instalar firmware nuevo, el router se reinicia para aplicar los cambios. |
| **4** | Se verifica la nueva versión en **Router Information**. | Ahora muestra la versión actualizada. |

---

#### 📊 Comparación: Antes y después

| Momento | Versión de firmware |
|---------|---------------------|
| **Antes de actualizar** | V1.0.12.120_1.0.17 |
| **Después de actualizar** | V1.0.12.120_2.0.83 ✅ |

---

#### 📋 Información del router después de la actualización

| Información | Valor |
|-------------|-------|
| **Modelo** | Nighthawk RAX50 |
| **Versión de hardware** | RAX50 |
| **Versión de firmware** | V1.0.12.120_2.0.83 ✅ |
| **Versión de idioma de interfaz** | V1.0.12.120_2.1.46.1 |
| **Dirección MAC (Internet)** | 10:0C:6B:19:25:F9 |
| **Dirección IP pública** | 69.130.255.94 |
| **Tipo de conexión** | DHCP |

---

#### 🧠 Menú Administration del router

| Opción | ¿Qué hace? |
|--------|------------|
| **Router Status** | Muestra información general del router (firmware, IP, MAC, estado de conexión). |
| **Logs** | Registros de actividad del router (conexiones, errores, intentos de acceso). |
| **Attached Devices** | Lista de dispositivos conectados a la red. |
| **Backup Settings** | Permite guardar o restaurar la configuración del router. |
| **Set Password** | Cambiar la contraseña de administración del router. |
| **NTP Settings** | Configurar el servidor de hora (Network Time Protocol). |
| **Router Update** | Buscar e instalar actualizaciones de firmware. |

---

#### ✅ Escenario completado: Resumen de todo lo hecho

| Etapa | Acción realizada | Resultado |
|-------|------------------|-----------|
| **1. Firewall de Windows** | Verificar y activar el Firewall de Windows Defender. | Firewall activado para redes privadas y públicas. |
| **2. Red privada** | Bloquear todas las conexiones entrantes. | Máxima seguridad para la red de confianza. |
| **3. Red pública** | Activar firewall sin bloquear todas las conexiones. | Servicios esenciales funcionan con protección. |
| **4. Acceso al router** | Ingresar a `192.168.1.1` con usuario y contraseña. | Acceso exitoso al panel de administración. |
| **5. Verificar firmware** | Revisar la versión de firmware instalada. | Se detectó que estaba desactualizada. |
| **6. Actualizar firmware** | Buscar, descargar e instalar la nueva versión. | Firmware actualizado a V1.0.12.120_2.0.83. |

---

#### 🔗 Conexión con todo el módulo

| Tema del módulo | Aplicación en este escenario |
|-----------------|------------------------------|
| **Seguridad del sistema** | Proteger la laptop con firewall. |
| **Firmware** | Actualizar el firmware del router. |
| **Hardening del SO** | Activar firewall, bloquear conexiones innecesarias. |
| **Gestión de parches** | Buscar e instalar actualizaciones de firmware. |
| **Plan de firmware de seguridad** | Aplicar los 4 pasos del plan en un caso real. |
| **Protección del SO host** | Firewall como primera línea de defensa. |
| **Superficie de ataque** | Reducir puntos de entrada cerrando conexiones y actualizando firmware. |

---

#### 🎯 Lección final del escenario

> *"Proteger un sistema operativo y una red doméstica implica múltiples capas: firewall activo, configuraciones adecuadas para cada tipo de red, firmware actualizado y contraseñas seguras. Cada capa refuerza a las demás. Si una falla, las otras siguen protegiendo."*


### 🚫 Deshabilitar puertos y servicios innecesarios

Cuando las organizaciones dejan funcionando **servicios que no usan**, le están dando a los atacantes un **perfil de ataque mejorado**. Los atacantes monitorean constantemente en busca de puertos abiertos con servicios en ejecución para encontrar por dónde entrar.

---

#### ⚠️ ¿Por qué es peligroso dejar servicios innecesarios activos?

| Riesgo | Explicación |
|--------|-------------|
| **Más puntos de entrada** | Cada servicio activo y cada puerto abierto es una puerta potencial para un atacante. |
| **Detección por parte de atacantes** | Los hackers escanean redes constantemente buscando puertos abiertos con servicios vulnerables. |
| **Vulnerabilidades sin parchear** | Si un servicio no se usa, es probable que tampoco se actualice, acumulando fallos de seguridad. |
| **Mayor superficie de ataque** | Cuantos más servicios corren, más oportunidades tiene un atacante de encontrar una debilidad. |

---

#### 📋 Ejemplos de servicios que suelen dejarse activos sin necesidad

| Servicio | ¿Para qué sirve? | ¿Se usa realmente? |
|----------|------------------|---------------------|
| **Servidor de Exchange** | Servidor de correo corporativo. | Si la empresa ya migró a la nube (Microsoft 365), no debería estar activo. |
| **Servidores backend** | Aplicaciones internas, bases de datos, APIs. | Si el proyecto se descontinuó, el servidor puede seguir corriendo sin que nadie lo recuerde. |
| **FTP** | Transferencia de archivos. | Si ya no se usa, debe desactivarse. |
| **Telnet** | Acceso remoto por terminal (sin cifrado). | Obsoleto e inseguro. Se debe usar SSH en su lugar. |
| **Bluetooth** | Conexión inalámbrica de corto alcance. | Si no se usa, debe desactivarse. |
| **Servicio de impresión** | Compartir impresoras en red. | Si no hay impresoras compartidas, debe apagarse. |

---

#### 🛠️ Buenas prácticas

| Práctica | Descripción |
|----------|-------------|
| **Auditar servicios activos** | Revisar periódicamente qué servicios están corriendo en cada sistema. |
| **Apagar lo que no se usa** | Desactivar o desinstalar servicios innecesarios. |
| **Cerrar puertos** | Usar el firewall para bloquear puertos que no necesitan estar abiertos. |
| **Principio de mínimo privilegio** | Solo mantener activo lo estrictamente necesario para el funcionamiento del sistema. |
| **Documentar** | Llevar un registro de qué servicios están activos y por qué. |

---

#### 🔍 ¿Cómo identificar servicios innecesarios?

**En Windows:**
- Abrir `services.msc` (presionar Windows + R y escribir `services.msc`).
- Revisar la lista de servicios y su estado.
- Poner en "Manual" o "Deshabilitado" los que no se necesiten.

**En Linux:**
- Usar el comando `systemctl list-units --type=service` para ver servicios activos.
- Usar `netstat -tuln` o `ss -tuln` para ver puertos abiertos.
- Desactivar con `systemctl disable [servicio]` y `systemctl stop [servicio]`.

---

#### 🧠 Analogía

> *Un sistema con servicios innecesarios activos es como una casa con muchas puertas y ventanas abiertas. Aunque las principales estén cerradas con llave, un atacante solo necesita encontrar una ventana olvidada para entrar.*

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Superficie de ataque** | Deshabilitar servicios reduce directamente la superficie de ataque. |
| **Hardening del sistema** | Es una de las prácticas estándar de hardening. |
| **Firewall** | El firewall bloquea puertos, complementando esta práctica. |
| **Protección del SO** | Es la segunda medida esencial después de la gestión de parches. |

> *"Cada servicio innecesario que se desactiva es una puerta menos para los atacantes. La seguridad también se construye quitando, no solo agregando."*

### 📧 Exchange Server y la deshabilitación de servicios innecesarios

**Exchange Server** es el servidor de correo corporativo de Microsoft. Tiene un despliegue basado en **roles** para separar los tipos de tráfico de red y permitir un control más preciso de la seguridad.

---

#### 🎯 ¿Por qué separar en roles?

Separar las funciones en distintos servidores permite:

| Beneficio | Explicación |
|-----------|-------------|
| **Control de rutas de protocolo** | Cada servidor maneja solo el tráfico que le corresponde. |
| **Separación lógica** | Aísla las funciones críticas (buzones) de las que dan la cara al usuario (web). |
| **Reducción de superficie de ataque** | Se deshabilitan todos los servicios innecesarios en cada servidor. |

---

#### 📋 Roles principales de Exchange Server

| Rol | ¿Qué hace? | ¿Qué protocolos usa? |
|-----|------------|----------------------|
| **Servidor de acceso de cliente (Client Access)** | Es la cara visible. Recibe las conexiones de los usuarios (OWA, Outlook, móviles). | **Solo HTTP/HTTPS**. Se comporta como un servidor web. |
| **Servidor de buzones (Backend)** | Almacena los buzones de correo y procesa los mensajes. | Solo los servicios necesarios para alojar buzones. Algunos servicios web mínimos para que Exchange funcione. |

---

#### 🧠 Ejemplo: Outlook Web App (OWA)

Cuando un usuario accede a su correo desde el navegador:
Usuario → Navegador (HTTPS) → Servidor de acceso de cliente (OWA) → Servidor de buzones

- El servidor de acceso de cliente **expone solo protocolos web (HTTP/HTTPS)** .
- El administrador puede **optimizar la ruta del protocolo** y **deshabilitar todos los servicios innecesarios**.
- El servidor de buzones solo ejecuta lo mínimo para alojar los correos.

---

#### 🔐 Seguridad según el Departamento de Defensa de EE. UU. (DoD)

Para reducir ataques al correo electrónico, los protocolos deben cumplir con las opciones de implementación de escritorio estándar del DoD:

| Requisito | ¿En qué consiste? |
|-----------|-------------------|
| **Microsoft Outlook con MAPI** | Usar el cliente Outlook con la interfaz de programación de aplicaciones de mensajería (MAPI) para comunicarse con Exchange de forma segura. |
| **Clientes habilitados para S/MIME** | Secure/Multipurpose Internet Mail Extensions: permite cifrar y firmar digitalmente los correos electrónicos. |
| **Conexiones seguras** | Todo el tráfico debe ir cifrado (HTTPS, TLS). |

---

#### 🛠️ Buenas prácticas aplicadas

| Práctica | Cómo se aplica en Exchange |
|----------|----------------------------|
| **Separación de roles** | Servidor de acceso separado del servidor de buzones. |
| **Deshabilitar servicios innecesarios** | Cada servidor ejecuta solo lo que su rol necesita. |
| **Reducción de superficie de ataque** | El servidor de acceso solo expone HTTP/HTTPS. |
| **Cifrado** | S/MIME para correos, TLS para conexiones. |

---

#### 🧠 Analogía

> *Exchange con roles separados es como un edificio de oficinas con recepción:*
> - **Servidor de acceso de cliente** = la recepción. Solo habla con los visitantes y recibe paquetes.
> - **Servidor de buzones** = la bóveda interna. Solo se comunica con la recepción, no con el exterior.
> - *Si un atacante quiere entrar, primero tiene que pasar por recepción, que está diseñada para filtrar accesos.*

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación con este contenido |
|---------------|-----------------------------|
| **Deshabilitar puertos y servicios innecesarios** | Cada rol de Exchange desactiva los servicios que no necesita. |
| **Superficie de ataque** | Separar roles reduce la superficie de ataque de cada servidor. |
| **Cifrado** | S/MIME y TLS protegen los correos en reposo y en tránsito. |
| **Hardening del sistema** | La separación de roles es una práctica avanzada de hardening. |

> *"La arquitectura basada en roles de Exchange es un ejemplo concreto de cómo reducir la superficie de ataque en entornos corporativos. Cada servidor hace solo lo que debe, y nada más."*

### 📋 Habilitar el registro de eventos (logging)

El **registro de eventos** es un recurso fundamental que proporciona información sobre el tráfico de red, la seguridad, el uso y otras condiciones del sistema. Los administradores y profesionales de seguridad recuperan estos datos para gestionar la disponibilidad, seguridad, rendimiento y transparencia.

---

#### 📊 Información crucial que contienen los registros

| Dato registrado | ¿Para qué sirve? | Ejemplo |
|-----------------|------------------|---------|
| **Fecha y hora** | Saber exactamente cuándo ocurrió un suceso. | `2026-05-08 14:32:15` |
| **Descripción del suceso** | Entender qué pasó. | "Intento de inicio de sesión fallido". |
| **Gravedad** | Priorizar la respuesta según el nivel de riesgo. | Crítico, Error, Advertencia, Informativo. |
| **Aplicación o proceso implicado** | Identificar qué componente falló o fue atacado. | `svchost.exe`, `sshd`, `mysql`. |
| **Código específico** | Identificar el tipo exacto de evento. | Evento ID 4625 (fallo de inicio de sesión en Windows). |
| **Información relevante adicional** | Rastrear el origen del problema. | Direcciones IP, nombres de usuario, puertos. |

---

#### 🔍 Análisis en profundidad

El análisis de registros es fundamental para el **análisis de causa raíz** de incidentes:

| Tipo de incidente | ¿Qué se busca en los logs? |
|-------------------|----------------------------|
| **Fallo de hardware** | Errores de disco, sobrecalentamiento, fallos de memoria. |
| **Error del sistema operativo** | Pantallas azules, kernel panic, servicios detenidos. |
| **Infracción de seguridad** | Intentos de acceso fallidos, escalada de privilegios, conexiones sospechosas. |
| **Fallo de aplicación** | Crashes, excepciones no manejadas, timeouts. |
| **Degradación de rendimiento** | Picos de CPU, memoria agotada, latencia de disco. |

> **Técnica clave:** examinar los eventos que ocurrieron **antes del incidente** para encontrar la causa.

---

#### 🛠️ Solución de problemas con múltiples registros

A veces un solo registro no alcanza. Se necesita **correlacionar varios registros** para construir una imagen completa del sistema.

| Fuente de registro | ¿Qué información aporta? |
|--------------------|--------------------------|
| **Logs del sistema operativo** | Eventos de inicio, errores del kernel, servicios. |
| **Logs de aplicación** | Errores de software, accesos a bases de datos. |
| **Logs de seguridad** | Intentos de login, cambios de permisos, auditorías. |
| **Logs de red** | Conexiones entrantes/salientes, tráfico sospechoso. |
| **Logs del firewall** | Bloqueos, intentos de intrusión, reglas activadas. |

**Técnicas modernas de gestión de logs:**
- **Agregación:** reunir logs de múltiples fuentes en un solo lugar.
- **Correlación:** encontrar relaciones entre eventos de distintos sistemas.
- **Detección de tendencias y anomalías:** identificar patrones que indiquen un problema o ataque.

---

#### 🔭 Observabilidad del sistema

La **observabilidad** es la capacidad de medir el estado actual de un sistema analizando los datos que genera, incluidos los registros de eventos.

| Componente de observabilidad | ¿Qué responde? |
|------------------------------|----------------|
| **Logs** | ¿Qué pasó y cuándo? |
| **Métricas** | ¿Cuánto tardó? ¿Cuánta memoria usó? |
| **Trazas (traces)** | ¿Qué camino siguió una solicitud a través del sistema? |

> *En sistemas distribuidos complejos, el análisis de un solo registro no siempre es suficiente. La correlación de múltiples fuentes permite detectar problemas que de otra forma pasarían desapercibidos.*

---

#### 🧠 ¿Por qué es importante en ciberseguridad?

| Motivo | Explicación |
|--------|-------------|
| **Detección de intrusiones** | Logs de seguridad muestran intentos de acceso sospechosos. |
| **Respuesta a incidentes** | Permiten reconstruir qué hizo un atacante después de entrar. |
| **Cumplimiento normativo** | Muchas regulaciones exigen mantener registros por un período mínimo. |
| **Análisis forense** | Los logs son evidencia digital en investigaciones. |
| **Mejora continua** | Identificar vulnerabilidades y errores recurrentes para corregirlos. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación con el registro de eventos |
|---------------|-------------------------------------|
| **Protección del SO** | Es la tercera medida esencial para proteger un SO. |
| **Monitoreo de logs** | Mencionado en las mejores prácticas de protección del SO host. |
| **Hardening del sistema** | Activar logging es parte del hardening. |
| **Firewall** | Los logs del firewall son una fuente clave de información de seguridad. |
| **Detección de intrusiones** | Los logs alimentan sistemas IDS/IPS y SIEM. |

> *"Los registros de eventos son como las cámaras de seguridad de un sistema. Sin ellos, un incidente puede pasar desapercibido y, si ocurre, no hay forma de saber qué pasó."*

### 🔐 Uso de autenticación segura

Hacer copias de seguridad de los datos es vital, pero también puede ser un **riesgo de seguridad** si no se usa una autenticación segura. La falta de controles en los respaldos ha causado muchas violaciones de seguridad que comprometieron millones de registros confidenciales.

---

#### ⚠️ El peligro de los backups sin autenticación segura

| Riesgo | Consecuencia |
|--------|--------------|
| **Backups sin protección** | Un atacante que accede al backup accede a todos los datos, igual que si hubiera entrado al sistema principal. |
| **Falta de controles de acceso** | Cualquiera con acceso a la red puede leer, modificar o eliminar las copias de seguridad. |
| **Replicación sin seguridad** | Replicar datos confidenciales no es suficiente. Hay que proteger también los backups. |

**Casos reales:** muchas filtraciones comprometieron información personal, propiedad intelectual y datos confidenciales por errores relacionados con las copias de seguridad.

---

#### ✅ Métodos de autenticación segura para backups

| Método | ¿En qué consiste? | ¿Cómo protege los backups? |
|--------|-------------------|----------------------------|
| **Autenticación multifactor (MFA)** | Requiere dos o más factores para verificar la identidad (algo que sabés, algo que tenés, algo que sos). | Aunque alguien robe la contraseña del sistema de backups, no podrá acceder sin el segundo factor. |
| **Control de acceso basado en roles (RBAC)** | Asigna permisos según el rol del usuario (administrador, operador, auditor). Solo accede a los backups quien realmente lo necesita. | Un empleado de marketing no puede acceder a los backups de la base de datos financiera. |
| **Cifrado** | Codifica los datos para que solo puedan leerse con una clave. Se aplica tanto en tránsito como en reposo. | Si alguien roba un disco de backup, los datos son ilegibles sin la clave de cifrado. |
| **Registros de acceso** | Guarda un historial de quién accedió a los backups, cuándo y qué hizo. | Permite detectar accesos no autorizados y auditar el uso del sistema de respaldo. |

---

#### 🧠 ¿Por qué es importante?

| Motivo | Explicación |
|--------|-------------|
| **Los backups son un blanco atractivo** | Contienen todos los datos de la organización en un solo lugar. |
| **Los atacantes también apuntan a los backups** | Si un ransomware cifra los datos y también los backups, la organización no puede recuperarse. |
| **Cumplimiento normativo** | Muchas regulaciones exigen proteger los backups con los mismos estándares que los datos originales. |
| **Protección post-incidente** | Después de un ataque, los backups seguros permiten restaurar los sistemas sin pagar rescates ni perder datos. |

---

#### 🛠️ Buenas prácticas

| Práctica | Descripción |
|----------|-------------|
| **Aplicar MFA** | Todo acceso al sistema de backups debe requerir múltiples factores de autenticación. |
| **Implementar RBAC** | Solo el personal autorizado puede acceder, modificar o eliminar copias de seguridad. |
| **Cifrar todo** | Backups cifrados en tránsito (durante la transferencia) y en reposo (cuando se almacenan). |
| **Registrar accesos** | Auditar periódicamente quién accede a los backups y detectar comportamientos anómalos. |
| **Backup del backup (inmutabilidad)** | Mantener copias que no puedan ser modificadas ni eliminadas (backups inmutables). |
| **Probar la restauración** | Verificar que los backups se puedan restaurar correctamente y que la autenticación funcione. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación con este contenido |
|---------------|-----------------------------|
| **Autenticación segura** | Cuarta medida esencial para proteger un SO. |
| **Cifrado** | Protege los datos en reposo y en tránsito. |
| **Registro de eventos** | Los logs de acceso son parte del monitoreo de seguridad. |
| **Hardening del sistema** | Aplicar MFA y RBAC son prácticas de hardening. |
| **Copia de seguridad** | Quinta medida esencial, que debe combinarse con autenticación segura. |

> *"Un backup sin autenticación segura es como guardar todas tus joyas en una caja fuerte y dejar la llave puesta. No basta con tener copia: hay que proteger quién y cómo puede acceder a ella."*

### 💾 Copia de seguridad de datos

Las copias de seguridad son esenciales para evitar la **pérdida de datos** por fallas de hardware, errores de software, corrupción de datos o eliminación accidental. Si ocurre un incidente, la copia de seguridad permite **recuperar los datos y volver a la normalidad**.

---

#### 📦 ¿Dónde almacenar las copias de seguridad?

Es fundamental guardar las copias en un **dispositivo diferente** al de los datos originales:

| Medio de almacenamiento | Ventaja |
|-------------------------|---------|
| **Disco duro externo** | Rápido, portable, accesible sin internet. |
| **Unidad flash USB** | Muy portable, ideal para pequeñas cantidades de datos. |
| **Sistema de almacenamiento en disco (NAS)** | Accesible desde toda la red, gran capacidad. |
| **Nube** | Accesible desde cualquier lugar, resistente a desastres físicos. |
| **Unidad de cinta** | Usado en empresas para backups masivos de larga duración. |

---

#### 🏠 Ubicación del backup

| Ubicación | Protege contra... |
|-----------|-------------------|
| **Misma ubicación** (mismo edificio) | Fallos de hardware, eliminación accidental. |
| **Ubicación remota** (otra ciudad, nube) | Incendios, inundaciones, robos, desastres naturales. |

---

#### ⏱️ Frecuencia de las copias de seguridad

| Regla | Explicación |
|-------|-------------|
| **Copias regulares y consistentes** | Cuanto más tiempo pase entre backups, más datos se pueden perder. |
| **Entre más críticos los datos, más frecuente el backup** | Sistemas financieros: backups cada hora. Documentos personales: cada día o semana. |
| **Múltiples versiones** | Guardar varias copias de distintos momentos permite restaurar a un punto anterior no afectado. |

**Ejemplo:**
- Backup diario → pérdida máxima: 1 día de trabajo.
- Backup semanal → pérdida máxima: 1 semana de trabajo.
- Backup mensual → pérdida máxima: 1 mes de trabajo.

---

#### 📋 Regla 3-2-1 de backups

Es la regla de oro para una estrategia de respaldo sólida:

| Regla | ¿Qué significa? |
|-------|-----------------|
| **3** copias de los datos | La original + dos backups. |
| En **2** tipos de medios diferentes | Ejemplo: disco externo + nube. |
| **1** copia fuera del sitio | En ubicación remota por si hay desastre físico. |

---

#### 🛡️ ¿Contra qué protegen los backups?

| Amenaza | ¿El backup ayuda? |
|---------|-------------------|
| **Falla de hardware** | ✅ Sí. Restaurás en un dispositivo nuevo. |
| **Error humano (borrar sin querer)** | ✅ Sí. Recuperás la versión anterior. |
| **Corrupción de datos** | ✅ Sí. Volvés a un punto antes de la corrupción. |
| **Ransomware** | ✅ Sí, si el backup no fue afectado. Por eso debe estar en un dispositivo separado o ser inmutable. |
| **Desastre natural** | ✅ Sí, si hay copia remota. |
| **Robo del dispositivo** | ✅ Sí, si hay copia en la nube o ubicación remota. |

---

#### 🧠 Mejores prácticas

| Práctica | Descripción |
|----------|-------------|
| **Automatizar** | Configurar backups automáticos para no depender de la memoria. |
| **Verificar** | Probar periódicamente que los backups se pueden restaurar. |
| **Cifrar** | Proteger los backups con cifrado para que nadie pueda leerlos si los roba. |
| **Autenticación segura** | Usar MFA y RBAC para controlar quién accede a los backups. |
| **Backups inmutables** | Mantener copias que no se puedan modificar ni borrar (protección anti-ransomware). |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación con este contenido |
|---------------|-----------------------------|
| **Protección del SO** | Es la quinta medida esencial. |
| **Autenticación segura** | Los backups deben protegerse con MFA, RBAC y cifrado. |
| **Hardening del sistema** | Tener un plan de backup es parte del hardening. |
| **Ransomware** | Un backup seguro e inmutable es la mejor defensa contra el secuestro de datos. |

> *"Hacer backup es fácil. Lo difícil es acordarse de hacerlo, hacerlo bien y verificar que funcione. Un backup que no se puede restaurar no es un backup: es una ilusión de seguridad."*

## 📋 Plan de Seguridad del Sistema Operativo

### 1. Evaluación de configuraciones de actualizaciones

#### 📊 Configuración actual

| Dispositivo / Software | ¿Se actualiza automáticamente? | Frecuencia de actualización | ¿Es suficiente? |
|------------------------|--------------------------------|-----------------------------|-----------------|
| **Windows 11 (SO)** | ✅ Sí | Automática (mensual) | ✅ Sí |
| **Microsoft Office** | ✅ Sí | Automática | ✅ Sí |
| **Navegador (Chrome)** | ✅ Sí | Automática | ✅ Sí |
| **Antivirus (Windows Defender)** | ✅ Sí | Automática (diaria) | ✅ Sí |
| **Router WiFi (firmware)** | ❌ No | Manual (cada 3-4 meses) | ⚠️ Debería revisar más seguido |
| **Impresora (firmware)** | ❌ No | Manual (cada 6 meses) | ⚠️ Debería revisar más seguido |
| **Drivers de hardware** | ⚠️ Parcial | Algunos automáticos, otros manuales | ⚠️ Revisar cada 3 meses |

#### 🔧 Acciones de mejora

- Activar las actualizaciones automáticas del router si tiene la opción.
- Programar un recordatorio cada 3 meses para revisar firmware de router e impresora.
- Usar una herramienta como "Windows Update" para verificar drivers pendientes.

---

### 2. Evaluación de puertos y dispositivos

#### 📋 Dispositivos y puertos que tengo

| Dispositivo / Puerto | ¿Lo uso regularmente? | ¿Debería desactivarlo? | Acción |
|----------------------|------------------------|------------------------|--------|
| **Bluetooth** | Solo a veces (auriculares). | ✅ Sí, cuando no lo uso. | Desactivar desde el centro de actividades cuando no se necesite. |
| **WiFi** | Sí, siempre. | ❌ No | Mantener activo. |
| **Puertos USB frontales** | Sí, para pendrives. | ❌ No | Mantener. |
| **Cámara web** | Solo en videollamadas. | ✅ Sí, cuando no la uso. | Tapar físicamente o desactivar en administrador de dispositivos. |
| **Micrófono** | Solo en videollamadas. | ✅ Sí, cuando no lo uso. | Desactivar en configuración de privacidad. |
| **Extensor WiFi** | No tengo. | - | Si tuviera, desconectar cuando no se use. |
| **Servicios de red innecesarios** | Revisar. | ✅ Sí. | Desactivar servicios como "Compartir impresoras" o "Escritorio remoto" si no se usan. |

#### 🔧 Acciones de mejora

- Desactivar Bluetooth cuando no se use.
- Tapar la cámara web físicamente.
- Revisar en `services.msc` qué servicios están corriendo y desactivar los que no necesito.
- Cerrar puertos innecesarios desde el firewall.

---

### 3. Registro de eventos

#### 📋 Evaluación actual

| Sistema | ¿Tiene registro de eventos? | ¿Está habilitado? | ¿Qué registra? |
|---------|-----------------------------|-------------------|----------------|
| **Windows 11** | ✅ Sí (Visor de eventos) | ✅ Sí | Inicios de sesión, errores del sistema, eventos de seguridad, actividad de aplicaciones. |
| **Router** | ✅ Sí (Logs del router) | ✅ Sí | Conexiones entrantes/salientes, intentos de acceso, cambios de configuración. |
| **Firewall de Windows** | ✅ Sí | ✅ Sí | Conexiones bloqueadas, reglas activadas, intentos de intrusión. |

#### 🔧 Acciones de mejora

- Revisar el Visor de eventos de Windows una vez por semana.
- Configurar alertas para eventos críticos (ej. múltiples intentos de inicio de sesión fallidos).
- Activar el envío de logs del router a un correo o servidor si es posible.

---

### 4. Seguridad del acceso al sistema operativo

#### 📋 Evaluación actual

| Método de autenticación | ¿Lo uso? | ¿Es suficiente? | Acción de mejora |
|-------------------------|----------|-----------------|------------------|
| **Contraseña de inicio de sesión** | ✅ Sí | ⚠️ Regular | Usar contraseña más larga y compleja. |
| **Windows Hello (PIN/Huella/Rostro)** | ✅ Sí (PIN) | ✅ Sí | Agregar huella dactilar si el equipo lo permite. |
| **Autenticación multifactor (MFA)** | ✅ Sí (cuentas online) | ✅ Sí | Activar MFA en todas las cuentas que lo permitan. |
| **Contraseña de administrador** | ✅ Sí | ✅ Sí | Mantener separada de la cuenta de uso diario. |
| **Contraseñas para datos sensibles** | ⚠️ Parcial | ❌ No suficiente | Agregar cifrado con contraseña a carpetas sensibles. |
| **Bloqueo automático de pantalla** | ✅ Sí (5 min) | ✅ Sí | Reducir a 2-3 minutos. |

#### 🔧 Acciones de mejora

- Activar MFA en todas las cuentas (email, banca, redes sociales, trabajo).
- Crear una cuenta de usuario estándar para el día a día y reservar la de administrador solo para cambios del sistema.
- Usar BitLocker (Windows) o VeraCrypt para cifrar carpetas con datos sensibles.
- Cambiar contraseñas cada 90 días.

---

### 5. Frecuencia de copias de seguridad

#### 📋 Evaluación actual

| Tipo de datos | ¿Tiene backup? | Frecuencia | Medio de almacenamiento | ¿Es suficiente? |
|---------------|----------------|------------|-------------------------|-----------------|
| **Documentos personales** | ✅ Sí | Semanal | Disco duro externo | ⚠️ Debería ser más frecuente. |
| **Fotos y videos** | ✅ Sí | Mensual | Nube (Google Photos) | ⚠️ Si agrego muchas fotos, debería ser semanal. |
| **Configuraciones del sistema** | ❌ No | - | - | ❌ Debería crear un punto de restauración. |
| **Datos de aplicaciones** | ❌ No | - | - | ❌ Debería incluir backups de configuraciones de apps importantes. |
| **Copia fuera del sitio** | ⚠️ Parcial | - | Nube | ✅ Sí, pero no para todos los datos. |

#### 📊 Cantidad de datos entre backups

| Período | Datos nuevos agregados | Riesgo de pérdida |
|---------|------------------------|-------------------|
| **Entre backups semanales** | Aproximadamente 10-15 documentos, 50 fotos. | Medio: perdería una semana de trabajo. |
| **Entre backups mensuales** | Aproximadamente 40-60 documentos, 200 fotos. | Alto: perdería un mes de recuerdos y trabajo. |

#### 🔧 Acciones de mejora

- Aumentar la frecuencia de backup de documentos a **diario** (automatizado).
- Aumentar la frecuencia de backup de fotos a **semanal**.
- Crear un punto de restauración del sistema una vez por mes.
- Aplicar la regla **3-2-1**: 3 copias, 2 medios diferentes, 1 fuera de casa.
- Agregar un backup en la nube (OneDrive, Google Drive) además del disco externo.
- Probar la restauración de un archivo una vez cada 3 meses para verificar que los backups funcionan.

---

### ✅ Resumen del plan de acción

| Prioridad | Acción | Plazo |
|-----------|--------|-------|
| 🔴 Alta | Activar MFA en todas las cuentas. | Hoy |
| 🔴 Alta | Aumentar frecuencia de backups a diario. | Esta semana |
| 🟡 Media | Desactivar Bluetooth y cámara cuando no se usen. | Hoy |
| 🟡 Media | Revisar logs del sistema semanalmente. | Esta semana |
| 🟡 Media | Cifrar carpeta de datos sensibles con BitLocker/VeraCrypt. | Este mes |
| 🟢 Baja | Programar recordatorio de actualización de firmware cada 3 meses. | Este mes |
| 🟢 Baja | Crear punto de restauración del sistema. | Este mes |

---

### 💭 Reflexión personal

> Hacer este plan me permitió darme cuenta de que tenía varios puntos débiles que no había considerado. Mis backups no eran tan frecuentes como deberían y no tenía MFA activado en todas mis cuentas. Tampoco revisaba los logs del sistema ni desactivaba el Bluetooth cuando no lo usaba.
>
> Lo más valioso de este ejercicio fue entender que la seguridad del sistema operativo no es una configuración que se hace una sola vez, sino una serie de hábitos y revisiones periódicas. No necesito ser un experto para aplicar estas medidas: solo necesito ser constante.
>
> A partir de ahora, mi sistema está más protegido y tengo un plan claro para mantenerlo así en el tiempo.

## 📝 Resumen de la lección: Seguridad del sistema operativo

En esta lección aprendimos la importancia de **proteger y fortalecer el sistema operativo** para evitar que las amenazas cibernéticas accedan a datos confidenciales.

### ✅ Técnicas aprendidas para proteger sistemas

| # | Técnica | ¿En qué consiste? |
|---|---------|-------------------|
| 1 | **Mantener el sistema actualizado** | Aplicar parches y actualizaciones de seguridad al SO, aplicaciones y firmware. |
| 2 | **Usar contraseñas seguras** | Implementar contraseñas complejas, MFA y políticas de caducidad. |
| 3 | **Restringir el acceso** | Limitar usuarios con privilegios, aplicar RBAC y usar firewalls. |
| 4 | **Implementar software de seguridad** | Antivirus, antimalware, IDS/IPS. |
| 5 | **Habilitar el cifrado** | Cifrado de disco completo y de datos en tránsito y en reposo. |
| 6 | **Monitorear los registros del sistema** | Revisar logs para detectar actividad sospechosa. |
| 7 | **Realizar copias de seguridad periódicas** | Backups regulares, automatizados y con la regla 3-2-1. |

### 🧠 Lo más importante

> *"Proteger un sistema operativo no es una acción única: es una combinación de buenas prácticas que se refuerzan entre sí. La seguridad está en las capas."*

### 🔜 Próximo paso

Esta fue la lección final del módulo. A continuación, revisaremos los **puntos clave de todo el módulo 3** y exploraremos recursos adicionales relacionados con la seguridad del sistema.


## 📚 Módulo 3: Seguridad de redes - Puntos para recordar

---

### 🔑 Conceptos clave

#### Firmware
1. El **firmware** es un componente de hardware crítico integrado en los dispositivos para ayudarlos a funcionar eficazmente.
2. Se diferencia del software en que está diseñado para almacenarse **permanentemente en memoria no volátil** y controla el comportamiento del dispositivo.
3. Existen **tres tipos** de firmware: **bajo nivel** (ROM, no actualizable), **alto nivel** (flash, actualizable) y **subsistema** (independiente, para partes específicas).
4. Las vulnerabilidades del firmware pueden exponer a los sistemas a los mismos riesgos que un SO sin parches. Es esencial prevenir amenazas como el phishing.
5. Las vulnerabilidades comunes incluyen: **falta de cifrado, desbordamiento de búfer, inyección de comandos, contraseñas débiles** y errores de autenticación.

---

#### Servidores
6. Un **servidor** es un dispositivo o sistema de software especializado que almacena y procesa datos, actuando como concentrador central en una red.
7. Tipos de servidores según su propósito:
   - Servidor web
   - Servidor FTP (transferencia de archivos)
   - Servidor de aplicaciones
   - Servidor de archivos
   - Servidor de base de datos
   - Servidor de correo
   - Servidor de impresión
   - Servidor DNS (nombres de dominio)
   - Servidor de monitoreo y administración
8. Comprender los roles de los servidores ayuda a entender los requisitos de los sistemas operativos que los gestionan.

---

#### Sistemas operativos
9. Un **sistema operativo (SO)** gestiona todas las aplicaciones y programas. Cuando se carga, permite que las aplicaciones interactúen con el hardware.
10. Sin un SO instalado, una computadora **no puede ejecutar programas**. Es el componente esencial del sistema informático.
11. Para garantizar **integridad, confidencialidad y disponibilidad** del SO, hay que protegerlo de virus, malware e intrusiones de hackers remotos.

---

#### Seguridad del SO
12. El **endurecimiento del sistema (hardening)** es el proceso de asegurar un sistema mitigando posibles vulnerabilidades.
13. Métodos para proteger un sistema operativo:

| # | Método | Objetivo |
|---|--------|----------|
| 1 | **Gestión de parches** | Mantener SO, aplicaciones y firmware actualizados. |
| 2 | **Deshabilitar puertos y servicios innecesarios** | Reducir la superficie de ataque. |
| 3 | **Habilitar registro de eventos** | Monitorear tráfico, seguridad y uso. |
| 4 | **Usar autenticación segura** | MFA, contraseñas fuertes, RBAC, cifrado. |
| 5 | **Copia de seguridad de datos** | Backups regulares con regla 3-2-1. |

---

### 💡 Grandes ideas y habilidades practicadas

| Habilidad | Actividad realizada |
|-----------|---------------------|
| **Pensamiento analítico, comunicación escrita** | Explicar por qué la seguridad del sistema es tan importante como la seguridad física de una casa u oficina. |
| **Ingenio, comunicación escrita** | Crear un plan para garantizar la seguridad del firmware (4 pasos). |
| **Mentalidad de crecimiento, comunicación escrita** | Enumerar los requisitos para ser ingeniero de firmware. |
| **Comunicación escrita** | Enumerar información clave sobre la certificación Red Hat (RHCSA). |
| **Pensamiento crítico** | Determinar el servidor apropiado para cada necesidad. |
| **Clasificación** | Clasificar los tipos de sistemas operativos (servidor, estación de trabajo, móvil). |
| **Descripción** | Describir el fortalecimiento del sistema (hardening). |
| **Resolución de problemas, agilidad de aprendizaje** | Proteger un sistema operativo host configurando firewall y actualizando firmware. |
| **Pensamiento crítico, documentación** | Crear un plan para proteger un sistema operativo. |
| **Gestión de carrera** | Resumir habilidades para ingeniero de firmware y tareas de un administrador Red Hat. |

---

### 🎯 Objetivos de aprendizaje cumplidos

Al completar este módulo, ahora podés:

| # | Objetivo | ¿Dónde lo aplicaste? |
|---|----------|----------------------|
| 1 | ✅ **Actualizar firmware** | Escenario práctico: actualizar el firmware del router Netgear. Plan de firmware de 4 pasos. |
| 2 | ✅ **Proteger un sistema operativo host** | Escenario práctico: configurar Firewall de Windows Defender, bloquear conexiones entrantes. |
| 3 | ✅ **Crear un plan para asegurar un sistema operativo** | OS Security Plan: actualizaciones, puertos, logs, autenticación y backups. |

---

### 🗺️ Mapa del módulo 3
Módulo 3: Seguridad de redes
│
├── 🔐 Seguridad del sistema
│ ├── Analogía casa ↔ sistema
│ └── Medidas básicas de protección
│
├── 🔧 Firmware
│ ├── ¿Qué es y para qué sirve?
│ ├── Tipos (bajo nivel, alto nivel, subsistema)
│ ├── Plan de firmware de seguridad (4 pasos)
│ ├── Vulnerabilidades comunes (CWE)
│ └── Hackeo de firmware (bootkits, rootkits)
│
├── 🖥️ Servidores
│ ├── Características clave
│ └── Tipos de servidores (web, FTP, DNS, correo, etc.)
│
├── 💻 Sistemas operativos
│ ├── Componentes (bootloader, kernel)
│ ├── Tipos (servidor, estación de trabajo, móvil)
│ ├── Windows (Home vs Pro)
│ ├── macOS
│ └── Linux (distribuciones, entornos de escritorio)
│
├── 🛡️ Seguridad del SO
│ ├── Hardening del sistema
│ ├── Protección del SO host (7 prácticas)
│ ├── 5 medidas esenciales (parches, puertos, logs, autenticación, backups)
│ ├── Gestión de parches
│ ├── Deshabilitar puertos y servicios
│ ├── Registro de eventos
│ ├── Autenticación segura
│ └── Copia de seguridad de datos
│
├── 🧪 Escenarios prácticos
│ ├── Configurar Firewall de Windows Defender
│ ├── Actualizar firmware del router
│ └── Plan de seguridad del SO
│
└── 💼 Gestión de carrera
├── Ingeniero de firmware
└── RHCSA (Red Hat Certified System Administrator)


---

### 🏆 Logros del módulo

> Completaste el módulo 3 del curso de ciberseguridad de IBM SkillsBuild. Aprendiste sobre firmware, servidores, sistemas operativos y cómo protegerlos. Aplicaste tus conocimientos en escenarios prácticos y creaste planes de seguridad reales. ¡Excelente trabajo!

## 📖 Explora más recursos

Para profundizar en los conceptos cubiertos en este módulo, consultá estos recursos:

### 🔗 Recursos adicionales

| Tema | Recurso | Descripción |
|------|---------|-------------|
| **Sistemas operativos no compatibles** | [¿Cuáles son los problemas de seguridad del uso de un sistema operativo no compatible?](https://www.itconvergence.com/blog/security-risks-of-unsupported-operating-systems/) | Blog de IT Convergence que explica los riesgos de seguridad de usar un SO que ya no recibe soporte. |
| **Proceso de arranque de Windows** | [Proteger el proceso de arranque de Windows](https://learn.microsoft.com/es-es/windows/security/operating-system-security/system-security/secure-the-windows-10-boot-process) | Documentación oficial de Microsoft sobre cómo proteger el proceso de arranque de Windows. |
| **Windows Server Security** | [Documentación de Windows Server Security](https://learn.microsoft.com/es-es/windows-server/security/security-and-assurance) | Microsoft explica cómo Windows Server Security proporciona capas de protección integradas en el SO. |
| **Linux en ciberseguridad** | [Cinco habilidades de Linux que debe dominar para ser un profesional de la ciberseguridad](https://www.comptia.org/blog/linux-skills-for-cybersecurity-professionals) | Blog de CompTIA sobre la relevancia de Linux para los profesionales de ciberseguridad. |

---

### 📚 Fuentes y referencias del módulo

#### Lección 1: Seguridad del firmware

| Fuente | Enlace |
|--------|--------|
| **CWE Top 25 Most Dangerous Software Weaknesses (2022)** | [https://cwe.mitre.org/top25/archive/2022/2022_cwe_top25.html](https://cwe.mitre.org/top25/archive/2022/2022_cwe_top25.html) |

#### Lección 2: Servidores y sistemas operativos

| Fuente | Enlace |
|--------|--------|
| **Windows 1.0 - PCMag Encyclopedia** | [https://www.pcmag.com/encyclopedia/term/windows-10](https://www.pcmag.com/encyclopedia/term/windows-10) |

---

### 🎓 Certificaciones mencionadas en el módulo

| Certificación | Descripción |
|---------------|-------------|
| **Red Hat Certified System Administrator (RHCSA)** | Certificación de Red Hat para administradores de sistemas Linux. Ideal para validar habilidades en entornos empresariales. |
| **Certified Firmware Engineer (CFE)** | Certificación para ingenieros de firmware. |
| **Certified Firmware Security Engineer (CFSE)** | Certificación enfocada en seguridad del firmware. |

---

### 🛠️ Herramientas y tecnologías vistas

| Herramienta / Tecnología | ¿Para qué se usa? |
|--------------------------|-------------------|
| **Windows Defender Firewall** | Firewall integrado en Windows para proteger contra accesos no autorizados. |
| **BitLocker** | Cifrado de disco completo en Windows. |
| **FileVault** | Cifrado de disco completo en macOS. |
| **LUKS** | Cifrado de disco en Linux. |
| **BIOS / UEFI** | Firmware de la placa madre. UEFI es la versión moderna con más seguridad (Secure Boot). |
| **TPM (Trusted Platform Module)** | Chip de seguridad que almacena claves de cifrado y verifica la integridad del sistema. |
| **SIEM** | Sistema de gestión de eventos e información de seguridad para monitoreo centralizado. |
| **IDS / IPS** | Sistema de detección / prevención de intrusiones. |
| **Red Hat Enterprise Linux** | Distribución de Linux para servidores empresariales. |
| **Ubuntu, Fedora, Debian** | Distribuciones de Linux populares para escritorio y servidor. |
| **Kali Linux** | Distribución de Linux especializada en ciberseguridad y pruebas de penetración. |
| **MAPI** | Interfaz de programación de aplicaciones de mensajería (usada por Outlook/Exchange). |
| **S/MIME** | Estándar para cifrar y firmar digitalmente correos electrónicos. |

---

### 📝 Glosario rápido del módulo 3

| Término | Definición breve |
|---------|------------------|
| **Firmware** | Software de bajo nivel integrado en el hardware que controla su funcionamiento. |
| **Bootloader** | Programa que carga el sistema operativo al encender la computadora. |
| **Kernel** | Núcleo del SO que gestiona hardware y software. |
| **Hardening** | Proceso de asegurar un sistema reduciendo vulnerabilidades. |
| **Superficie de ataque** | Conjunto de puntos de entrada que un atacante puede explotar. |
| **Parche** | Actualización que corrige vulnerabilidades de seguridad. |
| **MFA** | Autenticación multifactor: verificación con dos o más métodos. |
| **RBAC** | Control de acceso basado en roles. |
| **Bootkit** | Malware que infecta el proceso de arranque. |
| **Rootkit** | Malware que se oculta modificando el sistema operativo. |
| **Jailbreak** | Eliminar restricciones de iOS para instalar apps no autorizadas. |
| **Rooting** | Obtener permisos de superusuario en Android. |
| **Logs** | Registros de eventos del sistema. |
| **Backup** | Copia de seguridad de datos. |
| **Regla 3-2-1** | Estrategia de backup: 3 copias, 2 medios, 1 fuera del sitio. |
| **OTA** | Actualización inalámbrica de firmware/software (Over-The-Air). |
| **DNS** | Sistema de nombres de dominio: traduce nombres a direcciones IP. |
| **FTP** | Protocolo de transferencia de archivos. |
| **HTTP/HTTPS** | Protocolo de transferencia de hipertexto (seguro con cifrado). |

## 🧪 Preguntas de repaso - Módulo 3

---

### Pregunta 1: Cifrado de datos del firmware

**WeInvest crea un plan para garantizar la seguridad del firmware de sus dispositivos IoT. Para ello, WeInvest cifra los datos de su firmware. ¿Por qué debería cifrar los datos del firmware?**

✅ **Respuesta correcta:** Para evitar modificaciones no autorizadas o manipulación del firmware.

| Opción | ¿Es correcta? | Explicación |
|--------|:---:|-------------|
| Para facilitar la integración con otros dispositivos IoT | ❌ | El cifrado protege datos, no facilita integración. |
| Para mejorar el rendimiento y la velocidad | ❌ | El cifrado no mejora rendimiento, su propósito es seguridad. |
| Para evitar modificaciones no autorizadas o manipulación | ✅ | El cifrado garantiza que solo usuarios autorizados puedan modificar el firmware. |
| Para restringir el acceso a funciones críticas | ❌ | Eso se hace con autenticación y autorización (RBAC). |

---

### Pregunta 2: Actualizaciones OTA

**WeInvest implementa actualizaciones over-the-air (OTA) para sus dispositivos móviles. ¿Cuál es el propósito de las actualizaciones OTA?**

✅ **Respuesta correcta:** Para transmitir de forma inalámbrica nuevo firmware a dispositivos móviles.

| Opción | ¿Es correcta? | Explicación |
|--------|:---:|-------------|
| Para restringir el acceso a la red | ❌ | Eso se hace con firewalls y control de acceso. |
| Cómo deshabilitar los puertos USB | ❌ | Se deshabilitan desde configuración del sistema. |
| Para cifrar datos confidenciales | ❌ | El cifrado es una función de seguridad independiente. |
| Para transmitir de forma inalámbrica nuevo firmware | ✅ | Definición exacta de OTA: software/firmware transmitido sin cables. |

---

### Pregunta 3: Cifrado de copias de seguridad

**Debes proteger un sistema operativo implementando métodos de autenticación seguros para las copias de seguridad de los datos. ¿Qué método consiste en codificar los datos de la copia de seguridad y emplear una clave de descifrado para acceder a ellos?**

✅ **Respuesta correcta:** Cifrado.

| Opción | ¿Es correcta? | Explicación |
|--------|:---:|-------------|
| Cifrado | ✅ | Codifica datos y requiere clave para descifrarlos. |
| Control de acceso basado en roles | ❌ | Controla quién accede, pero no codifica datos. |
| Registros de acceso | ❌ | Auditan quién accedió, no codifican. |
| Autenticación de dos factores | ❌ | Verifica identidad con dos métodos, no codifica datos. |

---

### 📊 Resumen de los cuatro métodos de autenticación para backups

| Método | ¿Qué hace? |
|--------|------------|
| **Cifrado** | Codifica los datos. Solo se leen con clave de descifrado. |
| **Control de acceso basado en roles (RBAC)** | Asigna permisos según el rol del usuario. |
| **Registros de acceso** | Guarda historial de quién accedió y qué hizo. |
| **Autenticación multifactor (MFA)** | Requiere dos o más factores para verificar identidad. |

---

### 🎯 Puntaje acumulado

| Pregunta | Valor | Resultado |
|----------|-------|-----------|
| Cifrado de firmware | 20 CyberCoins | ✅ Correcto |
| Actualizaciones OTA | 30 CyberCoins | ✅ Correcto |
| Cifrado de backups | 30 CyberCoins | ✅ Correcto |
| **Total** | **80 CyberCoins** | 🏆 |


## 🌐 Módulo 4: Seguridad de redes (Network Security)

La seguridad general de un sistema depende de la seguridad de la red. Una organización puede tener políticas sólidas sobre cómo el personal usa y mantiene cada dispositivo, pero si no protege **cómo esos dispositivos se conectan y comunican** entre sí y con otras redes (incluido Internet), el sistema sigue siendo vulnerable.

---

### 📋 Lo que vamos a ver en este módulo

| Tema | Descripción |
|------|-------------|
| **Tipos de ataques a redes** | Cómo funcionan y qué amenazan. |
| **Dispositivos de seguridad de red** | Herramientas que los administradores usan para proteger contra ataques. |
| **Arquitectura de red segura** | Cómo diseñar redes con seguridad incorporada desde el principio. |
| **Control de acceso a la red** | Por qué es crucial para una seguridad de red sólida. |

---

### 🧠 Idea clave del módulo

> *"No basta con proteger cada dispositivo por separado. La red que los conecta también debe ser segura. Si la red es vulnerable, todos los dispositivos conectados a ella están en riesgo."*

---

### 🔗 Conexión con el módulo anterior

| Módulo 3 (Seguridad del sistema) | Módulo 4 (Seguridad de redes) |
|----------------------------------|-------------------------------|
| Protegimos dispositivos individuales (SO, firmware). | Ahora protegemos la **conexión entre ellos**. |
| Vimos firewall como protección local. | Veremos firewalls de red y otros dispositivos. |
| Aprendimos a asegurar el SO host. | Aprendemos a asegurar la infraestructura de red. |


### 🎯 Objetivos de aprendizaje

Al completar este módulo, deberás ser capaz de:

| # | Objetivo | ¿Qué implica? |
|---|----------|---------------|
| 1 | **Clasificar los tipos de ataques de aplicaciones y servicios** | Identificar y diferenciar ataques como DoS, DDoS, inyección SQL, cross-site scripting (XSS), etc. |
| 2 | **Clasificar los tipos de ataques inalámbricos** | Reconocer ataques específicos de redes WiFi: rogue access points, evil twin, war driving, etc. |
| 3 | **Identificar los beneficios de los dispositivos de seguridad de red** | Saber para qué sirven firewalls, IDS/IPS, proxies, VPNs y otros dispositivos de protección. |
| 4 | **Diseñar una red segura** | Aplicar principios de arquitectura de red segura desde el diseño inicial. |
| 5 | **Diferenciar entre los controles de acceso a la red** | Distinguir métodos como NAC, MAC filtering, 802.1X, y entender cuándo usar cada uno. |

---

### 🗺️ Mapa visual de objetivos
Módulo 4: Seguridad de redes
│
├── Amenazas
│ ├── Ataques a aplicaciones y servicios
│ └── Ataques inalámbricos
│
├── Defensas
│ └── Dispositivos de seguridad de red
│
├── Diseño
│ └── Arquitectura de red segura
│
└── Control
└── Control de acceso a la red (NAC)

## ⚠️ Lección 1: Amenazas a la seguridad de la red

La seguridad de la red es vital para mantener la **integridad de los datos** y la **privacidad** de una organización y sus empleados. Para garantizar una protección eficaz, se necesita una **comprensión completa** de las posibles amenazas y riesgos.

---

### 📋 Lo que vamos a ver en esta lección

| Tema | Descripción |
|------|-------------|
| **Importancia de la seguridad de la red** | Por qué es fundamental proteger la red. |
| **Tipos de ataques** | Las diferentes amenazas que pueden atacar una red. |
| **Cómo se producen los ataques** | El mecanismo detrás de cada tipo de ataque. |

---

### 🧠 Idea clave

> *"Para defender una red, primero hay que conocer qué la amenaza. Entender los ataques es el primer paso para protegerse."*

## 🌐 Seguridad de red y ataques de red

La **seguridad de red** protege la infraestructura de red del acceso no autorizado que puede provocar robos o daños. Protege información sensible como datos financieros, personales y empresariales confidenciales.

> *Incluso con buena seguridad en los sistemas y dispositivos, es fundamental proteger la red que los conecta. Si la red es vulnerable, todos los dispositivos quedan expuestos.*

---

### ⚠️ Tipos de amenazas a la seguridad de red

| Tipo de ataque | ¿En qué consiste? | Ejemplo |
|----------------|-------------------|---------|
| **Ataques a aplicaciones** | Explotan una vulnerabilidad conocida en el software que se ejecuta en un servidor. | **Ataque de intermediario (Man-in-the-Middle):** un actor malicioso engaña al usuario para robar información. Ejemplo: redirigir a un usuario a un sitio web falso que se parece al original para capturar contraseñas. |
| **Ataques inalámbricos** | Aprovechan las vulnerabilidades de las redes inalámbricas para interceptar información. | **Gemelo maligno (Evil Twin):** el atacante configura un punto de acceso WiFi falso. Si los usuarios se conectan, el atacante accede a su sistema e información. |

---

### 🛡️ Capas de una buena seguridad de red

| Capa | ¿Qué incluye? | ¿Para qué sirve? |
|------|---------------|------------------|
| **Control de acceso por software** | Autenticación de usuarios y dispositivos. Control de acceso por rol (RBAC). | Verificar identidad y otorgar o denegar acceso a recursos. Limitar quién usa recursos o datos según su rol. |
| **Hardware de seguridad** | Switches, routers, firewalls. | Monitorear y controlar el tráfico de red. Asegurar que solo el tráfico autorizado pase. |
| **Sistemas de detección y prevención** | IDS/IPS, firewalls. | Monitorear tráfico en busca de actividad sospechosa y bloquear ataques. |
| **Arquitectura de red segura** | Zonas, topologías, segmentación, aislamiento. | Ubicar estratégicamente servidores y dispositivos de seguridad para maximizar disponibilidad y minimizar riesgos. |

---

### 🎯 Ejemplos de ataques mencionados

| Ataque | Tipo | Descripción breve |
|--------|------|-------------------|
| **Gemelo maligno (Evil Twin)** | Inalámbrico | Punto de acceso WiFi falso que imita a uno legítimo. |
| **Secuestro (Hijacking)** | Aplicación | Tomar control de una sesión o conexión legítima. |
| **Inyecciones** | Aplicación | Insertar código malicioso en una aplicación (SQL, comandos). |
| **Envenenamiento ARP** | Red | Manipular las tablas ARP para interceptar tráfico. |
| **Bluejacking** | Inalámbrico | Enviar mensajes no solicitados por Bluetooth. |
| **Bluesnarfing** | Inalámbrico | Acceder a información de un dispositivo por Bluetooth sin autorización. |
| **Día cero (Zero-day)** | Aplicación/SO | Explotar una vulnerabilidad antes de que el fabricante la conozca o publique un parche. |

---

### 🧠 ¿Qué abarca la seguridad de red?
Prácticas básicas: Prácticas avanzadas:
├── Contraseñas seguras ├── Firewalls
├── Cerrar sesión ├── IDS/IPS
├── No compartir credenciales├── Segmentación de red
└── Sentido común └── Arquitectura segura


La seguridad de red cubre desde lo más simple hasta lo más complejo. También incluye las **políticas** relacionadas con el manejo de información confidencial.

---

### ⚠️ ¿Por qué es importante?

| Motivo | Consecuencia de no proteger la red |
|--------|-------------------------------------|
| Cada vez hay más información sensible en línea y en dispositivos. | Un acceso no autorizado puede tener **resultados desastrosos**. |
| Los ataques evolucionan constantemente. | Sin seguridad, los datos financieros, personales y empresariales quedan expuestos. |
| La red conecta todos los dispositivos. | Una red vulnerable pone en riesgo todos los sistemas, aunque estén bien protegidos individualmente. |

> *"La seguridad de red garantiza que los servicios y recursos críticos permanezcan intactos, seguros y disponibles para los usuarios autorizados, evitando accesos no autorizados e interrupciones por ciberataques."*


### 💭 Pregunta de reflexión: Tres principales medidas de seguridad de red

Después de ver el video, estas serían las **tres principales medidas de seguridad de red** que recomendaría a una organización:

---

#### 🥇 1. Control de acceso a la red

| ¿En qué consiste? | ¿Por qué es prioridad? |
|-------------------|------------------------|
| Usar técnicas de **autenticación** para verificar la identidad de usuarios y dispositivos. Conceder o denegar acceso a los recursos según el **rol o grupo** del usuario (RBAC). | Es la primera línea de defensa. Si solo entra quien debe entrar, se reduce drásticamente la superficie de ataque. Sin control de acceso, cualquier otra medida pierde efectividad. |

---

#### 🥈 2. Sistemas de detección y prevención de intrusiones (IDS/IPS y firewalls)

| ¿En qué consiste? | ¿Por qué es prioridad? |
|-------------------|------------------------|
| Monitorear el tráfico de red en busca de **actividad sospechosa**. Configurar firewalls y sistemas IDS/IPS para **detectar y bloquear ataques** antes de que lleguen a los sistemas internos. | Aunque un atacante intente entrar, estos sistemas actúan como guardianes que vigilan las 24 horas. Sin monitoreo, un ataque puede pasar desapercibido durante meses. |

---

#### 🥉 3. Arquitectura de red segura (segmentación y zonas)

| ¿En qué consiste? | ¿Por qué es prioridad? |
|-------------------|------------------------|
| Diseñar la red usando **zonas, topologías y segmentación** para ubicar estratégicamente servidores y dispositivos. Aislar los recursos críticos del resto de la red. | Si un atacante logra entrar, la segmentación **limita el daño**. No puede moverse libremente por toda la red. Es como tener compartimentos estancos en un barco: si uno se inunda, los demás no. |

---

### 📊 Por qué estas tres y no otras

| Medida | ¿Qué pasaría sin ella? |
|--------|------------------------|
| **Control de acceso** | Cualquiera podría conectarse a la red y acceder a recursos sensibles. |
| **IDS/IPS y firewalls** | Los ataques entrarían sin ser detectados ni bloqueados. |
| **Segmentación de red** | Un atacante que ingresa a un solo dispositivo podría moverse libremente por toda la organización. |

---

### 🧠 Lógica de prioridades
1º Control de acceso → Definir QUIÉN puede entrar.
2º Monitoreo y bloqueo → Vigilar y frenar a los que intentan entrar igual.
3º Segmentación → Limitar el daño si alguien logra entrar.


> *"La seguridad es como una cebolla: tiene capas. Si solo ponés una, cuando la atraviesen, quedás expuesto. Las tres medidas juntas crean una defensa sólida."*

## ⚠️ Ataques a aplicaciones y servicios

Los ataques a aplicaciones y servicios son una de las formas más comunes de ataque. Se dividen en dos categorías principales:

| Tipo | Objetivo |
|------|----------|
| **Ataque de aplicación** | Explota una vulnerabilidad en una aplicación o software para obtener acceso no autorizado, robar datos o tomar control del sistema. |
| **Ataque de servicio** | Busca **apagar** una computadora o red, dejándola no disponible para los usuarios legítimos. |

---

### 📋 Tipos de ataques más frecuentes

#### 1. Denegación de servicio (DoS y DDoS)

| Característica | DoS | DDoS |
|----------------|-----|------|
| **¿Cuántos dispositivos atacan?** | Una sola computadora. | Múltiples dispositivos conectados (botnet). |
| **¿Cómo funciona?** | Inunda la máquina objetivo con peticiones hasta que no puede procesar el tráfico normal. | Satura el sitio web objetivo con tráfico falso desde muchos dispositivos a la vez. |
| **Resultado** | El servicio deja de estar disponible para usuarios legítimos. | Igual que DoS, pero a mucha mayor escala. |

**Analogía:** Un embotellamiento de autos rojos que impide que los autos blancos (usuarios legítimos) puedan entrar a la carretera.

---

#### 2. Ataque de intermediario (MITM)

| ¿Qué es? | ¿Cómo funciona? |
|----------|-----------------|
| Un atacante se interpone en una conversación o transferencia de datos entre dos participantes. | Se inserta en la comunicación y finge ser el participante legítimo para ambos lados. Ninguno de los dos sabe que el atacante está ahí. |

**¿Qué puede hacer el atacante?**
- Interceptar información y datos de cualquiera de las partes.
- Enviar enlaces maliciosos a ambos participantes.

**Abreviaturas:** MITM, MitM, MIM.

**Analogía:** Alguien que intercepta las cartas entre dos personas, las lee, las modifica y las reenvía sin que nadie se dé cuenta.

---

#### 3. Desbordamiento de búfer

| ¿Qué es? | ¿Cómo funciona? |
|----------|-----------------|
| Un programa intenta almacenar más datos en un área de almacenamiento temporal (búfer) de los que puede manejar. | Los datos sobrantes se desbordan hacia zonas de memoria cercanas, sobrescribiendo lo que haya allí. |

**¿Por qué es peligroso?**
- Puede causar fallos o dañar datos.
- Un atacante puede **enviar datos adicionales a propósito** para provocar el desbordamiento.
- Puede incluir **instrucciones dañinas** en el desbordamiento.
- Si el programa ejecuta esas instrucciones, el atacante puede **tomar control del sistema**.

**Analogía:** Una valija pequeña a la que le metés demasiada ropa. La ropa sobrante se desborda y hace un desastre alrededor.

---

#### 4. Día cero (Zero-day)

| Fase | ¿Qué ocurre? |
|------|--------------|
| **1. Vulnerabilidad introducida** | La organización publica software con una vulnerabilidad que desconoce. |
| **2. Vulnerabilidad descubierta** | Los atacantes encuentran la vulnerabilidad antes que el fabricante. |
| **3. Explotación** | Los atacantes lanzan malware aprovechando la vulnerabilidad. Todavía **no existe parche** (de ahí "día cero"). |
| **4. Solución desarrollada** | El fabricante se entera y crea un parche. |
| **5. Parche publicado** | El fabricante distribuye la solución. |
| **6. Parche implementado** | Los usuarios instalan la actualización. La vulnerabilidad deja de ser "día cero". |

**Dato clave:** Pueden pasar **meses o incluso años** antes de que el fabricante descubra la vulnerabilidad.

---

#### 5. Suplantación de identidad (Spoofing)

Un atacante usa un dispositivo o red para **hacerse pasar por una entidad legítima**. Esto le permite tomar control de dispositivos o acceder a datos confidenciales.

| Tipo de suplantación | ¿En qué consiste? |
|----------------------|-------------------|
| **Suplantación de IP** | Crear paquetes IP con direcciones de origen **falsas** para hacerse pasar por otro sistema. Permite infectar con malware, robar datos o colapsar servidores sin ser detectado. |
| **Envenenamiento de DNS** | Introducir información falsa en la caché de un servidor DNS. Las consultas devuelven una dirección IP incorrecta, enviando a los usuarios a **sitios web falsos**. También se llama "suplantación de DNS". |
| **Suplantación de MAC** | Interceptar o manipular los mensajes de control intercambiados entre un dispositivo y su dirección MAC. Permite **falsificar la identidad** de un dispositivo en la red. |

**Analogía:** Un actor malicioso usando una máscara para hacerse pasar por un usuario legítimo.

---

### 📊 Resumen de ataques

| Ataque | Tipo | Objetivo principal |
|--------|------|-------------------|
| **DoS / DDoS** | Servicio | Dejar un servicio no disponible. |
| **MITM** | Aplicación | Interceptar y manipular comunicaciones. |
| **Desbordamiento de búfer** | Aplicación | Tomar control del sistema explotando errores de memoria. |
| **Día cero** | Aplicación | Explotar vulnerabilidades antes de que exista parche. |
| **Suplantación (Spoofing)** | Aplicación/Red | Hacerse pasar por una entidad legítima para robar datos o lanzar ataques. |

### 🔍 Suplantación de IP, DNS y MAC: diferencias y aclaraciones

---

#### 📍 Suplantación de IP

**¿Qué es?**
Un atacante **falsea la dirección IP de origen** de los paquetes que envía. Es como poner un remitente falso en una carta. El que la recibe cree que viene de otro lado.

**Ejemplo concreto:**
Situación normal:
Tu PC (192.168.1.50) → Servidor (192.168.1.1)
El servidor sabe quién le habla.

Con suplantación de IP:
Atacante (IP real 10.0.0.99) → Falsea su IP como 192.168.1.50 → Servidor (192.168.1.1)
El servidor cree que le está hablando tu PC, cuando en realidad es el atacante.


**¿Para qué se usa?**

| Objetivo | ¿Cómo? |
|----------|--------|
| **Ocultar la identidad** | El atacante no quiere ser rastreado. |
| **Lanzar ataques DoS** | Enviar miles de paquetes con IP falsa para saturar un servidor. |
| **Saltarse filtros de seguridad** | Si el servidor solo acepta conexiones de ciertas IPs, el atacante falsifica una IP autorizada. |

---

#### 🆚 ¿Es lo mismo suplantación de IP que envenenamiento de DNS?

**No, no son lo mismo.** Hacen cosas distintas:

| | Suplantación de IP | Envenenamiento de DNS |
|--|---------------------|------------------------|
| **¿Qué falsea?** | La dirección IP de origen de un paquete. | La información dentro de la caché de un servidor DNS. |
| **¿Dónde actúa?** | En los paquetes de datos que viajan por la red. | En el servidor que traduce nombres a IPs. |
| **Resultado** | El servidor cree que le habla otra persona. | El usuario es enviado a un sitio web falso sin saberlo. |
| **Analogía** | Poner un remitente falso en una carta. | Cambiar las páginas de la guía telefónica para que el número de "Banco" lleve a la casa del ladrón. |

**Ejemplo de envenenamiento de DNS:**
Normal:
Escribís "banco.com" → DNS responde IP real: 200.10.5.1 → Vas al banco de verdad.

Envenenado:
Escribís "banco.com" → DNS responde IP falsa: 150.99.2.7 → Vas a una copia del banco hecha por el atacante.


> El usuario **no se da cuenta** porque la dirección del navegador sigue diciendo "banco.com". Pero está en un sitio falso.

---

#### 🔐 Suplantación de MAC y filtrado por MAC

**¿Qué es la suplantación de MAC?**
Cada dispositivo de red tiene una **dirección MAC** única (grabada de fábrica en la placa de red). La suplantación de MAC consiste en **cambiar esa dirección** para hacerse pasar por otro dispositivo.

**¿Para qué sirve?**

| Objetivo | ¿Cómo? |
|----------|--------|
| **Saltarse filtros MAC** | Si una red solo acepta ciertas MACs, el atacante copia una autorizada. |
| **Robar la identidad de un dispositivo** | El atacante se hace pasar por una impresora, cámara o PC legítima. |
| **Capturar tráfico** | Hacerse pasar por el router para que todos los dispositivos le envíen datos a él. |

---

#### 🛡️ ¿Sirve configurar el filtrado de direcciones MAC en el router?

El **filtrado de direcciones MAC** es una medida de seguridad que muchos routers domésticos permiten. Consiste en crear una **lista blanca** con las MACs de tus dispositivos. Cualquier dispositivo que no esté en la lista no se conecta.

| Ventajas | Desventajas |
|----------|-------------|
| ✅ Agrega una capa extra de seguridad. | ❌ Un atacante con conocimientos puede **espiar** las MACs autorizadas usando herramientas como Wireshark. |
| ✅ Fácil de configurar desde el panel del router. | ❌ Luego de ver una MAC autorizada, puede **cambiar su propia MAC** para hacerse pasar por ella (suplantación de MAC). |
| ✅ Filtra conexiones no deseadas de vecinos o intrusos casuales. | ❌ Es molesto cuando recibís visitas: cada vez hay que agregar la MAC del nuevo dispositivo. |

> **Conclusión:** El filtrado MAC es una barrera adicional, pero **no es infalible**. Es como un portero que revisa nombres en una lista. Si alguien escucha el nombre de un invitado autorizado y lo repite, puede entrar. **Complementa** otras medidas (contraseña fuerte, WPA3, firewall), pero **no reemplaza** una buena seguridad básica.

---

#### 📊 Comparación final de los tres tipos de suplantación

| Tipo | ¿Qué falsea? | ¿Se puede prevenir? |
|------|--------------|---------------------|
| **Suplantación de IP** | Dirección IP de origen de un paquete. | Firewalls configurados para rechazar paquetes con IPs inconsistentes. |
| **Envenenamiento de DNS** | Información en la caché del servidor DNS. | Usar DNSSEC (DNS Security Extensions). |
| **Suplantación de MAC** | Dirección MAC de un dispositivo. | Filtrado MAC (barrera parcial) + monitoreo de red para detectar MACs duplicadas. |


## 📡 Ataques inalámbricos

Los ataques inalámbricos explotan las características y funciones específicas de las **redes inalámbricas**. El objetivo suele ser el mismo que en los ataques a aplicaciones: **robar información, controlar dispositivos o dejar servicios fuera de línea**.

La tecnología inalámbrica ofrece flexibilidad, comodidad y velocidad, pero puede ser más vulnerable que las redes cableadas tradicionales.

---

### 📋 Tipos de ataques inalámbricos más comunes

#### 1. Gemelo malvado (Evil Twin)

| ¿Qué es? | ¿Cómo funciona? |
|----------|-----------------|
| Un tipo de ataque de **intermediario (MITM)** donde el atacante configura un **punto de acceso WiFi falso**. | El WiFi falso se hace pasar por uno legítimo. El nombre de la red (SSID) parece idéntico al real. |

**¿Dónde se usa?**
- Aeropuertos
- Cafeterías
- Parques públicos
- Cualquier lugar con WiFi gratuito

**¿Qué logra el atacante?**
- Robar información (contraseñas, datos bancarios).
- Infiltrarse en el dispositivo de la víctima.
- Redirigir a sitios web falsos.

**Analogía:** Un ladrón que monta un puesto de café falso al lado del verdadero. Los clientes le entregan su dinero sin saber que no es el auténtico.

---

#### 2. Punto de acceso no autorizado (Rogue Access Point)

| ¿Qué es? | ¿Es siempre malicioso? |
|----------|------------------------|
| Cualquier punto de acceso inalámbrico que **no pertenece a la red oficial**. | No siempre. Algunos son instalados por empleados sin mala intención o por personal de TI para pruebas. |

**Cuando es instalado por un atacante:**

| Riesgo | Consecuencia |
|--------|--------------|
| **Eludir firewalls y dispositivos de seguridad** | Abre la red a ataques externos. |
| **Monitorear la actividad del usuario** | El atacante ve qué sitios visitás y qué descargás. |
| **Redirigir a sitios falsos** | Te lleva a una página creada para robar información o instalar malware. |
| **Filtrar información confidencial** | Roba contraseñas, datos de tarjetas, documentos. |

**Diferencia clave con el gemelo malvado:**

| Gemelo malvado | Punto de acceso no autorizado |
|----------------|-------------------------------|
| Imita a un WiFi legítimo **fuera** de la red. | Está conectado **dentro** de la red oficial, saltándose las protecciones internas. |

---

#### 3. Jamming (Interferencia)

| ¿Qué es? | ¿Cómo funciona? |
|----------|-----------------|
| Un tipo de ataque de **denegación de servicio (DoS)** contra redes inalámbricas. | Un dispositivo emite **energía electromagnética** que interfiere con las señales legítimas, aumentando el ruido y haciendo la red inutilizable. |

**Otros métodos de jamming:**
- Causar un mal funcionamiento en el protocolo de "apretón de manos" (handshake) para que los dispositivos no puedan conectarse.
- Saturar las frecuencias de WiFi o Bluetooth.

**Resultado:** Los usuarios legítimos no pueden comunicarse.

**Analogía:** Un tipo con un megáfono gigante al lado tuyo mientras intentás hablar por teléfono. No escuchás nada.

---

#### 4. Bluesnarfing

| ¿Qué es? | ¿Cómo funciona? |
|----------|-----------------|
| Ataque que aprovecha **vulnerabilidades en Bluetooth** para robar información o usar el dispositivo de la víctima. | El atacante se cuela en dispositivos móviles que dejaron la conexión Bluetooth **abierta y detectable**. |

**¿Qué puede robar el atacante?**
- Correos electrónicos
- Lista de contactos
- Números de teléfono
- Contraseñas
- Fotos y archivos

**Otros riesgos:**
- Usar el teléfono de la víctima para hacer **llamadas caras o ilegales**.
- Los **altavoces inteligentes** también son vulnerables.

**¿Se necesita ser un experto?**
No. Existen herramientas de bluesnarfing **listas para usar** y hasta **servicios de bluesnarfer de alquiler**.

**Analogía:** Alguien que, sin que te des cuenta, te saca la billetera del bolsillo mientras caminás por la calle. No forcejea, solo aprovecha que la dejaste al alcance.

---

### 📊 Resumen de ataques inalámbricos

| Ataque | Tipo | ¿Qué busca? | ¿Dónde actúa? |
|--------|------|-------------|---------------|
| **Gemelo malvado** | MITM | Robar información interceptando tráfico. | WiFi (punto de acceso falso fuera de la red). |
| **Punto de acceso no autorizado** | Acceso | Abrir una puerta trasera en la red. | WiFi (punto de acceso conectado dentro de la red). |
| **Jamming** | DoS | Dejar la red inutilizable. | Frecuencias de WiFi/Bluetooth. |
| **Bluesnarfing** | Robo de datos | Robar información y usar el dispositivo. | Bluetooth. |

---

### 🛡️ Medidas de protección básicas

| Ataque | Cómo protegerse |
|--------|-----------------|
| **Gemelo malvado** | No conectarse a redes WiFi abiertas sin verificar. Usar VPN. |
| **Punto de acceso no autorizado** | Monitorear la red para detectar dispositivos no autorizados. |
| **Jamming** | Usar redes cableadas para servicios críticos. Monitorear la señal. |
| **Bluesnarfing** | Desactivar Bluetooth cuando no se use. No dejar el dispositivo en modo "detectable". |

### 🎭 Evil Twin hoy: ¿sigue siendo peligroso?

Si bien antes los ataques de Gemelo Malvado eran mucho más efectivos, hoy en día **siguen existiendo**, pero son **más difíciles de ejecutar con éxito** gracias a varias protecciones modernas. Sin embargo, los atacantes **evolucionaron** y encontraron nuevas formas de engañar a los usuarios.

---

### 🛡️ ¿Por qué ya casi no funciona el Evil Twin clásico?

| Protección moderna | ¿Qué hace? |
|--------------------|------------|
| **HTTPS en casi todas partes** | Casi todas las páginas usan HTTPS. Aunque el atacante intercepte el tráfico, **no puede leerlo** porque va cifrado. Los navegadores además muestran una alerta muy visible si un sitio no es seguro. |
| **Apps de home banking con SSL Pinning** | Las apps de los bancos tienen "grabada" la identidad exacta del servidor legítimo. Si alguien intenta hacerse pasar por el banco, la app **no se conecta**. No hay forma de engañarla con un WiFi falso. |
| **Cifrado de extremo a extremo (WhatsApp, Signal)** | Los mensajes se cifran en **tu celular** y solo se descifran en el celular de destino. Ni el atacante, ni el proveedor de internet, ni siquiera WhatsApp pueden leerlos. |
| **Navegadores más inteligentes** | Chrome, Firefox y Edge bloquean sitios de phishing conocidos y muestran advertencias muy visibles si algo falla con el certificado de seguridad. |

---

### ⚠️ Lo que TODAVÍA puede hacer un atacante con un Evil Twin

| Ataque | ¿Funciona hoy? | ¿Qué tan grave es? |
|--------|:---:|:---:|
| **Ver qué sitios visitás** (dominios) | ✅ Sí | Medio. Sabe que entraste a `banco.com`, pero no ve tu contraseña ni tu saldo. |
| **Redirigir a sitios falsos sin HTTPS** | ⚠️ Muy raro | Bajo. Casi ningún sitio importante usa HTTP hoy en día. |
| **Capturar datos de formularios no seguros** | ⚠️ Muy raro | Bajo. La mayoría de los formularios usan HTTPS. |
| **Inyectar malware en descargas** | ⚠️ Parcial | Medio. Solo funciona si la descarga es por HTTP, algo cada vez menos común. |
| **Ataque de degradación (forzar HTTP)** | ❌ Casi no | Muy bajo. Los navegadores modernos lo detectan y bloquean. |
| **Portal cautivo falso** | ✅ Sí | **Alto.** Es la evolución más peligrosa del Evil Twin. |

---

### 🚨 La amenaza real hoy: el Portal Cautivo Falso

Es la **evolución moderna del Evil Twin** y sí es peligrosa porque no intenta romper el cifrado: **te engaña a vos para que le entregues tus datos voluntariamente**.

#### ¿Qué es un portal cautivo?

Es esa página que aparece automáticamente cuando te conectás a un WiFi público, antes de poder navegar. Suele pedirte:
- Que aceptes los términos y condiciones.
- Que ingreses un código.
- Que inicies sesión con alguna cuenta.

**Ejemplos legítimos:**
- WiFi de aeropuertos.
- WiFi de hoteles.
- WiFi de cafeterías con sistema de acceso.

#### ¿Cómo funciona el portal cautivo falso?
Paso 1: El atacante crea un WiFi falso llamado "WiFi Gratis Aeropuerto".

Paso 2: La víctima se conecta. El celular muestra "Conectado" y abre automáticamente el portal cautivo.

Paso 3: El portal cautivo dice:
┌─────────────────────────────────────┐
│ ¡Bienvenido al WiFi del Aeropuerto! │
│ │
│ Para conectarse, inicie sesión │
│ con su cuenta: │
│ │
│ [✓] Google │
│ [ ] Facebook │
│ [ ] Correo electrónico │
└─────────────────────────────────────┘

Paso 4: La víctima hace clic en "Google". Se abre una página que se ve
EXACTAMENTE igual al inicio de sesión real de Google.

Paso 5: La víctima ingresa su email y contraseña reales.

Paso 6: El atacante YA TIENE las credenciales de Google de la víctima.
Con eso accede a Gmail, Drive, YouTube, fotos, y todo lo demás.


#### ¿Por qué es tan efectivo?

| Motivo | Explicación |
|--------|-------------|
| **Es visualmente idéntico** | La página de inicio de sesión falsa se ve exactamente igual a la real. El candado HTTPS incluso puede aparecer si el atacante usa un certificado válido para su sitio falso. |
| **El usuario lo entrega voluntariamente** | No está rompiendo ningún cifrado. La víctima **escribe su contraseña por voluntad propia** creyendo que es legítimo. |
| **Es común en WiFi públicos** | La gente está acostumbrada a que los WiFi públicos pidan iniciar sesión. No sospechan. |
| **Funciona en cualquier dispositivo** | Celular, tablet, laptop. Todos son vulnerables a este engaño. |

---

### 🛡️ ¿Cómo protegerse del portal cautivo falso?

| Medida | ¿Por qué funciona? |
|--------|--------------------|
| **No uses WiFi públicos abiertos para nada sensible** | Si necesitás hacer algo importante (banco, email, compras), usá tus datos móviles 4G/5G. |
| **Si el portal cautivo te pide iniciar sesión con Google, Facebook o email... desconfiá** | Un WiFi legítimo rara vez necesita tus credenciales de redes sociales. Lo más común es que solo pida aceptar términos y condiciones. |
| **Verificá la URL antes de ingresar datos** | Si dice `google.com` es legítimo. Si dice `google-login-wifi.com` o cualquier variante rara, es falso. |
| **Usá autenticación multifactor (MFA)** | Aunque el atacante robe tu contraseña, no podrá entrar sin el segundo factor (código en tu celular, huella, etc.). |
| **No reutilices contraseñas** | Si usás la misma contraseña para todo, el atacante que roba tu "contraseña del WiFi" ahora tiene acceso a tu banco, email y redes. |
| **Preguntá al personal del lugar** | "¿Tienen WiFi? ¿Cuál es el nombre exacto y cómo se accede?". Así sabés si el portal cautivo que te aparece es el real. |

---

### 📊 Evolución del Evil Twin

| Época | Método del atacante | ¿Funcionaba? |
|-------|---------------------|:---:|
| **Antes (2005-2015)** | Interceptar tráfico HTTP directamente. Leer contraseñas en texto plano. | ✅ Muy efectivo |
| **Transición (2015-2020)** | HTTPS se generaliza. El atacante intenta degradar conexiones o usar certificados falsos. | ⚠️ Menos efectivo |
| **Hoy (2020-presente)** | Portal cautivo falso. Phishing directo al usuario. Robo de cookies de sesión. | ✅ Efectivo (pero más difícil de ejecutar) |

> *"Antes el atacante podía leer tus cartas espiando al cartero. Ahora las cartas van en una caja fuerte blindada. Pero si vos le abrís la caja fuerte al atacante porque creíste que era el del banco, el resultado es el mismo."*

### 🔵 Bluesnarfing: el riesgo de andar con Bluetooth prendido por la ciudad

---

#### ¿Qué es el bluesnarfing?

Es un ataque donde alguien accede a tu dispositivo a través de Bluetooth **sin que te des cuenta**, para robar información o usar tu equipo.

| Palabra | Significado |
|---------|-------------|
| **Blue** | Bluetooth |
| **Snarf** | Término hacker para "robar datos sin dejar rastro" |

---

#### ¿Cómo funciona paso a paso?

| Fase | ¿Qué hace el atacante? |
|------|------------------------|
| **1. Escaneo** | Camina por la calle, un centro comercial, un subte, un bar. Con su laptop o celular escanea dispositivos con Bluetooth encendido y **detectable**. |
| **2. Detección** | Ve tu celular en la lista. Aparece el nombre: "iPhone de María", "Galaxy S24", "Auriculares JBL". Ya sabe qué dispositivo tenés. |
| **3. Conexión** | Explota una vulnerabilidad del Bluetooth para **conectarse sin que vos aceptes**. No te aparece ningún mensaje de "¿Aceptar conexión?". Entra directo. |
| **4. Robo** | Una vez conectado, copia tus contactos, fotos, mensajes, contraseñas guardadas, archivos. También puede hacer llamadas desde tu número. |
| **5. Desconexión** | Se va. Vos no te enteraste de nada. Seguís caminando como si nada. |

---

#### ¿Qué tan cerca tiene que estar el atacante?

| Versión de Bluetooth | Alcance aproximado |
|----------------------|---------------------|
| **Bluetooth clásico (hasta 4.0)** | 10 metros |
| **Bluetooth 5.0 en adelante** | Hasta 100 metros (en espacio abierto) |

> Un atacante puede estar sentado en la misma cafetería, en la mesa de al lado en el patio de comidas, o caminando detrás tuyo en la calle. Ni lo notás.

---

#### ¿Qué información puede robar?

| Dato | ¿Se puede robar? | Ejemplo |
|------|:---:|---------|
| **Lista de contactos** | ✅ Sí | Nombres y teléfonos de toda tu agenda. |
| **Fotos y videos** | ✅ Sí | Tus fotos personales, documentos escaneados. |
| **Correos electrónicos** | ✅ Sí | Si el cliente de correo está sincronizado localmente. |
| **Contraseñas guardadas** | ⚠️ Depende | Si están en archivos accesibles del sistema. |
| **Mensajes SMS** | ✅ Sí | Mensajes de texto, códigos de verificación. |
| **Llamadas** | ✅ Sí | El atacante puede **usar tu número** para hacer llamadas caras o ilegales. |
| **Datos de apps** | ⚠️ Depende | Algunas apps almacenan datos localmente sin cifrar. |

---

#### 🎯 Escenario real en la ciudad
Lugar: Patio de comidas de un shopping. Hora pico. Mucha gente.

Atacante:

Se sienta en una mesa con su mochila. Saca una laptop o un celular.

Abre una herramienta de escaneo Bluetooth (gratuita, fácil de encontrar).

En 30 segundos ve 15 dispositivos con Bluetooth detectable:

"iPhone de Laura"

"Galaxy S24 de Carlos"

"AirPods Pro"

"Auriculares Sony"

Selecciona uno. La herramienta busca vulnerabilidades conocidas.

Si encuentra una sin parche, se conecta en segundos.

Descarga contactos, fotos y mensajes.

Cierra todo. Se va a otra mesa o a otro shopping.

La víctima:

Está almorzando con amigos. Ni se enteró.

Tenía Bluetooth prendido porque siempre lo deja así.

El dispositivo estaba en modo "detectable" (configuración por defecto).


---

#### ⚠️ ¿Esto todavía funciona hoy?

| Época | ¿Era fácil? | ¿Por qué? |
|-------|:---:|-----------|
| **2005-2012** | ✅ Muy fácil | Bluetooth tenía muchas vulnerabilidades. Los parches tardaban años en llegar. |
| **2013-2019** | ⚠️ Más difícil | Los sistemas operativos mejoraron. Android e iOS limitan la detectabilidad. |
| **2020-hoy** | ❌ Más difícil, pero no imposible | Los parches llegan rápido. Pero **siempre hay dispositivos desactualizados** o vulnerabilidades nuevas (zero-day). |

**Hoy en día es más difícil porque:**
- Los celulares modernos piden confirmación para conexiones entrantes.
- El modo "detectable" suele apagarse solo después de unos minutos.
- Los parches de seguridad se instalan automáticamente.

**Pero sigue siendo posible si:**
- Tenés un dispositivo viejo sin actualizar.
- Dejaste el Bluetooth en modo detectable permanentemente.
- Aparece una vulnerabilidad zero-day que todavía no tiene parche.

---

#### 🔵 Dispositivos más vulnerables

| Dispositivo | ¿Por qué es más vulnerable? |
|-------------|------------------------------|
| **Auriculares Bluetooth** | Siempre están en modo "emparejamiento" o detectable. No tienen pantalla para pedir confirmación. Algunos modelos baratos no tienen seguridad. |
| **Parlantes inteligentes** | Siempre escuchando conexiones. Si no están actualizados, son una puerta de entrada. |
| **Smartwatches** | Se conectan automáticamente. Algunos transfieren datos de salud, notificaciones y mensajes. |
| **Dispositivos IoT** | Cerraduras inteligentes, sensores, rastreadores. Muchos no reciben actualizaciones de seguridad. |

**Ejemplo real con auriculares:**
Un atacante podría conectarse a tus auriculares Bluetooth mientras viajás en subte. No para robarte datos, sino para **escuchar lo que estás escuchando** o incluso **inyectar audio** (meter ruido o voces en tus auriculares sin que sepas de dónde viene).

---

#### 🛡️ ¿Cómo protegerse?

| Medida | ¿Qué hace? |
|--------|------------|
| **Apagar Bluetooth cuando no lo uses** | Si no estás usando auriculares, el auto o el smartwatch, **apagalo**. Es la medida más efectiva. |
| **No dejar el dispositivo en modo "detectable"** | En Android e iOS, la opción de "Visible para otros dispositivos" debe estar desactivada. |
| **No aceptar conexiones de dispositivos desconocidos** | Si te aparece un mensaje para emparejar con algo que no reconocés, **rechazalo**. |
| **Eliminar dispositivos emparejados que ya no uses** | Esa impresora vieja, el parlante que ya no tenés, el auto que vendiste. Borralos de la lista. |
| **Mantener el sistema operativo actualizado** | Los parches de seguridad cierran vulnerabilidades de Bluetooth. |
| **No usar dispositivos Bluetooth baratos o genéricos** | Muchos no tienen seguridad implementada. Son una puerta abierta. |
| **Usar auriculares y dispositivos de marcas reconocidas** | Suelen tener mejor soporte y actualizaciones. |

---

#### 🎯 En resumen

| Andar con Bluetooth prendido por la ciudad... |
|-----------------------------------------------|
| ❌ No es seguro. |
| ⚠️ El riesgo real es bajo si tenés el sistema actualizado, pero **no es cero**. |
| 🎯 Un atacante paciente puede encontrar un dispositivo vulnerable en un lugar concurrido. |
| 🛡️ **Apagalo si no lo necesitás.** Es un gesto simple que elimina el riesgo por completo. |

> *"El Bluetooth es como la puerta de tu casa. Si la dejás abierta, no significa que te vayan a robar seguro. Pero es mucho más fácil para el ladrón. Cerrar la puerta (apagar el Bluetooth) es lo más inteligente."*

## 🛡️ Lección 2: Dispositivos de seguridad de red

Ya aprendiste algunos de los ataques que pueden amenazar una red. Los ciberataques ocurren a un ritmo cada vez mayor y los atacantes **evolucionan constantemente** sus métodos.

**La pregunta lógica es:** ¿Cómo podemos mantenernos al día y seguir protegiendo las redes y los datos?

Afortunadamente, existen **herramientas** para contraatacar. En esta lección vamos a ver los **dispositivos de seguridad de red** y el hardware que se puede usar para proteger una red y sus activos de acciones maliciosas.

---

### 📋 Lo que vamos a ver en esta lección

| Tema | Descripción |
|------|-------------|
| **Dispositivos de seguridad de red** | Herramientas físicas y virtuales que protegen la infraestructura. |
| **Hardware de protección** | Firewalls, IDS/IPS, proxies, VPN concentrators y más. |
| **Cómo funcionan** | El papel de cada dispositivo en la defensa de la red. |

---

### 🧠 Idea clave

> *"No basta con conocer los ataques. Hay que saber qué herramientas existen para detenerlos. Cada dispositivo de seguridad cumple un rol específico en la defensa."*

