# \AppApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**app_build_info_get**](AppApi.md#app_build_info_get) | **GET** /app/buildInfo | Get build info
[**app_default_save_path_get**](AppApi.md#app_default_save_path_get) | **GET** /app/defaultSavePath | Get default save path
[**app_preferences_get**](AppApi.md#app_preferences_get) | **GET** /app/preferences | Get application preferences
[**app_set_preferences_post**](AppApi.md#app_set_preferences_post) | **POST** /app/setPreferences | Set application preferences
[**app_shutdown_get**](AppApi.md#app_shutdown_get) | **GET** /app/shutdown | Shutdown application
[**app_version_get**](AppApi.md#app_version_get) | **GET** /app/version | Get application version
[**app_webapi_version_get**](AppApi.md#app_webapi_version_get) | **GET** /app/webapiVersion | Get API version



## app_build_info_get

> models::BuildInfo app_build_info_get()
Get build info

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::BuildInfo**](BuildInfo.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_default_save_path_get

> String app_default_save_path_get()
Get default save path

### Parameters

This endpoint does not need any parameter.

### Return type

**String**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_preferences_get

> models::Preferences app_preferences_get()
Get application preferences

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::Preferences**](Preferences.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_set_preferences_post

> app_set_preferences_post(json)
Set application preferences

Notes: 1. There is no need to pass all possible preferences' `token:value` pairs if you only want to change one option 2. Paths in `scan_dirs` must exist, otherwise this option will have no effect 3. String values must be quoted; integer and boolean values must never be quoted  For a list of possible preference options see [Get application preferences](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-application-preferences) 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**json** | [**models::SetPreferences**](SetPreferences.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_shutdown_get

> app_shutdown_get()
Shutdown application

### Parameters

This endpoint does not need any parameter.

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_version_get

> String app_version_get()
Get application version

### Parameters

This endpoint does not need any parameter.

### Return type

**String**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## app_webapi_version_get

> String app_webapi_version_get()
Get API version

### Parameters

This endpoint does not need any parameter.

### Return type

**String**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

