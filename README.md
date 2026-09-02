## Martín Contreras

🇦🇷 **Español** · 🇬🇧 [English below](#-english)

---

**Administrador SAP Basis y de plataformas.** Buenos Aires, Argentina.

Más de 6 años en IT, 4 de ellos sobre SAP S/4HANA en producción bajo compliance bancario.
Última barrera de control de cambios antes de producción, y autoridad de acceso privilegiado
para el soporte internacional de SAP.

Vengo del hardware y subí por infraestructura: técnico de campo en sucursales bancarias →
responsable único de IT de un edificio → Active Directory a escala → SAP Basis → plataformas
y seguridad.

🔎 Buscando roles de **SAP Basis · Seguridad SAP · Plataformas e Infraestructura**.

### Lo que administro

**SAP Basis**
S/4HANA · HANA DB · STMS y ciclo de transportes · control de cambios sobre producción ·
PFCG / SU01 / SU10 · SPAM / SNOTE · SM36 / SM37 · SAP OSS y SAP for Me ·
gestión de acceso privilegiado

**SAP BusinessObjects**
Instalación y despliegue de BO 4.3 sobre RHEL 9 en tres ambientes, íntegramente por consola,
en red segmentada sin salida a internet · CMC · autenticación LDAP / Active Directory ·
repositorio Oracle · Tomcat y keystore Java · arquitectura de nodo APS · diagnóstico en producción

**Infraestructura**
RHEL / Linux · Red Hat OpenShift · Active Directory y migración de dominio completa · GPOs ·
diseño de reglas de firewall · balanceo F5 · certificados TLS · MDM sobre 140 dispositivos ·
operación de Data Center · redes LAN

**Operación y seguridad**
Circuito formal de service desk · ventanas de mantenimiento coordinadas · on-call sobre HANA ·
definición de política de backup · monitoreo SNMP · respuesta a incidente de ransomware ·
compliance bancario

### 🐔 GAUCHO Aves — mi proyecto propio

Software de gestión avícola para granjas de gallinas ponedoras en Argentina.

- Corre **offline** en la PC del campo. Los empleados cargan desde el celular por WiFi local.
  Las granjas no tienen conectividad: el sistema no puede depender de ella.
- Resuelve el cumplimiento **DT-e / SENASA**, que ningún competidor local cubre.
- Inventario por lote, producción, sanidad y alertas INTA.
- **Instalador todo-en-uno de Windows**: Python embebido + PostgreSQL portable + Inno Setup.
  El productor hace doble clic y anda. Sin dependencias, sin internet.
- **109 archivos de test automatizados** en el backend.

`Python` · `FastAPI` · `PostgreSQL` · `React` · `Inno Setup`

🌐 **[gauchoagro.com](https://gauchoagro.com)** — el repositorio es privado por ser un producto
comercial.

### 🛠️ Cómo trabajo

Construí GAUCHO solo y de forma autodidacta, y para lograrlo tuve que resolver un problema
aparte: **cómo sostener un proyecto largo sin depender de mi memoria.**

Terminé diseñando el andamiaje antes que el código:

- **Protocolo de orquestación de IAs** — varias asistentes proponen, una sola escribe.
  Reglas por escrito, no improvisación.
- **Memoria en archivos versionados** — el contexto vive en el repositorio, no en una
  conversación. Cualquiera, persona o IA, puede arrancar en frío sin preguntar nada.
- **Disciplina de handover** — los documentos se marcan como caducos cuando dejan de ser
  ciertos. Un documento desactualizado traiciona al que lo lee.

Es la misma lógica que aplico en infraestructura: **que cada cambio tenga dueño, registro y
forma de volver atrás.**

### 👨‍🏫 Docencia

Profesor de secundaria — sistemas, 4to año. Binario, electricidad, resistencias, estructuras
de control y robótica. Enseñar me obliga a entender de verdad, y a explicar claro bajo presión.

### 🎓 Formación

- **SAP TADM10 y TADM12** — capacitación (Buffa Sistemas, 2024)
- **Google IT Support Professional** — administración de sistemas e infraestructura
- **Licenciatura en Gestión de Tecnología de la Información** — UADE (en curso)
- Inglés: escrito fluido · oral funcional. Uso diario de documentación y soporte internacional
  de SAP.

### 📫 Contacto

[LinkedIn](https://linkedin.com/in/martinalejandrocontereras) · martinalejandrocontreras@outlook.es

<br>

---

## 🇬🇧 English

**SAP Basis and platform administrator.** Buenos Aires, Argentina.

Over 6 years in IT, 4 of them on SAP S/4HANA in production under banking compliance. I was the
last control before production, and the access authority for SAP international support.

I came up through hardware and infrastructure: field technician in bank branches → sole IT
owner of a site → Active Directory at scale → SAP Basis → platforms and security.

🔎 Open to **SAP Basis · SAP Security · Platforms and Infrastructure** roles.

### What I administer

**SAP Basis**
S/4HANA · HANA DB · STMS and transport cycle · production change control ·
PFCG / SU01 / SU10 · SPAM / SNOTE · SM36 / SM37 · SAP OSS and SAP for Me ·
privileged access management

**SAP BusinessObjects**
Installed and deployed BO 4.3 on RHEL 9 across three environments, entirely from the console,
in a segmented network with no internet access · CMC · LDAP / Active Directory authentication ·
Oracle repository · Tomcat and Java keystore · APS node architecture · production troubleshooting

**Infrastructure**
RHEL / Linux · Red Hat OpenShift · Active Directory and full domain migration · GPOs ·
firewall rule design · F5 load balancing · TLS certificates · MDM across 140 devices ·
data center operations · LAN

**Operations and security**
Formal service desk process · coordinated maintenance windows · HANA on-call ·
backup policy definition · SNMP monitoring · ransomware incident response · banking compliance

### 🐔 GAUCHO Aves — my own product

Farm management software for laying-hen poultry farms in Argentina.

- Runs **offline** on the farm's own PC. Staff enter data from their phones over the local
  WiFi. Farms have no connectivity, so the system cannot depend on it.
- Solves **DT-e / SENASA** government traceability compliance, which no local competitor covers.
- Flock inventory, production, animal health, and INTA-based alerts.
- **Self-contained Windows installer**: embedded Python + portable PostgreSQL + Inno Setup.
  The farmer double-clicks and it runs. No dependencies, no internet.
- **109 automated test files** in the backend.

`Python` · `FastAPI` · `PostgreSQL` · `React` · `Inno Setup`

🌐 **[gauchoagro.com](https://gauchoagro.com)** — the repository is private, as it is a
commercial product.

### 🛠️ How I work

I built GAUCHO alone and self-taught, and to get there I had to solve a separate problem
first: **how to sustain a long project without relying on my own memory.**

I ended up designing the scaffolding before the code:

- **An AI orchestration protocol** — several assistants propose, only one writes. Written
  rules, not improvisation.
- **Memory in version-controlled files** — context lives in the repository, not in a chat.
  Anyone, human or AI, can start cold without asking a single question.
- **Handover discipline** — documents are marked stale the moment they stop being true. A
  document that lies betrays whoever reads it.

It is the same logic I apply to infrastructure: **every change should have an owner, a record,
and a way back.**

### 👨‍🏫 Teaching

Secondary school teacher — systems, 4th year. Binary, electricity, resistors, control
structures and robotics. Teaching forces me to actually understand, and to explain clearly
under pressure.

### 🎓 Education

- **SAP TADM10 and TADM12** — training (Buffa Sistemas, 2024)
- **Google IT Support Professional Certificate** — systems and infrastructure administration
- **BSc in Information Technology Management** — UADE (in progress)
- English: fluent written · functional spoken. Daily use of SAP documentation and international
  support.

### 📫 Contact

[LinkedIn](https://linkedin.com/in/martinalejandrocontereras) · martinalejandrocontreras@outlook.es
