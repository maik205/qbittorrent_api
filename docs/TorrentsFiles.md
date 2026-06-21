# TorrentsFiles

## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**index** | Option<**i64**> | File index | [optional]
**name** | Option<**String**> | File name (including relative path) | [optional]
**size** | Option<**i64**> | File size (bytes) | [optional]
**progress** | Option<**f32**> | File progress (percentage/100) | [optional]
**priority** | Option<**Priority**> | File priority. See possible values here below  | Value | Description      | | ----- | ---------------- | | 0     | Do not download  | | 1     | Normal priority  | | 6     | High priority    | | 7     | Maximal priority |  (enum: 0, 1, 6, 7) | [optional]
**is_seed** | Option<**bool**> | True if file is seeding/complete | [optional]
**piece_range** | Option<**Vec<i64>**> | The first number is the starting piece index and the second number is the ending piece index (inclusive) | [optional]
**availability** | Option<**f32**> | Percentage of file pieces currently available (percentage/100) | [optional]

[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


