---
title: "Snackbar"
date: 2019-09-30T11:05:36-05:00
description: Used for displaying in place and immediate feedback.
---
## Used for displaying in place and immediate feedback.
Appears at the bottom of the screen for a short period of time and then disappears.

![The snackbar](/component/images/snackbar.png?classes=border)

### Include the element in your layout file:
{{% notice note %}}The element is already included in the standard TouchPoint layout.{{% /notice %}}

```<div class="snackbar"></div>```

### Include the script:
{{% notice note %}}The script is already included in the standard TouchPoint layout.{{% /notice %}}

```@Fingerprint.Script("/Content/touchpoint/js/snackbar.js")```

### Call the snackbar programatically:

`snackbar(message, type, duration)`

### Arguments

* message - Text to be displayed
* type - A bootstrap contextual class (one of `success`, `warning`, `danger`)
* duration - Optional, defaults to 2000. The time to display in ms


