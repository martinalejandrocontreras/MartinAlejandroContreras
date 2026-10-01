## Martín Contreras

🇦🇷 **Español** · 🇬🇧 [English below](#-english)

---

**Administrador SAP Basis y de plataformas IT.** Buenos Aires, Argentina.

Más de 6 años en IT, 4 de ellos en GIRE bajo compliance bancario y casi 2 administrando SAP en
producción (S/4HANA Basis y BusinessObjects). Fui la última barrera de control de cambios antes de
producción y la autoridad de acceso privilegiado para el soporte internacional de SAP.

En los últimos meses me apoyé fuerte en la **IA** para construir mi propio producto de punta a punta.

Vengo del hardware y subí por infraestructura: técnico de campo en sucursales bancarias →
único técnico on-site de un edificio, mano derecha de mi jefe → Active Directory a escala →
SAP Basis → plataformas y seguridad.

🔎 Buscando roles de **SAP Basis · Seguridad SAP · Plataformas e Infraestructura**.

📄 **Dos CVs para elegir** — Infraestructura (IT Platform Administrator) y SAP Basis:
[martinalejandrocontreras.github.io/#cv](https://martinalejandrocontreras.github.io/#cv)

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
RHEL / Linux · Red Hat OpenShift · APIs e IBM API Gateway · Active Directory y migración de
dominio completa · GPOs · diseño de reglas de firewall · integración con balanceador F5 ·
certificados TLS · servidor de backup en cinta HPE LTO-7 · VMware · MDM sobre 140 dispositivos,
incluida la configuración de los Zebra · operación de Data Center · redes LAN

**Operación y seguridad**
Circuito formal de service desk · ventanas de mantenimiento coordinadas · on-call sobre HANA ·
definición de política de backup · monitoreo SNMP · respuesta a incidente de ransomware ·
compliance bancario

### 🐔 Gaucho Agro · Aves — mi proyecto propio

Software de gestión avícola para granjas de gallinas ponedoras en Argentina. Lo diseñé y dirijo su
construcción: **el código lo escribe la IA bajo mi dirección**, con Claude Code y Gemini.

- Corre **offline** en la PC del campo. Los empleados cargan desde el celular por WiFi local.
  Las granjas no tienen conectividad: el sistema no puede depender de ella.
- Resuelve el cumplimiento **DT-e / SENASA**, que ningún competidor local cubre.
- Inventario por lote, producción, sanidad, economía, incubación y alertas con valores INTA.
- **Instalador todo-en-uno de Windows**: Python embebido + PostgreSQL portable + Inno Setup.
  El productor hace doble clic y anda. Sin dependencias, sin internet.
- **Más de 300 tests automatizados** en el backend.

`Python` · `FastAPI` · `PostgreSQL` · `React` · `Inno Setup`

🌐 **[gauchoagro.com](https://gauchoagro.com)** — el repositorio es privado por ser un producto
comercial.

### 🤖 Cómo trabajo con IA

Gaucho Agro lo construí solo, y la IA fue parte del equipo desde el primer día. Para que funcionara
tuve que resolver un problema aparte: **cómo hacer que una IA trabaje con reglas, y no de memoria.**

- **Varias IAs, una sola escribe** — proponen varias, escribe una sola, con reglas por escrito.
  Comparé modelos sobre la misma especificación: donde la spec es precisa convergen; donde calla,
  aparece el criterio de cada uno.
- **Reglas que se aplican solas** — hooks que le reinyectan a la IA la tarea en curso en cada
  mensaje, y skills propias: una arranca cada sesión al día, otra guarda el avance haciendo build,
  tests y commit, solo si todo pasa.
- **Memoria en archivos, no en el chat** — el contexto vive en archivos versionados: cualquiera,
  persona o IA, arranca en frío sin preguntar nada. Y un documento se marca vencido apenas deja de
  ser cierto.
- **La IA escribe, los tests deciden** — más de 300 tests automatizados son la puerta: nada se
  commitea si no pasan.

Es la misma lógica que aplico en infraestructura: **que cada cambio tenga dueño, registro y forma
de volver atrás.** Y es lo que quiero llevar a la operación de plataformas: automatizar lo
repetitivo de Basis con IA, sin perder el control de cambios.

### 👨‍🏫 Docencia

Profesor de informática en secundaria (DGCyE, Provincia de Buenos Aires), desde enero de 2025 —
4to año: binario, electricidad, resistencias, estructuras de control y robótica. Enseñar me obliga
a entender de verdad, y a explicar claro bajo presión.

### 🎓 Formación

- **SAP TADM10 y TADM12** — capacitación (Buffa Sistemas, 2024)
- **Google IT Support Professional** — administración de sistemas e infraestructura
- **Licenciatura en Gestión de Tecnología de la Información** — UADE (en curso)
- Inglés: escrito fluido · oral funcional. Uso diario de documentación y soporte internacional
  de SAP.

### 📫 Contacto

🌐 **[martinalejandrocontreras.github.io](https://martinalejandrocontreras.github.io)** — portfolio completo y los dos CVs

[LinkedIn](https://linkedin.com/in/martinalejandrocontereras) · martinalejandrocontreras@outlook.es

<br>

---

## 🇬🇧 English

**SAP Basis and IT platform administrator.** Buenos Aires, Argentina.

6+ years in IT, including 4 years at GIRE under banking compliance and nearly 2 years administering
SAP in production (S/4HANA Basis and BusinessObjects). I was the final change-control gate before
production, and the privileged-access authority for SAP international support.

Over the last few months I've leaned heavily on **AI** to build my own product end to end.

I came up through hardware and infrastructure: field technician in bank branches → sole on-site
technician of a building, my manager's right hand → Active Directory at scale → SAP Basis →
platforms and security.

🔎 Open to **SAP Basis · SAP Security · Platforms and Infrastructure** roles.

📄 **Two CVs to choose from** — Infrastructure (IT Platform Administrator) and SAP Basis:
[martinalejandrocontreras.github.io/#cv](https://martinalejandrocontreras.github.io/#cv)

### What I administer

**SAP Basis**
S/4HANA · HANA DB · STMS and transport cycle · production change control ·
PFCG / SU01 / SU10 · SPAM / SNOTE · SM36 / SM37 · SAP OSS and SAP for Me ·
privileged access management

**SAP BusinessObjects**
Installation and deployment of BO 4.3 on RHEL 9 across three environments, entirely from the
console, in a segmented network with no internet access · CMC · LDAP / Active Directory
authentication · Oracle repository · Tomcat and Java keystore · APS node architecture ·
production troubleshooting

**Infrastructure**
RHEL / Linux · Red Hat OpenShift · APIs and IBM API Gateway · Active Directory and full domain
migration · GPOs · firewall rule design · F5 load-balancer integration · TLS certificates ·
HPE LTO-7 tape backup server · VMware · MDM across 140 devices, including Zebra configuration ·
data center operations · LAN

**Operations and security**
Formal service desk process · coordinated maintenance windows · HANA on-call ·
backup policy definition · SNMP monitoring · ransomware incident response · banking compliance

### 🐔 Gaucho Agro · Aves — my own product

Farm management software for laying-hen poultry farms in Argentina. I designed it and I direct its
build: **the code is written by AI under my direction**, with Claude Code and Gemini.

- Runs **offline** on the farm's own PC. Staff enter data from their phones over the local
  WiFi. Farms have no connectivity, so the system cannot depend on it.
- Solves **DT-e / SENASA** government traceability compliance, which no local competitor covers.
- Flock inventory, production, animal health, economics, incubation, and INTA-based alerts.
- **Self-contained Windows installer**: embedded Python + portable PostgreSQL + Inno Setup.
  The farmer double-clicks and it runs. No dependencies, no internet.
- **300+ automated tests** in the backend.

`Python` · `FastAPI` · `PostgreSQL` · `React` · `Inno Setup`

🌐 **[gauchoagro.com](https://gauchoagro.com)** — the repository is private, as it is a
commercial product.

### 🤖 How I work with AI

I built Gaucho Agro alone, and AI was part of the team from day one. To make it work I had to
solve a separate problem first: **how to get an AI to work by rules, not by memory.**

- **Several AIs, only one writes** — several propose, only one writes, under written rules. I
  compared models on the same spec: where the spec is precise they converge; where it is silent,
  each model's judgment shows.
- **Rules that enforce themselves** — hooks that re-inject the current task into every message,
  and custom skills: one starts each session up to date, another saves progress by building,
  testing and committing, only if everything passes.
- **Memory in files, not in the chat** — context lives in version-controlled files, so anyone,
  human or AI, can start cold without asking a single question. And a document is marked stale
  the moment it stops being true.
- **AI writes, tests decide** — 300+ automated tests are the gate: nothing gets committed unless
  they pass.

It is the same logic I apply to infrastructure: **every change should have an owner, a record,
and a way back.** And it is what I want to bring to platform operations: automating the
repetitive side of Basis with AI, without losing change control.

### 👨‍🏫 Teaching

Computer science teacher at a secondary school (DGCyE, Province of Buenos Aires), since January
2025 — 4th year: binary, electricity, resistors, control structures and robotics. Teaching forces
me to actually understand, and to explain clearly under pressure.

### 🎓 Education

- **SAP TADM10 and TADM12** — training (Buffa Sistemas, 2024)
- **Google IT Support Professional Certificate** — systems and infrastructure administration
- **BSc in Information Technology Management** — UADE (in progress)
- English: fluent written · functional spoken. Daily use of SAP documentation and international
  support.

### 📫 Contact

[LinkedIn](https://linkedin.com/in/martinalejandrocontereras) · martinalejandrocontreras@outlook.es

🌐 **[martinalejandrocontreras.github.io](https://martinalejandrocontreras.github.io)** — full portfolio and both CVs
