# Changelog
All notable changes to this project will be documented in this file.

## [Unreleased] - 2021-09-23
- Changed: invalid characters from pdf files are converted to utf-8
- Changed: added support for symfony/config:^5.0
- Fixed: exception when indexing a pdf not working (will now only show up in dev mode)
- Fixed: missing symfony dependencies

## [2.6.0] - 2021-03-12
- raised minimum smalot/pdfparser version to 0.18.2

## [2.5.2] - 2021-02-02
- allow smalot/pdfparser 0.18
- add github issue template

## [2.5.1] - 2021-01-28
- made filterPages non-mandatory

## [2.4.1] - 2020-06-03
- fixed exception when reject reason has no response

## [2.4.0] - 2020-06-02
- added BeforeGetSearchablePagesEvent to RebuildSearchIndexCommand
- added option to log search terms

## [2.3.0] - 2020-05-29
* added `valid_word_chars` option to configure keyword count method

## [2.2.0] - 2020-04-22
* added additional logging to search command
* added custom User-Agent of index requests
* fixed disabling search indexing 

## [2.1.0] - 2020-03-17
* added option to set maximum keyword count

## [2.0.2] - 2020-02-18
* respect getSearchablePages hook
* enhanced console output

## [2.0.1] - 2020-02-18
* added missing commands.yml

## [2.0.0] - 2020-02-17
* added RebuildSearchIndexCommand
* added disable search index option
* [BC BREAK] Renamed bundle class

## [1.1.2] - 2020-01-08
* adapted to coding standards

## [1.1.1] - 2019-11-06

* moved RelatedSearchLinkElement to the correct namespace
* renamed RelatedSearchElement to RelatedSearchLinkElement
* fixed related search element templates

## [1.1.0] - 2019-11-06

* added related search link content element

## [1.0.0] - 2019-11-06

First release
