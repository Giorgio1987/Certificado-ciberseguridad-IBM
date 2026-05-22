## Módulo 7: Computación en la nube y virtualización

### Acerca de este módulo

La **ciberseguridad** no es solo una responsabilidad sino un imperativo empresarial crítico. Con el aumento del uso de la computación en la nube y la virtualización, es más importante que nunca que las organizaciones protejan de forma proactiva sus datos y sistemas de las amenazas en línea. Con la última tecnología, las organizaciones pueden crear un mundo digital más seguro y resiliente donde la confianza sea la base de todo.

### Bienvenida al módulo

En este módulo, aprenderás sobre:

- **Virtualización** y cómo crear, configurar y proteger una **máquina virtual**.
- Cómo la **virtualización de red** transforma una red basada en hardware en una red basada en software.
- Cómo la **computación en la nube** ofrece servicios informáticos a través de Internet.
- La **nube como servicio (CaaS)** , que se refiere a las aplicaciones y recursos de infraestructura que residen en Internet.

### Objetivos de aprendizaje

Luego de completar este módulo, deberías ser capaz de:

- **Crear una máquina virtual**
- **Aplicar el modelo de despliegue en la nube adecuado** según las necesidades de una organización

### Acerca de esta lección: Virtualización de sistemas

¿Sabías que el futuro de la computación está en la nube? Los servicios en la nube prestados a través de Internet ofrecen escalabilidad, flexibilidad, rentabilidad y comodidad. La **virtualización** hace posible la computación en la nube al permitir compartir y asignar recursos informáticos físicos en múltiples máquinas virtuales. Piense en la virtualización como la *multitarea de TI definitiva*.

En esta lecc### Visión general de la computación en la nube

#### ¿Qué es la computación en la nube?

La **computación en la nube** se refiere a la variedad de servicios digitales que se proporcionan a través de Internet en lugar de en el sitio. Proporciona a los usuarios acceso bajo demanda a un grupo compartido de recursos informáticos, como:

- Servidores
- Aplicaciones
- Almacenamiento de datos

Estos recursos se pueden usar rápidamente con poco esfuerzo de gestión o interacción mínima con el proveedor de servicios.

#### Beneficios clave

- **Escalabilidad**: aumentar o disminuir el uso bajo demanda.
- **Eficiencia de costos**: pagar solo por lo que se usa, evitando costos de compra y mantenimiento de hardware/software propio.
- **Trabajo remoto y colaboración**: desde cualquier lugar con conexión a Internet.
- **Análisis de datos**: incluye analytics, business intelligence y otras funciones para innovación más rápida y economías de escala.

#### Proveedores de servicios en la nube (CSP)

Un CSP es una empresa que ofrece servicios de computación en la nube a través de Internet. Los principales modelos de servicio son:

- **IaaS (Infraestructura como Servicio)** : alquiler de recursos de hardware virtualizados (servidores, almacenamiento, componentes de red).
- **PaaS (Plataforma como Servicio)** : entornos proporcionados por la nube para que los desarrolladores creen, desplieguen y gestionen aplicaciones.
- **SaaS (Software como Servicio)** : aplicaciones listas para usar a través de Internet (ej. correo electrónico, gestión de documentos).

#### Relación con la virtualización

La **virtualización** es la tecnología que permite ejecutar varios sistemas operativos en una sola máquina física, creando entornos aislados (máquinas virtuales). Cada máquina virtual tiene su propio:

- Sistema operativo
- Memoria
- Almacenamiento
- Aplicaciones
- Interfaces de red

**Ventajas de la virtualización:**
- Mayor utilización de recursos
- Flexibilidad
- Escalabilidad
- Ahorro de costos (reduce la necesidad de hardware adicional)

> La computación en la nube es una parte crucial de la infraestructura de datos moderna y, gracias a sus múltiples beneficios, seguirá siéndolo durante mucho tiempo.ión, aprenderás:

- Cómo la **virtualización** mejora el uso de recursos y el ahorro de costos.
- A **crear**, **configurar** y **proteger** una máquina virtual.

### Beneficios de la virtualización

> ¿Sabías que la primera máquina virtual fue creada en la década de 1960 por IBM para computadoras mainframe? La virtualización ha recorrido un largo camino desde entonces, y hoy en día es una tecnología clave utilizada en la computación en la nube y los centros de datos.

**¿Qué es la virtualización?**  
Es un proceso mediante el cual una sola máquina física puede ejecutar múltiples sistemas operativos. En lugar de tener una máquina para cada sistema operativo, el software de virtualización crea **máquinas virtuales (VM)** que actúan como computadoras separadas, con sus propios sistemas operativos, aplicaciones y software.

#### Beneficios clave

**1. Operación**  
El software de virtualización actúa como una capa entre el hardware y el sistema operativo. Permite que una sola máquina física (*host*) ejecute varias VM simultáneamente, cada una con su propio sistema operativo invitado (*SO invitado*). Esto reduce la dependencia del hardware, mejora la flexibilidad operativa y permite a los administradores gestionar e implementar VM de manera eficiente, adaptándose a las cambiantes demandas de carga de trabajo.

**2. Múltiples entornos aislados**  
La virtualización crea entornos aislados en una sola máquina física. Cada VM opera de forma independiente, por lo que los problemas en una no afectan a las demás. Este aislamiento:
- Mejora la seguridad (evita acceso no autorizado entre VM)
- Aumenta la estabilidad (contiene fallos)
- Permite entornos robustos de desarrollo y pruebas con múltiples aplicaciones o sistemas ejecutándose simultáneamente sin interferencias.

**3. Partición y asignación de recursos**  
Permite una asignación precisa de recursos como CPU, memoria y almacenamiento. Las VM reciben recursos dinámicamente según sus necesidades, lo que:
- Optimiza el uso del hardware
- Reduce la necesidad de servidores físicos adicionales (ahorro de costos)
- Mejora la eficiencia energética y el espacio físico
- Facilita la escalabilidad de las operaciones

**4. Ubicaciones de virtualización**  
Se puede implementar en diferentes entornos:
- **Local (on-premise)** : control y seguridad
- **Nube**: escalabilidad y acceso remoto
- **Híbrida**: combina lo mejor de ambos mundos, ofreciendo un enfoque equilibrado para la gestión y despliegue de recursos.

Las organizaciones pueden elegir la infraestructura más adecuada según sus necesidades, escalabilidad y presupuesto.

### Características de la virtualización

La virtualización tiene muchas características, incluyendo las siguientes:

- **Protección contra fallos**
- **Procesamiento y operaciones optimizados**
- **Seguridad mejorada**
- **Fácil transferencia de máquinas o datos**
- **Menores costos**


## Como aprendiste, la tecnología de virtualización te permite usar una computadora física para ejecutar varios sistemas operativos. Sin embargo, los entornos en la nube son diferentes tipos de entornos de TI que comparten recursos escalables a través de una red. Se puede pensar en la virtualización como la tecnología y en la nube como el entorno. La virtualización, entonces, es la tecnología que impulsa la computación en la nube. 

### Relación entre virtualización y computación en la nube

Como aprendiste, la tecnología de **virtualización** te permite usar una computadora física para ejecutar varios sistemas operativos. Por otro lado, los **entornos en la nube** son diferentes tipos de entornos de TI que comparten recursos escalables a través de una red.

> **Idea clave:** Se puede pensar en la virtualización como la **tecnología** y en la nube como el **entorno**. La virtualización es la tecnología que impulsa la computación en la nube.

#### ¿Por qué la virtualización es esencial para la nube?

- Permite a los usuarios compartir los **recursos de hardware físico** (no solo datos y aplicaciones).
- Permite a los proveedores de la nube ofrecer entornos de **aplicaciones estandarizados**, simplificando la gestión y reduciendo costos.
- Sin virtualización, los proveedores tendrían que actualizar y mantener versiones de aplicaciones para **cada usuario** individualmente (tarea costosa).
- Con virtualización, las actualizaciones son **centralizadas** en entornos virtuales, y proveedores externos suelen gestionar estos servicios.

#### Modelo de negocio típico

Los proveedores de la nube suelen suscribirse a estos servicios, pagando de forma **mensual o anual**, lo que permite una gestión de infraestructura **escalable y rentable**.

### Hosts y dispositivos virtuales

Los hosts y dispositivos virtuales revolucionaron la forma en que las organizaciones despliegan y gestionan la infraestructura informática.

#### Host virtual

Un **host virtual** es una plataforma de alojamiento que proporciona recursos informáticos y de almacenamiento a uno o varios sitios web, aplicaciones o servicios, cada uno con un nombre de dominio y una dirección IP únicos. Permite a los usuarios alojar varios dominios o diferentes versiones de un sitio en un solo servidor.

#### Dispositivo virtual

Un **dispositivo virtual** es software preinstalado en una o más máquinas virtuales que cumplen una función específica. Se crea instalando un dispositivo de software en una máquina virtual empaquetada en una imagen.

- Utiliza un sistema operativo **preinstalado y preconfigurado** para proporcionar funciones específicas.
- Puede tener diferentes formatos y configuraciones.

##### Formato de virtualización abierto (OVF)

Un dispositivo virtual suele venir en **formato de virtualización abierto (OVF)**. Es una imagen de servidor virtual preinstalada y configurada que se puede importar y usar de inmediato. Si es necesario reconstruir un servidor virtual, simplemente se vuelve a importar el dispositivo virtual en lugar de reinstalar el sistema operativo y las aplicaciones desde cero.

##### Configuraciones cerradas y abiertas

- **Configuración cerrada:** El dispositivo virtual se empaqueta, distribuye, mantiene, actualiza y gestiona como una unidad.
- **Configuración abierta:** Los clientes pueden acceder al dispositivo para modificarlo, y dispone de interfaces para configuración personalizada o para entrega de parches y actualizaciones.

> Los dispositivos virtuales son fundamentales para **aprovisionar rápidamente** sistemas operativos y aplicaciones en plataformas de entrega en la nube.

### VMware

**VMware** fue fundada en 1998 en California y ayudó a revolucionar la industria de la virtualización.

VMware diseña su software de virtualización para diferentes tipos de usuarios:

- **Usuarios domésticos:** permite ejecutar varios sistemas operativos en una sola máquina.
- **Pequeñas empresas:** agiliza la gestión informática mediante la consolidación de recursos de servidor.
- **Empresas:** mejora la escalabilidad y la eficiencia a través de soluciones de infraestructura en la nube.

### VMware vCenter

VMware ofrece varios productos de virtualización para entornos de distintos tamaños:

- **VMware Workstation Pro:** ideal para ejecutar máquinas virtuales en computadoras Windows, Linux o Mac. Es bueno para crear entornos virtuales locales para aprendizaje o pruebas.

- **VMware vCenter:** plataforma de gestión centralizada diseñada para entornos VMware. Ofrece a los administradores un único portal web para monitorear eficazmente máquinas virtuales (VM), hosts, almacenamiento y componentes de red.

#### Funcionalidades clave de VMware vCenter

- Aprovisionamiento de máquinas virtuales
- Supervisión
- Asignación de recursos
- Optimización del rendimiento
- Migración en tiempo real (vMotion)
- Alta disponibilidad (HA)

> VMware vCenter es especialmente adecuado para gestionar despliegues de **vSphere a gran escala**.

### VirtualBox

**VirtualBox** es un software de **código abierto** útil para crear una máquina virtual donde los usuarios pueden ejecutar otro sistema operativo.

#### Terminología clave

- **Sistema operativo invitado:** el sistema operativo que se ejecuta dentro de la máquina virtual.
- **Sistema operativo anfitrión:** el sistema operativo que ejecuta VirtualBox.

#### Características

- Compatible con **Windows, Linux o macOS** como sistema operativo anfitrión.
- Los usuarios pueden configurar la VM especificando:
  - Núcleos de CPU
  - RAM
  - Espacio en disco
- Permite **pausar y reanudar** la máquina virtual más tarde.

### Diferencias entre VirtualBox y VMware (Workstation Pro/Player)

| Característica | VirtualBox | VMware Workstation |
|----------------|------------|--------------------|
| **Licencia** | Código abierto (GPL) y gratuito | Pro: comercial (pago) / Player: gratuito para uso personal |
| **Sistemas anfitrión** | Windows, Linux, macOS | Windows, Linux (macOS requiere VMware Fusion) |
| **Rendimiento general** | Bueno para tareas generales y pruebas | Superior, especialmente en E/S de disco y red |
| **Soporte 3D / gráficos** | Limitado (aunque ha mejorado) | Excelente, ideal para aplicaciones 3D o juegos |
| **Snapshots** | Sí, múltiples snapshots | Pro: múltiples snapshots / Player: solo uno |
| **Clonación** | Completa y enlazada | Completa y enlazada (solo en Pro) |
| **Arrastrar y soltar** | Funciona, a veces inestable | Muy estable |
| **Estabilidad** | Buena, pero con ciertos SO invitados puede fallar | Muy alta, considerada estándar profesional |
| **Integración con entornos empresariales** | Básica | Excelente (vSphere, ESXi, vCenter) |
| **Uso típico** | Aprendizaje, pruebas, entornos ligeros, desarrollo | Entornos exigentes, desarrollo profesional, laboratorios empresariales |

#### Resumen

- **Elige VirtualBox si** buscas una solución **gratuita, open source** y multiplataforma (incluye macOS anfitrión) para pruebas o aprendizaje sin necesidad de alto rendimiento.
- **Elige VMware Workstation si** necesitas **mejor rendimiento, estabilidad y soporte gráfico**, o si tu curso/empresa utiliza entornos VMware (vSphere, ESXi). La versión Player es gratuita para uso personal y cubre la mayoría de necesidades básicas.

> **Nota técnica:** Tanto VirtualBox como VMware Workstation son **hipervisores tipo 2** (se ejecutan sobre un sistema operativo anfitrión). En entornos empresariales de producción se usan **hipervisores tipo 1** como VMware ESXi o Microsoft Hyper-V, que corren directamente sobre el hardware.

### ¿Qué es un hypervisor?

Un **hypervisor** (o monitor de máquina virtual) es un software que permite crear y ejecutar **máquinas virtuales (VM)**. Actúa como una capa que separa el hardware físico (CPU, memoria, disco, red) de los sistemas operativos que se ejecutan encima.

#### ¿Cómo funciona?

El hypervisor toma los recursos físicos de una computadora (un servidor, por ejemplo) y los **divide** para que múltiples sistemas operativos invitados puedan usarlos de forma simultánea e independiente, sin interferir entre sí.

#### Tipos de hypervisores

| Tipo | Nombre | Características | Ejemplos |
|------|--------|----------------|----------|
| **Tipo 1** | *Bare-metal* (sobre hardware desnudo) | Se ejecuta directamente sobre el hardware, sin un sistema operativo base. Es más eficiente, seguro y usado en servidores y centros de datos. | VMware ESXi, Microsoft Hyper-V, KVM |
| **Tipo 2** | *Alojado* (hosted) | Se ejecuta como un programa más dentro de un sistema operativo anfitrión (Windows, Linux, macOS). Es ideal para desarrollo, pruebas o uso personal. | VirtualBox, VMware Workstation, VMware Player |

#### Comparación rápida

| | Hypervisor Tipo 1 | Hypervisor Tipo 2 |
|--|------------------|-------------------|
| **Instalación** | Directamente sobre el hardware | Sobre un SO anfitrión |
| **Rendimiento** | Muy alto (menos sobrecarga) | Bueno (algo de sobrecarga) |
| **Uso típico** | Servidores empresariales, nube, centros de datos | Desarrollo, pruebas, aprendizaje, escritorio |
| **Acceso a hardware** | Directo | A través del SO anfitrión |

> **En resumen:** el hypervisor es el **corazón de la virtualización**. Sin él, no podríamos tener múltiples sistemas operativos conviviendo en la misma máquina física.

### Aspecto destacado de la gestión profesional: ingeniero de virtualización

#### Habilidades de gestión profesional

Has aprendido mucho sobre virtualización. Si estás interesado en las tareas prácticas de virtualización, podrías considerar una carrera como **ingeniero de virtualización**.

#### ¿Qué hace un ingeniero de virtualización?

Los ingenieros de virtualización desempeñan un papel fundamental en la industria de TI. Son responsables de:

- **Diseñar** soluciones de virtualización
- **Implementar** soluciones de virtualización
- **Gestionar** soluciones de virtualización

Esto ayuda a las empresas a:
- Ahorrar dinero
- Mejorar la eficiencia
- Aumentar la agilidad

#### Cómo convertirte en ingeniero de virtualización

Para adquirir las habilidades necesarias, considera lo siguiente:

1. **Obtener un título relevante**  
   Una licenciatura en informática, tecnología de la información o un campo relacionado es esencial para la mayoría de los puestos.

2. **Realizar cursos relevantes**  
   Busca cursos sobre virtualización. Plataformas en línea como **IBM SkillsBuild**, **Coursera** y **edX** ofrecen una amplia gama de cursos para desarrollar las habilidades necesarias.

3. **Obtener certificaciones relevantes**  
   Varias certificaciones pueden demostrar tus habilidades y conocimientos en virtualización, como la certificación **VMware Certified Professional - Data Center Virtualization (VCP-DCV)**.

4. **Adquirir experiencia**  
   La mejor manera de adquirir experiencia en virtualización es conseguir un trabajo de nivel básico en TI, como técnico de soporte técnico o administrador de sistemas. Esto te dará la oportunidad de trabajar con tecnologías de virtualización y aprender las habilidades necesarias.

5. **Mantenerse actualizado**  
   Mantén tus habilidades actualizadas sobre las últimas tecnologías de virtualización.

   ### Acerca de esta lección: Virtualización de red

Los modelos de **virtualización de red** y **despliegue en la nube** son cada vez más populares en la industria de TI, y por una buena razón. Proporcionan soluciones escalables, flexibles y rentables para gestionar y desplegar infraestructura y servicios de TI.

Los modelos de ciberseguridad, virtualización de redes y despliegue en la nube están estrechamente relacionados. Comprender esta relación es crucial para crear **redes virtualizadas seguras y resilientes**.

En esta lección, aprenderás sobre:

- La **virtualización de red**
- Los diferentes tipos de **modelos de despliegue en la nube**

### ¿Qué es la virtualización de red?

¿Alguna vez te has preguntado cómo los proveedores de nube ofrecen soluciones de red flexibles y escalables a millones de clientes en todo el mundo? ¿O cómo pueden conectarte de forma segura a aplicaciones y datos, independientemente de tu ubicación o dispositivo? La respuesta está en la **magia de la virtualización de red**.

#### Definición

La **virtualización de red** combina hardware, recursos de software y funcionalidad de red en un único sistema basado en software. Con ella, los proveedores pueden:

- **Combinar** varias redes físicas en una red virtual basada en software.
- **Dividir** una sola red física en una red virtual separada e independiente.

#### Analogía con realidad virtual

La virtualización de red es similar a la **realidad virtual** en que ambas emplean tecnología basada en software para crear un entorno simulado que puedes personalizar y controlar. La diferencia clave:

- **Realidad virtual:** se centra en experiencias inmersivas dentro de mundos virtuales.
- **Virtualización de red:** pretende crear redes virtuales.

El objetivo principal de la virtualización de red es introducir una **capa de abstracción** entre el hardware físico y las aplicaciones de red, simplificando la gestión (como un controlador de tráfico facilita la fluidez del tráfico).

---

### Beneficios de la virtualización de red

#### 1. Independencia

La virtualización de red agrega una capa de abstracción entre el hardware físico (enrutadores, conmutadores) y las aplicaciones que emplean la red. Esta capa actúa como traductor, haciendo que la comunicación sea más fluida y flexible.

- Las redes virtuales están **lógicamente aisladas** entre sí.
- Permite que múltiples inquilinos o aplicaciones compartan los mismos recursos físicos sin interferir.
- **Beneficios:** mejor uso de recursos, escalabilidad y gestión simplificada.

> **Analogía:** como crear "carriles virtuales" separados en una autopista, aunque la carretera física siga siendo la misma.

#### 2. Escalabilidad

Con la virtualización de red, las organizaciones y los proveedores de nube pueden ampliar o reducir sus servicios sin tener que crear nuevas redes físicas. Las redes virtuales se pueden **crear, modificar o eliminar** fácilmente para adaptarse a las necesidades de la organización.

#### 3. Desempeño

Puedes configurar los servicios para garantizar un rendimiento y una confiabilidad óptimos. Servicios como:

- **Equilibrio de carga** (distribuir cargas de trabajo entre varios servidores o recursos para optimizar el rendimiento y evitar sobrecargas)
- **Modelado del tráfico**
- **Segmentación de la red**

Actúan como instrumentos afinados y orquestados con precisión para producir un rendimiento óptimo y armonioso.

> **Analogía:** como una orquesta afinada con precisión.

#### 4. Seguridad

La virtualización de red aumenta la seguridad al **separar la infraestructura física de las aplicaciones**, proporcionando una capa adicional de protección.

- **Aislamiento de red:** protege contra amenazas externas (malware, ransomware, etc.)
- Si un atacante obtiene acceso a los datos de un cliente, casi no tiene posibilidades de acceder a los datos de otro cliente.
- Al implementar protocolos y controles de seguridad adecuados, los proveedores de nube ayudan a las organizaciones a proteger mejor sus datos e infraestructura.

#### 5. Eficiencia

La virtualización de red ayuda a las organizaciones a **ahorrar tiempo y dinero**:

- Menor necesidad de hardware físico (enrutadores, conmutadores, servidores costosos).
- Menos gasto en mantenimiento y actualizaciones periódicas del equipo.
- El hardware tradicional requiere actualizaciones constantes para mantenerse seguro y efectivo.


### Virtualización de red: interna y externa

Existen dos tipos principales de virtualización de red: **interna** y **externa**.

#### Virtualización de red interna

La virtualización de red interna crea una **red simulada dentro de un solo servidor** para hacerlo más eficiente.

- Se configuran **contenedores de software** en el servidor.
- Diferentes sistemas operativos y aplicaciones pueden ejecutarse en el mismo servidor.
- **Beneficios:** menos hardware necesario, mayor flexibilidad, posibilidad de cambiar los recursos de red según las necesidades.

> **Analogía:** como dividir un edificio en departamentos virtuales, cada uno con sus propias reglas, pero compartiendo la misma estructura física.

#### Virtualización de red externa

La virtualización de red externa ayuda a los proveedores de servicios a crear **redes de área local virtuales (VLAN)** .

- Agrupa sistemas físicos que están conectados a la misma LAN.
- También puede dividir LAN separadas en una misma VLAN.
- **Beneficio principal:** optimizar los recursos de servidor.

**Ejemplo:** un proveedor puede crear VLAN separadas para diferentes grupos o clientes, cada una con sus propias políticas de seguridad y configuraciones de red.

#### Tecnología subyacente: NFV (Virtualización de Funciones de Red)

Tanto la virtualización interna como la externa emplean la **NFV** (Network Functions Virtualization). Esta tecnología permite empaquetar funciones de red (como firewalls, balanceadores de carga, enrutadores) como **máquinas virtuales o contenedores** que se ejecutan en servidores estándar, en lugar de usar hardware dedicado.

#### Comparación rápida

| | Virtualización interna | Virtualización externa |
|--|----------------------|----------------------|
| **Alcance** | Dentro de un solo servidor | Entre múltiples servidores/redes físicas |
| **Objetivo** | Hacer más eficiente un servidor | Crear VLAN y agrupar/segmentar redes físicas |
| **Ejemplo de uso** | Ejecutar varios SO y apps en un servidor | Separar tráfico de diferentes clientes en un proveedor de nube |

### Componentes de red en virtualización

#### Tarjeta de interfaz de red (NIC)

Una **tarjeta de interfaz de red (NIC)** es un componente de hardware que conecta una computadora u otro dispositivo electrónico a una red. Proporciona una interfaz física para que el dispositivo envíe y reciba datos a través de la red.

#### Tarjeta de interfaz de red virtual (VNIC)

En un entorno virtualizado, se crea y emplea una **tarjeta de interfaz de red virtual (VNIC)** para representar una NIC física.
 
> *(Si tienes la imagen, puedes insertarla aquí; la imagen muestra las zonas y conexiones)*

#### ¿Cómo se organizan?

- Un sistema único puede contener varias **zonas** (redes virtuales internas).
- Estas zonas emplean sus respectivas **VNIC** para comunicarse entre sí y con la red externa.

#### Conmutador virtual

Las VNIC se conectan a la **NIC física subyacente** a través de un **conmutador virtual** (o switch virtual). Un conmutador virtual proporciona la misma conectividad a los sistemas conectados a sus puertos que un conmutador físico (switch de hardware), pero funciona completamente en software.

**Analogía:** Así como un switch físico conecta varias computadoras en una red local, un conmutador virtual conecta varias máquinas virtuales (o VNIC) entre sí y con la red física real.

### Modelos de implementación en la nube

Ahora que conoces la virtualización de red, estudiemos los **modelos de despliegue en la nube** que la virtualización hace posibles. Las organizaciones pueden elegir entre cuatro modelos principales para alojar sus servicios y aplicaciones informáticos.

#### 1. Nube pública
- Los servicios se proporcionan a través de Internet por un proveedor externo.
- La infraestructura es compartida entre múltiples organizaciones (inquilinos).
- **Ventajas:** escalabilidad, pago por uso, bajo costo inicial.
- **Ejemplos:** AWS, Microsoft Azure, Google Cloud, IBM Cloud.

#### 2. Nube privada
- La infraestructura se utiliza exclusivamente por una sola organización.
- Puede estar alojada localmente (on-premise) o por un proveedor externo.
- **Ventajas:** mayor control, personalización, seguridad y cumplimiento normativo.
- **Ejemplos:** VMware vSphere en el centro de datos de la empresa, nube privada de IBM.

#### 3. Nube híbrida
- Combina nubes públicas y privadas que se comunican entre sí.
- Permite mover datos y aplicaciones entre ambos entornos.
- **Ventajas:** flexibilidad, optimización de costos, mayor resiliencia (lo crítico en privado, lo variable en público).
- **Ejemplo:** una empresa tiene su base de datos de clientes en su nube privada, pero usa una nube pública para ejecutar campañas de marketing estacionales.

#### 4. Nube comunitaria
- La infraestructura es compartida por varias organizaciones con **intereses comunes** (mismas políticas de seguridad, cumplimiento normativo, objetivos).
- Puede ser gestionada por ellas mismas o por un proveedor externo.
- **Ventajas:** costos compartidos, colaboración, estándares comunes.
- **Ejemplo:** varios hospitales comparten una nube comunitaria para almacenar historias clínicas cumpliendo con las regulaciones de salud.

#### Comparación rápida

| Modelo | ¿Quién usa la infraestructura? | ¿Dónde se aloja? | Nivel de control |
|--------|-------------------------------|------------------|------------------|
| **Pública** | Múltiples organizaciones | En el proveedor | Bajo |
| **Privada** | Una sola organización | On-premise o proveedor dedicado | Alto |
| **Híbrida** | Combinación | Mixto | Medio |
| **Comunitaria** | Grupo con intereses comunes | Puede ser mixto | Compartido |

> **Consejo:** La elección del modelo depende de las necesidades de la organización: presupuesto, requisitos de seguridad, escalabil### Nube pública

Una **nube pública** brinda a los usuarios acceso a sistemas virtuales, servicios y datos a través de Internet. Un **CSP (Cloud Service Provider)** mantiene la nube pública y proporciona acceso a servidores, almacenamiento, redes y plataformas de desarrollo que múltiples empresas pueden usar.

![Nube pública](image.png)

#### Beneficios de las nubes públicas

**1. Rentabilidad**  
Las empresas solo pagan por los recursos informáticos que realmente usan (modelo de pago por uso). No hay inversión inicial en hardware.

**2. Acceso a infraestructura de vanguardia**  
Las empresas pueden acceder a infraestructura informática moderna sin comprarla ni contratar personal de TI para mantenerla.

**3. Gestión eficaz de los recursos**  
La nube pública puede escalar recursos bajo demanda. Por ejemplo, una empresa minorista que experimenta un aumento drástico en las compras en línea durante una temporada navideña puede aumentar automáticamente los recursos de su servidor web.

#### ¿Quién usa nubes públicas?

- **Startups de comercio electrónico**  
  Empresas de rápido crecimiento que necesitan escalar rápidamente sin inversión inicial en infraestructura.

- **Empresas que buscan mayores recursos a bajo costo**  
  En lugar de invertir en hardware y software costosos, trasladan sus aplicaciones y datos a proveedores como **AWS** (Amazon Web Services) o **Microsoft Azure**. Esto permite escalar recursos sin preocuparse por costos y mantenimiento.

- **Empresas que necesitan seguridad, respaldo y recuperación**  
  Pueden aprovechar la experiencia del proveedor en seguridad, respaldo de datos y recuperación ante desastres, enfocándose en su negocio principal.

**Ejemplo práctico:**  
Una startup de comercio electrónico tuvo un fuerte aumento en la demanda, lo que puso a prueba su infraestructura de TI existente. Al migrar a una nube pública, pudo escalar rápidamente y delegar la seguridad y el respaldo al proveedor.idad y cumplimiento normativo.

### Nube privada

Una **nube privada** es una nube en la que una empresa tiene su propia infraestructura informática que **no se comparte con nadie más**. La empresa puede desplegar su propio software y plataformas. La infraestructura está protegida por un **firewall** y solo se puede acceder a través de la intranet de la empresa con conexiones cifradas.

> **Forma de pago:** Generalmente se basa en un modelo de tarifa por unidad de tiempo.

#### Beneficios de la nube privada

- **Control total** sobre las opciones y personalizaciones de hardware y software.
- **Mayor visibilidad** de los controles de seguridad y acceso (todo se ejecuta de manera privada).
- **Control sobre el cumplimiento normativo** de la propia empresa.

#### Desventajas de la nube privada

- **Alto mantenimiento:** la empresa debe gestionar sus propias plataformas y aplicaciones.
- **Alto costo:** puede ser costoso si se necesita contratar personal de TI. Algunos CSP ofrecen aplicaciones de software y escritorio virtual dentro de la nube privada para ayudar con el costo adicional.

#### ¿Quién emplea nubes privadas?

Grandes empresas que necesitan un alto nivel de control sobre su infraestructura de TI, seguridad de datos y requisitos de cumplimiento normativo. Por ejemplo:

- **Instituciones financieras**
- **Organizaciones de atención médica**
- **Agencias gubernamentales**

#### Caso práctico: industria de la salud

Una empresa de atención médica puede optar por una nube privada debido a la naturaleza confidencial de sus datos (PHI - Información de Salud Protegida).

- **Cumplimiento normativo:** debe cumplir estrictas regulaciones de privacidad.
- **Control total:** al desplegar la nube privada en su propio centro de datos, mantiene control total sobre los datos y puede implementar protocolos de seguridad a medida.
- **Supervisión cercana:** permite monitorear y gestionar la infraestructura para prevenir filtraciones u otros incidentes de seguridad.
- **Rentable a largo plazo:** para cargas de trabajo constantes a gran escala (alta potencia de cómputo y almacenamiento), puede ser más rentable que otras opciones.

> **Nota:** Las nubes privadas pueden ser más caras que las públicas, y la empresa solo puede emplear la infraestructura especificada en su contrato con el CSP.

### Nube híbrida

Una **nube híbrida** combina una **nube privada** y una **nube pública** que están conectadas entre sí, permitiendo mover datos y aplicaciones de un entorno a otro.

#### Características principales

- Integra infraestructura local (on-premise) con servicios de nube pública.
- Permite mantener datos sensibles en la nube privada y usar la nube pública para cargas de trabajo variables o de prueba.
- Ofrece **flexibilidad**, **optimización de costos** y **mayor resiliencia**.

#### Beneficios

- **Lo mejor de ambos mundos:** control y seguridad de la nube privada + escalabilidad y pago por uso de la nube pública.
- **Respuesta a picos de demanda:** si una empresa minorista tiene un aumento de tráfico inesperado, puede "estallar" hacia la nube pública (cloud bursting) sin necesidad de comprar hardware adicional.
- **Cumplimiento normativo:** los datos regulados se quedan en la nube privada; el resto puede ir a la pública.

#### Ejemplo práctico

Una institución financiera mantiene su base de datos de clientes y transacciones en su nube privada por seguridad. Para una campaña promocional estacional, despliega una aplicación web en una nube pública (AWS o Azure) que consulta la base de datos privada a través de una conexión segura. Así evita invertir en servidores que solo usaría dos meses al año.

---

### Nube comunitaria

Una **nube comunitaria** es una infraestructura compartida por **varias organizaciones con intereses comunes** (mismos requisitos de seguridad, políticas, cumplimiento normativo o misión). Puede ser gestionada por ellas mismas o por un proveedor externo.

#### Características principales

- Los costos se **comparten** entre los miembros de la comunidad.
- Se establecen **estándares y políticas comunes** (por ejemplo, protección de datos de salud, estándares bancarios).
- Cada organización mantiene sus propios datos y aplicaciones separados dentro de la infraestructura compartida.

#### Beneficios

- **Más económica** que una nube privada (porque se divide el gasto).
- **Mayor control y cumplimiento** que una nube pública (porque las reglas las define la comunidad).
- **Colaboración facilitada** entre organizaciones que necesitan intercambiar datos de forma segura.

#### ¿Quién la usa?

- **Organizaciones de salud:** varios hospitales comparten una nube que cumple con HIPAA (ley de privacidad médica) para almacenar historias clínicas.
- **Instituciones financieras:** bancos que necesitan cumplir normativas PCI-DSS para pagos.
- **Agencias gubernamentales:** distintos organismos del estado que comparten infraestructura con estándares de seguridad comunes.

#### Ejemplo práctico

Tres hospitales de una región deciden crear una nube comunitaria. Cada hospital sigue siendo independiente, pero comparten servidores, almacenamiento y medidas de seguridad. Así reducen costos individuales, pueden compartir investigaciones de forma segura y todos cumplen las mismas leyes de protección de datos.

---

### Comparativa final entre los cuatro modelos

| Modelo | ¿Infraestructura dedicada? | ¿Compartida con quién? | Costo típico | Control/seguridad |
|--------|---------------------------|------------------------|--------------|-------------------|
| **Pública** | No | Múltiples inquilinos (cualquiera) | Bajo (pago por uso) | Bajo |
| **Privada** | Sí | Solo la organización | Alto (capex + mantenimiento) | Muy alto |
| **Híbrida** | Mixto | Privada + pública | Variable | Alto (en lo crítico) |
| **Comunitaria** | Compartida dentro del grupo | Organizaciones con intereses comunes | Medio | Alto (dentro del grupo) |

### Acerca de esta lección: Nube como servicio (CaaS)

Cuando se trata de computación en la nube, no se trata solo de "CaaS" y efecto; también se trata de **ciberseguridad**.

La gestión y el almacenamiento de datos a través de la computación en la nube ganaron popularidad en los últimos años. Una forma de entregar recursos informáticos a través de Internet (incluyendo almacenamiento, redes y aplicaciones de software) es a través de la **nube como servicio (CaaS)**.

Para los profesionales de la ciberseguridad, es importante comprender CaaS porque es probable que los **datos que necesitan defender** estén almacenados en entornos de nube.

En esta lección, aprenderás sobre:

- **CaaS** (Nube como servicio)
- **CSP*### ¿Qué es la nube como servicio (CaaS)?


La **nube como servicio (CaaS)** ha transformado el almacenamiento y la gestión de datos, ofreciendo una solución flexible, rentable y escalable para recursos informáticos.

#### Definición

**CaaS** se refiere a los recursos de aplicaciones e infraestructura que residen en Internet. Los **proveedores de servicios en la nube (CSP)** contratan suscriptores individuales o corporativos que pueden usar estos servicios **sin pagar ni mantener** el hardware y el software.

#### Beneficios de CaaS

**1. Escalabilidad**  
CaaS aumenta de manera efectiva las opciones de escalabilidad y simultáneamente proporciona flexibilidad en los costos, porque la mayoría de los proveedores ofrecen un método de **pagar solo por lo que usas**.

**2. Entorno simplificado**  
CaaS permite a las empresas:
- Escalar inmediatamente cuando sea necesario
- Reducir las cargas de trabajo
- Evitar los costos de aprovisionamiento excesivo
- Beneficiarse del soporte de los proveedores
- Experimentar un entorno simplificado

**3. Aplicación basada en la nube**  
La nube despliega completamente una aplicación basada en la nube, donde **todas las partes de la aplicación se ejecutan en la nube**.

**4. Desarrollo de aplicaciones**  
Durante el desarrollo de aplicaciones, los desarrolladores crean aplicaciones basadas en la nube o las migran desde la infraestructura o los centros de datos existentes para aprovechar los beneficios de la computación en la nube.

**5. Flexibilidad**  
Las aplicaciones basadas en la nube pueden usar infraestructura de bajo nivel o servicios de nivel superior, ofreciendo flexibilidad frente a las restricciones, el diseño y las demandas de escalado de la infraestructura principal.* (Proveedores de servicios en la nube)
- Los **cuatro servicios principales** de computación en la nube

#### Ejemplo práctico de CaaS (Nube como Servicio)

Un ejemplo claro y muy común de **"Nube como Servicio" (Cloud as a Service)** es **Hostinger** o cualquier otro proveedor de **alojamiento web en la nube (Cloud Hosting)**.

Empresas como Hostinger toman toda la infraestructura compleja (servidores, almacenamiento, redes) y la ofrecen como un servicio ya gestionado.

**¿Qué significa esto en la práctica?**

- **Para el usuario:** Solo te suscribes a un plan (pagas una cuota mensual), eliges un tipo de hosting (ej. Cloud Startup) y puedes crear y publicar tu sitio web o aplicación en minutos[reference:2].
- **Simplificación total:** No necesitas comprar ni mantener servidores físicos. El proveedor (Hostinger) se encarga de la seguridad, las copias de seguridad, el equilibrio de la carga y de que todo funcione correctamente[reference:3].
- **Escalabilidad y pago por uso:** Si tu proyecto crece, puedes cambiar a un plan superior con más recursos (RAM, CPU) fácilmente. Este es el corazón del modelo de "pagar solo por lo que se usa" que estudiaste.

**En resumen:** Cuando una persona o una pequeña empresa contrata el hosting de Hostinger para crear su sitio web, no está comprando un servidor; está consumiendo **Nube como Servicio (CaaS)**. Toda la tecnología de centros de datos, virtualización y redes que has estudiado en este módulo está trabajando detrás para que eso sea posible.

### Modelos de servicio de computación en la nube

Para usar CaaS (Nube como Servicio), necesitas un **proveedor de servicios en la nube (CSP)**. Un CSP proporciona servicios informáticos a través de Internet.

Los cuatro servicios principales son:

#### 1. IaaS (Infraestructura como Servicio)
- **Qué es:** Te proporciona recursos de computación virtualizados (servidores, almacenamiento, redes). Vos instalás y gestionás el sistema operativo y las aplicaciones.
- **Ejemplo:** Amazon EC2, IBM Cloud Virtual Servers.
- **Para qué sirve:** Control total sin comprar hardware físico.

#### 2. PaaS (Plataforma como Servicio)
- **Qué es:** Te da un entorno de desarrollo y despliegue completo. Vos solo subís tu código; el proveedor gestiona el sistema operativo, el runtime y los servidores.
- **Ejemplo:** Google App Engine, Heroku, IBM Cloud Foundry.
- **Para qué sirve:** Desarrolladores que no quieren administrar infraestructura.

#### 3. SaaS (Software como Servicio)
- **Qué es:** Aplicaciones listas para usar a través de Internet. El proveedor se encarga de todo: servidores, actualizaciones, seguridad.
- **Ejemplo:** Gmail, Google Drive, Microsoft 365.
- **Para qué sirve:** Usuarios finales que solo quieren usar el software.

#### 4. DBaaS (Base de Datos como Servicio)
- **Qué es:** Una base de datos operativa gestionada por el proveedor. Incluye copias de seguridad, parches, escalado automático.
- **Ejemplo:** Amazon RDS, IBM Cloud Databases, MongoDB Atlas.
- **Para qué sirve:** Empresas o desarrolladores que necesitan una base de datos sin administrarla manualmente.

#### Comparación

| Modelo | Qué te dan | Qué hacés vos |
|--------|-----------|---------------|
| IaaS | Servidores, almacenamiento, redes | Instalás SO y apps |
| PaaS | Entorno de desarrollo + runtime | Subís tu código |
| SaaS | Aplicación lista | La usás |
| DBaaS | Base de datos gestionada | Consultás y gestionás datos |

### IaaS (Infraestructura como Servicio)


*La infraestructura incluye hardware como conmutadores, servidores, discos duros y enrutadores. Las computadoras y servidores que almacenan datos y ejecutan código, junto con los cables y dispositivos que los conectan, conforman la infraestructura informática.*

#### Definición

**IaaS (Infraestructura como Servicio)** proporciona acceso a:
- Funciones de red
- Computadoras virtuales o físicas
- Espacio de almacenamiento de datos

IaaS brinda a las empresas **flexibilidad y control** sobre sus recursos de TI.

#### Ejemplos de IaaS

- **Amazon Web Services (AWS)**
- **Google Compute Engine**
- **Rackspace**
- IBM Cloud Virtual Servers

#### ¿Qué empresas eligen IaaS?

Empresas que requieren un alto grado de flexibilidad y control sobre su infraestructura de TI, incluyendo aquellas que necesitan:
- Aumentar o reducir rápidamente sus recursos
- Cumplir requisitos especializados que no pueden satisfacer con soluciones listas para usar

#### Beneficios de IaaS

**Lo antiguo vs. lo nuevo**

Antes, la mayoría de las empresas alojaban sus propias redes y ejecutaban todas sus aplicaciones de forma local (on-premise). Hoy, mediante la migración a IaaS, las empresas pueden:

- Reducir el mantenimiento de los centros de datos locales
- Ahorrar en costos de hardware
- Obtener información comercial en tiempo real

**Infraestructura de autoabastecimiento**

Con IaaS, las empresas adquieren servicios de infraestructura y **pagan por uso**. Las tarifas generalmente se cobran por hora, semana o mes, según las circunstancias. Los clientes pueden ser cobrados en función del número de recursos de máquina virtual (VM) que usen durante un periodo de tiempo.

> **En resumen:** IaaS te da el control total sobre la infraestructura (servidores, redes, almacenamiento) sin que tengas que comprar ni mantener el hardware físico.

### PaaS (Plataforma como Servicio)


#### Definición

**PaaS (Plataforma como Servicio)** proporciona un entorno de desarrollo y despliegue completo en la nube. Los desarrolladores pueden crear, ejecutar y gestionar aplicaciones sin preocuparse por la infraestructura subyacente (servidores, almacenamiento, redes, sistemas operativos).

#### Ejemplos de PaaS

- **Google App Engine**
- **IBM Cloud Foundry**
- **Heroku**
- **Microsoft Azure App Service**

#### ¿Qué empresas o perfiles eligen PaaS?

- **Desarrolladores** que quieren enfocarse solo en escribir código y lanzar aplicaciones rápidamente.
- **Equipos de DevOps** que necesitan automatizar despliegues sin administrar servidores.
- **Startups** que buscan velocidad de salida al mercado sin invertir en infraestructura inicial.

#### Beneficios de PaaS

**1. Desarrollo más rápido**  
El entorno ya viene con sistemas operativos, librerías, bases de datos y herramientas de prueba. El desarrollador solo sube su código.

**2. Menos administración**  
No hay que parchear sistemas operativos, actualizar servidores ni gestionar backups de bajo nivel (muchas veces incluidos).

**3. Escalabilidad automática**  
La plataforma puede escalar la aplicación según la demanda: más usuarios, más recursos; menos usuarios, menos recursos. El pago suele ser por consumo.

**4. Colaboración facilitada**  
Diferentes desarrolladores pueden trabajar sobre la misma plataforma, compartir entornos de prueba y producción sin fricciones.

#### Lo antiguo vs. lo nuevo

**Antes:** Cada empresa debía comprar servidores, instalar sistemas operativos, configurar bases de datos, y mantener todo actualizado. Un proyecto simple requería semanas de preparación.

**Ahora con PaaS:** En minutos tenés un entorno listo para programar. El proveedor se encarga de la seguridad, los parches y la disponibilidad.

> **En resumen:** PaaS te da el **comedor equipado** para que solo traigas tu receta (código). Vos cocinás, pero no te preocupás por los hornos ni la heladera.

---

### SaaS (Software como Servicio)


#### Definición

**SaaS (Software como Servicio)** ofrece aplicaciones de software completamente funcionales a través de Internet, generalmente mediante un navegador web. El proveedor gestiona toda la infraestructura, las actualizaciones, la seguridad y la disponibilidad. El usuario solo se conecta y usa el software.

#### Ejemplos de SaaS

- **Gmail** (correo electrónico)
- **Google Drive / Microsoft 365** (ofimática en la nube)
- **Salesforce** (CRM - gestión de clientes)
- **Spotify** (streaming de música)
- **Netflix** (streaming de video)
- **Slack** (comunicación empresarial)

#### ¿Quiénes usan SaaS?

- **Usuarios finales** (personas o empleados) que necesitan una herramienta sin complicaciones técnicas.
- **Empresas** que quieren reducir costos de licencias y mantenimiento de software instalado localmente.
- **Equipos remotos** que necesitan colaborar desde cualquier lugar con conexión a Internet.

#### Beneficios de SaaS

**1. Sin instalación ni mantenimiento**  
No hay que instalar nada en la computadora local (excepto un navegador). Las actualizaciones son automáticas y transparentes.

**2. Acceso desde cualquier lugar**  
Solo se necesita Internet. Se puede trabajar desde casa, la oficina o un café.

**3. Pago por suscripción**  
Normalmente se paga un monto mensual o anual por usuario. Evita grandes desembolsos iniciales por licencias permanentes.

**4. Escalabilidad simple**  
Se pueden agregar o quitar usuarios en minutos, ajustando el costo según las necesidades del negocio.

**5. Seguridad y backups incluidos**  
El proveedor se encarga de proteger los datos y hacer copias de seguridad periódicas.

#### Lo antiguo vs. lo nuevo

**Antes:** Se compraba una licencia de software (costosa), se instalaba en cada computadora, se contrataba personal para actualizaciones y parches de seguridad. Si la empresa crecía, había que comprar más licencias y más servidores.

**Ahora con SaaS:** Abrís el navegador, iniciás sesión y el software está listo. El proveedor escala y protege todo por vos.

> **En resumen:** SaaS es como **alquilar una aplicación ya hecha**. Vos solo la usás y pagás por el tiempo o la cantidad de usuarios. Todo el resto lo maneja el proveedor.

---

### Comparativa rápida de los tres (IaaS, PaaS, SaaS)

| Modelo | Qué te da | Qué gestionás vos | Ejemplo |
|--------|-----------|-------------------|---------|
| **IaaS** | Servidores virtuales, almacenamiento, redes | SO, middleware, apps, datos | AWS EC2 |
| **PaaS### DBaaS (Base de Datos como Servicio)


#### Definición

**DBaaS (Base de Datos como Servicio)** es un modelo en el que el proveedor de nube ofrece una base de datos completamente gestionada. Los usuarios no instalan ni administran el motor de base de datos, el almacenamiento subyacente, las copias de seguridad ni las actualizaciones. Solo consumen la base de datos a través de conexiones estándar y pagan por lo que usan.

#### Ejemplos de DBaaS

- **Amazon RDS** (Relational Database Service: MySQL, PostgreSQL, Oracle, SQL Server)
- **IBM Cloud Databases** (PostgreSQL, MongoDB, Redis, etc.)
- **MongoDB Atlas** (MongoDB como servicio)
- **Google Cloud SQL**
- **Azure Cosmos DB**

#### ¿Quiénes usan DBaaS?

- **Desarrolladores** que necesitan una base de datos para sus aplicaciones sin perder tiempo instalando, configurando o parcheando motores.
- **Empresas** que quieren reducir la carga de administración de bases de datos (DBA) y enfocarse en el negocio.
- **Proyectos con cargas variables** que necesitan escalar capacidad de almacenamiento o rendimiento bajo demanda.
- **Equipos DevOps** que automatizan despliegues y necesitan bases de datos efímeras para pruebas.

#### Beneficios de DBaaS

**1. Administración cero (o casi cero)**  
El proveedor se encarga de:
- Instalación y parches del motor de base de datos
- Copias de seguridad automáticas
- Replicación y alta disponibilidad
- Monitoreo y alertas

**2. Escalabilidad elástica**  
Se puede aumentar almacenamiento, memoria o capacidad de procesamiento en minutos, a menudo sin interrumpir el servicio.

**3. Pago por uso**  
Se paga según los recursos consumidos (almacenamiento en GB, horas de ejecución, operaciones de lectura/escritura). Es más económico que tener servidores dedicados subutilizados.

**4. Seguridad integrada**  
Los proveedores ofrecen cifrado en reposo y en tránsito, redes privadas virtuales (VPC), y cumplimiento de normativas (GDPR, HIPAA, etc.) de forma predeterminada.

**5. Disponibilidad y recuperación ante desastres**  
Suelen incluir réplicas en múltiples zonas geográficas y restauración a un punto en el tiempo (point-in-time recovery).

#### Lo antiguo vs. lo nuevo

**Antes:** Una empresa compraba servidores, instalaba Oracle o MySQL, configuraba almacenamiento RAID, programaba backups nocturnos, contrataba administradores de bases de datos (DBAs) y monitoreaba 24/7. Ante un pico de tráfico, el equipo se quedaba sin rendimiento y la única solución era comprar más hardware.

**Ahora con DBaaS:** En unos minutos tenés una base de datos de producción con alta disponibilidad, backups automáticos, réplicas de solo lectura para reportes, y podés escalar el plan con un clic. El proveedor se encarga de la seguridad y el mantenimiento.

> **En resumen:** DBaaS es como **contratar un servicio de nevera inteligente**. No sabés ni te importa cómo funciona el motor de frío; solo guardás tus datos y los recuperás cuando querés. El proveedor se encarga de que esté siempre operativa, con hielo fresco y sin cortes de energía.

---

### Comparativa final de los cuatro modelos de servicio

| Modelo | Qué te da | Qué gestionás vos | Ejemplo típico |
|--------|-----------|-------------------|----------------|
| **IaaS** | Servidores virtuales, almacenamiento, redes | SO, middleware, apps, datos | AWS EC2, IBM Cloud Virtual Servers |
| **PaaS** | Entorno de desarrollo + runtime | Aplicación y datos (el resto lo hace la plataforma) | Heroku, Google App Engine |
| **SaaS** | Aplicación completa | Solo usás la app (datos de entrada/salida) | Gmail, Microsoft 365 |
| **DBaaS** | Base de datos gestionada | Consultas y modelos de datos (el motor lo gestiona el proveedor) | Amazon RDS, MongoDB Atlas, IBM Cloud Databases |** | Entorno de desarrollo + runtime | Apps y datos (el resto lo hace la plataforma) | Heroku |
| **SaaS** | Aplicación completa | Solo usás la app (datos de entrada/salida) | Gmail |


### Aspecto destacado de la gestión profesional: computación en la nube

#### Habilidades de gestión de carrera

Hay varias maneras de seguir una carrera en computación en la nube.

#### Opciones para formarte y certificarte

1. **Obtener un título universitario**  
   Un título en ciencias de la computación o un campo relacionado proporciona una base sólida en los conceptos básicos y tecnologías utilizadas en la computación en la nube.

2. **Buscar certificaciones relevantes**  
   Certificaciones ofrecidas por los principales proveedores de nube, como **IBM**, **Amazon Web Services (AWS)** y **Microsoft Azure**. Estas certificaciones demuestran competencia en tecnologías de nube y son muy valoradas por los empleadores.

#### Adquirir experiencia práctica

- Realizar **pasantías** o puestos de **nivel básico** en roles relacionados con la nube.
- Estos puestos proporcionan experiencia práctica con plataformas en la nube y exposición a los procesos y flujos de trabajo involucrados en las operaciones en la nube.

#### Networking y comunidad

- **Crear redes** con profesionales en el campo.
- Asistir a **eventos y conferencias** de la industria.
- Participar en **comunidades en línea** para desarrollar conocimientos y conexiones en la industria de la computación en la nube.

### Fuentes del módulo

La siguiente lista contiene las fuentes de este módulo:

#### Lección 2: Virtualización de red

1. [What is private cloud?](https://www.ibm.com) (se abre en una nueva pestaña). IBM (sitio web), consultado el 24 de junio de 2024.

#### Lección 3: La nube como servicio

1. [Cloud services](https://www.hpe.com) (se abre en una nueva pestaña). Hewlett Packard Enterprise (sitio web), consultado el 24 de junio de 2024.

### Los 4 modelos de servicio en la nube (explicación fácil)

#### IaaS (Infraestructura como Servicio)
**Analogía:** Hacés tu propia pizza desde cero. Te dan la cocina, los ingredientes; vos amasás, cocinás y servís.  
**En la nube:** servidores virtuales, almacenamiento, redes. Vos instalás el SO y las apps.  
**Ejemplo:** AWS EC2, IBM Cloud Virtual Servers.

#### PaaS (Plataforma como Servicio)
**Analogía:** Pedís pizza a domicilio. La pizza ya está cocinada; vos solo la servís y comés.  
**En la nube:** entorno con SO, base de datos, herramientas. Vos subís tu código y corre solo.  
**Ejemplo:** Heroku, Google App Engine.

#### SaaS (Software como Servicio)
**Analogía:** Comés en el restaurante. Llegás, comés y pagás; todo lo demás lo hace el local.  
**En la nube:** aplicación lista para usar desde el navegador. El proveedor gestiona todo.  
**Ejemplo:** Gmail, Netflix, Google Drive.

#### DBaaS (Base de Datos como Servicio)
**Analogía:** Alquilás una heladera inteligente. Solo guardás y sacás comida; ella se limpia y mantiene sola.  
**En la nube:** base de datos gestionada (backups, parches, escalado). Vos solo hacés consultas.  
**Ejemplo:** Amazon RDS, MongoDB Atlas, IBM Cloud Databases.

> **Resumen:** IaaS = control total, PaaS = solo código, SaaS = solo uso, DBaaS = solo datos.

