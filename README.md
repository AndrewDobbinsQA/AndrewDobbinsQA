# Hi, I'm Andrew Dobbins

**Senior Test Engineer | Test Automation & Software Quality | ISTQB Certified**

I'm a senior software test engineer based in Perth, Scotland, with over 10 years of commercial experience across web technologies, mobile applications and inflight entertainment systems.

My automation experience spans over five years of developing, maintaining and owning a commercial Selenium, Ruby and RSpec framework, followed by co-developing a modern Playwright and TypeScript replacement.

I specialise in reusable, configuration-driven test automation, cross-browser and cross-device testing, root-cause analysis and reliable behavioural assertions. My experience also includes automation code reviews, peer mentoring and risk-based quality assurance.

I'm currently developing an independent Playwright and TypeScript automation framework, demonstrating modern UI and REST API testing capabilities, reusable framework architecture and continuous integration.

I'm passionate about building reliable, maintainable and scalable test automation solutions that development teams can trust.

## Career Highlights

- **10+ years** of commercial software testing experience.
- **5.5+ years** of commercial Selenium, Ruby and RSpec automation development.
- **110+ merged automation pull requests**, progressing from contributor to framework owner and designer.
- Developed approximately **85% of a 42-specification end-to-end smoke suite**.
- **83 automation pull requests reviewed and approved**, contributing 126 review comments focused on reliability, maintainability and code quality.
- Designed reusable, configuration-driven automation across multiple customer environments.
- Developed cross-browser and real-device automation using BrowserStack, covering nine browser and device configurations per customer.
- Co-developed a modern Playwright and TypeScript automation framework using Docker.
- Developed sustained-playback tests with stall detection, network-error handling and diagnostic logging.
- Mentored colleagues in automation development and framework contribution.

## Technical Skills

### Test Automation

![Playwright](assets/badges/playwright.svg)
![Selenium WebDriver](https://img.shields.io/badge/Selenium%20WebDriver-43B02A?style=flat&logo=selenium&logoColor=white)
![RSpec](assets/badges/rspec.svg)

### Programming Languages

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![Ruby](https://img.shields.io/badge/Ruby-CC342D?style=flat&logo=ruby&logoColor=white)

### API Testing

![REST API](https://img.shields.io/badge/REST%20API-005571?style=flat)
![Swagger](https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat&logo=postman&logoColor=white)

### Cross-Browser & Cross-Device Testing

![BrowserStack](assets/badges/browserstack.svg)
![Chromium](assets/badges/chromium.svg)
![WebKit](assets/badges/webkit.svg)
![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=flat&logo=firefoxbrowser&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat&logo=android&logoColor=black)
![iOS](https://img.shields.io/badge/iOS-444444?style=flat&logo=apple&logoColor=white)

### Version Control, CI/CD & Infrastructure

![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)
![Bitbucket](https://img.shields.io/badge/Bitbucket-0052CC?style=flat&logo=bitbucket&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Docker Compose](https://img.shields.io/badge/Docker%20Compose-2496ED?style=flat&logo=docker&logoColor=white)

### Tools & Environments

![Jira](https://img.shields.io/badge/Jira-0052CC?style=flat&logo=jira&logoColor=white)
![TestRail](assets/badges/testrail.svg)
![VS Code](assets/badges/vscode.svg)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)
![SSH](assets/badges/ssh.svg)
![SQL](assets/badges/sql.svg)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat&logo=claude&logoColor=white)

## Featured Project

### [Playwright Automation Framework](https://github.com/AndrewDobbinsQA/playwright-automation)

[![Playwright Tests](https://github.com/AndrewDobbinsQA/playwright-automation/actions/workflows/playwright.yml/badge.svg?branch=main)](https://github.com/AndrewDobbinsQA/playwright-automation/actions/workflows/playwright.yml)

An independently developed UI and REST API test automation framework using Playwright and TypeScript, targeting the Practice Software Testing Toolshop application.

The project builds upon my commercial automation experience and demonstrates modern framework design, comprehensive test coverage, reproducible test environments and continuous integration.

**UI Test Automation:**

- Page Object Model architecture with reusable page interactions.
- Cross-browser testing across Chromium, Firefox and WebKit.
- Homepage and positive, negative and validation-based authentication testing.
- Product search and category filtering, including exact product collection validation.
- Parameterised test scenarios and reusable assertion helpers.

**REST API Test Automation:**

- Dedicated API test project supporting independent UI and API execution.
- Reusable API client architecture and strongly typed response models.
- Positive, negative and boundary testing across four product catalogue endpoints.
- Product retrieval, filtering, sorting, search and pagination validation.
- Runtime response structure and cross-endpoint data consistency validation.
- Dynamic test data identification and product relationship validation.
- Reusable HTTP response, pagination and product assertion helpers.

**Continuous Integration & Infrastructure:**

- Automated UI and API test execution using GitHub Actions.
- Reproducible Docker Compose-based test environment.
- Automated database migrations and seeding.
- Application readiness checks and diagnostic logging.
- Environment-based configuration and secure credential management.
- Strict TypeScript validation.
- Playwright HTML reporting and trace collection.

**Exploratory Testing & Defect Management:**

- Exploratory API testing using Swagger and direct HTTP requests.
- Investigation of application behaviour and API contract discrepancies.
- Structured defect reporting, severity classification and issue tracking.
- Conditional expected failure handling with direct defect traceability in automated test reports.
- Issue-driven development with defined acceptance criteria and pull request validation.

**Current Test Coverage:**

| Test Coverage | Scenarios | Configured Executions |
| --- | ---: | ---: |
| UI Automation | 10 | 30 |
| REST API Automation | 53 | 53 |
| **Total** | **63** | **83** |

The complete CI regression suite executes across three browser engines and a dedicated API test project, with 81 conventional passes, two documented expected failures and zero unexpected failures in the latest validated feature regression.

**Technical Milestones:**

- Designed and implemented a self-contained Docker-based test environment within GitHub Actions, removing dependency on a publicly hosted application and resolving Cloudflare-related authentication restrictions in CI.
- Established a reusable REST API testing architecture alongside the existing cross-browser UI framework, implementing 53 automated API scenarios across nine focused specification files.
- Introduced automated defect traceability, preserving visibility of known application defects without masking unexpected test failures.

**Planned Development:**

- Authentication and payment API test coverage.
- Combined UI and API test scenarios.
- Database validation using MariaDB.
- Shopping cart and end-to-end checkout coverage.
- Reusable fixtures and test data management.
- Accessibility and performance testing exploration.
- Continued framework refinement, reporting and failure diagnostics.

**Status:** In active development

## Engineering Focus

- Test automation framework architecture and design
- Page object models and reusable test components
- REST API automation and reusable API clients
- Configuration-driven, multi-environment testing
- Cross-browser and real-device automation
- Condition-based waits and reliable assertions
- Positive, negative and boundary testing
- API response validation and cross-endpoint data consistency
- Exploratory testing and defect traceability
- Flaky test investigation and root-cause analysis
- Media playback and resilience testing
- Automation code reviews and peer mentoring
- Risk-based testing and automation strategy
- Continuous integration and delivery
- AI-assisted testing and test design

## Certifications & Education

- **ISTQB Foundation Level Certification** (2016)
- **BSc (Hons), Environmental Management & Planning — 2:1**\
  Glasgow Caledonian University

## Outside of Work

Outside of software testing, I'm a keen cyclist, runner and hillwalker, with a particular interest in exploring Scotland's Munros.

I enjoy challenging myself, setting long-term goals and tracking my progress across these activities.

[![Strava](https://img.shields.io/badge/Strava-FC4C02?style=flat&logo=strava&logoColor=white)](https://www.strava.com/athletes/86488751)

## Connect with Me

Currently open to Senior Test Engineer, Test Automation Engineer and Software Development Engineer in Test (SDET) opportunities.

[![LinkedIn](assets/badges/linkedin.svg)](https://www.linkedin.com/in/andrewdobbinsqa/)
