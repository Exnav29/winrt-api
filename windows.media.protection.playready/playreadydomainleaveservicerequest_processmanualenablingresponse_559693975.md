---
-api-type: winrt method
---
 S_OK—The enabling response was processed and there are no more service requests necessary. A following call to [NextServiceRequest](playreadydomainleaveservicerequest_nextservicerequest.md) will return a **NULL** pointer.
 MSPR_E_CONTENT_ENABLING_ACTION_REQUIRED—A new service request was generated when processing the current service request. A call to **NextServiceRequest** should be made.
 DRM_E_SERVER_SERVICE_SPECIFIC—A PlayReady license or domain server failed.
 MSPR_E_SDK_UPDATE_REQUIRED—The individualization service requires a client SDK update before a new individualization operation can complete. Refreshing the PlayReady SDK is required.