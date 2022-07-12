# Api-Leo - API Definition

This API is used to manage Employees and Departments based in it's models.

## Module Overview

| Module   | Content                                                  |
|----------|----------------------------------------------------------|
| `client` | Generated API client                                     |
| `server` | Generated API server                                     |
| `spec`   | API spec file in openAPI format user for code generation |

File `src/main/resources/api-leo.yaml` of `spec module` provides the definition for all endpoints for Create, Read,
Update and Delete operations.

## Generation

To generate client and server dependencies you can run in the root folder:

```bash
mvn clean package
```