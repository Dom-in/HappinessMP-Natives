# REQUEST_CONTROL_OF_NETWORK_ID

## Declaration
```cpp
// 0x29926B20
bool REQUEST_CONTROL_OF_NETWORK_ID(int networkId);
```

### Arguments
- **int:** networkId

### Returns
- **bool**

## Description
Request ownership of the object with the specified network ID from the current owner. This is not instantanous, and it's recommended to call it multiple times, checking if we have gained control of the network ID each time, due to potential packet loss.