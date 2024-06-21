# Contribution Guidelines

## Structure

1. Chain ID folder (e.g., `/1`, `/56`, `/421614`). Only admins can add new chain ID folders.
2. Token address folder (e.g., `/421614/0x8s5d2fsd....5s8s6`).

## Files

Each token address folder should contain:

-   `logo.svg`: The token's logo.
-   `info.json`: Metadata about the token.

Example of `info.json`:

```json
{
    "address": "0x431825d2912F3BAB70dBdd92Ab1968d16EA8D9D7",
    "symbol": "USDT",
    "name": "USD Tether",
    "decimals": 6,
    "tags": ["stable"],
    "extensions": {}
}
```
