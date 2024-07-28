# ESP8266 based TM1628 clock

Includes:
- Wifi
- NTP time sync support
- REST Client
- IR receiver
- Ping support

## secrets.h sample:
```C++
#pragma once

#define SECRET_SSID "xxx"
#define SECRET_WIFI_KEY "xxx"

#define HTTP_SERVER_NAME "xxx"
#define HTTP_SERVER_PORT "80"

#define HTTP_REQ_PLAY         "/xxx/";
#define HTTP_REQ_PAUSE        "/xxx/";
#define HTTP_REQ_STOP         "/xxx/";
#define HTTP_REQ_VOLUME       "/xxx/";
#define HTTP_REQ_VOLUME_UP    "/xxx/";
#define HTTP_REQ_VOLUME_DOWM  "/xxx/";
#define HTTP_REQ_NEXT         "/xxx/";
#define HTTP_REQ_PREV         "/xxx/";
```

# Credits
algirdasc - https://github.com/algirdasc/esp32-tm1628-clock/tree/main
BlockThor - https://github.com/BlockThor/TM1628
