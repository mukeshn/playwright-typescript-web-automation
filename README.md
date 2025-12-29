# Playwright TypeScript Web Automation Framework

## Overview
This project is a scalable **Playwright + TypeScript automation framework**
designed for modern web applications.  
It supports end-to-end UI testing, API validation, CI execution, and
maintainable test architecture.

## Tech Stack
- Playwright
- TypeScript
- Node.js
- GitHub Actions
- REST API Testing
- SQL (data validation)

## Features
- Page Object Model (POM)
- Cross-browser testing (Chromium, Firefox, WebKit)
- Parallel execution
- CI integration using GitHub Actions
- API + UI hybrid testing
- Reusable utilities and fixtures

## Project Structure
- `tests/` – UI and API test cases
- `pages/` – Page Object classes
- `utils/` – Helpers and test data
- `fixtures/` – Test setup and teardown
- `.github/workflows` – CI pipeline

## How to Run
```bash
npm install
npx playwright test
