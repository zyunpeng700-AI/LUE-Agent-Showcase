# LUE-Agent

**A research workspace for urban land use efficiency analysis.**

[中文介绍](README.md) · [Architecture](docs/architecture.md) · [Validation scope](docs/validation.md)

LUE-Agent connects research questions, data availability checks, user-confirmed analysis, maps and reports in one workspace.

## Project status

Local validation and deployment preparation, as of October 14, 2026. There is no public hosted demo. Source code is not released. This repository contains project presentation materials, not an installable application.

## Implemented capabilities

- Research conversations and knowledge-assisted explanations.
- Registered data discovery and confirmation before formal analysis.
- Registered, uploaded and user-confirmed OSM boundaries.
- Maps, reports, data views and report export.
- Private user workspaces, personal memory controls and research history.
- User and shared data catalog administration.

Availability depends on registered resources and validated workflows. Representative live model and GIS cases have been tested; this does not establish universal scientific validity, production capacity or full GPU readiness.

## Technology overview

[Interface screenshots](docs/screenshots.md) show the actual React UI with synthetic accounts and fixture data. They are not live scientific results or evidence of a publicly hosted service.

React and TypeScript frontend, FastAPI application API, background task execution, PostgreSQL, and separate scientific resources and user artifacts.

Detailed prompts, internal decision rules, source code, model weights and datasets are excluded. No open-source license is granted for unreleased software.
