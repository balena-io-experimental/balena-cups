# Changelog for balenaPrint

All entries are made manually. This project adheres to [Semantic Versioning](http://semver.org/).

## 6.3.0 - 2021-11-7
- TLC on various repo artifacts [willswire]
- Update to support balenaFleets [willswire]

## 6.2.0 - 2021-1-27
- Rename project to balenaPrint [willswire]
- Added balena.yml file for baleneHub [willswire]

## 6.1.0 - 2020-5-24
- Add autoconfiguration of HP network printers [headlesscow]

## 6.0.1 - 2020-4-2
- Change ordering of listen directive to fix support for Android [rahul-thakoor]

## 6.0.0 - 2020-3-31
- Use Dockerfile.template [rahul-thakoor]
- Added support for foomatic drivers [rahul-thakoor]
- Allow remote access [rahul-thakoor]
- Startup message [rahul-thakoor]
- Broadened support for HP Printers [rahul-thakoor]
- Added support for Brother laser printers [Trond Viggo Håpnes]

## 5.1.0 - 2019-5-5
- Remove Port 631 from cupsd.conf

## 5.0.0 - 2019-5-3

- Remove Avahi (utilizing balenaOS instance)
- Filter IP traffic based on source (enable public device URL)
- Introduce `docker-compose` file to ensure DBUS connectivity
- Add volume and mount to /etc/cups/ for persistence of configuration files
- Verified AirPrint working configuration with Enterprise networks
- Visibility on iOS devices

## 4.1.0 - 2019-5-3

- Remove unused avahi-discover package
- Enable USB functionality

## 4.0.0 - 2019-5-3

- Incorporate custom cupsd.conf for access via public device url

## 3.0.0 - 2019-4-10

- Reduce to single container

## 2.0.0 - 2019-1-18

- Rewrite services into two separate applications
- Enable avahi service to be dependant on running cups instance
- Assign persistent volumes for config files for avahi and cups
- Better performance, better pizza, papa johns

## 1.0.0 - 2019-1-18

- Official Release [Will Walker]
