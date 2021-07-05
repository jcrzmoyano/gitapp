# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.2.1] - 2021-07-05

## Fixed

-   Agrega test RECHAZA NEGATIVO que fue borrado accidentalmente 
-   Arregla Test que Verifica los signos 

## [1.2.0] - 2021-06-20

### Added

-   Se agrega signos a los montos.  
-   Se agrega validacion para evitar recibir montos negativos al crear un movimiento. 

## Fixed

-   Se corrige el formato decimal de los montos.  

## [1.1.0] - 2021-06-20

### Added

-   Alerta al crear un movimiento

## Fixed

-   Refresca la página a la hora de agregar un movimiento
-   Arregla headers en "Resumen"

## [1.0.1] - 2021-05-03

### Added

-   Cypress detection for running tests on memory
-   Cypress seed before each cypress test

### Changed

-   Creates tables on server init and avoids erase on shutdown

### Removed

-   Cypress experimental configuration

## [1.0.0] - 2021-04-26

### Added

-   Movements API
-   Home UI with charts and last movements
-   Incomes UI with last incomes

[unreleased]: https://github.com/jcrzmoyano/gitapp/compare/v1.1.0...HEAD
[1.2.1]: https://github.com/jcrzmoyano/gitapp/releases/tag/v1.2.1
[1.2.0]: https://github.com/jcrzmoyano/gitapp/releases/tag/v1.2.0
[1.1.0]: https://github.com/jcrzmoyano/gitapp/releases/tag/v1.1.0
[1.0.1]: https://github.com/jcrzmoyano/gitapp/releases/tag/v1.0.1
[1.0.0]: https://github.com/jcrzmoyano/gitapp/releases/tag/v1.0.0
