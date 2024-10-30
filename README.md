# Spryker Feature: Company Account

The Company Account feature allows you to control user access to the system within an organization by configuring different permissions and roles for company's entities (units) and users. You can set up an own company structure of business units and users with various levels of permissions. This feature also enables you to create own permission rules and assign them to specific users.

[Learn more](https://docs.spryker.com/docs/pbc/all/customer-relationship-management/202307.0/company-account-feature-overview/company-account-feature-overview.html)

## Installation

```
composer require spryker-feature/company-account
```

## Recommended feature dependencies
- [spryker-feature/customer-account-management](https://github.com/spryker-feature/customer-account-management)

If you don't include the feature dependencies, make sure you use the respective modules instead.

## Optional modules
- [AuthRestApi ^2.15.0](https://github.com/spryker/auth-rest-api) (Legacy Glue)
- [BusinessOnBehalfExtension ^1.0.0](https://github.com/spryker/business-on-behalf-extension) (Extension)
- [BusinessOnBehalfGuiExtension ^1.0.0](https://github.com/spryker/business-on-behalf-gui-extension) (Extension)
- [CompaniesRestApi ^1.2.0](https://github.com/spryker/companies-rest-api) (Legacy Glue)
- [CompanyBusinessUnitAddressesRestApi ^1.2.0](https://github.com/spryker/company-business-unit-addresses-rest-api) (Legacy Glue)
- [CompanyBusinessUnitSalesConnector ^1.1.0](https://github.com/spryker/company-business-unit-sales-connector) (Connector)
- [CompanyBusinessUnitsRestApi ^1.3.0](https://github.com/spryker/company-business-units-rest-api) (Legacy Glue)
- [CompanyBusinessUnitsRestApiExtension ^1.0.0](https://github.com/spryker/company-business-units-rest-api-extension) (Extension)
- [CompanyRoleGuiExtension ^1.0.0](https://github.com/spryker/company-role-gui-extension) (Extension)
- [CompanyRolesRestApi ^1.1.0](https://github.com/spryker/company-roles-rest-api) (Legacy Glue)
- [CompanySalesConnector ^1.1.0](https://github.com/spryker/company-sales-connector) (Connector)
- [CompanyUserAuthRestApi ^2.1.0](https://github.com/spryker/company-user-auth-rest-api) (Legacy Glue)
- [CompanyUserExtension ^1.2.0](https://github.com/spryker/company-user-extension) (Extension)
- [CompanyUserGuiExtension](https://github.com/spryker/company-user-gui-extension) (Extension)
- [CompanyUsersRestApi ^2.7.0](https://github.com/spryker/company-users-rest-api) (Legacy Glue)
- [CompanyUserStorageExtension ^1.0.0](https://github.com/spryker/company-user-storage-extension) (Extension)
- [OauthCompanyUserExtension ^1.1.0](https://github.com/spryker/oauth-company-user-extension) (Extension)
