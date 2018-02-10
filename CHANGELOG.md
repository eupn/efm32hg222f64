# Change Log

All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## v0.2.0 - 2018.02.10

- Refactored GPIO ports. Replaced separate repeating bit fields sctructures `pa_`, `pb_`, ..., `pf_` by single array `ports[GPIO_PORT; 7usize]`

## v0.1.1 - 2018-02-09

- Changed Cargo.toml

## v0.1.0 - 2018-02-09

- Initial release
