# API Documentation Update

## Overview
This document outlines recent updates and additions to our self-evolving AI service, designed to enhance its functionality and user experience.

## Endpoint Updates

### 1. Enhanced Text Analysis Endpoint

**Description**: The new endpoint now offers advanced text analysis capabilities including sentiment detection, entity recognition, and keyword extraction with improved accuracy.

**Endpoint URL**: `/analyze/text`

#### Usage Example
```bash
curl -X POST https://api.example.com/analyze/text \
-H "Content-Type: application/json" \
-d '{
    "text": "Your text here"
}'
```

### 2. Image Recognition Endpoint

**Description**: This endpoint enables users to submit images for object recognition, scene detection, and facial analysis.

**Endpoint URL**: `/recognize/image`

#### Usage Example
```bash
curl -X POST https://api.example.com/recognize/image \
-H "Content-Type: image/jpeg" \
--data-binary @path/to/image.jpg
```

## Pricing Table Update

| Feature | Basic Plan | Standard Plan | Premium Plan |
|---------|------------|---------------|--------------|
| Text Analysis (Basic) | $10/month | $25/month | $40/month |
| Advanced Text Analysis | - | - | Included |
| Image Recognition | $15/month | $30/month | $60/month |

For more detailed pricing and subscription options, visit [our pricing page](https://www.example.com/pricing).

---

This update should help our users leverage the latest features of our AI service efficiently.