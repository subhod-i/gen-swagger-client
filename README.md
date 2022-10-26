# GEN-SWAGGER-CLIENT

Generate javascript swagger client from a swagger specification.

## Usage

```javascript
import { genSwaggerClient } from 'gen-swagger-client';

const client = await genSwaggerClient('http://example.com', {
      spec: { paths: { '/test': { get: { operationId: 'get_test' } } } }
})

client.api.getTest();
```
