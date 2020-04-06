# Spryker Feature: Company Account

The Company Account feature allows you to control user access to the system within an organization by configuring different permissions and roles for company's entities (units) and users. You can set up an own company structure of business units and users with various levels of permissions. This feature also enables you to create own permission rules and assign them to specific users.

## Installation

```
composer require spryker-feature/company-account
```

## Recommended feature dependencies
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [AuthRestApi ^2.6.0](https://github.com/spryker/auth-rest-api) (Glue)
- [BusinessOnBehalfExtension ^1.0.0](https://github.com/spryker/business-on-behalf-extension) (Extension)
- [BusinessOnBehalfGuiExtension ^1.0.0](https://github.com/spryker/business-on-behalf-gui-extension) (Extension)
- [CompaniesRestApi ^1.1.0](https://github.com/spryker/companies-rest-api) (Glue)
- [CompanyBusinessUnitAddressesRestApi ^1.0.0](https://github.com/spryker/company-business-unit-addresses-rest-api) (Glue)
- [CompanyBusinessUnitsRestApi ^1.2.0](https://github.com/spryker/company-business-units-rest-api) (Glue)
- [CompanyBusinessUnitsRestApiExtension ^1.0.0](https://github.com/spryker/company-business-units-rest-api-extension) (Extension)
- [CompanyRolesRestApi ^1.1.0](https://github.com/spryker/company-roles-rest-api) (Glue)
- [CompanyUserAuthRestApi ^2.0.0](https://github.com/spryker/company-user-auth-rest-api) (Glue)
- [CompanyUserExtension ^1.2.0](https://github.com/spryker/company-user-extension) (Extension)
- [CompanyUsersRestApi ^2.1.0](https://github.com/spryker/company-users-rest-api) (Glue)
- [CompanyUserStorageExtension ^1.0.0](https://github.com/spryker/company-user-storage-extension) (Extension)
- [OauthCompanyUser ^2.0.0](https://github.com/spryker/oauth-company-user) (Connector)
- [OauthCompanyUserExtension ^1.1.0](https://github.com/spryker/oauth-company-user-extension) (Extension)
