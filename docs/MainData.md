# MainData

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**rid** | Option<**i64**> | Response ID | [optional]
**full_update** | Option<**bool**> | Whether the response contains all the data or partial data | [optional]
**torrents** | Option<[**std::collections::HashMap<String, models::TorrentInfo>**](TorrentInfo.md)> | Property: torrent hash, value: same as [torrent list](https://github.com/qbittorrent/qBittorrent/wiki/WebUI-API-(qBittorrent-5.0)#get-torrent-list) | [optional]
**torrents_removed** | Option<**Vec<String>**> | List of hashes of torrents removed since last request | [optional]
**categories** | Option<[**std::collections::HashMap<String, models::TorrentsCategory>**](TorrentsCategory.md)> | Info for categories added since last request | [optional]
**categories_removed** | Option<**Vec<String>**> | List of categories removed since last request | [optional]
**tags** | Option<**Vec<String>**> | List of tags added since last request | [optional]
**tags_removed** | Option<**Vec<String>**> | List of tags removed since last request | [optional]
**server_state** | Option<[**models::TransferInfo**](TransferInfo.md)> |  | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


