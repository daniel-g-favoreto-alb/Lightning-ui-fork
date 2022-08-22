# Changelog

## v1.3.0

*22 aug 2022*

- Added Stepper component
- Added ProgressBar component
- Added ColorShift component for color accessibility

## v1.2.8

*9 aug 2022*

- Fixed bug where transition is not reset when the CollectionWrapper is cleared.

## v1.2.7

*18 jul 2022*

- Fixed bug where the width is not calculated when arrow functions (for example; w => w) are used in the template

## v1.2.6

*13 may 2022*

- The Keyboard component now sends more data when firing signals.

## v1.2.5

*25 apr 2022*

- Fixed bug where Carousel cleans up too many ItemWrappers

## v1.2.4

*11 apr 2022*

- Fixed refactor bug in ScrollingLabel
- Fixed autoStart setter / getter not working in ScrollingLabel

## v1.2.3

*8 apr 2022*

- Fixed bug where ItemWrappers are misplaced when navigating too fast in Carousel

## v1.2.2

*30 mar 2022*

- Fixed bug where previous ItemWrapper data is not cleared when the Grid is cleared

## v1.2.1

*21 mar 2022*

- Added wrap around feature to Keyboard
- Fixed bug where start position is not correct in the InputField

## v1.2.0

*25 nov 2021*

- Added a ScrollingLabel component
- Fixed bug in InputField component where cursor is not in the right position

## v1.1.7

*23 nov 2021*

- Added forceLoad feature to the CollectionWrapper

## v1.1.6

*10 nov 2021*

- Fixed bug where maxCharacters are not checked properly in Keyboard
- Fixed bug in navigation calculation resulting in incorrect focus
- Keyboard now resets focus when switching input components
- Added password mode to InputField
- Added auto hide cursore feature to InputField

## v1.1.5

*25 oct 2021*

- Fixed bug where scroll value is incorrect when CollectionWrapper is inactive.

## v1.1.4

*13 oct 2021*

- Fixed parameters for previous navigation Keyboard component.

## v1.1.3

*13 oct 2021*

- Fixed bug where KeyWrapper does not update or respawns the key properly.
- Fixed navigation over rows Keyboard component
- Fixed onInputChanged signal firing when max characters reached Keyboard component
- Added getter and setter for the label tag in Key component

## v1.1.0

*11 oct 2021*

- Released Keyboard component
- Released Key component
- Released InputField component
- Added related docs

## v1.0.10

*24 sep 2021*

- Fixed bug where Grid sets index when target index is the same as current index

## v1.0.9

*15 sep 2021*

- Fixed scroll transition value when CollectionWrapper is inactive
- Fixed navigation issue when navigating up or down

## v1.0.8

*12 jul 2021*

- Fixed bug where items are not position correctly when reposition function is called
- Added margin data to ItemWrapper

## v1.0.7

*5 jul 2021*

- Added feature where the CollectionWrapper returns the component instead of data when the related component is spawned.
- Fixed refactor issue in CollectionWrapper

## v1.0.5

*30 jun 2021*

- Fixed issue where Carousel required a margin to position its items correctly
- Fixed scroll issue in CollectionWrapper

## v1.0.3

*22 jun 2021*

- Fixed setIndex function in Carousel

## v1.0.2

*10 jun 2021*

- Fixed scroll and plot functions Carousel






