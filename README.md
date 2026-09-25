# Sreetha Aneesh | Portfolio

**Live site: [sreethaaneesh.com](https://sreethaaneesh.com)**

Personal portfolio of Sreetha Aneesh, a Senior Full Stack Developer with 5+ years of experience building Java, Spring Boot and React applications in financial services and healthcare.

- Website: https://sreethaaneesh.com
- LinkedIn: https://www.linkedin.com/in/sreetha-aneesh-47a96130/
- Email: sreeanee2021@gmail.com
- Location: Cupertino, CA

## About

Senior Full Stack Developer with 5+ years of experience in full-stack application development, backend engineering and enterprise software delivery across financial services, technology and healthcare. Skilled in Java, Spring Boot, React.js, Angular, TypeScript, REST APIs, microservices, SQL and cloud technologies. Also experienced in LLM model testing, response evaluation and training-data development.

## Experience

| Role | Company | Period |
| --- | --- | --- |
| Senior Full Stack Developer | PNC | Sep 2023 - Present |
| Full Stack Developer | Cigna | Jul 2022 - Aug 2023 |
| Full Stack Developer | CitiusTech | Jan 2020 - May 2021 |

## Skills

| Area | Technologies |
| --- | --- |
| Languages | Java, JavaScript, TypeScript, SQL |
| Frontend | React.js, Angular, Redux, HTML5, CSS3, Responsive Design, SPA, State Management |
| Backend and APIs | Spring Boot, Spring MVC, Node.js, REST APIs, SOAP, Microservices, API Gateway, Service Integration |
| Databases | PostgreSQL, MySQL, Oracle, MongoDB, Redis, Data Modeling, Query Optimization, Indexing, Stored Procedures |
| Cloud and DevOps | AWS, Azure, Docker, Kubernetes, Jenkins, GitHub Actions, CI/CD, Linux |
| Messaging | Apache Kafka, RabbitMQ, Event Streaming, Message Queues, Event-Driven Architecture |
| Testing and Quality | JUnit, Mockito, Jest, Cypress, Selenium, API Testing, Test Automation |
| Security | Spring Security, OAuth 2.0, JWT, RBAC, OWASP, Secure Coding |
| Observability | Prometheus, Grafana, ELK Stack, Distributed Tracing, Logging, Root Cause Analysis, Performance Optimization |
| Architecture | System Design, Distributed Systems, Design Patterns, Scalability, High Availability, Solution Design |
| Leadership and Delivery | Technical Leadership, Code Reviews, Mentoring, Architecture Reviews, Technical Documentation, Agile, Scrum, SDLC |
| AI / LLM | LLM Model Testing, LLM Evaluation, Response Analysis, Training Data Development |

## Featured work

- **LLM Model Testing and Evaluation**: reviewed generated responses against evaluation criteria across 100+ test prompts and prepared 500+ training examples.
- **Full Stack Application Development**: Java, Spring Boot, React.js, TypeScript and REST APIs across 10+ application workflows, backed by PostgreSQL and MySQL.
- [mern-ecommerce-rishi](https://github.com/sreeanee/mern-ecommerce-rishi): e-commerce app (JavaScript, HTML).
- [spark-kafka-cassandra-pipeline](https://github.com/sreeanee/spark-kafka-cassandra-pipeline): streaming data pipeline (Python, Docker).
- [mern-chat-app](https://github.com/sreeanee/mern-chat-app): chat app on the MERN stack.
- [Regression-model-for-demand-prediction](https://github.com/sreeanee/Regression-model-for-demand-prediction): demand prediction with regression (Python).
- [contribution-history](https://github.com/sreeanee/contribution-history): generated GitHub contribution history.

## Education

Bachelor of Engineering, University of Calicut (2006 - 2010)

## About this site

A static site with no build step: plain HTML, CSS and JavaScript, hosted on GitHub Pages at the custom domain in `CNAME`. Page content is loaded from JSON files, so text changes do not need code changes.

- Dark navy theme with purple, coral, teal and yellow accents
- Fonts: Bricolage Grotesque and Figtree (Google Fonts), icons from Font Awesome
- Responsive layout with keyboard focus styles and reduced-motion support
- Contact form sends to email through [FormSubmit](https://formsubmit.co)

### Project structure

```
index.html             page shell
assets/css/styles.css  design tokens and styles
assets/js/main.js      loads the JSON files and renders each section
assets/img/            headshot, project images, company logos
data/*.json            all page content
CNAME                  custom domain (sreethaaneesh.com)
```

### Editing content

| To change | Edit |
| --- | --- |
| Name, title, headline, highlights | `data/hero.json` |
| About text and stats | `data/about.json` |
| Jobs | `data/experience.json` |
| Skills | `data/skills.json` |
| Projects | `data/projects.json` |
| Education | `data/education.json` |
| Contact details and form | `data/contact.json` |
| Page title and meta tags | `data/site-config.json` and `index.html` |
| Headshot | replace `assets/img/headshot.jpg` (portrait, about 800x1000) |

### Run locally

The JSON files load with `fetch`, so open the site through a local server rather than the file itself:

```bash
python -m http.server 8000
```

Then visit http://localhost:8000.

### Deploy

Push to `main`. GitHub Pages rebuilds the site within a minute or two.
