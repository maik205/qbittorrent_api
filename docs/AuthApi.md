# \AuthApi

All URIs are relative to *http://localhost:8080/api/v2*

Method | HTTP request | Description
------------- | ------------- | -------------
[**auth_login_post**](AuthApi.md#auth_login_post) | **POST** /auth/login | Login
[**auth_logout_post**](AuthApi.md#auth_logout_post) | **POST** /auth/logout | Logout



## auth_login_post

> String auth_login_post(username, password, referer, origin)
Login

Upon success, the response will contain a cookie with your SID. You must supply the cookie whenever you want to perform an operation that requires authentication. 

### Parameters


Name | Type | Description  | Required | Notes
------------- | ------------- | ------------- | ------------- | -------------
**username** | **String** |  | [required] |
**password** | **String** |  | [required] |
**referer** | Option<**String**> |  |  |
**origin** | Option<**String**> |  |  |

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

- **Content-Type**: application/x-www-form-urlencoded
- **Accept**: text/plain

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)


## auth_logout_post

> auth_logout_post()
Logout

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

