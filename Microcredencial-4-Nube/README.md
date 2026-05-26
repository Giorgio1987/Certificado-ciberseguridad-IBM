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

## Módulo 8: Protección de la infraestructura en la nube

### Acerca de este módulo

Libera el poder de la **ciberseguridad en la nube** mientras te adentras en el ámbito de la protección de la infraestructura en la nube y el reforzamiento de tu habilidad digital contra las ciberamenazas.

Tener una infraestructura de nube segura es importante porque más organizaciones están aprovechando los beneficios de la computación en la nube.

Te damos la bienvenida al módulo **Protección de la infraestructura en la nube**.

#### En este módulo aprenderás:

- La importancia de la **seguridad de la infraestructura en la nube** en la ciberseguridad.
- Las posibles **amenazas y vulnerabilidades** que pueden poner en riesgo los entornos y las aplicaciones en la nube.
- Cómo proteger los datos basados en la nube y garantizar su **confidencialidad, integridad y disponibilidad** (tríada CIA).

#### Al final de este módulo podrás:

Mejorar las medidas de ciberseguridad y mantener segura la información confidencial en la nube.

### Objetivos de aprendizaje

Luego de completar este módulo, deberías ser capaz de:

- **Aplicar la gestión de acceso a la identidad** a situaciones del mundo real
- **Aplicar la infraestructura de la nube y los planes de recuperación** a un escenario
- **Crear una máquina virtual segura** con Microsoft Azure
- **Aplicar los principios de la estrategia de seguridad** a las aplicaciones en la nube
- **Resumir los conceptos clave** para proteger los datos, la infraestructura y las aplicaciones en la nube

### Visión general: Seguridad en la nube

#### ¿Por qué es importante la seguridad en la nube?

La computación en la nube ofrece un entorno informático dinámico y flexible, pero también presenta sus propios desafíos de seguridad. Los servicios en la nube son un objetivo tentador para los atacantes maliciosos porque hay muchos datos confidenciales almacenados en la nube.

#### ¿Qué es la seguridad en la nube?

La **seguridad en la nube** es el conjunto de prácticas, tecnologías y políticas diseñadas para hacer que el uso de los servicios en la nube sea más seguro. El objetivo principal es garantizar la **confidencialidad, integridad y disponibilidad** (tríada CIA) de los recursos basados en la nube.

#### Desafíos únicos de la seguridad en la nube

Aunque la computación en la nube enfrenta muchas de las mismas amenazas que un entorno local (on-premise), existen retos únicos:

- **Control de acceso:** la nube permite que múltiples usuarios y aplicaciones desde distintas ubicaciones accedan a recursos compartidos, lo que aumenta el riesgo de acceso no autorizado.
- **Secuestro de cuenta:** los atacantes pueden robar credenciales mediante phishing o ataques de fuerza bruta, obteniendo acceso a una amplia gama de recursos.
- **Protección de datos en múltiples ubicaciones:** es más difícil proteger datos almacenados en varias ubicaciones y datos en tránsito.
- **Escalabilidad:** aumenta el número de usuarios y recursos que pueden conectarse, dificultando la supervisión y seguridad del entorno.
- **Cumplimiento normativo:** los entornos en la nube también deben cumplir regulaciones, estándares de la industria y mejores prácticas.

#### Modelo de responsabilidad compartida

Los **proveedores de servicios en la nube (CSP)** son responsables de:
- Gestionar y mantener la infraestructura física y virtual
- Garantizar la disponibilidad de sus servicios
- Implementar cifrado de datos, seguridad de red, restricciones de acceso y otros controles de seguridad

Sin embargo, la seguridad en la nube es una **responsabilidad compartida** entre:
- El **proveedor de servicios en la nube**
- La **empresa cliente** (debe crear políticas y procedimientos de seguridad sólidos)
- El **usuario de la nube** (debe seguir esas políticas)

> **Conclusión:** Si todos ponen de su parte, la computación en la nube puede seguir siendo una gran opción para un entorno de trabajo flexible, seguro y eficiente.

### Amenazas exclusivas de la computación en la nube

Imagina que estás trabajando para una organización que está estableciendo una oficina en una nueva ubicación. La gerencia está sopesando los pros y los contras de optar por la computación en la nube en lugar de configurar un entorno de TI en el sitio.

En el caso de la computación en la nube, la **multiplicidad de usuarios y aplicaciones** puede dar lugar a las siguientes amenazas:

- **Mayor riesgo de acceso no autorizado**
- **Mayor riesgo de secuestro de cuentas de usuario**
- **Mayor riesgo de ataques de phishing o de fuerza bruta**
- **Dificultad para monitorear y asegurar los datos almacenados en múltiples ubicaciones**
- **Mayor dificultad para el cifrado de datos y las restricciones de acceso**

> **Nota:** Estas amenazas son exclusivas o se ven amplificadas en entornos de nube debido a su naturaleza compartida, la escalabilidad y el acceso desde múltiples ubicaciones.

### Comprender las amenazas de la computación en la nube

Con la computación en la nube, los usuarios pueden crear entornos sin tener que lidiar con los gastos generales de mantener una infraestructura física. Sin embargo, en el mundo empresarial, un **mayor uso de la nube conlleva más amenazas para la seguridad**. Por eso, es esencial comprender e identificar los riesgos de seguridad que conlleva el creciente uso de la tecnología de computación en la nube.

#### Principales amenazas cibernéticas en la nube

- **Identidades mal gestionadas**  
  La mala gestión de usuarios, permisos y credenciales puede dar acceso a personas no autorizadas.

- **Configuración incorrecta de la nube**  
  Configuraciones erróneas (como almacenamiento público accidental) exponen datos sensibles.

- **Denegación del servicio (DoS)**  
  Ataques que saturan los recursos de la nube, dejando los servicios inaccesibles.

- **Amenazas internas**  
  Empleados o colaboradores con acceso legítimo que hacen mal uso de los datos o los exponen.

- **Visibilidad reducida de la infraestructura**  
  Al no controlar físicamente los servidores, es más difícil monitorear y detectar actividades sospechosas.

- **Uso no autorizado de cargas de trabajo en la nube**  
  Recursos de nube (como servidores virtuales) pueden ser secuestrados para actividades maliciosas (minería, ataques).

- **Interfaces de programación de aplicaciones (API) poco seguras**  
  APIs mal protegidas pueden ser explotadas para acceder o manipular datos.

- **Violaciones de cumplimiento**  
  Incumplimiento de normativas (GDPR, HIPAA, PCI-DSS) que puede derivar en multas y sanciones.

  ### Identidades mal gestionadas

Las credenciales de acceso mal utilizadas son ahora la **técnica más utilizada** en las filtraciones de datos. La mayoría de los atacantes apuntan constantemente al directorio de la empresa y a la infraestructura de identidad con un éxito fenomenal.

La identidad es un **objetivo clave** en las redes no seguras. Cuando los atacantes tienen tus credenciales, pueden usarlas para obtener acceso a través de varios sitios.

#### Caso de estudio: Target (2014)

La multinacional minorista Target sufrió una filtración masiva de datos causada por un ciberataque. Los atacantes:

- Accedieron a los sistemas de los puntos de venta de la empresa
- Robaron información de tarjetas de crédito y débito de aproximadamente **40 millones de clientes**
- Emplearon **credenciales robadas a un proveedor** de Target para acceder a la red
- Navegaron hasta el directorio de empleados para obtener credenciales de nivel superior

> **Lección aprendida:** Este ataque es un ejemplo clásico de cómo los atacantes pueden explotar controles de acceso mal configurados e identidades mal gestionadas para obtener acceso no autorizado a datos confidenciales. La filtración de Target puso de relieve la necesidad crítica de aplicar políticas sólidas de **gestión de identidades y accesos**.

#### Recomendaciones para la gestión de identidades

**1. Gobernanza y administración de identidades (IGA)**  
Solución que ayuda a las organizaciones a gestionar el ciclo de vida de la identidad de los usuarios y su acceso a aplicaciones y datos críticos. Proporciona flujos de trabajo **automatizados** para crear, aprobar, modificar y revocar el acceso de los usuarios.

**2. Gestión de accesos privilegiados (PAM)**  
Solución que proporciona acceso **seguro y controlado** a cuentas privilegiadas, como las de los administradores de sistemas, para evitar el acceso no autorizado.

**3. Gestión de derechos de infraestructura en la nube (CIEM)**  
Soluciones que permiten a las organizaciones comprender sus derechos y permisos mediante el análisis y mapeo de todas las identidades, roles, grupos y políticas en **múltiples plataformas en la nube**.

**4. Principio del mínimo privilegio (POLP)**  
Debe aplicarse en todos los entornos, donde los usuarios solo tienen los permisos necesarios para realizar su trabajo **y nada más**.

### Configuración incorrecta de la nube

Las configuraciones incorrectas de la infraestructura en la nube siguen siendo una de las **principales causas** de las violaciones de seguridad de la computación en la nube en todo el mundo.

#### Casos de estudio

**1. Verizon (2021)**  
Aproximadamente **7.5 millones de suscriptores inalámbricos** tuvieron algunos puntos de datos expuestos, incluyendo:
- Qué tipo de dispositivos conectaron al servicio de Verizon
- A qué recompensas se suscribieron
- A qué servicios auxiliares se suscribieron (Apple Music, Disney+, YouTube TV o Verizon Cloud)

> *Fuente: Android Police*

**2. Adobe Creative Cloud (2019)**  
Los datos básicos de los clientes de casi **7.5 millones de usuarios** de Adobe Creative Cloud se expusieron en Internet dentro de una base de datos de Elasticsearch que se dejó conectada en línea **sin contraseña**.

> *Fuente: ZDNet*

#### Problemas de configuración más comunes

- **Buckets de almacenamiento de acceso público**  
  Contenedores de almacenamiento en la nube (como AWS S3) que quedan abiertos a todo Internet.

- **Controles de acceso a recursos inseguros**  
  Permisos mal configurados que permiten accesos no deseados.

- **Credenciales expuestas en repositorios públicos**  
  Contraseñas o claves de API subidas por error a GitHub u otros repositorios públicos.

#### Solución: CSPM (Cloud Security Posture Management)

> **Nota:** La mayoría de las filtraciones en la nube se derivan de **errores de configuración**, por lo que es crucial monitorear constantemente los errores de configuración de la nube.

El **software de gestión de la postura de seguridad en la nube (CSPM)** permite a las organizaciones hacer precisamente eso. En la cumbre de seguridad de Gartner de 2021 se mencionó que la **CSPM es ahora una herramienta obligatoria** para las organizaciones en la nube.

## ¿Qué es una "configuración incorrecta en la nube"?
Es cuando alguien (generalmente un administrador o desarrollador) deja mal configurada alguna opción de seguridad en un servicio de nube. Esto crea un agujero por donde los atacantes pueden colarse o acceder a datos que deberían estar protegidos.

En pocas palabras: Es como dejar la puerta de tu casa abierta o la ventana sin seguro, pero en el mundo digital.

Ejemplos concretos (los más comunes)
1. Bucket de almacenamiento público (el error más famoso)
¿Qué es un bucket? Es como un "cajón" en la nube donde se guardan archivos (AWS S3, Google Cloud Storage, etc.).

El error: Lo configuran como "público" en lugar de "privado". Cualquier persona con el enlace puede ver o descargar todo.

Ejemplo real: Adobe Creative Cloud (2019) dejó una base de datos sin contraseña y expuso 7.5 millones de registros de usuarios.

Analogía: Dejaste un cajón lleno de documentos personales en la vereda con un cartel que dice "MIRÁ LO QUE TENGO".

2. Puertos abiertos innecesarios
¿Qué es? Los servidores tienen "puertos" (como puertas) por donde entran las conexiones.

El error: Dejás abierto un puerto que no debería estar abierto (ej. el puerto 22 de SSH accesible desde todo Internet).

Analogía: Dejaste abierta la puerta de entrada a tu casa, pero también la puerta del sótano que nadie usa, por donde puede entrar cualquiera.

3. Credenciales en repositorios públicos (GitHub)
¿Qué es? Programadores que suben su código a GitHub.

El error: Olvidan sacar las contraseñas o claves de acceso (API keys) del código antes de hacerlo público.

Analogía: Escribiste la clave de tu casa en un papel y lo pegaste en la pared de la plaza.

4. Permisos demasiado amplios
¿Qué es? En la nube se asignan permisos a usuarios o aplicaciones (quién puede hacer qué).

El error: Dar permisos de "administrador total" a alguien que solo necesita leer un archivo.

Analogía: Le das las llaves de todo el edificio al cadete que solo tiene que entregar un paquete en recepción.

¿Por qué pasa tanto?
Causa	Explicación fácil
Complejidad	Las nubes (AWS, Azure, Google) tienen miles de opciones de configuración. Es fácil equivocarse.
Rapidez	Los equipos de TI quieren lanzar rápido y a veces se saltan los controles de seguridad.
Desconocimiento	No todos entienden qué opción es segura y cuál no.
Cambios manuales	Alguien toca una configuración "provisoria" y se olvida de volver a dejarla segura.
¿Cómo se evita?
Herramientas como CSPM (Cloud Security Posture Management) escanean automáticamente tu nube en busca de configuraciones incorrectas y te alertan.

Analogía: Es como tener un inspector de seguridad que camina por tu casa todo el día revisando que todas las puertas y ventanas estén cerradas.

#### ¿Cómo sería una configuración incorrecta en la nube? (Explicación fácil)

Una **configuración incorrecta en la nube** es cuando alguien deja mal configurada una opción de seguridad, creando un agujero por donde los atacantes pueden acceder a datos que deberían estar protegidos.

##### Ejemplos comunes

| Error | ¿Qué pasa? | Analogía |
|-------|------------|----------|
| **Bucket público** | Cualquiera puede ver/descargar archivos | Un cajón con documentos personales en la vereda |
| **Puertos abiertos** | Acceso no deseado al servidor | Una puerta de casa abierta que no debería |
| **Credenciales expuestas** | Contraseñas visibles en Internet | La clave de tu casa pegada en la plaza |
| **Permisos excesivos** | Un usuario puede hacer más de lo que debe | Dar llaves de todo el edificio al cadete |

##### ¿Por qué pasa?
- La nube es compleja (miles de opciones de configuración)
- Se prioriza la rapidez sobre la seguridad
- Falta de conocimiento o errores humanos

##### ¿Cómo se evita?
Con herramientas **CSPM** (Cloud Security Posture Management) que escanean automáticamente las configuraciones y alertan sobre riesgos.

### Denegación de servicio (DoS y DDoS)

Los entornos de la nube son especialmente **vulnerables a los ataques de denegación de servicio (DoS)** y de **denegación distribuida de servicio (DDoS)** debido a la necesidad de conectividad a Internet para acceder a ellos.

#### ¿En qué consisten?

Con DoS y DDoS, los atacantes **inundan la red** de una organización con una gran cantidad de tráfico web, lo que hace que los recursos no estén disponibles para clientes y empleados.

> **Cuanto mayor sea la parte de la infraestructura que reside en la nube, más disruptivo puede ser un ataque DoS.**

#### Caso de estudio: MafiaBoy (2000)

| ¿Quién? | Un hacker de 15 años conocido como **MafiaBoy** |
|---------|-------------------------------------------------|
| **¿Qué hizo?** | Creó una **botnet** infiltrándose en redes informáticas universitarias y las empleó para realizar ataques DDoS |
| **Objetivos** | Dell, E-Trade, eBay y Yahoo! |
| **Repercusiones** | Impacto significativo en la economía y el mercado de valores. Los precios de las acciones de Yahoo! y Amazon cayeron bruscamente. El índice Nasdaq cayó y tardó semanas en recuperarse. |

> **Nota:** Una **botnet** es una red de dispositivos conectados a Internet infectados con malware que permite al atacante controlar los dispositivos de forma remota.

#### Impacto del ataque de MafiaBoy

- Puso de relieve la **vulnerabilidad de la infraestructura de Internet**
- Llevó a un mayor **escrutinio de la seguridad en línea**
- Las empresas invirtieron más recursos en mejorar su **ciberseguridad**
- Los gobiernos promulgaron **nuevas leyes** para combatir los delitos cibernéticos

#### Cómo reducir el riesgo de ataques DoS/DDoS

1. **Restringir el acceso**  
   Restringir el acceso a los puertos, protocolos y servicios de la red para **minimizar la superficie de ataque**.

2. **Limitar los puntos únicos de fallo**  
   Usar **equilibradores de carga** y **redes de entrega de contenido (CDN)**. Una CDN es una red de servidores que distribuye contenido (sitios web, imágenes, videos) a los usuarios según su ubicación geográfica.

3. **Establecer una línea base de tráfico normal**  
   Establecer una línea base para poder detectar cualquier cosa anormal, como un **aumento repentino** en el tráfico de red.

4. **Instalar un firewall**  
   Instalar un **firewall de aplicaciones web (WAF)** para protegerse contra quienes exploten vulnerabilidades conocidas.

#### Ejemplos prácticos de mitigación de DoS/DDoS

**1. Restringir el acceso**  
*Sapphire Emporium* restringe el acceso a su aplicación web limitando el número de solicitudes procedentes de una dirección IP en un intervalo de tiempo determinado.

**2. Instalar un firewall**  
*Law-Tastic* instala un firewall para filtrar y bloquear el tráfico malicioso, protegiendo su red y servidores del acceso no autorizado.

**3. Establecer una línea base de tráfico normal**  
*Virtual Medics* establece una línea base de tráfico normal para su aplicación web mediante datos históricos y tendencias. Usa esta línea base para monitorear el tráfico entrante en busca de anomalías o picos que la excedan.

**4. Limitar los puntos únicos de fallo**  
*ZippyMart* configura varios servidores web para distribuir el tráfico entrante en su sitio. Si un servidor deja de funcionar, los otros servidores web pueden manejar el tráfico sin interrupción.

### Amenazas internas

Un gran porcentaje de las violaciones de seguridad se originan **en el interior de una organización**. Los ataques internos pueden ser:

- **Maliciosos** (empleados descontentos que actúan con intención de dañar)
- **Involuntarios** (errores accidentales, falta de conocimiento)

#### Cómo mitigar las amenazas internas

1. **Capacitación y sensibilización**  
   Garantizar una capacitación adecuada en seguridad para todos los empleados. Es crucial para mitigar los ataques internos.

2. **Principio de privilegio mínimo (POLP)**  
   Seguir este principio al diseñar los controles de acceso de tu entorno para **limitar el daño** que los empleados pueden causar. También crear un **protocolo de baja de personal adecuado** (revocar accesos cuando un empleado se va).

3. **Entorno de trabajo seguro y saludable**  
   Proporcionar un buen ambiente laboral para reducir el riesgo de que un **trabajador descontento** se pase de listo y cause daños.

### Reducción de la visibilidad de la infraestructura

Si una organización emplea un proveedor externo para la informática, está entregando el **control parcial** al proveedor de servicios en la nube (CSP).

#### Ejemplo práctico

Una empresa que emplea **Amazon Web Services (AWS)** para alojar un sitio web cede la responsabilidad de alojamiento a un proveedor de nube externo. Esto significa que el CSP se encarga de:

- Gestión de la infraestructura subyacente
- Mantenimiento
- Seguridad física y virtual

La empresa se centra en el **contenido y la funcionalidad** de su sitio web.

#### El problema

Sin embargo, la empresa debe monitorear completamente la infraestructura de la red para garantizar que sea segura. La organización **no es propietaria de la infraestructura física**, lo que dificulta obtener:

- Visibilidad completa de la infraestructura
- Visibilidad de los usos de los recursos
- Especialmente sin la experiencia técnica adecuada

#### Responsabilidad compartida

La nube opera con **responsabilidad compartida** entre la organización y el CSP:

- El CSP gestiona la **infraestructura física**
- La organización es responsable de garantizar que las **cargas de trabajo de datos y aplicaciones** en la nube permanezcan seguras

> La falta de visibilidad es común en muchos entornos de nube intrincados, lo que los hace **abiertos a filtraciones de datos y amenazas**.

#### Solución: Herramientas de monitoreo de red

Una organización debe monitorear su red con las herramientas de monitoreo adecuadas para que los administradores tengan **visibilidad en tiempo real** del tráfico de red.

**Ejemplos de herramientas de monitoreo de red:**

- **Nagios**
- **SolarWinds Network Performance Monitor**
- **PRTG Network Monitor**
- **Zabbix**

#### Reducción de la visibilidad de la infraestructura (explicación fácil)

##### ¿Cuál es el problema?

Cuando usás la nube, **no sos dueño de los servidores físicos**. Están en centros de datos del proveedor (AWS, Azure, IBM). No podés ver físicamente qué pasa con ese hardware.

##### Analogía: el estacionamiento

Alquilás un auto (tu servicio en la nube), pero el auto está guardado en un estacionamiento de otra empresa. Vos manejás el auto, pero no sabés si el estacionamiento tiene cámaras, guardias o si el techo es seguro. **Eso es falta de visibilidad.**

##### ¿Qué no podés ver?

- El servidor físico real donde corren tus VMs
- Qué otros clientes comparten el mismo hardware
- Las configuraciones internas de red del proveedor
- Los accesos físicos al centro de datos

##### ¿Por qué es riesgoso?

- No podés auditar completamente la seguridad
- Dependés de que el proveedor haga bien su trabajo
- Si el proveedor tiene un error, vos quedás expuesto
- Es más difícil detectar amenazas

##### Solución: herramientas de monitoreo

Usar herramientas que te den visibilidad desde tu lado:

- **Nagios** - monitoreo de servidores
- **SolarWinds** - rendimiento de red
- **PRTG** - tráfico y ancho de banda
- **Zabbix** - monitoreo de infraestructura en nube

### Responsabilidad compartida en la nube

El modelo de **responsabilidad compartida** establece que la seguridad en la nube es una tarea que involucra tanto al **proveedor de servicios en la nube (CSP)** como a la **organización cliente**.

- **El CSP protege:** servidores físicos, infraestructura, red física, hipervisor
- **La organización protege:** cargas de trabajo, datos, aplicaciones, control de accesos (IAM)

#### Ejemplos prácticos

**1. Thermal Oasis**  
*Thermal Oasis* depende de un proveedor de servicios en la nube para almacenar sus datos y proteger el acceso para evitar fugas o filtraciones. Mientras tanto, el CSP asume la responsabilidad de proteger los servidores físicos y la infraestructura donde se almacenan los datos.

> ✅ **Correcto:** Thermal Oasis demuestra el modelo de responsabilidad compartida: el proveedor protege la infraestructura física y la organización asegura sus datos y aplicaciones.

**2. Law-tastic (Sin acceso a infraestructura física)**  
*Law-tastic* almacena datos confidenciales de clientes en su servidor en la nube, pero su servicio actual carece de visibilidad, seguridad y herramientas adecuadas de monitoreo de red.

> ✅ **Correcto:** El servicio de Law-tastic carece de visibilidad porque no tiene acceso a la infraestructura física gestionada por el CSP. Esto dificulta monitorear completamente la infraestructura y el uso de recursos.

**3. Leaf Technologies (Necesidad de herramientas de monitoreo)**  
El departamento de TI de *Leaf Technologies* instala **Nagios**, una herramienta de monitoreo, para rastrear el tráfico de red en tiempo real. Nagios permite al departamento de TI identificar y solucionar problemas de red a medida que surgen, garantizando un tiempo de inactividad mínimo.

> ✅ **Correcto:** Leaf Technologies utiliza Nagios para monitorear el tráfico de red en tiempo real, abordando la necesidad de herramientas de monitoreo para mantener la visibilidad.


### Uso no autorizado de cargas de trabajo en la nube (TI en la sombra)

La mayoría de los principales CSP operan con un modelo de **autoservicio**, lo que facilita a los usuarios el aprovisionamiento y desaprovisionamiento de cargas de trabajo a voluntad según sus necesidades. Sin embargo, esta facilidad de uso también genera **TI en la sombra**.

#### ¿Qué es la TI en la sombra?

La **TI en la sombra** es el uso de soluciones tecnológicas **no autorizadas** en una organización, a menudo fuera del ámbito del departamento de TI.

**Ejemplos comunes:**

- Empleados que usan cuentas personales de almacenamiento en la nube (Dropbox, Google Drive) para almacenar datos de la empresa
- Uso de cuentas de correo electrónico personales para comunicación laboral
- Uso de software o aplicaciones no autorizadas para realizar tareas laborales

#### Problemas que causa la TI en la sombra

- **Mayor riesgo de pérdida y fugas de datos**
- **Costos inesperados** (servicios no controlados que generan gastos)
- **Violaciones de cumplimiento** (normativas como GDPR, HIPAA)

#### Métodos recomendados para mitigar la TI en la sombra

**1. Principio de privilegio mínimo (POLP)**  
Seguir el POLP y solo autorizar la creación de cargas de trabajo para los usuarios que necesiten hacerlo como parte de su trabajo.

**2. Registro de auditoría**  
Configurar registros de auditoría y mecanismos de alerta para rastrear todas las actividades que ocurren en el interior y detectar fácilmente cualquier actividad no autorizada.

#### TI en la sombra (explicación fácil)

##### ¿Qué es?

Es cuando **empleados usan servicios o dispositivos que el departamento de TI no autorizó**. Trabajan "en las sombras", fuera del control de la empresa.

##### Analogía: la cocina de la oficina

Todos deberían usar la heladera y el microondas de la empresa. Pero algunos empleados traen su propia hornito y heladera personal sin avisar. El encargado no sabe qué enchufaron, si es peligroso o si guardan comida en mal estado.

##### Ejemplos comunes

| Lo que hace el empleado | El riesgo |
|------------------------|-----------|
| Guarda archivos de trabajo en su Dropbox personal | Si hackean su cuenta, se filtran datos de la empresa |
| Usa su correo personal de Gmail para trabajar | La empresa no tiene auditoría de esos correos |
| Instala software no autorizado | Puede traer virus o generar costos ocultos |
| Sube datos internos a ChatGPT u otra IA | La empresa no sabe qué hace esa IA con los datos |

##### ¿Por qué pasa?

- El proceso oficial de TI es lento
- Les resulta más cómodo o familiar
- No saben los riesgos
- Las herramientas oficiales a veces son malas

##### Problemas que causa

- Filtración de datos
- Gastos inesperados
- Multas por incumplir leyes

##### Soluciones

1. **POLP:** solo los empleados que realmente necesitan crear recursos tienen permiso
2. **Registros de auditoría:** todo queda registrado, saltan alertas si alguien crea algo sin autorización
3. **Capacitación:** explicar los riesgos a los empleados
4. **Dar buenas herramientas oficiales:** para que no busquen alternativas por su cuenta


### Interfaces de programación de aplicaciones (API) poco seguras

Una empresa puede tener un control estricto dentro de su infraestructura, pero las **API inseguras** pueden debilitar las defensas del entorno y crear una entrada para atacantes.

#### ¿Qué es una API?

Una **interfaz de programación de aplicaciones (API)** es un grupo de rutinas, protocolos y herramientas para crear aplicaciones de software. Las API especifican cómo deben interactuar los componentes de software, permitiendo la comunicación entre diferentes sistemas, aplicaciones y servicios.

> **Analogía:** Una API es como un **mesero en un restaurante**. Vos (aplicación) le pedís algo al mesero (API), y él se lo comunica a la cocina (otro sistema). Si el mesero no verifica quién sos, cualquiera puede pedir comida sin pagar.

#### Problemas de seguridad de las API

Muchas API tienen sus propias vulnerabilidades de seguridad que, cuando se explotan, pueden poner en riesgo un entorno de nube. Los atacantes pueden usar una API que **no tenga mecanismos de autenticación adecuados** para robar o manipular datos.

#### Caso de estudio: Filtración de datos de Google+ (2018)

Una vulnerabilidad en la **API de Google+** permitió a desarrolladores externos acceder a datos de los usuarios, incluyendo:

- Nombres
- Direcciones de correo electrónico
- Ocupaciones
- Edades

> Esta fue una de las mayores filtraciones de datos involucrando a una API insegura.

#### Cómo mitigar amenazas de API poco seguras

El equipo de TI debe:

1. **Verificar todas las aplicaciones externas** que cualquier equipo planea usar
2. **Estar al tanto de los riesgos** antes de la implementación
3. **Atender las actualizaciones de seguridad** y los **parches de aplicaciones** de manera oportuna

### Violaciones de cumplimiento

Las organizaciones deben cumplir con **múltiples regulaciones** dependiendo de sus operaciones geográficas y tipo de industria. Con la aparición de nuevas regulaciones y las más antiguas que se actualizan a medida que cambia el panorama, puede ser un desafío para las organizaciones mantenerse al día.

#### Responsabilidad de la organización

Las organizaciones deben asegurarse de que su **proveedor de nube (CSP) permita el cumplimiento** de las regulaciones necesarias. No todos los CSP cumplen con todas las normativas (GDPR, HIPAA, PCI-DSS, etc.).

#### Mejor práctica: Cumplimiento continuo

El **cumplimiento continuo de la nube** es la mejor solución para los problemas normativos. Las organizaciones deben:

- Monitorear constantemente su estado de cumplimiento en la nube
- **No esperar hasta la temporada de auditorías** para verificar el cumplimiento

> Realizar la **debida diligencia** al principio del proceso mitiga los **altos costos del incumplimiento** (multas, sanciones, pérdida de reputación).

### Defensa proactiva y holística

Ninguna de estas amenazas es nueva, pero el **panorama cambiante** y la **transición a la nube** requieren un enfoque diferente en comparación con las cargas de trabajo locales del pasado.

#### Beneficios de ser proactivo

Ser **proactivo** (actuar antes de que ocurra un incidente) en lugar de reactivo (actuar después del incidente):

- Evita problemas **mayores y más costosos**
- Ayuda a las organizaciones a **construir su reputación** (confianza de clientes y socios)
- Permite a los empleados **enfocarse en tareas que agregan valor** al negocio, en lugar de apagar incendios constantemente

> **En resumen:** La defensa proactiva implica anticiparse a las amenazas, monitorear continuamente y corregir vulnerabilidades antes de que sean explotadas. Un enfoque **holístico** considera la seguridad en todas las capas: identidades, configuraciones, redes, aplicaciones, datos y cumplimiento.

### Aspecto destacado de la gestión profesional: analista de seguridad en la nube

¿Te parece emocionante combatir las amenazas de la nube como carrera? Si es así, considera una carrera como **analista de seguridad en la nube**.

#### ¿Qué hace un analista de seguridad en la nube?

Los analistas de seguridad en la nube garantizan la seguridad de los **sistemas y datos basados en la nube**. Sus responsabilidades incluyen:

- Evaluar los **posibles riesgos de seguridad** y desarrollar planes para mitigarlos
- **Monitorear los sistemas** en busca de accesos no autorizados o violaciones
- **Implementar controles y procedimientos de seguridad** para protegerse contra amenazas
- **Mantenerse al día** con las últimas tendencias y tecnologías de seguridad para mejorar continuamente la postura de seguridad del entorno de nube de la organización

#### Pasos para convertirte en analista de seguridad en la nube

**1. Obtener un título relevante**  
Título en ciencias de la computación, ciberseguridad o un campo relacionado. Estos títulos proporcionan los conocimientos y habilidades fundamentales necesarios.

**2. Obtener experiencia laboral**  
Buscar pasantías, trabajos a tiempo parcial u oportunidades de voluntariado para obtener experiencia práctica en seguridad en la nube. Esto ayuda a desarrollar habilidades prácticas y comprender mejor la industria.

**3. Certificarse**  
Obtener certificaciones relevantes como:
- **CCSP** (Certified Cloud Security Professional)
- **CISSP** (Certified Information Systems Security Professional)
- **CompTIA Cloud+**

> Estas certificaciones demuestran tu experiencia en seguridad en la nube y pueden ayudarte a impresionar a posibles empleadores.

**4. Mantenerse al día**  
Mantenerse al tanto de las tendencias de la industria, nuevas tecnologías y amenazas emergentes leyendo publicaciones de la industria y asistiendo a conferencias y sesiones de capacitación.

**5. Crear una red de contactos (Networking)**  
Establecer relaciones con profesionales de la industria, asistir a eventos de networking y unirse a organizaciones profesionales relevantes. La creación de redes puede ayudarte a obtener información sobre la industria y generar oportunidades laborales.

### Acerca de esta lección: Seguridad de la infraestructura en la nube

La seguridad de la infraestructura en la nube es como un **juego de ajedrez**: debes planear y ejecutar cuidadosamente cada movimiento para proteger al **rey (los datos)** de los ataques del oponente **(hacker)**. La mejor defensa es una combinación de **posicionamiento estratégico** y **medidas proactivas**.

A medida que las organizaciones migran más recursos a la nube, deben incorporar **herramientas de seguridad basadas en la nube** como parte de su infraestructura.

#### Medidas de seguridad esenciales

- **Red** (firewalls, segmentación, control de tráfico)
- **Cifrado** (datos en reposo y en tránsito)
- **Copias de seguridad de datos** (recuperación ante desastres)
- **Contraseñas seguras** (políticas de autenticación robustas)
- **Monitoreo continuo** (detección de anomalías en tiempo real)

En esta lección, explorarás algunas **herramientas adicionales** para proteger la **superficie de ataque más amplia** que crea un entorno de nube.

### Modelos de responsabilidad de seguridad

Dependiendo del tipo de servicio en la nube (IaaS, PaaS, SaaS), la responsabilidad de la seguridad se divide de manera diferente entre el cliente y el proveedor.

#### Responsabilidades según el modelo de servicio

| Capa | IaaS | PaaS | SaaS |
|------|------|------|------|
| Configuración de la aplicación | Cliente | Cliente | Proveedor |
| Controles de identidad y acceso | Cliente | Cliente | Compartida |
| Almacenamiento de datos de aplicaciones | Cliente | Cliente | Proveedor |
| Aplicación | Cliente | Cliente | Proveedor |
| Sistema operativo | Cliente | Proveedor | Proveedor |
| Controles de flujo de red | Cliente | Compartida | Proveedor |
| Infraestructura de host | Proveedor | Proveedor | Proveedor |
| Seguridad física | Proveedor | Proveedor | Proveedor |

#### Niveles de responsabilidad

- **El cliente es predominantemente responsable de la seguridad** → IaaS (la mayor parte recae en el cliente)
- **Tanto el cliente como el servicio en la nube tienen responsabilidades de seguridad** → PaaS (responsabilidad compartida)
- **El servicio en la nube es totalmente responsable de la seguridad** → SaaS (el cliente solo configura y usa)

> **Recuerda:** En todos los modelos, el cliente siempre es responsable de sus **datos**, la **gestión de identidades (IAM)** y la **configuración de usuarios**.

### Protección de la infraestructura en la nube: IAM, DLP y Cloud DR

Ahora que entiendes el **modelo de responsabilidad compartida**, vamos a explorar herramientas adicionales que pueden asegurar la mayor superficie de ataque que crea un entorno en la nube.

#### 1. IAM (Gestión de acceso a la identidad)

La **gestión de acceso a la identidad (IAM)** implica gestionar las identidades de los usuarios y controlar su acceso a aplicaciones, redes y otros recursos.

La IAM incluye el modelo **IAAA**:

- **Identificación:** quién dice ser el usuario (ej. nombre de usuario)
- **Autenticación:** probar que es quien dice ser (ej. contraseña, MFA)
- **Autorización:** qué recursos puede acceder (ej. permisos, roles)
- **Contabilidad (Accounting):** registrar lo que hace (ej. logs, auditoría)

#### 2. DLP (Prevención de pérdida de datos)

La **prevención de pérdida de datos (DLP)** es un conjunto de herramientas y procesos que ayudan a las organizaciones a proteger la información confidencial de la divulgación o el uso no autorizados mediante la **detección y prevención de filtraciones de datos en tiempo real**.

**Ejemplos de lo que DLP puede prevenir:**
- Un empleado que intenta enviar un archivo con datos de clientes a su correo personal
- Alguien que copia información sensible a un USB no autorizado
- Datos que se suben accidentalmente a un bucket público

#### 3. Cloud DR (Recuperación ante desastres en la nube)

La **recuperación ante desastres en la nube (Cloud DR)** es un servicio que permite a las organizaciones **replicar y recuperar** sus aplicaciones y datos críticos en la nube en caso de una interrupción o desastre de TI (ciberataque, incendio, fallo de hardware, etc.).

**Beneficios del Cloud DR:**
- Garantiza la **continuidad del negocio**
- **Minimiza el tiempo de inactividad**
- Permite recuperar sistemas rápidamente desde cualquier lugar

> **Analogía del Cloud DR:** Es como tener un **seguro + una copia de las llaves guardada en casa de un vecino**. Si tu casa se inunda, podés ir al vecino y seguir operando mientras reparás la tuya.

### Gestión de acceso a identidades (IAM)

Los clientes de los proveedores de servicios en la nube son responsables de **proteger sus cuentas de usuario** y gestionar el acceso de los usuarios a los datos confidenciales.

#### Diferencia entre entorno local y nube

- **Entorno local tradicional:** los administradores protegen solo los recursos y usuarios dentro de las paredes de su negocio.
- **Computación en la nube:** amplía la oportunidad para que usuarios globales accedan a los recursos, pero también **amplía las vulnerabilidades**. Esto hace que la gestión de cuentas de usuario y la seguridad de los datos sean aún más críticas.

#### Ejemplo cotidiano de IAM

Cuando compras una aplicación, descargas música o ves una película de Netflix, el acceso al contenido se gestiona verificando tu identidad a través de contraseñas, códigos de acceso, PIN y otras formas de verificación.

#### Beneficios de IAM

**1. Proteger los datos confidenciales**  
IAM es fundamental para cualquier infraestructura de nube nativa o híbrida porque ayuda a las organizaciones a proteger los datos confidenciales, reducir el riesgo de acceso no autorizado y cumplir con las regulaciones de privacidad.

**2. Desplegar protocolos de aplicación basados en políticas**  
Según IBM, *"las herramientas y servicios de IAM permiten a las empresas desplegar protocolos de aplicación basados en políticas para todos los usuarios que intentan acceder a servicios tanto locales como basados en la nube. La funcionalidad principal de IAM es crear identidades digitales para todos los usuarios para que puedan ser monitoreados y restringidos activamente, cuando sea necesario, durante todas las interacciones de datos"*.

**3. Proteger los activos de información**  
Las soluciones de IAM ayudan a las organizaciones a proteger los activos de información controlando:
- **Quién** puede acceder a qué sistemas
- **Cuándo** pueden acceder a ellos
- **Qué** pueden hacer mientras están conectados

> Solo las personas autorizadas pueden realizar ciertas operaciones en sistemas protegidos sin comprometer la seguridad.

#### IAM en la práctica: Sector salud

Las organizaciones de atención médica usan IAM para asegurar el acceso a los **registros médicos electrónicos (EMR)** de los pacientes.

**El proceso de IAM incluye:**

1. **Autenticación:** el sistema solicita a cada proveedor de atención médica que proporcione sus credenciales únicas (nombre de usuario y contraseña).
2. **Autorización:** luego de autenticar, el sistema verifica sus derechos de acceso y les otorga acceso **solo a los EMR** de los pacientes que están autorizados a ver.
3. **Cumplimiento:** este proceso garantiza que las organizaciones de atención médica mantengan el cumplimiento de los requisitos normativos y protejan la privacidad de los datos de los pacientes.

### Prevención de pérdida de datos (DLP)

#### ¿Qué es la pérdida de datos?

La **pérdida de datos** es otro término para una **filtración de datos**, que ocurre cuando el robo o la fuga de datos expone información confidencial a personas no autorizadas.

Independientemente de los controles que uses para proteger la confidencialidad de los datos, el objetivo sigue siendo el mismo: **evitar la pérdida de datos**.

La **prevención de pérdida de datos (DLP)** es la capacidad de una organización para **detectar y prevenir** la pérdida de datos.

#### Escenario práctico: Institución financiera

El equipo de seguridad de TI de una institución financiera implementó la tecnología DLP para evitar que los **datos confidenciales de los clientes** salgan de la red de la organización.

**Configuración del sistema DLP:**
- Monitorear todo el **tráfico de correo electrónico saliente**
- Buscar datos confidenciales (números de Seguro Social, información de tarjetas de crédito)

**Lo que sucedió:**
Un día, el sistema DLP alertó al equipo de TI de que un empleado intentó enviar por correo una hoja de cálculo que contenía una gran cantidad de números de cuenta de clientes a una dirección **externa**.

**Resultado:**
El equipo de TI investigó de inmediato y descubrió que el empleado **no sabía** que enviar la hoja de cálculo por correo violaba la política de la empresa.

> Con las soluciones DLP, las empresas pueden crear **políticas** que definan qué tipos de datos son confidenciales.

#### Estrategias de DLP

**1. Definir el uso de datos**  
Las empresas pueden emplear soluciones DLP para establecer políticas que definan **cómo acceder y usar** estos datos. También pueden monitorear las actividades de los usuarios para garantizar el cumplimiento de estas políticas.

**2. Usar el cifrado**  
Las soluciones DLP incluyen tecnologías de cifrado para garantizar que la información personal **no se envíe en texto plano** a través de una red.

**3. Usar análisis de comportamiento impulsados por IA**  
Los sistemas DLP pueden incluir análisis de comportamiento que detectan actividades sospechosas como:
- Intentos de acceder a varias cuentas o dispositivos a la vez
- Un patrón inusual de solicitudes de datos

### Microsoft Azure

Las organizaciones tienen muchos proveedores de servicios en la nube para elegir. Algunos de los proveedores más populares incluyen:

- **Amazon Web Services (AWS)**
- **Google Cloud Platform (GCP)**
- **Microsoft Azure**

En esta lección, exploraremos **Microsoft Azure**.

#### ¿Qué es Microsoft Azure?

**Microsoft Azure** ofrece una amplia gama de servicios y herramientas para crear, desplegar y gestionar aplicaciones y servicios a través de centros de datos gestionados por Microsoft.

#### Características de seguridad de Azure

MS Azure proporciona varias características que las organizaciones pueden usar para mejorar la seguridad de su infraestructura en la nube:

| Característica | ¿Qué hace? |
|----------------|-------------|
| **Gestión de identidad y acceso** | Controla quién puede acceder a qué recursos (Azure AD, MFA) |
| **Seguridad de la red** | Firewalls, grupos de seguridad de red (NSG), redes virtuales (VNet) |
| **Cifrado de datos** | Protege datos en reposo y en tránsito (Azure Key Vault) |
| **Detección y monitoreo de amenazas** | Azure Security Center, Sentinel (SIEM) |
| **Cumplimiento y gobernanza** | Azure Policy, Blueprints, cumplimiento normativo (GDPR, HIPAA, etc.) |
| **Protección DDoS** | Protección contra ataques de denegación de servicio distribuido |

> Estas funciones pueden ayudar a las organizaciones a **reforzar su postura de seguridad** en la nube, protegiendo sus aplicaciones, datos e infraestructura de posibles amenazas y vulnerabilidades.

### Microsoft Azure: Portal y conceptos básicos

El portal de Azure se puede acceder en **[portal.azure.com](https://portal.azure.com)**.

#### Interfaz principal

El portal muestra:
- **Azure services:** Create a resource, Resource groups, Subscriptions, Microsoft Defender for Cloud, Virtual machines, Storage accounts, SQL databases, etc.
- **Resources:** Recursos recientes y favoritos (nombre, tipo, última vista)
- **Navigate:** Subscriptions, Resource groups, All resources, Dashboard

#### Suscripciones

Necesitas una **suscripción** para gestionar y organizar los recursos de Azure. La suscripción tiene un costo asociado.

#### Grupos de recursos (Resource Groups)

Un **grupo de recursos** es un contenedor lógico que organiza recursos relacionados (máquinas virtuales, cuentas de almacenamiento, redes, etc.) en una sola unidad.

**Beneficios de los grupos de recursos:**
- Organizan todos los recursos de una solución
- Permiten gestionar recursos como un grupo
- Cada organización decide cómo asignarlos según sus necesidades

#### Creación de un grupo de recursos (pasos básicos)

1. **Project details**
   - **Subscription:** seleccionar la suscripción (ej. Azure subscription 1)
   - **Resource group:** nombre del grupo (ej. Nexusfields)

2. **Resource details**
   - **Region:** seleccionar ubicación del centro de datos (ej. (US) East US)

3. **Revisar y crear (Review + create)** - validar la configuración y crear el grupo

> **Ejemplo del curso:** Asmarina guía la creación de un grupo llamado **Nexusfields**.

### Microsoft Azure: Creación de grupo de recursos y máquina virtual

#### Paso 1: Crear un grupo de recursos

Una vez completados los datos del grupo de recursos, Azure valida la configuración.

**Validación exitosa:** aparece el mensaje "Validation passed".

**Configuración típica:**
- **Subscription:** Azure subscription 1
- **Resource group:** Nexusfields
- **Region:** East US

**Opciones disponibles:**
- Review + create (Revisar y crear)
- Download a template for automation (Descargar plantilla para automatización)

> Al seleccionar **Create (Crear)** , Azure crea el grupo de recursos.

#### Paso 2: Ver el grupo de recursos creado

En la página **Resource groups** se puede ver:

- Lista de grupos de recursos con su nombre, suscripción y ubicación
- Opciones: Create, Manage view, Refresh, Export to CSV, Assign tags

**Ejemplo:** Nexusfields - Azure subscription 1 - East US

#### Paso 3: Navegar al inicio (Home)

Una vez creado el grupo, se regresa a la página de inicio del portal de Azure para continuar con la siguiente tarea.

#### Paso 4: Crear una máquina virtual

**¿Qué es una máquina virtual? (recordatorio)**

Una **máquina virtual (VM)** es un software que se comporta como una computadora física separada con:
- Su propio **sistema operativo (SO)**
- **Programas** y aplicaciones
- **Almacenamiento**
- **Conexiones a redes**

Muchas máquinas virtuales pueden funcionar juntas en un **mismo servidor físico**.

**Desde el portal de Azure:**
1. En la página de inicio, seleccionar **Virtual machines** (Máquinas virtuales)
2. Allí se podrá crear y configurar una nueva VM dentro del grupo de recursos Nexusfields

### Microsoft Azure: Creación de una máquina virtual

#### Pantalla principal de Máquinas Virtuales

En la página **Virtual machines** se pueden:
- **Crear** nuevas máquinas virtuales (Linux o Windows)
- **Ver** todas las VM existentes
- **Gestionar** VM (Iniciar, reiniciar, detener, eliminar)
- Cambiar entre vista clásica o moderna

> Si no hay VM creadas, se muestra el mensaje: *"No virtual machines to display"*

**Opciones disponibles:** Create, Switch to classic, Reservations, Manage view, Refresh, Export to CSV, Open query, Assign tags, Start, Restart, Stop, Delete.

#### Crear una nueva máquina virtual

**Paso 1: Acceder a creación**
- En la página de Virtual machines, seleccionar **Create** → **Azure virtual machine**

**Paso 2: Configurar pestaña Basics (Datos básicos)**

**Project details (Detalles del proyecto):**
- **Subscription:** Azure subscription 1
- **Resource group:** Nexusfields (o crear uno nuevo)

**Instance details (Detalles de la instancia):**
- **Virtual machine name:** nombre de la VM (ej. **VM Linux** o **LinuxVM1**)
- **Region:** (US) East US (ubicación del centro de datos)
- **Availability options:** opciones de disponibilidad

**Pestañas adicionales de configuración:**
- **Basics** → Datos básicos (suscripción, grupo, nombre, región)
- **Disks** → Discos (tamaño y tipo de almacenamiento)
- **Networking** → Redes (VNet, subred, IP pública, NSG)
- **Management** → Gestión (monitoreo, backups, actualizaciones)
- **Monitoring** → Monitoreo (alertas, diagnóstico)
- **Advanced** → Opciones avanzadas (extensiones, scripts)
- **Tags** → Etiquetas para organización
- **Review + create** → Revisar y crear la VM

> **Nota:** Se puede completar solo la pestaña Basics y luego usar **Review + create** para crear la VM con parámetros predeterminados, o revisar cada pestaña para una personalización completa.

**Ejemplo del curso:** Nexusfields necesita una **VM Linux**. Se asigna el nombre **LinuxVM1** y se continúa con la configuración.

#### Ejercicio de repaso: Selección de discos en Azure

**Pregunta:**  
Asmarina necesita elegir una opción de almacenamiento para copias de seguridad y datos no críticos, como archivos de proyectos archivados e informes antiguos. ¿Qué opción debería seleccionar?

- [ ] Ultra Disk
- [x] **Standard HDD**
- [ ] Standard SSD
- [ ] Premium SSD

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Standard HDD**. Es la opción más económica y adecuada para datos no críticos como copias de seguridad, archivos archivados e informes antiguos. Los discos Premium SSD o Ultra Disk están diseñados para cargas de trabajo de alto rendimiento y tienen un costo mayor.
</details>

### Microsoft Azure: Cifrado de discos y gestión de claves

#### Configuración de discos en Azure

En el panel **Disks** (Discos) se configura el disco duro virtual de la VM:

- **OS disk size:** tamaño del disco del sistema operativo (ej. 30 GiB)
- **OS disk type:** tipo de disco (Standard HDD, Standard SSD, Premium SSD)
- **Delete with VM:** si el disco se elimina junto con la VM
- **Key management:** gestión de claves de cifrado
- **Enable Ultra Disk compatibility:** habilitar discos Ultra (alto rendimiento)

#### Cifrado de discos en Azure

Azure disk storage encryption **cifra automáticamente** los datos almacenados en discos gestionados (disco OS y discos de datos) en reposo por defecto.

#### Opciones de gestión de claves (Key management)

| Tipo de clave | ¿Qué es? | ¿Quién la gestiona? | ¿Cuándo usarla? |
|---------------|----------|---------------------|-----------------|
| **Platform-managed key (PMK)** | Clave de cifrado gestionada completamente por Azure | Azure | La mayoría de los casos, cuando no se requiere control específico sobre las claves |
| **Customer-managed key (CMK)** | Clave de cifrado que el cliente importa desde otra ubicación | El cliente (debe importar, gestionar y almacenar la clave) | Requisitos normativos estrictos o necesidad de control total sobre las claves |

> **Ejemplo del curso:** Nexusfields no tiene el tiempo ni la necesidad de gestionar la clave de cifrado, por lo que **PMK (Platform-managed key)** es la mejor opción.

#### Resumen

- **PMK:** Azure gestiona todo el ciclo de vida de las claves. Es más simple y recomendada para la mayoría de los escenarios.
- **CMK:** El cliente importa sus propias claves (ej. desde AWS, on-premise o un HSM) y es responsable de su gestión. Ofrece mayor control pero requiere más administración.

### Microsoft Azure: Despliegue completado y recursos creados

#### Finalización del despliegue

Una vez completada la configuración de la VM, Azure procede al despliegue. Al finalizar, se muestra la pantalla **"Your deployment is complete"**.

**Detalles del despliegue:**
- **Deployment name:** nombre del despliegue (ej. CreateVm-canonical...)
- **Subscription:** Azure subscription 1
- **Resource group:** Nexusfields

**Opciones post-despliegue:**
- **Cost Management:** configurar alertas de costos para evitar cargos inesperados
- **Microsoft Defender for Cloud:** asegurar aplicaciones e infraestructura
- **Free Microsoft tutorials:** acceder a tutoriales gratuitos de Azure

#### Recursos creados

En la página de inicio o en **Resources** (Recursos) aparecen los elementos creados recientemente:

| Nombre | Tipo | Última vista |
|--------|------|---------------|
| **LinuxVM1** | Virtual machine | Hace 2 minutos |
| **Nexusfields** | Resource group | Hace 2 minutos |

#### Próximo paso: Proteger la VM

Una vez creada la VM, se pueden tomar medidas adicionales para protegerla, como usar **Microsoft Defender for Cloud**, la herramienta de seguridad integrada de Microsoft Azure.

> **Microsoft Defender for Cloud** permite:
> - Monitorear la postura de seguridad
> - Detectar amenazas y vulnerabilidades
> - Recibir recomendaciones de seguridad
> - Proteger cargas de trabajo en la nube


### Microsoft Defender for Cloud y Firewall Manager

#### Microsoft Defender for Cloud - Overview

**Microsoft Defender for Cloud** es la herramienta de seguridad integrada de Microsoft Azure. Proporciona:

- **Overview:** resumen general de la postura de seguridad
- **Recommendations:** recomendaciones de seguridad clasificadas por gravedad
- **Security alerts:** alertas de seguridad activas
- **Inventory:** inventario de recursos
- **Cloud Security Explorer:** consultas de seguridad personalizables

#### Recommendations (Recomendaciones)

El panel **Recommendations** muestra las recomendaciones de seguridad proporcionadas por Microsoft Defender for Cloud, clasificadas de mayor a menor gravedad:

- **High** (Alta): 4/11
- **Medium** (Media): 1/5
- **Low** (Baja): 0/3

> La columna **Status** (Estado) muestra si las tareas se completaron o no se asignaron. Las tareas no asignadas se enumeran como recursos incorrectos (Unhealthy).

#### Cloud Security Explorer

El panel **Cloud Security Explorer** permite realizar consultas relacionadas con la seguridad. **Ejemplos de plantillas de consulta:**

| Consulta | ¿Qué busca? |
|----------|-------------|
| *Internet exposed VMs with high severity vulnerabilities* | VMs expuestas a Internet con vulnerabilidades de alta gravedad |
| *Internet exposed VMs with low severity vulnerabilities* | VMs expuestas a Internet con vulnerabilidades de baja gravedad |
| *User accounts without MFA and with permissions to Storage Accounts* | Cuentas de usuario sin MFA con permisos en cuentas de almacenamiento |
| *User accounts with permission to vulnerable VMs* | Cuentas de usuario con permiso para acceder a VMs vulnerables |

#### Firewall Manager

El panel **Firewall Manager** muestra un resumen de las opciones de firewall disponibles o activas:

- **Virtual hub security coverage** (cobertura de seguridad del hub virtual)
- **Virtual network firewall security coverage** (cobertura de firewall de red virtual)
- **Virtual network DDoS security coverage** (cobertura de protección DDoS)

**Para crear un firewall:** se deben ver las **Azure Firewall policies** (pólizas de firewall de Azure) primero.

> **Nota:** Azure Firewall es un servicio de seguridad de red que protege las redes virtuales de Azure filtrando el tráfico entrante y saliente.

### Microsoft Azure: Creación de una política de firewall (Firewall Policy)

#### Acceso a Azure Firewall Policies

Desde **Firewall Manager**, se puede acceder a **Azure Firewall Policies** en el panel de seguridad (Security). Aquí se definen las reglas para el filtrado de tráfico en múltiples instancias de Azure Firewall.

#### Crear una política de firewall

Seleccionar **Create Azure Firewall Policy** para comenzar.

#### Configuración de la política (pestaña Basics)

**Project details:**
- **Subscription:** Azure subscription 1
- **Resource group:** Nexusfields (o el grupo creado)

**Policy details:**
- **Name:** nombre de la política (ej. **Firewall1** o **Firewall11**)
  - Debe comenzar con letra o número
  - Entre 1 y 80 caracteres
  - Puede contener letras, números, guiones bajos, puntos o guiones
- **Region:** East US (o la región correspondiente)

#### Política heredada (Parent policy)

- La política hija hereda todas las colecciones de reglas de la política padre seleccionada
- Las reglas heredadas tienen prioridad sobre las reglas definidas en la política nueva
- **Parent policy:** se puede seleccionar "None" si no se necesita heredar

#### Niveles de política (Policy tier)

| Nivel | Características | Costo | Uso típico |
|-------|----------------|------|------------|
| **Basic** | Funcionalidades básicas, soporte limitado | Más bajo | Pequeñas empresas, desarrollo, pruebas |
| **Standard** | Funcionalidades completas, soporte estándar | Medio | Producción general |
| **Premium** | Funcionalidades avanzadas, TLS inspección, IDPS | Más alto | Entornos críticos, alta seguridad |

> **Ejemplo del curso:** Nexusfields ha aprobado solo el nivel más básico → se selecciona **Basic**.

**Opciones adicionales:**
- **DNS Settings:** configuración de DNS (siguiente pestaña)
- **Download a template for automation:** descargar plantilla para automatización

Una vez completada la configuración básica, se selecciona **Review + create** para crear la política de firewall.

#### ¿Por qué usar VM + Firewall juntos? ¿No alcanza con aislar?

**Aislar** (el aislamiento natural de Azure) evita que otras máquinas virtuales accedan a la tuya sin permiso. Pero **no protege contra atacantes de Internet**.

**El firewall** filtra todo el tráfico que entra y sale de la VM:
- Bloquea puertos innecesarios
- Permite solo IPs autorizadas
- Detecta y bloquea tráfico malicioso (DDoS, fuerza bruta)
- Registra intentos de acceso

> **Analogía:** El aislamiento es tener paredes y un portón. El firewall es tener un guardia de seguridad que revisa a cada persona que quiere entrar o salir. Se necesitan ambos porque las amenazas pueden venir de vecinos (otras VMs) O de extraños (Internet).

**Caso concreto:** Sin firewall, cualquiera en Internet puede intentar conectarse a tu VM LinuxVM1 por SSH (puerto 22) y probar contraseñas. Con firewall, solo permites conexiones desde tu IP, bloqueando al resto del mundo.

#### ¿Por qué crear la VM en Azure y no en mi PC local?

**Tu PC local (VirtualBox/VMware):**
- La VM solo corre cuando tu PC está encendida
- Solo vos podés acceder (y desde tu casa)
- Limitada por los recursos de tu PC (RAM, CPU, disco)
- Sin herramientas de seguridad empresariales (Defender, Firewall avanzado)

**Microsoft Azure (la nube):**
- La VM corre 24/7 aunque apagues tu PC
- Podés acceder desde cualquier lugar con Internet
- Escalable: cambiás de tamaño con un clic
- Herramientas profesionales: Microsoft Defender for Cloud, Azure Firewall, IAM, DDoS protection
- Backups automáticos y recuperación ante desastres

> **El curso usa Azure porque:** enseña seguridad en la nube real, con herramientas que usan las empresas (no solo virtualización básica). La experiencia con Azure es más valorada en el currículum que solo VirtualBox.

**Conclusión:** Aprendé virtualización en tu PC local. Aprendé **seguridad empresarial en la nube** con Azure.

#### ¿Microsoft Azure es pago?

**Respuesta corta:** Depende, pero se puede usar gratis.

**Opciones gratuitas:**
- **Cuenta gratuita:** $200 USD de crédito por 30 días
- **Servicios siempre gratis:** VM B1s (750 horas/mes), almacenamiento limitado, etc.
- **Créditos para estudiantes:** $100 USD (con correo .edu)

**Recomendación para el curso:**
1. Creá una cuenta gratuita de Azure
2. Usá el crédito de $200 USD para las prácticas
3. **Eliminá o detené las VM** cuando termines de usarlas
4. Configurá alertas de costo para evitar sorpresas

> **Importante:** Si no activás el pago por uso o eliminás los recursos, **no te cobran**.

### Recuperación ante desastres en la nube (Cloud DR)

A pesar de implementar medidas preventivas tanto para las infraestructuras locales como para las basadas en la nube, las organizaciones aún pueden experimentar **filtraciones de datos e interrupciones disruptivas**.

Las empresas deben reaccionar rápidamente a las vulnerabilidades recién descubiertas o a las interrupciones del sistema para garantizar la **continuidad del negocio** y la **disponibilidad de los datos**.

#### ¿Qué es la recuperación ante desastres en la nube?

Las soluciones de **recuperación ante desastres (DR)** son cruciales para la seguridad en la nube, ya que equipan a las organizaciones con las herramientas, los servicios y los protocolos necesarios para:

- **Acelerar la recuperación de datos**
- **Restaurar las operaciones comerciales normales**

#### Caso de estudio: Interrupción de AWS (febrero de 2017)

Uno de los desastres en la nube más significativos que requirió una solución de recuperación ante desastres fue la interrupción de **Amazon Web Services (AWS)**.

| Hecho | Detalle |
|-------|---------|
| **1. Sitios web populares dejaron de estar disponibles** | La interrupción provocó que muchos sitios web y servicios populares dejaran de funcionar |
| **2. Muchas organizaciones sintieron el impacto** | Entre las afectadas: empresas de medios, agencias gubernamentales, Netflix, Slack y GitHub |
| **3. Servicio restaurado** | AWS restauró el servicio luego de aproximadamente **4 horas** |

#### Lección aprendida

El incidente destacó la **importancia de contar con soluciones de recuperación ante desastres** para mitigar el impacto de tales incidentes en las operaciones comerciales.

> **Conclusión:** No basta con prevenir. Hay que estar preparados para **responder y recuperarse rápidamente** cuando ocurre un desastre (caída del proveedor, ciberataque, fallo de hardware, desastre natural).

### Estrategia integral de copia de seguridad y replicación

Una estrategia completa de **copia de seguridad y replicación** es una de las consideraciones más importantes para la **recuperación ante desastres** en una infraestructura basada en la nube.

#### Mejores prácticas para copias de seguridad

**1. Múltiples copias en diferentes regiones**  
Es esencial tener varias copias de seguridad ubicadas en **diferentes regiones geográficas** y almacenadas con **otros proveedores de almacenamiento**. Esta estrategia garantiza que los datos estén siempre disponibles, aunque uno de los proveedores sufra una interrupción.

**2. Cifrado de datos**  
Es esencial asegurarse de que los conjuntos de datos estén correctamente **cifrados y protegidos**:
- **En reposo:** cuando están almacenados
- **En tránsito:** cuando se mueven entre sistemas

> Esto evita el acceso no autorizado a información confidencial o actividades maliciosas, como **ataques de ransomware**.

**3. Seguimiento y auditorías**  
Es una buena práctica:
- Realizar un seguimiento de los **inicios de sesión** y los **registros de acceso**
- Realizar **auditorías de seguridad periódicas** para identificar posibles vulnerabilidades

#### Recuperación ante desastres como servicio (DRaaS)

Las organizaciones deben considerar el uso de soluciones **automatizadas** de recuperación ante desastres, como la **recuperación ante desastres como servicio (DRaaS)** basada en la nube.

**Beneficios de DRaaS:**

| Beneficio | Descripción |
|-----------|-------------|
| **Escalabilidad bajo demanda** | Se ajusta automáticamente a las necesidades de la organización |
| **Ahorro de costos** | Comparado con procesos manuales de DR |
| **Tiempos rápidos de recuperación** | Garantiza que las empresas puedan reanudar operaciones rápidamente luego de un evento inesperado |

#### Características clave de una solución DR

- **Cloud backup:** copias de seguridad en la nube
- **Instant recovery:** recuperación instantánea
- **End-to-end encryption:** cifrado de extremo a extremo

> **En resumen:** Una buena estrategia de respaldo no solo guarda copias, sino que las distribuye, las cifra, las audita y permite recuperarlas rápidamente mediante automatización.

### Aspecto destacado de la gestión profesional: certificación CompTIA Cloud+

#### Habilidades de gestión profesional

¿Estás interesado en la **seguridad de la infraestructura en la nube**? ¿Te emociona la idea de gestionar y mantener la seguridad en la nube y luchar contra los hackers? Si es así, deberías considerar una carrera en **seguridad de infraestructura en la nube**.

Una forma de asegurar un puesto en este campo es obtener la certificación **Cloud+ de CompTIA**.

#### ¿Qué es la certificación CompTIA Cloud+?

> *"Es una certificación global que valida las habilidades necesarias para **implementar y automatizar entornos de nube seguros** que soporten la alta disponibilidad de sistemas y datos empresariales."*

#### Áreas que evalúa la certificación

- **Arquitectura y diseño de la nube**
- **Seguridad en la nube**
- **Despliegue en la nube**
- **Operaciones y soporte**
- **Solución de problemas**

#### Carreras que benefician con esta certificación

Esta certificación sería una excelente adición al currículo de alguien que busca ingresar a las siguientes carreras:

- **Ingeniero en la nube**
- **Especialista en la nube**
- **Gestor de proyectos en la nube**
- **Ingeniero de redes**
- **Especialista en seguridad en la nube**

### Acerca de esta lección: Seguridad de aplicaciones en la nube

Proteger las aplicaciones basadas en la nube es como **proteger tu casa del cielo**: no puedes controlar el clima, pero puedes asegurarte de que el techo sea lo suficientemente fuerte como para resistir cualquier tormenta.

#### ¿Qué aprenderás en esta lección?

En esta lección, aprenderás sobre la **seguridad de las aplicaciones en la nube**, que implica proteger las aplicaciones de software que se ejecutan en la infraestructura de la nube.

Explorarás:

- **Cuatro principios** de una estrategia de seguridad en la nube
- Varias **soluciones de seguridad de aplicaciones en la nube**

### Aplicaciones en la nube

Una amplia gama de aplicaciones en la nube puede permitir a las empresas lograr una mayor **agilidad**, **escalabilidad** y **eficiencia** en sus operaciones.

#### ¿Qué es una aplicación en la nube?

Una **aplicación en la nube** es un tipo de aplicación de software que se ejecuta en la infraestructura de la nube. Los usuarios pueden acceder y operar aplicaciones en la nube **completamente en línea** sin instalar software o hardware en una computadora local.

#### Proveedores de servicios en la nube (CSP)

Entre los proveedores típicos se incluyen:

- **IBM**
- **Amazon Web Services (AWS)**
- **Microsoft Azure**
- **Google Cloud Platform (GCP)**

#### Características de las aplicaciones en la nube

Los desarrolladores diseñan aplicaciones en la nube para que sean:

- **Altamente escalables**
- **Flexibles**
- **Accesibles desde cualquier dispositivo** con conexión a Internet

**Dispositivos de acceso:** computadoras de escritorio, portátiles, tabletas y teléfonos móviles (a través de navegador web o aplicación).

#### Ejemplos de servicios ofrecidos

| Categoría | Ejemplos |
|-----------|----------|
| **Almacenamiento de datos** | Box, OneDrive, Dropbox |
| **Suites de productividad** | Google Workspace, Microsoft Office 365 |
| **Herramientas de colaboración** | Slack, Teams, Trello |
| **Plataformas CRM** | Salesforce Sales Cloud |
| **Software de contabilidad** | QuickBooks Online, Wave Accounting, Quicken Online |

#### Aplicaciones populares en la nube

**Microsoft Office 365**  
Colección de aplicaciones basadas en la nube útiles en el hogar y la oficina, que incluyen correo electrónico, creación y colaboración de documentos y videoconferencias.

**Slack**  
Plataforma de mensajería y colaboración basada en la nube. Los equipos pueden comunicarse y colaborar en tiempo real.

**Salesforce Sales Cloud**  
Plataforma de gestión de relaciones con los clientes (CRM) basada en la nube. Las empresas la usan para gestionar sus procesos de ventas e interacciones con los clientes.

**QuickBooks Online**  
Software de contabilidad basado en la nube. Las pequeñas y medianas empresas pueden gestionar sus finanzas desde cualquier lugar.

> **Piensa en esto:** Probablemente uses al menos algunos de estos servicios en tu vida diaria (trabajo, escuela, hobbies, etc.). Puedes almacenar, compartir y acceder a archivos desde cualquier lugar mediante estas plataformas.

### Estrategia de seguridad de aplicaciones en la nube

El creciente uso de aplicaciones en la nube significa que una organización debe tener una **estrategia de seguridad de las aplicaciones en la nube**.

#### ¿Qué es la seguridad de aplicaciones en la nube?

Garantizar la seguridad de las aplicaciones de software basadas en la nube durante todo su **ciclo de vida de desarrollo** se conoce como seguridad de las aplicaciones en la nube.

Implica el uso de:
- **Políticas** a nivel de aplicación
- **Herramientas** de seguridad
- **Tecnologías** de protección
- **Protocolos** de comunicación

**Objetivos:**
- Mantener una **visibilidad completa** de todos los recursos basados en la nube
- **Defenderse contra los ciberataques**
- **Restringir el acceso** únicamente a los usuarios autorizados

> Las aplicaciones en la nube son vulnerables a amenazas y ataques, al igual que los sistemas locales.

#### Principios de la estrategia de seguridad en la nube

---

### 1. Centrarse en el adversario

**¿Qué significa?**  
Comprender las **motivaciones, tácticas y técnicas** de los posibles atacantes para diseñar e implementar medidas de seguridad eficaces.

**Implica:**
- Adoptar un enfoque **proactivo** (no solo reaccionar después del ataque)
- Mantenerse al día con las **amenazas emergentes** y técnicas de ataque
- Comprender las últimas **tendencias de seguridad** y mejores prácticas
- **Probar y refinar continuamente** las medidas de seguridad

> **En resumen:** Pensar como un atacante para anticiparse a sus movimientos.

---

### 2. Reducir el riesgo de exposición

**¿Qué significa?**  
Minimizar el riesgo de que **usuarios no autorizados** tengan acceso a datos o infraestructura.

**Medidas para mitigar riesgos:**

| Medida | ¿Qué hace? |
|--------|------------|
| **Implementar controles de acceso** | Limita quién puede entrar y qué puede ver/hacer |
| **Aplicar cifrado** | Protege datos incluso si son interceptados |
| **Realizar evaluaciones de seguridad periódicas** | Identifica vulnerabilidades antes de que sean explotadas |
| **Emplear medidas de detección y respuesta a amenazas** | Detecta y actúa ante incidentes en tiempo real |
| **Aplicar políticas de seguridad** | Establece reglas claras para todos los usuarios |

---

### 3. Implementar una política, un marco y una arquitectura de seguridad en la nube

**¿Qué significa?**  
Un enfoque **holístico** para proteger los recursos, datos y cargas de trabajo de la nube.

**Tres componentes clave:**

| Componente | Descripción |
|------------|-------------|
| **Política** | Reglas, directrices y normas de acceso, uso y gestión de los recursos de la nube |
| **Marco (Framework)** | Enfoque estructurado para desarrollar, desplegar y mantener aplicaciones e infraestructuras seguras en la nube |
| **Arquitectura** | Diseño e implementación de controles de seguridad para proteger aplicaciones y sistemas en la nube |

---

### 4. Monitoreo de la superficie de ataque

**¿Qué significa?**  
Evaluar periódicamente las **posibles vulnerabilidades** y los **puntos de entrada** que los atacantes pueden aprovechar para comprometer los recursos de la nube.

**Cómo se hace:**
- **Herramientas automatizadas** (escaneo continuo)
- **Revisiones manuales** (expertos en seguridad)

**Beneficios del monitoreo proactivo:**
- Identificar **riesgos potenciales**
- Implementar medidas de seguridad **antes de un ataque**
- Reducir la **exposición a los ataques**

> **En resumen:** Conocer las propias debilidades antes de que las encuentre un atacante.

#### Ejercicio: Aplicar los principios de seguridad a We Invest

**Principio 1 - Centrarse en el adversario (enfoque proactivo)**
- [x] Capacitar a empleados para reconocer y denunciar amenazas
- [x] Analizar inteligencia de amenazas (motivaciones, tácticas, técnicas)

**Principio 2 - Reducir el riesgo de exposición**
- [x] Implementar autenticación multifactor (MFA)
- [x] Implementar monitoreo continuo para detectar actividades sospechosas

**Principio 3 - Política, marco y arquitectura (enfoque holístico)**
- [x] Utilizar mejores prácticas de la industria para guiar políticas y marcos
- [x] Implementar arquitectura de seguridad con controles diseñados

**Principio 4 - Monitoreo de la superficie de ataque**
- [x] Realizar evaluaciones periódicas de vulnerabilidades y pruebas de penetración
- [x] Implementar monitoreo continuo para detectar accesos no autorizados

### Soluciones de seguridad de aplicaciones en la nube

A medida que más organizaciones adoptan la nube, particularmente en el contexto del desarrollo de software, deben establecer e implementar una **solución completa de seguridad en la nube** para protegerse contra un número creciente de amenazas y ataques.

Las soluciones de seguridad, como las siguientes, son vitales para proteger una infraestructura de aplicaciones en la nube a lo largo de un **ciclo de vida del software**:

- **CNAPP** (Cloud-Native Application Protection Platform)
- **CASB** (Cloud Access Security Broker)
- **CSPM** (Cloud Security Posture Management)

---

### 1. CNAPP (Plataforma de protección de aplicaciones nativa de la nube)

#### ¿Qué es?

Una **CNAPP** es una solución de seguridad para proteger las **aplicaciones nativas de la nube**. Proporciona protección y visibilidad integrales para aplicaciones creadas con:

- **Microservicios** (arquitectura donde un sistema se divide en componentes pequeños e independientes que se comunican vía API)
- **Contenedores**
- Otras tecnologías nativas de la nube

> *"La protección de las aplicaciones nativas de la nube implica un conjunto continuo de procesos centrados en identificar, acceder, priorizar y adaptar al riesgo en las aplicaciones, la infraestructura y la configuración nativas de la nube."*

#### Características de CNAPP

| Característica | ¿Qué hace? |
|----------------|------------|
| **Gestión de vulnerabilidades** | Escanea aplicaciones en busca de vulnerabilidades y brinda recomendaciones para remediarlas antes de que sean explotadas |
| **Segmentación de la red** | Aísla aplicaciones, servicios y datos en entornos multinube y de nube híbrida |
| **Protección en tiempo de ejecución** | Monitorea el entorno para detectar y responder a malware, ataques DDoS y exploits de bases de datos |
| **Seguridad de API** | Protege las API aplicando políticas de limitación de velocidad, autenticación, cifrado y protección DDoS |

---

### 2. CASB (Cloud Access Security Broker)

#### ¿Qué es?

Un **CASB** actúa como un **firewall para los servicios en la nube**, proporcionando una puerta de enlace para hacer cumplir las políticas de seguridad. Actúa como un **guardián** entre los usuarios y los proveedores de servicios en la nube, permitiendo a las organizaciones extender sus políticas de seguridad más allá de su entorno de TI y hacia la nube.

#### Cuatro objetivos principales de CASB

| Objetivo | Descripción |
|----------|-------------|
| **Visibilidad** | Analiza y correlaciona actividades, eventos y registros de usuarios de varios servicios en la nube |
| **Cumplimiento** | Ayuda a cumplir con regulaciones (GDPR, HIPAA, PCI DSS) mediante DLP, cifrado y control de acceso |
| **Seguridad de datos** | Protege datos confidenciales con cifrado, tokenización y prevención de pérdida de datos |
| **Protección frente a amenazas** | Protege contra malware, ransomware y ataques de phishing |

---

### 3. CSPM (Gestión de la postura de seguridad en la nube)

#### ¿Qué es?

El **CSPM** es un componente crítico que ayuda a las organizaciones a identificar y mitigar posibles riesgos de seguridad mediante:

- **Automatización avanzada**
- **Supervisión** continua
- **Técnicas de detección de amenazas**

#### Ejemplo práctico de CSPM

Una organización despliega una nueva aplicación en la nube. Las herramientas CSPM escanean la aplicación y su infraestructura en busca de **errores de configuración o vulnerabilidades**.

**Caso concreto:** Una herramienta CSPM detecta que una base de datos crítica se expuso inadvertidamente a Internet debido a una regla de control de acceso incorrecta. Alerta al equipo de seguridad, que soluciona rápidamente la configuración errónea restringiendo el acceso.

> Así se evitan accesos no autorizados y posibles filtraciones de datos.

#### Capacidades de CSPM

| Capacidad | Descripción |
|-----------|-------------|
| **Monitoreo continuo del cumplimiento** | Verifica automáticamente el cumplimiento de estándares regulatorios y de la industria |
| **Supervisión de la configuración de seguridad** | Identifica errores comunes como puertos abiertos, protocolos no seguros y datos no cifrados |
| **Gestión de la seguridad multinube** | Proporciona gestión unificada en múltiples proveedores de nube (AWS, Azure, GCP) |
| **Evaluación y priorización de riesgos** | Evalúa riesgos según su impacto potencial en la continuidad del negocio |
| **Sugerencias de remediación y automatización** | Ofrece sugerencias de mitigación y puede automatizar el proceso según la gravedad de la vulnerabilidad |

#### ¿En qué entornos funciona CSPM?

Las herramientas CSPM pueden buscar configuraciones erróneas en múltiples entornos:

- **IaaS** (Infraestructura como Servicio)
- **SaaS** (Software como Servicio)
- **PaaS** (Plataforma como Servicio)

> **En resumen:** CSPM actúa como un **inspector continuo** que revisa automáticamente que todo esté bien configurado y seguro, antes de que ocurra un problema.

### Actividad: Resumir los conceptos clave para proteger las aplicaciones en la nube

#### Habilidades para la inserción laboral
- **Agilidad en el aprendizaje**
- **Comunicación escrita**

Ahora que examinaste los conceptos clave para proteger las aplicaciones en la nube, aplicarás estos conceptos a las situaciones de dos empresas:

- **Everwell** (proveedor de atención médica)
- **Nexus Marketplace** (empresa de comercio electrónico)

---

### Escenario 1: Everwell

**Contexto:**  
Eres el director de seguridad de la información de **Everwell**, un gran proveedor de atención médica. Everwell ha migrado recientemente a un sistema basado en la nube para mantener **registros médicos electrónicos (EMR)** . Estás considerando implementar un **Cloud Access Security Broker (CASB)** para protegerte mejor contra las violaciones de datos y las violaciones de cumplimiento.

**¿Por qué CASB es adecuado para Everwell?**

| Necesidad de Everwell | Cómo ayuda CASB |
|----------------------|-----------------|
| **Datos sensibles de salud (PHI)** | Aplica cifrado, tokenización y prevención de pérdida de datos (DLP) |
| **Cumplimiento normativo (HIPAA)** | Ayuda a cumplir regulaciones mediante políticas de control de acceso y monitoreo |
| **Visibilidad del uso de la nube** | Analiza actividades y registros de usuarios en servicios en la nube |
| **Protección contra amenazas** | Protege contra malware, ransomware y ataques de phishing |

> **Conclusión para Everwell:** Un CASB es ideal para Everwell porque actúa como un guardián entre los usuarios y los servicios en la nube, asegurando que los datos médicos confidenciales se mantengan seguros y cumpliendo con normativas como HIPAA.

---

### Escenario 2: Nexus Marketplace

**Contexto:**  
Eres el director de seguridad de la información de **Nexus Marketplace**, una empresa de comercio electrónico. Nexus Marketplace ha migrado recientemente a un **entorno multinube** (múltiples proveedores como AWS, Azure, GCP) para servir mejor a sus clientes en todo el mundo. Debido a la mayor complejidad, la empresa está considerando implementar una herramienta de **Gestión de la Postura de Seguridad en la Nube (CSPM)**.

#### ¿Cómo puede ayudar CSPM a Nexus Marketplace?

**Resumen (2-3 puntos clave):**

1. **Monitoreo continuo de configuraciones en múltiples nubes**  
   CSPM escanea automáticamente los entornos de AWS, Azure y GCP en busca de **errores de configuración** (puertos abiertos, datos no cifrados, permisos incorrectos) que podrían exponer datos de clientes o transacciones.

2. **Cumplimiento y evaluación de riesgos**  
   CSPM verifica el cumplimiento de estándares como **PCI DSS** (requerido para procesar pagos con tarjeta) y prioriza los riesgos según su impacto potencial en el negocio.

3. **Automatización de remediación**  
   Cuando CSPM detecta una vulnerabilidad o mala configuración, puede **alertar al equipo de seguridad** y, en algunos casos, **corregir automáticamente** el problema antes de que sea explotado por atacantes.

> **Conclusión para Nexus Marketplace:** CSPM es esencial para un entorno multinube porque proporciona una **vista unificada** de la seguridad a través de diferentes proveedores, identifica configuraciones erróneas y ayuda a mantener un cumplimiento consistente, reduciendo la complejidad operativa.

---

### Resumen de conceptos aplicados

| Solución | Mejor para | Función principal |
|----------|------------|-------------------|
| **CASB** | Organizaciones con datos sensibles y requisitos de cumplimiento (Everwell) | Guardián entre usuarios y servicios en la nube, aplica políticas de seguridad |
| **CSPM** | Entornos multinube y configuraciones complejas (Nexus Marketplace) | Monitoreo continuo, detección de configuraciones erróneas, cumplimiento |
| **CNAPP** | Aplicaciones nativas de la nube (con microservicios, contenedores) | Protección integral durante todo el ciclo de vida de la aplicación |

¿Qué son CASB, CSPM y CNAPP? (Explicación fácil)
Primero, la analogía de la casa con alarma
Imaginá que tu empresa es una casa y los datos son lo que hay adentro.

Concepto	Analogía
El proveedor de nube (Azure, AWS)	Es el terreno y la estructura de la casa. Ellos ponen las paredes, el techo, las cañerías.
Tu empresa	Es el dueño que vive en la casa. Ponés los muebles, los electrodomésticos, y decidís quién entra.
CASB, CSPM, CNAPP	Son como empresas de seguridad externas que contratás para que vigilen tu casa.
¿Son software? ¿Vienen con la nube? ¿Hay que instalarlos?
Respuesta corta:
Pregunta	Respuesta
¿Son software?	Sí, son programas/plataformas de software.
¿Vienen incluidos con Azure/AWS?	Algunas funciones básicas sí, pero las herramientas completas suelen ser servicios adicionales (pagados o con capas gratuitas).
¿Hay que instalarlos?	No se "instalan" como un programa en tu PC. Se activan o contratan dentro de la nube (como un servicio más).
Explicación de cada uno con ejemplos concretos
1. CASB (Cloud Access Security Broker) - "El portero"
¿Qué hace?
Controla quién se conecta a tus servicios en la nube y qué hace. Es como un portero que revisa a todos los que entran y salen de tu edificio.

¿Cómo funciona?
Se conecta entre tus usuarios y tus servicios en la nube (Office 365, Dropbox, Salesforce, etc.). Todo el tráfico pasa por él.

Ejemplo concreto:

Un empleado intenta descargar un archivo con datos de pacientes desde su casa.

El CASB detecta que ese archivo es confidencial y bloquea la descarga o envía una alerta.

¿Viene con Azure?
Microsoft tiene Microsoft Defender for Cloud Apps (que es un CASB). Hay que activarlo desde el portal de Azure (no viene "prendido" por defecto).

2. CSPM (Cloud Security Posture Management) - "El inspector de obra"
¿Qué hace?
Revisa cómo están configurados tus recursos en la nube. Busca errores como "dejé un bucket público" o "no tengo cifrado activado".

¿Cómo funciona?
Es un software que escanea automáticamente tu nube (AWS, Azure, GCP) y te dice: "Acá hay un problema, arreglalo".

Ejemplo concreto:

Un administrador crea una base de datos y sin querer la deja pública (cualquiera en Internet puede verla).

El CSPM detecta eso en minutos y te envía una alerta: "¡Cuidado! Base de datos expuesta".

¿Viene con Azure?
Microsoft Defender for Cloud incluye funciones de CSPM. Hay que activarlo (tiene una capa gratuita básica y una versión paga con más funciones).

3. CNAPP (Cloud-Native Application Protection Platform) - "El todoterreno"
¿Qué hace?
Es como CASB + CSPM + más cosas (protección de contenedores, microservicios, etc.). Es una solución todo en uno para proteger aplicaciones modernas.

¿Cómo funciona?
Unifica varias herramientas en una sola plataforma.

Ejemplo concreto:

Tenés una aplicación hecha con microservicios (muchos pedacitos chiquitos que hablan entre sí).

CNAPP protege desde el código (cuando lo escribís) hasta la infraestructura (donde corre).

¿Viene con Azure?
Partes de CNAPP están en Microsoft Defender for Cloud (Defender para contenedores, para bases de datos, etc.). Se activa desde el portal.

Entonces... ¿cómo se "instalan"?
Paso	Qué hacés
1. Entrás al portal de Azure (portal.azure.com)	Como cuando creaste la VM
2. Buscás "Microsoft Defender for Cloud"	Es el nombre que usa Azure para estas herramientas
3. Lo activás	A veces con un botón "Enable" o "Upgrade"
4. Configurás qué querés monitorear	Elegís qué recursos (VMs, bases de datos, etc.)
No es como instalar Word o Photoshop. Es como contratar un servicio: das unos clics, y Azure empieza a monitorear por vos.

¿Cuestan plata?
Herramienta	En Azure
CSPM básico	Gratis (Microsoft Defender for Cloud - capa gratuita)
CSPM completo + CASB + CNAPP	Pago (por recurso o por hora)
Para aprender y practicar: la capa gratuita de Defender for Cloud es suficiente. Te muestra recomendaciones básicas.

### ¿Cómo funcionan CASB, CSPM y CNAPP? (Explicación fácil)

#### ¿Son software? ¿Se instalan?

- **Son software**, pero no se "instalan" como un programa en tu PC.
- Se **activan o contratan** como servicios dentro de la nube (Azure, AWS).
- Se configuran desde el portal de nube (como cuando creaste la VM).

#### ¿Vienen con la nube?

- **Algunas funciones básicas vienen incluidas** (ej. CSPM gratuito en Azure).
- Las **funciones completas son adicionales** (plan pago).

#### ¿Cómo funcionan?

| Herramienta | Analogía | ¿Qué hace? |
|-------------|----------|------------|
| **CASB** | El portero | Controla quién entra/sale y qué hace en la nube |
| **CSPM** | El inspector de obra | Revisa configuraciones (cifrado, accesos, puertos) |
| **CNAPP** | El todoterreno | Hace todo lo anterior + protege aplicaciones modernas |

#### En Azure se llaman:

- **Microsoft Defender for Cloud** (incluye CSPM + partes de CASB y CNAPP)
- **Microsoft Defender for Cloud Apps** (el CASB completo)

#### ¿Cómo se activa?

1. Vas al portal de Azure
2. Buscás "Microsoft Defender for Cloud"
3. Lo activás (la capa gratuita alcanza para aprender)
4. Azure empieza a monitorear tus recursos automáticamente


### ¿Debo elegir CASB, CSPM o CNAPP? ¿O puedo elegir solo el "todoterreno"?

**Respuesta corta:** Podés elegir CNAPP si querés, pero depende de tu caso.

#### ¿Qué conviene según el escenario?

| Escenario | Recomendación |
|-----------|---------------|
| **Usás solo Azure** | Usá **Microsoft Defender for Cloud** (ya incluye CSPM + partes de CNAPP). Es gratis (básico) o con plan pago. |
| **Usás varias nubes (AWS + Azure + GCP)** | Considerá un **CNAPP multinube** externo (Wiz, Orca, Prisma Cloud) |
| **Solo te importa controlar qué apps usan tus empleados** | Alcanza con un **CASB** |
| **Solo te importa configuraciones (buckets públicos, puertos abiertos)** | Alcanza con un **CSPM** |

#### En tu curso (usando Azure):

**No necesitas decidir nada.** Usá **Microsoft Defender for Cloud** (ya lo tenés en tu suscripción de Azure). Te da:
- Monitoreo básico de configuraciones (CSPM)
- Recomendaciones de seguridad
- Alertas de amenazas

> **Regla general:** Si podés pagarlo y usás varias nubes, CNAPP es la mejor opción (hace todo). Si sos chico o usás una sola nube, las herramientas nativas del proveedor son suficientes.

## Resumen y perspectivas

En esta lección, aprendiste sobre las **aplicaciones en la nube** y las **estrategias y soluciones de seguridad** para protegerlas.

Debido a que las aplicaciones en la nube se ejecutan en la nube, las organizaciones deben emplear soluciones basadas en la nube para garantizar su seguridad. También aprendiste la importancia de desarrollar una **estrategia de seguridad de aplicaciones en la nube**.

Algunas de las soluciones de seguridad de aplicaciones en la nube más importantes incluyen:

- **CNAPP** (Plataformas de protección de aplicaciones nativas de la nube)
- **CASB** (Agentes de seguridad de acceso a la nube)
- **CSPM** (Gestión de la postura de seguridad en la nube)

---

### Puntos para recordar - Conceptos clave

1. La computación en la nube puede plantear importantes **amenazas de ciberseguridad** a las empresas, y es necesario adoptar medidas **proactivas** para mitigar los riesgos.

2. Las **principales ciberamenazas** de computación en la nube incluyen:
   - Identidades mal gestionadas
   - Mala configuración de la nube
   - Denegación del servicio (DoS/DDoS)
   - Amenazas de usuarios internos
   - Visibilidad reducida de la infraestructura
   - Uso no autorizado de cargas de trabajo en la nube (TI en la sombra)
   - API poco seguras
   - Violaciones de cumplimiento

3. Las organizaciones pueden implementar las siguientes medidas para **gestionar y gobernar identidades y derechos**:
   - **IGA** (Gobernanza y administración de identidades)
   - **PAM** (Gestión de acceso privilegiado)
   - **CIEM** (Gestión de derechos de infraestructura en la nube)
   - **POLP** (Principio de privilegios mínimos)

4. Las organizaciones deben monitorear la **configuración incorrecta de la nube** de manera consistente, y el software **CSPM** les ayuda a hacerlo.

5. La **seguridad de la red** incluye dos categorías: local y basada en la nube.

6. La informática empresarial tradicional implica **servidores locales** y soporte de TI especializado.

7. Los **principales proveedores de la nube** se encargan del mantenimiento, las copias de seguridad y las actualizaciones de software.

8. Las **cinco mejores prácticas** para la seguridad en la nube incluyen:
   - Cifrado del tráfico
   - Planificación de copias de seguridad de datos
   - Supervisión del entorno en la nube
   - Mejora de la seguridad de la cuenta de usuario
   - Evaluación de la postura de seguridad en la nube

9. La responsabilidad de la seguridad informática se **comparte** entre el cliente de la nube y el proveedor en la nube pública.

10. Las organizaciones deben consultar sobre:
    - Medidas de seguridad de los proveedores de nube
    - Ubicaciones de los servidores
    - Protocolos de incidentes
    - Planes de recuperación ante desastres
    - Protección de acceso
    - Soporte técnico
    - Resultados de pruebas de penetración
    - Cifrado de datos
    - Licencias de acceso a los datos
    - Métodos de autenticación
    - Soporte de cumplimiento

11. Las soluciones **IAM**, la **capacitación en ciberseguridad** y una sólida **seguridad de punto final** son esenciales para proteger los recursos de la nube.

12. Las **aplicaciones en la nube** se ejecutan en una infraestructura en la nube y se accede a ellas totalmente en línea.

13. Las aplicaciones en la nube pueden proporcionar: almacenamiento de datos, productividad, herramientas de colaboración, CRM y software de contabilidad.

14. Una **estrategia integral de seguridad en la nube** debe:
    - Centrarse en el adversario
    - Reducir el riesgo de exposición
    - Implementar una política, marco y arquitectura de seguridad
    - Monitorear la superficie de ataque

15. **CNAPP** y **CASB** son dos soluciones que proporcionan políticas y controles de seguridad para aplicaciones basadas en la nube.

---

### Grandes ideas - Habilidades practicadas

Además, exploraste o practicaste estas habilidades:

| Habilidad | Aplicación |
|-----------|-------------|
| **Habilidades de empleabilidad** | Atención al detalle |
| **Pensamiento analítico** | Comunicación escrita |
| **Pensamiento analítico** | Enumerar amenazas exclusivas de la computación en nube |
| **Atención al detalle** | Distinguir entre tipos de mitigación para ataques DoS/DDoS |
| **Mentalidad de crecimiento** | Identificar desafíos de visibilidad de infraestructura |
| **Investigación** | Reflexionar sobre pasos para ser analista de seguridad en la nube |
| **Pensamiento crítico** | Describir la TI en la sombra |
| **Resolución de problemas** | Aplicar IAM a situaciones reales |
| **Atención al detalle** | Crear una VM segura con Microsoft Azure |
| **Agilidad de aprendizaje** | Aplicar principios de estrategia de seguridad |
| **Pensamiento crítico** | Enumerar efectos de interrupción del servicio en la nube |
| **Comunicación escrita** | Aplicar planes de recuperación e infraestructura |
| **Adaptabilidad y resiliencia** | Reflexionar sobre habilidades para certificación CompTIA Cloud+ |

---

### Objetivos de aprendizaje - Módulo 8 completado

Ahora que has completado este módulo, deberías poder:

- ✅ **Aplicar la gestión de acceso a la identidad** a situaciones del mundo real
- ✅ **Aplicar la infraestructura de la nube y los planes de recuperación** a un escenario
- ✅ **Crear una máquina virtual segura** empleando Microsoft Azure
- ✅ **Aplicar los principios de la estrategia de seguridad** a las aplicaciones en la nube
- ✅ **Resumir los conceptos clave** para proteger los datos, la infraestructura y las aplicaciones en la nube

---

### Explora más recursos

Para explorar los conceptos cubiertos en este módulo con más profundidad, consulta estos recursos:

- **[Creación de un espacio de trabajo digital seguro y accesible con IBM Cloud Virtual Private Cloud](https://www.ibm.com)** (video) - Teck Wei Ting, jefe de operaciones técnicas de Inspire-Tech, analiza los beneficios de crear un espacio de trabajo digital seguro.

- **[Soluciones de seguridad en la nube](https://www.ibm.com)** (artículo) - Cómo pasar con confianza a una multinube híbrida e integrar la seguridad en cada fase.

- **[¿Qué es la seguridad en la nube?](https://www.ibm.com)** (artículo) - Explica varios aspectos de la seguridad en la nube, incluidos su importancia y desafíos.

- **[Arquitectura de referencia técnica de seguridad en la nube de CISA](https://www.cisa.gov)** - Enfoque de arquitectura de referencia técnica (TRA) para la migración a la nube y la protección de datos.

---

### Referencias del módulo

**Lección 1: Amenazas en la nube**

1. Plachkinova, Miloslava, and Maurer, Chris. *Teaching Case: Security Breach at Target*. Journal of Information Systems Education, 2018.

2. Wang, Jules. *Data breach exposed millions of Verizon customers' account info*. Android Police, 6 de marzo de 2023.

3. Cimpanu, Catalin. *Adobe left 7.5 million Creative Cloud user records exposed online*. ZDNET, 26 de octubre de 2019.

**Lección 2: Seguridad de la infraestructura en la nube**

1. *Cloud security guidance*. National Cyber Security Centre (Reino Unido), consultado el 26 de junio de 2024.

2. *What is cloud security?*. IBM, consultado el 26 de junio de 2024.

3. *CompTIA Cloud+ certification*. CompTIA, consultado el 26 de junio de 2024.

**Lección 3: Seguridad de aplicaciones en la nube**

1. Alvarenga, Gui. *Cloud application security*. CrowdStrike, 18 de octubre de 2022.

2. *CSPM Meaning: Understanding the Distinctions: CNAPP vs CSPM vs CWPP*. Uptycs, 23 de marzo de 2021.


#### Ejercicio de repaso: Limitar la superficie de ataque contra DDoS

**Pregunta:**  
Imagina que eres el director de TI de una empresa llamada NoAlphabet, y tus recursos basados en la nube están actualmente bajo un ataque DDoS que causa una interrupción significativa del servicio.

¿Qué estrategia limitaría la **superficie de ataque** que está disponible para un ataque distribuido de denegación de servicio?

- [ ] Establecer una línea base de tráfico normal
- [x] **Restringir el acceso a los puertos, protocolos y servicios de red**
- [ ] Usar equilibradores de carga y redes de entrega de contenido (CDN)
- [ ] Instalar un firewall de aplicaciones web (WAF)

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Restringir el acceso a los puertos, protocolos y servicios de red**. Esta estrategia reduce la superficie de ataque eliminando puntos de entrada innecesarios. Las otras opciones son medidas complementarias (detección, distribución de tráfico, filtrado) pero no reducen directamente la superficie de ataque.

</details>

#### Ejercicio de repaso: Estrategia para disponibilidad de datos

**Pregunta:**  
Luego de un ciberataque a MarketU, su plataforma basada en la nube experimentó una interrupción disruptiva. Como parte del proceso de recuperación, ¿qué estrategia priorizarías para **garantizar la disponibilidad de los datos incluso si otro proveedor experimenta una interrupción**?

- [ ] Externalizar todas las responsabilidades de ciberseguridad al proveedor de la nube
- [ ] Instalar software antivirus adicional e iniciar un plan de respuesta
- [x] **Establecer varias copias de seguridad ubicadas en diferentes regiones**
- [ ] Realizar un reinicio completo del sistema de inmediato

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Establecer varias copias de seguridad ubicadas en diferentes regiones**. Esta es la única opción que garantiza disponibilidad incluso si un proveedor de nube sufre una interrupción (redundancia geográfica y/o multinube).
#### Ejercicio de repaso: Reducir exposición por acceso no autorizado

**Pregunta:**  
Eres un funcionario de ciberseguridad de Blue Tech, una empresa mediana que utiliza la plataforma de gestión de relaciones con el cliente (CRM) basada en la nube, Salesforce. Los usuarios no autorizados recientemente obtuvieron acceso a los datos de clientes de Blue Tech.

¿Qué estrategia deberías implementar para **reducir el riesgo futuro** de tal exposición?

- [ ] Realizar auditorías de rendimiento periódicas en Salesforce
- [ ] Agregar redundancia invirtiendo en plataformas de CRM adicionales
- [x] **Aplicar cifrado e implementar controles de acceso en Salesforce**
- [ ] Delegar todas las responsabilidades de CRM a otro proveedor

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Aplicar cifrado e implementar controles de acceso en Salesforce**. Los controles de acceso evitan que usuarios no autorizados entren, y el cifrado protege los datos incluso si alguien logra interceptarlos. Las otras opciones no abordan el problema de raíz.

</details>
</details>

#### Ejercicio de repaso: Elegir la solución de seguridad adecuada para SaaS

**Pregunta:**  
Como líder de ciberseguridad en WeInvest, una consultoría financiera, debes proteger su aplicación **QuickBooks Online** (software de contabilidad basado en la nube).

¿Qué solución de seguridad deberías implementar?

- [ ] Plataforma de protección de aplicaciones nativas de la nube (CNAPP)
- [x] **Cloud Access Security Broker (CASB)**
- [ ] Gestión de postura de seguridad en la nube (CSPM)
- [ ] Sistema de detección de intrusiones (IDS)

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **CASB (Cloud Access Security Broker)**. QuickBooks Online es una aplicación SaaS (Software como Servicio). Un CASB está diseñado específicamente para proteger aplicaciones SaaS, actuando como un guardián que controla el acceso, aplica políticas de seguridad y monitorea la actividad de los usuarios.

- **CNAPP** → protege aplicaciones nativas de la nube (las que desarrolla la empresa)
- **CSPM** → protege configuraciones de infraestructura en la nube
- **IDS** → detecta intrusiones en la red, pero no tiene visibilidad dentro de aplicaciones SaaS

</details>


## Proyecto culminante: Proponer servicios en la nube y medidas de seguridad

Te damos la bienvenida a **Proponer servicios en la nube y medidas de seguridad**.

### Descripción del proyecto

En este proyecto culminante, garantizarás la seguridad de los datos y la infraestructura de **Jasper Manufacturing**, una pequeña empresa de fabricación que migra sus sistemas y aplicaciones a la nube.

El proyecto tiene **dos objetivos**:

1. **Identificar los mejores modelos de computación en la nube** para las necesidades de Jasper Manufacturing
2. **Recomendar tácticas adecuadas de mitigación de amenazas** para proteger los sistemas, los datos, las aplicaciones y la infraestructura en la nube de la empresa

---

### Aprendizaje previo

Este proyecto se basa en los conocimientos y habilidades que adquiriste en estos módulos:

- **Computación en la nube y virtualización** (Módulo 7)
- **Protección de la infraestructura en la nube** (Módulo 8)

---

### Resumen de competencias

Luego de completar este proyecto culminante, deberías poder realizar lo siguiente:

- **Aplicar los modelos de computación en la nube adecuados** según las necesidades de una organización
- **Resumir los conceptos clave** para proteger los datos, la infraestructura y las aplicaciones en la nube

---

### Habilidades para la inserción laboral

Además, practicarás estas habilidades para la inserción laboral:

| Habilidad | Cómo la aplicarás en este proyecto |
|-----------|-------------------------------------|
| **Pensamiento analítico** | Analizarás las necesidades de la empresa y los beneficios de diferentes modelos en la nube. También analizarás posibles amenazas y evaluarás tácticas de mitigación. |
| **Atención al detalle** | Examinarás de cerca las necesidades de la empresa, las características de los modelos en la nube y la naturaleza de las amenazas potenciales. |
| **Pensamiento crítico** | Evaluarás los pros y contras de diferentes modelos y marcos de computación en la nube, así como los riesgos y tácticas de mitigación. |
| **Toma de decisiones** | Tomarás decisiones informadas sobre los mejores modelos en la nube y las tácticas de mitigación más efectivas. |
| **Comunicación escrita** | Expresarás detalladamente tus recomendaciones y el razonamiento detrás de ellas, conectándolas con las necesidades de la empresa. |
| **Agilidad de aprendizaje** | Aprenderás rápidamente sobre modelos de nube, amenazas de seguridad y tácticas de mitigación, integrando nuevos conceptos con lo que ya conoces. |
| **Resolución de problemas** | Identificarás problemas potenciales (amenazas), los analizarás y propondrás soluciones (tácticas de mitigación). |

---

### Estructura del proyecto

A continuación, se presentan los escenarios y las tareas que deberás completar para ayudar a **Jasper Manufacturing** en su migración a la nube.

<!-- Acá irán los escenarios específicos del proyecto cuando los compartas -->

### ¿Cómo te evaluarán?

Completarás **dos evaluaciones** en este proyecto culminante:

#### Evaluación 1: Proyecto

Responderás preguntas para demostrar tu capacidad para garantizar la **protección de sistemas, datos, aplicaciones e infraestructura en la nube**.

- **Puntaje mínimo requerido:** 80%
- **Intentos:** Puedes volver a intentarlo tantas veces como desees
- **⚠️ Importante:** No cierres el navegador mientras trabajas en el proyecto porque perderás tu progreso y tendrás que empezar de nuevo.

#### Evaluación 2: Cuestionario

Completarás una evaluación de **10 preguntas** para demostrar los conocimientos y habilidades que aplicaste en el proyecto.

- **Puntaje mínimo requerido:** 80%
- **Intentos:** Puedes volver a intentarlo si es necesario
- **Feedback:** Recibirás comentarios sobre tus respuestas

---

### Pasos para completar el proyecto

En el puesto de **analista de seguridad en la nube**, garantizarás la protección de los sistemas, los datos, las aplicaciones y la infraestructura en la nube.

Completarás este proyecto en **cuatro pasos**:

---

#### Paso 1: Determinar el mejor modelo de despliegue en la nube para la organización

| Tarea | Descripción |
|-------|-------------|
| **Tarea 1** | Analizar el escenario de Jasper Manufacturing |
| **Tarea 2** | Identificar el modelo de despliegue en la nube que mejor se adapte a sus necesidades |
| **Tarea 3** | Justificar la elección del modelo de despliegue |

**Modelos de despliegue a considerar:**
- Nube pública
- Nube privada
- Nube híbrida
- Nube comunitaria

---

#### Paso 2: Determinar el mejor modelo de servicio en la nube para la organización

| Tarea | Descripción |
|-------|-------------|
| **Tarea 1** | Identificar el modelo de servicio en la nube que mejor se adapte a las necesidades de la organización |
| **Tarea 2** | Justificar la elección del modelo de servicio |

**Modelos de servicio a considerar:**
- IaaS (Infraestructura como Servicio)
- PaaS (Plataforma como Servicio)
- SaaS (Software como Servicio)
- DBaaS (Base de Datos como Servicio)

---

#### Paso 3: Explicar las amenazas potenciales a un entorno basado en la nube

| Tarea | Descripción |
|-------|-------------|
| **Tarea 1** | Identificar las amenazas potenciales para el entorno de la organización basado en la nube |
| **Tarea 2** | Describir los riesgos asociados con cada amenaza identificada |
| **Tarea 3** | Describir el impacto potencial de las amenazas en la organización |

**Amenazas a considerar:**
- Identidades mal gestionadas
- Configuración incorrecta de la nube
- Denegación de servicio (DoS/DDoS)
- Amenazas internas
- Visibilidad reducida de la infraestructura
- Uso no autorizado de cargas de trabajo (TI en la sombra)
- API poco seguras
- Violaciones de cumplimiento

---

#### Paso 4: Recomendar métodos para proteger los datos, la infraestructura y las aplicaciones en la nube

| Tarea | Descripción |
|-------|-------------|
| **Tarea 1** | Identificar tácticas de mitigación de amenazas para proteger los datos, la infraestructura y las aplicaciones en la nube |
| **Tarea 2** | Describir cómo las tácticas de mitigación reducen o eliminan los riesgos asociados con la nube |

**Tácticas de mitigación a considerar:**
- IAM (Gestión de identidades y accesos)
- Cifrado de datos (en reposo y en tránsito)
- CSPM (Gestión de postura de seguridad en la nube)
- CASB (Cloud Access Security Broker)
- CNAPP (Plataforma de protección de aplicaciones nativas)
- Copias de seguridad y recuperación ante desastres (Cloud DR)
- Monitoreo continuo y detección de amenazas
- POLP (Principio de mínimo privilegio)
- Autenticación multifactor (MFA)
- Firewalls y segmentación de red

### Descripción general del proyecto por pasos

#### Paso 1: Determinar el mejor modelo de despliegue en la nube para la organización

En este paso, leerás sobre la situación de **Jasper Manufacturing** y su interés en la transición a la nube.

**Analizarás:**
- Su infraestructura informática actual
- Sus objetivos empresariales
- Requisitos o limitaciones específicos

**Luego:**
- Identificarás el **mejor modelo de despliegue en la nube** según las necesidades de Jasper Manufacturing
- **Justificarás** tu elección

**Modelos de despliegue a considerar:**
- Nube pública
- Nube privada
- Nube híbrida
- Nube comunitaria

---

#### Paso 2: Determinar el mejor modelo de servicio en la nube para la organización

En este paso, evaluarás los beneficios de varios **modelos de servicio en la nube** para abordar la situación de la empresa.

**Factores a considerar:**
- Costo
- Escalabilidad
- Seguridad
- Cumplimiento normativo

**Luego:**
- Seleccionarás el **modelo que mejor se adapte** a los criterios de la empresa
- **Justificarás** tu elección

**Modelos de servicio a considerar:**
- IaaS (Infraestructura como Servicio)
- PaaS (Plataforma como Servicio)
- SaaS (Software como Servicio)
- DBaaS (Base de Datos como Servicio)

---

#### Paso 3: Explicar las amenazas potenciales para un entorno basado en la nube

En este paso, identificarás las **amenazas potenciales** para el entorno basado en la nube de Jasper Manufacturing.

Para cada amenaza, deberás identificar:
- **El riesgo asociado** (¿qué puede pasar?)
- **El impacto potencial** si la empresa no la aborda (¿qué consecuencias tendría?)

**Amenazas a considerar:**
- Identidades mal gestionadas
- Configuración incorrecta de la nube
- Denegación de servicio (DoS/DDoS)
- Amenazas internas
- Visibilidad reducida de la infraestructura
- Uso no autorizado de cargas de trabajo (TI en la sombra)
- API poco seguras
- Violaciones de cumplimiento

---

#### Paso 4: Recomendar métodos para proteger los datos, la infraestructura y las aplicaciones en la nube

En este paso, identificarás los **controles específicos** que la empresa debería implementar para hacer frente a las amenazas a la nube.

Para cada control recomendado:
- Identificarás la **táctica de mitigación**
- **Justificarás** por qué es adecuada para Jasper Manufacturing

**Tácticas de mitigación a considerar:**
- IAM (Gestión de identidades y accesos) con POLP y MFA
- Cifrado de datos (en reposo y en tránsito)
- CSPM (para monitorear configuraciones)
- CASB (para proteger aplicaciones SaaS)
- CNAPP (para aplicaciones nativas de la nube)
- Copias de seguridad y recuperación ante desastres (Cloud DR)
- Monitoreo continuo y detección de amenazas
- Firewalls y segmentación de red
- Capacitación en seguridad para empleados

### Proyecto culminante: Jasper Manufacturing

#### Antecedentes

**Jasper Manufacturing** es una empresa mediana especializada en la producción de **componentes automotrices**. La empresa creció significativamente en los últimos años y ahora opera múltiples plantas de fabricación y oficinas en toda **América del Norte**.

Para mantenerse al día con este crecimiento y mejorar la eficiencia operativa, Jasper Manufacturing desea migrar su infraestructura de TI a la **nube**.

---

#### Tu rol

Jasper Manufacturing te contrata como **analista de seguridad en la nube** para obtener una opinión externa sobre su traslado a la nube.

Tu punto de contacto es **Yemane**, el director de TI. Te pide que propongas los **servicios en la nube** y las **soluciones de seguridad** más apropiados dadas las necesidades de la empresa y que justifiques tus elecciones.

---

#### Infraestructura actual (según Yemane)

| Aspecto | Descripción |
|---------|-------------|
| **Centros de datos locales** | 2 centros de datos en el medio oeste y la costa oeste de EE.UU. |
| **Alojan** | Aplicaciones críticas, bases de datos, sistemas de almacenamiento de archivos |
| **Red** | Infraestructura sólida que conecta todas las ubicaciones |
| **Problema** | Algunas ubicaciones remotas experimentan **latencia** y **limitaciones de ancho de banda** |

---

#### Ecosistema de TI actual

| Tipo de aplicación | Detalles |
|-------------------|----------|
| **ERP** | Sistemas de planificación de recursos empresariales |
| **CRM** | Software de gestión de relaciones con clientes |
| **Aplicaciones personalizadas** | Gestión de producción (requieren configuraciones específicas) |
| **Herramientas de productividad** | Ofimática (correo, documentos, etc.) |
| **Sistemas heredados** | Algunos requieren configuraciones específicas de hardware y software |

---

#### Datos confidenciales almacenados

- **Procesos de fabricación patentados** (propiedad intelectual)
- **Información de clientes**
- **Registros de empleados**

> ⚠️ **Estos datos requieren altos niveles de protección y cumplimiento normativo.**

Jasper Manufacturing - Resumen fácil
¿Qué es la empresa?
Una empresa mediana que fabrica partes para autos. Tiene varias fábricas y oficinas en Estados Unidos y Canadá.

¿Qué tienen ahora (antes de la nube)?
Recurso	Qué es
2 centros de datos propios	Son como dos "cuartos de servidores" grandes que la empresa maneja sola (uno en el medio oeste de EE.UU., otro en la costa oeste)
Red interna	Conectan todas sus oficinas y fábricas entre sí
Problema de red	Algunas oficinas remotas tienen internet lento y demora (latencia)
¿Qué sistemas usan?
Sistema	Para qué sirve
ERP	Manejan toda la empresa (compras, inventario, finanzas)
CRM	Manejan la relación con clientes
Aplicaciones personalizadas	Programas hechos a medida para controlar la producción
Herramientas de oficina	Correo, Word, Excel, etc.
Sistemas viejos (heredados)	Programas antiguos que necesitan hardware o software específico para funcionar
¿Qué datos sensibles tienen?
Fórmulas y procesos de fabricación (secreto de la empresa)

Datos de clientes

Datos de empleados

👉 Esto es muy importante: estos datos no se pueden perder ni filtrar.

¿Qué problema quieren resolver?
Crecieron mucho y sus centros de datos propios no les están dando abasto

Algunas oficinas tienen internet lento

Quieren modernizarse y ser más eficientes

¿Qué quieren hacer?
Migrar a la nube (irse de sus propios servidores a la nube como Azure, AWS, etc.)

Resumen en una tabla fácil
Aspecto	Situación actual
Tamaño	Mediana
Industria	Autopartes
Ubicaciones	Fábricas y oficinas en toda América del Norte
Centros de datos	2 propios (EE.UU.)
Problema técnico	Internet lento en algunas oficinas remotas
Aplicaciones	ERP, CRM, sistemas hechos a medida, sistemas viejos
Datos sensibles	Fórmulas secretas, clientes, empleados
Objetivo	Migrar a la nube para crecer y ser más eficientes
¿Qué vas a tener que decidir como analista?
Paso	Pregunta a responder
1	¿Qué modelo de nube le conviene? (pública, privada, híbrida, comunitaria)
2	¿Qué modelo de servicio le conviene? (IaaS, PaaS, SaaS, DBaaS)
3	¿Qué amenazas pueden afectarlos en la nube?
4	¿Qué medidas de seguridad tienen que poner para protegerse?


### Proyecto Jasper Manufacturing - Preguntas de verificación

#### Pregunta 1: Característica clave de la infraestructura actual
- [x] **Dos centros de datos locales que albergan aplicaciones y datos críticos**
- [ ] Un modelo de gestión de infraestructuras de TI externalizado
- [ ] Un único centro de datos con conectividad de red limitada
- [ ] Almacenamiento basado en la nube para todas las aplicaciones y datos

#### Pregunta 2: Problema notable en la infraestructura de red
- [x] **Latencia de red y restricciones de ancho de banda en algunas ubicaciones remotas**
- [ ] Altos costos operativos de mantenimiento de la red
- [ ] Falta de conectividad entre las distintas oficinas
- [ ] Medidas de seguridad inadecuadas para la transmisión de datos

#### Pregunta 3: Tipos de aplicaciones en el ecosistema de TI
- [x] **Sistemas ERP, software CRM, aplicaciones de gestión de producción personalizadas y herramientas de productividad ofimática**
- [ ] Software de colaboración basado en la nube, aplicaciones de código abierto y servicios alojados por terceros
- [ ] Software financiero, herramientas de gestión de proyectos y servicios en la nube de terceros
- [ ] Aplicaciones móviles, plataformas de redes sociales y aplicaciones web orientadas al cliente

#### Pregunta 4: Preocupación importante sobre los datos almacenados
- [x] **Confidencialidad de los datos, incluida la fabricación patentada y la información del cliente**
- [ ] Altos costos asociados con el almacenamiento de datos y la infraestructura de gestión
- [ ] Complejidad de gestionar e integrar diversas fuentes de datos de manera eficiente
- [ ] Disponibilidad de servicios de almacenamiento de datos y soluciones confiables


#### Pregunta 5: Limitación del personal de TI

**¿Cuál es una limitación del personal de TI de Jasper Manufacturing en lo que respecta a las tecnologías en la nube?**

- [ ] Capacitación insuficiente en análisis de datos y elaboración de informes
- [x] **Experiencia limitada con tecnologías en la nube**
- [ ] Falta de conocimiento en medidas avanzadas de ciberseguridad
- [ ] Niveles de personal y recursos inadecuados

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Experiencia limitada con tecnologías en la nube**. Yemane mencionó que el personal tiene experiencia en infraestructura local (centros de datos propios), pero su experiencia con la nube es limitada.

</details>

### Proyecto Jasper Manufacturing - Objetivos empresariales

#### Pregunta 1: Objetivo comercial principal
- [ ] Reducir empleados y espacio de oficina
- [ ] Eliminar servidores físicos y centros de datos
- [x] **Mejorar la eficiencia operativa, la escalabilidad y la seguridad**
- [ ] Implementar software de código abierto

#### Pregunta 2: Gestión del gasto en TI
- [ ] Reducir salarios del personal de TI
- [ ] Vender los centros de datos existentes
- [ ] Subcontratar todas las operaciones de TI
- [x] **Usar modelos de precios de pago por uso**

#### Pregunta 3: Tipo de entorno de TI buscado
- [ ] Entorno rígido con protocolos estrictos
- [x] **Entorno flexible que se adapta a necesidades cambiantes y soporta trabajo remoto**
- [ ] Entorno desestructurado sin objetivos
- [ ] Entorno mínimo sin flexibilidad

#### Pregunta 4: Importancia de la recuperación ante desastres
- [x] **Minimizar el tiempo de inactividad y la pérdida de datos en caso de desastre**
- [ ] Evitar la necesidad de copias de seguridad periódicas
- [ ] Reducir el personal de TI necesario
- [ ] Eliminar completamente los ciberataques


### Justificación del modelo de despliegue híbrido para Jasper Manufacturing

**Jasper Manufacturing debe adoptar un modelo de nube HÍBRIDO** (combinación de nube privada + nube pública) por las siguientes razones:

#### 1. Por sus sistemas heredados y aplicaciones personalizadas
La empresa tiene **sistemas antiguos (heredados)** y **aplicaciones personalizadas** que requieren configuraciones específicas de hardware y software. Estos sistemas no pueden migrarse fácilmente a la nube pública. En un modelo híbrido, pueden:
- **Mantener en su nube privada local** (o centro de datos propio) las aplicaciones heredadas que necesitan configuraciones especiales
- **Migrar a la nube pública** las aplicaciones modernas (ERP, CRM, herramientas de oficina)

#### 2. Por la confidencialidad de sus datos sensibles
Jasper Manufacturing almacena **procesos de fabricación patentados** (secretos industriales), información de clientes y datos de empleados. Estos datos requieren altos niveles de protección. En un modelo híbrido:
- Los **datos más sensibles** pueden mantenerse en la nube privada (mayor control)
- Los **datos menos críticos** pueden ir a la nube pública (ahorro de costos)

#### 3. Por la experiencia limitada del personal en nube
El equipo de TI tiene **experiencia limitada con tecnologías de nube**. Un modelo híbrido permite:
- Una **migración gradual** (no todo de golpe)
- Mantener parte de la infraestructura conocida (local) mientras aprenden a manejar la nube pública
- Reducir el riesgo de errores de configuración

#### 4. Por los problemas de red (latencia y ancho de banda)
Algunas ubicaciones remotas tienen **internet lento**. Con un modelo híbrido:
- Las aplicaciones críticas que necesitan baja latencia pueden **seguir en infraestructura local** (cerca de las fábricas)
- Las aplicaciones menos sensibles a la latencia pueden ir a la nube pública

#### 5. Por los objetivos de escalabilidad y ahorro de costos
Jasper Manufacturing quiere **pagar solo por lo que usa** (modelo de pago por uso) y poder **escalar rápidamente**. El modelo híbrido permite:
- Usar la **nube pública** para manejar picos de demanda (escalabilidad)
- Mantener la **nube privada** para cargas de trabajo estables y predecibles
- Optimizar costos: no pagar por recursos que no se usan

#### 6. Por la necesidad de recuperación ante desastres (DR)
El modelo híbrido es ideal para **recuperación ante desastres**:
- La nube pública puede actuar como **sitio de respaldo** de la infraestructura local
- Si un centro de datos local falla, las aplicaciones críticas pueden **conmutar a la nube pública**
- Minimiza el tiempo de inactividad y la pérdida de datos

---

### Por qué NO elegir los otros modelos

| Modelo | ¿Por qué no es adecuado? |
|--------|--------------------------|
| **Nube pública sola** | No puede manejar sistemas heredados que requieren hardware específico. Riesgo de cumplimiento para datos sensibles. |
| **Nube privada sola** | Requiere grandes inversiones de capital inicial (lo que quieren evitar). No ofrece la escalabilidad elástica del pago por uso. |
| **Nube comunitaria** | Es para organizaciones con intereses comunes (varios hospitales, varios bancos). Jasper Manufacturing no comparte intereses específicos con otras empresas para justificar este modelo. |

#### Pregunta de repaso: Características de la nube pública

**¿Cuáles de las siguientes son características del modelo de nube pública?**

- [ ] Combinación de escalabilidad con control local de datos confidenciales
- [x] **Escalabilidad y rentabilidad, pero menos control sobre la seguridad de los datos**
- [ ] Recursos compartidos con otras organizaciones que tienen necesidades similares
- [ ] Control total sobre hardware y software, pero costos más altos

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Escalabilidad y rentabilidad, pero menos control sobre la seguridad de los datos**. Esta es la esencia de la nube pública: gran escalabilidad y bajo costo de entrada, pero con la responsabilidad compartida (el proveedor gestiona la infraestructura física, el cliente gestiona sus datos y accesos).

</details>

#### Pregunta de repaso: Características de la nube híbrida

**¿Cuáles de las siguientes son cualidades del modelo de nube híbrida?**

- [x] **Combinación de escalabilidad con control local de datos confidenciales**
- [ ] Recursos compartidos con otras organizaciones que tienen necesidades similares
- [ ] Control total sobre hardware y software, pero costos más altos
- [ ] Escalabilidad y rentabilidad, pero menos control sobre la seguridad de los datos

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Combinación de escalabilidad con control local de datos confidenciales**. La nube híbrida permite usar la nube pública para escalar cuando sea necesario, mientras se mantienen los datos sensibles en un entorno privado o local con mayor control.

</details>

⚠️ CUIDADO: Esta selección es INCORRECTA.

La imagen muestra que se seleccionó Nube Pública, pero según el análisis detallado que hicimos de Jasper Manufacturing, el modelo correcto es NUBE HÍBRIDA.

Respuesta correcta
Modelo elegido:

☐ Público

☐ Privado

☑ Híbrido

☐ Comunitario

¿Por qué NO es correcta la nube pública para Jasper Manufacturing?
Problema con nube pública	Por qué no funciona para Jasper
Sistemas heredados	Tienen aplicaciones antiguas que requieren hardware/software específico. La nube pública no puede ejecutarlos sin modificaciones costosas.
Datos sensibles	Tienen secretos de fabricación (propiedad intelectual). En la nube pública, los datos están en infraestructura compartida con otros clientes.
Cumplimiento	Necesitan mantener altos niveles de seguridad y cumplimiento normativo. La nube pública da menos control.
Latencia	Algunas ubicaciones remotas tienen internet lento. Depender solo de nube pública empeoraría el rendimiento.
Resumen comparativo para tu proyecto
Modelo	¿Sirve para Jasper?	¿Por qué?
Pública	❌ No	Menos control para datos sensibles, no soporta sistemas heredados
Privada	❌ No (sola)	Requiere alta inversión inicial (lo que quieren evitar)
Híbrida	✅ Sí	Combina control local (datos sensibles + sistemas heredados) con escalabilidad de nube pública
Comunitaria	❌ No	Solo para organizaciones con intereses comunes (varios hospitales, varios bancos)


**Modelo elegido:** Híbrido

**Justificación:** Jasper Manufacturing necesita un modelo híbrido porque:
1. Tiene sistemas heredados que requieren hardware específico (se quedan en infraestructura local)
2. Almacena datos sensibles (procesos patentados) que requieren mayor control (nube privada/local)
3. Busca escalabilidad y pago por uso (nube pública para cargas variables)
4. Necesita recuperación ante desastres (la nube pública puede ser el respaldo)
5. Su personal tiene experiencia limitada en nube (migración gradual posible)

#### Pregunta: Flexibilidad del modelo híbrido

**¿Qué aspecto del modelo de nube híbrida respalda los requisitos de Jasper Manufacturing de un entorno de TI flexible que se adapte a las necesidades cambiantes del negocio?**

- [ ] Simplifica la infraestructura de TI a una única plataforma
- [ ] Restringe las actualizaciones a una vez al año
- [ ] Limita el acceso solo a los empleados en el sitio
- [x] **Proporciona recursos de nube locales y remotos**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Proporciona recursos de nube locales y remotos**. El modelo híbrido permite mantener aplicaciones críticas y datos sensibles en infraestructura local (control), mientras se utiliza la nube pública para escalar, innovar o manejar picos de demanda (flexibilidad). Esto da a Jasper Manufacturing lo mejor de ambos mundos.

</details>

#### Pregunta: Cómo el modelo híbrido aborda la latencia y ancho de banda limitado

**¿Por qué el modelo de nube híbrida es efectivo para abordar las limitaciones de ancho de banda y latencia de red de Jasper Manufacturing en ubicaciones remotas?**

- [ ] Obliga a todas las ubicaciones remotas a actualizar su infraestructura de red
- [ ] Elimina la necesidad de almacenamiento de datos local
- [x] **Permite que los datos críticos se almacenen localmente mientras se emplean servicios en la nube para otras tareas**
- [ ] Requiere que todos los datos se procesen a través de la nube pública

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Permite que los datos críticos se almacenen localmente mientras se emplean servicios en la nube para otras tareas**. El modelo híbrido permite mantener aplicaciones sensibles a la latencia y datos críticos en infraestructura local (cerca de las ubicaciones remotas), mientras se usa la nube pública para tareas no críticas que no requieren respuesta inmediata. Así se evita el problema de internet lento.

</details>

#### Pregunta: Recuperación ante desastres con modelo híbrido

**¿Cómo mejora el modelo de nube híbrida las capacidades de recuperación ante desastres de Jasper Manufacturing?**

- [ ] Simplifica la infraestructura de TI a una única plataforma
- [ ] Restringe las actualizaciones a una vez al año
- [ ] Limita el acceso solo a los empleados en el sitio
- [x] **Proporciona recursos de nube locales y remotos**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Proporciona recursos de nube locales y remotos**. El modelo híbrido permite tener infraestructura local para operaciones diarias y usar la nube pública como sitio de respaldo (DR site). Si ocurre un desastre local, las aplicaciones críticas pueden conmutar a la nube pública, minimizando el tiempo de inactividad y la pérdida de datos.

</details>

#### Pregunta: Recuperación ante desastres con modelo híbrido (versión 2)

**¿Cómo mejora el modelo de nube híbrida las capacidades de recuperación ante desastres de Jasper Manufacturing?**

- [ ] Emplea una única ubicación de copia de seguridad para todos los datos sin integración en la nube
- [ ] Se basa completamente en servidores locales para toda la recuperación y el almacenamiento de datos
- [ ] Implementa solo la nube pública para toda la recuperación ante desastres sin copias de seguridad locales
- [x] **Combina la resiliencia de la nube pública con el control de la nube privada para datos críticos**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Combina la resiliencia de la nube pública con el control de la nube privada para datos críticos**. El modelo híbrido permite usar la nube pública como sitio de respaldo (resiliencia, disponibilidad geográfica) mientras se mantienen los datos más sensibles en la nube privada o infraestructura local (control, cumplimiento). Así se logra lo mejor de ambos mundos para la recuperación ante desastres.

</details>

#### Pregunta: Seguridad y cumplimiento con modelo híbrido

**¿De qué manera el modelo de nube híbrida garantiza altos niveles de seguridad de datos y cumplimiento para Jasper Manufacturing?**

- [x] **Almacena datos confidenciales en una nube privada mientras usa una nube pública para tareas menos sensibles**
- [ ] Depende únicamente de proveedores externos para todas las medidas de seguridad de datos
- [ ] Coloca todos los datos en una nube pública para facilitar el acceso y la gestión
- [ ] Reduce los requisitos de cumplimiento al limitar el almacenamiento de datos a una sola ubicación

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Almacena datos confidenciales en una nube privada mientras usa una nube pública para tareas menos sensibles**. El modelo híbrido permite mantener los datos más sensibles (procesos patentados, información de clientes) en un entorno privado y controlado para cumplir con normativas, mientras se aprovecha la nube pública para cargas de trabajo no críticas.

</details>

#### Pregunta: Beneficios de IaaS para Jasper Manufacturing

**¿Cuáles de las siguientes son beneficios del modelo de infraestructura como servicio (IaaS) para Jasper Manufacturing?**

- [x] **Escalabilidad y control sobre los recursos informáticos**
- [ ] Capacidades de seguridad y cumplimiento reducidas
- [ ] Alta inversión de capital inicial y complejidad de gestión
- [ ] Personalización y control limitados sobre el hardware

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Escalabilidad y control sobre los recursos informáticos**. IaaS permite a Jasper Manufacturing escalar recursos bajo demanda (pagando solo por lo que usa) y mantener control sobre sistemas operativos, aplicaciones y configuraciones. Esto es ideal para sus sistemas heredados, aplicaciones personalizadas y picos de producción.

</details>

#### Pregunta: Ventajas de PaaS

**¿Cuáles son las principales ventajas del modelo de plataforma como servicio (PaaS) para Jasper Manufacturing?**

- [ ] Control total sobre las configuraciones de hardware y software
- [x] **Desarrollo y despliegue racionalizados de las aplicaciones**
- [ ] Menor necesidad de cumplir con las regulaciones de la industria
- [ ] Capacidad mejorada para personalizar la infraestructura subyacente

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Desarrollo y despliegue racionalizados de las aplicaciones**. PaaS proporciona un entorno preconfigurado con herramientas de desarrollo, SO y runtime, lo que permite a los desarrolladores de Jasper Manufacturing enfocarse en el código y desplegar aplicaciones más rápido, sin gestionar la infraestructura subyacente.

</details>

#### Pregunta: Ventajas de SaaS

**¿Qué ventajas ofrece el modelo de software como servicio (SaaS) para Jasper Manufacturing?**

- [ ] Procesos complejos de configuración e integración
- [ ] Alto control sobre el hardware y el software subyacentes
- [x] **Ahorro de costos y facilidad de uso para aplicaciones de software**
- [ ] Personalización de todos los aspectos del entorno de software

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Ahorro de costos y facilidad de uso para aplicaciones de software**. SaaS permite a Jasper Manufacturing usar aplicaciones (como Office 365, Salesforce) pagando una suscripción por usuario, sin invertir en servidores ni preocuparse por mantenimiento. Es ideal para herramientas de productividad, colaboración y CRM.

</details>

Respuesta correcta (si solo se puede elegir uno)
✅ Infraestructura como servicio (IaaS)

Modelo elegido:

☑ Infraestructura como servicio (IaaS)

☐ Plataforma como servicio (PaaS)

☐ Software como servicio (SaaS)

¿Por qué IaaS es la mejor opción si solo se puede elegir uno?
Porque IaaS es el modelo FUNDACIONAL que cubre la mayoría de las necesidades críticas de Jasper Manufacturing:

Necesidad crítica de Jasper	¿La cubre IaaS?	¿La cubre SaaS?	¿La cubre PaaS?
Sistemas heredados (requieren configuraciones específicas)	✅ Sí	❌ No	❌ No
Aplicaciones personalizadas	✅ Sí	❌ No	⚠️ Parcial
Datos sensibles (procesos patentados, clientes)	✅ Sí	❌ No	⚠️ Parcial
Control sobre SO y configuraciones	✅ Sí	❌ No	❌ No
Escalabilidad y pago por uso	✅ Sí	✅ Sí	✅ Sí
Migración gradual (personal con experiencia limitada)	✅ Sí	✅ Sí	⚠️ Parcial
Además: Con IaaS, Jasper Manufacturing puede instalar y ejecutar aplicaciones SaaS-like en sus propias VMs (por ejemplo, instalar Nextcloud en lugar de usar Dropbox). Con SaaS no pueden ejecutar sus sistemas heredados.


**Modelo elegido:** IaaS

**Justificación:** Jasper Manufacturing debe elegir IaaS porque es el único modelo que satisface TODAS sus necesidades críticas:
1. Permite ejecutar sistemas heredados que requieren configuraciones específicas
2. Permite control total sobre aplicaciones personalizadas de producción
3. Mantiene control sobre datos sensibles (procesos patentados)
4. Ofrece escalabilidad y pago por uso sin inversión inicial
5. Permite una migración gradual (el personal tiene experiencia limitada en nube)

SaaS sería útil para oficina y CRM, pero no puede ejecutar sus sistemas críticos. IaaS es el modelo base indispensable.


#### Pregunta: Ventajas de IaaS para Jasper Manufacturing

**¿Cuáles de las siguientes son ventajas del modelo de infraestructura como servicio (IaaS) para Jasper Manufacturing?**

- [ ] Personalización y control limitados sobre el hardware
- [ ] Compatibilidad e integración de software mejoradas
- [x] **Escalabilidad y control de los recursos informáticos**
- [ ] Seguridad de datos mejorada a través del aislamiento físico

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Escalabilidad y control de los recursos informáticos**. IaaS permite a Jasper Manufacturing escalar recursos bajo demanda (pagando solo por lo que usa) y mantener control sobre sistemas operativos, aplicaciones y configuraciones. Esto es ideal para sus sistemas heredados, aplicaciones personalizadas y picos de producción.

</details>

#### Pregunta: Comparación IaaS vs PaaS

**¿Cómo se compara IaaS con PaaS en términos de flexibilidad y control para Jasper Manufacturing?**

- [ ] IaaS ofrece menos control sobre las configuraciones de hardware y software
- [x] **IaaS ofrece más flexibilidad y control sobre la infraestructura**
- [ ] IaaS ofrece más herramientas y servicios preconfigurados
- [ ] IaaS ofrece menos control sobre la seguridad y el cumplimiento

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **IaaS ofrece más flexibilidad y control sobre la infraestructura**. A diferencia de PaaS, IaaS permite a Jasper Manufacturing elegir y configurar sistemas operativos, instalar cualquier software (incluyendo sistemas heredados y aplicaciones personalizadas), y gestionar la seguridad a su medida. PaaS es más restrictivo pero ofrece menos trabajo de administración.

</details>

#### Pregunta: Desafíos de adoptar IaaS

**¿Cuáles son los posibles desafíos de adoptar IaaS para Jasper Manufacturing?**

- [ ] Escalabilidad y asignación de recursos limitadas
- [ ] Se requiere una alta inversión de capital inicial
- [ ] Menor necesidad de cumplir con las regulaciones de la industria
- [x] **Complejidad de la gestión y responsabilidad de la seguridad**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Complejidad de la gestión y responsabilidad de la seguridad**. IaaS requiere que Jasper Manufacturing administre sistemas operativos, aplicaciones, configuraciones de red y seguridad (modelo de responsabilidad compartida). Esto es un desafío porque el personal de Jasper tiene **experiencia limitada en nube** y debe asegurar datos sensibles (procesos patentados, información de clientes).

</details>


#### Pregunta: Riesgo de acceso no autorizado

**¿Cuál es un riesgo significativo relacionado con el acceso no autorizado en entornos de nube?**

- [x] **Gestión de identidades incorrecta**
- [ ] Configuración incorrecta de la nube
- [ ] Amenazas internas
- [ ] Denegación de servicio

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Gestión de identidades incorrecta**. Esto incluye credenciales débiles, falta de MFA, permisos excesivos, cuentas sin revocar. Estos problemas permiten que atacantes o usuarios no autorizados accedan a recursos que no deberían. Es la causa principal de accesos no autorizados en la nube.

</details>

#### Pregunta: Problema de configuración incorrecta

**¿Qué problema surge de una configuración incorrecta en entornos de nube?**

- [ ] Errores internos
- [x] **Configuración incorrecta**
- [ ] Tráfico de red excesivo
- [ ] Actividades internas maliciosas

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Configuración incorrecta**. Es el nombre de la amenaza en sí misma. Cuando alguien configura mal un recurso en la nube (deja un bucket público, abre puertos innecesarios, asigna permisos excesivos), el problema resultante se denomina "configuración incorrecta de la nube".

</details>

#### Pregunta: Impacto de las amenazas internas

**¿Cómo puede afectar el uso del acceso autorizado por parte de las amenazas internas a la seguridad en la nube?**

- [ ] Mejorar el rendimiento de la red
- [ ] Causar daños físicos a los servidores
- [ ] Aumentar el costo de los servicios
- [x] **Realizar actividades maliciosas**

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **Realizar actividades maliciosas**. Las amenazas internas son empleados o contratistas con acceso legítimo que usan ese acceso para robar datos, sabotear sistemas o filtrar información sensible. Para Jasper Manufacturing, esto es crítico porque almacena procesos patentados y datos de clientes.

</details>


#### Pregunta: Preocupación principal sobre interfaces en la nube

**¿Cuál es la principal preocupación al usar interfaces en entornos de nube?**

- [x] **API poco seguras**
- [ ] Tráfico de red excesivo
- [ ] Configuración de ajustes incorrecta
- [ ] Gestión de identidades incorrecta

<details>
<summary>Ver explicación</summary>

La respuesta correcta es **API poco seguras**. En los entornos de nube, las APIs son las interfaces principales para interactuar con los servicios. Si no tienen autenticación y autorización adecuadas, los atacantes pueden acceder o manipular datos, crear o eliminar recursos, y comprometer la seguridad. El caso de Google+ (2018) es un ejemplo clásico de filtración por API insegura.
#### Pregunta: Riesgo de configuración incorrecta

**Amenaza:** Error de configuración

**Riesgo asociado:** ✅ **Exposición de sistemas y datos a posibles atacantes**

<details>
<summary>Ver explicación</summary>

La configuración incorrecta (misconfiguration) es una de las principales causas de filtraciones en la nube. El riesgo principal es que recursos como buckets de almacenamiento, bases de datos o servidores queden expuestos al público o a atacantes. Para Jasper Manufacturing, esto podría significar la pérdida de sus procesos patentados o datos de clientes.

</details>
</details>

#### Pregunta: Riesgo de amenazas internas

**Amenaza:** Amenazas internas

**Riesgo asociado:** ✅ **Realizar actividades maliciosas con acceso autorizado**

<details>
<summary>Ver explicación</summary>

Las amenazas internas son personas con acceso legítimo a los sistemas (empleados, contratistas). El riesgo principal es que usen ese acceso autorizado para actividades maliciosas: robo de datos sensibles, sabotaje, filtración de información. Para Jasper Manufacturing, esto es crítico por sus procesos patentados y datos de clientes.

</details>

✅ Explotación de API para acceder a datos o manipularlos

¿Por qué?
Las API poco seguras tienen vulnerabilidades en su diseño o implementación que permiten a los atacantes explotarlas para:

Acceder a datos que no deberían poder ver

Manipular o modificar datos

Ejecutar acciones no autorizadas (crear, eliminar, modificar recursos)

❌ Las otras opciones son incorrectas porque:

Opción	¿Por qué es incorrecta?
"Interrupción de las operaciones debido al tráfico de red saturado"	Eso es un ataque DoS/DDoS, no específico de APIs inseguras
"Acceso no autorizado debido a una gestión de identidad deficiente"	Eso es identidades mal gestionadas (IAM), no específico de APIs
"Pérdida de datos debido a una configuración incorrecta"	Eso es configuración incorrecta (misconfiguration) , no específico de APIs
Ejemplo concreto
Google+ (2018): Una API insegura permitió a desarrolladores externos acceder a datos de usuarios (nombres, correos, ocupaciones, edades) que no deberían haber podido ver. Explotaron la API para acceder a datos.

Para Jasper Manufacturing: Si una API de su ERP o sistema de producción es insegura, un atacante podría:

Extraer procesos patentados (robo de propiedad intelectual)

Modificar órdenes de producción (sabotaje)

Acceder a datos de clientes

#### Pregunta: Riesgo de API poco seguras

**Amenaza:** API poco seguras

**Riesgo asociado:** ✅ **Explotación de API para acceder a datos o manipularlos**

<details>
<summary>Ver explicación</summary>

Las API poco seguras permiten a los atacantes explotar vulnerabilidades para acceder a datos no autorizados o manipular recursos. Esto puede resultar en robo de propiedad intelectual, sabotaje, o violaciones de cumplimiento. El caso de Google+ (2018) es un ejemplo clásico.

</details>

#### Pregunta: Impacto de la configuración incorrecta (corregido)

**Amenaza:** Error de configuración
**Riesgo:** Exposición de sistemas y datos a posibles atacantes
**Impacto:** ✅ **Daños financieros por incumplimiento de las prácticas de protección de datos**

<details>
<summary>Ver explicación</summary>

La exposición de datos por mala configuración puede resultar en multas regulatorias, demandas, costos de notificación y remediación. Estos son daños financieros directos. Aunque también hay daño reputacional, el impacto más concreto y cuantificable suelen ser las pérdidas económicas.

</details>

#### Pregunta: Impacto de ataques DoS/DDoS

**Amenaza:** Ataques de denegación de servicio (DoS)
**Riesgo:** Interrupción de las operaciones debido a tráfico de red sobrecargado
**Impacto:** ✅ **Interrupción de los servicios de la empresa debido a un procesamiento de red más lento**

<details>
<summary>Ver explicación</summary>

Un ataque DoS/DDoS satura la red con tráfico falso, haciendo que el procesamiento sea lento o imposible. El impacto directo es que los servicios de la empresa (ERP, CRM, sistemas de producción) se interrumpen, afectando la operación diaria de Jasper Manufacturing.

</details>

#### Pregunta: Impacto de amenazas internas

**Amenaza:** Amenazas internas  
**Riesgo:** Realizar actividades maliciosas con acceso autorizado  
**Impacto:** ✅ **Pérdida de confianza del público debido a que un empleado actuó maliciosamente**

<details>
<summary>Ver explicación</summary>

Cuando un empleado de confianza (con acceso autorizado) realiza acciones maliciosas, como robar procesos patentados o filtrar datos de clientes, el impacto principal es la **pérdida de confianza del público**. Clientes, socios y el mercado pierden confianza en la empresa, lo que puede traducirse en pérdida de negocios, daño a la marca y dificultades para conseguir nuevos clientes.

</details>

- [ ] Aumento de los costos debido a protocolos de comunicación inseguros a través de las API
- [ ] Pérdida de confianza por fugas de datos debido a API débiles
- [x] **Interrupción de operaciones debido a vulnerabilidades de API**

#### Pregunta: Mitigación de acceso no autorizado

**Amenaza:** Acceso no autorizado
**Control:** Implementar autenticación multifactor (MFA) y controles de acceso basados en roles (RBAC)
**Descripción:** ✅ **Al aplicar una autenticación sólida y limitar el acceso de los usuarios**

<details>
<summary>Ver explicación</summary>

La autenticación multifactor (MFA) proporciona una autenticación sólida al requerir múltiples factores de verificación. Los controles de acceso basados en roles (RBAC) limitan el acceso de los usuarios según lo que necesitan para su trabajo (principio de mínimo privilegio). Juntos, mitigan eficazmente el riesgo de acceso no autorizado.

</details>

- [ ] Al limitar el acceso a los recursos de la empresa y monitorear el uso
- [ ] Al aumentar el número de servidores y la capacidad de la red
- [x] **Al detectar y mitigar el tráfico excesivo**
- [ ] Al externalizar la gestión de la red a un proveedor externo


✅ Al garantizar el cumplimiento de las normas del sector

¿Por qué?
El riesgo es el incumplimiento normativo (no seguir leyes o estándares como GDPR, HIPAA, PCI-DSS, etc.).
El control incluye dos acciones:

Auditorías periódicas de cumplimiento → verifican si se están aplicando las normas requeridas.

Programas de capacitación para empleados → enseñan al personal cómo actuar para cumplir las normas.

El objetivo y el resultado de ambas medidas es garantizar el cumplimiento de las normas del sector.

❌ Las otras opciones son incorrectas porque:

Opción	¿Por qué es incorrecta?
"Contratar un funcionario de cumplimiento a tiempo completo"	Puede ayudar, pero no es la descripción de lo que hacen las auditorías y la capacitación.
"Reducir la cantidad de registros de datos almacenados"	Minimizar datos puede reducir el alcance del cumplimiento, pero no es la función principal de auditorías y capacitación.
"Cambiar de proveedor de nube anualmente"	No tiene relación con auditorías internas ni capacitación, y además sería contraproducente.

#### Pregunta: Mitigación del incumplimiento normativo

**Amenaza:** Incumplimiento normativo
**Control:** Auditorías periódicas de cumplimiento + capacitación a empleados
**Descripción:** ✅ **Al garantizar el cumplimiento de las normas del sector**

<details>
<summary>Ver explicación</summary>

Las auditorías verifican si se están cumpliendo las leyes y estándares aplicables (ej. GDPR, HIPAA). La capacitación enseña al personal cómo manejar datos y seguir los procedimientos necesarios. Juntos, estos controles ayudan a garantizar que Jasper Manufacturing cumple con las normas del sector.

</details>


