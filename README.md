Recently verified tokens also get a special badge on the trends page:

<img width="236" alt="Screenshot 2024-03-09 at 15 48 23" src="https://github.com/CNFT-Predator/verified-tokens/assets/44160230/dd78dfb3-419f-4b4a-8b20-07531ea5a5dd">

Afterward, the badge will turn into checkmark.

<img width="183" alt="Screenshot 2024-03-09 at 16 03 42" src="https://github.com/CNFT-Predator/verified-tokens/assets/44160230/cda80cd1-5cef-4232-81e1-4345881971c9">

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

### Please attach png or jpg image file to the description
![image](https://github.com/CNFT-Predator/verified-tokens/assets/44160230/26b1c721-f4d4-46c9-bd07-6f985bba3c29)

#### Please attach verification payment of 100 ADA to the following address as tx hash to the description
```
addr1qycq6luvdlfpmekh7fg4y5p92px2j9u9g3jneuu2flyxueq4fvegghd65626mer4amt9k60myjanlpdn7zwfn2cvrjusaqf5z8
```
