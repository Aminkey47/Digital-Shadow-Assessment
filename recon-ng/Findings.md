# Findings

## Target

OWASP (owasp.org)

## Modules Tested

- Bing Domain Web
- Shodan Hostname
- Censys (configuration)

## Results

### Bing Domain Web

- Successfully executed the module.
- Returned limited results, primarily search URLs rather than useful host information.

### Shodan

- Module installed successfully.
- Authentication succeeded using the API key.
- Searches failed because the free OSS plan does not include the required query credits.

### Censys

- Created a Censys account.
- Modern Personal Access Tokens were incompatible with the Recon-ng module, which expects the legacy API authentication method.

## Overall Findings

Recon-ng demonstrated the power of modular OSINT but also highlighted that many advanced modules depend on third-party APIs and paid service tiers.
