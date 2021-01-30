ESP32-A1S audio_hal driver.

Notes: 

1) in your ~/esp-adf/components/audio_hal/driver/ac101 folder you will find 2 symlinks.
Theese links are in lower caps and should point to AC101.c and AC101.h in the same directory.
This is done to avoid missing sources.

2) in the ~/esp-adf/components/audio_hal/CMakelists.txt the last two lines have been commented out
This makes it impossible using the zl38063 driver. If you need that specific driver uncomment.
