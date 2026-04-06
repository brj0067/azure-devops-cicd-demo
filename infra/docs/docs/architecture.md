# Architecture

## Flow
1. Application runs on Azure App Service
2. Managed Identity authenticates to Azure AD
3. Azure Key Vault validates access via RBAC
4. Secrets are retrieved securely

## Benefits
- No secrets in code
- Secure identity-based access
