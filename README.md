# scrypt2luaAPI
Converts Scrypt code to Lua before execution.

# IMPORTANT

Make sure to place `api_handler.scrypt`, `api_registry.scrypt` and `localapi.scrypt` in your executor's workspace folder as the API requires those files and will error if they are not found.

Also, **DO NOT** change any of the hexadecimal bytes inside those files; they have tamper protection and may corrupt Roblox using an invalid API `start_api_reference_entrance{}` key.
