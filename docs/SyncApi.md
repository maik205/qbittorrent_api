# \SyncApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sync_maindata_post**](SyncApi.md#sync_maindata_post) | **POST** /sync/maindata | Get main data
[**sync_torrent_peers_post**](SyncApi.md#sync_torrent_peers_post) | **POST** /sync/torrentPeers | Get torrent peers data



## sync_maindata_post

> models::MainData sync_maindata_post(rid)
Get main data

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rid** | Option<**i64**> | Response ID. If not provided, `rid=0` will be assumed. If the given `rid` is different from the one of last server reply, `full_update` will be `true` (see the server reply details for more info) |  |

### Return type

[**models::MainData**](MainData.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## sync_torrent_peers_post

> serde_json::Value sync_torrent_peers_post(hash, rid)
Get torrent peers data

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | Torrent hash | [required] |
**rid** | Option<**i64**> | Response ID. If not provided, `rid=0` will be assumed. If the given `rid` is different from the one of last server reply, `full_update` will be `true` (see the server reply details for more info) |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

