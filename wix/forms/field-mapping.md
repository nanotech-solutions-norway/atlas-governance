# Wix Field Mapping

## Purpose
Map Wix intake fields to the runtime payload contract.

| Wix field | Runtime property | Notes |
|---|---|---|
| offerId | offerId | required |
| roleId | roleId | required |
| workflowId | workflowId | required |
| deploymentMode | deploymentMode | required |
| languageMode | languageMode | required |
| sourceBoundary | sourceBoundary | optional |
| prohibitedDataClass | prohibitedDataClass | optional |
| customerEmail | customerEmail | required |
| companyName | companyName | optional |
| notes | notes | optional |

## Rule
Any mapping change must be versioned here before it is deployed in Wix or the runtime.
