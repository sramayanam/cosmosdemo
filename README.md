# Azure IoT Hub Device Emulator
Original source comes from Paolo Salvatori and is published @ https://code.msdn.microsoft.com/How-to-read-events-from-an-1641eb1b
The tool is used to simulate a configuarable amout of devices sending messages to Azure IoT Hub.

Made two changes:
1. Add protocol selection (AMQP, MQTT, HTTP) when connecting to Azure IoT Hub
2. Update device id to be random values to avoid duplication