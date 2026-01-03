
# Portafolio y aspectos destacados

[Read in English](./README.md)

<table>
	<tr>
		<td width="110" align="center">
			<img src="https://avatars.githubusercontent.com/u/76532366" alt="avatar" width="96" />
		</td>
		<td valign="middle">
			<strong style="font-size:18px">Nicolás Sabogal</strong><br/>
			Ingeniero de Sistemas<br/>
			<br/>
			<a href="mailto:ndsabogalv@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-ndsabogalv@gmail.com-blue?style=flat&logo=gmail&logoColor=white"/></a>
			<a href="https://www.linkedin.com/in/ndsabogalv/"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-ndsabogalv-blue?style=flat&logo=linkedin&logoColor=white"/></a>
			<img alt="Location" src="https://img.shields.io/badge/Location-Bogot%C3%A1%2C%20Colombia-lightgrey?style=flat&logo=googlemaps&logoColor=white"/>
			<a href="#contact"><img alt="Open to work" src="https://img.shields.io/badge/Open%20to%20work-Full--time-brightgreen?style=flat"/></a>
		</td>
	</tr>
</table>

---

> Ayudo a equipos a entregar sistemas backend listos para producción y aplicaciones de negocio que optimizan operaciones, mejoran reportes y soportan flujos administrativos cotidianos.

**Keywords:** Backend Engineer · Production APIs · Serverless · Infrastructure as Code · Terraform · CI/CD · Database Design · ETL Pipelines · Machine Learning · Observability · Docker

## Tabla de contenidos

- [Resumen profesional](#professional-summary)
- [Competencias principales](#core-skills)
- [Logros seleccionados](#selected-achievements)
- [Proyectos destacados](#highlighted-projects)
- [Contacto y disponibilidad](#contact)
- [Cómo trabajo](#how-i-work)
- [Idiomas](#languages)
- [Estadísticas de GitHub](#stats)

---

<a id="professional-summary"></a>

## Resumen profesional

Construyo sistemas backend fiables, arquitecturas serverless para procesamiento de datos y APIs de producción. Diseño esquemas relacionales y NoSQL normalizados, implemento pipelines de CI/CD robustos con Infraestructura como Código (Terraform) y desarrollo procesos ETL escalables para aplicaciones basadas en datos. Me enfoco en arquitecturas pragmáticas, observabilidad y pruebas automatizadas (alcanzando hasta un 95% de cobertura) para entregar resultados predecibles y de alta calidad.

**Buscando:** Backend Engineer; Data Engineer; DevOps/Cloud Engineer; Database Designer.

- **Backend & Serverless Engineer:** Construir y mantener APIs de producción y funciones serverless con enfoque en fiabilidad y observabilidad.
- **Data / ETL Engineer:** Implementar pipelines de ingestión y ETL robustos que preparen datasets validados para analytics y ML, aprovechando arquitecturas serverless para escalabilidad.
- **DevOps e Infraestructura:** Implementar pipelines de CI/CD e Infraestructura como Código (Terraform) para automatizar despliegues y asegurar la paridad de entornos.
- **Database Designer:** Diseñar esquemas relacionales y NoSQL normalizados, optimizando consultas para casos transaccionales y de reporting.
- **Machine Learning Engineer:** Prototipar modelos y producir datasets listos para entrenamiento para convertir investigación en funcionalidades de producto.

---

<a id="core-skills"></a>

## Competencias principales

- **Backend:** Java (Spring Boot), Python (FastAPI, AWS Lambda), Node.js (Express)
- **Bases de datos y modelado:** PostgreSQL, DynamoDB, diseño de esquemas relacionales, normalización, indexación y optimización de consultas
- **Datos & ETL:** Pipelines ETL, ingestión de datos (APIs, WebSocket), Pandas, NumPy, limpieza y transformaciones de datos
- **Machine Learning:** Prototipado con scikit-learn, Keras; feature engineering y preprocesamiento de datos
- **Infraestructura:** Terraform, AWS (S3, Lambda, API Gateway), LocalStack, Docker, GitHub Actions CI/CD
- **Prácticas:** Diseño de APIs, tests automatizados (unitarias, integración, E2E, coverage), observabilidad, arquitectura liviana

---

<a id="selected-achievements"></a>

## Logros seleccionados

- **Lideré entregas inter-equipos:** Coordiné múltiples equipos, definí límites de servicios y aseguré la entrega a tiempo de funcionalidades centrales (horarios, ubicaciones, UI).
- **CI/CD e Infraestructura como Código:** Desarrollé una aplicación Python serverless con un pipeline de CI/CD completo (GitHub Actions) e Infraestructura como Código (Terraform). Alcancé un ~95% de cobertura de pruebas (unitarias, integración y E2E), aplicando quality gates estrictos.
- **Modelado relacional e implementación:** Traduje un diagrama ER a un esquema relacional normalizado en PostgreSQL, implementé el esquema en PostgreSQL e implementé el modelo JPA para reforzar la integridad y simplificar consultas transaccionales.
- **Ingestión de datos confiable & ETL:** Implementé un receptor FastAPI/WebSocket que valida, normaliza y persiste series temporales PPG, generando artefactos CSV y salidas ETL para análisis downstream.
- **Despliegue de Modelos ML & Procesamiento de Señales:** Desarrollé un clasificador de Fibrilación Auricular basado en ventanas utilizando modelos híbridos de Keras/TensorFlow que procesa señales PPG completas. Implementé detección automática de frecuencia, re-muestreo y pipelines de normalización robusta para manejar diversas fuentes de datos de wearables.
- **Productividad y reproducibilidad para desarrolladores:** Dockericé componentes backend y adapté un starter Dockerizado de Node.js con live-reload para acelerar la incorporación y asegurar entornos reproducibles de desarrollo.
- **Seguridad & buenas prácticas en APIs:** Apliqué autenticación JWT, manejo consistente de errores, versionado y hooks de observabilidad para mejorar mantenibilidad y seguridad del servicio.

---

<a id="highlighted-projects"></a>

## Proyectos destacados

- **PyKata CI/CD Showcase** — Aplicación Python serverless para explorar y ejecutar katas de programación. Implementé un pipeline de CI/CD completo con GitHub Actions, Infraestructura como Código con Terraform (AWS/LocalStack) y alcancé un ~95% de cobertura de pruebas. Utiliza FastAPI para desarrollo local y AWS Lambda para producción. Stack: Python (FastAPI, Lambda), Terraform, GitHub Actions, LocalStack, DynamoDB, S3. Repo: https://github.com/MrPocketMonsters/pykata
- **Plataforma Administrativa para Entidades Promotoras de Salud (EPS)** — Proyecto de grado (13 desarrolladores). Coordiné tecnologías y tareas entre cuatro equipos y lideré el equipo de Instituciones Prestadoras de Salud (IPS) (horarios, salas, doctores). Implementé el esquema normalizado en PostgreSQL, el modelo JPA completo, dockericé el aplicativo e implementé autenticación basada en JWT. Stack: React, Spring Boot, PostgreSQL, Docker. Repo: https://github.com/EdwinGuevarahub/Ingenieria-de-software-II-EPS
- **PPG Data Receiver & AF Classifier** — Sistema end-to-end para la ingestión y análisis de PPG de wearables. Cuenta con un receptor FastAPI/WebSocket para visualización en tiempo real y clasificación de señales recibidas utilizando modelos híbridos Keras/TensorFlow. El sistema maneja re-muestreo automático, filtrado de señales (Butterworth) y clasificación basada en ventanas de Fibrilación Auricular/Ritmo Sinusal con puntuación de confianza. Stack: FastAPI, TensorFlow/Keras, Pandas, NumPy. Repo: https://github.com/MrPocketMonsters/PPGDataReceiverAPI
- **Node API Starter** — Starter Express dockerizado optimizado para desarrollo rápido de APIs y entornos locales reproducibles; soporta live-reload para productividad del desarrollador (diseñado para integrar hooks de ingestión/ETL). Stack: Node.js, Express, Docker. Repo: https://github.com/MrPocketMonsters/node_api

---

<a id="contact"></a>

## Contacto y disponibilidad

- **Open to:** Roles a medio tiempo — Remoto, o presencial en Bogotá, Colombia.
- **Email:** <ndsabogalv@gmail.com>
- **LinkedIn:** https://www.linkedin.com/in/ndsabogalv/

---

<a id="how-i-work"></a>

## Cómo trabajo

- Entrego código probado, documentado y APIs bien definidas.
- Prefiero comunicación directa y prioridades técnicas claras.
- Uso contenedores y CI/CD para asegurar entregas reproducibles.

---

<a id="languages"></a>

## Idiomas

- **Español:** Nativo
 - **Inglés:** C1 — Certificado EF SET ([verificar](https://cert.efset.org/en/2PD38G))

---

<a id="stats"></a>

## Estadísticas de GitHub

![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MrPocketMonsters&layout=compact)

<div style="border:1px solid #e1e4e8; border-radius:8px; padding:12px; background:#ffffff; max-width:760px;">
	<p style="margin:0 0 8px 0;">
		<span style="color:#007ec6; padding:4px 8px; border-radius:4px; font-weight:600; font-size:17px;">Contribution Heatmap</span>
	</p>
	<p style="margin:8px 0 0 0;">
		<img src="https://ghchart.rshah.org/MrPocketMonsters" alt="Contribution Heatmap" />
	</p>
</div>
