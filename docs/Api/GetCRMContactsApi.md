# OpenAPI\Client\GetCRMContactsApi

All URIs are relative to https://api-bssserver29.cloud.conpeek.com.

Method | HTTP request | Description
------------- | ------------- | -------------
[**crmCrmIdContactGet()**](GetCRMContactsApi.md#crmCrmIdContactGet) | **GET** /crm/{crm_id}/contact | 


## `crmCrmIdContactGet()`

```php
crmCrmIdContactGet($crm_id)
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\GetCRMContactsApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string | CRM ID

try {
    $apiInstance->crmCrmIdContactGet($crm_id);
} catch (Exception $e) {
    echo 'Exception when calling GetCRMContactsApi->crmCrmIdContactGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **crm_id** | **string**| CRM ID |

### Return type

void (empty response body)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
