# JFrog Artifactory (artifactory)
JFrog Artifactory is a universal artifact repository manager supporting all major package formats and build tools including Maven, Gradle, npm, NuGet, PyPI, Docker, Helm, RubyGems, CocoaPods, and more. As the central hub of the JFrog Platform, Artifactory stores, manages, and distributes binary artifacts across the entire software development lifecycle. It integrates with CI/CD pipelines through native plugins for Jenkins, GitHub Actions, CircleCI, and other tools. Artifactory provides comprehensive REST APIs for managing repositories, artifacts, builds, security, and system configuration programmatically.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Artifacts, DevOps, CI/CD, Docker Registry, Maven, Package Management, Repository

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-04-19

## APIs

### Artifactory REST API
Comprehensive REST API for managing artifacts, repositories, users, groups, permissions, replication, security, and system configuration in JFrog Artifactory.

**Human URL:** [https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis)

#### Tags:

 - Artifacts, Repositories, REST

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis)
- [OpenAPI](openapi/artifactory-rest-api-openapi.yml)
- [Authentication](https://jfrog.com/help/r/jfrog-rest-apis/authentication)
- [JSONSchema](json-schema/artifactory-repository-configuration.json)
- [JSONSchema](json-schema/artifactory-file-info.json)
- [JSONSchema](json-schema/artifactory-permission-target.json)

### Artifactory Query Language (AQL) API
Advanced search API using a SQL-like query language (AQL) for finding artifacts, builds, modules, and entries based on properties, statistics, and metadata.

**Human URL:** [https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language](https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language)

#### Tags:

 - AQL, Query, Search

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language)
- [OpenAPI](openapi/artifactory-aql-api-openapi.yml)
- [CodeExamples](https://jfrog.com/help/r/jfrog-artifactory-documentation/aql-examples)

### Artifactory Docker Registry API
Docker Registry v2 API for pushing, pulling, and managing Docker images stored in JFrog Artifactory acting as a Docker registry.

**Human URL:** [https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry](https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry)

#### Tags:

 - Docker, Containers, Registry

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry)
- [OpenAPI](openapi/artifactory-docker-registry-api-openapi.yml)

### Artifactory Build Integration API
API for publishing and managing build information from CI/CD systems, enabling traceability between artifact versions and the builds that produced them.

**Human URL:** [https://jfrog.com/help/r/jfrog-rest-apis/builds](https://jfrog.com/help/r/jfrog-rest-apis/builds)

#### Tags:

 - Builds, CI/CD, Integration

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/builds)
- [OpenAPI](openapi/artifactory-build-integration-api-openapi.yml)
- [JSONSchema](json-schema/artifactory-build-info.json)

## Common Properties

- [Terms of Service](https://jfrog.com/terms-of-service/)
- [Privacy Policy](https://jfrog.com/privacy-policy/)
- [Status Page](https://status.jfrog.com/)
- [Pricing](https://jfrog.com/pricing/)
- [Blog](https://jfrog.com/blog/)
- [JFrog GitHub](https://github.com/jfrog)
- [JFrog on X](https://twitter.com/jfrog)
- [Support](https://jfrog.com/support/)
- [Developer Portal](https://jfrog.com/developers/)
- [Documentation](https://jfrog.com/help/)
- [Getting Started](https://jfrog.com/help/r/jfrog-artifactory-documentation/getting-started-with-artifactory)
- [Sign Up Free](https://jfrog.com/start-free/)
- [Login](https://my.jfrog.com/login/)
- [JFrog Community](https://community.jfrog.com/)
- [YouTube](https://www.youtube.com/@jfrog)
- [JFrog CLI](https://jfrog.com/help/r/jfrog-cli/jfrog-cli)
- [Release Notes](https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes)

## Artifacts

### OpenAPI

- [Artifactory REST API](openapi/artifactory-rest-api-openapi.yml)
- [Artifactory AQL API](openapi/artifactory-aql-api-openapi.yml)
- [Artifactory Docker Registry API](openapi/artifactory-docker-registry-api-openapi.yml)
- [Artifactory Build Integration API](openapi/artifactory-build-integration-api-openapi.yml)

## Features

| Name | Description |
|------|-------------|
| Universal Package Management | Single repository manager supporting 30+ package formats including Maven, npm, NuGet, PyPI, Docker, Helm, Conda, Conan, and more. |
| Artifact Metadata and Search | Rich metadata tagging and AQL query language for finding artifacts based on properties, statistics, dates, and custom attributes. |
| Build Integration | Native CI/CD integration publishing build information to track which artifacts were produced by which build, enabling full artifact traceability. |
| Security and Permissions | Fine-grained permission targets, LDAP/SAML/SSO integration, API key management, and access tokens for secure artifact access control. |
| Replication | Push and pull replication across multiple Artifactory instances for geo-distributed teams and disaster recovery. |
| Docker Registry | Full Docker Registry v2 API compliance for pushing, pulling, and managing Docker images with automated vulnerability scanning. |

## Use Cases

| Name | Description |
|------|-------------|
| CI/CD Pipeline Integration | Development teams integrate Artifactory with Jenkins, GitHub Actions, and other CI/CD tools to store, version, and distribute build artifacts. |
| Container Registry | Platform engineering teams use Artifactory as an enterprise Docker registry with security scanning, access controls, and promotion workflows. |
| Dependency Proxy | Organizations proxy public package registries (npm, PyPI, Maven Central) through Artifactory to cache dependencies, apply security policies, and ensure build reproducibility. |
| Release Management | Release engineers promote artifacts through staging environments using build promotion, managing the lifecycle from snapshot to release. |

## Integrations

| Name | Description |
|------|-------------|
| Jenkins | Official Jenkins Artifactory Plugin for publishing artifacts and build information from Jenkins pipelines. |
| GitHub Actions | JFrog GitHub Actions for integrating Artifactory into GitHub CI/CD workflows. |
| JFrog Xray | Deep integration with JFrog Xray for continuous security and compliance scanning of artifacts and dependencies. |
| JFrog Pipelines | Native integration with JFrog Pipelines for end-to-end CI/CD orchestration using Artifactory as the artifact store. |

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
