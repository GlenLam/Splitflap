# Change log

## [Version 1.1.1](https://github.com/yannickl/Splitflap/releases/tag/1.1.1)
Released on 2015-12-14.

- [FIX] flap animation continue when new text is set [#2](https://github.com/yannickl/Splitflap/issues/2)

## [Version 1.1.0](https://github.com/yannickl/Splitflap/releases/tag/1.1.0)
Released on 2015-11-27.

- [ADD] `TwelveHourClock`, `TwentyFourHourClock` and `MinuteAndSecond` tokens
- [ADD] tvOS supports
- [FIX] Keep text displayed when reload data

## [Version 1.0.1](https://github.com/yannickl/Splitflap/releases/tag/1.0.1)
Released on 2015-11-17.

- [FIX] Builder properties access control ([#1](https://github.com/yannickl/Splitflap/issues/1))

## [Version 1.0.0](https://github.com/yannickl/Splitflap/releases/tag/1.0.0)
Released on 2015-11-13.

- [UPDATE] Rename `supportedTokensInSplitflap:` method to `tokensInSplitflap:`
- [ADD] `setText:animated:completionBlock:` method to know when an animation finished
- [ADD] Test cases

## [Version 0.2.0](https://github.com/yannickl/Splitflap/releases/tag/0.2.0)
Released on 2015-11-12.

- [FIX] Parse characters and words
- [ADD] `FlapViewBuilder` to make flap configuration easier
- [ADD] `splitflap:builderForFlapAtIndex:` method to customize the each flap individually:
  - `backgroundColor`, `cornerRadius`, `font`, `textAlignment`, `textColor`, `lineColor`

## [Version 0.1.0](https://github.com/yannickl/Splitflap/releases/tag/0.1.0)
Released on 2015-11-11.

- `flapSpacing` property to configure the spacing between flaps
- `supportedTokensInSplitflap:` method to define the "characters" used by flaps
- `numberOfFlapsInSplitflap:` to set the number of flaps
- `splitflap(splitflap:rotationDurationForFlapAtIndex:` method to change the rotation duration of each flaps
- Cocoapods support
- Carthage support
