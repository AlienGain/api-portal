# API Documentation Portal

This repository hosts the API documentation for our services using GitHub Pages and Swagger UI.

## Available API Documentation

The following API documentation is available:

1. **API Gateway** - Documentation for the API Gateway service
2. **User Service** - Documentation for the User service
3. **Ledger Service** - Documentation for the Ledger service

## How to Access

You can access the API documentation in two ways:

1. **Visit the GitHub Pages site**: The documentation is hosted on GitHub Pages at the URL associated with this repository.

2. **Run locally**:
   - Clone this repository
   - Open `index.html` in your browser

## Direct Links

You can directly link to specific API documentation by using the following URL format:

```
https://[github-pages-url]/#docs/api-gateway.yaml
https://[github-pages-url]/#docs/user.yaml
https://[github-pages-url]/#docs/ledger.yaml
```

## Development

### Structure

- `index.html` - The main page that loads the Swagger UI
- `docs/` - Directory containing the OpenAPI/Swagger YAML files
  - `api-gateway.yaml` - API Gateway documentation
  - `user.yaml` - User Service documentation
  - `ledger.yaml` - Ledger Service documentation
- `_config.yml` - Jekyll configuration for GitHub Pages
- `Gemfile` - Ruby dependencies for GitHub Pages

### Updating Documentation

To update the API documentation:

1. Modify the corresponding YAML file in the `docs/` directory
2. Commit and push the changes to the repository
3. GitHub Pages will automatically rebuild the site

## License

This project is licensed under the terms specified in the LICENSE file.
