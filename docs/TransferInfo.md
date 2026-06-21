# TransferInfo

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**dl_info_speed** | Option<**i64**> | Global download rate (bytes/s) | [optional]
**dl_info_data** | Option<**i64**> | Data downloaded this session (bytes) | [optional]
**up_info_speed** | Option<**i64**> | Global upload rate (bytes/s) | [optional]
**up_info_data** | Option<**i64**> | Data uploaded this session (bytes) | [optional]
**dl_rate_limit** | Option<**i64**> | Download rate limit (bytes/s) | [optional]
**up_rate_limit** | Option<**i64**> | Upload rate limit (bytes/s) | [optional]
**dht_nodes** | Option<**i64**> | DHT nodes connected to | [optional]
**connection_status** | Option<**String**> | Connection status. See possible values here below  Possible values of connection_status: | Value        | | ------------ | | connected    | | firewalled   | | disconnected |  | [optional]
**queueing** | Option<**bool**> | True if torrent queueing is enabled | [optional]
**use_alt_speed_limits** | Option<**bool**> | True if alternative speed limits are enabled | [optional]
**refresh_interval** | Option<**i64**> | Transfer list refresh interval (milliseconds) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


