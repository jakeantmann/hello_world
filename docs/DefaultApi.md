# HelloWorld.DefaultApi

All URIs are relative to *http://localhost:9090/v1.0*

Method | HTTP request | Description
------------- | ------------- | -------------
[**helloPostGreeting**](DefaultApi.md#helloPostGreeting) | **POST** /greeting/{name} | Generate greeting

<a name="helloPostGreeting"></a>
# **helloPostGreeting**
> &#x27;String&#x27; helloPostGreeting(name)

Generate greeting

Generates a greeting message.

### Example
```javascript
import {HelloWorld} from 'hello_world';

let apiInstance = new HelloWorld.DefaultApi();
let name = "name_example"; // String | Name of the person to greet.

apiInstance.helloPostGreeting(name, (error, data, response) => {
  if (error) {
    console.error(error);
  } else {
    console.log('API called successfully. Returned data: ' + data);
  }
});
```

### Parameters

Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **name** | **String**| Name of the person to greet. | 

### Return type

**&#x27;String&#x27;**

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: Not defined
 - **Accept**: text/plain

