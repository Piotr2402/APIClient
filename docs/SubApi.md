# SubApi

All URIs are relative to *https://localhost:8080/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**sub**](SubApi.md#sub) | **GET** /sub | Add two numbers


<a name="sub"></a>
# **sub**
> String sub(a, b)

Add two numbers

Subtracts two numbers send as parameters.

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.SubApi;


SubApi apiInstance = new SubApi();
Double a = 3.4D; // Double | First element
Double b = 3.4D; // Double | Second element
try {
    String result = apiInstance.sub(a, b);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling SubApi#sub");
    e.printStackTrace();
}
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **a** | **Double**| First element | [default to 0]
 **b** | **Double**| Second element | [default to 0]

### Return type

**String**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: application/xml, application/json

