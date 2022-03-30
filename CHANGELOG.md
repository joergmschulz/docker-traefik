## 1.1.13 2022-03-30 <dave at tiredofit dot ca>

   ### Added
      - Traefik cert dumper 2.8.1
      - Traefik MIgration tool 0.13.4


## 1.1.12 2022-02-09 <dave at tiredofit dot ca>

   ### Changed
      - Rework to support new base image


## 1.1.11 2022-02-09 <dave at tiredofit dot ca>

   ### Changed
      - Update Base Image


## 1.1.10 2021-12-07 <dave at tiredofit dot ca>

   ### Added
      - Add Zabbix auto agent registration for templates


## 1.1.9 2021-11-24 <dave at tiredofit dot ca>

   ### Added
      - Alpine 3.15 base


## 1.1.8 2021-09-04 <dave at tiredofit dot ca>

   ### Changed
      - Change the way logrotate configuress


## 1.1.7 2021-08-31 <dave at tiredofit dot ca>

   ### Added
      - Alpine 3.14


## 1.1.6 2021-08-31 <dave at tiredofit dot ca>

   ### Added
      - Add fluent-bit logging


## 1.1.5 2021-01-25 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.7
      - Traefik Migration Tool 0.13.1
      - Traefik Certs Dumper 2.7.4
      - Arm64, ArmV6, ArmV7 build variants added


## 1.1.4 2021-01-05 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.6


## 1.1.3 2020-12-10 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.5


## 1.1.2 2020-12-03 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.4


## 1.1.1 2020-10-25 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.2


## 1.1.0 2020-10-04 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.3.1


## 1.0.18 2020-09-19 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.2.11


## 1.0.17 2020-08-30 <dave at tiredofit dot ca>

   ### Changed
      - Bugfix to 1.0.16


## 1.0.16 2020-08-29 <dave at tiredofit dot ca>

   ### Added
      - Add more features for Traefik Certificate Dumping


## 1.0.15 2020-08-19 <dave at tiredofit dot ca>

   ### Changed
      - Fix for SETUP_TYPE=MANUAL not actually skipping writing parts of configuration file


## 1.0.14 2020-07-30 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.2.8


## 1.0.13 2020-07-20 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.2.6


## 1.0.12 2020-07-15 <dave at tiredofit dot ca>

   ### Changed
      - Fix missing default variables


## 1.0.11 2020-07-09 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.2.3

   ### Changed
      - Code Cleanup


## 1.0.10 2020-06-20 <dave at tiredofit dot ca>

   ### Changed
      - Patchup to support reading both defaults and functions at runtime


## 1.0.9 2020-06-05 <dave at tiredofit dot ca>

   ### Changed
      - Move /etc/s6/services to /etc/services.available


## 1.0.8 2020-06-05 <dave at tiredofit dot ca>

   ### Added
      - Added CERTIFICATE_DUMP_POST_HOOK environment variable to execute scripts or commands post Certificate dump


## 1.0.7 2020-05-01 <dave at tiredofit dot ca>

   ### Added
      - Traefik 2.2.1


## 1.0.6 2020-04-23 <dave at tiredofit dot ca>

   ### Changed
      - Fix to allow various variables that allow multiple values to allow single values


## 1.0.5 2020-04-23 <dave at tiredofit dot ca>

   ### Added
      - Introduce TLS Curve Preferences


## 1.0.4 2020-04-23 <dave at tiredofit dot ca>

   ### Changed
      - Tweak TLS Configuration


## 1.0.3 2020-04-23 <dave at tiredofit dot ca>

   ### Changed
      - Tweak to make HTTP to HTTPS redirection function properly


## 1.0.2 2020-04-23 <dave at tiredofit dot ca>

   ### Changed
      - Cleanup HTTP and HTTPS Middlewares


## 1.0.1 2020-04-23 <dave at tiredofit dot ca>

   ### Changed
      - Patchup to Traefik Certificate Dumper exported path


## 1.0.0 2020-04-22 <dave at tiredofit dot ca>

   ### Added
      - Completely rewritten configuration generator
      - See README for more details
      - Traefik 2.2.0


## 0.15 2019-11-01 <dave at tiredofit dot ca>

* Add Traefik Migration Tool

## 0.14 2019-11-01 <dave at tiredofit dot ca>

* Traefik 2.0.4

## 0.13 2019-08-27 <dave at tiredofit dot ca>

* Traefik 2.0.0GA
* Still working on Dynamic Configuration

## 0.12 2019-08-27 <dave at tiredofit dot ca>

* Traefik 2.0rc1

## 0.11 2019-07-27 <dave at tiredofit dot ca>

* WIP on rewriting configuration builder
* Traefik 2.0beta1

## 0.10 2019-07-09 <dave at tiredofit dot ca>

* Change Logrotate functionality

## 0.9 2019-07-02 <dave at tiredofit dot ca>

* Alpine 3.10
* Traefik 2.0alpha8

## 0.8.4 2019-05-09 <dave at tiredofit dot ca>

* More Zabbix Metrics

## 0.8.3 2019-05-07 <dave at tiredofit dot ca>

* More Zabbix Metrics

## 0.8.2 2019-05-06 <dave at tiredofit dot ca>

* More Zabbix Metrics

## 0.8.1 2019-05-04 <dave at tiredofit dot ca>

* Zabbix Patchup

## 0.8 2019-05-04 <dave at tiredofit dot ca>

* Add Zabbix Monitoring Template and script

## 0.7 2019-05-02 <dave at tiredofit dot ca>

* Fix for Logrotate not creating new file

## 0.6 2019-04-30 <dave at tiredofit dot ca>

* Fix for DNS Resolvers when validating against Letsencrypt
* Change LETSENCRYPT_DYNAMIC_GENERATE to LETSENCRYPT_ONHOST_GENERATE (Default: True) and LETSENCRYPT_ONDEMAND_GENERATE (Default: False)
* Cleanup of code

## 0.5 2019-04-30 <dave at tiredofit dot ca>

* Fix Dashboard Authentication and Display

## 0.4 2019-04-30 <dave at tiredofit dot ca>

* Add logrotation

## 0.3 2019-04-30 <dave at tiredofit dot ca>

* Add LetsEncrypt Capabilities
* Add Compression
* Write Documentation

## 0.2 2019-04-28 <dave at tiredofit dot ca>

* Add Traefik Certs Dumper
* Add REST Capabilities
* Protect Dashboard with Authentication
* HTTP/HTTPS Proxy Protocol and Trusted IPs
* HTTPS Upgrade Support

## 0.1 2019-04-28 <dave at tiredofit dot ca>

* Initial Release
* Alpine 3.9
* Traefik 2.0 Alpha
