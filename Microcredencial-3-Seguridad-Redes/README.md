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

