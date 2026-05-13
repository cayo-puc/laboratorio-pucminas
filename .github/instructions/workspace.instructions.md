---
description: Core workspace instructions for the Soc Ops Java project, including build, run, and test guidance.
---

# Workspace Instructions

## Mandatory development checklist

- [ ] Lint code with your Java/IDE tools or configured Maven checkers
- [ ] Build with `cd socops && ./mvnw clean package`
- [ ] Test with `cd socops && ./mvnw test`

## What this repo contains

- Spring Boot app in `socops/`
- Thymeleaf UI: `socops/src/main/resources/templates/game.html`
- CSS utilities in `socops/src/main/resources/static/css/app.css`
- Java code in `socops/src/main/java/com/socops/`

## Key commands

- `cd socops && ./mvnw clean package`
- `cd socops && ./mvnw spring-boot:run`
- `cd socops && ./mvnw test`
- `curl -I http://127.0.0.1:8080`

## Important files

- `socops/pom.xml`
- `socops/src/main/java/com/socops/SocOpsApplication.java`
- `socops/src/main/java/com/socops/web/BingoRestController.java`
- `socops/src/main/resources/templates/game.html`
- `socops/src/main/resources/static/css/app.css`

## Agent guidance

- Use `./mvnw` in `socops/` for build and run.
- Prefer editing Thymeleaf and CSS directly; there is no separate frontend framework.
- `.github/prompts/setup.prompt.md` defines setup bootstrap behavior.
