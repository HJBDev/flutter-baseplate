## [0.1.4] - 29/05/2019

* Removed deprecated Baseplate class. Please now use bpRow and bpCol instead.
* Support for max screen size added

## [0.1.3] - 13/05/2019

* Added Support for `BoxConstraints` for when the widget will be less than the screen width on responsive layouts

## [0.1.2] - 06/02/2019

* Added deprecation notice to Baseplate.row and Baseplate.col methods. Calling via bpRow and bpCol is preferred as these widgets _do_ appear in the inspector.
* Updated example.

## [0.1.1] - 06/02/2019

* Fixed logical error causing padding to display incorrectly when wrapping onto two rows.

## [0.1.0] - 06/02/2019

* Switched to FractionallySizedBoxes to enable nesting of rows. Could break layouts on some devices hence the version increase.

## [0.0.3] - 06/02/2019

* Removed unnecessary named parameters on the row constructor.
* License added.

## [0.0.1] - 06/02/2019.

* Initial Release. See readme.md
