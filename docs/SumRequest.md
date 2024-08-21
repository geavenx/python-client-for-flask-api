# SumRequest


## Properties

Name | Type | Description | Notes
------------ | ------------- | ------------- | -------------
**numbers** | **List[float]** | List of numbers to sum | [optional] 

## Example

```python
from calcssdkpython.models.sum_request import SumRequest

# TODO update the JSON string below
json = "{}"
# create an instance of SumRequest from a JSON string
sum_request_instance = SumRequest.from_json(json)
# print the JSON string representation of the object
print(SumRequest.to_json())

# convert the object into a dict
sum_request_dict = sum_request_instance.to_dict()
# create an instance of SumRequest from a dict
sum_request_from_dict = SumRequest.from_dict(sum_request_dict)
```
[[Back to Model list]](../README.md#documentation-for-models) [[Back to API list]](../README.md#documentation-for-api-endpoints) [[Back to README]](../README.md)


