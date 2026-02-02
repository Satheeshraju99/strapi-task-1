# Strapi Task 1 – DevOps Pre-Internship

**Name:** Satheesh R
**Program:** DevOps Pre-Internship
**Company:** PearlThoughts

---

## Overview

This repository contains **Task 1** of the DevOps Pre-Internship program at **PearlThoughts**.
The objective of this task was to gain hands-on experience with **Strapi**, understand headless CMS concepts, and demonstrate the ability to set up, configure, and document a modern backend application.

---

## What is Strapi? (My Understanding)

Strapi is an **open-source headless Content Management System (CMS)** that enables developers to create, manage, and deliver content through APIs such as **REST** and **GraphQL**.

Unlike traditional CMS platforms, Strapi separates the **backend content management** from the **frontend presentation layer**. This allows backend teams to manage structured content efficiently, while frontend or mobile applications consume content via APIs. This architecture fits well with modern, cloud-native and DevOps-oriented applications.

---

## Key Features of Strapi

* Web-based Admin Panel for content management
* Custom content-type creation without backend coding
* Secure API-based content delivery
* Flexible and developer-friendly architecture
* Suitable for modern DevOps workflows

---

## Objective of Task 1

The main goal of this task was to understand Strapi through practical implementation by completing the following:

* Clone and explore the official Strapi repository
* Run Strapi locally
* Explore the project folder structure
* Access and configure the Admin Panel
* Create a sample content type
* Add and publish sample content
* Push the project to GitHub
* Document all steps in a README file
* Record a Loom video demonstration

---

## Technology Stack

| Component        | Version / Tool    |
| ---------------- | ----------------- |
| Runtime          | Node.js v18 (LTS) |
| CMS              | Strapi v5         |
| Database         | SQLite (default)  |
| Version Control  | Git and GitHub    |
| Operating System | Windows           |

---

## Strapi Repository Exploration

As part of the task, I cloned and explored the official Strapi repository to understand its internal structure.

### Key Directories Reviewed

* `packages/` – Core Strapi modules
* `examples/` – Reference applications
* `docs/` – Official documentation
* `scripts/` – Build and automation scripts

This exploration helped me understand how Strapi is modularized and structured internally.

---

## Local Strapi Setup

### Create the Strapi Application

```bash
npx create-strapi-app my-strapi-app --quickstart
```

This command:

* Created a new Strapi project
* Configured SQLite automatically
* Started the development server
* Opened the Admin Panel

### Run the Application

```bash
npm run develop
```

### Admin Panel URL

```
http://localhost:1337/admin
```

---

## Admin Panel Configuration

* Created an administrator account
* Logged into the Strapi Dashboard
* Accessed the Content-Type Builder and Content Manager

---

## Content Type Creation

Using the Content-Type Builder, a **Collection Type** named **Article** was created.

### Fields Defined

* `title` – Text (Required)
* `description` – Rich Text
* `publishedDate` – Date

The content type was saved successfully, and the server restarted automatically.

---

## Sample Content Entry

* Created one Article entry
* Added sample data
* Published the entry
* Verified the entry under the Published section

This confirmed that the content type and database configuration were working correctly.

---

## Project Structure Overview

Important directories and files in the project include:

* `config/` – Server, database, and plugin configuration
* `src/api/` – API logic for content types
* `src/api/article/` – Schema, routes, controllers, and services
* `public/` – Static assets
* `database/` – SQLite database and migrations

---

## How to Run the Project Locally

1. Clone the repository
2. Install dependencies:

   ```bash
   npm install
   ```
3. Start the development server:

   ```bash
   npm run develop
   ```
4. Access the Admin Panel at:

   ```
   http://localhost:1337/admin
   ```

---

## Loom Video Demonstration

The Loom video demonstrates:

* Running Strapi locally
* Accessing the Admin Panel
* Article content-type configuration
* Published sample content
* GitHub repository overview

Loom Video Link:
[https://www.loom.com/share/3b8eb5de1d11409db5a2ae3420d8cc9e](https://www.loom.com/share/3b8eb5de1d11409db5a2ae3420d8cc9e)

---

## GitHub Repository

Repository Link:
[https://github.com/Satheeshraju99/strapi-task-1](https://github.com/Satheeshraju99/strapi-task-1)

---

## Conclusion

Through Task 1, I gained practical exposure to Strapi setup, headless CMS concepts, local development, content-type creation, and GitHub workflow. This task helped me understand how Strapi fits into modern backend and DevOps workflows, especially for API-based applications.

Task 1 completed successfully.

branch: satheesh