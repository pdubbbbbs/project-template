# API Documentation Guide

## Overview

This document provides a template for API documentation. When documenting APIs, follow this structure for consistency.

## API Endpoints

### Template Endpoint Structure

```markdown
## Endpoint Name

**URL:** `/api/endpoint`

**Method:** `GET/POST/PUT/DELETE`

**Authentication:** Required/Not Required

### Request Parameters

| Parameter | Type | Required | Description |
|-----------|------|----------|-------------|
| param1 | string | Yes | Description of param1 |
| param2 | number | No | Description of param2 |

### Request Body

```json
{
    "field1": "value1",
    "field2": "value2"
}
```

### Response

#### Success Response (200 OK)

```json
{
    "status": "success",
    "data": {
        "field1": "value1",
        "field2": "value2"
    }
}
```

#### Error Response (4XX/5XX)

```json
{
    "status": "error",
    "message": "Error description"
}
```

### Example

```bash
curl -X POST \
  http://api.example.com/endpoint \
  -H 'Content-Type: application/json' \
  -d '{"field1": "value1"}'
```
```

## Best Practices

1. Keep documentation up to date with code changes
2. Include request/response examples
3. Document all parameters and fields
4. Specify authentication requirements
5. Include error scenarios and handling
6. Provide curl examples for testing

## Versioning

Document API versions clearly:

- v1.0.0 - Initial release
- v1.1.0 - Added new endpoints
- v2.0.0 - Breaking changes
