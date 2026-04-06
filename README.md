# Azure DevSecOps Key Vault Integration

## 🚀 Overview

This project demonstrates secure secret management using Azure Key Vault integrated with Azure App Service via Managed Identity, following DevSecOps best practices.

## 🔐 Problem

Storing secrets in application configuration is insecure and violates security best practices.

## ✅ Solution

* Azure Key Vault for secure secret storage
* Managed Identity for authentication (no credentials)
* RBAC for access control
* Key Vault references in App Service

## 🏗️ Architecture

App Service → Managed Identity → Azure Key Vault → Secrets

## 🛠️ Technologies

* Azure Key Vault
* Azure App Service
* Managed Identity
* Azure RBAC
* Azure DevOps

## ⚙️ Implementation

### Key Vault

* Created secure vault
* Stored application secrets

### Managed Identity

* Enabled System-Assigned Identity
* Used for authentication

### RBAC

* Assigned Key Vault Secrets User role

### App Configuration

* Used Key Vault references in app settings

## 🔐 Security Benefits

* No hardcoded secrets
* Least privilege access
* Centralized secret management

## 📸 Screenshots

(To be added)

## 🚀 Future Improvements

* Infrastructure as Code (Bicep/Terraform)
* CI/CD automation
* Monitoring and alerts
