### Hex (Little Endian)
- $ft = (Hex) //Contoh: 0x01DC62B4C6C58120
- $dt = [DateTime]::FromFileTimeUtc($ft)
- $dt.ToLocalTime()
