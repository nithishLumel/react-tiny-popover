## [7.2.2] - 2023-02-13

### Fixed

- popover positioning miscalculation issue

## [7.2.1] - 2023-02-11

### Fixed

- blurry popover on non-retina displays (thanks @D34THWINGS)
- click-outside support now works across different windows (thanks @dutziworks)

## [7.2.0] - 2021-08-24

### Added

- added `clickOutsideCapture` prop to `Popover`

## [7.1.0] - 2021-08-24

### Added

- added `violations` property to `PopoverState`
- added `hasViolations` property to `PopoverState`
- React 18 is now an accepted peer dependency

### Changed

- `onClickOutside` now uses event capturing (thanks @davidjgross)

### Fixed

- `usePopover` now returns immediately when popover is not open, fixing an issue where utility and positioning functions sometimes fired even when popover was not open

## [7.0.1] - 2021-08-24

### Fixed

- Issue where popovers within a new stacking context would sometimes not render at the correct position

## [7.0.0] - 2021-08-24

### Added

- SSR support
- `boundaryElement` prop

### Changed

- Renamed `containerParent` to `parentElement`

### Fixed

- Popovers not rendering at proper location within translated container elements

## [6.0.10] - 2021-08-04

### Changed

- Removed `custom` string type from `position` and `align` props, replaced with `undefined`
- `useArrowContainer` does not render an arrow if `position` is `undefined`

## [6.0.9] - 2021-08-02

### Fixed

- `ArrowContainer` now handles custom class names properly (thanks KWLEvans)

## [6.0.8] - 2021-08-02

### Changed

- Inline source maps
