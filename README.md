# AzureAD Pod Identity and Azure Key Vault FlexVolume for Kubernetes

This repository provides all required YAML to use secrets from *Azure Key Vault* without specifying sensitive data in *Kubernetes Secrets*, instead a *Azure AD Pod Identity* is used to issue authenticated calls to *Azure Key Vault*.

Further information on this sample can be found on my blog at

  * https://thorsten-hans.com/azure-ad-pod-identity-in-aks-a-journey-to-integrate-azure-key-vault-d09bc9f8f70b
