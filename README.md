<div align="center">

```
 ██████╗██╗   ██╗██████╗ ███████╗██████╗ ███████╗███████╗ ██████╗
██╔════╝╚██╗ ██╔╝██╔══██╗██╔════╝██╔══██╗██╔════╝██╔════╝██╔════╝
██║      ╚████╔╝ ██████╔╝█████╗  ██████╔╝███████╗█████╗  ██║     
██║       ╚██╔╝  ██╔══██╗██╔══╝  ██╔══██╗╚════██║██╔══╝  ██║     
╚██████╗   ██║   ██████╔╝███████╗██║  ██║███████║███████╗╚██████╗
 ╚═════╝   ╚═╝   ╚═════╝ ╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝ ╚═════╝
```

# 🛡️ Awesome Cybersecurity & Machine Learning

**Una lista curada de recursos, herramientas y documentos excepcionales sobre ciberseguridad e inteligencia artificial aplicada a la protección de sistemas.**

---

[![Awesome](https://img.shields.io/badge/Awesome-List-fc60a8?style=for-the-badge&logo=awesomelists&logoColor=white)](https://github.com/sindresorhus/awesome)
[![ML](https://img.shields.io/badge/Machine_Learning-Security-00c7b7?style=for-the-badge&logo=tensorflow&logoColor=white)](https://github.com/)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-brightgreen?style=for-the-badge&logo=github)](https://github.com/)
[![License](https://img.shields.io/badge/License-MIT%20%2F%20CC%204.0-blue?style=for-the-badge)](LICENSE)

</div>

---

## 📑 Tabla de Contenidos

- [🌟 Listas Destacadas](#-listas-destacadas)
- [🚨 Bases de Datos de Amenazas](#-bases-de-datos-de-amenazas-y-alertas)
- [🤖 Machine Learning para Ciberseguridad](#-machine-learning-para-ciberseguridad)
  - [📊 Datasets](#-conjuntos-de-datos-datasets)
  - [📄 Papers Académicos](#-artículos-académicos-papers)
  - [🎯 Tutoriales](#-tutoriales)
- [📚 Libros Imprescindibles](#-libros-imprescindibles)
- [🛡️ Desarrollo Seguro OWASP](#️-desarrollo-seguro-owasp)
- [🎓 Plataformas de Aprendizaje](#-plataformas-de-aprendizaje)
- [🤝 Contribuciones](#-contribuciones)
- [📄 Licencia](#-licencia)

---

## 🌟 Listas Destacadas

> Recopilaciones de software, bibliotecas y recursos de seguridad mantenidas por la comunidad.

| Recurso | Descripción |
|---------|-------------|
| [🔗 Awesome Security](https://github.com/sbilly/awesome-security) | Colección general de software, libros y recursos sobre seguridad |
| [🔗 Awesome Web Security](https://github.com/qazbnm456/awesome-web-security) | Técnicas de penetración web de vanguardia |
| [🔗 Awesome Threat Intelligence](https://github.com/hslatman/awesome-threat-intelligence) | Recursos sobre inteligencia de amenazas |

---

## 🚨 Bases de Datos de Amenazas y Alertas

> Fuentes para mantenerse actualizado sobre vulnerabilidades, CVEs y exploits activos.

```
⚠️  Monitorear estas fuentes = ventaja sobre los atacantes
```

| Fuente | Tipo | Descripción |
|--------|------|-------------|
| [ATT&CK](https://attack.mitre.org/) | 🗂️ Framework | Base de conocimientos sobre comportamiento de adversarios |
| [CVE-search](https://cve.mitre.org/) | 🔍 Base de datos | Búsqueda pública de vulnerabilidades en software y hardware |
| [Exploit Database](https://www.exploit-db.com/) | 💣 Exploits | Colección masiva mantenida por Offensive Security |
| [GitHub Advisory DB](https://github.com/advisories) | 📋 Advisories | Vulnerabilidades recientes en software open source |

---

## 🤖 Machine Learning para Ciberseguridad

> La intersección entre inteligencia artificial y seguridad ofensiva/defensiva.

```python
# El futuro de la ciberseguridad es predictivo, no reactivo
model.fit(threat_data, labels)
prediction = model.predict(network_traffic)
```

### 📊 Conjuntos de Datos (Datasets)

| Dataset | Uso | Descripción |
|---------|-----|-------------|
| [HIKARI-2021](https://zenodo.org/record/6463389) | 🌐 Redes | Análisis de tráfico de red cifrado |
| [NSL-KDD](https://www.unb.ca/cic/datasets/nsl.html) | 🔍 IDS | Clásico para detección de intrusiones |
| [Malicious URLs](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset) | 🔗 URLs | Identificación de URLs maliciosas |
| [EMBER](https://github.com/elastic/ember) | 🦠 Malware | Detección de malware estático por Elastic |

### 📄 Artículos Académicos (Papers)

> 🎓 Investigación fundamental en la aplicación de ML a la seguridad.

- 📖 **[Outside the Closed World](https://ieeexplore.ieee.org/document/5504793)** — ML para detección de intrusiones en red
- 📖 **[Adversarial SVM Learning](https://dl.acm.org/doi/10.1145/2046684.2046692)** — Máquinas de vectores de soporte adversariales
- 📖 **[DeepLog](https://dl.acm.org/doi/10.1145/3133956.3134015)** — Detección de anomalías en logs de sistema con Deep Learning

### 🎯 Tutoriales

- 🔐 **Clasificación de fuerza de contraseñas** basada en ML
- ⚡ **Detección de comandos maliciosos de PowerShell** con redes neuronales profundas
- 🤖 **Deep Learning para romper CAPTCHAs** — análisis y contramedidas

---

## 📚 Libros Imprescindibles

> Lecturas fundamentales para profesionales del sector.

```
📖 "An investment in knowledge pays the best interest." — Benjamin Franklin
```

| Libro | Autor | Enfoque |
|-------|-------|---------|
| 📕 **RTFM: Red Team Field Manual v2** | Ben Clark | Referencia rápida ofensiva |
| 📗 **The Web Application Hacker's Handbook** | Dafydd Stuttard | Hacking web aplicado |
| 📘 **Machine Learning and Security** | Chio & Freeman | ML + Ciberseguridad |
| 📙 **Ethical Hacking** | Daniel G. Graham | Hacking ético práctico |

---

## 🛡️ Desarrollo Seguro (OWASP)

> Estándares y herramientas de referencia para la seguridad de aplicaciones.

<table>
<tr>
<td align="center">

**🔟 OWASP Top 10**  
Los 10 riesgos más críticos  
en aplicaciones web

</td>
<td align="center">

**🧃 OWASP Juice Shop**  
App web intencionalmente  
insegura para entrenamiento

</td>
<td align="center">

**⚡ OWASP ZAP**  
Herramienta integrada  
de pruebas de penetración

</td>
</tr>
</table>

- [OWASP Top 10](https://owasp.org/www-project-top-ten/) — Riesgos críticos para aplicaciones web
- [OWASP Juice Shop](https://owasp.org/www-project-juice-shop/) — Laboratorio de práctica vulnerable
- [OWASP ZAP](https://www.zaproxy.org/) — Proxy de interceptación y scanner

---

## 🎓 Plataformas de Aprendizaje

> Entrena, practica y certifica tus habilidades.

| Plataforma | Tipo | Nivel |
|------------|------|-------|
| [🟥 TryHackMe](https://tryhackme.com/) | Laboratorios guiados | Principiante → Avanzado |
| [⬛ HackTheBox](https://www.hackthebox.com/) | CTF / Máquinas reales | Intermedio → Avanzado |
| [🔵 Cybrary](https://www.cybrary.it/) | Cursos estructurados | Todos los niveles |
| [🟠 PortSwigger Academy](https://portswigger.net/web-security) | Web Security | Intermedio |

---


---

## 📄 Licencia

Este proyecto está bajo licencia **WOLVESTI** y **Creative Commons Attribution-ShareAlike 4.0 International**.

---

<div align="center">

**⭐ Si este repositorio te fue útil, dale una estrella**

[![GitHub stars](https://img.shields.io/github/stars/kaleth4?style=social)](https://github.com/kaleth4)

*Mantenido por [kaleth4](https://github.com/kaleth4) · WolvesTI · Bogotá, Colombia*

