# Blackbird Reset

There are three ways to reset the Blackbird LoRaWAN gateway: a simple reboot, a Wi-Fi password reset, and a full factory reset. These can be performed using the hardware reset button or through the gateway's Web UI.

## Hardware Reset Button

The Blackbird LoRaWAN gateway has a hardware reset button, which can be used to perform the following reset actions:

![](../../../.gitbook/assets/gw_reset_button.png)

1. **Reboot**: To reboot the device, press the reset button momentarily. The device will restart automatically.
2. **Wi-Fi Password Reset**: To reset the Wi-Fi password to its default value, press and hold the reset button for 5 to 15 seconds. The LED will blink three times as a confirmation that the Wi-Fi password has been reset.

**Please keep in mind that the Wi-Fi password reset will took a significant amount of time to complete. Do not interrupt the process by pressing the reset button again, as this may cause the device to malfunction. After the process is completed you will see Wi-Fi named Chirp-xxxxxx (where xxxxxx is the unique number of your gateway, that you may use as a default password for Wi-Fi connection).**

3. **Full Factory Reset**: To perform a full factory reset, press and hold the reset button for more than 15 seconds. The LED will blink seven times as a confirmation when the button is released, indicating that the factory reset has been performed.

## Gateway Wisgate UI

![](../../../.gitbook/assets/gw_reset_webui.png)

You can also perform a Reboot, a Wi-Fi password reset and a full factory reset through the gateway's Wisgate UI. Follow these steps:

1. Access the Blackbird Wisgate UI by entering its IP address in your web browser.
2. Log in using your password.
3. Navigate to the "Settings" tab.
4. To reset the WiFi password, click on the "Reconfigure" button. A confirmation message will appear, and the WiFi password will be reset to its default value.
5. To perform a full factory reset, click on the "Reset" button. A confirmation message will appear, and the gateway will be reset to its factory settings.

Please note that performing a full factory reset will erase all your configurations. After performing a full factory reset, you will need to reconfigure the gateway ommiting the step with gateway registration (since it already registered in CHIRP network).
