### Mengubah Timestamp Registri ke Hex (Little Endian), supaya bisa mengetahui waktu aslinya.
$ft = (Hex) //Contoh: 0x01DC62B4C6C58120 <br>
$dt = [DateTime]::FromFileTimeUtc($ft) 
$dt.ToLocalTime() <br>
