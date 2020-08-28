---
title: HMI.WebBrowser.show
supported:
  - 2
  - 3
  - 4
type: event
---
Event triggered when focus is on the WebPortal browser.

### EXAMPLE

```javascript
try {
	// HMI.WebBrowser
	if ((typeof HMI !== "undefined") && (typeof HMI.WebBrowser !== "undefined") && (typeof HMI.WebBrowser.addEventListener !== "undefined")) {
		HMI.WebBrowser.addEventListener("show", function(){
			alert("The browser is back in focus");
		});
	}
} catch(e) {
	DealWithHMIWebBrowserError(e);
}
```

*Appeared in Software version 30.11.04.10*