# ESP32-TFT
This is a sample project on how to connect a SPI TFT display to a Heltec Wifi V3 ESP32 module. 
My dev enviroment is vscode with PlatformIO. This should work with arduinoIDE with libraries configured the same.

These pins are used as default pins are used by onboard OLED 

// TFT_MOSI 33 // In some display driver board, it might be written as "SDA" and so on.
// TFT_SCLK 34 // Also SCL
// TFT_CS   5  // Chip select control pin
// TFT_DC   2  // Data Command control pin
// TFT_RST  1  // Reset pin (could connect to Arduino RESET pin)
// TFT_BL   3  // LED back-light
