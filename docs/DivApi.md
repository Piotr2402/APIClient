# DivApi

All URIs are relative to *https://localhost:8080/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**div**](DivApi.md#div) | **GET** /div | Divide two numbers


<a name="div"></a>
# **div**
> String div(a, b)

Divide two numbers

Divide two numbers send as parameters.

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.DivApi;


DivApi apiInstance = new DivApi();
Double a = 3.4D; // Double | First element
Double b = 3.4D; // Double | Second element
try {
    String result = apiInstance.div(a, b);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling DivApi#div");
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

