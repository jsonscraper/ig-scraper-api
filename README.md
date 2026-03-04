# IG Scraper API

![Packagist PHP Version Support](https://img.shields.io/packagist/php-v/jsonscraper/ig-scraper-api)
![GitHub last commit](https://img.shields.io/github/last-commit/jsonscraper/ig-scraper-api)
![GitHub](https://img.shields.io/github/license/jsonscraper/ig-scraper-api)

[<img src="https://run.pstmn.io/button.svg" alt="Run In Postman" style="width: 128px; height: 32px;">](https://www.postman.com/jsonscraper/workspace/jsonscraper/collection/52903714-fe84d353-0a19-431f-a39d-1c2640d96fb0?action=share&creator=52903714)

[<img width="2206" alt="evelode" src="https://github.com/user-attachments/assets/92a16057-ff9d-49ad-bb37-ecb7e2dd5f5f">](https://www.postman.com/jsonscraper/workspace/jsonscraper/collection/52903714-fe84d353-0a19-431f-a39d-1c2640d96fb0?action=share&creator=52903714)

Starting with the [IG Scraper API](https://jsonscraper.com/services/ig-scraper-api/), you gain access to a powerful ecosystem designed to speed up development and simplify data collection. Built for large-scale crawling, low latency, and high availability, our API is ideal for analytics, monitoring, and automation projects.

## Quick Start

We provide modern API wrappers with detailed examples to help you integrate faster:

- [API Documentation (Postman)](https://www.postman.com/jsonscraper/workspace/jsonscraper/collection/52903714-fe84d353-0a19-431f-a39d-1c2640d96fb0?action=share&creator=52903714)
- [API Documentation (New)](https://documenter.getpostman.com/view/52903714/2sBXcKCdc4)

## Run in Postman

Use our ready-to-use Postman collection to instantly start testing endpoints and exploring API capabilities.

## API Documentation

With our detailed Postman collection, you can explore and test all IG Scraper API endpoints in real time. Start with a Personal plan to test all available endpoints.

## Choose the right plan for you

Find a plan that best matches the scale you need for your application.

Plan | Price / month	| Requests / month	| Cost per request
-- | -- | -- | --
Personal | $49.99	| 20,000 | $0.0025
Business | $119.00	| 50,000 | $0.0024
Professional	| $169.00	| 75,000 | $0.0023
Corporate	| $199.00	| 100,000	| $0.0020
Enterprise	| $299.00	| 150,000	| $0.0020
Executive	| $449.00	| 250,000	| $0.0018
Premier	| $799.00	| 500,000	| $0.0016
Ultimate	| $1,399.00	| 1,000,000	| $0.0014

## Authentication

Authentication occurs by passing the [license key](https://jsonscraper.com/services/ig-scraper-api/) value through a query string named `license_key`.

API Server Url: `https://ig.jsonscraper.com`

## Security

For more reliable interaction with the API server, you should use the license_key.

Example of a signed request:

```bash
curl -X 'GET' \ 'https://ig.jsonscraper.com/v1/user/by/username?username=apple&license_key=license_key' \ -H 'accept: application/json'
```

- `https://ig.jsonscraper.com` - API server url
- `/v1/user/by/username` - API route, all available routes you can find in our documentation
- `username` - Account username
- `license_key` - your own unique license key, which can be purchased here

## Rate Limits

The developer `license_key` gives the right to use all methods within the IG Scraper API within the limit of requests for a specific period. Requests limit based on your license length and will be flushed when you renew or upgrade your license. Empty or invalid responses doesn't affect requests counter.

Every license plan also have a requests per minute rate limit. More info about license plans you can check [here](https://jsonscraper.com/services/ig-scraper-api/).

## License

You can [buy](https://jsonscraper.com/services/ig-scraper-api/) a valid license for IG Scraper API here. This license based on period of usage and requests count.

Please [contact us via website chat](https://jsonscraper.com#chatraChatExpanded) if you need to submit a support request or have additional questions.

## Changelog

You can found it in our [Postman collection](https://www.postman.com/jsonscraper/workspace/jsonscraper/collection/52903714-fe84d353-0a19-431f-a39d-1c2640d96fb0?action=share&creator=52903714) for IG Scraper API.
