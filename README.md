# 🛠️ FB Service - Web App

Welcome to the official repository of **FB Service**, the digital platform dedicated to appliance assistance and repair services in the Agno Valley (VI).

🔗 **Live Site:** [https://fbserviceassistenza.web.app/](https://fbserviceassistenza.web.app/)

## 📝 Project Description
This Web App was designed to provide a professional online presence for FB Service. The site facilitates interaction between customers and technicians, clearly highlighting the services offered and ensuring maximum transparency through integrated legal documentation.

## ✨ Main Features

* **🖥️ Assistance Hub**: Catalog of supported appliance types (washing machines, dishwashers, ovens, etc.).
* **📞 Contact Center**: Direct contact system with Google Maps integration to view the operational area in the Agno Valley.

* **⚖️ Legal Compliance**: Dedicated **Privacy Policy**, **Cookie Policy**, and **Terms of Service** pages in full compliance with the GDPR.
* **📱 Responsive Design**: Interface optimized for smooth navigation on both desktop and mobile devices.

## 🛠️ Technology Stack

* **Hosting**: [Firebase Hosting](https://firebase.google.com/docs/hosting) (Google infrastructure for maximum speed and reliability).
* **Frontend**: HTML5, modern CSS3, and JavaScript.
* **CI/CD**: GitHub Actions (Automatic deployment with every code update).
* **Version Management**: Git & GitHub for source code control.

## 🚀 Development Workflow (Automatic Deployment)

The project uses a **Continuous Deployment** pipeline. Manual deployment via CLI is not necessary:

1. Make changes to the files locally.
2. Push the `main` branch:
```bash
git add .
git commit -m "Description of change"
git push origin main
```
3. **GitHub Actions** will detect the change and automatically update the live site.

## 📁 Project Structure
```text
├── .github/workflows/ # Automatic Deployment Configurations
├── public/ # Site source files (HTML, CSS, JS)
├── firebase.json # Firebase Hosting Configuration
├── package.json # Dependency Management and Build Scripts
└── README.md # Project Documentation
