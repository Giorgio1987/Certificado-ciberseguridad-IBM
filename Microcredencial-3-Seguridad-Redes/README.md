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

### 🔧 ¿Qué son los dispositivos de seguridad de red?

La seguridad de la red implica implementar **hardware y software** para proteger la red y la infraestructura del acceso no autorizado, las interrupciones y los ataques.

Una seguridad de red efectiva ayuda a proteger los activos de la organización contra amenazas tanto **externas** como **internas**.

---

### 📋 Dispositivos más comunes para combatir amenazas

| Dispositivo | Función principal | Imagen mental |
|-------------|-------------------|---------------|
| **Firewalls (Cortafuegos)** | Filtran el tráfico entrante y saliente según reglas de seguridad. Son la primera línea de defensa. | Un guardia de seguridad que revisa quién entra y quién sale. |
| **Enrutadores (Routers)** | Dirigen el tráfico entre redes. Pueden incluir funciones de seguridad como listas de control de acceso (ACL). | Un semáforo que decide por dónde va cada auto. |
| **Conmutadores de red (Switches)** | Conectan dispositivos dentro de una misma red. Algunos ofrecen segmentación y seguridad a nivel de puerto. | Las calles internas de un barrio cerrado. |
| **Servidores proxy** | Actúan como intermediarios entre los usuarios e internet. Filtran contenido, ocultan direcciones IP y cachean datos. | Un mayordomo que recibe los paquetes en la puerta y los revisa antes de entregártelos. |
| **Equilibradores de carga (Load Balancers)** | Distribuyen el tráfico entre varios servidores para evitar sobrecargas y mejorar la disponibilidad. | Un empleado que reparte gente entre varias cajas para que ninguna se sature. |
| **Módulos de seguridad de hardware (HSM)** | Almacenan y protegen claves de cifrado en un dispositivo físico especializado. | Una caja fuerte específicamente diseñada para guardar llaves. |

---

### 🧠 En resumen

> *"Cada dispositivo de seguridad cumple un rol específico. Como las piezas de un equipo de fútbol: el arquero (firewall), los defensores (proxy), los mediocampistas (router/switch) y el director técnico que organiza (load balancer). Todos trabajan juntos para proteger la red."*

### 🔥 Firewalls (Cortafuegos)

El término "firewall" proviene del siglo XVII y se refería a un **muro ignífugo** para evitar que los incendios se propagaran. En los años 70, los ingenieros informáticos lo adoptaron para describir herramientas que evitan que los ciberataques tengan éxito.

**¿Qué hace un firewall?**
Monitorea **todo el tráfico** entre una red e Internet. Examina cada paquete que entra y sale y aplica **reglas predefinidas** para decidir si lo permite o lo bloquea.

---

#### 🧠 Analogía

> Un firewall es como un **controlador de tráfico** en la entrada de un edificio. Revisa cada vehículo (paquete), consulta su lista de reglas y decide quién puede pasar y quién no.

**Funciones del firewall:**
- Bloquear tráfico no deseado o fuentes no reconocidas.
- Validar el acceso evaluando el tráfico en busca de malware o ataques.

---

#### 📋 Métodos de filtrado de reglas de firewall

| Método | ¿Cómo funciona? | Ejemplo |
|--------|------------------|---------|
| **Permitir o bloquear (filtrado simple)** | El tipo más básico. Permite o bloquea **todo** el tráfico que cumple con los criterios establecidos. | Bloquear todo el tráfico del puerto 80 (HTTP). Permitir solo el puerto 443 (HTTPS). |
| **Filtrado basado en origen y destino** | Permite o bloquea tráfico según **de dónde viene** (IP de origen) o **hacia dónde va** (IP de destino). | Bloquear todo el tráfico que venga de Rusia. Permitir solo conexiones hacia el servidor de la empresa. |
| **Filtrado de inspección con estado (Stateful)** | Analiza si el paquete forma parte de una **conexión previamente establecida**. No solo mira el paquete individual, sino el contexto. | Si un usuario interno pidió una página web, el firewall deja entrar la respuesta. Si alguien externo intenta iniciar una conexión, la bloquea. |
| **Filtrado a nivel de aplicación** | Bloquea el tráfico de **aplicaciones específicas** que no son relevantes para el trabajo. | Bloquear Netflix, YouTube o torrents en la red corporativa. Permitir solo aplicaciones de trabajo. |

---

#### 📊 Tipos de reglas en resumen

| Regla se basa en... | ¿Qué filtra? |
|---------------------|--------------|
| **Números de puerto** | Tráfico por servicio (HTTP: 80, HTTPS: 443, FTP: 21). |
| **Protocolos** | TCP, UDP, ICMP. |
| **Nombres de dominio** | `facebook.com`, `netflix.com`. |
| **Direcciones IP** | IPs específicas o rangos de IPs. |
| **Usuarios** | Tráfico según el usuario autenticado. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firewall de Windows Defender** | Es un firewall a nivel de host. Los firewalls de red protegen toda la infraestructura. |
| **Hardening del sistema** | Configurar reglas de firewall es una práctica de hardening. |
| **Superficie de ataque** | Un firewall bien configurado reduce drásticamente la superficie de ataque. |

### 📡 Enrutadores (Routers)

Los enrutadores son la **conexión de hardware** de una red a datos externos, generalmente desde Internet. Los datos viajan desde un módem al router, que luego los dirige a los dispositivos de la red.

---

#### ⚠️ El peligro de un router inseguro

Si un router funciona con la **configuración predeterminada de fábrica**:

| Riesgo | Consecuencia |
|--------|--------------|
| Dirección IP pública sin contraseña WiFi única. | Cualquiera con un dispositivo inalámbrico puede acceder. |
| Contraseña de administrador por defecto (`admin/admin`). | Un atacante puede tomar control del router. |
| Sin cifrado o con cifrado débil. | La información sensible viaja expuesta. |

**Datos en riesgo:** correos electrónicos, información bancaria, programación de dispositivos inteligentes del hogar.

---

#### 🛡️ Cómo mantener seguro un enrutador

| Paso | Acción |
|------|--------|
| **1** | Buscar la **dirección IP** del router (en el manual o sitio del fabricante). |
| **2** | Encontrar el **nombre de usuario y contraseña** de administrador. |
| **3** | Desde un navegador, ingresar la dirección IP del router en la barra de búsqueda. |
| **4** | Iniciar sesión con el usuario y contraseña de administrador. |
| **5** | Crear un **nombre para el router** que no sea fácilmente asociable a vos (no usar tu apellido). |
| **6** | **Cambiar la contraseña inmediatamente.** Elegir una contraseña compleja, única y difícil de adivinar. |
| **7** | Seleccionar un **tipo de cifrado** fuerte. |
| **8** | Guardar la configuración actualizada. |

---

#### 🔐 Tipos de cifrado del router

| Tipo | Seguridad | Características |
|------|:---:|------------------|
| **WEP** (Wired Equivalent Privacy) | ❌ Muy baja | El más antiguo y el **menos seguro**. Usa ondas de radio fáciles de descifrar. Misma clave para cada paquete. Los atacantes pueden analizarlo fácilmente con software automatizado. |
| **WPA** (Wi-Fi Protected Access) | ⚠️ Media | Desarrollado para resolver los defectos de WEP. Codifica la clave de cifrado. Más seguro que WEP, pero aún vulnerable. |
| **WPA2** (Wi-Fi Protected Access 2) | ✅ Alta | Actualmente la **forma más segura** disponible para la mayoría de los routers. Codifica la clave de cifrado y no permite protocolos débiles como TKIP. |
| **WPA3** (Wi-Fi Protected Access 3) | ✅ Muy alta | La versión más reciente. Protección contra ataques de fuerza bruta y cifrado más robusto. Disponible en routers modernos. |
| **AES** (Advanced Encryption Standard) | ✅ Muy alta | Cifrado extremadamente seguro. Es el mismo tipo que usa el gobierno de EE.UU. para información clasificada. Se debe usar **junto con WPA2 o WPA3**. Routers fabricados después de 2006 deberían tener esta opción. |

---

#### 📊 Comparación de cifrados

| Cifrado | ¿Se recomienda? | ¿Por qué? |
|---------|:---:|-----------|
| **WEP** | ❌ No | Obsoleto. Se descifra en minutos. |
| **WPA** | ❌ No | Mejor que WEP, pero aún vulnerable. |
| **WPA2 + AES** | ✅ Sí | Seguro y ampliamente compatible. |
| **WPA3 + AES** | ✅ Sí (recomendado) | La opción más segura disponible hoy. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firmware del router** | Mantener el firmware actualizado es parte de la seguridad del router. |
| **Plan de firmware de seguridad** | Los pasos para asegurar el router son parte del plan. |
| **Contraseñas seguras** | Cambiar la contraseña por defecto es una práctica esencial de hardening. |
| **Cifrado** | Elegir WPA2/WPA3 con AES protege la red inalámbrica. |

> *"Un router con la configuración de fábrica es una puerta abierta. Cambiar la contraseña, elegir un buen cifrado y mantener el firmware actualizado son los tres pilares de la seguridad del router."*

### 🔀 Conmutadores de red (Switches)

Mientras que las redes domésticas suelen tener solo un módem, un router y algunos dispositivos, las organizaciones necesitan conectar y gestionar muchos más equipos. Para eso usan **conmutadores de red**.

---

#### ¿Qué hace un switch?

Un switch **integra todos los dispositivos de una red**, permitiendo que compartan y transfieran datos sin problemas entre ellos.

**Dispositivos que puede conectar:**
- Firewalls
- Puntos de acceso inalámbricos
- Teléfonos VoIP
- Impresoras
- Servidores
- Computadoras
- Cámaras de seguridad
- Y más...

---

#### 🛠️ ¿Qué permite hacer?

| Función | Beneficio |
|---------|-----------|
| **Conexión centralizada** | Todos los dispositivos se conectan al switch, que los comunica entre sí. |
| **Gestión centralizada** | Los administradores pueden controlar y monitorear todos los dispositivos desde una sola plataforma. |
| **Asignación de recursos** | Permite mover recursos rápidamente por la red según sea necesario. |

---

#### ⚠️ Vulnerabilidades de seguridad

Debido a que los switches conectan tantos dispositivos, son un **blanco atractivo para los atacantes**. Si comprometen un switch, pueden obtener acceso a toda la red.

**Riesgos:**
- Acceso no autorizado a la red.
- Interceptación de tráfico entre dispositivos.
- Ataques de suplantación de MAC.

---

#### 🛡️ Cómo proteger un switch

| Medida | ¿En qué consiste? |
|--------|-------------------|
| **Seguridad física** | Bloquear físicamente el switch en un armario o rack con acceso restringido. |
| **Deshabilitar puertos no utilizados** | Apagar los puertos que no tienen dispositivos conectados para que nadie pueda enchufar algo sin autorización. |
| **Configurar ajustes de firmware** | Mantener el firmware actualizado y revisar la configuración de seguridad. |
| **Segmentación (VLANs)** | Separar la red en segmentos lógicos para aislar dispositivos sensibles. |
| **Port Security** | Limitar qué direcciones MAC pueden conectarse a cada puerto. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firmware** | Los switches tienen firmware que debe actualizarse. |
| **Suplantación de MAC** | Un switch protegido con port security puede prevenir este ataque. |
| **Hardening del sistema** | Deshabilitar puertos no usados es una práctica de hardening. |
| **Superficie de ataque** | Cada puerto abierto en un switch es un punto de entrada potencial. |

> *"Un switch es como una central telefónica: conecta a todos. Si alguien toma el control de la central, puede escuchar todas las conversaciones. Por eso protegerlo es crítico."*

### 🔄 Servidores proxy

Un medio importante para implementar firewalls es a través de **servidores proxy**.

---

#### ¿Qué es un servidor proxy?

Un **proxy** (o servidor proxy) es un sistema o router que actúa como **puerta de enlace** entre los usuarios e Internet. A veces se lo llama **"intermediario"** porque va entre los usuarios y los sitios web que visitan.

Usuario → Servidor Proxy → Internet → Sitio web
↑
Tiene su propia IP.
La red conoce esta dirección.


---

#### ¿Cómo funciona?

| Paso | Acción |
|------|--------|
| **1** | El usuario envía una solicitud para visitar un sitio web. |
| **2** | La solicitud viaja a través del servidor proxy. |
| **3** | El proxy obtiene la respuesta del servidor web (usando su propia IP, no la del usuario). |
| **4** | El proxy reenvía los datos al navegador del usuario. |

---

#### 🛡️ ¿Qué capa de seguridad proporciona?

| Función de seguridad | ¿Cómo lo hace? |
|----------------------|----------------|
| **Filtrado de contenido** | Los administradores pueden configurar filtros web para bloquear sitios maliciosos o no deseados. |
| **Protección contra malware** | El proxy puede analizar el tráfico entrante en busca de software malicioso antes de que llegue al usuario. |
| **Ocultar direcciones IP** | El sitio web de destino ve la IP del proxy, no la del usuario. Esto protege la privacidad. |
| **Protección contra espionaje** | Protege la actividad de los empleados contra miradas externas. |

---

#### 🚀 Otras tareas clave del proxy

| Función | Beneficio |
|---------|-----------|
| **Balanceo de tráfico** | Distribuye las solicitudes para evitar fallos y sobrecargas. |
| **Ahorro de ancho de banda** | Almacena archivos en **caché**. Si varios usuarios piden lo mismo, el proxy lo entrega sin volver a pedirlo a Internet. |
| **Compresión de tráfico** | Comprime datos entrantes para reducir el consumo de ancho de banda. |
| **Integración con otras herramientas** | Se puede combinar con puertas de enlace web seguras o productos de seguridad de email. |

---

#### 🧠 Analogía

> Un proxy es como un **asistente personal** que hace los mandados por vos:
> - Vos le decís "traeme el diario".
> - Él va al kiosco, compra el diario y te lo trae.
> - El kiosquero no sabe quién sos vos. Solo ve al asistente.
> - Si el diario viene con algo sospechoso, el asistente lo revisa antes de entregártelo.

---

#### 📊 Ventajas del proxy

| Ventaja | Explicación |
|---------|-------------|
| **Privacidad** | Los sitios web no ven tu IP real. |
| **Seguridad** | Filtra malware y sitios maliciosos antes de que lleguen a vos. |
| **Control** | La empresa puede decidir qué sitios se permiten y cuáles no. |
| **Rendimiento** | La caché acelera el acceso a sitios visitados frecuentemente. |
| **Ahorro** | Comprime datos y reduce el consumo de ancho de banda. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firewall** | Un proxy puede funcionar como firewall a nivel de aplicación. |
| **Tipos de servidores** | El servidor proxy es uno de los tipos de servidores vistos en el módulo 3. |
| **Superficie de ataque** | El proxy reduce la superficie de ataque ocultando las IPs internas. |
| **Filtrado de contenido** | Similar a las reglas de firewall, pero a nivel de aplicación web. |

### ⚖️ Equilibradores de carga (Load Balancers)

Un **equilibrador de carga** es un dispositivo de hardware dedicado o un servidor orientado a Internet que ejecuta un servicio de balanceo de carga.

---

#### ¿Qué hace un balanceador de carga?

| Función | ¿En qué consiste? |
|---------|-------------------|
| **Distribuir tráfico** | Reparte las solicitudes entre **varios servidores** para que ninguno se sobrecargue. |
| **Descifrar tráfico SSL** | Puede descifrar el tráfico HTTPS para aliviar la carga de los servidores web. |
| **Mejorar rendimiento** | Ahorra tiempo a los servidores y mejora la velocidad de las aplicaciones. |

---

#### 🧠 Analogía

> Un balanceador de carga es como el **empleado de un banco** que organiza la fila y va repartiendo clientes entre las cajas disponibles:
> - Si una caja está ocupada, manda al siguiente cliente a otra caja libre.
> - Si una caja se descompone, deja de mandarle gente.
> - Los clientes no se amontonan en una sola caja.

Usuarios → Balanceador de carga → Servidor 1
→ Servidor 2
→ Servidor 3


---

#### 📊 Tipos de balanceadores de carga

| Tipo | Características |
|------|-----------------|
| **Hardware dedicado** | Dispositivo físico especializado. Alto rendimiento, pero costoso y requiere mantenimiento. |
| **Servidor (software)** | Se instala en un servidor común. Más flexible y económico. |
| **En la nube** | Servicio ofrecido por proveedores cloud (AWS, Azure, Google Cloud). Se está volviendo la opción **más popular**. |

---

#### ⚠️ Consideraciones de seguridad

Independientemente del tipo de balanceador, los administradores deben considerar:

| Riesgo | Descripción |
|--------|-------------|
| **Vulnerabilidades del propio balanceador** | El dispositivo o software puede tener fallos de seguridad. |
| **Configuración incorrecta** | Una mala configuración puede exponer la red o los servidores. |
| **Uso inadecuado** | No actualizarlo o no monitorearlo correctamente. |

---

#### ☁️ Ventajas del balanceo de carga en la nube

| Ventaja | ¿Por qué? |
|---------|-----------|
| **Menos vulnerable a explotación** | Los proveedores cloud protegen sus productos rigurosamente. |
| **Parches rápidos** | Si encuentran un problema, lo solucionan de inmediato. |
| **Servicio independiente** | Es difícil para un atacante penetrar el balanceador para comprometer la red. |
| **Resuelve riesgos de sistemas tradicionales** | Elimina muchos de los problemas de los balanceadores físicos antiguos. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Disponibilidad** | El balanceador garantiza que los servicios sigan funcionando aunque un servidor falle. |
| **Ataques DoS/DDoS** | Un balanceador ayuda a mitigar ataques distribuyendo el tráfico malicioso. |
| **Tipos de servidores** | El balanceador trabaja en conjunto con servidores web y de aplicaciones. |
| **Hardening** | Configurar correctamente el balanceador es parte del hardening de la red. |

> *"Un balanceador de carga es como un director de tránsito inteligente. Si una calle se congestiona, desvía el tráfico por otra. Y si alguien intenta saturar una calle a propósito, distribuye los autos para que nadie se quede parado."*

### 🔑 Módulos de seguridad de hardware (HSM)

La **criptografía** es una parte clave de la seguridad de la red. Las organizaciones usan **módulos de seguridad de hardware** para realizar funciones criptográficas y proteger las claves.

---

#### ¿Qué es un HSM?

Un **HSM (Hardware Security Module)** es un **procesador criptográfico dedicado**, diseñado específicamente para proteger el **ciclo de vida de la clave criptográfica**.
Servidor/aplicación → Solicita cifrar, descifrar o firmar → HSM (guarda y protege las claves)


---

#### 🛡️ ¿Qué hace un HSM?

| Función | Descripción |
|---------|-------------|
| **Gestionar claves** | Administra de forma segura todo el ciclo de vida de las claves criptográficas (creación, almacenamiento, uso, rotación, destrucción). |
| **Procesar claves** | Realiza operaciones criptográficas dentro de un dispositivo **reforzado y resistente a manipulaciones**. |
| **Almacenar claves** | Guarda las claves en hardware seguro. Si alguien intenta abrir físicamente el dispositivo, las claves se destruyen automáticamente. |
| **Cifrar y descifrar** | Realiza cifrado y descifrado de datos. |
| **Autenticación** | Verifica identidades mediante firmas digitales. |
| **Firma digital** | Crea firmas digitales para transacciones, documentos y software. |

---

#### 🏢 ¿Quiénes usan HSM?

Los HSM actúan como **anclas de confianza** que protegen la infraestructura criptográfica de las organizaciones más preocupadas por la seguridad del mundo.

| Industria | ¿Para qué lo usa? |
|-----------|-------------------|
| **Bancos y finanzas** | Proteger transacciones financieras, identidades de clientes y cumplir con normativas (PCI-DSS). |
| **Gobierno** | Proteger información clasificada y firmar documentos oficiales. |
| **Certificadoras (CA)** | Proteger las claves privadas que firman certificados digitales (HTTPS). |
| **Salud** | Proteger datos de pacientes (HIPAA). |
| **Nube** | Los proveedores cloud ofrecen HSM como servicio para sus clientes. |

---

#### 🧠 Analogía

> Un HSM es como una **caja fuerte especializada para llaves digitales**:
> - Guarda las llaves (claves criptográficas) en un lugar extremadamente seguro.
> - Solo las usa dentro de la caja. Las llaves **nunca salen** del HSM.
> - Si alguien intenta forzar la caja, las llaves se **autodestruyen**.
> - Es a prueba de manipulaciones, fuego, golpes y hackers.

---

#### 📊 Características clave

| Característica | Explicación |
|----------------|-------------|
| **Dedicado** | Es hardware diseñado exclusivamente para tareas criptográficas. |
| **Reforzado** | Construido para resistir ataques físicos y lógicos. |
| **Resistente a manipulaciones** | Si detecta manipulación, borra las claves automáticamente. |
| **Alto rendimiento** | Puede procesar miles de operaciones criptográficas por segundo. |
| **Cumplimiento normativo** | Ayuda a cumplir con estándares como FIPS 140-2, PCI-DSS, GDPR. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Cifrado** | El HSM es el dispositivo que realiza y protege el cifrado. |
| **Autenticación segura** | Los HSM almacenan las claves usadas en autenticación y firmas digitales. |
| **Copia de seguridad** | Las claves del HSM también necesitan respaldo seguro. |
| **PKI (Infraestructura de clave pública)** | Los HSM son el corazón de una PKI: protegen las claves privadas de las autoridades certificadoras. |

> *"Un HSM es el guardián definitivo de las claves. Si las claves son el secreto mejor guardado, el HSM es la fortaleza donde viven. Sin HSM, las claves estarían en software común, mucho más vulnerables a robos."*

### 💼 Gestión de carrera: Administrador de red

Los **administradores de red** gestionan y mantienen las redes informáticas para que los usuarios y los servicios puedan acceder a los recursos de red de manera **eficiente y segura**.

---

#### 📋 ¿Qué hace un administrador de red?

| Responsabilidad | Descripción |
|-----------------|-------------|
| **Crear y aplicar políticas y procedimientos** | Define las reglas de uso de la red y las hace cumplir. |
| **Monitorear la red** | Supervisa el tráfico, el rendimiento y la seguridad de forma continua. |
| **Solucionar problemas** | Diagnostica y resuelve fallos de conectividad, rendimiento o seguridad. |
| **Gestionar cuentas de usuario** | Crea, modifica y elimina usuarios. Asigna permisos y controla accesos. |
| **Colaborar con ciberseguridad** | En organizaciones grandes, trabaja junto al equipo de seguridad. En empresas pequeñas, puede ser el responsable directo de la seguridad de la red. |

---

#### 🛠️ Tecnologías que debe dominar

| Tecnología | ¿Para qué? |
|------------|------------|
| **Sistemas operativos** | Windows Server, Linux, macOS. |
| **Enrutadores (Routers)** | Dirigir el tráfico entre redes. |
| **Conmutadores (Switches)** | Conectar dispositivos dentro de la red. |
| **Firewalls** | Proteger la red filtrando tráfico malicioso. |
| **Servidores proxy** | Intermediar entre usuarios e Internet. |
| **Redes inalámbricas** | Gestionar puntos de acceso WiFi y su seguridad. |

---

#### 🔍 Habilidades clave

| Habilidad | ¿Por qué es importante? |
|-----------|-------------------------|
| **Evaluar nuevas tecnologías** | Determinar si pueden mejorar el diseño o la funcionalidad de la red. |
| **Conocimiento de tendencias** | Estar al día con las últimas tecnologías y amenazas. |
| **Comprensión de objetivos de negocio** | Alinear la infraestructura de red con las metas de la organización. |
| **Resolución de problemas** | Diagnosticar y arreglar fallos rápidamente para minimizar el tiempo de inactividad. |

---

#### 🔗 Conexión con lo aprendido en el módulo

| Tema del módulo | Relación con el administrador de red |
|-----------------|--------------------------------------|
| **Dispositivos de seguridad de red** | Son las herramientas que el administrador configura y mantiene. |
| **Firewalls, routers, switches, proxies** | Forman parte del día a día del administrador. |
| **Ataques a la red** | El administrador debe conocerlos para defender la red. |
| **Hardening** | Aplicar medidas de endurecimiento en todos los dispositivos. |
| **Control de acceso** | Gestionar quién entra a la red es una de sus tareas principales. |
| **Firmware** | Mantener actualizado el firmware de todos los dispositivos. |

---

#### 🎯 Perfil profesional

> Un administrador de red es como el **director de infraestructura** de una ciudad digital:
> - Diseña las calles (topología de red).
> - Instala semáforos (routers y switches).
> - Pone guardias (firewalls).
> - Repara baches (soluciona problemas).
> - Y se asegura de que todo funcione las 24 horas.

---

#### 📊 Comparación con otros roles de TI

| Rol | Foco principal |
|-----|----------------|
| **Administrador de red** | Infraestructura de conectividad. |
| **Administrador de sistemas** | Servidores y sistemas operativos. |
| **Especialista en ciberseguridad** | Protección contra amenazas. |
| **Ingeniero de firmware** | Software de bajo nivel de dispositivos. |

> *"El administrador de red es quien mantiene la autopista digital funcionando. Sin él, los datos no llegan a destino y la organización se queda incomunicada."*

## 🏗️ Lección 3: Arquitectura de seguridad de red

Si alguien quiere construir un banco, pensará detenidamente cómo hacerlo seguro:
- Diseñar la **bóveda** para que los ladrones no puedan entrar fácilmente.
- Diseñar el edificio para que las **salidas sean limitadas** y fáciles de vigilar.
- Asegurarse de que las medidas de seguridad **no interfieran** con el funcionamiento normal del banco.

Cuando alguien diseña una red, tiene **preocupaciones similares**. Una de las formas más efectivas de proteger una red es **diseñarla para la seguridad desde el principio**.

---

### 📋 Lo que vamos a ver en esta lección

| Tema | Descripción |
|------|-------------|
| **Conceptos básicos de arquitectura de sistemas** | Fundamentos del diseño de redes. |
| **Métodos de arquitectura segura** | Técnicas que los arquitectos de sistemas usan para crear redes intrínsecamente más seguras. |
| **Protección desde el diseño** | Cómo anticiparse a filtraciones y ataques desde la fase de planificación. |

---

### 🧠 Idea clave

> *"No es lo mismo agregar seguridad después de construir la red, que diseñarla con seguridad desde el primer plano. La arquitectura segura ahorra problemas, dinero y filtraciones."*

### 🏗️ ¿Qué es la arquitectura de red?

Cuando una organización necesita una red, un **arquitecto de red** la planifica primero. Decide:
- **Qué dispositivos** usar (routers, switches, firewalls, servidores).
- **Cómo se conectarán** entre sí.
- **Cómo el sistema realizará** las funciones necesarias.

---

#### 📋 Definición

La **arquitectura de red** es el **diseño estructural y lógico** de una red. Describe:

| Elemento | ¿Qué define? |
|----------|--------------|
| **Dispositivos de red** | Qué equipos se utilizan (routers, switches, firewalls, proxies, etc.). |
| **Conexiones** | Cómo se conectan los dispositivos entre sí (topología, cableado, inalámbrico). |
| **Reglas de transferencia** | Los protocolos y políticas que rigen cómo se mueven los datos. |

---

#### ⚠️ Impacto de una buena o mala arquitectura

| Una buena arquitectura... | Una mala arquitectura... |
|---------------------------|--------------------------|
| Mejora el rendimiento de toda la organización. | Ralentiza la red y dificulta el trabajo. |
| Facilita la seguridad desde el diseño. | Deja agujeros de seguridad difíciles de cerrar después. |
| Soporta crecimiento futuro. | Se vuelve obsoleta rápidamente. |
| Permite autenticación rápida y eficiente. | Dificulta el reconocimiento y autorización de usuarios. |

---

#### 🔍 Ejemplos de decisiones arquitectónicas

| Decisión | Consecuencia si se elige mal |
|----------|------------------------------|
| **Cables o equipos incorrectos** para la carga esperada del servidor. | La red se vuelve lenta. |
| **Protocolos que no soportan autenticación eficiente**. | Los usuarios tardan en conectarse o quedan expuestos. |
| **Falta de segmentación**. | Un atacante que entra a un dispositivo puede moverse libremente por toda la red. |
| **No considerar el crecimiento de dispositivos**. | La red se satura al agregar nuevos usuarios o dispositivos IoT. |

---

#### 🧠 Analogía

> La arquitectura de red es como el **plano de un edificio**:
> - Define dónde van las paredes (segmentación).
> - Por dónde pasan las cañerías y cables (cableado estructurado).
> - Dónde están las puertas y quién tiene llave (control de acceso).
> - Si el plano está mal hecho, el edificio tendrá problemas para siempre. Si está bien diseñado desde el principio, todo funciona y es seguro.

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Dispositivos de seguridad de red** | Son las piezas que el arquitecto decide dónde colocar. |
| **Hardening** | Una buena arquitectura facilita aplicar hardening. |
| **Superficie de ataque** | La arquitectura define la superficie de ataque de la red. |
| **Segmentación** | Es una decisión arquitectónica clave para la seguridad. |

> *"La arquitectura de red no se trata solo de que internet funcione. Se trata de que funcione rápido, seguro y que pueda crecer sin romperse. Un buen diseño desde el principio ahorra millones en problemas después."*

### 📐 Diseño de red

El **diseño de red** es el proceso de crear una arquitectura de red para una organización y situación específicas. Incluye:

- Análisis de red.
- Selección de hardware.
- Planeación de la implementación.
- Y otros procesos de planificación.

---

#### 🧠 ¿Cuándo empieza y termina?
Identificación de requisitos → Diseño → Implementación
(comerciales y técnicos)


El diseño comienza con la **identificación de requisitos** y continúa hasta justo antes de la implementación física de la red.

---

#### 📊 Complejidad según el tamaño

| Tipo de red | Complejidad del diseño | Ejemplo |
|-------------|------------------------|---------|
| **Hogar u oficina pequeña** | Simple y directo. | Una casa con módem, router y 5 dispositivos. |
| **Gran empresa** | Muy complejo. | Un banco con sucursales, data centers y miles de empleados. |

---

#### 📋 Las dos categorías de requisitos

Antes de diseñar una red, se debe recopilar información hablando con las partes interesadas de la organización. Esta información se divide en dos categorías:

| Categoría | ¿Qué responde? | Ejemplos |
|-----------|----------------|----------|
| **Requisitos empresariales** | ¿Qué necesita el negocio? | Presupuesto, cantidad de usuarios, tipo de aplicaciones, expectativas de crecimiento, normativas a cumplir. |
| **Requisitos técnicos** | ¿Qué necesita la tecnología? | Ancho de banda, velocidad, latencia, protocolos, dispositivos necesarios, compatibilidad, seguridad. |

---

#### 🔍 Ejemplos concretos

**Requisitos empresariales:**
- "Necesitamos que 500 empleados trabajen sin problemas."
- "La red debe cumplir con la normativa PCI-DSS porque procesamos pagos con tarjeta."
- "Planeamos abrir dos sucursales nuevas en los próximos 3 años."

**Requisitos técnicos:**
- "El ancho de banda mínimo debe ser de 1 Gbps."
- "La latencia entre sucursales no debe superar los 10 ms."
- "Debemos usar WPA3 para todas las conexiones inalámbricas."
- "El firewall debe soportar inspección SSL."

---

#### 🧠 Analogía

> Diseñar una red es como construir una autopista:
> - **Requisitos empresariales:** ¿Cuántos autos van a circular? ¿Va a crecer el tráfico? ¿Qué peajes necesitamos?
> - **Requisitos técnicos:** ¿Cuántos carriles? ¿De qué material? ¿Qué señalización? ¿Dónde van los puentes?
> - Si no preguntás ambas cosas, la autopista queda chica, se congestiona o se cae a los pocos años.

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Arquitectura de red** | El diseño es el proceso que crea la arquitectura. |
| **Dispositivos de seguridad** | La selección de hardware es parte del diseño. |
| **Hardening** | Un buen diseño facilita el hardening posterior. |
| **Ataques a la red** | Conocer las amenazas ayuda a diseñar una red más resistente. |

> *"El diseño de red no es solo conectar cables. Es entender qué necesita la organización y planificar una red que lo cumpla de forma segura, eficiente y escalable."*

### 🔌 Dispositivos de infraestructura de red

Los **dispositivos de infraestructura de red** son los componentes que controlan las comunicaciones necesarias para datos, aplicaciones, servicios y multimedia.

**Ejemplos:**
- Enrutadores (routers)
- Firewalls
- Conmutadores (switches)
- Servidores
- Equilibradores de carga (load balancers)
- Sistemas de detección de intrusiones (IDS)
- Sistemas de nombres de dominio (DNS)
- Redes de área de almacenamiento (SAN)

---

#### ⚠️ ¿Por qué son blancos ideales para atacantes?

Estos dispositivos **literalmente conforman la red**. La mayor parte o **todo el tráfico** debe pasar a través de ellos.

| Si un atacante controla... | Puede... |
|----------------------------|----------|
| **El router de puerta de enlace** | Monitorear, modificar y denegar el tráfico hacia y desde la organización. |
| **La infraestructura interna de enrutamiento y conmutación** | Monitorear, modificar y denegar el tráfico hacia y desde hosts clave dentro de la red. |

> *"Quien controla la infraestructura de enrutamiento de una red, controla los datos que fluyen a través de ella."*

---

#### 🛡️ Mejores prácticas para proteger la infraestructura de red

| # | Práctica | ¿En qué consiste? |
|---|----------|-------------------|
| 1 | **Configuraciones seguras** | Proteger los dispositivos con configuraciones endurecidas como requisito básico. Seguir guías, benchmarks y mejores prácticas de fabricantes y organismos. |
| 2 | **Deshabilitar protocolos de administración remota sin cifrar** | No usar Telnet, HTTP o FTP para administrar dispositivos. Usar SSH, HTTPS y SFTP. |
| 3 | **Desactivar servicios innecesarios** | Apagar protocolos de descubrimiento, enrutamiento de origen, HTTP, SNMP y cualquier servicio que no se use. |
| 4 | **Políticas de contraseñas sólidas** | Usar contraseñas fuertes y el cifrado más potente disponible para protegerlas. |
| 5 | **Restringir el acceso físico** | Limitar quién puede tocar físicamente routers y switches. Asegurar el acceso a líneas de consola, auxiliares y terminales virtuales. |
| 6 | **Respaldar configuraciones** | Hacer copias de seguridad de las configuraciones y almacenarlas **sin conexión** (offline). |
| 7 | **Mantener actualizado el SO del dispositivo** | Usar la última versión del sistema operativo del dispositivo de red y aplicar todos los parches. |

---

#### 🧠 Analogía

> Los dispositivos de infraestructura de red son como las **centrales eléctricas y estaciones de bombeo** de una ciudad:
> - Si alguien toma el control de la central eléctrica, apaga la luz de toda la ciudad.
> - Si alguien envenena la estación de bombeo, contamina el agua que llega a todas las casas.
> - Por eso protegerlos no es opcional: son el corazón de la red.

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Hardening del sistema** | Las prácticas de protección son hardening aplicado a dispositivos de red. |
| **Gestión de parches** | Mantener actualizado el SO del dispositivo es gestión de parches. |
| **Contraseñas seguras** | Políticas de contraseñas fuertes y cifrado. |
| **Copia de seguridad** | Respaldar configuraciones offline para recuperación ante desastres. |
| **Firmware** | Muchos dispositivos de red funcionan con firmware que debe actualizarse. |

> *"Proteger cada dispositivo de infraestructura no es un lujo: es la base sobre la que se construye toda la seguridad de la red. Si la base se cae, todo lo demás se derrumba."*


### 🏛️ DMZ (Zona Desmilitarizada)

Una **DMZ** (DeMilitarized Zone, zona desmilitarizada) es una **red separada** que actúa como **amortiguador** entre la red interna de una organización e Internet.

---

#### ¿Qué hace una DMZ?

| Función | Descripción |
|---------|-------------|
| **Protege la LAN interna** | Agrega una capa adicional de seguridad contra tráfico no confiable. |
| **Se conecta a Internet** | Proporciona acceso a algunos recursos externos. |
| **Conexión limitada a la red interna** | Solo tiene una conexión segura y controlada con la red privada. |
Internet ↔ DMZ (servidores públicos) ↔ Firewall ↔ Red interna (datos sensibles)


---

#### 🧠 Analogía

> Una DMZ es como el **hall de entrada de un banco**:
> - El público puede entrar al hall (DMZ) para hacer trámites.
> - Pero la bóveda (red interna) está detrás de una puerta blindada.
> - Aunque alguien cause problemas en el hall, no puede llegar a la bóveda.

---

#### 🎯 ¿Para qué sirve?

| Beneficio | Explicación |
|-----------|-------------|
| **Aísla servidores públicos** | Los servidores que deben ser accesibles desde Internet están en la DMZ, no en la red interna. |
| **Limita el daño** | Si un atacante compromete un servidor en la DMZ, **no puede acceder directamente** a los datos internos. |
| **Dificulta el acceso a datos sensibles** | Hace más difícil que un atacante obtenga acceso a servidores internos desde Internet. |

---

#### 📋 ¿Qué se aloja típicamente en una DMZ?

| Servicio | Ejemplo |
|----------|---------|
| **Servidor web** | El sitio web público de la empresa. |
| **Servidor DNS** | Resolución de nombres de dominio para consultas externas. |
| **Servidor FTP** | Transferencia de archivos con clientes o proveedores. |
| **Servidor de correo** | Recepción de correos desde Internet. |
| **Servidor proxy** | Intermediario para acceso a Internet. |
| **Servidor VoIP** | Comunicaciones de voz sobre IP. |

---

#### 🔍 Ejemplos concretos

**Ejemplo 1: Minorista de comercio electrónico**

| Componente | Ubicación |
|------------|-----------|
| **Servidor web** (tienda online) | DMZ |
| **Base de datos de clientes y tarjetas** | Red interna |
| **Resultado:** Los clientes pueden comprar. Si el servidor web es hackeado, los datos sensibles siguen protegidos en la red interna. |

**Ejemplo 2: Red social o proveedor cloud**

| Componente | Ubicación |
|------------|-----------|
| **Servidores web y API públicas** | DMZ |
| **Base de datos de usuarios, mensajes privados** | Red interna |
| **Resultado:** Millones de usuarios acceden a los servicios. Un ataque a los servidores públicos no compromete los datos privados. |

---

#### 📊 Estructura típica de una DMZ
INTERNET
│
▼
┌────────────────┐
│ Firewall 1 │ (Perimetral)
└────────────────┘
│
▼
┌──────────────────────────────────────┐
│ DMZ │
│ Servidor Web | DNS | FTP | Correo │
└──────────────────────────────────────┘
│
▼
┌────────────────┐
│ Firewall 2 │ (Interno)
└────────────────┘
│
▼
┌────────────────┐
│ RED INTERNA │
│ (Bases de │
│ datos, │
│ archivos, │
│ empleados) │
└────────────────┘


---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firewalls** | La DMZ se implementa usando firewalls que separan las zonas. |
| **Superficie de ataque** | La DMZ reduce la superficie de ataque de la red interna. |
| **Segmentación** | La DMZ es una forma de segmentación de red por seguridad. |
| **Arquitectura de red** | Es una decisión de diseño arquitectónico para mejorar la seguridad. |

> *"La DMZ es el patio de recepción. Todos los visitantes pasan por ahí. La casa (red interna) está detrás de otra puerta. Si un visitante se porta mal, solo llega hasta el patio."*

### 🔄 NAT: Traducción de direcciones de red

**NAT (Network Address Translation)** es un proceso mediante el cual una **única dirección IP pública** puede representar a **varias computadoras** dentro de una red privada.

Un dispositivo de red (generalmente un router o firewall NAT) asigna esta IP pública a un grupo de computadoras internas.

---

#### 🧠 Analogía

> NAT es como la **recepcionista de una gran empresa**:
> - El mundo exterior llama al **número público** de la empresa (la IP pública).
> - La recepcionista atiende y decide a quién pasar la llamada.
> - La persona que llama **nunca obtiene tu número interno** (tu IP privada).
> - La recepcionista tiene instrucciones sobre qué llamadas bloquear, cuáles transferir y a dónde.

---

#### ⚙️ ¿Cómo funciona?
Internet → Solicitud llega a IP pública + puerto → NAT traduce → IP privada interna
│
Nadie afuera ve las IPs internas.


| Paso | Acción |
|------|--------|
| **1** | Llega una solicitud a la dirección IP pública del router. |
| **2** | NAT consulta sus reglas y traduce la IP pública a la IP privada del dispositivo correcto. |
| **3** | Reenvía el paquete sin revelar las direcciones IP privadas internas. |
| **4** | La respuesta viaja de vuelta, NAT traduce de nuevo a la IP pública. |

---

#### 🛡️ ¿Qué beneficios tiene?

| Beneficio | Explicación |
|-----------|-------------|
| **Oculta la red interna** | Muestra solo **una IP** al mundo exterior. Nadie sabe cuántos dispositivos hay adentro ni sus direcciones reales. |
| **Conservación de direcciones IP** | Muchas computadoras comparten una sola IP pública. Importante porque las IPs públicas son limitadas. |
| **Seguridad adicional** | Actúa como una barrera natural. Los dispositivos internos no son directamente accesibles desde Internet. |
| **Ideal para acceso remoto** | Los arquitectos de red la implementan en entornos donde empleados se conectan desde afuera. |

---

#### 📊 Comparación: Sin NAT vs Con NAT

| | Sin NAT | Con NAT |
|--|---------|---------|
| **Cada dispositivo tiene...** | Su propia IP pública (cara y poco segura). | Una IP privada. Comparten una sola IP pública. |
| **Visibilidad desde Internet** | Cada dispositivo es visible. | Solo se ve el router/firewall. |
| **Seguridad** | Baja. Cada dispositivo es un blanco. | Alta. La red interna está oculta. |

---

#### 🏠 Ejemplo real: Tu casa
Tu router de casa tiene UNA sola IP pública (ej: 181.45.23.10)

Dentro de tu casa:

Tu celular: 192.168.1.5 (IP privada)

Tu laptop: 192.168.1.7 (IP privada)

Tu Smart TV: 192.168.1.10 (IP privada)

Cuando cualquiera de estos navega por internet:
Todos salen con la misma IP pública: 181.45.23.10

Nadie en Internet sabe cuántos dispositivos tenés ni sus IPs reales.


---

#### 🔗 NAT y DMZ: ¿Se llevan bien?

| NAT | DMZ |
|-----|-----|
| Oculta la red interna mostrando una sola IP. | Expone algunos servidores (los de la DMZ) a Internet. |
| Protege los dispositivos privados. | Protege la red interna poniendo los servidores públicos en otra zona. |

> **NAT y DMZ trabajan juntos.** NAT oculta la red interna. La DMZ expone solo lo necesario (servidor web, por ejemplo) mientras el resto sigue oculto.

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Firewall** | Muchos firewalls incluyen función NAT. |
| **Router** | El router de casa hace NAT automáticamente. |
| **DMZ** | NAT oculta la red interna, la DMZ expone solo ciertos servidores. |
| **IP Pública vs Privada** | NAT es el traductor entre ambas. |

> *"NAT es el guardián silencioso. No lo ves, no lo tocás, pero todos los días evita que Internet sepa cuántos dispositivos tenés, cómo se llaman y dónde están."*

### 🍯 Honeypot (Tarros de miel)

Un **honeypot** es un sistema diseñado para **atraer a los atacantes** y distraerlos de los recursos reales de una organización. Se ve, se siente y actúa como una red llena de recursos valiosos, pero en realidad es una **trampa** con herramientas de monitoreo.

---

#### 🎯 ¿Para qué sirve?

| Objetivo | Descripción |
|----------|-------------|
| **Distraer atacantes** | Los aleja de los sistemas reales y los mantiene ocupados en un entorno falso. |
| **Estudiar su comportamiento** | Permite ver cómo se mueve un atacante dentro de un sistema sin poner en peligro la red real. |
| **Detectar vulnerabilidades** | Los datos recolectados muestran qué técnicas usan los atacantes y qué debilidades explotan. |
| **Mejorar la seguridad** | Con esa información, la organización puede corregir vulnerabilidades y entrenar a sus empleados. |

---

#### 🧠 Analogía

> Un honeypot es como un **auto señuelo** que la policía deja estacionado en una zona de robos:
> - Parece un auto real, pero tiene cámaras y GPS ocultos.
> - Los ladrones lo roban sin saber que están siendo filmados.
> - La policía estudia cómo lo robaron y atrapa a los responsables.
> - El auto real de los vecinos está a salvo.

---

#### 📊 Honeypot vs Honeynet

| Término | ¿Qué es? |
|---------|----------|
| **Honeypot** | Un **único** sistema señuelo (un servidor, una página de login falsa). |
| **Honeynet** | Un **conjunto** de honeypots conectados entre sí, simulando una red entera. |

---

#### ⚙️ ¿Qué contiene un honeypot?

| Elemento | Función |
|----------|---------|
| **Recursos falsos** | Archivos, bases de datos, páginas de login que parecen reales. |
| **Herramientas de monitoreo** | Rastrean cada movimiento del atacante: qué hace, qué busca, cómo se mueve. |
| **Aislamiento** | Está separado de la red real. Si el atacante entra, no puede saltar a los sistemas verdaderos. |
| **Registro detallado** | Guarda logs de toda la actividad para análisis posterior. |

---

#### 🔍 Ejemplo real: Un banco

| Situación | ¿Qué hace el banco? |
|-----------|---------------------|
| Es blanco frecuente de ataques por manejar información sensible. | Crea un honeypot que imita una **página de inicio de sesión falsa** de su sitio web. |
| Los atacantes intentan entrar al honeypot creyendo que es real. | El sistema registra sus tácticas, sus herramientas y su comportamiento. |
| El banco analiza los datos recolectados. | Descubre nuevas técnicas de ataque. |
| Con esa información... | Corrige vulnerabilidades en el sistema real. Entrena a sus empleados para detectar esos ataques. |

---

#### 🧠 Valor para los profesionales de seguridad

| Sin honeypot | Con honeypot |
|--------------|--------------|
| Dedican todo el día a **bloquear** ataques. | Pueden **estudiar** a los atacantes tranquilamente. |
| No saben cómo se mueve un atacante hasta que ocurre un incidente real. | Ven en cámara lenta cómo se mueve, qué busca y qué herramientas usa. |
| Reaccionan después del daño. | Anticipan y mejoran defensas antes de que ataquen el sistema real. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **DMZ** | Un honeypot puede colocarse en la DMZ para atraer ataques lejos de la red interna. |
| **Firewall** | El firewall puede redirigir tráfico sospechoso al honeypot en lugar de a los servidores reales. |
| **Monitoreo y logs** | El honeypot es una herramienta de monitoreo avanzado. |
| **Ataques a la red** | Permite estudiar en vivo los ataques que vimos en la lección 1. |

> *"Un honeypot es como poner un cartel que dice 'tesoro aquí', pero en realidad es una celda con cámaras. El ladrón entra contento. Vos lo filmás, estudiás y cerrás la puerta."*

### ✂️ Segmentación de red

La **segmentación de red** es dividir una red grande en **segmentos más pequeños** (subredes), generalmente usando switches y routers. Esto permite controlar mejor el tráfico y el acceso.

---

#### 🎯 ¿Para qué sirve?

| Beneficio | Descripción |
|-----------|-------------|
| **Mejorar la seguridad** | Si un atacante entra a un segmento, no puede moverse libremente a los demás. |
| **Mejorar el monitoreo** | Es más fácil vigilar segmentos pequeños que una red gigante. |
| **Mejorar el rendimiento** | El tráfico se mantiene dentro de cada segmento, reduciendo la congestión. |
| **Controlar el tráfico** | Se pueden aplicar reglas específicas para cada subred. |

---

#### 🧠 Analogía

> Una red sin segmentar es como un **edificio sin puertas internas**: cualquiera que entra al hall puede caminar por todas las oficinas.
>
> Una red segmentada es como un edificio con **puertas con llave en cada piso**: aunque alguien entre al hall, no puede pasar a los pisos sin autorización.
Red sin segmentar: Red segmentada:
┌─────────────────────┐ ┌──────┐ ┌──────┐ ┌──────┐
│ │ │ RRHH │ │ TI │ │ Ventas│
│ TODOS LOS │ │solo │ │solo │ │solo │
│ DISPOSITIVOS │ │RRHH │ │TI │ │Ventas │
│ JUNTOS │ └──────┘ └──────┘ └──────┘
│ │ ↑ ↑ ↑
└─────────────────────┘ Segmentos separados


---

#### 📋 Las 4 mejores prácticas de segmentación

| # | Práctica | ¿En qué consiste? | Ejemplo |
|---|----------|-------------------|---------|
| 1 | **Principio de privilegio mínimo** | Asignar a los usuarios solo los permisos que necesitan para su trabajo. Nada más. | Un empleado de marketing no puede acceder a la base de datos financiera. |
| 2 | **Aislar hosts de la red** | Separar redes según la criticidad de las operaciones. Si dos redes no necesitan comunicarse, **no deben poder hacerlo**. | Los servidores de pagos están en una subred separada de las PCs de los empleados. |
| 3 | **Perfeccionar el proceso de autorización** | Solo usuarios autenticados y autorizados acceden a la red. Crear y actualizar políticas de autorización constantemente. | Si un usuario cambia de rol, sus permisos de acceso a subredes se actualizan de inmediato. |
| 4 | **Lista de permitidos de tráfico** | Permitir solo lo que está autorizado, en lugar de bloquear lo malo. Es más seguro y mejora la productividad. | Solo las IPs del segmento de TI pueden acceder a los servidores de administración. Todo lo demás está bloqueado por defecto. |

---

#### 🔍 ¿Por qué la práctica 4 es más segura?

| Enfoque | ¿Cómo funciona? | ¿Por qué es mejor? |
|---------|-----------------|--------------------|
| **Lista negra (blocklist)** | Bloquear lo que se sabe que es malo. | Si aparece algo nuevo y malo, pasa hasta que lo agreguen a la lista. |
| **Lista blanca (allowlist)** | Permitir **solo** lo que está autorizado. Todo lo demás está bloqueado. | Lo nuevo y desconocido queda bloqueado automáticamente. |

---

#### 🛡️ ¿Qué pasa si un atacante entra?

| Sin segmentación | Con segmentación |
|------------------|------------------|
| Se mueve lateralmente por toda la red. | Queda atrapado en un segmento pequeño. |
| Puede llegar a servidores críticos. | No puede saltar a otros segmentos sin autorización. |
| El daño es total. | El daño está **contenido**. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **DMZ** | La DMZ es una forma de segmentación: separa lo público de lo privado. |
| **VLANs** | Son la tecnología que permite segmentar lógicamente una red. |
| **Firewall** | Se usan para controlar el tráfico entre segmentos. |
| **Principio de privilegio mínimo** | Visto también en hardening y control de acceso. |

> *"Segmentar una red es ponerle puertas a los pasillos. Si alguien entra por la ventana de la cocina, no puede abrir la puerta blindada de la tesorería."*

### 🌐 Extranet e Intranet

Otra forma de dividir estratégicamente una red es crear **redes separadas** según quién las usa.

---

#### 📋 Definiciones

| Red | ¿Para quién es? | ¿Quién accede? |
|-----|-----------------|----------------|
| **Intranet** | Usuarios **internos** de la organización. | Solo empleados. |
| **Extranet** | Usuarios **externos** autorizados (socios, proveedores, clientes). | Empleados + externos autorizados. |
| **Internet** | Todo el mundo. | Cualquiera. |

---

#### 🧠 Diferencia clave
┌─────────────┐ ┌─────────────┐ ┌─────────────┐
│ INTRANET │ │ EXTRANET │ │ INTERNET │
│ │ │ │ │ │
│ Solo emplea-│ │ Empleados + │ │ Todo el │
│ dos. │ │ socios, │ │ mundo. │
│ │ │ proveedores,│ │ │
│ Documentos │ │ clientes. │ │ Acceso │
│ internos, │ │ │ │ público. │
│ RRHH, │ │ Pedidos, │ │ │
│ finanzas. │ │ seguimiento │ │ │
│ │ │ de envíos, │ │ │
│ │ │ inventario. │ │ │
└─────────────┘ └─────────────┘ └─────────────┘


---

#### ⚠️ Regla importante

> **La extranet NO se conecta directamente a la intranet.** Aunque ambas pueden conectarse a Internet, están separadas. Esto evita que un usuario externo que accede a la extranet pueda llegar a la red interna.

---

#### 🎯 ¿Para qué sirve una extranet?

| Función | Ejemplo |
|---------|---------|
| **Pedidos en línea** | Un proveedor entra a la extranet para ver los pedidos que le hizo la empresa. |
| **Seguimiento de envíos** | Un cliente consulta el estado de su pedido sin acceder a los sistemas internos. |
| **Gestión de inventario** | Un socio comercial revisa el stock disponible para planificar sus compras. |
| **Comunicación con proveedores** | Compartir documentos, facturas y especificaciones técnicas de forma segura. |

---

#### 🛡️ ¿Por qué es más seguro?

| Situación | Con extranet separada | Sin extranet (todo junto) |
|-----------|----------------------|---------------------------|
| Un proveedor necesita ver pedidos. | Entra a la extranet. No ve nada interno. | Tendría que entrar a la intranet y podría ver datos sensibles. |
| Un cliente quiere seguir su envío. | Usa la extranet. No toca la red corporativa. | No habría forma segura de darle acceso. |
| Un atacante compromete la cuenta de un proveedor. | Solo ve la extranet. La intranet sigue protegida. | Podría acceder a toda la red interna. |

---

#### 📶 WiFi para invitados: un ejemplo cotidiano

El **WiFi para invitados** es una forma de extranet aplicada al hogar o la oficina:

| WiFi principal | WiFi de invitados |
|----------------|-------------------|
| Conecta tus dispositivos personales. | Conecta a visitas, amigos, clientes. |
| Tiene acceso a la red interna (impresora, archivos compartidos). | **Solo** da acceso a Internet. No ve nada interno. |
| Contraseña privada. | Contraseña separada (o abierta con portal cautivo). |

**Beneficio de seguridad:**
- Si un amigo trae un celular con malware, ese malware no puede saltar a tus dispositivos porque está en una red separada.
- Protege dispositivos más vulnerables (como cámaras IoT, impresoras) de visitantes no confiables.

---

#### 📊 Comparación final

| Característica | Intranet | Extranet | Internet |
|----------------|----------|----------|----------|
| **Usuarios** | Solo empleados | Empleados + externos autorizados | Todo el mundo |
| **Acceso a datos internos** | ✅ Sí | ❌ No (solo lo que se comparte) | ❌ No |
| **Ejemplos** | Documentos de RRHH, finanzas, comunicados | Pedidos, seguimiento de envíos, portal de proveedores | Google, YouTube, redes sociales |
| **Seguridad** | Alta (cerrada) | Media (controlada) | Baja (abierta) |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Segmentación de red** | Extranet e intranet son formas de segmentación por tipo de usuario. |
| **DMZ** | La extranet a veces se implementa en una DMZ para aislarla de la intranet. |
| **Firewall** | Separan la intranet de la extranet y de Internet. |
| **Control de acceso** | Define quién puede entrar a cada red. |

> *"La intranet es la oficina. La extranet es la sala de reuniones con los de afuera. Internet es la calle. Todas están conectadas, pero con puertas diferentes."*

### 🏠 Segmentación, Extranet e Intranet explicadas con un ejemplo hogareño

---

#### 📶 Lo que hice en casa: Red de invitados

Configuré mi router para tener **dos redes separadas**:
Mi router
│
├── Red principal (la mía)
│ └── Mis dispositivos: PC, celular, Smart TV
│
└── Red de invitados
└── Dispositivos de visitas: el celular de un amigo


---

#### 📊 ¿Qué es cada cosa?

| Lo que tengo en casa | Término técnico | ¿Qué significa? |
|----------------------|-----------------|-----------------|
| **Red principal** (la mía) | **Intranet** | Red privada para usuarios internos (yo y mi familia). Nadie de afuera puede entrar. |
| **Red de invitados** | **Extranet** | Red separada para usuarios externos (visitas). Solo da acceso a Internet, no a mis dispositivos. |

---

#### ✂️ ¿Y si quisiera dividir mi red principal?

Eso sería **segmentación de red (subredes)**:
Mi router
│
└── Red principal (Intranet)
├── Subred 1: 192.168.1.x → Mis dispositivos personales
├── Subred 2: 192.168.2.x → Dispositivos IoT (cámaras, luces)
└── Subred 3: 192.168.3.x → Dispositivos del trabajo


Y después pondría **reglas**:

| Regla | ¿Qué hace? |
|-------|------------|
| Subred 1 puede hablar con Subred 2. | ✅ Mi celular controla las luces. |
| Subred 2 NO puede iniciar conexión a Subred 1. | ❌ Una cámara hackeada no puede llegar a mi PC. |
| Subred 3 está completamente aislada. | ❌ Nadie puede entrar a mis dispositivos de trabajo. |

---

#### 🆚 Diferencia clave entre los tres conceptos

| Concepto | ¿Qué es? | Ejemplo en casa |
|----------|----------|-----------------|
| **Intranet** | Red privada para los de adentro. | Mi red principal. |
| **Extranet** | Red separada para usuarios externos. | Mi red de invitados. |
| **Subred (segmentación)** | Dividir una misma red en partes con reglas. | Separar IoT, PCs y trabajo dentro de mi red principal. |

---

#### 🧠 Analogía
Mi casa:
├── Intranet: Las habitaciones de la familia.
│ └── Subredes: Puertas con llave entre habitaciones (si quisiera ponerlas).
│
└── Extranet: El quincho para visitas.
└── Usan el baño del quincho, no el de mi habitación.

Todo usa la misma conexión de agua y luz (el mismo router/proveedor).
Pero los espacios están separados.


---

#### ✅ ¿Es seguro lo que tengo ahora?

| Lo que logré con la red de invitados | ¿Es seguro? |
|--------------------------------------|:---:|
| Las visitas usan Internet sin ver mis dispositivos. | ✅ Sí |
| Mis dispositivos están protegidos de las visitas. | ✅ Sí |
| No necesito más equipos ni otra línea de internet. | ✅ Sí |
| Las visitas no pueden acceder a mis archivos ni a mi red. | ✅ Sí |

---

#### 🎯 Conclusión

| ¿Necesito subredes? | ❌ No, para uso hogareño no hace falta. |
|----------------------|------------------------------------------|
| ¿Necesito otra línea de internet? | ❌ No. |
| ¿Lo que tengo es suficiente? | ✅ Sí, es más de lo que la mayoría tiene. |
| ¿Es seguro? | ✅ Sí. Separé lo interno de lo externo. |
### 🧱 Air Gap (Brecha de aire)

Un **air gap** es la forma más estricta de división de red. Consiste en **aislar completamente** un dispositivo o una red privada de otros dispositivos y redes, incluida la Internet pública.

---

#### ¿Qué significa "air gap"?

Literalmente, **"brecha de aire"** . Significa que **no hay ninguna conexión física ni inalámbrica** entre el sistema protegido y el mundo exterior.

> *"Con la red de invitados ya hice más del 90% de lo que la mayoría de la gente no hace. Funciona, es seguro y no necesito complicarme más."*

Red normal: Red con air gap:
┌──────────┐ ┌──────────┐ ┌──────────────────┐
│ Red A │←──→│ Internet │ │ Red aislada │
└──────────┘ └──────────┘ │ │
│ SIN conexión a │
│ Internet ni a │
│ otras redes. │
│ │
│ Solo se comunica│
│ internamente. │
└──────────────────┘


---

#### 🔒 ¿Qué nivel de seguridad proporciona?

| Característica | Descripción |
|----------------|-------------|
| **Aislamiento total** | Electromagnético, electrónico y físico. No hay WiFi, Bluetooth, ni cable de red al exterior. |
| **Sin tráfico entrante ni saliente** | No pueden entrar ni salir datos. |
| **Solo comunicación interna** | Los dispositivos solo hablan con otros dentro de la misma red aislada. |
| **Protección absoluta** | Ningún ataque o violación en otras redes puede llegar más allá del air gap. |

---

#### 🎯 ¿Quién lo usa?

| Sector | ¿Qué protege? |
|--------|---------------|
| **Militar** | Sistemas de armas, comunicaciones clasificadas, inteligencia. |
| **Servicios públicos** | Centrales nucleares, redes eléctricas, plantas de agua. |
| **Médico** | Equipos de diagnóstico, historiales clínicos críticos, sistemas de soporte vital. |
| **Financiero** | Sistemas de liquidación de pagos entre bancos. |
| **Gobierno** | Sistemas electorales, bases de datos clasificadas. |

---

#### 🧠 Analogía

> Un air gap es como una **habitación sellada sin puertas ni ventanas**:
> - No entra ni sale nada.
> - Solo las personas que ya están adentro pueden comunicarse entre sí.
> - Para meter algo nuevo (un archivo, una actualización), hay que usar un medio físico (USB, CD) y pasarlo manualmente, con estrictos controles de seguridad.

---

#### ⚠️ ¿Tiene desventajas?

| Desventaja | Explicación |
|------------|-------------|
| **Inconveniente** | Pasar datos requiere medios físicos (USB, discos externos). Es lento y manual. |
| **Caro** | Equipos dedicados, sin conexión a Internet. |
| **No es práctico para todo** | Solo se usa para sistemas críticos. Nadie pondría su PC de escritorio en un air gap. |
| **Riesgo de insider** | Si alguien con acceso físico mete un USB infectado, puede romper el air gap. |

---

#### 📊 Comparación con otras estrategias

| Estrategia | Nivel de seguridad | ¿Conectado a Internet? |
|------------|:---:|:---:|
| **Firewall + NAT** | Medio | ✅ Sí |
| **DMZ** | Alto | ✅ Parcialmente (solo la DMZ) |
| **Extranet** | Alto | ✅ Limitado |
| **Air Gap** | Máximo | ❌ No |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Segmentación de red** | Es la forma más extrema de segmentación. |
| **DMZ** | La DMZ expone algo. El air gap no expone nada. |
| **Firewall** | Si el air gap es una isla desierta, el firewall es una muralla con puertas controladas. |

> *"El air gap es la máxima seguridad posible: un sistema tan aislado que ni Internet ni ninguna otra red puede tocarlo. Pero es tan restrictivo que solo se usa para lo más crítico."*

## 🧪 Actividad: Diseño de una red segura

### 📋 Escenario

**Yummy In My Tummy**, una compañía de alimentos, quiere **alojar su propio servidor web** donde los clientes puedan buscar recetas que usen sus ingredientes. Las recetas deben almacenarse en una **base de datos** accesible para los clientes.

El equipo de ciberseguridad propuso **cuatro opciones** de arquitectura de red. Nuestra tarea es analizar cada una y determinar si tiene el nivel de seguridad necesario.

---

### 🔍 Preguntas para evaluar cada diseño

| # | Pregunta |
|---|----------|
| 1 | ¿Están presentes todos los **dispositivos necesarios** para una red segura? |
| 2 | ¿El diagrama de arquitectura **separa los sistemas internos y externos**? |
| 3 | ¿Existen **protecciones suficientes** para el modelo de negocio (servidor web + base de datos)? |

---

### 🧠 Lo que debemos buscar

| Elemento de seguridad | ¿Por qué es necesario? |
|-----------------------|------------------------|
| **Firewall** | Para filtrar el tráfico entre Internet y los servidores. |
| **DMZ** | Para alojar el servidor web público separado de la base de datos interna. |
| **Separación servidor web / base de datos** | El servidor web (recetas) debe estar en la DMZ. La base de datos debe estar en la red interna. |
| **NAT** | Para ocultar las IPs internas. |
| **Segmentación** | Para que un ataque al servidor web no comprometa la base de datos. |

---

### 🎯 Objetivo de la actividad

> Aplicar el pensamiento analítico para identificar qué arquitectura de red protege correctamente la información de los clientes, separando lo público (recetas en el servidor web) de lo interno (base de datos).

## 🧪 Actividad: Diseño de una red segura

### 📋 Escenario

**Yummy In My Tummy**, una compañía de alimentos, quiere **alojar su propio servidor web** donde los clientes puedan buscar recetas que usen sus ingredientes. Las recetas deben almacenarse en una **base de datos** accesible para los clientes.

El equipo de ciberseguridad propuso **cuatro opciones** de arquitectura de red. Nuestra tarea es analizar cada una y determinar cuál tiene el nivel de seguridad necesario.

---

### 🔍 Criterios de evaluación

| # | Pregunta | ¿Por qué es importante? |
|---|----------|--------------------------|
| 1 | ¿Están presentes todos los **dispositivos necesarios** para una red segura? | Sin firewall, cualquiera entra. Sin DMZ, todo está expuesto. |
| 2 | ¿El diagrama de arquitectura **separa los sistemas internos y externos**? | El servidor web es público. La base de datos debe ser privada. |
| 3 | ¿Existen **protecciones suficientes** para el modelo de negocio (servidor web + base de datos)? | Si hackean el servidor web, la base de datos debe seguir protegida. |

---

### 📊 Análisis de las 4 arquitecturas

#### ✅ Red 1 (CORRECTA)
Internet → Firewall → Servidor web (DMZ)
→ Base de datos (Red interna)


| Elemento | ¿Está presente? | ¿Está bien ubicado? |
|----------|:---:|:---:|
| **Firewall** | ✅ Sí | ✅ Al perímetro |
| **DMZ** | ✅ Sí | ✅ Contiene el servidor web |
| **Servidor web** | ✅ Sí | ✅ En la DMZ |
| **Base de datos** | ✅ Sí | ✅ En la red interna |
| **Separación público/privado** | ✅ Sí | ✅ Correcta |

**Veredicto:** ✅ **Arquitectura correcta.** Si hackean el servidor web, la base de datos sigue protegida en la red interna.

---

#### ❌ Red 2
Internet → Firewall → Servidor web + Base de datos (todo junto)


| Elemento | ¿Está presente? | ¿Está bien ubicado? |
|----------|:---:|:---:|
| **Firewall** | ✅ Sí | ✅ Al perímetro |
| **DMZ** | ❌ No | ❌ No hay separación |
| **Servidor web** | ✅ Sí | ❌ Está junto con la BD |
| **Base de datos** | ✅ Sí | ❌ Está expuesta junto con el servidor web |
| **Separación público/privado** | ❌ No | ❌ Todo está en el mismo lugar |

**Veredicto:** ❌ **Insegura.** Si hackean el servidor web, acceden directamente a la base de datos.

---

#### ❌ Red 3
Internet → Firewall → Servidor web + Base de datos (todo junto)


| Elemento | ¿Está presente? | ¿Está bien ubicado? |
|----------|:---:|:---:|
| **Firewall** | ✅ Sí | ✅ Al perímetro |
| **DMZ** | ❌ No | ❌ No hay separación |
| **Servidor web** | ✅ Sí | ❌ Está junto con la BD |
| **Base de datos** | ✅ Sí | ❌ Está expuesta junto con el servidor web |
| **Separación público/privado** | ❌ No | ❌ Sin DMZ |

**Veredicto:** ❌ **Insegura.** Mismo problema que la Red 2. Sin DMZ ni separación.

---

#### ❌ Red 4
Internet → Firewall → DMZ (Servidor web + Base de datos juntos en la DMZ)


| Elemento | ¿Está presente? | ¿Está bien ubicado? |
|----------|:---:|:---:|
| **Firewall** | ✅ Sí | ✅ Al perímetro |
| **DMZ** | ✅ Sí | ✅ Existe |
| **Servidor web** | ✅ Sí | ✅ En la DMZ |
| **Base de datos** | ✅ Sí | ❌ Está en la DMZ (debería estar en red interna) |
| **Separación público/privado** | ❌ No | ❌ La BD está en zona pública |

**Veredicto:** ❌ **Insegura.** La DMZ está mal implementada. La base de datos no debe estar en la DMZ porque queda expuesta.

---

### 📊 Comparación final

| Red | Firewall | DMZ | BD en red interna | Separación público/privado | ¿Es segura? |
|-----|:---:|:---:|:---:|:---:|:---:|
| **Red 1** | ✅ | ✅ | ✅ | ✅ | ✅ **Sí** |
| **Red 2** | ✅ | ❌ | ❌ | ❌ | ❌ No |
| **Red 3** | ✅ | ❌ | ❌ | ❌ | ❌ No |
| **Red 4** | ✅ | ✅ | ❌ (está en DMZ) | ❌ | ❌ No |

---

### 🎯 Conclusión

**La Red 1 es la arquitectura correcta** porque cumple con todos los requisitos de seguridad:

| # | Requisito cumplido | ¿Cómo lo cumple? |
|---|---------------------|-------------------|
| 1 | Firewall protegiendo el perímetro. | ✅ Hay un firewall entre Internet y la DMZ. |
| 2 | Servidor web en DMZ, accesible desde Internet. | ✅ Los clientes pueden buscar recetas. |
| 3 | Base de datos en red interna, separada del servidor público. | ✅ Si hackean el servidor web, no pueden acceder a la BD. |
| 4 | Separación entre sistemas internos y externos. | ✅ DMZ + Red interna correctamente divididos. |

---

### 🧠 Lección aprendida

> *"Una arquitectura segura no solo necesita los dispositivos correctos (firewall, DMZ). Necesita que cada componente esté en la zona correcta. Un firewall sin DMZ no protege. Una DMZ con la base de datos adentro tampoco. La seguridad está en la correcta separación."*

### 💼 Gestión de carrera: Certificación CompTIA Network+

La certificación **Network+ de CompTIA** es una certificación de la industria diseñada para profesionales de TI que desean demostrar su conocimiento sobre **redes informáticas** y su capacidad para **implementarlas y mantenerlas**.

---

#### 📋 ¿Qué cubre la certificación?

| Área | Contenido |
|------|-----------|
| **Instalación** | Cómo montar y poner en marcha una red. |
| **Configuración** | Ajustes de routers, switches, firewalls y otros dispositivos. |
| **Seguridad** | Protección de la red contra amenazas y ataques. |
| **Resolución de problemas** | Diagnosticar y solucionar fallos de conectividad y rendimiento. |
| **Hardware de red** | Conocimiento de routers, switches, cables, puntos de acceso. |
| **Software y sistemas operativos** | Sistemas operativos de red y herramientas de gestión. |
| **Protocolos de red** | TCP/IP, DNS, DHCP, HTTP/HTTPS, FTP, etc. |

---

#### 🎯 ¿Para quién es útil?

| Puesto de trabajo | ¿Cómo ayuda la certificación? |
|-------------------|-------------------------------|
| **Especialista en soporte técnico** | Demuestra que sabés diagnosticar y resolver problemas de red. |
| **Administrador de redes** | Valida que podés gestionar y mantener una red corporativa. |
| **Analista de redes** | Acredita tu capacidad para analizar tráfico y rendimiento. |
| **Ingeniero de sistemas** | Muestra que entendés la infraestructura de red a nivel profesional. |

---

#### 🧠 ¿Por qué es valiosa?

| Beneficio | Explicación |
|-----------|-------------|
| **Reconocimiento internacional** | CompTIA es una de las organizaciones de certificación más respetadas del mundo. |
| **Válida conocimientos prácticos** | No es solo teoría. Cubre escenarios reales de instalación, configuración y resolución de problemas. |
| **Abre puertas laborales** | Muchas empresas la piden como requisito para puestos de TI y redes. |
| **Base para otras certificaciones** | Sirve como fundamento para certificaciones más avanzadas (CCNA, Security+). |

---

#### 🔗 Conexión con lo aprendido en el módulo

| Tema del módulo | Relación con Network+ |
|-----------------|----------------------|
| **Dispositivos de seguridad de red** | Firewalls, routers, switches, proxies son parte del examen. |
| **Arquitectura de red** | DMZ, segmentación, NAT, extranet. |
| **Ataques a la red** | Conocer amenazas ayuda a prevenirlas y solucionarlas. |
| **Seguridad inalámbrica** | WPA2, WPA3, Evil Twin, Rogue AP. |
| **Hardening de red** | Configuraciones seguras, deshabilitar servicios innecesarios. |

> *"La certificación Network+ es como un pasaporte al mundo de las redes profesionales. Demuestra que no solo entendés cómo funciona una red, sino que podés armarla, protegerla y arreglarla."*

## 🔐 Lección 4: Control de acceso a la red

Cualquier sistema puede ser seguro solo si se puede **confiar en las personas que lo usan**. Si una red permite el acceso a los **usuarios equivocados** o permite a los usuarios acceder a los **activos y recursos equivocados**, el riesgo de ataque y daño crece enormemente.

---

### 📋 Lo que vamos a ver en esta lección

| Tema | Descripción |
|------|-------------|
| **Control de acceso a la red** | Cómo los administradores configuran los sistemas para garantizar que las personas correctas accedan a los recursos que necesitan. |
| **Principios de acceso** | Privilegio mínimo, necesidad de saber, separación de funciones. |
| **Métodos de control** | NAC, 802.1X, MAC filtering, autenticación basada en roles. |

---

### 🧠 Idea clave

> *"La seguridad de la red no solo depende de firewalls y DMZs. Depende de quién puede entrar, a qué puede acceder y qué permisos tiene. Si le das las llaves del banco a cualquiera, no importa qué tan buena sea la bóveda."*

### 🔐 ¿Qué es el control de acceso a la red (NAC)?

El **control de acceso a la red (NAC - Network Access Control)** es un proceso para **controlar y gestionar** el acceso a una red mediante la **autenticación de usuarios y dispositivos** antes de permitirles conectarse.

---

#### 🎯 ¿Qué busca garantizar?

| Objetivo | Descripción |
|----------|-------------|
| **Solo usuarios de confianza** | Que únicamente las personas autorizadas puedan acceder a la red. |
| **Dispositivos verificados** | Que los dispositivos que se conectan cumplan con las políticas de seguridad. |
| **Posibles atacantes fuera** | Bloquear el acceso a cualquier entidad no autorizada o sospechosa. |

---

#### 🧠 Analogía

> El NAC es como el **guardia de seguridad en la entrada de un edificio corporativo**:
> - Te pide tu identificación (autenticación del usuario).
> - Verifica que estés en la lista de invitados (autorización).
> - Revisa que no traigas objetos peligrosos (cumplimiento del dispositivo).
> - Si todo está en orden, te deja pasar. Si no, te bloquea.

---

#### 🛡️ ¿Por qué es vital para la seguridad de la red?

| Beneficio | ¿Cómo ayuda? |
|-----------|--------------|
| **Evita acceso no autorizado** | Bloquea a usuarios y dispositivos que no cumplen con las políticas. |
| **Reduce el riesgo de filtraciones** | Si solo entran los autorizados, hay menos posibilidades de robo de datos. |
| **Reduce el riesgo de ciberataques** | Impide que atacantes se conecten libremente a la red. |
| **Garantiza el cumplimiento normativo** | Ayuda a cumplir con políticas de seguridad y regulaciones (GDPR, PCI-DSS, HIPAA). |

---

#### ⚙️ ¿Cómo funciona el NAC?
Dispositivo solicita conexión
│
▼
¿Usuario autenticado?
│ │
Sí No
│ │
▼ ▼
¿Dispositivo cumple Bloqueado
políticas de
seguridad?
│ │
Sí No
│ │
▼ ▼
Acceso Acceso limitado
completo o en cuarentena


---

#### 📊 Elementos que verifica el NAC

| Elemento | ¿Qué revisa? | Ejemplo |
|----------|--------------|---------|
| **Usuario** | Credenciales, roles, permisos. | ¿Es un empleado activo? ¿Tiene permiso para esta red? |
| **Dispositivo** | Sistema operativo, antivirus, parches, firewall. | ¿Tiene Windows actualizado? ¿Tiene antivirus activo? |
| **Ubicación** | Desde dónde se conecta. | ¿Está en la oficina o en una cafetería? |
| **Horario** | Cuándo intenta conectarse. | ¿Es horario laboral o las 3 AM? |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Autenticación segura** | El NAC usa autenticación como primer paso. |
| **Firewall** | El NAC controla quién entra. El firewall controla qué tráfico pasa. |
| **Segmentación** | Una vez dentro, el NAC puede asignar al usuario a una VLAN específica según su rol. |
| **Hardening** | Verificar que los dispositivos cumplan políticas es parte del hardening. |

> *"El NAC es la primera línea de defensa humana. Antes de que un paquete llegue al firewall, el NAC ya decidió si ese usuario y ese dispositivo pueden siquiera estar en la red."*

Usuario intenta conectarse
│
▼
AUTENTICACIÓN
¿Quién sos?
│ │
OK Falló
│ │
▼ ▼
AUTORIZACIÓN Acceso denegado
¿Tenés permiso?
│ │
OK Falló
│ │
▼ ▼
Acceso Acceso denegado
concedido


---

#### 🛡️ ¿Por qué son importantes para la seguridad?

| Beneficio | Explicación |
|-----------|-------------|
| **Protege información confidencial** | Solo usuarios verificados y autorizados acceden a datos sensibles. |
| **Garantiza confianza en la red** | Todos los que están en la red fueron validados. |
| **Previene accesos no autorizados** | Sin autenticación, cualquiera entra. Sin autorización, cualquiera hace lo que quiere. |
| **Trazabilidad** | Se sabe quién accedió y qué hizo. |

---

#### 📊 Ejemplo concreto

| Situación | Autenticación | Autorización |
|-----------|---------------|--------------|
| Un empleado de marketing quiere acceder a la carpeta de finanzas. | ✅ Pasó (es un empleado válido). | ❌ Denegado (no tiene permiso para esa carpeta). |
| Un hacker intenta entrar con una contraseña robada. | ⚠️ Pasó (contraseña correcta). Pero si hay MFA... | ❌ Sin segundo factor, no pasa. |
| Un administrador de TI necesita acceder al servidor. | ✅ Pasó. | ✅ Autorizado (tiene rol de administrador). |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **NAC (Control de acceso a la red)** | NAC usa autenticación y autorización como base. |
| **MFA (Autenticación multifactor)** | Es un método de autenticación más fuerte. |
| **RBAC (Control de acceso basado en roles)** | Es un método de autorización. |
| **Firewall** | Controla tráfico. La autenticación/autorización controla usuarios. |

> *"La autenticación dice quién sos. La autorización dice qué podés hacer. Sin la primera, cualquiera entra. Sin la segunda, cualquiera toca todo. Las dos juntas son el candado y la llave de la red."*

Filtrado MAC (básico):
"Tu MAC es AA:BB:CC:DD:EE:FF? Ok, pasá."
→ Un atacante copia esa MAC y también pasa.


--- --------------------------------------------------------------------------------------------
NAC (avanzado):
"¿Quién sos? (usuario/contraseña + MFA)
 ¿Tu antivirus está activo? ¿Tu Windows está actualizado?
 ¿Tu firewall está prendido? ¿Es horario laboral?
 ¿Estás en la oficina o en un país sospechoso?"
→ Si algo falla, no pasás o vas a cuarentena.

Dispositivo → Agente NAC (revisa estado) → Switch/Router (punto de aplicación) → Servidor NAC (decide)
                                                                                        │
                                                                              ¿Cumple las políticas?
                                                                                 │          │
                                                                                Sí         No
                                                                                 │          │
                                                                             Accede    Bloqueado o
                                                                             a la red  en cuarentena


### 📋 IAAA: Identificación, Autenticación, Autorización y Contabilidad

Los administradores usan el marco **IAAA** para controlar el acceso a los recursos y proteger la información confidencial. La **confidencialidad, integridad y disponibilidad** de los datos dependen de estos cuatro pilares.

---

#### 🔍 Los cuatro pilares de IAAA

| Pilar | ¿Qué hace? | Pregunta que responde | Ejemplo |
|-------|------------|----------------------|---------|
| **Identificación** | Declara quién sos. | "¿Quién decís ser?" | Ingresar tu nombre de usuario o escanear tu tarjeta de acceso. |
| **Autenticación** | Verifica que realmente sos quien decís ser. | "¿Podés probarlo?" | Ingresar tu contraseña, usar tu huella dactilar o mostrar tu DNI. |
| **Autorización** | Determina qué podés hacer una vez adentro. | "¿Tenés permiso para esto?" | Un empleado puede ver su carpeta, pero no la de finanzas. |
| **Contabilidad** | Registra todo lo que hiciste. | "¿Qué hiciste mientras estuviste adentro?" | Logs de acceso, archivos abiertos, cambios realizados, hora de entrada y salida. |

---

#### 🧠 Analogía

> Es como entrar a un **hotel de alta seguridad**:
> - **Identificación:** Decís "Soy Juan Pérez, tengo una reserva".
> - **Autenticación:** Mostrás tu DNI o pasaporte para probarlo.
> - **Autorización:** El recepcionista te da la llave de tu habitación, pero no la de la suite presidencial.
> - **Contabilidad:** El hotel registra a qué hora entraste, qué servicios usaste y cuándo saliste.

---

#### ⚙️ Flujo completo de IAAA
IDENTIFICACIÓN
"Soy juan.perez"
│
▼

AUTENTICACIÓN
"Esta es mi contraseña y mi huella"
│
▼

AUTORIZACIÓN
"Podés acceder a tu carpeta y al email"
│
▼

CONTABILIDAD
"Registrado: juan.perez accedió a las 09:15, abrió 3 archivos, salió a las 17:00"


---

#### 📊 ¿Por qué son importantes los cuatro?

| Si falta... | ¿Qué pasa? |
|-------------|------------|
| **Identificación** | No sabés quién entró. Cualquiera puede decir cualquier cosa. |
| **Autenticación** | Alguien puede hacerse pasar por otro sin prueba. |
| **Autorización** | Todos pueden acceder a todo. Un pasante puede ver datos confidenciales. |
| **Contabilidad** | No hay registro de lo que pasó. Si hay un incidente, no sabés quién lo hizo ni cuándo. |

---

#### 🔗 Conexión con la tríada CIA

| Pilar de IAAA | ¿A qué pilar de CIA ayuda? |
|---------------|----------------------------|
| **Identificación + Autenticación** | **Confidencialidad:** Solo los autorizados entran. |
| **Autorización** | **Integridad:** Solo los autorizados modifican datos. |
| **Contabilidad** | **Disponibilidad + Integridad:** Si algo falla, sabés quién lo hizo y podés recuperarlo. |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **Autenticación segura** | Es el segundo pilar de IAAA. |
| **NAC** | NAC implementa IAAA a nivel de red. |
| **RBAC** | Es un método de autorización. |
| **Registro de eventos (logging)** | Es la base de la contabilidad. |
| **Cifrado** | Protege la confidencialidad de los datos una vez que el usuario fue autenticado. |

> *"IAAA es la fórmula completa del control de acceso. No alcanza con saber quién entra. Hay que verificarlo, limitarlo y registrar todo lo que hace. Si falta uno de los cuatro, la seguridad tiene un agujero."*

### 🔐 Métodos de autenticación adicionales

Los nombres de usuario y contraseñas brindan autenticación básica, pero la mayoría de los sistemas modernos usan **métodos adicionales** para un mayor nivel de protección.

---

#### 📋 Métodos de autenticación

| Método | ¿En qué consiste? | Ejemplo |
|--------|-------------------|---------|
| **Autenticación basada en el conocimiento (KBA)** | Verifica la identidad haciendo preguntas basadas en información que **solo el usuario conoce**. | Pregunta secreta ("¿Cuál es el nombre de tu primera mascota?") o un PIN. |
| **Inicio de sesión único (SSO)** | Permite acceder a **varios recursos** con un solo conjunto de credenciales. Autentica una vez y crea un token que sirve como llave para todo lo demás. | Iniciar sesión en Google y acceder a Gmail, Drive y YouTube sin volver a loguearte. |
| **Autenticación multifactor (MFA)** | Requiere **dos o más factores** para demostrar la identidad. | Contraseña + código enviado al celular + huella dactilar. |
| **Autenticación adaptativa** | Cambia los requisitos de autenticación **en tiempo real** según el riesgo detectado. | Si entrás desde tu PC habitual, solo contraseña. Si entrás desde otro país, te pide MFA adicional. |

---

#### 🔍 Detalle de cada método

##### 1. KBA (Knowledge-Based Authentication)

| Característica | Descripción |
|----------------|-------------|
| **¿Qué usa?** | Información que solo el usuario conoce. |
| **Ejemplos** | Preguntas secretas, PIN, fecha de nacimiento. |
| **¿Es segura?** | ⚠️ Media. Las respuestas pueden adivinarse o encontrarse en redes sociales. |

---

##### 2. SSO (Single Sign-On)

| Característica | Descripción |
|----------------|-------------|
| **¿Qué hace?** | Autenticás una vez y accedés a múltiples servicios. |
| **¿Cómo funciona?** | El portal de SSO autentica al usuario y crea un **certificado o token** que sirve como llave. |
| **Ventaja** | Comodidad. No hay que recordar 50 contraseñas. |
| **Desventaja** | Si alguien roba esa única contraseña, accede a todo. Por eso debe combinarse con MFA. |

---

##### 3. MFA (Autenticación Multifactor)

| Factor | Tipo | Ejemplos |
|--------|------|----------|
| **Algo que sabés** | Conocimiento | Contraseña, PIN. |
| **Algo que tenés** | Posesión | Código en el celular, token físico, tarjeta inteligente. |
| **Algo que sos** | Biometría | Huella dactilar, reconocimiento facial, voz. |

> *"MFA es la regla de oro hoy. Si alguien roba tu contraseña, todavía necesita tu celular o tu huella para entrar."*

---

##### 4. Autenticación adaptativa (basada en riesgos)

| Característica | Descripción |
|----------------|-------------|
| **¿Qué evalúa?** | Contexto: ubicación, dispositivo, hora, comportamiento habitual. |
| **¿Cómo responde?** | Si detecta algo inusual, **aumenta los requisitos de autenticación** automáticamente. |

| Comportamiento normal | Comportamiento sospechoso |
|-----------------------|---------------------------|
| Inicio de sesión desde casa (8 AM). | Inicio de sesión desde otro país (3 AM). |
| Solo pide contraseña. | Pide contraseña + código SMS + huella. |

---

#### 📊 Comparación de métodos

| Método | Nivel de seguridad | Comodidad |
|--------|:---:|:---:|
| **Solo contraseña** | Bajo | Alta |
| **KBA (preguntas secretas)** | Medio-Bajo | Media |
| **SSO** | Medio (sin MFA) / Alto (con MFA) | Muy alta |
| **MFA** | Alto | Media |
| **Autenticación adaptativa** | Muy alto | Alta (se adapta automáticamente) |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **IAAA** | Estos métodos refuerzan el pilar de **Autenticación**. |
| **NAC** | NAC usa varios de estos métodos para verificar usuarios y dispositivos. |
| **Protección del SO** | MFA y SSO son parte de las mejores prácticas de seguridad. |

> *"La contraseña sola ya no alcanza. MFA, SSO y autenticación adaptativa son el estándar actual. Cada capa adicional hace más difícil que un atacante se haga pasar por vos."*

### 🔐 Esquemas de control de acceso

Gestionar el acceso para un puñado de usuarios es fácil. Pero cuando hay **cientos o miles de usuarios y dispositivos**, se vuelve muy complejo. Los **esquemas de control de acceso** ayudan a proporcionar **coherencia** en el control de acceso a los recursos de red.

---

#### 🎯 ¿Qué garantizan?

| Objetivo | Descripción |
|----------|-------------|
| **Solo usuarios autorizados** | Accedan a los recursos que necesitan. |
| **Evitar acceso no autorizado** | Bloquear a quienes no tienen permiso. |
| **Prevenir robo y daños** | Proteger los datos y sistemas. |

---

#### 📋 Los 4 esquemas principales

| Esquema | ¿Quién decide el acceso? | ¿En qué se basa? | Analogía |
|---------|--------------------------|------------------|----------|
| **ABAC** (Atributos) | El sistema, basado en políticas. | Atributos del usuario, recurso y entorno. | Un portero que decide según tu cargo, hora y ubicación. |
| **RBAC** (Roles) | El administrador, según roles. | Rol del usuario en la organización. | Un empleado de limpieza tiene llave de los armarios, no de la caja fuerte. |
| **DAC** (Discrecional) | El **propietario** de cada recurso. | Lo que el dueño decide compartir. | Vos decidís quién entra a tu casa y quién no. |
| **MAC** (Obligatorio) | Una **autoridad central**. | Reglas y políticas predeterminadas. Niveles jerárquicos. | El gobierno decide quién accede a documentos secretos. |

---

#### 1. ABAC: Control de acceso basado en atributos

| Característica | Descripción |
|----------------|-------------|
| **¿En qué se basa?** | Atributos del **usuario** (cargo, ubicación), del **recurso** (tipo de archivo) y del **entorno** (hora del día). |
| **¿Cómo decide?** | El sistema otorga o deniega acceso según cómo estos atributos coinciden con las políticas predefinidas. |
| **Ejemplo** | Un médico puede ver historiales clínicos solo dentro del hospital y en horario laboral. |
Usuario: Médico
Recurso: Historia clínica
Entorno: Hospital, 10 AM
Política: Permitir

Usuario: Médico
Recurso: Historia clínica
Entorno: Cafetería, 11 PM
Política: Denegar


---

#### 2. RBAC: Control de acceso basado en roles

| Característica | Descripción |
|----------------|-------------|
| **¿En qué se basa?** | Roles asignados a usuarios o grupos según su función empresarial. |
| **¿Cómo decide?** | Los administradores asignan roles. El sistema concede derechos de acceso basados en esos roles. |
| **Ejemplo** | El rol "Ventas" accede a clientes. El rol "RRHH" accede a empleados. Ninguno accede a lo del otro. |

┌──────────────┐ ┌──────────────┐ ┌──────────────┐
│ Ventas │ │ RRHH │ │ TI │
│ │ │ │ │ │
│ • Clientes │ │ • Empleados │ │ • Servidores │
│ • Pedidos │ │ • Sueldos │ │ • Red │
│ • Facturas │ │ • Legajos │ │ • Todo │
└──────────────┘ └──────────────┘ └──────────────┘


---

#### 3. DAC: Control de acceso discrecional

| Característica | Descripción |
|----------------|-------------|
| **¿En qué se basa?** | Cada recurso tiene un **propietario** que decide quién accede. |
| **¿Cómo decide?** | El propietario concede o deniega acceso a otros usuarios **según su criterio**. |
| **Ejemplo** | Creás un documento en Google Drive y decidís compartirlo con Juan, pero no con María. |

Vos (propietario del archivo)
│
├── Juan: ✅ Puede ver y editar
└── María: ❌ No puede ver


| Ventaja | Desventaja |
|---------|------------|
| Muy flexible. | Depende del criterio de cada usuario. Puede generar caos en organizaciones grandes. |

---

#### 4. MAC: Control de acceso obligatorio

| Característica | Descripción |
|----------------|-------------|
| **¿En qué se basa?** | Una **autoridad central** (administrador de seguridad) define reglas estrictas. |
| **¿Cómo decide?** | Los usuarios **no tienen control** sobre sus propios derechos. Todo está predeterminado por niveles jerárquicos. |
| **Ejemplo** | Documentos clasificados como "Secreto", "Confidencial", "Público". Solo quien tiene el nivel autorizado accede. |

Niveles de clasificación:
┌──────────────────────────────────┐
│ Alto Secreto │ Solo directores│
│ Secreto │ Solo gerentes │
│ Confidencial │ Empleados │
│ Público │ Todos │
└──────────────────────────────────┘
Un empleado con nivel "Confidencial" NO puede ver documentos "Secretos".

| Ventaja | Desventaja |
|---------|------------|
| Muy seguro. Centralizado. | Poco flexible. Se usa en entornos militares y gubernamentales. |

---

#### 📊 Comparación de esquemas

| Esquema | Flexibilidad | Seguridad | ¿Quién controla? | Uso típico |
|---------|:---:|:---:|------------------|------------|
| **ABAC** | Alta | Alta | El sistema (políticas) | Empresas modernas |
| **RBAC** | Media | Alta | Administrador | Empresas de todos los tamaños |
| **DAC** | Muy alta | Media | Usuario propietario | PCs personales, pequeñas oficinas |
| **MAC** | Baja | Muy alta | Autoridad central | Ejército, gobierno, inteligencia |

---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **IAAA** | Estos esquemas implementan el pilar de **Autorización**. |
| **NAC** | NAC puede usar RBAC o ABAC para decidir quién entra a la red. |
| **Principio de privilegio mínimo** | RBAC y MAC lo aplican naturalmente. |
| **Segmentación** | Los esquemas de acceso determinan quién puede cruzar los segmentos. |

> *"Elegir el esquema correcto depende del tamaño y la sensibilidad de la organización. RBAC es el más común en empresas. MAC es para secretos de estado. DAC es para el día a día personal. ABAC es el futuro, combinando todo."*

### 📁 Permisos del sistema de archivos

Mientras que muchos métodos de control de acceso evalúan a los **usuarios y sus atributos**, los permisos del sistema de archivos están relacionados con los **propios recursos** (archivos y carpetas).

---

#### 🎯 ¿Qué determinan?

Los controles del sistema de archivos determinan qué cuentas, usuarios, grupos o servicios pueden realizar **acciones** como:

| Acción | ¿Qué permite? |
|--------|---------------|
| **Leer** | Ver el contenido de un archivo o carpeta. |
| **Escribir** | Modificar o crear archivos. |
| **Ejecutar** | Ejecutar programas o scripts. |

---

#### 🪟 Ejemplo: Sistema de archivos de Microsoft Windows

En Windows, los permisos se pueden aplicar a:
- **Archivos individuales** o **carpetas completas**.
- **Heredados** de las carpetas principales (una subcarpeta hereda los permisos de la carpeta que la contiene).
- Otorgados o denegados a **usuarios individuales** o **grupos**.
- **Cambiados o eliminados** en cualquier momento por el propietario o administrador.

---

#### 📋 Permisos de Windows

| Permiso | ¿Qué permite? |
|---------|---------------|
| **Control total** | Todo: leer, escribir, modificar, eliminar y cambiar permisos. |
| **Modificar** | Leer, escribir, modificar y eliminar archivos. |
| **Leer y ejecutar** | Ver archivos y ejecutar programas. |
| **Leer** | Solo ver archivos y carpetas. |
| **Escribir** | Crear y modificar archivos. |
| **Permisos especiales** | Permisos avanzados y personalizados (tomar propiedad, cambiar auditoría, etc.). |

---

#### 🧠 Analogía

> Los permisos de archivos son como las **llaves de una oficina**:
> - **Control total:** Tenés la llave maestra. Entrás a todo y podés prestar llaves.
> - **Modificar:** Entrás, trabajás y ordenás, pero no podés cambiar la cerradura.
> - **Leer y ejecutar:** Podés leer documentos y usar programas, pero no modificar nada.
> - **Leer:** Solo podés mirar. No tocás nada.
> - **Escribir:** Podés dejar documentos nuevos, pero no ver los que ya están (raro, pero existe).

---

#### ⚙️ ¿Cómo funciona la herencia?
Carpeta principal: "Proyectos" (permisos: Leer para todos)
│
├── Subcarpeta A (hereda "Leer para todos")
├── Subcarpeta B (hereda "Leer para todos")
└── Subcarpeta C (hereda "Leer para todos")


Si cambiás los permisos en "Proyectos", todas las subcarpetas heredan el cambio automáticamente. A menos que rompas la herencia manualmente.

---

#### 📊 Denegar vs Permitir

| Regla | ¿Qué pasa? |
|-------|------------|
| **Permitir** | El usuario o grupo puede realizar la acción. |
| **Denegar** | El usuario o grupo NO puede, **incluso si otro permiso lo permite**. Denegar **siempre gana**. |
Ejemplo:
Usuario "Juan" tiene:

Grupo "Ventas": Permitir Leer

Permiso individual: Denegar Leer

Resultado: Juan NO puede leer. Denegar tiene prioridad.


---

#### 🔗 Conexión con lo aprendido

| Tema anterior | Relación |
|---------------|----------|
| **IAAA** | Los permisos de archivos son parte del pilar de **Autorización**. |
| **DAC (Control discrecional)** | El propietario decide los permisos de cada archivo. |
| **MAC (Control obligatorio)** | Los permisos los define una autoridad central, no el usuario. |
| **RBAC (Roles)** | Los permisos se asignan por rol, no por usuario individual. |
| **Hardening** | Configurar permisos correctos es una práctica de hardening. |

> *"Los permisos de archivos son la última barrera. Aunque alguien entre a la red y acceda al servidor, los permisos correctos pueden evitar que lea o modifique datos sensibles."*

### 💼 Gestión de carrera: Analista de Gestión de Identidad y Acceso (IAM)

Los **analistas de IAM (Identity and Access Management)** gestionan y protegen el acceso de los usuarios a los recursos de la compañía: sistemas informáticos, redes y aplicaciones.

**Deber principal:** Garantizar que **solo los usuarios autorizados** puedan acceder a información confidencial.

---

#### 🤝 ¿Con quién trabajan?

| Equipo | Colaboración |
|--------|--------------|
| **TI** | Implementación técnica de controles de acceso. |
| **Seguridad** | Monitoreo de amenazas y respuesta a incidentes. |
| **Cumplimiento** | Asegurar que se cumplan normativas y políticas. |

---

#### 📋 Tareas típicas de un analista IAM

| Área | Tareas |
|------|--------|
| **Gestión de cuentas de usuario** | Crear, modificar y desactivar cuentas de empleados, contratistas y socios. |
| **Control de acceso** | Asignar y revocar permisos según el rol de cada usuario siguiendo el principio de mínimo privilegio. |
| **Políticas de contraseñas** | Implementar y hacer cumplir políticas de contraseñas seguras, caducidad y complejidad. |
| **Autenticación multifactor (MFA)** | Configurar y gestionar sistemas de MFA. |
| **Single Sign-On (SSO)** | Administrar portales de inicio de sesión único para acceso a múltiples aplicaciones. |
| **Revisión de accesos (Access Reviews)** | Auditorías periódicas de quién tiene acceso a qué. Detectar permisos innecesarios o cuentas huérfanas. |
| **Gestión de roles (RBAC)** | Definir roles y asignar permisos según funciones laborales. |
| **Monitoreo y detección** | Supervisar intentos de acceso sospechosos y alertar sobre anomalías. |
| **Cumplimiento normativo** | Asegurar que los accesos cumplan con regulaciones (GDPR, HIPAA, PCI-DSS, SOX). |
| **Automatización** | Implementar herramientas para automatizar altas, bajas y cambios de usuarios. |
| **Documentación** | Mantener registros de políticas, procedimientos y cambios realizados. |
| **Respuesta a incidentes** | Bloquear accesos comprometidos y colaborar en investigaciones de seguridad. |
| **Gestión de identidades privilegiadas (PIM/PAM)** | Administrar cuentas con altos privilegios como administradores y superusuarios. |
| **Onboarding/Offboarding** | Asegurar que los nuevos empleados tengan acceso el primer día y que los que se van lo pierdan de inmediato. |

---

#### 🧠 Perfil profesional

| Habilidad | ¿Por qué es necesaria? |
|-----------|------------------------|
| **Atención al detalle** | Un permiso mal asignado puede causar una filtración. |
| **Conocimiento de normativas** | GDPR, HIPAA, PCI-DSS requieren controles IAM estrictos. |
| **Pensamiento analítico** | Detectar patrones sospechosos de acceso. |
| **Trabajo en equipo** | Colaboración constante con TI, seguridad y RRHH. |
| **Conocimiento técnico** | Active Directory, Azure AD, Okta, SailPoint, CyberArk. |

---

#### 🔗 Conexión con lo aprendido en el módulo

| Tema del módulo | Relación con el analista IAM |
|-----------------|------------------------------|
| **IAAA** | Es la base de su trabajo diario. |
| **RBAC, ABAC, MAC, DAC** | Son los esquemas que implementa y gestiona. |
| **MFA y SSO** | Son herramientas que configura y administra. |
| **NAC** | Control de acceso a la red, parte de sus responsabilidades. |
| **Principio de privilegio mínimo** | Es la regla de oro que aplica a cada usuario. |
| **Contabilidad (logging)** | Monitorea y audita accesos. |

---

#### 🌐 ¿Dónde buscar más información?

| Fuente | Términos de búsqueda sugeridos |
|--------|-------------------------------|
| **Google** | "tareas para la administración de identidad y acceso" |
| **Indeed / LinkedIn / Glassdoor** | "analista de administración de identidad y acceso", "analista de IAM", "Identity and Access Management analyst" |
| **Portales de certificación** | CompTIA Security+, CISSP, CIAM |

> *"El analista IAM es el guardián de las llaves digitales. Decide quién entra, quién no, y se asegura de que nadie tenga más acceso del que necesita. Si hay una filtración, es su responsabilidad haberlo evitado."*

## 📚 Módulo 4: Seguridad de redes - Puntos para recordar

---

### 🔑 Conceptos clave

#### Amenazas a la red
1. **Ataques a aplicaciones y servicios** (los más comunes):
   - **Ataque de aplicación:** explota una vulnerabilidad en una aplicación o software.
   - **Ataque de servicio:** busca apagar una computadora o red para que no esté disponible.

2. **Ataques inalámbricos:** explotan características específicas de las redes inalámbricas.

---

#### Dispositivos de seguridad
3. Los **dispositivos de seguridad de red** son hardware que ayudan a detener ataques.

4. Dispositivos más importantes:
   - Firewalls
   - Enrutadores (Routers)
   - Conmutadores (Switches)
   - Equilibradores de carga (Load Balancers)
   - Módulos de seguridad de hardware (HSM)

---

#### Arquitectura de red
5. La **arquitectura de red** puede facilitar la seguridad si se implementan las mejores prácticas desde el diseño.

6. Estructuras que promueven la seguridad:
   - **DMZ:** separa servidores públicos de la red interna.
   - **NAT:** oculta direcciones IP internas.
   - **Honeypots:** sistemas señuelo para estudiar atacantes.
   - **Segmentación de red:** divide la red en partes más pequeñas.
   - **Extranet:** red para usuarios externos autorizados.
   - **Air Gap:** aislamiento total sin conexión al exterior.

---

#### Control de acceso
7. El **control de acceso a la red (NAC)** permite que solo usuarios de confianza y autorizados accedan a la red.

8. Las cuatro partes esenciales del control de acceso (**IAAA**):
   - **Identificación:** quién decís ser.
   - **Autenticación:** verificarlo.
   - **Autorización:** qué podés hacer.
   - **Contabilidad:** registrar todo.

9. **Esquemas de control de acceso:**
   - **ABAC:** basado en atributos.
   - **RBAC:** basado en roles.
   - **DAC:** control discrecional (el propietario decide).
   - **MAC:** control obligatorio (autoridad central).

---

### 💡 Grandes ideas y habilidades practicadas

| Habilidad | Actividad realizada |
|-----------|---------------------|
| **Pensamiento analítico, comunicación escrita** | Enumerar medidas de seguridad de red. Explicar cómo la autenticación y autorización mantienen la confidencialidad. |
| **Pensamiento analítico** | Clasificar ataques a aplicaciones y servicios. Clasificar ataques inalámbricos. Diseñar una red segura. |
| **Pensamiento crítico** | Describir protocolos de cifrado. Identificar beneficios de dispositivos de seguridad. |
| **Mentalidad de crecimiento, comunicación escrita** | Enumerar habilidades técnicas para gestionar redes. Explorar certificación CompTIA Network+. |
| **Investigación, comunicación escrita** | Resumir tareas típicas de un analista IAM. |
| **Pensamiento creativo** | Diferenciar entre controles de acceso a la red. |

---

### 🎯 Objetivos de aprendizaje cumplidos

| # | Objetivo | ¿Dónde lo aplicaste? |
|---|----------|----------------------|
| 1 | ✅ **Clasificar tipos de ataques a aplicaciones y servicios** | Lección 1: DoS/DDoS, MITM, desbordamiento de búfer, día cero, suplantación. |
| 2 | ✅ **Clasificar tipos de ataques inalámbricos** | Lección 1: Gemelo malvado, punto de acceso no autorizado, jamming, bluesnarfing. |
| 3 | ✅ **Identificar beneficios de dispositivos de seguridad** | Lección 2: Firewalls, routers, switches, proxies, load balancers, HSM. |
| 4 | ✅ **Diseñar una red segura** | Lección 3: Actividad Yummy In My Tummy, arquitectura con DMZ, NAT, honeypot, segmentación. |
| 5 | ✅ **Diferenciar entre controles de acceso a la red** | Lección 4: IAAA, NAC, RBAC, ABAC, DAC, MAC, permisos de archivos. |

---

### 🗺️ Mapa del módulo 4
Módulo 4: Seguridad de redes
│
├── ⚠️ Lección 1: Amenazas a la seguridad de la red
│ ├── Ataques a aplicaciones y servicios (DoS, DDoS, MITM, Buffer Overflow, Zero-day, Spoofing)
│ └── Ataques inalámbricos (Evil Twin, Rogue AP, Jamming, Bluesnarfing)
│
├── 🛡️ Lección 2: Dispositivos de seguridad de red
│ ├── Firewalls (filtrado simple, origen/destino, stateful, aplicación)
│ ├── Routers (configuración segura, cifrado WEP/WPA/WPA2/WPA3)
│ ├── Switches (segmentación, port security)
│ ├── Proxies (intermediario, filtrado, caché)
│ ├── Load Balancers (distribución de tráfico)
│ └── HSM (protección de claves criptográficas)
│
├── 🏗️ Lección 3: Arquitectura de seguridad de red
│ ├── Diseño de red (requisitos empresariales y técnicos)
│ ├── Infraestructura de red (protección de dispositivos)
│ ├── DMZ (zona desmilitarizada)
│ ├── NAT (traducción de direcciones)
│ ├── Honeypot (señuelo para atacantes)
│ ├── Segmentación de red (subredes)
│ ├── Extranet / Intranet
│ ├── Air Gap (aislamiento total)
│ └── Actividad: Diseñar una red segura (Yummy In My Tummy)
│
├── 🔐 Lección 4: Control de acceso a la red
│ ├── NAC (Network Access Control)
│ ├── IAAA (Identificación, Autenticación, Autorización, Contabilidad)
│ ├── Métodos de autenticación (KBA, SSO, MFA, Adaptativa)
│ ├── Esquemas de control de acceso (ABAC, RBAC, DAC, MAC)
│ └── Permisos del sistema de archivos
│
└── 💼 Gestión de carrera
├── Administrador de red
├── Certificación CompTIA Network+
└── Analista de gestión de identidad y acceso (IAM)


---

### 🏆 Logros del módulo

> Completaste el módulo 4 del curso de ciberseguridad de IBM SkillsBuild. Aprendiste sobre amenazas a la red, dispositivos de seguridad, arquitectura segura y control de acceso. Diseñaste una red segura, clasificaste ataques y exploraste carreras profesionales. ¡Excelente trabajo!

---

### 📖 Recursos adicionales del módulo

| Tema | Recurso |
|------|---------|
| **Certificación CompTIA Network+** | [CompTIA Network+](https://www.comptia.org/certifications/network) |
| **Analista IAM** | Buscar en Indeed/LinkedIn: "analista de administración de identidad y acceso" |
| **Seguridad de routers** | Documentación de fabricantes (Cisco, Netgear, TP-Link) |
| **Arquitectura de red** | Guías de mejores prácticas de NIST, ISO 27001 |

## 📖 Explora más recursos

Para profundizar en los conceptos tratados en este módulo, consultá estos recursos:

### 🔗 Recursos adicionales

| Tema | Recurso | Descripción |
|------|---------|-------------|
| **Seguridad de la red** | [¿Qué es la seguridad de la red?](https://www.ibm.com/mx-es/topics/network-security) | Sitio web de IBM con una descripción general de la seguridad de la red y su importancia. |
| **Gestión de roles de seguridad** | [Mejores prácticas en gestión de roles de seguridad](https://www.youtube.com/watch?v=Zg6XkLu0nwE) | Video del ingeniero IBM Security Jeff Crume explicando cómo usar roles para simplificar el acceso seguro. |
| **Ataques de denegación de servicio** | [Explicación de los ataques de denegación de servicio](https://www.youtube.com/watch?v=7T0k0JXEOHw) | Video de Jeff Crume explicando qué es un ataque DoS y cómo funciona. |
| **Equilibradores de carga** | [¿Qué es un equilibrador de carga?](https://www.youtube.com/watch?v=7XmWQqYk5Kw) | Video de Bradley Knapp de IBM Cloud explicando cómo usar load balancers. |
| **Soluciones de protección de red** | [Soluciones de protección y seguridad de red](https://www.ibm.com/mx-es/security/network-security) | Sitio web de IBM con ejemplos de herramientas y recursos adicionales. |

---

### 📚 Fuentes y referencias del módulo

#### Lección 2: Dispositivos de seguridad de red

| Fuente | Enlace |
|--------|--------|
| **Los términos tecnológicos son más antiguos de lo que piensas** | [Merriam-Webster](https://www.merriam-webster.com/words-at-play/tech-terms-older-than-you-think) |

---

### 🎓 Certificaciones mencionadas en el módulo

| Certificación | Descripción | Enlace |
|---------------|-------------|--------|
| **CompTIA Network+** | Certificación de redes informáticas para profesionales de TI. | [CompTIA Network+](https://www.comptia.org/certifications/network) |
| **Red Hat Certified System Administrator (RHCSA)** | Certificación de administración de sistemas Linux de Red Hat. | [Red Hat RHCSA](https://www.redhat.com/en/services/certification/rhcsa) |

---

### 🛠️ Herramientas y tecnologías vistas en el módulo

| Herramienta / Tecnología | ¿Para qué se usa? |
|--------------------------|-------------------|
| **Firewall (Cortafuegos)** | Filtrar tráfico de red según reglas de seguridad. |
| **Router** | Dirigir tráfico entre redes. |
| **Switch (Conmutador)** | Conectar dispositivos dentro de una misma red. |
| **Proxy** | Intermediario entre usuarios e Internet. Filtrado y caché. |
| **Load Balancer (Equilibrador de carga)** | Distribuir tráfico entre varios servidores. |
| **HSM (Módulo de seguridad de hardware)** | Proteger claves criptográficas en hardware dedicado. |
| **NAT (Network Address Translation)** | Traducir direcciones IP privadas a públicas y viceversa. |
| **NAC (Network Access Control)** | Controlar qué usuarios y dispositivos pueden conectarse a la red. |
| **VPN (Virtual Private Network)** | Conexión segura y cifrada a través de Internet. |
| **WPA2 / WPA3** | Protocolos de cifrado para redes WiFi. |
| **AES** | Estándar de cifrado avanzado. |
| **SSO (Single Sign-On)** | Inicio de sesión único para múltiples aplicaciones. |
| **MFA (Autenticación multifactor)** | Verificación de identidad con dos o más factores. |
| **802.1X** | Protocolo de autenticación para control de acceso a la red. |
| **VLAN** | Red de área local virtual para segmentación lógica. |

---

### 📝 Glosario rápido del módulo 4

| Término | Definición breve |
|---------|------------------|
| **DoS** | Denegación de servicio: saturar un sistema para que no esté disponible. |
| **DDoS** | DoS distribuido: ataque desde múltiples dispositivos (botnet). |
| **MITM** | Ataque de intermediario: interceptar comunicación entre dos partes. |
| **Buffer Overflow** | Desbordamiento de búfer: escribir más datos de los que un búfer puede manejar. |
| **Zero-day** | Vulnerabilidad explotada antes de que el fabricante publique un parche. |
| **Spoofing** | Suplantación de identidad (IP, DNS, MAC). |
| **Evil Twin** | Punto de acceso WiFi falso que imita uno legítimo. |
| **Rogue AP** | Punto de acceso no autorizado conectado a la red. |
| **Jamming** | Interferencia de señales inalámbricas para denegar comunicación. |
| **Bluesnarfing** | Robo de datos a través de Bluetooth. |
| **DMZ** | Zona desmilitarizada: red separada para servidores públicos. |
| **NAT** | Traducción de direcciones de red: oculta IPs internas. |
| **Honeypot** | Sistema señuelo para atraer y estudiar atacantes. |
| **Air Gap** | Aislamiento total: red sin conexión física al exterior. |
| **Extranet** | Red privada abierta a usuarios externos autorizados. |
| **Intranet** | Red privada solo para usuarios internos. |
| **Segmentación** | Dividir una red en partes más pequeñas (subredes). |
| **NAC** | Control de acceso a la red. |
| **IAAA** | Identificación, Autenticación, Autorización, Contabilidad. |
| **RBAC** | Control de acceso basado en roles. |
| **ABAC** | Control de acceso basado en atributos. |
| **DAC** | Control de acceso discrecional (el propietario decide). |
| **MAC** | Control de acceso obligatorio (autoridad central). |
| **MFA** | Autenticación multifactor. |
| **SSO** | Inicio de sesión único. |
| **KBA** | Autenticación basada en conocimiento (preguntas secretas). |
| **WPA3** | Protocolo de cifrado WiFi más seguro actualmente. |
| **HSM** | Módulo de seguridad de hardware para claves criptográficas. |

