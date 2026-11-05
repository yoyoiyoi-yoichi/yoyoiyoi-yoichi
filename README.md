# Hi, I'm Meiko 👋

### Embedded & IoT Engineer · Tokyo, Japan

I connect things that were never meant to be connected, and then I keep them connected.

By day I build device-to-cloud plumbing for industrial sensors: gateways in factory corners, MQTT brokers in the middle, and dashboards that someone in an office actually looks at. Most of my work lives in the unglamorous layer between a sensor that blinks and a graph that moves.

## What my days actually look like

- Arguing with MQTT brokers (Mosquitto / EMQX / AWS IoT Core) about QoS levels, retained messages, and ACLs
- Reading serial logs and packet captures until the one weird device explains itself
- Finding out the "mystery outage" was an expired TLS certificate, a dead PoE switch, or someone unplugging the gateway to charge their phone
- Driving to a site with a laptop, a spare gateway, and a bag of cables I refuse to throw away "just in case"
- Writing the runbook afterwards, because future me deserves better than present me had

## Toolbox

- **Protocols & platforms:** MQTT, Modbus, BLE, HTTP webhooks, AWS IoT Core, Node-RED
- **Devices:** ESP32, Raspberry Pi, industrial gateways, whatever has a UART and opinions
- **Languages:** Python for glue and tooling, C when I have to read what the firmware is really doing, shell for everything else
- **Instruments of truth:** Wireshark, a logic analyzer, a multimeter, and `mosquitto_sub -v` at 2 a.m.
- **Currently poking at:** Matter / Thread, and Rust for edge services that shouldn't need a reboot to behave

## The gorilla thing

The lab calls me the gorilla, and honestly it's accurate. When a UPS needs carrying, a rack needs mounting, or a connector needs more hand strength than diplomacy, they come to me. I can rack a server and debug a broker ACL in the same afternoon, and I take both parts as a compliment.

The pink bob and the dark glasses are so field techs can find me in a warehouse. It works.

## How I think about the work

- Measure first. Guessing is just debugging with extra confidence.
- Log everything; the one value you didn't log is the one the incident will be about.
- Change one thing at a time, write down what happened, and don't trust a fix you can't reproduce breaking.
- Most ghost bugs are DNS, certificates, power, or cables. In that order, roughly.

Off the clock, my apartment is over-automated in ways I would never ship to a customer: too many sensors, a broker with opinions, and lights that mostly do what I meant. I regret nothing, and I'm not fixing the bathroom presence sensor. It stays.

— Meiko
