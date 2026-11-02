# Hi, I'm Mauricio Barrera 👋

**Full-stack developer · GIS · Cloud · Technical leadership**  
📍 Montevideo, Uruguay · 🏢 [ICA – Ingenieros Consultores Asociados](https://www.ica.com.uy)

I build web and mobile applications, APIs, and geospatial solutions. At **ICA**, I combine hands-on development with team leadership and project coordination, connecting software, ArcGIS, and cloud infrastructure to support real operational workflows.

My background in systems administration also shapes how I build: deployment, monitoring, and ongoing operation are part of the work.

## 🛠️ What I work on

- 🗺️ **Geospatial applications:** interactive web maps with the ArcGIS Maps SDKs, publishing and managing data on ArcGIS Enterprise and ArcGIS Online, spatial data in PostGIS, and operational dashboards for teams that work in the field.
- 💻 **Web and mobile development:** Angular and React front ends, Flutter apps, and APIs in .NET, Node.js, and Python, including authentication and integrations between systems.
- 🧩 **Internal tools and business software:** extending open-source platforms to fit how a company actually works, such as time tracking, capacity planning, and reporting in Kimai, or self-hosted Odoo deployments.
- 🤖 **AI with spatial data:** experimenting with language models that query GIS layers and answer questions on a map.
- ☁️ **Cloud and operations:** Azure, Docker, and IIS deployments, CI/CD with Azure DevOps and GitHub Actions, infrastructure migrations, and logging, metrics, and alerting with Grafana, Prometheus, Loki, and OpenTelemetry.
- 🧭 **Technical delivery:** turning requirements into implementation plans, reviewing code, mentoring developers, and coordinating releases with clients.

## 🧰 Technologies

**Frontend**  
<img src="https://skillicons.dev/icons?i=ts,angular,react,vite,html,css" alt="TypeScript, Angular, React, Vite, HTML, CSS" />

**Mobile**  
<img src="https://skillicons.dev/icons?i=flutter,dart" alt="Flutter, Dart" />

**Backend**  
<img src="https://skillicons.dev/icons?i=cs,dotnet,py,nodejs,php,symfony" alt="C#, .NET, Python, Node.js, PHP, Symfony" />

**GIS and data**  
<img src="https://skillicons.dev/icons?i=postgres" alt="PostgreSQL" />&nbsp;
<img src="https://img.shields.io/badge/ArcGIS-2C7AC3?style=for-the-badge&logo=arcgis&logoColor=white" alt="ArcGIS" height="48" />
<img src="https://img.shields.io/badge/PostGIS-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostGIS" height="48" />
<img src="https://img.shields.io/badge/SQL_Server-CC2927?style=for-the-badge&logo=microsoftsqlserver&logoColor=white" alt="SQL Server" height="48" />

**Cloud, delivery and observability**  
<img src="https://skillicons.dev/icons?i=azure,docker,githubactions,linux,grafana,prometheus" alt="Azure, Docker, GitHub Actions, Linux, Grafana, Prometheus" />&nbsp;
<img src="https://img.shields.io/badge/Azure_DevOps-0078D7?style=for-the-badge&logo=azuredevops&logoColor=white" alt="Azure DevOps" height="48" />
<img src="https://img.shields.io/badge/OpenTelemetry-425CC7?style=for-the-badge&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" height="48" />

## 🎓 Background

Before moving into software development, I worked in IT support and systems administration at Uruguay’s Ministry of Defence. My studies in Computer Engineering and Business Administration at Universidad de la República complement my work across engineering and project delivery.

<a href="https://learn.microsoft.com/api/credentials/share/en-us/MauricioBarrera-4176/404C4EFB9C9B3F37?sharingId=D35033A1D1EA731C"><img src="https://learn.microsoft.com/en-us/media/learn/certification/badges/microsoft-certified-fundamentals-badge.svg" width="64" height="64" alt="Microsoft Certified: Azure Fundamentals" /></a>

## 📬 Get in touch

<a href="mailto:mauriciodbarrera@gmail.com"><img src="https://img.shields.io/badge/Email-mauriciodbarrera%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<a href="https://www.linkedin.com/in/mauribarrera"><img src="https://img.shields.io/badge/LinkedIn-mauribarrera-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>

## 💼 Work at ICA

Most of my work is client software that isn't public. These are some of the projects I've worked on, described without client names.

- 🔥 **Wildfire and firefighting operations platform**: an integrated system for a national forestry organization that records smoke and fire events, alerts affected properties, dispatches ground and air resources, and measures response times across the season.  
  *TypeScript · .NET · ArcGIS Enterprise · Azure*
- ⛽ **Fuel distribution logistics platform**: a full-stack application that combines operational and geospatial data, with map viewers for monitoring routes and vehicles in real time.  
  *Angular · .NET · ArcGIS Maps SDK for JavaScript · ArcGIS Enterprise*
- 🌾 **Agricultural traceability GIS API**: a REST component that validates cadastral parcels and exchanges data with a national agricultural traceability platform built for EUDR compliance.  
  *ArcGIS · REST APIs*
- 🐘 **Global conservation impact map**: an interactive map of field operations and activity data, embedded in the platform of a global wildlife-conservation nonprofit.  
  *React · ArcGIS Maps SDK for JavaScript · TypeScript*
- 🏘️ **Cadastral viewer and property-tax records**: a configurable Angular viewer and a .NET API for searching records, designed to be deployed across multiple counties and municipalities.  
  *Angular · .NET · ArcGIS Maps SDK for JavaScript*
- 🚚 **Freight analytics frontend**: a new Angular 19 front end for a freight logistics platform, with map components for analyzing transportation and distribution data.  
  *Angular 19 · ArcGIS Maps SDK for JavaScript*
- 🏗️ **Enterprise GIS platform migration**: moving a large ArcGIS Enterprise deployment from 10.9.1 to 11.3, including compatibility assessment, service migration and platform validation.  
  *ArcGIS Enterprise · ArcGIS Server*

## 📌 Selected public projects

### Kimai plugins

A suite of open-source plugins for [Kimai](https://www.kimai.org), the self-hosted time-tracking app, built to run time tracking, capacity planning and reporting for a consulting team. They hook into Kimai's own working-time calculation, so absences, locked months, planning and reports all work from the same numbers.

| Plugin | What it does |
| --- | --- |
| [AbsencesBundle](https://github.com/moui/AbsencesBundle) | Company holiday calendar and per-person absences that feed Kimai's working times, with vacation balances and a report |
| [WeeklyPlanningBundle](https://github.com/moui/WeeklyPlanningBundle) | Weekly capacity planning per person and project, with budget forecasts and live plan-vs-actual deviations |
| [MissingHoursBundle](https://github.com/moui/MissingHoursBundle) | Shows people the hours they're missing, gives team leads a report, and emails reminders |
| [WorkingTimeLockBundle](https://github.com/moui/WorkingTimeLockBundle) | Snapshots and locks completed months so later contract changes can't rewrite past balances |
| [ManagementReportsBundle](https://github.com/moui/ManagementReportsBundle) | Hours summary with KPIs, charts and concentration rankings, plus contract and inactive-customer reports |
| [SupportHoursBundle](https://github.com/moui/SupportHoursBundle) | Support hours per customer, exported to Excel and emailed monthly |
| [GuidelinesBundle](https://github.com/moui/GuidelinesBundle) | Admin-edited guidelines on the dashboard, plus rules for timesheet descriptions and future times |

**PHP · Symfony · Doctrine · Twig · PHPStan · GitHub Actions** · English and Spanish · MIT

### [Women’s representation in Montevideo](https://github.com/moui/techy24-representatividad_mujeres_mvd)

An interactive map exploring women’s representation in Montevideo’s streets and public spaces. Created for a Techy workshop at ICA, the demo introduces map layers, styling, comparison tools, and charts through a sequence of commits.

**TypeScript · ArcGIS Maps SDK for JavaScript · Web Components · Vite**

### [Infortac website](https://github.com/moui/infortac-website)

A Spanish-language company website with a product showcase, contact flows through email and WhatsApp, and analytics with visitor opt-in. The repository includes development and publishing instructions, automated checks, and analytics documentation.

**React · Vite · GitHub Actions**
