# OpenAPI\Client\AddCRMContactApi

All URIs are relative to https://api-bssserver29.cloud.conpeek.com.

Method | HTTP request | Description
------------- | ------------- | -------------
[**crmCrmIdContactPost()**](AddCRMContactApi.md#crmCrmIdContactPost) | **POST** /crm/{crm_id}/contact | 


## `crmCrmIdContactPost()`

```php
crmCrmIdContactPost($crm_id, $body)
```



### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\AddCRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string | CRM ID
$body = array('key' => new \stdClass); // object

try {
    $apiInstance->crmCrmIdContactPost($crm_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling AddCRMContactApi->crmCrmIdContactPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **crm_id** | **string**| CRM ID |
 **body** | **object**|  | [optional]

### Return type

void (empty response body)

### Authorization

[ApiKeyAuth](../../README.md#ApiKeyAuth)

### HTTP request headers

- **Content-Type**: `application/json`
- **Accept**: `application/json`

[[Back to top]](#) [[Back to API list]](../../README.md#endpoints)
[[Back to Model list]](../../README.md#models)
[[Back to README]](../../README.md)
