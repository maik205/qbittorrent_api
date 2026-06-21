# \TorrentsApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**torrent_webseeds_post**](TorrentsApi.md#torrent_webseeds_post) | **POST** /torrents/webseeds | Get torrent web seeds
[**torrents_add_peers_post**](TorrentsApi.md#torrents_add_peers_post) | **POST** /torrents/addPeers | Add peers
[**torrents_add_post**](TorrentsApi.md#torrents_add_post) | **POST** /torrents/add | Add new torrent
[**torrents_add_tags_post**](TorrentsApi.md#torrents_add_tags_post) | **POST** /torrents/addTags | Add torrent tags
[**torrents_add_trackers_post**](TorrentsApi.md#torrents_add_trackers_post) | **POST** /torrents/addTrackers | Add trackers to torrent
[**torrents_bottom_prio_post**](TorrentsApi.md#torrents_bottom_prio_post) | **POST** /torrents/bottomPrio | Minimal torrent priority
[**torrents_categories_get**](TorrentsApi.md#torrents_categories_get) | **GET** /torrents/categories | Get all categories
[**torrents_create_category_post**](TorrentsApi.md#torrents_create_category_post) | **POST** /torrents/createCategory | Add new category
[**torrents_create_tags_post**](TorrentsApi.md#torrents_create_tags_post) | **POST** /torrents/createTags | Create tags
[**torrents_decrease_prio_post**](TorrentsApi.md#torrents_decrease_prio_post) | **POST** /torrents/decreasePrio | Decrease torrent priority
[**torrents_delete_post**](TorrentsApi.md#torrents_delete_post) | **POST** /torrents/delete | Delete torrents
[**torrents_delete_tags_post**](TorrentsApi.md#torrents_delete_tags_post) | **POST** /torrents/deleteTags | Delete tags
[**torrents_download_limit_post**](TorrentsApi.md#torrents_download_limit_post) | **POST** /torrents/downloadLimit | Get torrent download limit
[**torrents_edit_category_post**](TorrentsApi.md#torrents_edit_category_post) | **POST** /torrents/editCategory | Edit category
[**torrents_edit_tracker_post**](TorrentsApi.md#torrents_edit_tracker_post) | **POST** /torrents/editTracker | Edit trackers
[**torrents_file_prio_post**](TorrentsApi.md#torrents_file_prio_post) | **POST** /torrents/filePrio | Set file priority
[**torrents_files_post**](TorrentsApi.md#torrents_files_post) | **POST** /torrents/files | Get torrent contents
[**torrents_increase_prio_post**](TorrentsApi.md#torrents_increase_prio_post) | **POST** /torrents/increasePrio | Increase torrent priority
[**torrents_info_post**](TorrentsApi.md#torrents_info_post) | **POST** /torrents/info | Get torrent list
[**torrents_pause_post**](TorrentsApi.md#torrents_pause_post) | **POST** /torrents/pause | Pause torrents
[**torrents_piece_hashes_post**](TorrentsApi.md#torrents_piece_hashes_post) | **POST** /torrents/pieceHashes | Get torrent pieces' hashes
[**torrents_piece_states_post**](TorrentsApi.md#torrents_piece_states_post) | **POST** /torrents/pieceStates | Get torrent pieces' states
[**torrents_properties_post**](TorrentsApi.md#torrents_properties_post) | **POST** /torrents/properties | Get torrent generic properties
[**torrents_reannounce_post**](TorrentsApi.md#torrents_reannounce_post) | **POST** /torrents/reannounce | Reannounce torrents
[**torrents_recheck_post**](TorrentsApi.md#torrents_recheck_post) | **POST** /torrents/recheck | Recheck torrents
[**torrents_remove_categories_post**](TorrentsApi.md#torrents_remove_categories_post) | **POST** /torrents/removeCategories | Remove categories
[**torrents_remove_tags_post**](TorrentsApi.md#torrents_remove_tags_post) | **POST** /torrents/removeTags | Remove torrent tags
[**torrents_remove_trackers_post**](TorrentsApi.md#torrents_remove_trackers_post) | **POST** /torrents/removeTrackers | Remove trackers
[**torrents_rename_file_post**](TorrentsApi.md#torrents_rename_file_post) | **POST** /torrents/renameFile | Rename file
[**torrents_rename_folder_post**](TorrentsApi.md#torrents_rename_folder_post) | **POST** /torrents/renameFolder | Rename folder
[**torrents_rename_post**](TorrentsApi.md#torrents_rename_post) | **POST** /torrents/rename | Set torrent name
[**torrents_resume_post**](TorrentsApi.md#torrents_resume_post) | **POST** /torrents/resume | Resume torrents
[**torrents_set_auto_management_post**](TorrentsApi.md#torrents_set_auto_management_post) | **POST** /torrents/setAutoManagement | Set automatic torrent management
[**torrents_set_category_post**](TorrentsApi.md#torrents_set_category_post) | **POST** /torrents/setCategory | Set torrent category
[**torrents_set_download_limit_post**](TorrentsApi.md#torrents_set_download_limit_post) | **POST** /torrents/setDownloadLimit | Set torrent download limit
[**torrents_set_force_start_post**](TorrentsApi.md#torrents_set_force_start_post) | **POST** /torrents/setForceStart | Set force start
[**torrents_set_location_post**](TorrentsApi.md#torrents_set_location_post) | **POST** /torrents/setLocation | Set torrent location
[**torrents_set_share_limits_post**](TorrentsApi.md#torrents_set_share_limits_post) | **POST** /torrents/setShareLimits | Set torrent share limit
[**torrents_set_super_seeding_post**](TorrentsApi.md#torrents_set_super_seeding_post) | **POST** /torrents/setSuperSeeding | Set super seeding
[**torrents_set_upload_limit_post**](TorrentsApi.md#torrents_set_upload_limit_post) | **POST** /torrents/setUploadLimit | Set torrent upload limit
[**torrents_tags_get**](TorrentsApi.md#torrents_tags_get) | **GET** /torrents/tags | Get all tags
[**torrents_toggle_first_last_piece_prio_post**](TorrentsApi.md#torrents_toggle_first_last_piece_prio_post) | **POST** /torrents/toggleFirstLastPiecePrio | Set first/last piece priority
[**torrents_toggle_sequential_download_post**](TorrentsApi.md#torrents_toggle_sequential_download_post) | **POST** /torrents/toggleSequentialDownload | Toggle sequential download
[**torrents_top_prio_post**](TorrentsApi.md#torrents_top_prio_post) | **POST** /torrents/topPrio | Maximal torrent priority
[**torrents_trackers_post**](TorrentsApi.md#torrents_trackers_post) | **POST** /torrents/trackers | Get torrent trackers
[**torrents_upload_limit_post**](TorrentsApi.md#torrents_upload_limit_post) | **POST** /torrents/uploadLimit | Get torrent upload limit



## torrent_webseeds_post

> Vec<models::TorrentsWebseeds> torrent_webseeds_post(hash)
Get torrent web seeds

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the generic properties of | [required] |

### Return type

[**Vec<models::TorrentsWebseeds>**](TorrentsWebseeds.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_add_peers_post

> torrents_add_peers_post(hashes, peers)
Add peers

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) | The hash of the torrent, or multiple hashes separated by a pipe `|` | [required] |
**peers** | [**Vec<String>**](String.md) | The peer to add, or multiple peers separated by a pipe `|`. Each peer is a colon-separated `host:port` | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_add_post

> torrents_add_post(urls, savepath, category, tags, skip_checking, paused, root_folder, rename, up_limit, dl_limit, ratio_limit, seeding_time_limit, auto_tmm, sequential_download, first_last_piece_prio, torrents)
Add new torrent

This method can add torrents from server local file or from URLs. `http://`, `https://`, `magnet:` and `bc://bt/` links are supported.

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**urls** | Option<**String**> | URLs separated with newlines |  |
**savepath** | Option<**String**> | Download folder |  |
**category** | Option<**String**> | Category for the torrent |  |
**tags** | Option<[**Vec<String>**](String.md)> | Tags for the torrent, split by ',' |  |
**skip_checking** | Option<**String**> | Skip hash checking. Possible values are `true`, `false` (default) |  |[default to false]
**paused** | Option<**String**> | Add torrents in the paused state. Possible values are `true`, `false` (default) |  |[default to false]
**root_folder** | Option<**String**> | Create the root folder. Possible values are `true`, `false`, unset (default) |  |[default to unset]
**rename** | Option<**String**> | Rename torrent |  |
**up_limit** | Option<**i64**> | Set torrent upload speed limit. Unit in bytes/second |  |
**dl_limit** | Option<**i64**> | Set torrent download speed limit. Unit in bytes/second |  |
**ratio_limit** | Option<**f32**> | Set torrent share ratio limit |  |
**seeding_time_limit** | Option<**i64**> | Set torrent seeding time limit. Unit in seconds |  |
**auto_tmm** | Option<**bool**> | Whether Automatic Torrent Management should be used |  |
**sequential_download** | Option<**String**> | Enable sequential download. Possible values are `true`, `false` (default) |  |[default to false]
**first_last_piece_prio** | Option<**String**> | Prioritize download first last piece. Possible values are `true`, `false` (default) |  |[default to false]
**torrents** | Option<[**Vec<std::path::PathBuf>**](Std__path__PathBuf.md)> | Raw data of torrent file. `torrents` can be presented multiple times. |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: multipart/form-data
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_add_tags_post

> torrents_add_tags_post(hashes, tags)
Add torrent tags

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**tags** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_add_trackers_post

> torrents_add_trackers_post(hash, urls)
Add trackers to torrent

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** |  | [required] |
**urls** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_bottom_prio_post

> torrents_bottom_prio_post(hashes)
Minimal torrent priority

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_categories_get

> std::collections::HashMap<String, models::TorrentsCategory> torrents_categories_get()
Get all categories

### Parameters

This endpoint does not need any parameter.

### Return type

[**std::collections::HashMap<String, models::TorrentsCategory>**](TorrentsCategory.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_create_category_post

> torrents_create_category_post(category, save_path)
Add new category

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**category** | **String** |  | [required] |
**save_path** | Option<**String**> |  |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_create_tags_post

> torrents_create_tags_post(tags)
Create tags

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tags** | [**Vec<String>**](String.md) | `tags` is a list of tags you want to create. Can contain multiple tags separated by `,`. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_decrease_prio_post

> torrents_decrease_prio_post(hashes)
Decrease torrent priority

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_delete_post

> torrents_delete_post(hashes, delete_files)
Delete torrents

Requires knowing the torrent hashes. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**delete_files** | **bool** | If set to `true`, the downloaded data will also be deleted, otherwise has no effect. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_delete_tags_post

> torrents_delete_tags_post(tags)
Delete tags

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**tags** | [**Vec<String>**](String.md) | `tags` is a list of tags you want to create. Can contain multiple tags separated by `,`. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_download_limit_post

> std::collections::HashMap<String, i64> torrents_download_limit_post(hashes)
Get torrent download limit

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

**std::collections::HashMap<String, i64>**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_edit_category_post

> torrents_edit_category_post(category, save_path)
Edit category

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**category** | **String** |  | [required] |
**save_path** | Option<**String**> |  |  |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_edit_tracker_post

> torrents_edit_tracker_post(hash, orig_url, new_url)
Edit trackers

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent | [required] |
**orig_url** | **String** | The tracker URL you want to edit | [required] |
**new_url** | **String** | The new URL to replace the `origUrl` | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_file_prio_post

> torrents_file_prio_post(hash, id, priority)
Set file priority

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent | [required] |
**id** | [**Vec<i64>**](I64.md) | File ids, separated by `|` | [required] |
**priority** | **i32** | File priority to set (consult [torrent contents API](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-contents) for possible values) | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_files_post

> Vec<models::TorrentsFiles> torrents_files_post(hash, indexes)
Get torrent contents

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the contents of | [required] |
**indexes** | Option<[**Vec<String>**](String.md)> | The indexes of the files you want to retrieve. `indexes` can contain multiple values separated by `|`. |  |

### Return type

[**Vec<models::TorrentsFiles>**](TorrentsFiles.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_increase_prio_post

> torrents_increase_prio_post(hashes)
Increase torrent priority

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_info_post

> Vec<models::TorrentInfo> torrents_info_post(filter, category, tag, sort, reverse, limit, offset, hashes)
Get torrent list

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**filter** | Option<**String**> | Filter torrent list by state. Allowed state filters: `all`, `downloading`, `seeding`, `completed`, `paused`, `active`, `inactive`, `resumed`, `stalled`, `stalled_uploading`, `stalled_downloading`, `errored` |  |
**category** | Option<**String**> | Get torrents with the given category (empty string means \\\"without category\\\"; no \\\"category\\\" parameter means \\\"any category\\\" <- broken until [#11748](https://github.com/qbittorrent/qBittorrent/issues/11748) is resolved). Remember to URL-encode the category name. For example, `My category` becomes `My%20category` |  |
**tag** | Option<**String**> | Get torrents with the given tag (empty string means \\\"without tag\\\"; no \\\"tag\\\" parameter means \\\"any tag\\\". Remember to URL-encode the category name. For example, `My tag` becomes `My%20tag` |  |
**sort** | Option<**String**> | Sort torrents by given key. They can be sorted using any field of the response's JSON array (which are documented below) as the sort key. |  |
**reverse** | Option<**bool**> | Enable reverse sorting. Defaults to `false` |  |[default to false]
**limit** | Option<**i64**> | Limit the number of torrents returned |  |
**offset** | Option<**i64**> | Set offset (if less than 0, offset from end) |  |
**hashes** | Option<[**Vec<String>**](String.md)> | Filter by hashes. Can contain multiple hashes separated by `|` |  |

### Return type

[**Vec<models::TorrentInfo>**](TorrentInfo.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_pause_post

> torrents_pause_post(hashes)
Pause torrents

Requires knowing the torrent hashes. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_piece_hashes_post

> Vec<String> torrents_piece_hashes_post(hash)
Get torrent pieces' hashes

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the generic properties of | [required] |

### Return type

**Vec<String>**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_piece_states_post

> Vec<i32> torrents_piece_states_post(hash)
Get torrent pieces' states

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the generic properties of | [required] |

### Return type

**Vec<i32>**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_properties_post

> models::TorrentsProperties torrents_properties_post(hash)
Get torrent generic properties

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the generic properties of | [required] |

### Return type

[**models::TorrentsProperties**](TorrentsProperties.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_reannounce_post

> torrents_reannounce_post(hashes)
Reannounce torrents

Requires knowing the torrent hashes. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_recheck_post

> torrents_recheck_post(hashes)
Recheck torrents

Requires knowing the torrent hashes. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_remove_categories_post

> torrents_remove_categories_post(categories)
Remove categories

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**categories** | **String** | `categories` can contain multiple cateogies separated by `\\\\n` (%0A urlencoded) | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_remove_tags_post

> torrents_remove_tags_post(hashes, tags)
Remove torrent tags

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**tags** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_remove_trackers_post

> torrents_remove_trackers_post(hash, urls)
Remove trackers

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent | [required] |
**urls** | [**Vec<String>**](String.md) | URLs to remove, separated by `|` | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_rename_file_post

> torrents_rename_file_post(hash, old_path, new_path)
Rename file

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent | [required] |
**old_path** | **String** | The old path of the torrent | [required] |
**new_path** | **String** | The new path to use for the file | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_rename_folder_post

> torrents_rename_folder_post(hash, old_path, new_path)
Rename folder

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent | [required] |
**old_path** | **String** | The old path of the torrent | [required] |
**new_path** | **String** | The new path to use for the file | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_rename_post

> torrents_rename_post(hash, name)
Set torrent name

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** |  | [required] |
**name** | **String** |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_resume_post

> torrents_resume_post(hashes)
Resume torrents

Requires knowing the torrent hashes. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_auto_management_post

> torrents_set_auto_management_post(hashes, enable)
Set automatic torrent management

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**enable** | **bool** | `enable` is a boolean, affects the torrents listed in `hashes`, default is `false` | [required] |[default to false]

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_category_post

> torrents_set_category_post(hashes, category)
Set torrent category

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**category** | **String** | `category` is the torrent category you want to set. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_download_limit_post

> torrents_set_download_limit_post(hashes, limit)
Set torrent download limit

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**limit** | **i64** |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_force_start_post

> torrents_set_force_start_post(hashes, value)
Set force start

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**value** | **bool** | `value` is a boolean, affects the torrents listed in `hashes`, default is `false` | [required] |[default to false]

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_location_post

> torrents_set_location_post(hashes, location)
Set torrent location

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**location** | **String** | `location` is the location to download the torrent to. If the location doesn't exist, the torrent's location is unchanged. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_share_limits_post

> torrents_set_share_limits_post(hashes, ratio_limit, seeding_time_limit)
Set torrent share limit

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**ratio_limit** | **f32** | `ratioLimit` is the max ratio the torrent should be seeded until. `-2` means the global limit should be used, -1 means no limit. | [required] |
**seeding_time_limit** | **f32** | `seedingTimeLimit` is the max amount of time the torrent should be seeded. `-2` means the global limit should be used, `-1` means no limit. | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_super_seeding_post

> torrents_set_super_seeding_post(hashes, value)
Set super seeding

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**value** | **bool** | `value` is a boolean, affects the torrents listed in `hashes`, default is `false` | [required] |[default to false]

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_set_upload_limit_post

> torrents_set_upload_limit_post(hashes, limit)
Set torrent upload limit

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |
**limit** | **i64** |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_tags_get

> Vec<String> torrents_tags_get()
Get all tags

### Parameters

This endpoint does not need any parameter.

### Return type

**Vec<String>**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: Not defined
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_toggle_first_last_piece_prio_post

> torrents_toggle_first_last_piece_prio_post(hashes)
Set first/last piece priority

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_toggle_sequential_download_post

> torrents_toggle_sequential_download_post(hashes)
Toggle sequential download

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_top_prio_post

> torrents_top_prio_post(hashes)
Maximal torrent priority

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

 (empty response body)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: Not defined

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_trackers_post

> Vec<models::TorrentsTrackers> torrents_trackers_post(hash)
Get torrent trackers

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hash** | **String** | The hash of the torrent you want to get the generic properties of | [required] |

### Return type

[**Vec<models::TorrentsTrackers>**](TorrentsTrackers.md)

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## torrents_upload_limit_post

> std::collections::HashMap<String, i64> torrents_upload_limit_post(hashes)
Get torrent upload limit

Requires knowing the torrent hash. You can get it from [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list).

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**hashes** | [**Vec<String>**](String.md) |  | [required] |

### Return type

**std::collections::HashMap<String, i64>**

### Authorization

[sid](../README.md#sid)

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: application/json

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

