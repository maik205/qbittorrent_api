# \SearchApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**search_delete_post**](SearchApi.md#search_delete_post) | **POST** /search/delete | Delete search
[**search_enable_plugin_post**](SearchApi.md#search_enable_plugin_post) | **POST** /search/enablePlugin | Enable search plugin
[**search_install_plugin_post**](SearchApi.md#search_install_plugin_post) | **POST** /search/installPlugin | Install search plugin
[**search_plugins_get**](SearchApi.md#search_plugins_get) | **GET** /search/plugins | Get search plugins
[**search_results_post**](SearchApi.md#search_results_post) | **POST** /search/results | Get search results
[**search_start_post**](SearchApi.md#search_start_post) | **POST** /search/start | Start search
[**search_status_post**](SearchApi.md#search_status_post) | **POST** /search/status | Get search status
[**search_stop_post**](SearchApi.md#search_stop_post) | **POST** /search/stop | Stop search
[**search_uninstall_plugin_post**](SearchApi.md#search_uninstall_plugin_post) | **POST** /search/uninstallPlugin | Uninstall search plugin
[**search_update_plugins_post**](SearchApi.md#search_update_plugins_post) | **POST** /search/updatePlugins | Update search plugins



## search_delete_post

> search_delete_post(id)
Delete search

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **f64** | ID of the search job | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_enable_plugin_post

> search_enable_plugin_post(names, enable)
Enable search plugin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**names** | [**Vec<String>**](String.md) | Name of the plugin to enable/disable (e.g. \\\"legittorrents\\\"). Supports multiple names separated by `|` | [required] |
**enable** | **bool** | Whether the plugins should be enabled | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_install_plugin_post

> search_install_plugin_post(sources)
Install search plugin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**sources** | [**Vec<String>**](String.md) | Url or file path of the plugin to install (e.g. \\\"https://raw.githubusercontent.com/qbittorrent/search-plugins/master/nova3/engines/legittorrents.py\\\"). Supports multiple sources separated by `|` | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_plugins_get

> Vec<models::SearchPlugin> search_plugins_get()
Get search plugins

### Parameters

This endpoint does not need any parameter.

### Return type

[**Vec<models::SearchPlugin>**](SearchPlugin.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_results_post

> models::SearchResults search_results_post(id, limit, offset)
Get search results

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | **f64** | ID of the search job | [required] |
**limit** | Option<**f64**> | max number of results to return. 0 or negative means no limit |  |
**offset** | Option<**f64**> | result to start at. A negative number means count backwards (e.g. -2 returns the 2 most recent results) |  |

### Return type

[**models::SearchResults**](SearchResults.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_start_post

> models::SearchJob search_start_post(pattern, plugins, category)
Start search

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**pattern** | **String** | Pattern to search for (e.g. \\\"Ubuntu 18.04\\\") | [required] |
**plugins** | [**Vec<String>**](String.md) | Plugins to use for searching (e.g. \\\"legittorrents\\\"). Supports multiple plugins separated by `|`. Also supports `all` and `enabled` | [required] |
**category** | [**Vec<String>**](String.md) | Categories to limit your search to (e.g. \\\"legittorrents\\\"). Available categories depend on the specified `plugins`. Also supports `all` | [required] |

### Return type

[**models::SearchJob**](SearchJob.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_status_post

> Vec<models::SearchJobStatus> search_status_post(id)
Get search status

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | Option<**f64**> | ID of the search job. If not specified, all search jobs are returned |  |

### Return type

[**Vec<models::SearchJobStatus>**](SearchJobStatus.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_stop_post

> search_stop_post(id)
Stop search

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**id** | Option<**f64**> | ID of the search job |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_uninstall_plugin_post

> search_uninstall_plugin_post(names)
Uninstall search plugin

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**names** | [**Vec<String>**](String.md) | Name of the plugin to uninstall (e.g. \\\"legittorrents\\\"). Supports multiple names separated by `|` | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## search_update_plugins_post

> search_update_plugins_post()
Update search plugins

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

