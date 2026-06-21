# RssRuleDef

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**enabled** | Option<**bool**> | Whether the rule is enabled | [optional]
**must_contain** | Option<**String**> | The substring that the torrent name must contain | [optional]
**must_not_contain** | Option<**String**> | The substring that the torrent name must not contain | [optional]
**use_regex** | Option<**bool**> | Enable regex mode in \"mustContain\" and \"mustNotContain\" | [optional]
**episode_filter** | Option<**String**> | Episode filter definition | [optional]
**smart_filter** | Option<**bool**> | Enable smart episode filter | [optional]
**previously_matched_episodes** | Option<**Vec<i64>**> | The list of episode IDs already matched by smart filter | [optional]
**affected_feeds** | Option<**Vec<String>**> | The feed URLs the rule applied to | [optional]
**ignore_days** | Option<**f64**> | Ignore sunsequent rule matches | [optional]
**last_match** | Option<**String**> | The rule last match time | [optional]
**add_paused** | Option<**bool**> | Add matched torrent in paused mode | [optional]
**assigned_category** | Option<**String**> | Assign category to the torrent | [optional]
**save_path** | Option<**String**> | Save torrent to the given directory | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


