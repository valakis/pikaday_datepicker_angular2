# Changelog

## 2.2.0 - 2017-09-15

- fixed the min-, max-, and date-setting after translation to js
- deprecated this package, use the new pikaday_datepicker_angular instead

## 2.1.4 - 2017-06-05

- directly link to the pikaday_dart_helpers.js file from packages/pikaday/

## 2.1.3 - 2017-06-05

- forgot to activate the right transformers in 2.1.2

## 2.1.2 - 2017-06-05

- fixed an issue where the selected date wasn't of type DateTime
(when compiled to js) but Date. Unfortunatly you need to import
the file pikaday_dart_helpers.js for now
(until the real issue in package:js is fixed).

## 2.1.1 - 2017-05-22

- updated README.md

## 2.1.0 - 2017-05-22

- change backend dependency from pikaday_datepicker to pikaday
- removed deprecated use of EventEmitter

## 2.0.0 - 2017-05-17

- upgraded to Angular2 version 3.0.0 up

## 1.0.1 - 2017-02-28

- documentation fixes (package path in README.md and HOWTO compile to js)
- blueprint for compile-to-js transformer configuration
  
## 1.0.0 - 2017-01-26

- initial version is the standalone Angular2 Component surrounding the now indipendent
  plain Dart version around the pikaday js-lib.