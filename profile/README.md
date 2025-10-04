# FixPoint - Smart Mobile Ticketing Platform

Welcome to the **FixPoint GitHub Organization**  a modern, scalable, and secure platform built for **Domino’s Sri Lanka Maintenance Operations**.  
This organization hosts all the source code, infrastructure, and documentation for our **Smart Mobile Ticketing Platform**.

---

## 📱 About FixPoint

FixPoint is a **cloud-powered mobile solution** that streamlines ticketing and maintenance workflows for Domino’s Sri Lanka.  
Our platform ensures faster response times, real-time updates, and secure data handling.

### ✨ Core Features
- Mobile-first experience for service teams (Flutter app)
- Smart ticket assignment & tracking
- Real-time notifications & status updates
- Secure backend with **role-based authentication**
- Scalable **AWS cloud infrastructure**
- Visual dashboards and reporting

---

## 🛠 Tech Stack

| Layer            | Technology                       |
|------------------|----------------------------------|
| **Backend**      | Node.js + Express.js (MVC)       |
| **Frontend**     | Flutter (Android & iOS)          |
| **Database**     | PostgreSQL (AWS RDS)             |
| **Cloud**        | AWS EC2, S3, IAM                 |
| **Tools**        | Docker, GitHub Actions, Postman  |
| **Design**       | Figma, PlantUML, Draw.io         |
| **Management**   | Jira (Agile, sprint tracking)    |

---

## 📂 Repository Structure

| Repository         | Description |
|--------------------|-------------|
| **fixpoint-backend** | Node.js + Express.js API (ticketing logic, auth, integrations) |
| **fixpoint-mobile**  | Flutter mobile app (Android & iOS) |
| **fixpoint-infra**   | Docker configs, AWS deployment, CI/CD pipelines |
| **fixpoint-design**  | UX/UI designs, diagrams, and prototypes |
| **fixpoint-docs**    | Technical documentation, API specs, sprint notes |

---

## 🚀 Development Workflow

We follow **GitHub Flow** + Agile methodology.

### Branching Strategy
- `main` — production-ready code  
- `develop` — pre-release / staging  
- `feature/<name>` — new features  
- `bugfix/<name>` — bug fixes  
- `hotfix/<name>` — urgent production patches

### Commit Convention
We use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) to keep commit history clean:
- feat: add ticket validation API
- fix: resolve AWS RDS connection issue
- docs: update architecture diagram

---

## 📖 Contribution Guidelines

We welcome contributions! Please follow these steps:
1. Fork the repository you want to work on.
2. Create a branch: `git checkout -b feature/your-feature`.
3. Commit changes: `git commit -m "feat: add your feature"`.
4. Push and create a Pull Request.
5. Wait for code review & approval.

---

> ⚡ FixPoint is built with ❤️ for fast, reliable, and secure mobile ticketing operations.
