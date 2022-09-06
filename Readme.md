# Losant Example
Simple example built for [esp-rust-board](https://github.com/esp-rs/esp-rust-board) that sends temperature and humidity to
Losant, via MQTT, where it can be [visualized in this dashboard](https://app.losant.com/dashboards/6317314b80eae13991afeb09).

![Losant Dashboard](static/losant_dashboard.png)

If you want to reproduce this example:
1. [Create a standalone Losant device with the proper atributes (in this case `humidity` and `temperature`)](https://docs.losant.com/devices/overview/)
2. [Create Losant access key and secret](https://docs.losant.com/applications/access-keys/)
3. Rename `cfg.toml.example` to `cfg.toml`
4. Fill the `cfg.toml` with
   1. `wifi_ssid`: Wifi SSID
   2. `wifi_pass`: Wifi password
   3. `client_id`: Losant device ID
   4. `username`: Losant access key
   5. `password`: Losant access secret
5. [Create a Losant dashboard](https://docs.losant.com/dashboards/overview/)

