# LivChart AI Analytics

Release repository for **LivChart AI Analytics** and **LivChart Local AI Analytics**.

This repository is used only for published application packages. It does not
contain the LivChart source code.

## Product Overview

LivChart is an AI-assisted analytics and BI platform for turning business data
into governed dashboards, charts, and workbook-style analysis.

LivChart combines:

- AI provider integration for chart and insight generation
- Data provider and query workflows
- ETL and DataStudio preparation
- AI-assisted Chart Wizard flows
- Dashboard Manager and dashboard viewing
- Analytics Studio workbooks for Excel-like analysis
- Sharing, permissions, and controlled publication flows

## Product Editions

### LivChart AI Analytics

Designed for cloud or managed AI provider workflows. It can connect to supported
AI providers such as OpenAI, Gemini, and Livaicloud for AI-assisted analytics,
chart planning, dashboard support, and insight generation.

### LivChart Local AI Analytics

Designed for local or private AI inference workflows. It supports local model
providers such as Ollama and LM Studio for organizations that need data privacy,
on-prem deployment, local GPU usage, or closed-network analytics.

## Release Packages

Download the package for your operating system from the latest GitHub Release:

| Platform | Asset |
| --- | --- |
| Windows | `LivChart_Windows_Dist.zip` |
| Linux | `LivChart_Linux_Dist.zip` |
| macOS | `LivChart_MacOS_Dist.zip` |

Each package includes the packaged application files and platform-specific run
scripts.

## Typical Flow

1. Admin connects an AI provider.
2. Admin connects data providers and creates queries.
3. Data is prepared in DataStudio / ETL.
4. Charts are created with Chart Wizard.
5. Dashboards are assembled in Dashboard Manager.
6. Users view shared dashboards.
7. Users create personal charts or workbooks in Analytics Studio.
8. Personal analysis can be shared or promoted through controlled publication
   flows.

## Analytics Studio

Analytics Studio is LivChart's workbook-style analysis workspace. Users can work
with ETL-backed sheets, filters, computed columns, pivots, charts, subtotals,
formatting, exports, and AI-assisted actions without directly changing governed
dashboard assets.

## Source Code Policy

This repository is intentionally release-only.

- Source code is not published here.
- Built zip packages are distributed through GitHub Releases.
- Release notes and checksums are provided with each version where available.

## Support

For installation, licensing, provider setup, or deployment support, contact the
LivChart maintainer or your internal LivChart administrator.
