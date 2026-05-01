# API Documentation Update

## Endpoint Descriptions

### /predict

**Description**: Predicts the next best action based on historical data.

- **Method**: POST
- **Parameters**:
  - `data`: JSON object containing historical user actions.
- **Returns**: JSON object with predicted next action.

```json
{
  "action": "click_button"
}
```

### /train

**Description**: Trains the AI model on new data.

- **Method**: PUT
- **Parameters**:
  - `data`: JSON array of training examples.
- **Returns**: Confirmation message.

```json
{
  "message": "Training successful"
}
```

## Usage Examples with curl

### Predict Example

```bash
curl -X POST -H "Content-Type: application/json" -d '{"data": {"user_id": "12345", "actions": ["login", "view_home"]}}' https://api.example.com/predict
```

### Train Example

```bash
curl -X PUT -H "Content-Type: application/json" -d '[{"id": "67890", "action": "logout"}, {"id": "12345", "action": "view_profile"}]' https://api.example.com/train
```

## Pricing Table Update

| Feature | Monthly Fee |
|---------|-------------|
| Predict | $10         |
| Train   | $5          |

For more detailed pricing information, please visit our [Pricing Page](https://www.example.com/pricing).