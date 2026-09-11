<div align="center">
<h1>Treavor Johnson</h1>
Knoxville, TN | <a href="mailto:treavorcjohnson@gmail.com">treavorcjohnson@gmail.com</a> | +1 (423)333-9462 | <a href="https://linkedin.com/in/treavorjohnson">LinkedIn</a> | <a href="https://github.com/treavorj">GitHub</a>
</div>

## Summary

Engineering Specialist with **9+ years** of experience at [Denso Manufacturing](#denso-manufacturing-maryville-tn), specializing in industrial automation, distributed systems, and manufacturing process optimization. Proficient in programming languages (`Go`, `Python`, `JavaScript`) and industrial controllers (Omron, Allen Bradley, Fanuc). [Led capital projects](#autonomous-mobile-robot-amr-system) worth over **$3M**, implemented systems handling **2.8 PB** of data, and programmed [**400+ machines**](#denso-manufacturing-maryville-tn) for data collection across seven production lines. Experience managing technical systems, managing projects with local and abroad peers, and setting strategic direction for multiple campuses of manufacturing. [Honors Mechanical Engineering degree](#education) with minors in Materials Science, Reliability Engineering, and Engineering Entrepreneurship.

## Skills

- **Programming Languages:** Go, Python, JavaScript, HTML, CSS, MATLAB, SQL, Dart SASS
- **Web Frameworks & Tools:** HTMX, Templ, Kibana, D3.js, Grafana, Vega, React, Angular
- **Databases & Storage:** SQLite, Postgres, ElasticSearch, Surreal
- **DevOps & Infrastructure:** Network Management, Docker, Podman, Kubernetes, RAFT, Casbin, Gitlab CI/CD, OTEL, HA Proxy
- **Operating Systems:** Linux, Windows, Container Creation
- **Industrial Controllers:** Omron Sysmac, Omron CJ, Allen Bradley RSLogix, Allen Bradley MicroLogix, Fanuc PMC, Brother PMC, Okuma PMC
- **Vision Systems:** Custom computer vision, Keyence XGX/IV/IX, Cognex
- **CAD Software:** SolidWorks, AutoCAD, Inventor, Fusion360, OnShape
- **Office Software:** MS Outlook, MS Teams, MS Excel, MS Powerpoint, MS Project, MS Access, MS OneNote, Obsidian
- **Digital Twin Software:** Visual Components, Simul8
- **Middleware Software:** Ignition, Devicewise

## Professional Experience

### Denso Manufacturing Maryville, TN

**Principal Engineer (E4)** | May 2017 – Present

- Create strategy for North American Autonomous Manufacturing
- Program and set up SCADA systems for over **400+ machines** across seven lines
- Optimize Allen Bradley, Omron Sysmac, and Omron CJ PLC programming for cycle time and readability
- Lead multiple projects from initial design review through implementation worth over **$2M**
- Host cross-functional teams to analyze and implement process improvements
- Analyze datasets over **100K+ data points** to ensure process reliability
- Write specifications for new machines and lines up to **$25M**
- Create over **50 CNC programs** for aluminum machining and steel turning
- Realized over **60%** cycle time savings by rewriting Mitutoyo CMM Programs
- Manage network systems for industrial infrastructure and global connectivity
- Create agentic tools for automation and intelligent decision-making within Denso operations
- Manage **2.8 PB** total storage for image retention across 13 manufacturing lines
- Create and improve process documentation for various products/processes including pressing, machining, assembly, welding, vision, and more
- Develop and manage quality system for tracking all part and attribute masters across the facility
- Design and implement new racks for hosting software/applications
- Manage network traffic across complex mostly isolated networks for **15** production lines

#### Key Technical Projects:

##### Distributed Data Collection Platform

- Architected and developed `go` distributed system with `RAFT` based consensus for data collection and interaction
- Enabled store and forward from multiple kubernetes clusters to central kubernetes cluster with `CEPH` backed storage
- Created custom authentication and authorization that integrates with multiple providers including OAuth 2.0 and custom providers
- Internal `MQTT` broker for easy data storage from PLCs and other MQTT compliant devices
- Designed custom `MQTT` function blocks for Omron Sysmac PLCs for MQTTv5
- Integrated FTP Server for ingestion of images and large files
- Automatic parsing of csv files to store into `SQL` DB
- gRPC and Rest endpoints for internal and external communication with OpenAPI documentation
- Custom web interface for adjusting settings, viewing realtime data, adding context to data using `html`, `css`, and `javascript` served using `Templ` and `HTMX`
- Created workflow plugin for software that allowed manual or automatic runtime configurable flows to alter data, call external systems, or send notifications

##### Casting Data Collection Platform

- Architected and developed a production system running for over **1 year** with **zero downtime** collecting data from casting and cutting equipment in `go`
- Custom file parsers and dynamic workflow engine for external API calls
- Visual manual inspection interface with real-time data monitoring
- API layer for part traceability logging from multiple machines
- All data stored in `ElasticSearch` with automated shift report generation
- Automated log capture within `ElasticSearch` for troubleshooting and diagnostics
- Custom authentication implementation supporting username/password and access badge integration

##### Autonomous Mobile Robot (AMR) System

_Software:_

- Created a containerized control system using `Python`, `JavaScript`, `HTML`, `CSS`, `HTMX`, and PLC logic for scheduling AMR jobs and changing machine state
- Achieved **99.99% uptime** before project completion
- Created distributed software connection across multiple different isolated networks with gateway devices
- Developed custom function blocks for interacting with `HTTP` and `MQTT` endpoints between the AMR and PLC
- Integrated `Python` with Omron CJ PLCs over FINS for memory reading and writing

_Project Management:_

- Coordinated team of 6 engineers through inception, procurement, and completion of **$3M** project
- Managed integration of **20** AMRs into three production lines
- Hosted weekly project update meetings with all stakeholders including senior management and production line leadership
- Successfully realized **15** headcount reduction

##### End Frame Line Installation

- Successfully started up **$1M** End Frame Machining Line from conception to full production capable of **180,000** frames per month
- Implemented all project phases including: Process Design Plan, Feasibility Study, Specification Writing, Quoting, Design Reviews, Procurement, and Final Release
- Created all process and quality documentation including MSA and capability studies, PFMEA, and Control Plans
- Wrote all CMM and CNC programs to enable high productivity and quality with a **70%** reduction in cycle time from the previous line
- Trained production on new machining line

### The University of Tennessee, Knoxville – Knoxville, TN

**Undergraduate Researcher – MABE** | January 2017 – May 2017

- Build implicit 2D transient multi-boundary heat transfer solver in MATLAB
- Collaborate with peers to design and validate heat transfer equipment
- Read and analyze numerous academic papers

### JTEKT Automotive – Vonore, TN

**Manufacturing Engineering Intern** | May 2016 – January 2017

- Improve manufacturing processes to improve system reliability and cycle time
- Increased tool life for all whirling operations by **30%**
- Designed new fixturing for grinding processes with automatic miss-load detection
- Test machine capability to advise on new product lines and machine maintenance
- Perform ROI calculations on new automation

### Waupaca Foundry Inc. – Etowah, TN

**Intern/Co-op** | Summers & Winters May 2013 – January 2015, May 2015 – January 2016

- Manage projects and teams of workers of over ten employees
- Design and improve parts for various types of machinery
- Produce over **1,000** of 2-D and 3-D models for new and existing equipment
- Create and organize a file system to hold millions of files
- Designed and implemented new mold walking equipment capable of withstanding **24,000lbs** of force weighing under **50lbs** per sled

## Education

### The University of Tennessee, Knoxville

#### Honors Bachelor of Science in Mechanical Engineering | May 2017

**Minors:**

- Materials Science and Engineering
- Reliability and Maintainability Engineering
- Engineering Entrepreneurship
