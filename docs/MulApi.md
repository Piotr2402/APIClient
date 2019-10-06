# MulApi

All URIs are relative to *https://localhost:8080/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**mul**](MulApi.md#mul) | **GET** /mul | Multiply two numbers


<a name="mul"></a>
# **mul**
> String mul(a, b)

Multiply two numbers

Multiply two numbers send as parameters.

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.MulApi;


MulApi apiInstance = new MulApi();
Double a = 3.4D; // Double | First element
Double b = 3.4D; // Double | Second element
try {
    String result = apiInstance.mul(a, b);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling MulApi#mul");
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

