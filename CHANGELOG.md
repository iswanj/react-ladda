# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [5.0.1] - 2016-09-22
### Changed
- Support `react@15.x.x`

## [5.0.0] - 2016-09-17
### Changed
- Refactor
- Use Babel/ES7 for compilation
- Fixed React warning described in #36
- Changed prop names to the actual [data attributes that Ladda uses](https://github.com/hakimel/Ladda#html)

## [4.0.0] - ?

## [3.0.0] - 2015-07-11
### Changed
- New props for `LaddaButton` that do not collide with existing element props (`buttonStyle` instead of `style`)
- Gave `LaddaButton` ownership of the `button` component. Any props applied to the `LaddaButton` are applied to the wrapped `button`. The children of the `LaddaButton` are rendered inside `ladda-label`.
