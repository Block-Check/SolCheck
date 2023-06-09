# SolCheck - B2B ML scam detection service

__All SolCheck code repositories are private because it is cybersecurity and any publication of code can be used by scammers__

### Quick Start
You can use our [documentation](https://solcheck.gitbook.io/docs-of-solcheck/) or follow this guide 

#### Get your API keys
Your API requests are authenticated using API keys. Any request that doesn't include an API key will return an error.
You can generate an API key from an early access form, read more in [Create API Key](https://solcheck.gitbook.io/docs-of-solcheck/api-overview/create-api-key) section.

#### NFT scam detection
Make your first request which will check if a given NFT presents a risk of scams
```
curl -X POST https://api.solcheck.xyz/Prod/solana/v0/mainnet/token/check \
    -H 'x-api-key: <API_KEY>' \
    -d 2hQZuDm1y4HPiphKnEgJNsGWa4B4M5VhMdAbXNPABgfw
```
Get your first response: 
```
{
    "result": "SUSPECTED_MALICIOUS", 
    "malicious_type": "PHISHING",
    "token_address": "2hQZuDm1y4HPiphKnEgJNsGWa4B4M5VhMdAbXNPABgfw"
}
```

### Contacts

[Site](https://app.solcheck.xyz)

[Twitter](https://twitter.com/SolanaCheck)

[Corporate email](mailto:solanacheck@gmail.com)

[CEO email](mailto:vadimlarintech@gmail.com)
