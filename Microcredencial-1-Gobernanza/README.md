# Microcredencial 1: Gobernanza, Riesgo y Cumplimiento 🛡️

En este módulo, exploro las diversas ciberamenazas y las mejores prácticas para combatirlas, enfocándome en la protección de activos y la gestión de riesgos humanos y físicos.

## 🎯 Objetivos de Aprendizaje
Basado en el programa oficial de IBM SkillsBuild:
* **Análisis de Impacto:** Evaluar cómo las ciberamenazas afectan a los sistemas y procesos de una organización.
* **Mitigación de Malware:** Uso práctico de herramientas como Malwarebytes para eliminar virus y amenazas.
* **Ingeniería Social:** Identificación de tácticas de phishing en correos electrónicos.
* **Seguridad Física:** Desarrollo de planes de control para proteger edificios y dispositivos.

---

## 🗒️ Temario y Notas de Estudio

### 1. Tipos de Malware
* **Definición:** Software malicioso diseñado para infiltrarse o dañar un sistema.
* **Práctica:** Ejecución de escaneos de antivirus para detectar y eliminar amenazas comunes.

### 2. Ingeniería Social
* **Concepto:** Explotación de vulnerabilidades en la psicología humana.
* **Phishing:** Análisis de correos fraudulentos y sus características principales para evitar el robo de credenciales.

### 3. Amenazas Físicas y Controles Ambientales
* Protección de activos valiosos (servidores, dispositivos).
* **Controles Físicos:** Diseño de planes de seguridad para el acceso a instalaciones.

---

## 🛠️ Laboratorios Realizados
* [ ] Escaneo de amenazas con Malwarebytes.
* [ ] Análisis de casos de Phishing.
* [ ] Creación de un plan de control de seguridad física.

---

## 🌐 Peligros al Navegar por Internet
Al procesar y compartir información digital, nos exponemos a una gran variedad de ataques diseñados para obtener control o causar daño.

### 🚨 Tipos de Amenazas Digitales
* **Virus:** Cualquier programa que infecta un sistema sin permiso del usuario para ganar control o causar daño.
* **Adware:** Software no deseado diseñado para mostrar anuncios en el navegador, exponiéndonos a ataques maliciosos.
* **Keyloggers:** Herramientas que registran cada tecla presionada, permitiendo el robo de contraseñas, datos médicos y financieros.

### 🛡️ Controles de Seguridad y Soluciones
Para prevenir que estos ataques tengan éxito, se deben implementar diferentes tipos de controles:
* **Basados en Software:** Uso de programas antivirus y bloqueadores de anuncios (ad blockers).
* **Estándares de la Industria:** Implementación de marcos de trabajo como **CIS Controls** y **NIST**.


---
> *“A medida que los atacantes se vuelven más inteligentes, es vital conocer las amenazas y las debilidades que buscan explotar.”*
---

![EXPLICACIÓN DE LOS PELIGROS](../img/peligros-sin-antivirus.png)
 
### 🦠 El Virus Informático: El riesgo de la interacción
Inspirados en los virus biológicos, estos programas se replican y propagan dañando los sistemas a su paso.

* **Definición:** Malware que se adjunta a archivos o programas legítimos para replicarse y saltar de un dispositivo a otro.
* **El factor humano (Activación):** Los virus **necesitan interacción del usuario** para ejecutarse. No actúan solos; necesitan que alguien "abra la puerta".
* **Vectores de infección comunes:**
    * Archivos adjuntos en correos electrónicos (documentos que parecen inofensivos pero son ejecutables disfrazados).
    * Descargas desde sitios web no confiables.
    * Conexión de dispositivos ya infectados (como pendrives o discos externos) a tu equipo.
* **Impacto y Daño:** * Disrupción de operaciones y alteración de datos críticos.
    * Borrado completo de discos duros.
    * El daño se intensifica exponencialmente a medida que el virus logra replicarse y extenderse por la red.
    ![I LOVE YOU](../img/I-LOVE-YOU.png)

    **Worm (Gusano):** Malware independiente que se propaga automáticamente a través de las redes explotando vulnerabilidades, a diferencia del virus sin necesidad de intervención humana.
    Los gusanos pueden eliminar datos, saturar redes, degradar el rendimiento del hardware e instalar otro software malicioso.

    ![Stuxnet worn](../img/Stuxnet.png)
---

## ☣️ Caso de Estudio: El Gusano Stuxnet
Stuxnet es uno de los ejemplos más famosos de cómo un malware puede saltar del mundo digital al mundo físico para causar daño real.

### 🔍 ¿Qué fue Stuxnet?
* **Definición:** Un gusano informático extremadamente complejo diseñado para sabotear infraestructuras críticas (específicamente centrífugas de procesamiento de uranio en Irán).
* **Vector de Infección:** Se propagó inicialmente a través de **unidades USB infectadas**, logrando saltar el "Air Gap" (aislamiento de red).
* **Modus Operandi:** * El malware enviaba señales falsas a los sensores de control industrial para ocultar su presencia mientras dañaba físicamente la maquinaria.
    * Fue diseñado para operar de forma totalmente sigilosa y mezclarse con las operaciones normales de la planta.

---

## ⏱️ Vulnerabilidades de Día Cero (Zero-day)
Stuxnet fue revolucionario porque utilizó múltiples vulnerabilidades de este tipo al mismo tiempo.

* **Concepto:** Son fallos de seguridad en un software o hardware que son previamente desconocidos por el fabricante.
* **El Riesgo:** Como el fabricante aún no conoce la debilidad, **no existe un parche o actualización** disponible para arreglarla.
* **Ataque de Día Cero:** Ocurre cuando un atacante descubre y explota esta vulnerabilidad antes de que el desarrollador tenga oportunidad de crear una defensa.

---
**Trojan (Troyano):** Se disfraza de software legítimo y útil para engañar al usuario. Su objetivo suele ser crear "puertas traseras" (backdoors) para el atacante.
Los atacantes disfrazan los troyanos como programas o archivos benignos, como juegos, fondos de pantalla u otras descargas.
Cuando ejecutas el troyano, el atacante puede controlar tu ordenador de forma remota, robar datos, espiar tu actividad, instalar malware,o realizar otras acciones maliciosas.
Y al igual que los gusanos, algunos troyanos no requieren la interacción del usuario para ejecutarse.

***
![EMOTET](../img/Emotet.png)

## 🐎 Troyanos (Trojans): El engaño como arma
A diferencia de los virus, los troyanos no se replican por sí mismos; utilizan el engaño para que el usuario les permita la entrada al sistema.

### 🔍 Caso de Estudio: Emotet
**Emotet** es un troyano avanzado diseñado originalmente para robar credenciales bancarias.

* **Vector de ataque:** Se propaga mediante archivos adjuntos de correo electrónico disfrazados de documentos de Microsoft Word.
* **Activación:** El malware se activa en cuanto el usuario hace clic en el archivo adjunto.
* **Persistencia:** Una vez dentro, utiliza ataques de **fuerza bruta** para adivinar contraseñas y propagarse por la red hacia unidades compartidas.



### 🔑 Concepto: Ataque de Fuerza Bruta (Brute Force)
* **Definición:** Es un método de "ensayo y error" donde el atacante intenta adivinar contraseñas o credenciales probando múltiples combinaciones hasta encontrar la correcta.
* **Uso en Emotet:** Sirve para ganar acceso a otros equipos y servidores dentro de la misma red una vez que el troyano inicial ha infectado una máquina.