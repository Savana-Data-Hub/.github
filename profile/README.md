# Savana Data Hub 🌍📊

**A robust data management application tailored for efficient data entry, storage, retrieval, and visualization**

## 🏗️ Architecture

Savana Data Hub follows a modular architecture with separate repositories for different components:

### 📁 Repository Structure

| Repository | Description | Build Status |
|------------|-------------|---------|
| [`savana-data-hub`](https://github.com/Savana-Data-Hub/savana-data-hub) | Core backend API service providing REST endpoints, database models, and business logic for the Savana platform | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/savana-data-hub/build-and-push.yml?branch=main&style=flat) |
| [`login-app`](https://github.com/Savana-Data-Hub/login-app) | Authentication frontend application handling user login | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/login-app/build-and-push.yml?branch=main&style=flat) |
| [`usage-analytics`](https://github.com/Savana-Data-Hub/usage-analytics) | Platform analytics dashboard tracking user interactions, system metrics, and serving as the default landing page | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/usage-analytics/build-and-push.yml?branch=main&style=flat) |
| [`dashboard-app`](https://github.com/Savana-Data-Hub/dashboard-app) | Main administrative dashboard providing data visualization | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/dashboard-app/build-and-push.yml?branch=main&style=flat) |
| [`aggregate-data-entry-app`](https://github.com/Savana-Data-Hub/aggregate-data-entry-app) | Specialized application for bulk data entry and aggregation workflows with validation and processing features | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/aggregate-data-entry-app/build-and-push.yml?branch=main&style=flat) |
| [`capture-app`](https://github.com/Savana-Data-Hub/capture-app) | Real-time data capture interface supporting forms, file uploads, and direct data input from various sources | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/capture-app/build-and-push.yml?branch=main&style=flat) |
| [`maintenance-app-legacy`](https://github.com/Savana-Data-Hub/maintenance-app-legacy) | Legacy system maintenance tools and utilities for backward compatibility and system administration | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/maintenance-app-legacy/build-and-push.yml?branch=main&style=flat) |
| [`import-export-app`](https://github.com/Savana-Data-Hub/import-export-app) | Data migration and transformation service supporting CSV, JSON, XML import/export with mapping and validation | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/import-export-app/build-and-push.yml?branch=main&style=flat) |
| [`user-app`](https://github.com/Savana-Data-Hub/user-app) | User management interface for account administration, role assignment, and permission management | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/user-app/build-and-push.yml?branch=main&style=flat) |
| [`user-profile-app`](https://github.com/Savana-Data-Hub/user-profile-app) | Personal profile management application allowing users to update preferences, settings, and personal information | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/user-profile-app/build-and-push.yml?branch=main&style=flat) |
| [`settings-app`](https://github.com/Savana-Data-Hub/settings-app) | System configuration interface for platform-wide settings, feature toggles, and environment management | ![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/Savana-Data-Hub/settings-app/build-and-push.yml?branch=main&style=flat) |
