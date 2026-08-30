# CertifyClouds Scanner Homebrew Tap

Scan Azure Key Vaults for expiring secrets, certificates, and keys.

## Install

```bash
brew tap certifyclouds/certifyclouds
brew install certifyclouds
```

## Usage

```bash
# Authenticate with Azure
az login

# Scan all Key Vaults
cc-scan

# Export as JSON
cc-scan --format json --output report.json

# Security findings only
cc-scan --security-only
```

## Links

- [Documentation](https://docs.certifyclouds.com/scanner/)
- [PyPI](https://pypi.org/project/certifyclouds/)
- [Website](https://certifyclouds.com/scanner)
