# Revision history for ukrainian-phonetics-basic

## 0.1.0.0 -- 2020-10-21

* First version. Released on an unsuspecting world.

## 0.1.1.0 -- 2020-10-22

* First version revised A. Fixed issue with existence of multi-vowel syllables in the module Languages.Phonetic.Ukrainian.Syllable.
.
## 0.1.2.0 -- 2020-10-24

* First version revised B. Added a new function convertToProperUkrainianX to the Melodics.Ukrainian module to get the boxed Vector of Char's.

## 0.1.3.0 -- 2020-10-24

* First version revised C. Added a new function convertToProperUkrainianS to the module Melodics.ByteString.Ukrainian that is needed in some other cases.

## 0.1.4.0 -- 2020-10-26

* First version revised D. Added new functions that convert from Data.Vector.Vector Char to the representation in the Melodics.ByteString.Ukrainian module.

## 0.1.5.0 -- 2020-10-27

* First version revised E. Added two new functions to the module Languages.Phonetics.Ukrainian.Syllable to work with Data.Vector.Vector of Char.

## 0.1.6.0 -- 2020-10-28

* First version revised F. Fixed some issues with palatalization and some combinations that were not properly handled.

## 0.1.7.0 -- 2020-10-28

* First version revised G. Fixed some issues with empty ByteString in the Melodics.ByteString.Ukrainian module.

## 0.1.8.0 -- 2020-11-05

* First version revised H. Fixed issues with classification functions inside the Melodics.ByteString.Ukrainian module. Changed the dependencies boundaries to
use the latest improved versions of the packages.

## 0.1.9.0 -- 2020-11-05

* First version revised I. Fixed issues with separating soft sign from the processed sound combinations inside the Melodics.ByteString.Ukrainian module.

## 0.1.10.0 -- 2020-11-06

* First version revised J. Fixed issues with rare complex letter combinations in the Melodics.ByteString.Ukrainian module. The applyChanges uses now strict in the accumulator
version of the foldr -- foldr'.

## 0.1.11.0 -- 2020-11-06

* First version revised K. Some code improvements to do it more flexible in the module Melodics.ByteString.Ukrainian. Switched to the lazy version of the
foldr in the applyChanges function.

## 0.2.0.0 -- 2020-11-07

* Second version. Added new variants of the uzpp2Durat1 and syllableDurations functions, obtained from the execution of the pldUkr from the
r-glpk-phonetic-languages-ukrainian-durations package.

## 0.2.0.1 -- 2020-11-09

* Second version revised A. Some documentation improvements.

## 0.2.0.2 -- 2020-11-10

* Second version revised B. Fixed issue with inexact documentation.

## 0.3.0.0 -- 2020-11-25

* Third version. Added new functions to support not only vector-based computations in the Languages.Phonetics.Ukrainian.Syllable module, but also the list-based ones. Added a
new dependency of subG package.

## 0.3.1.0 -- 2020-11-25

* Third version revised A. Removed subG from the dependencies. Some code improvements.

## 0.3.1.1 -- 2020-11-26

* Third version revised B. Some code optimizations in the Languages.Phonetics.Ukrainian.Syllable module.

## 0.3.1.2 -- 2020-11-26

* Third version revised C. Some minor code optimization in the Languages.Phonetics.Ukrainian.Syllable module.

## 0.3.2.0 -- 2020-12-03

* Third version revised D. Added a new variant of the uzpp2 to float conversion function to the
Languages.Phonetics.Ukrainian.Syllable module.

## 0.4.0.0 -- 2020-12-05

* Fourth version. Added a new module Languages.Phonetic.Ukrainian.Syllable.Double with the functionality based on Double.

## 0.4.1.0 -- 2020-12-05

* Fourth version revised A. Fixed issue with being not imported properly of the dependency module.
