# PHP Loose Typing Bug

This repository demonstrates a common issue in PHP related to loose typing and how it can lead to unexpected results when dealing with `null` and `undefined` values.

The `bug.php` file contains a function that attempts to handle a null value gracefully.  However, if an undefined value is passed, it results in `NaN`. This highlights the importance of robust input validation in PHP to prevent unexpected behavior and errors.