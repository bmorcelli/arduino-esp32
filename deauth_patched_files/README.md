# Deauth patched files
Copy these files to: `tools/sdk/esp32/lib` and `tools/sdk/esp32s3/lib`
```
rm ./tools/sdk/esp32/lib/libnet80211.a
rm ./tools/sdk/esp32s3/lib/libnet80211.a
cp ./deauth_patched_files/ESP32-lib/libnet80211.a ./tools/sdk/esp32/lib/
cp ./deauth_patched_files/ESP32s3-lib/libnet80211.a ./tools/sdk/esp32s3/lib/
```