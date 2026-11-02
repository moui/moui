# Hi, I'm Mauricio Barrera 👋

**Full-stack developer · GIS · Cloud · Technical leadership**  
📍 Montevideo, Uruguay · 🏢 [ICA – Ingenieros Consultores Asociados](https://www.ica.com.uy)

I build web and mobile applications, APIs, and geospatial solutions. At **ICA**, I combine hands-on development with team leadership and project coordination, connecting software, ArcGIS, and cloud infrastructure to support real operational workflows.

My background in systems administration also shapes how I build: deployment, monitoring, and ongoing operation are part of the work.

## 🛠️ What I work on

- 🗺️ **Geospatial applications:** interactive web maps with the ArcGIS Maps SDKs, publishing and managing data on ArcGIS Enterprise and ArcGIS Online, spatial data in PostGIS, and operational dashboards for teams that work in the field.
- 💻 **Web and mobile development:** Angular and React front ends, Flutter apps, and APIs in .NET, Node.js, and Python, including authentication and integrations between systems.
- 🧩 **Internal tools and business software:** extending open-source platforms to fit how a company actually works, such as time tracking, capacity planning, and reporting in Kimai, or self-hosted Odoo deployments.
- 📐 **Systems design and architecture:** designing solutions end to end, from components and integrations to environments, infrastructure as code, and how a system will be operated once it's live.
- 📝 **Technical proposals:** writing solution approaches, architecture and work plans for public tenders, R&D calls, and international RFPs.
- 🤖 **AI with spatial data:** MCP tools that let language models query GIS data, plus AI-assisted engineering practices for the team.
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

Most of my work is client software that isn't public, so here is what it does and what I did on it.

### 🔥 SGI: Fire Management System · [Sociedad de Productores Forestales](https://www.spf.com.uy)

The wildfire detection and response platform used by Uruguay's forestry companies. It records smoke and fire events reported by towers, cameras, aircraft and people, identifies the properties at risk and alerts their owners, dispatches ground and air resources by protocol, and measures every step of the response. It has been in operation since 2022 and is used throughout each fire season.

**My role:** lead developer and technical lead, across the system:
- Most of the web app: a React PWA for dispatchers and field crews, with ArcGIS maps, WhatsApp and email communications, and embedded Power BI reports.
- The .NET backend and its integration APIs: a fire-detection camera system, a messaging platform, and weather data.
- Geospatial ingestion and geoprocessing jobs: weather observations, rasters and satellite data, running in Azure Functions.
- Observability: Grafana Cloud with Alloy agents inside the Azure network, with dashboards and alerts for platform health and data flows.
- A design for an AI assistant that answers questions about live events and resources through MCP tools over ArcGIS Enterprise.

*React · TypeScript · Redux Toolkit · Mantine · ArcGIS Maps SDK · .NET · SQL Server · Azure · Grafana*

I also built the SPF's **phytosanitary surveillance dashboards**: embedded Power BI reports with access controlled through ArcGIS Online groups.

### 🐘 WCS Map Component · [Wildlife Conservation Society](https://www.wcs.org)

A React map library used in WCS's own platform to show its conservation sites, field operations and activity data around the world. ICA has developed and maintained it since 2022, releasing new features at the request of WCS's Conservation Technology team.

**My role:**
- Lead developer of the component, published as an npm package with a QA and demo site.
- Its documentation.
- Azure Functions and ArcGIS Pro tools that automate ArcGIS administration and data updates.

*React · TypeScript · ArcGIS Maps SDK · Mantine · Azure Functions · ArcGIS Pro*

### 🌾 EUDR compliance for agricultural traceability

The GIS side of a national traceability system that lets producers certify that exports meet the EU Deforestation Regulation (EUDR).

**My role:** led the GIS team:
- Designed the geospatial architecture: an enterprise geodatabase, three environments, and ArcGIS Enterprise.
- Built the .NET GIS API that validates cadastral parcels for other systems.
- Built the geoprocessing service that generates EUDR GeoJSON files with topology checks, published through Azure DevOps pipelines.

*ArcGIS Enterprise · ArcPy · .NET · SQL Server · MongoDB · Azure DevOps*

### Other client work

- Map-based platforms for fuel distribution and freight logistics, built with Angular, .NET and ArcGIS.
- Configurable cadastral and property-tax viewers deployed across several municipalities.
- Upgrading an enterprise ArcGIS platform from 10.9.1 to 11.3.
- Technical proposals and solution architecture for public tenders and international RFPs.

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
