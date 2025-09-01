# Getting Started

Quick start guide for the API:

## Installation
```bash
npm install api-client
```

## Basic Usage
```python
from api_client import UserAPI

client = UserAPI(api_key="your-key")
user = client.get_user(user_id=123)
print(user.email)
```