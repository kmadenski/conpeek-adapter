# OpenAPI\Client\CRMContactApi

All URIs are relative to http://}, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**crmCrmIdContactContactIdDelete()**](CRMContactApi.md#crmCrmIdContactContactIdDelete) | **DELETE** /crm/{crm_id}/contact/{contact_id} | DELETE CRM contact |
| [**crmCrmIdContactContactIdGet()**](CRMContactApi.md#crmCrmIdContactContactIdGet) | **GET** /crm/{crm_id}/contact/{contact_id} | Get CRM contact |
| [**crmCrmIdContactContactIdPut()**](CRMContactApi.md#crmCrmIdContactContactIdPut) | **PUT** /crm/{crm_id}/contact/{contact_id} | Update CRM contact |
| [**crmCrmIdContactGet()**](CRMContactApi.md#crmCrmIdContactGet) | **GET** /crm/{crm_id}/contact | Get CRM contacts |
| [**crmCrmIdContactPost()**](CRMContactApi.md#crmCrmIdContactPost) | **POST** /crm/{crm_id}/contact | Add CRM contact |


## `crmCrmIdContactContactIdDelete()`

```php
crmCrmIdContactContactIdDelete($crm_id, $contact_id)
```

DELETE CRM contact

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\CRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string
$contact_id = 'contact_id_example'; // string

try {
    $apiInstance->crmCrmIdContactContactIdDelete($crm_id, $contact_id);
} catch (Exception $e) {
    echo 'Exception when calling CRMContactApi->crmCrmIdContactContactIdDelete: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **crm_id** | **string**|  | |
| **contact_id** | **string**|  | |

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

## `crmCrmIdContactContactIdGet()`

```php
crmCrmIdContactContactIdGet($crm_id, $contact_id)
```

Get CRM contact

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\CRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string
$contact_id = 'contact_id_example'; // string

try {
    $apiInstance->crmCrmIdContactContactIdGet($crm_id, $contact_id);
} catch (Exception $e) {
    echo 'Exception when calling CRMContactApi->crmCrmIdContactContactIdGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **crm_id** | **string**|  | |
| **contact_id** | **string**|  | |

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

## `crmCrmIdContactContactIdPut()`

```php
crmCrmIdContactContactIdPut($crm_id, $contact_id, $body)
```

Update CRM contact

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\CRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string
$contact_id = 'contact_id_example'; // string
$body = array('key' => new \stdClass); // object

try {
    $apiInstance->crmCrmIdContactContactIdPut($crm_id, $contact_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling CRMContactApi->crmCrmIdContactContactIdPut: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **crm_id** | **string**|  | |
| **contact_id** | **string**|  | |
| **body** | **object**|  | [optional] |

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

## `crmCrmIdContactGet()`

```php
crmCrmIdContactGet($crm_id)
```

Get CRM contacts

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\CRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string

try {
    $apiInstance->crmCrmIdContactGet($crm_id);
} catch (Exception $e) {
    echo 'Exception when calling CRMContactApi->crmCrmIdContactGet: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **crm_id** | **string**|  | |

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

## `crmCrmIdContactPost()`

```php
crmCrmIdContactPost($crm_id, $body)
```

Add CRM contact

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\CRMContactApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$crm_id = 'crm_id_example'; // string
$body = array('key' => new \stdClass); // object

try {
    $apiInstance->crmCrmIdContactPost($crm_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling CRMContactApi->crmCrmIdContactPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **crm_id** | **string**|  | |
| **body** | **object**|  | [optional] |

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
