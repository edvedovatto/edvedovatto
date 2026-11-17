<img src="banner.png" alt="Eduardo Vedovatto - Senior QA Engineer, test automation" width="100%">

I'm a Senior QA Engineer with 10+ years in QA across fintech, payments and automotive. I automate web and API tests wired into CI, and I use AI tools in day-to-day QA work, reviewing everything they produce.

## Recent work

- **Trustly** - built custom Claude Code skills for day-to-day QA, including Jira-based shift-left monitoring. After finding that about 84% of the documentation hadn't been updated in over two years, built a tool that suggests updates with each delivery.
- **GOW** - built test automation from scratch with Playwright (Page Object) and CI/CD on Azure DevOps across several projects, including a US fintech; APIs with Java + REST Assured or Postman, depending on the project; used Playwright MCP to map flows, reviewing all AI output.
- **Zallpy Digital** - cut test-data preparation time by about 70% by generating test data through the API, introduced a Definition of Done and systematic defect analysis, and also led the project's QA team of five.

Most of my work sits in client codebases I can't share, so I built two public projects to show how I test.

## Projects

### [Setslip](https://github.com/edvedovatto/setslip) - my own Android app, tested end to end

I built the app AI-driven with automation in mind: it was designed to be testable from day one.

- 52 Gherkin scenarios on Appium 3 + UiAutomator2, plus 34 unit tests
- Stable IDs exposed by the app, no XPath and no `Thread.sleep`
- Emulator (API 36) in GitHub Actions: smoke every night, full suite every week
- Failures come with a screenshot, view hierarchy, logcat and video

`Kotlin` `Jetpack Compose` `Java 17` `Appium` `Cucumber` `GitHub Actions`

### [qa-automation-portfolio](https://github.com/edvedovatto/qa-automation-portfolio) - one shop, tested through the UI and the API

OWASP Juice Shop, split on purpose: the UI covers what only the UI can show, business rules and contracts live in the API tests.

- 25 UI tests (Playwright + Gherkin) and 35 API tests (REST Assured)
- Every test creates its own user through the API; the main responses are checked against JSON schemas
- Juice Shop's built-in bugs are kept as 13 tests of the correct behavior, run in a separate CI pass that flags any that get fixed
- Accessibility scanned with axe against WCAG 2.1 AA

`TypeScript` `Playwright` `Java 17` `REST Assured` `axe` `Docker` `GitHub Actions`

## Stack

**Automation:** Playwright, Cypress, Selenium, Appium, Robot Framework, Cucumber, JMeter<br>
**API:** REST Assured, JUnit, Postman, Bruno<br>
**CI/CD:** GitHub Actions, Azure DevOps, Docker<br>
**AI in QA:** Claude Code (custom skills), GitHub Copilot, Playwright MCP<br>
**Languages:** TypeScript, JavaScript, Java, SQL

## Contact

Open to remote Senior QA Engineer, QA Automation and SDET roles, from Porto Alegre, Brazil (UTC-3), with US and European time-zone overlap. ISTQB CTFL, English C2.

[edvedovatto.github.io](https://edvedovatto.github.io) · [LinkedIn](https://www.linkedin.com/in/vedovatto) · [ed.vedovatto@gmail.com](mailto:ed.vedovatto@gmail.com)
