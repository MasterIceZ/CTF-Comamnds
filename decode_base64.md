```python
import base64
message = input()
message_bytes = message.encode('ascii')
base64_bytes = base64.b64encode(message_bytes)
base64_message = base64_bytes.decode('ascii')

print(base64_message)
```
[Source](https://stackabuse.com/encoding-and-decoding-base64-strings-in-python/)
