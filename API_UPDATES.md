# API Documentation Update for Self-Evolving AI Service

## New Endpoints

### 1. Image Recognition Endpoint
**Description:** Analyzes images to identify objects, faces, and text.

#### Request:
```curl
POST /api/v2/image_recognition HTTP/1.1
Host: ai-service.example.com
Content-Type: application/json
Authorization: Bearer YOUR_ACCESS_TOKEN

{
  "image_url": "http://example.com/sample-image.jpg"
}
```

#### Response:
```json
{
  "objects": ["dog", "cat"],
  "faces": [{"age": 25, "emotion": "happy"}],
  "text": "Hello world!"
}
```

## Pricing Table Update

| Feature               | Free Tier (100 requests/month) | Basic ($5/month) | Pro ($20/month) |
|-----------------------|--------------------------------|------------------|-----------------|
| Image Recognition     | 10 requests/day                | 100 requests/day   | Unlimited       |
| Custom Training Models| 2 models per month             | Unlimited        | Unlimited       |

For more details and a complete guide, visit our [API Documentation](https://docs.ai-service.example.com).