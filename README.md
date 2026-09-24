<div align="center">

<!-- ═══════════════════════════════════════════════════════════ -->

<!--                    SYSTEM INITIALIZATION                    -->

<!-- ═══════════════════════════════════════════════════════════ -->

<img src="https://capsule-render.vercel.app/api?type=waving&height=230&color=0:05080D,50:0D1117,100:111827&text=DIEGO%20SANTOS&fontSize=58&fontColor=00E5FF&fontAlignY=38&desc=COMPUTER%20SCIENCE%20STUDENT%20%7C%20FULL%20STACK%20DEVELOPER&descAlignY=61&descSize=16&animation=twinkling" width="100%"/>

<br>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=2800&pause=900&color=00E5FF&center=true&vCenter=true&width=850&lines=INITIALIZING+DEVELOPER+PROFILE...;SYSTEM+ONLINE+%E2%9C%93;PYTHON+%7C+FASTAPI+%7C+REACT+%7C+POSTGRESQL;BUILDING+REAL+WORLD+FULL+STACK+PROJECTS...;WELCOME+TO+MY+GITHUB+%F0%9F%91%8B" alt="Typing Animation"/>

<br>

<img src="https://img.shields.io/badge/SYSTEM-ONLINE-00E5FF?style=for-the-badge&logo=github&logoColor=black"/>
<img src="https://img.shields.io/badge/FOCUS-FULL%20STACK-58A6FF?style=for-the-badge"/>
<img src="https://img.shields.io/badge/STATUS-BUILDING-8B5CF6?style=for-the-badge"/>

</div>

> whoami

╔══════════════════════════════════════════════════════════════╗
║                    DEVELOPER PROFILE                         ║
╠══════════════════════════════════════════════════════════════╣
║                                                              ║
║  Name       : Diego Santos                                   ║
║  Role       : Computer Science Student | Full Stack          ║
║               Developer                                       ║
║  Education  : Computer Science                                ║
║  Focus      : Backend • Frontend • APIs • Databases           ║
║  Status     : Building & Learning                             ║
║                                                              ║
╚══════════════════════════════════════════════════════════════╝

🧠 About Me

Hello! I'm Diego Santos, a Computer Science student and developer focused on building practical, real-world applications.

My current stack includes Python, FastAPI, React, JavaScript, HTML, CSS, PostgreSQL, SQLAlchemy, JWT, Docker, and Pytest.

I enjoy understanding how applications work end to end — from API design and business logic to databases, authentication, testing, and web interfaces.

I learn by building complete projects, improving their architecture, documenting the implementation, and turning what I study into working software.

CODE → LEARN → BUILD → IMPROVE → REPEAT

⚡ Tech Stack

<div align="center">

🐍 Backend

<img src="https://skillicons.dev/icons?i=python,fastapi" />

<br><br>

🌐 Frontend

<img src="https://skillicons.dev/icons?i=html,css,javascript,react" />

<br><br>

🗄️ Database

<img src="https://skillicons.dev/icons?i=postgresql" />

<br><br>

🔧 Development Tools

<img src="https://skillicons.dev/icons?i=git,github,vscode,docker" />

</div>

🛠️ Tools & Environment

<div align="center">

<img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white"/>
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
<img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white"/>
<img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
<img src="https://img.shields.io/badge/Swagger-85EA2D?style=for-the-badge&logo=swagger&logoColor=black"/>
<img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"/>

</div>

## 🚀 Featured Projects

## 🎫 HelpDesk Manager
Full-stack help desk management system built with FastAPI, React, PostgreSQL, Docker, JWT, Alembic and Pytest.

[View Repository](https://github.com/diegosantos-io/helpdesk-manager)

## 👥 Client Management System
Full-stack client management application built with React, FastAPI, PostgreSQL, JWT, Docker and Pytest.

[View Repository](https://github.com/diegosantos-io/sistema-gerenciamento-clientes)

🎫 HelpDesk Manager

Full-stack help desk management system built with FastAPI, React, PostgreSQL, Docker, JWT, Alembic, and Pytest.

The application manages technical support operations through role-based access for users, technicians, and administrators.

🧰 Stack

Frontend
React
JavaScript
HTML
CSS

Backend
Python
FastAPI
SQLAlchemy
Pydantic

Database
PostgreSQL
Alembic

Security
JWT
bcrypt

Infrastructure
Docker
Docker Compose

Testing
Pytest

⚙️ Key Features

[✓] JWT authentication
[✓] Role-based access control
[✓] User management
[✓] Account activation and deactivation
[✓] Ticket creation and tracking
[✓] Technician assignment
[✓] Technician ticket handling
[✓] Ticket resolution
[✓] Ticket history
[✓] Administrative ticket transfer
[✓] Transfer reason tracking
[✓] Search and filtering
[✓] Public ticket statistics
[✓] PostgreSQL persistence
[✓] Alembic migrations
[✓] Docker support
[✓] 29 automated tests

📡 Main API Routes

POST   /usuarios/
POST   /usuarios/login
GET    /usuarios/me
GET    /usuarios/
POST   /usuarios/admin
PUT    /usuarios/{usuario_id}
DELETE /usuarios/{usuario_id}

POST   /chamados/
GET    /chamados/
GET    /chamados/tecnico
GET    /chamados/publico
GET    /chamados/{chamado_id}
POST   /chamados/{chamado_id}/assumir
POST   /chamados/{chamado_id}/resolver
GET    /chamados/{chamado_id}/historico
POST   /chamados/{chamado_id}/transferir

🧪 Testing

The project currently has 29 automated tests passing, covering authentication, users, permissions, tickets, administrative operations, and ticket workflows.

============================= test session =============================

29 passed

============================= STATUS: PASS =============================

🏗️ Architecture

                     ┌──────────────────┐
                     │      REACT       │
                     │    Frontend      │
                     └────────┬─────────┘
                              │
                           HTTP / JSON
                              │
                              ▼
                     ┌──────────────────┐
                     │     FASTAPI      │
                     │     Backend      │
                     └────────┬─────────┘
                              │
                   ┌──────────┴──────────┐
                   │                     │
                   ▼                     ▼
            ┌─────────────┐       ┌─────────────┐
            │     JWT     │       │   Services  │
            │    Auth     │       │  Business   │
            └─────────────┘       │    Logic    │
                                  └──────┬──────┘
                                         │
                                         ▼
                                  ┌─────────────┐
                                  │ SQLAlchemy  │
                                  └──────┬──────┘
                                         │
                                         ▼
                                  ┌─────────────┐
                                  │ PostgreSQL  │
                                  └─────────────┘

<div align="center">

<a href="https://github.com/diegosantos-io/helpdesk-manager">
<img src="https://img.shields.io/badge/VIEW%20PROJECT-58A6FF?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

👥 Client Management System

Full-stack client management application built with React, Python, FastAPI, and PostgreSQL.

The project evolved from a basic client CRUD API into a complete application with authentication, validation, testing, Docker, and database migrations.

🧰 Stack

Frontend
React
JavaScript
HTML
CSS

Backend
Python
FastAPI
SQLAlchemy
Pydantic

Database
PostgreSQL
Alembic

Security
JWT
bcrypt

Infrastructure
Docker
Docker Compose

Testing
Pytest

⚙️ Key Features

[✓] User registration
[✓] JWT authentication
[✓] Protected routes
[✓] Password hashing with bcrypt
[✓] Client creation
[✓] Client listing
[✓] Client lookup by ID
[✓] Client updates
[✓] Client deletion
[✓] Search by name, email, and phone
[✓] Pagination
[✓] Data validation
[✓] Centralized error handling
[✓] Duplicate email prevention
[✓] Session persistence
[✓] Responsive interface
[✓] Swagger documentation
[✓] Alembic migrations
[✓] Docker
[✓] Automated tests

📡 API

POST    /usuarios/
POST    /usuarios/login

GET     /clientes/
POST    /clientes/
GET     /clientes/{id}
PUT     /clientes/{id}
DELETE  /clientes/{id}

GET     /health

<div align="center">

<a href="https://github.com/diegosantos-io/sistema-gerenciamento-clientes">
<img src="https://img.shields.io/badge/VIEW%20PROJECT-58A6FF?style=for-the-badge&logo=github&logoColor=white"/>
</a>

</div>

🎯 Current Mission

┌──[ DIEGO@GITHUB ]─[ ~/development ]──────────────────────────┐
│                                                              │
│  $ systemctl status developer                                │
│                                                              │
│  ● developer.service - ACTIVE                                │
│                                                              │
│  [✓] Learn Python                                            │
│  [✓] Build REST APIs                                         │
│  [✓] Work with PostgreSQL                                    │
│  [✓] Build Full Stack Projects                               │
│  [✓] Implement Authentication                                │
│  [✓] Work with Docker                                        │
│  [✓] Write Automated Tests                                   │
│  [ ] Deploy Production Applications                          │
│  [ ] Improve Advanced React                                  │
│  [ ] Build More Production-Ready Systems                     │
│                                                              │
│  STATUS: CONSTANTLY EVOLVING                                 │
│                                                              │
└──────────────────────────────────────────────────────────────┘

📊 GitHub Analytics

<div align="center">

<img height="180em" src="https://github-readme-stats.vercel.app/api?username=diegosantos-io&show_icons=true&include_all_commits=true&count_private=true&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=8957E5&text_color=C9D1D9"/>

<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=diegosantos-io&layout=compact&langs_count=8&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9"/>

</div>

<br>

<div align="center">

<img src="https://streak-stats.demolab.com?user=diegosantos-io&theme=github-dark-blue&hide_border=true&background=0D1117&stroke=21262D&ring=58A6FF&fire=FF7B72&currStreakLabel=58A6FF" width="70%"/>

</div>

📈 Activity Graph

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=diegosantos-io&bg_color=0D1117&color=58A6FF&line=8957E5&point=FFFFFF&area=true&hide_border=true" width="100%"/>

</div>

🏆 GitHub Trophies

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=diegosantos-io&theme=onestar&no-frame=true&no-bg=true&margin-w=8&row=1"/>

</div>

🐍 Contribution Protocol

<div align="center">

<img src="https://raw.githubusercontent.com/diegosantos-io/diegosantos-io/main/dist/github-contribution-grid-snake-dark.svg" alt="Snake animation"/>

</div>

🌐 Connect With Me

<div align="center">

<a href="https://github.com/diegosantos-io">
<img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white"/>
</a>

<a href="https://www.linkedin.com/in/diego-santos-3352a92a8/">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/>
</a>

</div>

<div align="center">

> SYSTEM MESSAGE

┌─────────────────────────────────────────────────────┐
│                                                     │
│   Thanks for accessing my developer profile.       │
│                                                     │
│   Every project is another step forward.           │
│   Every bug is another lesson.                     │
│   Every line of code is part of the journey.       │
│                                                     │
│   SYSTEM STATUS: ONLINE ✓                          │
│                                                     │
└─────────────────────────────────────────────────────┘

<br>

<img src="https://capsule-render.vercel.app/api?type=waving&height=120&color=0:21262D,50:161B22,100:0D1117&section=footer"/>

© 2026 Diego Santos • Built with code & curiosity

</div>
