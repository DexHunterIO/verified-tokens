To add a new token, create a new pull request with the following format:

```
 "token_id": {
    "token_id": token_id,
    "token_policy": policy_id,
    "token_ascii": token_full_name,
    "is_verified": true,
    "ticker": token_ticker,
    "decimals": token_decimals
  }
```

Example:
```
 "02f74e4bd8fbf86339e55569e710886b04208a6005338bf2089187bf445643": {
    "token_id": "02f74e4bd8fbf86339e55569e710886b04208a6005338bf2089187bf445643",
    "token_policy": "02f74e4bd8fbf86339e55569e710886b04208a6005338bf2089187bf",
    "token_ascii": "DVC",
    "is_verified": true,
    "ticker": "DVC",
    "decimals": 0
  }
```
