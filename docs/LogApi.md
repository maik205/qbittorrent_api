# \LogApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**log_main_post**](LogApi.md#log_main_post) | **POST** /log/main | Get log
[**log_peers_post**](LogApi.md#log_peers_post) | **POST** /log/peers | Get peer log



## log_main_post

> Vec<models::MainLog> log_main_post(normal, info, warning, critical, last_known_id)
Get log

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**normal** | **bool** | Include normal messages (default: `true`) | [required] |[default to true]
**info** | **bool** | Include info messages (default: `true`) | [required] |[default to true]
**warning** | **bool** | Include warning messages (default: `true`) | [required] |[default to true]
**critical** | **bool** | Include critical messages (default: `true`) | [required] |[default to true]
**last_known_id** | **i64** | Exclude messages with \\\"message id\\\" <= `last_known_id` (default: `-1`) | [required] |[default to -1]

### Return type

[**Vec<models::MainLog>**](MainLog.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## log_peers_post

> Vec<models::PeersLog> log_peers_post(last_known_id)
Get peer log

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**last_known_id** | **i64** | Exclude messages with \\\"message id\\\" <= `last_known_id` (default: `-1`) | [required] |[default to -1]

### Return type

[**Vec<models::PeersLog>**](PeersLog.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

