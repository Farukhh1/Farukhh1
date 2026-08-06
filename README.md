# Hi, I'm [Farrukh] 👋

BS Computer Science student at UET Lahore, building practical, real-world software — from reverse-engineering legacy business systems to shipping their modern replacements.

I like taking messy, real problems (an old system nobody understands, a process still running on spreadsheets) and turning them into something clean that actually gets used.

---

## 🔨 What I've built

### 🏭 SteelERP — Legacy ERP Replacement
A full rebuild of a 20-year-old Visual FoxPro + SQL Server ERP system used by a steel trading company — replacing it with a modern, maintainable web app while preserving the accounting logic (3-tier Chart of Accounts codes) the business actually relies on.

- Reverse-engineered the legacy system: extracted SQL Server connection details from a compiled FoxPro binary, got the original 20-year-old app running locally to understand its data model before touching anything
- Rebuilt from scratch: **FastAPI + HTMX + Jinja2 + Tailwind CSS + PostgreSQL**, with SQLAlchemy + Alembic replacing two decades of undocumented, ad-hoc schema changes with tracked migrations
- Shipped features: authentication, license-expiry enforcement, Customers CRUD, a hierarchical Chart of Accounts module, PDF report generation
- **Deployed and actively used** by the client — packaged as a standalone executable (PyInstaller + PyArmor) for non-technical daily use
- Followed up with a second module (Store/Stock management) after the client saw the first one working and asked for more

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `HTMX` `Tailwind CSS`

---

### 🛡️ ExamGuard — Network-Level Exam Lockdown Tool
A Flask-based tool that blocks LLM access at the network level during exams, via a DNS proxy and HTTPS interception, with a live dashboard.

`Python` `Flask` `Networking` `DNS`

**[→ View on GitHub](https://github.com/Farukhh1/ExamGuard)**

---

### 🧾 HyperStar Management System
A point-of-sale desktop application for retail management.

`C#` `WinForms` `MySQL`

**[→ View on GitHub](https://github.com/Farukhh1/HyperStarFinal)**

---

## 🧰 Skills

**Languages:** Python, C#, C++, SQL<br>
**Backend/Web:** FastAPI, Flask, SQLAlchemy, HTMX<br>
**Desktop:** WinForms<br>
**Databases:** PostgreSQL, SQL Server, MySQL<br>
**Other:** OOP, Data Structures & Algorithms, Machine Learning fundamentals (DeepLearning.AI ML Specialization)

---

## 📫 Reach me

- LinkedIn: [https://www.linkedin.com/in/syed-farrukh-11844637a/]
- Email: [Farrukhabbas505@gmail.com]

---

<sub>Currently exploring: AI/ML applications alongside backend development.</sub>
