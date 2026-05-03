# Sonatype

Sonatype provides software supply chain management solutions including Sonatype Lifecycle (IQ Server), Repository Firewall, SBOM Manager, and Nexus Repository. The Lifecycle Public REST API enables DevSecOps teams to automate application portfolio management, policy enforcement, vulnerability analysis, SBOM generation, and component scanning.

**URL:** [https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/sonatype/refs/heads/main/apis.yml)

## Tags

Software Supply Chain, Security, Vulnerability Management, SBOM, Software Composition Analysis, DevSecOps

## APIs

### Sonatype Lifecycle API

The Sonatype Lifecycle Public REST API (v1.201.0) provides 188 endpoints for managing applications, organizations, policies, policy violations, waivers, vulnerability analysis, SBOM generation (SPDX, CycloneDX), scan management, component search, reports, source control integration, users, and roles.

**Human URL:** [https://help.sonatype.com/en/iq-api-reference.html](https://help.sonatype.com/en/iq-api-reference.html)

#### Tags

Software Supply Chain, Security, Policy, Vulnerability Management, SBOM, Software Composition Analysis, Applications, Organizations

#### Properties

- [Documentation](https://help.sonatype.com/en/iq-api-reference.html)
- [Reference](https://help.sonatype.com/en/rest-apis.html)
- [OpenAPI](openapi/sonatype-lifecycle-openapi.yml)
- [JSON Schema - Application](json-schema/sonatype-application-schema.json)
- [JSON Schema - Policy Violation](json-schema/sonatype-policy-violation-schema.json)

## Artifacts

### OpenAPI Specifications

| File | Description |
|---|---|
| [sonatype-lifecycle-openapi.yml](openapi/sonatype-lifecycle-openapi.yml) | Sonatype Lifecycle Public REST API v1.201.0 (188 paths) |

### JSON Schema

| File | Description |
|---|---|
| [sonatype-application-schema.json](json-schema/sonatype-application-schema.json) | Schema for Sonatype Lifecycle application objects |
| [sonatype-policy-violation-schema.json](json-schema/sonatype-policy-violation-schema.json) | Schema for policy violation objects |

### JSON Structure

| File | Description |
|---|---|
| [sonatype-application-structure.json](json-structure/sonatype-application-structure.json) | Application object structure documentation |

### JSON-LD

| File | Description |
|---|---|
| [sonatype-context.jsonld](json-ld/sonatype-context.jsonld) | JSON-LD context for Sonatype Lifecycle entities |

### Examples

| File | Description |
|---|---|
| [sonatype-list-applications-example.json](examples/sonatype-list-applications-example.json) | List applications example |
| [sonatype-search-component-example.json](examples/sonatype-search-component-example.json) | Search component by PURL example |

### Spectral Rules

| File | Description |
|---|---|
| [sonatype-rules.yml](rules/sonatype-rules.yml) | Spectral ruleset for Sonatype Lifecycle API conventions |

### Naftiko Capabilities

#### Shared Definitions

| File | Description |
|---|---|
| [shared/sonatype-lifecycle.yaml](capabilities/shared/sonatype-lifecycle.yaml) | Per-API capability definition for Sonatype Lifecycle |

#### Workflow Capabilities

| File | Description | Tools |
|---|---|---|
| [software-supply-chain-security.yaml](capabilities/software-supply-chain-security.yaml) | Software supply chain security workflows for DevSecOps teams | 9 tools |

### Vocabulary

| File | Description |
|---|---|
| [sonatype-vocabulary.yml](vocabulary/sonatype-vocabulary.yml) | Sonatype Lifecycle vocabulary and domain terms |

## Common Properties

- [Portal](https://www.sonatype.com/)
- [Documentation](https://help.sonatype.com/)
- [Website](https://www.sonatype.com/)
- [GitHub](https://github.com/sonatype-nexus-community)
- [Blog](https://www.sonatype.com/blog)
- [Changelog](https://help.sonatype.com/en/sonatype-iq-server-2025-release-notes.html)
- [Support](https://support.sonatype.com/)

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
