# Vehicle Inventory API — Technical Documentation Portfolio

A sanitized, portfolio-ready documentation project based on a vehicle inventory API and a separate search service.

> **Portfolio disclaimer:** This repository is an anonymized reconstruction for demonstration purposes. It does not publish proprietary company names, internal URLs, source-system names, credentials, or confidential business information.

## What this demonstrates

- Developer-oriented information architecture
- API reference writing
- Request and response documentation
- Complex search filters and pagination
- Authentication and error handling
- Clear examples for developers
- GitHub Pages-ready static documentation

## Endpoints

- `GET /vehicles/list` — list vehicles
- `GET /vehicles/details` — retrieve a vehicle
- `POST /vehicles/search` — search vehicles using structured filters

## Important note about the search endpoint

The search capability came from a separate microservice in the source material. For this portfolio version, it has been normalized into the same documentation experience as the list and details endpoints. The original `/v3/vehicle/search` and `/v4/vehicle/search` routes are intentionally not exposed.

The search contract has been sanitized: internal source mappings, corporate environments, proprietary identifiers, and real-world examples have been removed or replaced with neutral examples.

## Run locally

Open `docs/index.html` directly in a browser.

## Publish with GitHub Pages

1. Push the repository to GitHub.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**.
4. Select the `main` branch and `/docs` folder.
5. Save.

GitHub Pages visibility depends on your GitHub plan and repository settings. Do not assume that a private repository makes the published site private.
