# Crime Reporting & Analytics System

A cross-platform crime reporting and analytics system developed as my **4th-year university project** at Strathmore University.

The original project consisted of an Android mobile application for submitting and browsing crime reports, a backend API, and a web-based administration and analytics platform. The system was designed to demonstrate how location-based crime reports could be collected, managed, and analyzed through a centralized platform.

> **Status: Archived / Legacy Project**
>
> This repository contains the original university project and is no longer under active development. I am currently rebuilding the project as a separate, modernized version with the intention of eventually deploying it publicly.

## Overview

The system was designed around two primary interfaces:

* **Android Application** — Used by members of the public to register, submit crime reports, upload images, browse reports, and manage their profiles.
* **Web Application** — Used for administration and crime analysis, including reviewing submitted reports and examining crime trends and geographic data.

A shared backend and database connected the two applications.

## Features

### Mobile Application

* User registration and authentication
* User profiles
* Crime report submission
* Image uploads
* Browsing submitted reports
* Location-based crime reporting
* Session management

### Administration & Analytics

* Crime report management
* User management
* Crime-type statistics
* Crime trend analysis
* Geographic crime analysis
* Crime-density/heatmap data
* Location-based filtering and analysis

### Backend

* REST API
* Authentication and session management
* Database integration
* Password security
* Communication between the mobile and web applications

## Technology

| Component          | Technology                                      |
| ------------------ | ----------------------------------------------- |
| Mobile Application | Kotlin, Android Jetpack Compose                 |
| Backend            | Python, FastAPI                                 |
| Database           | SQLAlchemy                                      |
| API                | REST                                            |
| Web Application    | HTML, CSS, JavaScript                           |
| Development        | Git, GitHub, Visual Studio Code, Android Studio |

## System Structure

```text
                    ┌─────────────────────┐
                    │      Database       │
                    └──────────▲──────────┘
                               │
                         SQLAlchemy
                               │
                    ┌──────────┴──────────┐
                    │    FastAPI Backend  │
                    │      REST API       │
                    └───────┬───────┬─────┘
                            │       │
                  ┌─────────┘       └─────────┐
                  ▼                           ▼
        ┌─────────────────┐         ┌─────────────────┐
        │ Android Mobile  │         │ Web Application │
        │     App         │         │ Administration  │
        └─────────────────┘         │  & Analytics   │
                                    └─────────────────┘
```

## Project Background

This project was developed as part of my fourth year of the **Bachelor of Business Information Technology** program at Strathmore University.

It was an opportunity to apply concepts from software engineering, database development, mobile application development, web development, API design, authentication, and data analysis to a single integrated system.

The original system was developed independently from the ground up, including the mobile application, web application, backend, database integration, and analytics functionality.

## Repository Status

This repository represents the **original academic implementation** of the project.

It is preserved primarily for:

* historical reference
* documenting my university work
* demonstrating my development experience at the time
* comparing the original implementation with the future remake

**No further development is planned for this repository.**

### Future Development

A new version of this project is being developed separately with a focus on improving the original system's architecture, usability, design, and deployment.

**Remake:** *Coming soon*

**Live Demo:** *Coming soon*

The remake will be maintained in its own repository and will supersede this implementation.

## Disclaimer

This project was developed for academic purposes. The original implementation should not be considered a production-ready crime reporting platform.

The repository is retained as a record of the original project and as a demonstration of my development experience during university.
