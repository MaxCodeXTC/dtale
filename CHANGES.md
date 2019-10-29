Changelog

### 1.0.0 (2019-09-06)

  * Initial public release

### 1.1.0 (2019-10-08)

  * IE support
  * **Describe** & **About** popups
  * Custom CLI support

### 1.1.1 (2019-10-23)

  * [#13](https://github.com/manahl/dtale/issues/13): fix for auto-detection of column widths for strings and floats

### 1.2.0 (2019-10-24)

  * [#20](https://github.com/manahl/dtale/issues/13): fix for data being overriden with each new instance
  * [#21](https://github.com/manahl/dtale/issues/13): fix for displaying timestamps if they exist
  * calling `show()` now returns an object which can alter the state of a process
    * accessing/altering state through the `data` property 
    * shutting down a process using the `kill()` function

### 1.3.0 (2019-10-29)
  * `webbrowser` integration (the ability to automatically open a webbrowser upon calling `dtale.show()`)
  * flag for hiding the "Shutdown" button for long-running demos
  * "Instances" navigator popup for viewing all activate D-Tale instances for the current python process