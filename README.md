<div align="center">

<h1>🔄 Github Actions workflows templates 🔄</h1>

</div>

This repository contains a set of GitHub Actions workflow templates designed to streamline, centralize, and automate various CI pipelines. Below is a brief description of each workflow.

---
### Available Workflows templates

#### Lint

- Super-Linter validation for **HTML** and **CSS**
  ```
  .github/
  └── workflows/
      └── linter-static-front.yaml
  ```

- Super-Linter validation for **Javascript** and **Typescript**
  ```
  .github/
  └── workflows/
      └── linter-npm.yaml
  ```

#### Build and Push

- Build & Push for **Docker Hub** (including ```npm install```)
  ```
  .github/
  └── workflows/
      └── build-push-docker-hub.yaml
  ```

- Build & Push for **GHCR** (including ```npm install```)
  ```
  .github/
  └── workflows/
      └── build-push-ghcr.yaml
  ```
