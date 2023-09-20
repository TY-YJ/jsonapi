# jsonapi

This Python module provides a custom JSON encoder (BetterEncoder) and decoder (BetterDecoder) designed to handle specific data types like complex numbers and ranges when serializing and deserializing JSON. The module also includes dumps and loads functions for easy use.

## Installation
You can install the package using pip:

## Supported Data Types
The custom encoder and decoder support the following data types:

complex numbers
range objects

## Example

import jsonapi


```python
# Your object
my_object = ...

# Encode the object
encoded_json = json.dumps(my_object)


# Decode the object
decoded_json = json.loads(my_object)
```
