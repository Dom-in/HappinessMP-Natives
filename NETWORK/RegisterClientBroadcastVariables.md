# REGISTER_CLIENT_BROADCAST_VARIABLES

## Declaration
```cpp
// 0x499B6DB6
void REGISTER_CLIENT_BROADCAST_VARIABLES(void* vars, int size, int broadcast_id);
```

### Arguments
- **void\*:** vars
- **int:** size
- **int:** broadcast_id

### Results

## Description
Registers the variables for each client running the script. The table passed to the **vars** argument must have a maximum size of 1024 bytes, the first 4 bytes being a 32-bit integer for the number of slots in the network session, and the rest of the space as an array of structs; therefore the structs for each slot can only have a maximum size of 32 bytes if 32 players, and 64 bytes if 16 players.

