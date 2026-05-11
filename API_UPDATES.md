# API Documentation Update

## Introduction

Welcome to our evolving AI service. This document outlines recent updates and new features.

## Updates

### 1. New Endpoint: Sentiment Analysis

**Description**: Analyze the sentiment of text data (positive, negative, neutral).

**Endpoint**: `/api/v2/sentiment`

#### Request Example
```bash
curl -X POST "https://api.example.com/api/v2/sentiment" \
-H "Content-Type: application/json" \
-d '{"text": "I love this product!"}'
```

#### Response Example
```json
{
  "sentiment": "positive",
  "confidence": 0.95
}
```

### 2. Pricing Table Update

Our service now offers a tiered pricing model based on API usage.

| Plan | Monthly Limit (Requests) | Cost per Request |
|------|--------------------------|------------------|
| Basic | 1,000                    | $0.01            |
| Pro  | 5,000                    | $0.008           |

For more detailed pricing, please visit our [pricing page](https://example.com/pricing).

## Contact

If you have any questions or need further assistance, please contact our support team at support@example.com.

---

This update enhances your ability to interact with our AI service efficiently and effectively, providing a more seamless experience.