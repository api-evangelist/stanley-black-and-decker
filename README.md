# Stanley Black & Decker

Stanley Black & Decker is a global manufacturer and marketer of hand tools, power tools, and related accessories. Through brands like DEWALT, Stanley, Craftsman, and Black+Decker, the company provides connected tool management platforms, IoT solutions, and partner integrations for jobsite productivity.

- **Website:** [https://www.stanleyblackanddecker.com/](https://www.stanleyblackanddecker.com/)
- **DEWALT Website:** [https://www.dewalt.com/](https://www.dewalt.com/)
- **Tool Connect Portal:** [https://sitemanager.dewalt.com/](https://sitemanager.dewalt.com/)
- **GitHub Org:** [https://github.com/StanleyInnovation](https://github.com/StanleyInnovation)
- **Privacy Policy:** [https://www.stanleyblackanddecker.com/privacy-notice](https://www.stanleyblackanddecker.com/privacy-notice)
- **Terms of Service:** [https://www.stanleyblackanddecker.com/terms-use](https://www.stanleyblackanddecker.com/terms-use)

## APIs

### DEWALT Tool Connect API

The DEWALT Tool Connect API enables integration with DEWALT's connected tool management platform, allowing partners to access tool inventory, track assets, manage Bluetooth-connected products, and synchronize jobsite data. Used by fleet management and construction software providers.

**Tags:** Connected Tools, IoT, Tool Management, Jobsite

| Resource | URL |
|---|---|
| Portal | [https://sitemanager.dewalt.com/](https://sitemanager.dewalt.com/) |
| Documentation | [https://www.dewalt.com/systems/tool-connect](https://www.dewalt.com/systems/tool-connect) |
| OpenAPI | [openapi/stanley-black-and-decker-tool-connect-api-openapi.yml](openapi/stanley-black-and-decker-tool-connect-api-openapi.yml) |
| Spectral Rules | [rules/stanley-black-and-decker-rules.yml](rules/stanley-black-and-decker-rules.yml) |
| Capabilities | [capabilities/jobsite-tool-management.yaml](capabilities/jobsite-tool-management.yaml) |

### Stanley X IoT API

Stanley X is the innovation arm of Stanley Black & Decker providing IoT connectivity APIs for smart factory solutions, equipment management, and digital manufacturing workflows.

**Tags:** IoT, Smart Factory, Industrial, Manufacturing

## OpenAPI Specifications

| API | File |
|---|---|
| DEWALT Tool Connect API | [openapi/stanley-black-and-decker-tool-connect-api-openapi.yml](openapi/stanley-black-and-decker-tool-connect-api-openapi.yml) |

**Operations:** List Tools, Get Tool, Get Tool Usage, List Batteries, Get Battery, List Assets, Register Asset, Get Asset, List Jobsites, Create Jobsite, Get Jobsite, List Users

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/tool-connect-api.yaml](capabilities/shared/tool-connect-api.yaml) | DEWALT Tool Connect API — connected tool and asset management |

### Workflow Capabilities

| Capability | File | Description |
|---|---|---|
| Jobsite Tool Management | [capabilities/jobsite-tool-management.yaml](capabilities/jobsite-tool-management.yaml) | Full jobsite tool tracking, battery health, asset registration, and team management |

## Spectral Rules

| File | Description |
|---|---|
| [rules/stanley-black-and-decker-rules.yml](rules/stanley-black-and-decker-rules.yml) | Spectral ruleset enforcing Stanley Black & Decker API conventions |

## JSON Schemas

| Schema | File |
|---|---|
| Tool | [json-schema/stanley-black-and-decker-tool-schema.json](json-schema/stanley-black-and-decker-tool-schema.json) |
| Battery | [json-schema/stanley-black-and-decker-battery-schema.json](json-schema/stanley-black-and-decker-battery-schema.json) |

## JSON Structures

| Structure | File |
|---|---|
| Tool | [json-structure/stanley-black-and-decker-tool-structure.json](json-structure/stanley-black-and-decker-tool-structure.json) |

## JSON-LD Context

| File | Description |
|---|---|
| [json-ld/stanley-black-and-decker-context.jsonld](json-ld/stanley-black-and-decker-context.jsonld) | JSON-LD context mapping SBD connected tool concepts to schema.org and IoT ontologies |

## Examples

| Example | File |
|---|---|
| List Tools | [examples/stanley-black-and-decker-list-tools-example.json](examples/stanley-black-and-decker-list-tools-example.json) |
| Register Asset | [examples/stanley-black-and-decker-register-asset-example.json](examples/stanley-black-and-decker-register-asset-example.json) |

## Vocabulary

| File | Description |
|---|---|
| [vocabulary/stanley-black-and-decker-vocabulary.yml](vocabulary/stanley-black-and-decker-vocabulary.yml) | Domain vocabulary for DEWALT connected tools, IoT, and jobsite management concepts |

## Maintainers

**FN:** API Evangelist

**Email:** info@apievangelist.com
