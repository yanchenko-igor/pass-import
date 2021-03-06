# Changes By Release

All the releases are signed using the GPG key
[`06A26D531D56C42D66805049C5469996F0DF68EC`](https://pujol.io/keys/)

## 2.2 - 2018-03-18

* Add support for 1PIF file #36.
* Important clean-up & code improvement #34.
* Pwsafe: add support for:
  - Multiline notes #29,
  - Password history #30,
  - Email #32.
* Do not remove protocol in url #31.
* Update chrome CSV format for Chrome 66 #26 & #27.
* Update 1password format #23 & #28.
* Fix typos & improve code coverage.

## 2.1 - 2017-12-21

* Fix typos #22.
* Add support for bitwarden #19.
* Fix a lot of python linter errors.
* Improve installation documentation.

## 2.0 - 2017-12-03

`pass-import` now natively supports import from other password manager and
therefore, it does not require the importer scripts any-more. Moreover, all the
importer's systems have been intensely tested against a test database.

**pass-import now supports the following 17 password managers:**
* 1password6
* 1password4
* chrome
* dashlane
* enpass
* fpm
* gorilla
* kedpm
* keepass
* keepasscsv
* keepassx
* keepassxc
* lastpass
* passwordexporter
* pwsafe
* revelation
* roboform

## 1.0 - 2017-12-01

* KDE wallet: unicode bugfix #16.

## 0.2 - 2017-09-15

* keepass2csv: add username and do not add empty lines #13.
* Add Enpass #9.
* Lastpass: Ensure UTF-8 encoding #5.
* Add Chrome importer #3.

## 0.1 - 2017-09-01

* Initial release.
