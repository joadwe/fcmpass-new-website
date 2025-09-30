---
hide:
  - navigation
---

# Changelog

## v5.0.11

### Added

* Support for Bigfoot, CytoFLEX Mosaic, FACSDiscover
* Ability to export Catalogue

### Updated

* Light scatter voltration is no longer tied to Aurora, CytoFLEX, and Quanteon platforms.

## v5.0.10

### Fixes

* Fixed an error that would stop calibration being sucessful if only fluorescent parameters were provided.
* Fixed an error that would cause a datetime issue when importing FCS files from computers with the language not set to English.

## v5.0.9

### Updated

* Window resizing now available in all windows

## v5.0.8

### Fixes

* Login and registration: fixed issue where software would close on first initial activation of license key and issues with returning to login menu when saved login credentials became invalid due to user changes or license expiration.&#x20;
* Fixed error where custom core-shell model names were not being saved to file and a check that all custom-core shell models have unique names.

### Updated

* Light scatter calibration performs check to ensure the correct criteria are met for high-sensitivity flow cytometers to derive the system collection angle

### Added

* Added a default homogenous sphere model for enveloped viruses
* Added link to EULA in startup screen menu&#x20;

## v5.0.7

### Updated

* Licensing server updated. Outdated FCM<sub>PASS</sub> copies downloaded from nano.ccr.cancer.gov/fcmpass will no longer be able to register. All new users should download the most recent version of the software from www.fcm<sub>pass</sub>.com/download
* Intel-based Apple computers are no longer suppported. M-series Apple computer remain supported.

### Fixes

* Fixed error stopping new users from registering.

## v5.0.6

### Added&#x20;

* Support for CytoFLEX nano.fcs file reading

## v5.0.5

### Added&#x20;

* Support for Novocyte .fcs file reading

## v5.0.4

### Added&#x20;

* Documentation links added to software under ’help" in main menu bar.
* License agreement added to interface
* Account logout added to preferences

### Updated

* Software terms and conditions updated.&#x20;
* Support addresses and links updated.&#x20;
* Software licensing libraries updated to Cryptlex 3.26
