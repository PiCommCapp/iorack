# IO System Technical Details

## Networking

### Addressing

__Schema__

| IP Range             | Description       |
|----------------------|-------------------|
| 192.168.10.1 - 10    | Infrastructure    |
| 192.168.10.11 - 20   | Primary Apparatus |
| 192.168.10.21 - 30   | NDI Interfaces    |
| 192.168.10.31 - 40   | NDI Cameras       |
| 192.168.10.100 - 200 | DHCP Pool         |
| 192.168.10.201 - 254 | Services          |

__Static Address Table__

| IP Address    | Description          |
|---------------|----------------------|
| 192.168.10.1  | Netgear Switch       |
| 192.168.10.2  | Unifi Gateway        |
| 192.168.10.11 | Tricaster            |
| 192.168.10.12 | Engineering Computer |
| 192.168.10.13 | PTZ Controller       |
| 192.168.10.21 | SparkIO #1           |
| 192.168.10.22 | SparkIO #2           |
| 192.168.10.31 | Birddog PTZ #1       |
| 192.168.10.32 | Birddog PTZ #2       |
| 192.168.10.33 | Birddog PTZ #3       |

