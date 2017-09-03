## Confluent Open Source Platform REST Proxy Docker image using Oracle JDK

### Supported tags and respective Dockerfile links:

* ```jesse-slim-8u144-2.11.11-3.2.2``` _\([jesse-slim-8u144-2.11.11-3.2.2/Dockerfile]\)_
[![](https://images.microbadger.com/badges/image/mbe1224/confluent-osp-rest-proxy:jesse-slim-8u144-2.11.11-3.2.2.svg)](https://microbadger.com/images/mbe1224/confluent-osp-rest-proxy:jesse-slim-8u144-2.11.11-3.2.2 "")
* ```jesse-slim-8u144-2.11.11-3.3.0``` _\([jesse-slim-8u144-2.11.11-3.3.0/Dockerfile]\)_
[![](https://images.microbadger.com/badges/image/mbe1224/confluent-osp-rest-proxy:jesse-slim-8u144-2.11.11-3.3.0.svg)](https://microbadger.com/images/mbe1224/confluent-osp-rest-proxy:jesse-slim-8u144-2.11.11-3.3.0 "")

#### All tag names follow the naming convention:

```debian_image_tag``` + '-' + ```java_version``` + '-' + ```scala_version``` + '-' + ```confluent_platform_version```

### Usage:

Build the image
```shell
docker build -t mbe1224/confluent-osp-rest-proxy .
```

### About this image:

- Debian "slim" image variant
- Oracle Java SE Development Kit (JDK) addded, without MissionControl, VisualVM, JavaFX and JRE
- Oracle Java Cryptography Extension added
- Python 2.7.9-1 & pip 8.1.2 added
- SHA 256 sum checks for all downloads
- JAVA\_HOME and SCALA\_HOME environment variables set up

### License:

* [Apache License]
* [Oracle Binary Code License Agreement]

   [jesse-slim-8u144-2.11.11-3.2/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/jesse-slim-8u144-2.11.11-3.2/Dockerfile>
   [stretch-slim-8u144-2.11.11-3.2/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/stretch-slim-8u144-2.11.11-3.2/Dockerfile>
   [jesse-slim-8u144-2.12.3-3.2/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/jesse-slim-8u144-2.12.3-3.2/Dockerfile>
   [stretch-slim-8u144-2.12.3-3.2/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/stretch-slim-8u144-2.12.3-3.2/Dockerfile>
   [jesse-slim-8u144-2.11.11-3.3/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/jesse-slim-8u144-2.11.11-3.3/Dockerfile>
   [stretch-slim-8u144-2.11.11-3.3/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/stretch-slim-8u144-2.11.11-3.3/Dockerfile>
   [jesse-slim-8u144-2.12.3-3.3/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/jesse-slim-8u144-2.12.3-3.3/Dockerfile>
   [stretch-slim-8u144-2.12.3-3.3/Dockerfile]: <https://github.com/MihaiBogdanEugen/confluent-osp-rest-proxy/blob/stretch-slim-8u144-2.12.3-3.3/Dockerfile>
   [Apache License]: <https://raw.githubusercontent.com/MihaiBogdanEugen/confluent-osp-rest-proxy/master/LICENSE>
   [Oracle Binary Code License Agreement]: <https://raw.githubusercontent.com/MihaiBogdanEugen/confluent-osp-rest-proxy/master/Oracle_Binary_Code_License_Agreement%20for%20the%20Java%20SE%20Platform_Products_and_JavaFX>