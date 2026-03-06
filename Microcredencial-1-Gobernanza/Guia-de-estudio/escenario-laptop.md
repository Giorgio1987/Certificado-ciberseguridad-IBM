## 📝 Caso Práctico: Seguridad en el Despliegue de Equipos
**Escenario:** Preparación de una laptop corporativa con datos de clientes sin instalación inmediata de antivirus.

**Mi Análisis y Respuesta:**
Entregar un equipo con datos sensibles sin protección activa rompe el principio de **Defensa en Profundidad**. El usuario se expone a riesgos críticos donde la "responsabilidad" no es suficiente:

* **Ransomware (Amenaza Principal):** Un solo archivo malicioso podría cifrar los datos de los clientes, exigiendo un rescate y paralizando la startup.
* **Spyware/Keyloggers:** Riesgo de robo de credenciales de acceso a la red interna al navegar por internet.
* **Gusanos (Worms):** Posibilidad de infección y propagación automática hacia otros equipos de la empresa a través de la red local.

**Lección Aprendida:** Los controles técnicos (Antivirus/EDR) deben preceder siempre al uso por parte del usuario. Como dice el estándar **NIST**, la configuración de seguridad debe estar aplicada antes del despliegue del activo.