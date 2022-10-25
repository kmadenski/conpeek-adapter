# OpenAPI\Client\VoiceCampaignRequestApi

All URIs are relative to http://}, except if the operation defines another base path.

| Method | HTTP request | Description |
| ------------- | ------------- | ------------- |
| [**voiceCampaignVoiceCampaignIdRequestPost()**](VoiceCampaignRequestApi.md#voiceCampaignVoiceCampaignIdRequestPost) | **POST** /voice_campaign/{voice_campaign_id}/request | Add Voice Campaign Request |


## `voiceCampaignVoiceCampaignIdRequestPost()`

```php
voiceCampaignVoiceCampaignIdRequestPost($voice_campaign_id, $body)
```

Add Voice Campaign Request

### Example

```php
<?php
require_once(__DIR__ . '/vendor/autoload.php');


// Configure API key authorization: ApiKeyAuth
$config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKey('Authorization', 'YOUR_API_KEY');
// Uncomment below to setup prefix (e.g. Bearer) for API key, if needed
// $config = OpenAPI\Client\Configuration::getDefaultConfiguration()->setApiKeyPrefix('Authorization', 'Bearer');


$apiInstance = new OpenAPI\Client\Api\VoiceCampaignRequestApi(
    // If you want use custom http client, pass your client which implements `GuzzleHttp\ClientInterface`.
    // This is optional, `GuzzleHttp\Client` will be used as default.
    new GuzzleHttp\Client(),
    $config
);
$voice_campaign_id = 'voice_campaign_id_example'; // string
$body = array('key' => new \stdClass); // object

try {
    $apiInstance->voiceCampaignVoiceCampaignIdRequestPost($voice_campaign_id, $body);
} catch (Exception $e) {
    echo 'Exception when calling VoiceCampaignRequestApi->voiceCampaignVoiceCampaignIdRequestPost: ', $e->getMessage(), PHP_EOL;
}
```

### Parameters

| Name | Type | Description  | Notes |
| ------------- | ------------- | ------------- | ------------- |
| **voice_campaign_id** | **string**|  | |
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
