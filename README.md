# Azure AD B2C Custom Policy Generator

Generation of Azure AD B2C Tenant Identity Experience Framework (IEF) XML policies.

> Configure the config.json according to your IEF values
[Adding Signing and Encryption Keys for Identity Experience Framework](https://learn.microsoft.com/en-us/azure/active-directory-b2c/tutorial-create-user-flows?pivots=b2c-custom-policy#add-signing-and-encryption-keys-for-identity-experience-framework-applications)

## Local Accounts
b2c-local-accounts.ps1
> Generate IEF XML for Local Accounts support only.

<img src="images/b2c-local-accounts.png" width="300">

## Local Accounts with signup disabled
b2c-local-accounts-with-signup-disabled.ps1
> Generate IEF XML for Local Accounts Only with self-service signup disabled.

<img src="images/b2c-local-accounts-signup-disabled.png" width="300">

## Local Accounts and federated Azure AD
Pending.