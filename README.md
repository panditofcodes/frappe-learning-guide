## ✅ **Core / Must-Know (Beginner to Early Intermediate)**

These are the **essential skills** needed to build apps, understand the framework, and become productive in a Frappe environment.

### 🚀 Getting Started

* Frappe Framework Overview
* Bench, Site, and App structure
* Environment Setup (`bench init`, `new-site`, `new-app`, `install-app`)
* App folder and module structure

### 📄 Doctype & Data Modeling

* Creating Doctypes (UI + Code)
* Field types and options
* Naming series and autoname
* Child Tables and Link fields
* Role Permissions Manager (basic permission control)

### ✍️ Basic Customization

* Custom Fields
* Property Setters
* Print Formats (Jinja basics)
* Report Builder (standard reports)

### 💻 Basic Scripting

* Client Scripts (`frappe.ui.form.on`)
* Basic `frappe.call` to fetch server-side data
* Server Scripts (simple events like `validate`, `on_submit`)

### ⚙️ Core ORM & Backend

* `frappe.get_doc`, `frappe.get_all`, `frappe.db.get_value`, etc.
* Python controller methods (`validate`, `before_save`, `on_submit`)
* Using hooks: `doc_events`, `scheduler_events`

---

## 🔁 **Productive / Intermediate-Level**

Skills that increase productivity and allow for **custom logic, APIs, frontend, and automation**.

### 🧠 Intermediate Backend

* Fixtures: Exporting customizations
* Custom REST API endpoints (`@frappe.whitelist`)
* Using Frappe's built-in REST API
* Scheduler Events and Background Jobs (`enqueue`)
* Email Queue, Notifications, and Email Alerts

### 🖼️ Frontend & Web Tools

* Web Pages (Portal / Public pages)
* Web Templates with Jinja
* Web Forms (Data collection)
* Dynamic Print Formats (HTML/CSS)

### 📊 Reporting

* Query Reports (SQL-based)
* Script Reports (Python + JS)
* Filters and JS integration in reports

### 🔐 Intermediate Permissions

* Match Conditions and User Permissions
* Sharing and Document-Level Permissions

---

## 🧠 **Advanced / Optional (Nice-to-Know, Specialized Use)**

These are **optional, situational, or advanced** features helpful for scaling apps, integrations, and real-time interactions.

### ⚡ Advanced Tools

* Frappe Query Builder (`frappe.qb`)
* Writing Unit Tests (`frappe.test_runner`)
* Using `frappe.logger` for error logging

### 🌐 Integrations

* Webhooks (incoming/outgoing)
* Third-party API integrations
* Custom authentication (OAuth/JWT if needed)

### 🔄 Realtime and WebSocket

* Frappe’s Realtime Events (SocketIO)
* Notifications via WebSocket

### 📦 Packaging & Deployment

* App versioning and GitHub deployment
* Installing apps on other sites
* Using `patches.txt` and migrations

---

## 💡 Summary Table

| Category                   | Topics Covered                                                          |
| -------------------------- | ----------------------------------------------------------------------- |
| ✅ **Core / Must-Know**     | Setup, Doctypes, Permissions, Client/Server Scripts, ORM, Basic Reports |
| 🔁 **Intermediate**        | APIs, Fixtures, Background Jobs, Web Pages, Web Forms, Custom Reports   |
| 🧠 **Advanced / Optional** | Query Builder, Webhooks, Realtime, Unit Testing, App Packaging          |

---
