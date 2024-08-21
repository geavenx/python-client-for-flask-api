# MultiplyRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**numbers** | **List[float]** | List of numbers to multiply | [optional] 

## Example

```python
from calcssdkpython.models.multiply_request import MultiplyRequest

# TODO update the JSON string below
json = "{}"
# create an instance of MultiplyRequest from a JSON string
multiply_request_instance = MultiplyRequest.from_json(json)
# print the JSON string representation of the object
print(MultiplyRequest.to_json())

# convert the object into a dict
multiply_request_dict = multiply_request_instance.to_dict()
# create an instance of MultiplyRequest from a dict
multiply_request_from_dict = MultiplyRequest.from_dict(multiply_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


