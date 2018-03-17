# iot
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![StackShare](https://img.shields.io/badge/tech-stack-0690fa.svg?style=flat)](https://stackshare.io/mmontes11/iot)

Generic purpose Internet of Things platform. It consists of the following parts:

* [iot-server](https://github.com/mmontes11/iot-server)
* [iot-client](https://github.com/mmontes11/iot-client)
* [iot-raspi-sensors](https://github.com/mmontes11/iot-raspi-sensors)
* [biot](https://github.com/mmontes11/biot)

### Configuration

* [.env](https://github.com/mmontes11/iot/blob/develop/.env)
* [nginx.conf](https://github.com/mmontes11/iot/blob/develop/nginx/nginx.conf)
* [iot-server/.env](https://github.com/mmontes11/iot/blob/develop/iot-server/.env)
* [biot/.env](https://github.com/mmontes11/iot/blob/develop/biot/.env)

### Run in development

```bash
$ ./run-development.sh 
```

### Run in production

```bash
$ ./run-production.sh 
```

### Things

Once backend is up and running, you can start deploying things:

* [iot-raspi-sensors](https://github.com/mmontes11/iot-raspi-sensors)