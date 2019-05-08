# change-intuneDeviceCategory
Change Intune Device Categories using the MS Graph PowerShell interface for Azure Intune

This project uses the MS Graph calls to directly alter the Intune Device Category of a device

change-intuneDeviceCategory.ps1 [[-intuneDeviceId] <string>] [[-DeviceCategoryID] <string>] [[-User] <string>]

The user supplied in -user should be in UPN format and authorised to make changes to Intune _and_ be authorised for MS Graph API calls.
To list valid Intune Device Categories and get their IDs, use get-intuneDeviceCategory
To list valid Intune Devices and get their ID, use get-intuneManagedDevice

To explore the graph API and check account permissions, us the Microsoft Graph Explorer website at https://developer.microsoft.com/en-us/graph/graph-explorer#
