# ServerboundPreLoginPacket

| Name | Size (bytes) | Notes |
|-------------------------|-------------|------|
| PacketID | 0x01 (u8) | Must be 0xE8 |
| Unknown | 0x03 | |
| Player name | Variable (short-prefixed) | UTF16 string with length determined by prefixed ushort |
