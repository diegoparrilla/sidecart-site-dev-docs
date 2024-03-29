---
layout: default
title: Parameters
nav_order: 8
---

# Configuration Parameters

{: warning}
Please modify the parameters with caution, as they can affect the behavior of the SidecarT board. Read the [User Guide](/userguide) section for more information.

| Parameter            | Type      | Description                                            | Released | Default                              |
|:---------------------|:----------|:-------------------------------------------------------|:---------|:-------------------------------------|
| BOOT_FEATURE         | STRING    | Firmware mode to start after SidecarT reboot           | v0.0.1   | CONFIGURATOR                         |
| DELAY_ROM_EMULATION  | BOOLEAN   | Enable or disable Delay/Ripper mode                    | v0.0.9   | false                                |
| DOWNLOAD_TIMEOUT_SEC | INTEGER   | The timeout in seconds for the download operations     | v0.0.15  | 60                                   |
| FLOPPIES_FOLDER      | STRING    | The folder where the SidecarT will find the Floppy images | v0.0.10  | /floppies                            |
| FLOPPY_DB_URL        | STRING    | The URL of the Atari ST floppy database                | v0.0.11  | http:// ataristdb.        |
| FLOPPY_IMAGE_A       | STRING    | File with the floppy image to emulate in drive A       | v0.0.10  |                                      |
| FLOPPY_IMAGE_B       | STRING    | File with the floppy image to emulate in drive B       |          |                                      |
| HOSTNAME             | STRING    | The hostname of the SidecarT in the TCP/IP network     | v0.0.1   | sidecart                             |
| LATEST_RELEASE_URL   | STRING    | The URL of the file with the latest SidecarT release version | v0.0.1   | http:// atarist./ version.txt |
| MENU_REFRESH_SEC     | INTEGER   | The number of seconds to refresh the Configurator menu | v0.0.15  | 3                                    |
| NETWORK_STATUS_SEC   | INTEGER   | The number of seconds for the polling interval to check the status of the network | v0.0.15  | 10                                    |
| ROMS_FOLDER          | STRING    | The folder where the SidecarT will find the ROM images | v0.0.1   | /roms                                |
| ROMS_YAML_URL        | STRING    | The URL of the JSON file with the ROMs information     | v0.0.1   | http:// roms./ roms.json   |
| RTC_NTP_SERVER_HOST  | STRING    | The NTP server host to synchronize the RTC             | v0.0.12  | pool.ntp.org                         |
| RTC_NTP_SERVER_PORT  | INTEGER   | The NTP server port to synchronize the RTC             | v0.0.12  | 123                                  |
| RTC_TYPE             | STRING    | The type of RTC to emulate: SIDECART, DALLAS           | v0.0.12  | SIDECART                             |
| RTC_UTC_OFFSET       | STRING    | The UTC offset of the RTC                              | v0.0.12  | 0                                    |
| SAFE_CONFIG_REBOOT   | BOOL      | If true, the SidecarT will reboot after a computer power cycle, otherwise it will reboot immediately | v0.0.9   | true                                 |
| WIFI_PASSWORD        | STRING    | The password of the WiFi network to connect to         | v0.0.1   |                                      |
| WIFI_SCAN_SECONDS    | INTEGER   | The number of seconds to scan for WiFi networks        | v0.0.1   | 15                                   |
| WIFI_SSID            | STRING    | The SSID of the WiFi network to connect to             | v0.0.1   |                                      |
| WIFI_AUTH            | INTEGER   | The authentication type of the WiFi network to connect to | v0.0.1   |                                      |
| WIFI_COUNTRY         | STRING    | The country code of the WiFi network to connect to     | v0.0.15   | XX                                    |
