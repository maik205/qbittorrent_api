# TorrentsTrackers

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**url** | Option<**String**> | Tracker url | [optional]
**status** | Option<**Status**> | Tracker status. See the table below for possible values  | Value | Description                                                                        | | ----- | ---------------------------------------------------------------------------------- | | 0     | Tracker is disabled (used for DHT, PeX, and LSD)                                   | | 1     | Tracker has not been contacted yet                                                 | | 2     | Tracker has been contacted and is working                                          | | 3     | Tracker is updating                                                                | | 4     | Tracker has been contacted, but it is not working (or doesn't send proper replies) |  (enum: 0, 1, 2, 3, 4) | [optional]
**tier** | Option<**i64**> | Tracker priority tier. Lower tier trackers are tried before higher tiers. Tier numbers are valid when `>= 0`, `< 0` is used as placeholder when `tier` does not exist for special entries (such as DHT). | [optional]
**num_peers** | Option<**i64**> | Number of peers for current torrent, as reported by the tracker | [optional]
**num_seeds** | Option<**i64**> | Number of seeds for current torrent, asreported by the tracker | [optional]
**num_leeches** | Option<**i64**> | Number of leeches for current torrent, as reported by the tracker | [optional]
**num_downloaded** | Option<**i64**> | Number of completed downlods for current torrent, as reported by the tracker | [optional]
**msg** | Option<**String**> | Tracker message (there is no way of knowing what this message is - it's up to tracker admins) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


