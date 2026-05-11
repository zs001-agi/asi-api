# API Documentation Update

## Overview
Our AI service continues to evolve, offering new functionalities and improvements. Below are the latest updates to our API documentation.

## New Endpoints

### Endpoint: `/predict`

**Description:**  
This endpoint is designed for real-time predictions based on provided data inputs.

#### Request Parameters:
- `data`: JSON array of input data (required)

#### Example Request:
```bash
curl -X POST "https://api.example.com/predict" \
-H "Content-Type: application/json" \
-d '[
  {
    "feature1": 0.5,
    "feature2": 3
  },
  {
    "feature1": 0.7,
    "feature2": 4
  }
]'
```

#### Response:
- `predictions`: JSON array of predictions

## Pricing Table Update

| Feature                     | Basic Plan ($/month) | Standard Plan ($/month) |
|-----------------------------|----------------------|----------------------------|
| Number of Predictions         | 100                  | 500                        |
| Real-time Prediction Support  | No                   | Yes                          |
| Custom Model Training         | Limited              | Unrestricted                 |

For more detailed pricing and plans, please visit our [Pricing Page](https://www.example.com/pricing).

## Contact Us
If you have any questions or need further assistance, feel free to contact our support team at support@example.com.

---