# Classplus Token Extractor API

🔐 Extract Classplus JWT token using mobile, orgCode, and OTP.

## 🛠 Endpoints:

1. `/send-otp` – POST:
```json
{
  "phone": "XXXXXXXXXX",
  "orgCode": "abcd"
}
```

2. `/verify-otp` – POST:
```json
{
  "otp": "123456",
  "phone": "XXXXXXXXXX",
  "orgCode": "abcd"
}
```

Returns:
```json
{
  "token": "eyJhbGciOiJIUzI1NiIs..."
}
```

[![Deploy to Render](https://render.com/images/deploy-to-render-button.svg)](https://render.com/deploy)
