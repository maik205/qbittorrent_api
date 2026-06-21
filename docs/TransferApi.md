# \TransferApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**transfer_ban_peers_post**](TransferApi.md#transfer_ban_peers_post) | **POST** /transfer/banPeers | Ban peers
[**transfer_download_limit_get**](TransferApi.md#transfer_download_limit_get) | **GET** /transfer/downloadLimit | Get global download limit
[**transfer_info_get**](TransferApi.md#transfer_info_get) | **GET** /transfer/info | Get global transfer info
[**transfer_set_download_limit_post**](TransferApi.md#transfer_set_download_limit_post) | **POST** /transfer/setDownloadLimit | Set global download limit
[**transfer_set_upload_limit_post**](TransferApi.md#transfer_set_upload_limit_post) | **POST** /transfer/setUploadLimit | Set global upload limit
[**transfer_speed_limits_mode_get**](TransferApi.md#transfer_speed_limits_mode_get) | **GET** /transfer/speedLimitsMode | Get alternative speed limits state
[**transfer_toggle_speed_limits_mode_get**](TransferApi.md#transfer_toggle_speed_limits_mode_get) | **GET** /transfer/toggleSpeedLimitsMode | Toggle alternative speed limits
[**transfer_upload_limit_get**](TransferApi.md#transfer_upload_limit_get) | **GET** /transfer/uploadLimit | Get global upload limit



## transfer_ban_peers_post

> transfer_ban_peers_post(peers)
Ban peers

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**peers** | Option<[**Vec<String>**](String.md)> | The peer to ban, or multiple peers separated by a pipe `|`. Each peer is a colon-separated `host:port` |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_download_limit_get

> i64 transfer_download_limit_get()
Get global download limit

### Parameters

This endpoint does not need any parameter.

### Return type

**i64**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_info_get

> models::TransferInfo transfer_info_get()
Get global transfer info

This method returns info you usually see in qBt status bar.

### Parameters

This endpoint does not need any parameter.

### Return type

[**models::TransferInfo**](TransferInfo.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_set_download_limit_post

> transfer_set_download_limit_post(limit)
Set global download limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**limit** | Option<**i64**> | The global download speed limit to set in bytes/second |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_set_upload_limit_post

> transfer_set_upload_limit_post(limit)
Set global upload limit

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**limit** | Option<**i64**> | The global download speed limit to set in bytes/second |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_speed_limits_mode_get

> i32 transfer_speed_limits_mode_get()
Get alternative speed limits state

### Parameters

This endpoint does not need any parameter.

### Return type

**i32**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## transfer_toggle_speed_limits_mode_get

> transfer_toggle_speed_limits_mode_get()
Toggle alternative speed limits

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


## transfer_upload_limit_get

> i64 transfer_upload_limit_get()
Get global upload limit

### Parameters

This endpoint does not need any parameter.

### Return type

**i64**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

