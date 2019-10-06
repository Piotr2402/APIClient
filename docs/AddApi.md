# AddApi

All URIs are relative to *https://localhost:8080/api*

Method | HTTP request | Description
------------- | ------------- | -------------
[**add**](AddApi.md#add) | **GET** /add | Add two numbers


<a name="add"></a>
# **add**
> String add(a, b)

Add two numbers

Add two numbers send as parameters.

### Example
```java
// Import classes:
//import io.swagger.client.ApiException;
//import io.swagger.client.api.AddApi;


AddApi apiInstance = new AddApi();
Double a = 3.4D; // Double | First element
Double b = 3.4D; // Double | Second element
try {
    String result = apiInstance.add(a, b);
    System.out.println(result);
} catch (ApiException e) {
    System.err.println("Exception when calling AddApi#add");
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

