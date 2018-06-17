
This is a fork of the IRremote Arduino library to add support for sending IR with the ESP32.
To use it, pass the pin you connect the IR LED to:

    const byte LED_PIN = 21;
    IRsend irsend(LED_PIN);

The pin must be capable of doing LEDC PWM.

Check out the original repro for readme, copyright, license etc:
https://github.com/z3t0/Arduino-IRremote