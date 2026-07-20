# Privacy Policy

**Last updated:** July 22, 2026

This Privacy Policy describes how **1-Wire Smart Home Controller** ("the App") developed by **Aleksandr Demidov** handles your information.

## Important: We Do Not Collect Your Personal Information

**This App does not collect, store, or transmit any personal information, user data, or device data to us or any third party.**

The App operates entirely on your **local WiFi network** and communicates only with your 1-Wire smart home controllers. All data remains exclusively on your own devices and local network.

## What This App Does

The App allows you to:

- View real-time sensor data (temperature, voltage, digital states) from your own devices
- Control relays and actuators connected to your controllers
- Configure automation rules (schedules, thermostats, astro mode)
- Update controller firmware

**Important: Controllers operate fully offline.** Your smart home controller will continue to function with all configured automation, sensor monitoring, and relay control **without an internet connection**. All automation rules (time-based schedules, thermostat settings, astro mode, etc.) run locally on the controller device itself.

## Current 1-Wire Controller Supports Chips:

- DS18B20 (a temperature sensor)
- DS2413A (2 channels of sensors or relays)
- DS2408 (8 channels of sensors or relays)
- DS2438Z (thermocouple and voltmeter or ammeter)

## Data That Stays On Your Local Network

When you use the App, the following data exists **only on your local network** between your mobile device and your controllers:

- **Controller identifiers** (device serial numbers, local hostnames)
- **Sensor readings** (temperature, voltage, switch states from your own sensors)
- **Relay/actuator states** (on/off status of your connected devices)
- **Control commands** (your instructions to turn devices on/off)
- **Configuration data** (your saved settings for automation and control)
- **Network communication** (WebSocket, UDP port 7777, MQTT topics if configured)

**None of this data is sent to us, stored on our servers, or shared with any third party.**

## Limited Technical Information

The App may collect **non-personal, anonymous** technical information solely for the purpose of improving the App:

- **App version and device type** (to ensure compatibility)
- **Crash reports** (anonymous error logs to fix bugs)
- **Feature usage statistics** (aggregated, non-identifiable data about which features are used)

This anonymous data contains **no personal identifiers, no IP addresses, no user accounts, and no smart home data.**

## No Account Required

- The App does **not** require you to create an account
- The App does **not** require you to sign in with Google, Facebook, or any other service
- The App does **not** access your contacts, photos, location (except for astro mode calculations if you choose to enable it), or any other personal data on your mobile device

## WiFi Network Credentials

When you configure a controller to connect to your WiFi network:

- Credentials are entered **directly into the controller's web interface**
- They are **stored only on the controller device itself**
- We **never** see, store, or transmit your WiFi password
- We **never** access your WiFi network remotely

## Optional Location Data (Astro Mode)

If you choose to use **astro mode** (sunrise/sunset automation):

- You may enter **geographical coordinates** for your location
- These coordinates are **stored only on your controller**
- They are used **solely for astronomical calculations** (sunrise/sunset times)
- We do **not** collect or store this information

## Third-Party Services

### MQTT Integration (Optional)

If you configure MQTT integration:

- Your controller will connect to **your chosen MQTT broker**
- We do **not** operate, control, or access any MQTT brokers
- Data shared with MQTT brokers is governed by **your broker's privacy policy**

### Open Source Components

The App may use open source libraries that have their own licenses. We will disclose any components that collect data.

## Data Security

Since all data remains on your local network:

- **Your WiFi network security protects your data** (use WPA2/WPA3 encryption)
- **Your router's firewall prevents external access**
- **No data leaves your local network** unless you explicitly configure external integrations (MQTT, OpenHab, etc.)

## Your Rights

Since we do not collect your personal information:

- There is **no personal data to access, correct, or delete**
- You have **full control** over all data on your own devices and network
- You can **factory reset** your controllers at any time to remove all stored data

## Children's Privacy

The App is **not intended for use by children under 13** (or under 16 in the EU). We do not knowingly collect any information from children.

## Changes to This Privacy Policy

We may update this Privacy Policy if our data practices change. We will notify you by updating the "Last updated" date and posting the new policy in the App.

## Contact Us

If you have any questions about this Privacy Policy, please contact us:

**Email:** [alex.m.demidoff@gmail.com](mailto:alex.m.demidoff@gmail.com)

**Developer:** Aleksandr Demidov  
**App Name:** 1-Wire Smart Home Controller  
**Product Website:** [https://home.1vp.ru/en/1-wire-controller/](https://home.1vp.ru/en/1-wire-controller/)
