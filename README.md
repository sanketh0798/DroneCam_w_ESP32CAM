IMAGE RECONGNITION VIDEO STREAMING BASED ON ESP32

Devices used - 
      ESP32 CAM AI Thinker, 
      CH340G USB To TTL(Serial) Converter, 
      I2C OLED.

Libraries - 
      esp32 by espressif systems, 
      EloquentEsp32cam by simone salerno, 
      Adafruit GFX Library, 
      Adafruit SSD1306 (This is the most common driver for these OLEDs).

ML tool - EDGE IMPULSE
IDE - Arduino

Steps/approach
    1. Get the library for esp32 cam and run the example CameraWebServer of ESP32 Camera.
    2. See the video streaming in local wifi
    3. Use the Eloquent library example to interface with EDGE IMPULSE and capture sample images in Egde Impluse.
    4. Do the steps in Edge impulse to generate the ML based image recongnition library/code.
    5. Add the generated code in the library and run the code from Example->"egde impulse project name"->esp32->esp32 camera.
    6. This is the base code.
    7. Use the Adafruit example for OLED display, and try to display "HELLO WORLD".
    8. Now modify the base code to add the CameraWebServer and OLED display code to implement the project
