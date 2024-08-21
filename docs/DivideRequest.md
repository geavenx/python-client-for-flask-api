# DivideRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**numbers** | **List[float]** | List of numbers to divide | [optional] 

## Example

```python
from calcssdkpython.models.divide_request import DivideRequest

# TODO update the JSON string below
json = "{}"
# create an instance of DivideRequest from a JSON string
divide_request_instance = DivideRequest.from_json(json)
# print the JSON string representation of the object
print(DivideRequest.to_json())

# convert the object into a dict
divide_request_dict = divide_request_instance.to_dict()
# create an instance of DivideRequest from a dict
divide_request_from_dict = DivideRequest.from_dict(divide_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


