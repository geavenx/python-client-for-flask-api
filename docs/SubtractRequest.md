# SubtractRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**numbers** | **List[float]** | List of numbers to subtract | [optional] 

## Example

```python
from calcssdkpython.models.subtract_request import SubtractRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SubtractRequest from a JSON string
subtract_request_instance = SubtractRequest.from_json(json)
# print the JSON string representation of the object
print(SubtractRequest.to_json())

# convert the object into a dict
subtract_request_dict = subtract_request_instance.to_dict()
# create an instance of SubtractRequest from a dict
subtract_request_from_dict = SubtractRequest.from_dict(subtract_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


