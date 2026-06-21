# \RssApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**rss_add_feed_post**](RssApi.md#rss_add_feed_post) | **POST** /rss/addFeed | Add feed
[**rss_add_folder_post**](RssApi.md#rss_add_folder_post) | **POST** /rss/addFolder | Add folder
[**rss_items_post**](RssApi.md#rss_items_post) | **POST** /rss/items | Get all items
[**rss_mark_as_read_post**](RssApi.md#rss_mark_as_read_post) | **POST** /rss/markAsRead | Mark as read
[**rss_matching_articles_post**](RssApi.md#rss_matching_articles_post) | **POST** /rss/matchingArticles | Get all articles matching a rule
[**rss_move_item_post**](RssApi.md#rss_move_item_post) | **POST** /rss/moveItem | Move item
[**rss_refresh_item_post**](RssApi.md#rss_refresh_item_post) | **POST** /rss/refreshItem | Refresh item
[**rss_remove_item_post**](RssApi.md#rss_remove_item_post) | **POST** /rss/removeItem | Remove item
[**rss_remove_rule_post**](RssApi.md#rss_remove_rule_post) | **POST** /rss/removeRule | Remove auto-downloading rule
[**rss_rename_rule_post**](RssApi.md#rss_rename_rule_post) | **POST** /rss/renameRule | Rename auto-downloading rule
[**rss_rules_get**](RssApi.md#rss_rules_get) | **GET** /rss/rules | Get all auto-downloading rules
[**rss_set_rule_post**](RssApi.md#rss_set_rule_post) | **POST** /rss/setRule | Set auto-downloading rule



## rss_add_feed_post

> rss_add_feed_post(url, path)
Add feed

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**url** | **String** | URL of RSS feed (e.g. \\\"http://thepiratebay.org/rss//top100/200\\\") | [required] |
**path** | Option<**String**> | Full path of added folder (e.g. \\\"The Pirate Bay\\\\Top100\\\\Video\\\") |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_add_folder_post

> rss_add_folder_post(path)
Add folder

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**path** | **String** | Full path of added folder (e.g. \\\"The Pirate Bay\\\\Top100\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_items_post

> serde_json::Value rss_items_post(with_data)
Get all items

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**with_data** | Option<**bool**> | True if you need current feed articles |  |

### Return type

[**serde_json::Value**](serde_json::Value.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_mark_as_read_post

> rss_mark_as_read_post(item_path, article_id)
Mark as read

If `articleId` is provided only the article is marked as read otherwise the whole feed is going to be marked as read.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**item_path** | **String** | Current full path of item (e.g. \\\"The Pirate Bay\\\\Top100\\\") | [required] |
**article_id** | Option<**String**> | ID of article |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_matching_articles_post

> std::collections::HashMap<String, Vec<String>> rss_matching_articles_post(rule_name)
Get all articles matching a rule

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_name** | **String** | Rule name (e.g. \\\"Punisher\\\") | [required] |

### Return type

[**std::collections::HashMap<String, Vec<String>>**](Vec.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_move_item_post

> rss_move_item_post(item_path, dest_path)
Move item

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**item_path** | **String** | Current full path of item (e.g. \\\"The Pirate Bay\\\\Top100\\\") | [required] |
**dest_path** | **String** | New full path of item (e.g. \\\"The Pirate Bay\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_refresh_item_post

> rss_refresh_item_post(item_path)
Refresh item

Refreshes folder or feed.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**item_path** | **String** | Current full path of item (e.g. \\\"The Pirate Bay\\\\Top100\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_remove_item_post

> rss_remove_item_post(path)
Remove item

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**path** | **String** | Full path of added folder (e.g. \\\"The Pirate Bay\\\\Top100\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_remove_rule_post

> rss_remove_rule_post(rule_name)
Remove auto-downloading rule

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_name** | **String** | Rule name (e.g. \\\"Punisher\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_rename_rule_post

> rss_rename_rule_post(rule_name, new_rule_name)
Rename auto-downloading rule

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_name** | **String** | Rule name (e.g. \\\"Punisher\\\") | [required] |
**new_rule_name** | **String** | New rule name (e.g. \\\"The Punisher\\\") | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_rules_get

> std::collections::HashMap<String, models::RssRuleDef> rss_rules_get()
Get all auto-downloading rules

### Parameters

This endpoint does not need any parameter.

### Return type

[**std::collections::HashMap<String, models::RssRuleDef>**](RssRuleDef.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## rss_set_rule_post

> rss_set_rule_post(rule_name, rule_def)
Set auto-downloading rule

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**rule_name** | **String** | Rule name (e.g. \\\"Punisher\\\") | [required] |
**rule_def** | [**models::RssRuleDef**](RssRuleDef.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

