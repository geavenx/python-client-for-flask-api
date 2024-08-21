# calcssdkpython.ArithmeticOperationsApi

All URIs are relative to *http://localhost:5000*

Method | HTTP request | Description
------------- | ------------- | -------------
[**divide_post**](ArithmeticOperationsApi.md#divide_post) | **POST** /divide | Divide a list of numbers
[**multiply_post**](ArithmeticOperationsApi.md#multiply_post) | **POST** /multiply | Multiply a list of numbers
[**subtract_post**](ArithmeticOperationsApi.md#subtract_post) | **POST** /subtract | Subtract a list of numbers
[**sum_post**](ArithmeticOperationsApi.md#sum_post) | **POST** /sum | Sum a list of numbers


# **divide_post**
> DivideResponse divide_post(divide_request=divide_request)

Divide a list of numbers

### Example


```python
import calcssdkpython
from calcssdkpython.models.divide_request import DivideRequest
from calcssdkpython.models.divide_response import DivideResponse
from calcssdkpython.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:5000
# See configuration.py for a list of all supported configuration parameters.
configuration = calcssdkpython.Configuration(
    host = "http://localhost:5000"
)


# Enter a context with an instance of the API client
with calcssdkpython.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = calcssdkpython.ArithmeticOperationsApi(api_client)
    divide_request = calcssdkpython.DivideRequest() # DivideRequest |  (optional)

    try:
        # Divide a list of numbers
        api_response = api_instance.divide_post(divide_request=divide_request)
        print("The response of ArithmeticOperationsApi->divide_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArithmeticOperationsApi->divide_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **divide_request** | [**DivideRequest**](DivideRequest.md)|  | [optional] 

### Return type

[**DivideResponse**](DivideResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Result of division |  -  |
**400** | Invalid input or division by zero |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **multiply_post**
> MultiplyResponse multiply_post(multiply_request=multiply_request)

Multiply a list of numbers

### Example


```python
import calcssdkpython
from calcssdkpython.models.multiply_request import MultiplyRequest
from calcssdkpython.models.multiply_response import MultiplyResponse
from calcssdkpython.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:5000
# See configuration.py for a list of all supported configuration parameters.
configuration = calcssdkpython.Configuration(
    host = "http://localhost:5000"
)


# Enter a context with an instance of the API client
with calcssdkpython.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = calcssdkpython.ArithmeticOperationsApi(api_client)
    multiply_request = calcssdkpython.MultiplyRequest() # MultiplyRequest |  (optional)

    try:
        # Multiply a list of numbers
        api_response = api_instance.multiply_post(multiply_request=multiply_request)
        print("The response of ArithmeticOperationsApi->multiply_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArithmeticOperationsApi->multiply_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **multiply_request** | [**MultiplyRequest**](MultiplyRequest.md)|  | [optional] 

### Return type

[**MultiplyResponse**](MultiplyResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Product of numbers |  -  |
**400** | Invalid input |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **subtract_post**
> SubtractResponse subtract_post(subtract_request=subtract_request)

Subtract a list of numbers

### Example


```python
import calcssdkpython
from calcssdkpython.models.subtract_request import SubtractRequest
from calcssdkpython.models.subtract_response import SubtractResponse
from calcssdkpython.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:5000
# See configuration.py for a list of all supported configuration parameters.
configuration = calcssdkpython.Configuration(
    host = "http://localhost:5000"
)


# Enter a context with an instance of the API client
with calcssdkpython.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = calcssdkpython.ArithmeticOperationsApi(api_client)
    subtract_request = calcssdkpython.SubtractRequest() # SubtractRequest |  (optional)

    try:
        # Subtract a list of numbers
        api_response = api_instance.subtract_post(subtract_request=subtract_request)
        print("The response of ArithmeticOperationsApi->subtract_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArithmeticOperationsApi->subtract_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **subtract_request** | [**SubtractRequest**](SubtractRequest.md)|  | [optional] 

### Return type

[**SubtractResponse**](SubtractResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Result of subtraction |  -  |
**400** | Invalid input |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

# **sum_post**
> SumResponse sum_post(sum_request=sum_request)

Sum a list of numbers

### Example


```python
import calcssdkpython
from calcssdkpython.models.sum_request import SumRequest
from calcssdkpython.models.sum_response import SumResponse
from calcssdkpython.rest import ApiException
from pprint import pprint

# Defining the host is optional and defaults to http://localhost:5000
# See configuration.py for a list of all supported configuration parameters.
configuration = calcssdkpython.Configuration(
    host = "http://localhost:5000"
)


# Enter a context with an instance of the API client
with calcssdkpython.ApiClient(configuration) as api_client:
    # Create an instance of the API class
    api_instance = calcssdkpython.ArithmeticOperationsApi(api_client)
    sum_request = calcssdkpython.SumRequest() # SumRequest |  (optional)

    try:
        # Sum a list of numbers
        api_response = api_instance.sum_post(sum_request=sum_request)
        print("The response of ArithmeticOperationsApi->sum_post:\n")
        pprint(api_response)
    except Exception as e:
        print("Exception when calling ArithmeticOperationsApi->sum_post: %s\n" % e)
```



### Parameters


Name | Type | Description  | Notes
------------- | ------------- | ------------- | -------------
 **sum_request** | [**SumRequest**](SumRequest.md)|  | [optional] 

### Return type

[**SumResponse**](SumResponse.md)

### Authorization

No authorization required

### HTTP request headers

 - **Content-Type**: application/json
 - **Accept**: application/json

### HTTP response details

| Status code | Description | Response headers |
|-------------|-------------|------------------|
**200** | Sum of numbers |  -  |
**400** | Invalid input |  -  |

[[Back to top]](#) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to Model list]](../README.md#documentation-for-models) [[Back to README]](../README.md)

