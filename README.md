# JFrog Artifactory (artifactory)

JFrog Artifactory is a universal artifact repository manager supporting all major package formats and build tools including Maven, Gradle, npm, NuGet, PyPI, Docker, Helm, RubyGems, CocoaPods, and more. As the central hub of the JFrog Platform, Artifactory stores, manages, and distributes binary artifacts across the entire software development lifecycle. It integrates with CI/CD pipelines through native plugins for Jenkins, GitHub Actions, CircleCI, and other tools. Artifactory provides comprehensive REST APIs for managing repositories, artifacts, builds, security, and system configuration programmatically.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/artifactory/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Artifacts
- DevOps
- CI/CD
- Docker Registry
- Maven
- Package Management
- Repository

## Timestamps

- **Created:** 2024-01-15
- **Modified:** 2026-05-19

## APIs

### Artifactory REST API

Comprehensive REST API for managing artifacts, repositories, users, groups, permissions, replication, security, and system configuration in JFrog Artifactory.

- **Human URL:** [https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis)
- **Base URL:** `https://artifactory.example.com/artifactory/api`

#### Tags

- Artifacts
- Repositories
- REST

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/artifactory-rest-apis)
- [OpenAPI](openapi/artifactory-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/artifactory-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/artifactory-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Authentication](https://jfrog.com/help/r/jfrog-rest-apis/authentication)
- [JSON Schema](json-schema/artifactory-repository-configuration.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/artifactory-file-info.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/artifactory-permission-target.json) — [JSON Schema](https://json-schema.org/specification)

### Artifactory Query Language (AQL) API

Advanced search API using a SQL-like query language (AQL) for finding artifacts, builds, modules, and entries based on properties, statistics, and metadata.

- **Human URL:** [https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language](https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language)
- **Base URL:** `https://artifactory.example.com/artifactory/api/search/aql`

#### Tags

- AQL
- Query
- Search

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-artifactory-documentation/artifactory-query-language)
- [OpenAPI](openapi/artifactory-aql-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/artifactory-aql-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/artifactory-aql-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Code Examples](https://jfrog.com/help/r/jfrog-artifactory-documentation/aql-examples)

### Artifactory Docker Registry API

Docker Registry v2 API for pushing, pulling, and managing Docker images stored in JFrog Artifactory acting as a Docker registry.

- **Human URL:** [https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry](https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry)
- **Base URL:** `https://artifactory.example.com/artifactory/api/docker`

#### Tags

- Docker
- Containers
- Registry

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-artifactory-documentation/docker-registry)
- [OpenAPI](openapi/artifactory-docker-registry-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/artifactory-docker-registry-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/artifactory-docker-registry-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Artifactory Build Integration API

API for publishing and managing build information from CI/CD systems, enabling traceability between artifact versions and the builds that produced them.

- **Human URL:** [https://jfrog.com/help/r/jfrog-rest-apis/builds](https://jfrog.com/help/r/jfrog-rest-apis/builds)
- **Base URL:** `https://artifactory.example.com/artifactory/api/build`

#### Tags

- Builds
- CI/CD
- Integration

#### Properties

- [Documentation](https://jfrog.com/help/r/jfrog-rest-apis/builds)
- [OpenAPI](openapi/artifactory-build-integration-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/artifactory-build-info.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Terms of Service](https://jfrog.com/terms-of-service/)
- [Privacy Policy](https://jfrog.com/privacy-policy/)
- [Status Page](https://status.jfrog.com/)
- [Pricing](https://jfrog.com/pricing/)
- [Blog](https://jfrog.com/blog/)
- [GitHub Organization](https://github.com/jfrog)
- [X (Twitter)](https://twitter.com/jfrog)
- [Support](https://jfrog.com/support/)
- [Portal](https://jfrog.com/developers/)
- [Documentation](https://jfrog.com/help/)
- [Getting Started](https://jfrog.com/help/r/jfrog-artifactory-documentation/getting-started-with-artifactory)
- [Sign Up](https://jfrog.com/start-free/)
- [Login](https://my.jfrog.com/login/)
- [Resources](https://community.jfrog.com/)
- [YouTube](https://www.youtube.com/@jfrog)
- [C L I](https://jfrog.com/help/r/jfrog-cli/jfrog-cli)
- [Changelog](https://jfrog.com/help/r/jfrog-release-information/jfrog-release-notes)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Integrations](https://jfrog.com/integrations/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
