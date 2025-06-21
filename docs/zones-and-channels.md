# Codeplug Guide for my R7

This document details the programming configuration for my Motorola R7 DMR radio, covering zones, channels, talkgroups, repeaters, simplex channels, hotspot settings, FRS/GMRS channels, and analog frequencies.

## Overview

The Motorola R7 is configured for both digital (DMR) and analog communications, supporting connections to repeaters, a personal hotspot, simplex operations, and FRS/GMRS channels. The setup includes regional talkgroups tailored for specific use cases and locations.

## Zones

Zones group channels for easy access. The following zones are programmed:

| Zone Name          | Description                                      |
|--------------------|--------------------------------------------------|
| Hillsboro/Saddle   | Repeater for Hillsboro/Saddle repeater        |
| Portland/MtScott   | Channels for Portland/MtScott repeater           |
| Hotspot            | Simplex channels for personal hotspot            |
| DMR Simplex        | DMR simplex channels                             |
| FRS/GMRS           | Family Radio Service/General Mobile Radio Service |
| Analog             | Analog simplex frequencies                       |

*Note*: The Hillsboro/Saddle, Portland/MtScott, and Hotspot zones include all talkgroups listed in the Talkgroups section.

## Talkgroups

The following talkgroups are programmed for repeaters and the personal hotspot, each configured as a separate channel. All listed talkgroups are included in the Hillsboro/Saddle, Portland/MtScott, and Hotspot zones:

| Talkgroup Name     | Talkgroup ID | Time Slot | Description                           |
|--------------------|--------------|-----------|---------------------------------------|
| Parrot             | 9998         | 1         | Echo test for DMR setup              |
| Oregon 1           | 3141         | 1         | Oregon regional communication         |
| Washington 1       | 3153         | 1         | Washington regional communication     |
| Hawaii 1           | 3115         | 1         | Hawaii regional communication         |
| Hawaii TAC 1       | 311551       | 1         | Hawaii tactical communication         |
| Hawaii Tech Net    | 310745       | 1         | Hawaii technical net                  |
| PNW Rgnl 2         | 31771        | 2         | Pacific Northwest regional            |
| Cascade 1          | 3191         | 1         | Cascade regional communication        |
| Local 1            | 3181         | 1         | Local communication                   |

## Repeaters

[PNWDigital Repeater Map](https://pnwdigital.net/repeaters-map/)

Two repeaters are programmed for specific locations, each including all talkgroups listed above:

| Repeater Name      | Frequency (RX/TX, MHz) | Color Code | Talkgroups Programmed                                              | Location Usage |
|--------------------|------------------------|------------|--------------------------------------------------------------------|----------------|
| [Hillsboro/Saddle](https://pnwdigital.net/sv/siteinfo2.php?site=314116)   | 440.8125/445.8125      | 1          | All the talkgroups above, minus the Hawaii-related ones | Newberg        |
| [Portland/MtScott](https://pnwdigital.net/sv/siteinfo2.php?site=311191)   | 441.3250/446.3250      | 7          | All the talkgroups above, minus the Hawaii-related ones | Vancouver      |

## DMR Simplex Channels

The following simplex channels are programmed for DMR operation, all set to high power:

| Channel Name   | Frequency (MHz) | Color Code | Talkgroup ID | Time Slot |
|----------------|-----------------|------------|--------------|-----------|
| DMR Simplex 1  | 441.000         | CC1        | 99           | TS1       |
| DMR Simplex 2  | 446.500         | CC1        | 99           | TS1       |
| DMR Simplex 3  | 446.075         | CC1        | 99           | TS1       |
| DMR Simplex 4  | 433.450         | CC1        | 99           | TS1       |

## Hotspot Configuration

The personal hotspot is configured for simplex operation with all talkgroups listed in the Talkgroups section, using a consistent frequency, color code, and time slot for each. All channels are set to low power for home use to minimize interference and conserve battery:

| Channel Name       | Talkgroup ID | Power Level |
|--------------------|--------------|-------------|
| Parrot             | 9998         | Low         |
| Oregon 1           | 3141         | Low         |
| Washington 1       | 3153         | Low         |
| Hawaii 1           | 3115         | Low         |
| Hawaii TAC 1       | 311551       | Low         |
| Hawaii Tech Net    | 310745       | Low         |
| PNW Rgnl 2         | 31771        | Low         |
| Cascade 1          | 3191         | Low         |
| Local 1            | 3181         | Low         |

## FRS/GMRS Channels

The radio is programmed with FRS/GMRS channels 1–22 and the 8 GMRS repeater channels, using standard frequencies, GMRS power levels, and bandwidths:

| Channel Number | Frequency (MHz) | GMRS Power  | GMRS Bandwidth | Notes                     |
|----------------|-----------------|-------------|----------------|---------------------------|
| Channel 1      | 462.5625        | High Power  | 20 kHz         |                           |
| Channel 2      | 462.5875        | High Power  | 20 kHz         |                           |
| Channel 3      | 462.6125        | High Power  | 20 kHz         |                           |
| Channel 4      | 462.6375        | High Power  | 20 kHz         |                           |
| Channel 5      | 462.6625        | High Power  | 20 kHz         |                           |
| Channel 6      | 462.6875        | High Power  | 20 kHz         |                           |
| Channel 7      | 462.7125        | High Power  | 20 kHz         |                           |
| Channel 8      | 467.5625        | Low Power   | 12.5 kHz       |                           |
| Channel 9      | 467.5875        | Low Power   | 12.5 kHz       |                           |
| Channel 10     | 467.6125        | Low Power   | 12.5 kHz       |                           |
| Channel 11     | 467.6375        | Low Power   | 12.5 kHz       |                           |
| Channel 12     | 467.6625        | Low Power   | 12.5 kHz       |                           |
| Channel 13     | 467.6875        | Low Power   | 12.5 kHz       |                           |
| Channel 14     | 467.7125        | Low Power   | 12.5 kHz       |                           |
| Channel 15     | 462.5500        | High Power  | 20 kHz         |                           |
| Channel 16     | 462.5750        | High Power  | 20 kHz         |                           |
| Channel 17     | 462.6000        | High Power  | 20 kHz         |                           |
| Channel 18     | 462.6250        | High Power  | 20 kHz         |                           |
| Channel 19     | 462.6500        | High Power  | 20 kHz         |                           |
| Channel 20     | 462.6750        | High Power  | 20 kHz         |                           |
| Channel 21     | 462.7000        | High Power  | 20 kHz         |                           |
| Channel 22     | 462.7250        | High Power  | 20 kHz         |                           |
| Repeater 1     | 467.5500/462.5500 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 2     | 467.5750/462.5750 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 3     | 467.6000/462.6000 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 4     | 467.6250/462.6250 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 5     | 467.6500/462.6500 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 6     | 467.6750/462.6750 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 7     | 467.7000/462.7000 | High Power  | 20 kHz         | RX/TX pair for repeater    |
| Repeater 8     | 467.7250/462.7250 | High Power  | 20 kHz         | RX/TX pair for repeater    |

## Analog Channels

The following analog channel is programmed for simplex operation:

| Channel Name       | Frequency (MHz) | Mode   | Notes                           |
|--------------------|-----------------|--------|---------------------------------|
| National Calling   | 446.000         | Analog | National simplex calling frequency |

## Programming Notes

- **Power Settings**: Use low power for hotspot channels to minimize interference and conserve battery. All DMR simplex channels are set to high power.
- **Backup**: Save the codeplug file after programming to preserve the configuration.