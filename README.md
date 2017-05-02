# auxclick
This repository contained a [proposed specification](https://wicg.github.io/auxclick/) for a new MouseEvent called auxclick for non-primary buttons as the counterpart of click event which is restricted to the primary button.

As the incubation around this API was successful and the feature was shipped by multiple browsers the API moved to the [W3C UIEvents specification](https://w3c.github.io/uievents/#event-type-auxclick), as maintained by the Web Platform Working Group.

## References
* [WICG Discourse thread](https://discourse.wicg.io/t/new-event-for-non-primary-button-click/1527)
* [Chrome shipping status](https://www.chromestatus.com/feature/5663174342737920) and ["Intent to ship" thread](https://groups.google.com/a/chromium.org/forum/#!topic/blink-dev/R8OehqGJzt0).  Shipped in Chrome 55.
* [Mozilla bug](https://bugzilla.mozilla.org/show_bug.cgi?id=1304044) - shipping in Firerfox 53.
* Related [WebKit bug](https://bugs.webkit.org/show_bug.cgi?id=22382) - no public plans to ship.
